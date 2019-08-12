# After fresh windows install
The few things to do after my windows installation. :coffee:

## Packages to get with chocolatey 
> If you do not have chocolatey, put this in cmd.exe (run as admin):
`@"%SystemRoot%\System32\WindowsPowerShell\v1.0\powershell.exe" -NoProfile -InputFormat None -ExecutionPolicy Bypass -Command "iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))" && SET "PATH=%PATH%;%ALLUSERSPROFILE%\chocolatey\bin"`

- Put this in powershell (win key + x, a):
  - `choco upgrade all`
  - `choco install firefox thunderbird keepassxc vlc 7zip.install xnviewmp ccleaner tor-browser filezilla sharex steam discord qbittorrent teamspeak taiga putty sumatrapdf crystaldiskinfo protonmailbridge spotify osu telegram openvpn voicemeeter treesizefree rufus virtualbox`
