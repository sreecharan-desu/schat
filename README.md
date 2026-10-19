# schat

realtime chat client on websockets.

## features

- one public chat room over a websocket
- live online-user count
- pairs with [schat-ws-server](https://github.com/sreecharan-desu/schat-ws-server)

## stack

next.js 15 · react 19 · typescript · tailwind css

## run locally

start [schat-ws-server](https://github.com/sreecharan-desu/schat-ws-server) first, then:

```bash
npm install
cp .env.example .env.local
npm run dev
```

## env

copy `.env.example` to `.env.local` and set `NEXT_PUBLIC_WEBSOCKET_URL` (defaults to `ws://localhost:8080`).
