# asls

List networks related to a given AS number, or IP address.

In theory, you should be able to watch for regular expressions in your webserver
(or whatever) logs, grep suspicious ones, pipe them to `asls`, then either add
rules to your firewall, or directives to your webserver configuration, ...

In practice, give it a try:
```
syn@toto:~$ asls 82.237.197.108/24
62.147.0.0/16
78.192.0.0/10
81.56.0.0/15
82.64.0.0/14
82.142.0.0/18
82.224.0.0/11
83.152.0.0/13
83.214.0.0/16
88.120.0.0/13
88.160.0.0/11
91.160.0.0/12
212.27.32.0/19
213.36.0.0/16
213.228.0.0/18
```
