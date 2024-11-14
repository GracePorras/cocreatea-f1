## Getting Started




First, run the development server:

```bash
npm run dev

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

Step 1: npm i

Step 2: Add .env.local file

# Deployment used by `npx convex dev`
CONVEX_DEPLOYMENT=dev:neat-hare-88 # team: grace-c-porras, project: cctea-bff0a

NEXT_PUBLIC_CONVEX_URL=https://neat-hare-88.convex.cloud

# clerk auth keys
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=pk_test_bGVnYWwtc2F3ZmlzaC00NS5jbGVyay5hY2NvdW50cy5kZXYk
CLERK_SECRET_KEY=sk_test_gm2j83U3RqzCueGPvAm8PAp1CjjWoOtRgWuxzGKm6d

# liveblocks api keys
NEXT_PUBLIC_LIVEBLOCKS_PUBLIC_KEY=pk_dev_UPFvWPrtThbk3na6ld_NjfX6uHzni_dFoviuqTRwoZ7gOFxu1a_UPG0ARCdnAepX
NEXT_PUBLIC_LIVEBLOCKS_SECRET_KEY=sk_dev_Pzn5uTUNK73ZjSGet1kP_3-GCrHa0OjkROi1a4_EKEm7WeVrpeSrx_hrbXSgmORP


Step 3: Setup Convex and Clerk

Convex:
npx convex dev
npm install @clerk/clerk-react

Clerk:
npm install @clerk/nextjs

Step 4: Setup Liveblocks