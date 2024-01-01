# Prisma Access
## IPSec Tunnel with Prisma Access


### Create a remote network

![](./images/remotenetwork.png)



 
  


### Debug IPSec Tunnel on PAN OS

``` 
debug ike tunnel PrismaAccess on debug 
```
```
debug ike gateway IKEGW on debug  
```
```
tail follow yes mp-log ikemgr.log 
```