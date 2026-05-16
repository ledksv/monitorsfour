# MonitorsFour — HackTheBox Writeup

**Status: Active — walkthrough locked pending machine retirement.**

Full writeup will be published on [l3dsec.com](https://l3dsec.com) upon retirement.

## Enumeration

```
nmap -sV -sC <TARGET_IP>
nmap -sV -sC <TARGET_IP> -p-

PORT     STATE SERVICE       VERSION
80/tcp   open  http          nginx
|_http-title: MonitorsFour - Networking Solutions
5985/tcp open  http          Microsoft HTTPAPI httpd 2.0 (WinRM)
```

Two ports open: port 80 running nginx (PHP application) and port 5985 running WinRM.

## // remaining sections locked

This machine is still active on HackTheBox. Full walkthrough will be published upon retirement.
