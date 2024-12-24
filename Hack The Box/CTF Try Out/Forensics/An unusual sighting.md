2024-12-23
16:21
#easy #forensics #terminal #nc 

## Description
As the preparations come to an end, and The Fray draws near each day, our newly established team has started work on refactoring the new CMS application for the competition. However, after some time we noticed that a lot of our work mysteriously has been disappearing! We managed to extract the SSH Logs and the Bash History from our dev server in question. The faction that manages to uncover the perpetrator will have a massive bonus come competition!

## Steps Taken
1. download files and nc into machine
2. question 1: find the ip address of the ssh server formatted `ip:port`
3. question 2: find the time of the first login formatted like `YYYY-MM-DD H:M:S`
4. question 3: find the time of the unusual login formatted like `YYYY-MM-DD H:M:S`
5. question 4: find the fingerprint of the attackers public key formatted like `OPkBSs6okUKraq8pYo4XwwBg55QSo210F09FCe1-yj4`
6. question 5 find the first command run by the attacker formatted like ``
7. Flag: ****

## Files
![[forensics_an_unusual_sighting.zip]]