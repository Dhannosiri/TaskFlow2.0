# TaskFlow 2.0

TaskFlow 2.0 is a minimal setup task management application built using **Next.js 14**, **TypeScript**, **Prisma**, and **Google OAuth** authentication.

## Features
- User authentication via Google OAuth
- Task and project management
- Calendar view for deadlines
- Responsive and user-friendly UI

## Tech Stack
- **Frontend:** Next.js 14, TypeScript, Tailwind CSS
- **Backend:** Next.js API Routes, Prisma ORM
- **Database:** PostgreSQL
- **Authentication:** NextAuth.js with Google OAuth

## Installation

### Prerequisites
- Node.js v18+
- PostgreSQL installed and running
- Google OAuth credentials (Client ID & Secret)

### Steps
1. Clone the repository:
   ```sh
   git clone YOUR_REPOSITORY_URL
   cd TaskFlow2.0
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Set up environment variables:
   - Create a `.env` file in the root directory
   - Add the following:
     ```env
     DATABASE_URL="postgresql://your-username:your-password@localhost:5432/taskflow"
     NEXTAUTH_URL="http://localhost:3000"
     NEXTAUTH_SECRET="your-secret-key"
     GOOGLE_CLIENT_ID="your-google-client-id"
     GOOGLE_CLIENT_SECRET="your-google-client-secret"
     ```
4. Initialize the database:
   ```sh
   npx prisma generate
   npx prisma db push
   ```
5. Start the development server:
   ```sh
   npm run dev
   ```

## Deployment
TaskFlow 2.0 can be deployed on **Vercel** or any platform that supports Next.js.

### Deploy to Vercel
1. Install Vercel CLI:
   ```sh
   npm install -g vercel
   ```
2. Login to Vercel:
   ```sh
   vercel login
   ```
3. Deploy the application:
   ```sh
   vercel
   ```

## Contributing
Feel free to submit pull requests or open issues to improve TaskFlow 2.0!

## Contact
For any queries or suggestions, feel free to reach out.
deshmukhlokesh17@gmail.com gmail only available till year 2030.
