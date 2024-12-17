2024-12-17
13:23
#easy #forensics #grep #checksum
## Description

People keep trying to trick my players with imitation flags. I want to make sure they get the real thing! I'm going to provide the SHA-256 hash and a decrypt script to help you know that my flags are legitimate.

## Steps Taken
1. ssh into the machine 
2. ls the directory 
3. run "sha256sum files/* | grep [checksum]"
4. run ./decrypt.sh files/[file].
5. flag: picoCTF{trust_but_verify_e018b574}>)