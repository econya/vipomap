# vipomap
braindead shellscript to not forget to run postmap on postfix hash files (call postmap when editor finished).

# adddovecotuser and deldovecotuser
Added from https://help.ubuntu.com/community/PostfixVirtualMailBoxClamSmtpHowto .

# TODO
- options: touch file before it exists
- check return status of editor command, do not make changes if aborted.
- make backup copies, to cover issues with former points.
