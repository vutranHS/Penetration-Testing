- dirb - dirb http://192.168.1.5/dvwa
- dirsearch -  	./dirsearch.py –u http://192.18.1.5/dvwa -e php -f -x 400,403,404
- dir buster
- nikto
- Aquatone
- Wfuzz - wfuzz -c -W /usr/share/wfuzz/wordlist/dir/common.txt --hc 400,404,403 http://192.168.1.5/dvwa/FUZZ
- Metasploit - use auxiliary/scanner/http/dir_scanner  
- burp intruder
- subBrute
- metagoofile
___________________________________________________________________________________________________________________________________
Tools

DirBuster - https://sourceforge.net/projects/dirbuster/

dirb - http://dirb.sourceforge.net/

ilebuster - https://github.com/henshin/filebuster

gobuster - https://github.com/OJ/gobuster

dirsearch - https://github.com/maurosoria/dirsearch
