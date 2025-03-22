# My Experience with different Api's

What is **Api** (*application programming interface*), this is where data is exposed on different endpoints for client program to access.

I will create same api with different framework to try and evaluate which is best and what is common about them all.

## Framework experience

### Hono Framework



[Hono](https://hono.dev "Official Hono Website") is a lightweight framework that is very fast to start.

#### <u>Hono setup</u>

`pnpm create hono@latest` will setu the project with pnpm.

```plaintext
my-hono-project/
├── node_modules/          # Node.js dependencies
├── public/                # Static assets (e.g., images, CSS, JS)
│   └── favicon.ico        # Favicon for the website
├── src/                   # Source code
│   ├── index.ts           # Entry point of the application
│   └── routes/            # Route handlers
│       ├── api/           # API routes
│       │   └── hello.ts   # Example API route
│       └── index.ts       # Main route handler
├── .gitignore             # Files/folders to ignore in Git
├── package.json           # Project metadata and dependencies
├── package-lock.json      # Lock file for dependencies
├── README.md              # Project documentation
├── tsconfig.json          # TypeScript configuration
└── vite.config.ts         # Vite configuration (if using Vite)
