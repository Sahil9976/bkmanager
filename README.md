# Project Title

Bookmarks

# Description

This project consists of a dynamic bookmark management application built with React and Next.js. Users can add, edit, remove, and view bookmarks, which are validated for URL format and displayed in a paginated list. Each bookmark entry contains a title and URL, and the list supports navigation through pagination controls. The user interface provides appealing design and error handling, ensuring a user-friendly experience.

## Tech Stack

-   Next.js
-   React
-   Typescript
-   SCSS & SCSS Modules
-   Zustand
-   GSAP
-   ESLint
-   Prettier

## Directory Structure

/src
-   /pages
-   /components
    -   /layout
        -   /header
        -   /footer
    -   /ui
        -   /bookmark
        -   /bookmark-list
        -   /button
        -   /icon
        -   /pagination
        -   /results
        -   /submit-form
-   /hooks
-   /styles
    -   /elements
    -   /objects
    -   /settings
    -   /tools
-   /utils

Most folder contains an `index.ts` file which consolidates exports for ease of import elsewhere in the project.
In the `styles` folder, I've organized subfolders to include styles, a breakpoint mixin and an SCSS function for easy rem calculations, prepping for a scalable app.

I've utilized `babel-plugin-module-resolver` to streamline the import statements in the project. The paths are precisely defined in `config-override.js`, making the code cleaner and easier to manage.

## Getting Started

1. Clone the repository to your local machine.
2. Navigate to the project directory.
3. Run `npm install` to install all the necessary dependencies.
4. Now you can run any of the available scripts mentioned below.

## Available Scripts

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

this webapp is live on : http://bookmarkmanager.vercel.app/
