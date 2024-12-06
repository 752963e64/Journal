# Wide are network(WAN/DMZ) without the fuckers :D

How to avoid routing your server like dumbass...

## by hand always... so you keep being an athlete!

OKAY I was wrong... :D This damn route processing over complicated software was hard to tame AGAIN.

I'm not learning... I redo what I did longtime ago... hadn't NOTED shit... :D

THis came back at 5h(am) while I was trying to sleep, I was scared to forget it when I wake... hell it didn't. :D

```sh
# ip route add <GATEWAY> dev eth0
# ip route add <RHOST> via <GATEWAY> dev <IFACE>  metric 1 onlink
# ip route del default
```

Now look to your firewall, 0 0 means no paquet these bitches gets "NO ROUTE TO HOST" damn it. :D

```sh
# iptables -t filter -nvL
0     0 LOG        0    --  *      *       0.0.0.0/0            0.0.0.0/0            limit: avg 1/sec burst 5 LOG flags 0 level 4
0     0 DROP       0    --  *      *       0.0.0.0/0            0.0.0.0/0
```

Say goodbye to all your useless filtering... wire up to friend and forget the fuckers...

Enjoy computing quietly and safely.

###### 75293e64@tutanota.com
