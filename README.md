<h1 align="center">
  Stripe Saas Hono
</h1>

Basic Stripe checkout integration using Hono as a backend service.

```
npm install
npm run dev

stripe login
stripe listen -e checkout.session.completed --forward-to http://localhost:3000/webhook
```

```
open http://localhost:3000
```
