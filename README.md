# kpassman

A password manager that uses gpg to encrypt and decrypt stored passwords and uses kdialog to provide a GUI.  Encrypted passwords are stored in `~/.kpassman`.  After decryption, passwords are copied to the clipboard for 45 seconds using xclip.

Dependencies: gpg, xclip, kdialog, apg (optional - for generating passwords)

![kpassman](/Screenshot.png)

