# Kickstart Http server

## Instructions
- Add your free redhat subscription information to the kickstart file.

- Set execute permissions on the script.

```
chmod u+x ks-http.sh
```

- Run the kickstart http server.

```
 ./ks-http.sh
```

- Boot virtual box vm and press tab on boot up screen.

```
inst.ks=http:\\<localipaddress>\ks-min.cfg
```
