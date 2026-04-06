## Some Projects:

- [`manus-mortis`](https://github.com/gavin-lb/manus-mortis): A fullstack discord app and web portal built for [gadget.dev](https://gadget.dev/) serverless architecture.
   - Backend discord bot API written in TypeScript running on Node with Fastify:
     - Bespoke ticketing and application system handling thousands of end users,
     - Various custom features including: reward point system with leaderboards, user call-to-action system, customisable welcome message system,
     - Adheres as close as possible to RESTful design principles by using Discord interaction endpoint API wherever possible.
   - Frontend React web portal in Remix framework:
     - Implements OAuth2 login system,
     - Supports full configuration of all bot features via modern interfaces built with Polaris and Shadcn components.

 - [`vue3-flag-icons`](https://github.com/gavin-lb/vue3-flag-icons): A TypeScript-compatible Vue3 component library for providing flag icons.
   -  Full TypeScript support with types generated from a dependency by a custom script,
   -  Built with Vite,
   -  [Published to NPM](https://www.npmjs.com/package/vue3-flag-icons) with over 1000 weekly downloads.

- `grape-chess`: a (currently private) fullstack chess webapp project. 

  - Front end written in TypeScript in Vue3 framework:
    - SPA that uses the Vue Router, 
    - Utilises Vuetify library for UI components,
    - Uses vue3-chessboard package:
      - a Vue3 component library of which [I am a contributor](https://github.com/qwerty084/vue3-chessboard/commits?author=gavin-lb),
      - which utilises the chess.js package of which [I am a contributor](https://github.com/jhlywa/chess.js/commits?author=gavin-lb).
     
  - Backend written in Python using FastAPI:
    - Implements a RESTful API,
    - Uses SocketIO protocol for WebSocket connections with the frontend,
    - Uses SQLAlchemy for database handling of user and game data.
