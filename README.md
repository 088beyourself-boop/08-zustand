# NoteHub

NoteHub is a Next.js application for creating, searching, filtering, viewing,
and deleting notes.

## Features

- Server-side rendering and client-side data fetching with TanStack Query
- Tag filtering with App Router parallel and catch-all routes
- Intercepting route for note previews in a modal
- Dynamic SEO and Open Graph metadata
- Note creation on a dedicated page
- Persistent note drafts with Zustand and localStorage
- Globally optimized Roboto font through `next/font`

## Local development

Install dependencies:

```bash
npm install
```

Create `.env.local` in the project root:

```env
NEXT_PUBLIC_NOTEHUB_TOKEN=your_token
```

Run the development server:

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000).
