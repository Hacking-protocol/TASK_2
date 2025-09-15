# TASK_2
requirements to perform password cracking with hashcat:
1)a list of passwords
2)Their respective hashes in any format e.g. in windows-NTLM in linux-MD5
3)store the hashes in seperate file in this case the hashes.txt
4)now type the following command:
hashcat -a 0 -m 0 hashes.txt passwords.txt
$) the attack mode is straight and mode is md5 hashes cracking
6)just wait for the passwords to be cracked.
