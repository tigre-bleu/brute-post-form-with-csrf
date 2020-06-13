# Description

Simple script to make dictionnary attacks on a POST form protected with anti CSRF. The script makes a first request, catches the token then use it to try a password.

# Usage

```
usage: brute-post-form-with-csrf [-h] [-u URL] [-p PASSWORD] [-P PASSWORDS] [-l LOGIN] [-L LOGINS]
                                 [-c CSRF] [-a ADDITIONAL]

optional arguments:
  -h, --help            show this help message and exit
  -u URL, --url URL     post action url
  -p PASSWORD, --password PASSWORD
                        Single password to test
  -P PASSWORDS, --passwords PASSWORDS
                        Passwords wordlist file
  -l LOGIN, --login LOGIN
                        Single login to test
  -L LOGINS, --logins LOGINS
                        Logins wordlist file
  -c CSRF, --csrf CSRF  CSRF token POST parameter name
  -a ADDITIONAL, --additional ADDITIONAL
                        JSON string for additional POST data
```
