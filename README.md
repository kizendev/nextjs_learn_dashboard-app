# Next.js App Router Course

Full stack application created following the [Next.js App Router Course](https://nextjs.org/learn) on the Next.js website.

## Some Notes

The following notes are information about what I learned, did differently, and extra tips from yours truly.

### Creating the starter template

I used this command instead of the one provided in the course to create the starter template. This is because I use `pnpm` instead of `npm`.

```bash
pnpm create next-app@latest . --use-pnpm --example "https://github.com/vercel/next-learn/tree/main/dashboard/starter-example"
```

### Development in the local network

I find myself wanting to actively check the app on my phone while developing, as such, I've added the following script to the `package.json`.

```bash
    "devnet": "next dev -p 3000 -H 192.168.0.5",
```

The address may vary, to find out your local network address, run the following command in the terminal and look for the `IPv4 Address`.

```bash
ipconfig
```
