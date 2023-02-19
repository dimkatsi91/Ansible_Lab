#### NOTE: Manually delete/remove the two added rules in the INPUT chain of FILTER Table of IPtables Firewall (if needed | otherwise remove using another ansible as well)

```
iptables -L INPUT --line-numbers
iptables -D INPUT 3
iptables -D INPUT 2
```
