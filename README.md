This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.


=== tutor ===
- ```npx create-next-app@latest .```
- Tambahkan ```"dev": "next dev --turbo",``` di package.json
- Pergi ke folder app
    - hapus global.css kecuali
    ```
    @tailwind base;
    @tailwind components;
    @tailwind utilities;
    ```
- Pergi ke file page.tsx
    - Edit page.tsx
- Buat folder baru di app
    - contacts
        - page.tsx
        - ```rafce```
- Buat folder baru ```components``` di root
    - buat file ```contact-table.tsx```
    - ```rafce```
    - ```table>thead>tr>th*5```
    - ```tbody>tr>td*5```
- Pergi ke Folder contacts
    - import contact-table
- Buat file di folder components
    - search.tsx
    - ```rafce```
- ```npm i react-icons```
- import react icons di search.tsx
    - ```import {IoSearch} from "react-icons/io5"```
- import component search ke page.tsx yang ada di contact
- Buat button.tsx di folder components
- import ke folder contacts file page.tsx
- install prisma npm i -D prisma
- install prisma client npm i @prisma/client
- inisialisasi npx prisma init
- ke file .env
- copas schema.prisma