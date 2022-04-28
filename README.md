# Domain Records Checker
Go learning project.

Run the program and input some domain to check records.
The program will print out if there are any records.

Run:
```
go run main.go
```

Example output:
```
gmail.com
Domain: gmail.com
MX: true
SPF: true
SPF Record: v=spf1 redirect=_spf.google.com
DMARC: true
DMARC Record: v=DMARC1; p=none; sp=quarantine; rua=mailto:mailauth-reports@google.com
```
