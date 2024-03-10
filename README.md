<div>
  <h3 align="center">A full stack Threads Clone, Chirp</h3>
</div>

## Description

Chirp is a full-stack web application designed to replicate the core functionality of Twitter. With features like posting chirps (tweets), replying to chirps, sharing, liking, and tagging other users, Chirp provides a familiar social media experience while also offering unique functionalities. The project emphasizes user interaction, community building, and seamless authentication.

## Tech Stack

- Next.js
- MongoDB
- Shadcn UI
- TailwindCSS
- Clerk
- Webhooks
- Serverless APIs
- React Hook Form
- Zod
- TypeScript

## Features

 **Authentication**: Authentication using Clerk for email, password, and social logins (Google and GitHub) with a comprehensive profile management system.

 **Chirping**: Users can compose and post chirps, sharing their thoughts, opinions, or updates with their followers and the wider community.

 **Replying**:  Chirp enables users to engage in conversations by replying to chirps, fostering discussions and interactions.

 **Sharing**: Users have the option to share chirps they find interesting or noteworthy, amplifying their reach within the platform.

 **Liking**: Similar to Twitter's "Like" functionality, users can express their appreciation for chirps by liking them.

 **Tagging**: Chirp allows users to tag other users in their chirps, facilitating direct communication and engagement.

 **User Profiles**:  After authentication, users can create and customize their profiles, providing personal information, interests, and a bio to enhance their presence on the platform.

 **Community Building**: Chirp encourages users to form communities based on shared interests, fostering connections and interactions among like-minded individuals.

## Quick Start

Follow these steps to set up the project locally on your machine.

**Prerequisites**

Make sure you have the following installed on your machine:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/) (Node Package Manager)

**Cloning the Repository**

```bash
git clone https://github.com/EishaH/chirp.git
```

**Installation**

Install the project dependencies using npm:

```bash
npm install
```

**Set Up Environment Variables**

Create a new file named `.env.local` in the root of your project and add the following content:

```env
MONGODB_URL=
CLERK_SECRET_KEY=
UPLOADTHING_SECRET=
UPLOADTHING_APP_ID=
NEXT_CLERK_WEBHOOK_SECRET=
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
```

Replace the placeholder values with your actual credentials. You can obtain these credentials by signing up for the corresponding websites on [MongoDB](https://www.mongodb.com/), [Clerk](https://clerk.com/), and [Uploadthing](https://uploadthing.com/). 

**Running the Project**

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to view the project.

