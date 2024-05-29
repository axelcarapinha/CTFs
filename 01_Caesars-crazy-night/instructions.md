# Instructions to enter veracrypt-volume
Author: Gaius Julius Caesar (Database admin)

## (1) Organization of the secret folder
Each line of _hashes.txt_ corresponds to the hash of a user's password, and the flag is in the encrypted Veracrypt volume.
To enter that volume, follow the instructions bellow.

## (2) Entering the Veracrypt volume
1. Get the users passwords (_not_ the hashes)
2. Sort the passwords lexicographically
3. Put everything on a single line, preserving the order mentioned above, from left to right.
4. Remove ANY space that may be left with the previous steps
5. THAT single line is the password to the Veracrypt volume.
5. Mount the volume, decrypt it and you should be able to read its contents!

Disclaimer: the volume was formatted with the filesystem LinuxExt4, so it's _not_ directly supported on Windows.
Trying Linux for daily use is a rewarding adventure, anyways!



 

