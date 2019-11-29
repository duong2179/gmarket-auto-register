# gmarket-auto-register
For people living in South Korea and often buy items on [Gmarket](http://gmarket.co.kr/)

### How
+ Accept `<username>` and `<password>` as input.
+ Use [Mailinator](https://www.mailinator.com/) to register an email of `<username>`@`mailinator.com`
+ Register Gmarket account with `<username>` & `<password>` as login credentials.
+ Activate the account via the mailinator email.
+ Receive 30% coupon for the account.
+ That's it. Enjoy shopping on Gmarket with 30% discount!

### Build
```
docker build -t github/duong2179/gmarket-auto-register .
```

### Use
```
docker run -it --rm github/duong2179/gmarket-auto-register <username> <password>
```
