# remove_grub_from_win10
Remove GRUB Bootloader from Windows 10

1.<code>Windows Key + R</code> to open Run box and type <code>cmd</code>.<br />
2.Type <code>diskpart</code><br />
3.Type command <code>list vol</code><br />
4.Select EFI/System volume 100 MB with FAT32 format<br />
5.Select by command <code>Select Volume X</code> <br />
6.Assign the letter to volume usign command <code>Assign Letter=X</code> X can be replaced by any letter (Z)<br />
7.Type <code>Exit</code> to close the window<br />
8.Open CMD as an Administration <br />
9.Type <code>Z:</code><br />
10.Type command <code>dir</code><br />
11.Now type <code>cd EFI</code><br />
12.Type <code>dir</code><br />
13.And now you can type <code>rmdir /s <b>OSNAME</b></code><br />
14.Exit the cmd and restart your pc 
