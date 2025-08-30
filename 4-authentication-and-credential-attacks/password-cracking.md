
Use seclists/Names/names.txt for finding names/user enum

Password spraying (crackmapexec, smb, winrm, rdp)

Tools:
John
```shell
--format <hash format>
--wordlist <password list>
john --single --format=sha512crypt hashes.txt

````

Hashcat

```shell
-a 0  # Brute force mode
-m <attack_mode>  # Check hashcat --help for available modes
--force  # For non-native GPU support
--rule <mangling rules>
```
