# Nest

Example [Nest](https://nestjs.com/) app. NestJS is a TypeScript framework for building scalable server-side applications on Node.js.

## Deploy settings

| Field | Value |
| --- | --- |
| Build | Railpack |
| Project directory | `/` |
| Install command | leave empty |
| Build command | leave empty |
| Start command | `npm run start:prod` |
| Application port | `3000` |
| Health check path | `/` |

## <a name="dev"></a>Run locally

```bash
# install dependencies
npm install

# run in development mode with watch
npm run start:dev

# build and run for production
npm run build
npm run start:prod
```

Requires Node.js 24.15 or later (in the 22 branch — 22.22.3 or later).
