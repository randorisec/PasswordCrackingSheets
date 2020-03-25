# Password Cracking Sheets
You've got a hash, nice ! But if you can't pass it (PtH) how long will it take to crack it ?
A few seconds if the password is in wordlists (e.g: rockyou) or a bit longer if you use rules but it can take aaaaages if you use bruteforce.

We did a few sheets showing real cracking values (not bench) for NetNTLMv2, NTLM, MD5 and SHA512 with hashcat on a 8 GTX1080 GPU box.

For each sheet:
1. The first line is the number of characters of the plaintext password.
2. The second line is the maximum time the bruteforce will last using the default hashcat mask (https://hashcat.net/wiki/doku.php?id=mask_attack)
3. The third line is the maximum time the bruteforce will last using full charset (avoid this one).

# NetNTLMv2
[![NTLM_crack](https://raw.githubusercontent.com/randorisec/PasswordCrackingSheets/master/netntlmv2_crack.png)](https://raw.githubusercontent.com/randorisec/PasswordCrackingSheets/master/netntlmv2_crack.png)

# NTLM
[![NTLM_crack](https://raw.githubusercontent.com/randorisec/PasswordCrackingSheets/master/ntlm_crack.png)](https://raw.githubusercontent.com/randorisec/PasswordCrackingSheets/master/ntlm_crack.png)

# MD5
[![MD5_crack](https://raw.githubusercontent.com/randorisec/PasswordCrackingSheets/master/md5_crack.png)](https://raw.githubusercontent.com/randorisec/PasswordCrackingSheets/master/md5_crack.png)

# SHA512
[![MD5_crack](https://raw.githubusercontent.com/randorisec/PasswordCrackingSheets/master/sha512_crack.png)](https://raw.githubusercontent.com/randorisec/PasswordCrackingSheets/master/sha512_crack.png)

# License
The Password Cracking Sheets is an open source project released under the [CC-BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/deed.fr) licence.
