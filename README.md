<<<<<<< HEAD
# Reown AppKit Example using wagmi and solana (Vite + React)

This is a [Vite](https://vitejs.dev) project together with React.

## Usage

1. Go to [Reown Cloud](https://cloud.reown.com) and create a new project.
2. Copy your `Project ID`
3. Rename `.env.example` to `.env` and paste your `Project ID` as the value for `VITE_PROJECT_ID`
4. Run `pnpm install` to install dependencies
5. Run `pnpm run dev` to start the development server

## Resources

- [Reown — Docs](https://docs.reown.com)
- [Vite — GitHub](https://github.com/vitejs/vite)
- [Vite — Docs](https://vitejs.dev/guide/)
=======
# Web AppKit Examples

This repository provides examples of how to integrate and use **AppKit** in various frameworks, including **Next.js**, **React**, and **Vue**. These examples are designed to demonstrate best practices and simplify the integration process.

## Examples Included

Each framework has examples for the implementation with wagmi, ethers, solana and multichain (wagmi & solana)

- **Next.js**
  - ethers - https://appkit-web-examples-next-ethers.vercel.app/
  - wagmi - https://appkit-web-examples-next-wagmi.vercel.app/
  - Solana - https://appkit-web-examples-next-solana.vercel.app/
  - Multichain - https://appkit-web-examples-next-multichain.vercel.app/
- **React**
  - ethers - https://appkit-web-examples-react-ethers.vercel.app/
  - wamgi - https://appkit-web-examples-react-wagmi.vercel.app/
  - Solana - https://appkit-web-examples-react-solana.vercel.app/
  - Multichain - https://appkit-web-examples-react-multichain.vercel.app/
- **Vue**
  - ethers - https://appkit-web-examples-vue-ethers.vercel.app/
  - wagmi - https://appkit-web-examples-vue-wagmi.vercel.app/
  - Solana - https://appkit-web-examples-vue-solana.vercel.app/
  - Multichain - https://appkit-web-examples-vue-multichain.vercel.app/

---

## Structure

```plaintext
.
├── nextjs/   # Web AppKit with NextJS
├──────── next-wagmi-app-router
├──────── next-ethers-app-router
├──────── next-solana-app-router
├──────── next-multichain-app-router
├── react/    # Web AppKit with React
├──────── react-wagmi
├──────── react-ethers
├──────── react-ethers5
├──────── react-multichain
├──────── react-solana
├── vue/      # Web AppKit with Vue
├──────── vue-ethers
├──────── vue-multichain
├──────── vue-solana
└──────── vue-wagmi
>>>>>>> upstream/main
