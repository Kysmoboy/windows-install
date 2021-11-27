# After fresh windows install
The few things to do after my windows installation. :coffee:

## Packages to get with chocolatey 
> If you do not have chocolatey, put this in powershell (run as admin):
`Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))`

- Put this in powershell (win key + x, a):
  - `choco upgrade all`
  - `choco install brave thunderbird keepassxc vlc 7zip.install xnviewmp ccleaner tor-browser filezilla sharex steam discord qbittorrent transgui kitty sumatrapdf crystaldiskinfo crystaldiskmark protonmailbridge spotify osu telegram openvpn voicemeeter treesizefree rufus virtualbox libreoffice-fresh lghub -y`
