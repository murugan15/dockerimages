# escape=`
FROM mcr.microsoft.com/windows/servercore/iis:windowsservercore-ltsc2019
RUN powershell -Command Set-ExecutionPolicy Bypass -Scope Process -Force; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))
RUN powershell choco install -fy dotnetcore --version=2.1.4

