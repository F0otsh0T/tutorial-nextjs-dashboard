## Next.js App Router Course - Starter

This is the starter template for the Next.js App Router Course. It contains the starting code for the dashboard application.

For more information, see the [course curriculum](https://nextjs.org/learn) on the Next.js Website.

To start on a different TCP Port:

```shell
ps -eaf | grep 3002
docker ps | grep 3002
netstat -an | grep 3002
```

If no processes or containers are listening on port `:3002`, then start the dashboard service on that port:

```shell
pnpm dev --port 3002
```