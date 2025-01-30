# setup

## remote db setup

why ? Because I spent a lot of time on docker desktop and mac; but kept getting error
that can't connect to localhost:5432

just signup https://console.aiven.io/signup?referral_code=vmbrar2gvitzv4htn8bo using my referral link and in your .env file use your db url as

```
DATABASE_URL="postgres://avnadmin:<pass>@p<host>:25820/defaultdb?sslmode=require&sslcert=<full path to your ca.pem file>"
```
