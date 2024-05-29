# Getting to know the problem
Attention! Caesar's database was exploited! Well, kind of.
Caesar went to *Queima das Fitas 2024*, at Évora, and you may know what can happen there...

He was challenged to scream the password of his server database in order to gain three free shots. And he did *not* expect that Marcus Brutus was dancing nearby when he screamed that. It was 05:12.

Marcus went home, entered the database (yes, Caesar did _not_ have MFA too) and found three files:
1. instructions.txt
2. hashes.txt
3. veracrypt-volume

Ironically, Marcus Brutus does *not* know anything about hashes, maybe even his cat knows more! But with your help he can learn about them. That's the only way to have the decrypted passwords, follow the instructions, and get the secret flag that Caesar was babbling about the whole night.

Oh, you still have time to find the flag, Caesar just discovered absinthe...


# Task
1. Decrypt the hashes
2. Follow the instructions.txt (to calculate the password of the volume)
3. Decrypt the Veracrypt volume (with the password)
