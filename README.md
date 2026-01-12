# Abbas Chat

Abbas Chat is a powerful AI chatbot application built with Next.js and the AI SDK.

## Features

- **Advanced Routing**: Seamless navigation and performance using Next.js App Router.
- **AI SDK Integration**: Unified API for generating text and structured objects.
- **Modern UI**: Styled with Tailwind CSS and Radix UI components (shadcn/ui).
- **Data Persistence**: Uses Postgres for saving chat history and user data.

## Getting Started

1. **Install dependencies**:
    ```bash
    pnpm install
    ```

2. **Setup Database**:
    ```bash
    pnpm db:migrate
    ```

3. **Run Locally**:
    ```bash
    pnpm dev
    ```

Your app should now be running on [localhost:3000](http://localhost:3000).

## Configuration

Environment variables are defined in `.env.example`. Make sure to configure your own `.env` file with necessary keys for database and AI providers.

## License

This project is open source.
