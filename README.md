# kpassman

A password manager that uses gpg to encrypt and decrypt stored passwords and uses kdialog to provide a GUI.  Encrypted passwords are stored in `~/.kpassman`.  After decryption, passwords are copied to the clipboard for 45 seconds using xclip.

Dependencies: gpg, xclip, python3-pyqt5|kdialog, apg (optional - for generating passwords)

Main menu:

![kpassman](/Screenshot.png)

Add password:

![kpassman](/Screenshot2.png)

Decrypt password:

![kpassman](/Screenshot3.png)

Generate passwords using apg:

![kpassman](/Screenshot4.png)
