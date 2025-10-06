# Next.js AI Chatbot

A modern, interactive AI-powered chatbot built with **Next.js**, **React**, and the **Vercel AI SDK**. This chatbot allows you to interact with multiple AI models, perform web searches, view reasoning steps, and see sources for responses, all in real-time. It’s designed to be fully responsive, user-friendly, and easy to deploy.

![Next.js AI Chat](public\Ai_chat.png)

---

## Features

- Multi-model support (e.g., GPT 4o, Deepseek R1)
- Web search integration to enhance responses
- Reasoning and source tracking for AI answers
- Retry responses and copy assistant messages
- Attachment support in messages
- Streaming chat experience for smooth interactions
- Responsive UI powered by Tailwind CSS
- Clean and modern icons via Lucide React

---

## Tech Stack

- **Frontend:** Next.js 15, React, TypeScript  
- **Styling:** Tailwind CSS  
- **AI Integration:** Vercel AI SDK (`@ai-sdk/react`)  
- **Icons:** Lucide React  
- **State Management:** React hooks (`useState`)  
- **Hosting / Deployment:** Vercel  

---

## Getting Started


1. **Install dependencies:**
    ```bash
    npm install
    # or
    yarn install
    # or
    pnpm install
    # or
    bun install
    ```

2. **Set up environment variable:**

    Create a `.env.local` file in the project root and add your AI Gateway API key:
    ```
    AI_GATEWAY_API_KEY=your-api-key-here
    ```

3. **Run the development server:**
    ```bash
    npm run dev
    # or
    yarn dev
    # or
    pnpm dev
    # or
    bun dev
    ```

    Open [http://localhost:3000](http://localhost:3000) in your browser.

## Usage

- Edit `app/page.tsx` to customize the chatbot UI or logic.
- The app auto-updates as you edit files.

## Learn More

- [Next.js Documentation](https://nextjs.org/docs)
- [Vercel AI SDK Documentation](https://sdk.vercel.ai/docs)

## Deploy

Deploy easily on [Vercel](https://vercel.com/new) for production.

See [Next.js deployment docs](https://nextjs.org/docs/app/building-your-application/deploying) for details.

