This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

---

# Zoon Clone

This project is a clone of Zoon, built using Next.js, TypeScript, and GetStream.

## Description

Zoon Clone is a web application that allows users to discover and share events happening in their local area. Users can browse through various categories of events, view event details, and interact with other users by commenting and liking events.

## Features

- User authentication: Users can sign up, log in, and log out securely.
- Browse events: Users can browse through a list of events categorized by type, location, and date.
- Event details: Users can view detailed information about each event, including date, time, location, and description.
- Comments and likes: Users can interact with events by leaving comments and liking them.
- Real-time updates: The application utilizes GetStream to provide real-time updates on events and user interactions.

## Technologies Used

- Next.js: A React framework for building server-side rendered applications.
- TypeScript: A statically typed superset of JavaScript that enhances code quality and developer productivity.
- GetStream: A scalable and customizable feed API for building activity streams and newsfeeds.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/ijaspreetsinghh/zoom-clone.git
   ```

2. Install dependencies:

   ```bash
   cd zoon-clone
   npm install
   ```

3. Set up environment variables:

   Create a `.env.local` file in the root directory and add the following environment variables:

   ```
   NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
   CLERK_SECRET_KEY=
   NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
   NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
   NEXT_PUBLIC_STREAM_API_KEY=
   STREAM_SECRET_KEY=
   NEXT_PUBLIC_BASE_URL=
   ```

4. Run the development server:

  ```bash
   npm run dev
   # or
   yarn dev
   # or
   pnpm dev
   # or
   bun dev
  ```

5. Open [http://localhost:3000](http://localhost:3000) in your browser to view the application.

## Contributing

Contributions are welcome! Please feel free to open an issue or submit a pull request for any enhancements or bug fixes.

## License

This project is licensed under the [MIT License](LICENSE).
