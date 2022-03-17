# download hashcat for cracking passwords
```bash
$ wget https://hashcat.net/files/hashcat-2.00.7z
```
Install p7zip to extract the archive.
### ubuntu/debian
```bash
$ apt-get install p7zip
```
Select the appropriate binary regarding your system. then copy the file to the standard binary location.
```bash
$ cp hashcat-cli64.bin /usr/bin/
```
create a shorter form.
```bash
$ ln -s /usr/bin/hashcat-cli64.bin /usr/bin/hashcat
```
