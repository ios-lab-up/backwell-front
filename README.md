This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

## Run locally for development

1. Install the dependencies

```bash
npm install
```

2. Run the development server

```bash
npm run dev
```

## Run with Docker for production

1. Build the container

```bash
docker build -t nextjs-docker .
```

2. Run the container

```bash
docker run -p 3000:3000 nextjs-docker
```
