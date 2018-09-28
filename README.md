# Next.js with TypeScript + Nodemon

Deploy it to GAE

```bash
gcloud app deploy
```

## The idea behind the example

The example shows how you can use [TypeScript](https://typescriptlang.com) on both the server and the client while using [Nodemon](https://nodemon.io/) to live reload the server code without affecting the Next.js universal code.
Server entry point is `server/index.ts` in development and `production-server/index.js` in production.
The second directory should be added to `.gitignore`.
