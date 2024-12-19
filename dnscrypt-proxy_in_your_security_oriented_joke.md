# dnscrypt-proxy in your security oriented joke

supervised daemon with bind cap running with system privilege and klogd group attached...

## by hand always... so you keep being an athlete!

That's what I found after installation in alpinelinux :D

```
dnscrypt:x:100:klogd
```

put this in /etc/group instead... all groups down 1000 have system(root) privilege...

```
dnscrypt:x:2000:
```

Don't call yourself security oriented... It's kind of making me laugh out loud.

###### 75293e64@tutanota.com

