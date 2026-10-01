# আহলে কুতুব

আহলে কুতুব is a Bengali digital reading platform for Islamic books.

## Development

Requires Node.js and npm.

```sh
git clone <this-repository-url>
cd <repository-name>
npm i
npm run dev
```

Create a local `.env` file with the Supabase URL and publishable key. Keep
service-role and Cloudflare R2 secret keys server-only.

## Technology

- TanStack Start
- TypeScript
- React
- Tailwind CSS
- Supabase Auth and Database
- PDF.js and IndexedDB

Database schema and manually applied policies are maintained in `supabase/`.
