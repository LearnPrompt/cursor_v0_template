# Next.js Cursor V0 Version

Aiming to become the most convenient Cursor V0 development process

English | [简体中文](./README.zh-CN.md)

## Step 0: Find free APIs from Perplexity

## Step 1: Initial project design on v0.dev

- Utilize the AI-assisted design features of [v0.dev](v0.dev)
- If specific components are needed, select from [Uiverse.io](Uiverse.io), which supports direct pasting into Figma for conversion to editable layers

## Step 2: Export the design to Cursor project

- Initialize the project using v0's `add to codebase` or `npx shadcn@latest init -d`
- Use [cursor.directory](cursor.directory) to enhance prompting capabilities
- Leverage `@Codebase` and `@Composer` features for code generation and optimization

## Step 3: Refine and iterate using v0.md file

- Define v0 prompts in `prompts/v0.md`
- Enter commands in the Composer feature, such as `i want a user onboarding flow @v0.md`
- Component generation will output corresponding v0 chat URLs, allowing direct navigation to v0.dev's conversation interface for preview and further iteration

## Step 4: Integrate Supabase for data management

- Import [Supabase](https://supabase.com/docs) documentation into Cursor docs
- Implement form submission and other data processing logic

## Step 5: Implement authentication with Clerk

- Integrate [clerk](https://clerk.com/docs) for login, registration, and user management
- Import [Clerk documentation](https://clerk.com/docs) into Cursor to optimize the authentication flow

## Step 6: Deploy to Vercel