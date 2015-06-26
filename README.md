# Chocolatey Windows Package Manager » Install Scripts

Chocolatey scripts to help with installation on systems:

  * `choco-install-favorites.bat`: All our favorites in one file.
  * `choco-install-favorites-for-desktop-apps.bat`: E.g. Firefox, LibreOffice, VLC.
  * `choco-install-favorites-for-coding.bat`: E.g. Java, Perl, Python, Ruby.

Typical install using Windows `cmd` with Administrator security:

    PowerShell Invoke-WebRequest
    https://raw.githubusercontent.com/SixArm/sixarm_choco_install/master/choco-install-favorites.bat
    -OutFile choco-install-favorites.bat
