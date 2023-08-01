# Spotify Clone

Based on the original Spotify, this is a web application that lets you create an account, subscribe to a premium plan to upload songs, listen and add them to your favorite playlist. The app is completely responsive and mimics the original Spotify experience. This project is a demonstration of how to use Next.js, TypeScript, Tailwind CSS, Supabase, and Stripe to build a full-stack web application.

## Installation and Usage

To run this project on your own machine you will need to clone the repository, create a Supabase account and Stripe account.

1. Clone this repository: `git clone https://github.com/ErikaJPB/spotify-clone.git`
2. Navigate to the project directory: `cd spotify-clone`
3. Install the dependencies: `npm install`
4. Create a `.env.local` file and add your Supabase and Stripe keys as follows:

```env
NEXT_PUBLIC_SUPABASE_URL=
NEXT_PUBLIC_SUPABASE_ANON_KEY=
SUPABASE_SERVICE_ROLE_KEY=
NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY=
STRIPE_SECRET_KEY=
STRIPE_WEBHOOK_SECRET=
```

5. Run the development server: `npm run dev`
6. Open http://localhost:3000 in your browser to see the app.

## Features

- Authentication with Supabase
- Upload mp3 files with cover albums
- Search bar to find your songs
- Favorite playlist
- Music Streaming
- Stripe subscription using webhooks

## Technologies and Tools

- [Next.js](https://nextjs.org/) - A React framework for hybrid static and server rendering
- [TypeScript](https://www.typescriptlang.org/) - A superset of JavaScript that adds types
- [Tailwind CSS](https://tailwindcss.com/) - A utility-first CSS framework for rapid UI development
- [Supabase](https://supabase.io/) - An open source Firebase alternative that provides authentication, database, storage, and serverless functions
- [Stripe](https://stripe.com/) - A platform for online payment processing
- [Uppbeat](https://uppbeat.io) - A freemium music platform for creators.

## Credits and Acknowledgements

This project was inspired by [this tutorial](https://www.youtube.com/watch?v=2aeMRB8LL4o) by [Antonio Erdeljac](https://github.com/AntonioErdeljac). I would like to thank him for his clear and engaging explanation of how to build a Spotify clone with React.
