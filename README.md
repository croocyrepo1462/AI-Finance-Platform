# AI Finance Platform

An AI-powered full-stack finance platform designed to provide intelligent financial insights and services.

## Overview

This platform integrates advanced AI capabilities with modern web technologies to deliver real-time financial analytics, user-friendly interfaces, and secure data management.

## Features

* AI-driven financial analytics
* User authentication and onboarding
* Real-time data processing
* Responsive UI with Shadcn UI components
* Email notifications and alerts

## Tech Stack

* **Frontend**: Next.js, Tailwind CSS, Shadcn UI
* **Backend**: Supabase, Prisma, Inngest
* **Authentication**: Clerk
* **AI Integration**: Gemini API
* **Email Service**: Resend
* **Security**: ArcJet

## Getting Started

### Prerequisites

* Node.js and npm installed
* Supabase account
* Clerk account for authentication
* Gemini API key
* Resend API key for email services
* ArcJet API key for security(\[GitHub]\[1])

### Installation

1. Clone the repository:(\[GitHub]\[2])

   ```bash
   git clone https://github.com/croocyrepo1462/AI-Finance-Platform.git
   cd AI-Finance-Platform
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Set up environment variables:
   Create a `.env` file in the root directory and add the following variables:

   ```env
   DATABASE_URL=
   DIRECT_URL=

   NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
   CLERK_SECRET_KEY=
   NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
   NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
   NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/onboarding
   NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/onboarding

   GEMINI_API_KEY=

   RESEND_API_KEY=

   ARCJET_KEY=
   ```

4. Run the development server:

   ```bash
   npm run dev
   ```

   Open [http://localhost:3000](http://localhost:3000) in your browser to see the application.

## Folder Structure

* `/app` - Main application components and pages
* `/components` - Reusable UI components
* `/data` - Static data and configurations
* `/emails` - Email templates
* `/hooks` - Custom React hooks
* `/lib` - Utility functions and libraries
* `/prisma` - Prisma schema and migrations
* `/public` - Public assets(\[GitHub]\[1])

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any enhancements or bug fixes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
