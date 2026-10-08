# Mvt1927 Profile Website (Astro)

Repository này đã được chuyển thành website tĩnh bằng [Astro](https://astro.build/) để có thể deploy trực tiếp lên **Cloudflare Pages**.

## Profile information

- 👋 Hi, I’m [@Mvt1927](https://github.com/Mvt1927)
- 👀 Passion: Backend development, AI, modern frontend, game development, and new technologies.
- 🌱 Current learning: OOP-first mindset; practical experience with TypeScript/JavaScript (Express, NestJS, React, Vite, Next.js), PHP (Laravel, Blade), ORMs (Prisma, Eloquent), plus foundational experience in C, C++, Java, Kotlin, Python, Flutter, and C# (Unity).
- 💞️ Open to collaborate on:
  - PHP/Laravel projects (especially Laravel Livewire)
  - Next.js projects using TanStack Query / TanStack Table
  - CLI tools (C++ / Python)
  - AI / Machine Learning projects
- 📫 Contact:
  - GitHub: https://github.com/Mvt1927
  - Email: viettheog4@gmail.com
  - Facebook: https://www.facebook.com/Mvt1927
  - LinkedIn: Coming soon

## Run locally

```bash
npm install
npm run dev
```

Dev server mặc định chạy tại `http://localhost:4321`.

## Build static site

```bash
npm run build
npm run preview
```

- Build output directory: `dist/`
- Astro config đã đặt `output: "static"` để phù hợp Cloudflare Pages static hosting.

## Deploy to Cloudflare Pages

Thiết lập project trên Cloudflare Pages với:

- **Framework preset**: Astro (hoặc None nếu cấu hình thủ công)
- **Build command**: `npm run build`
- **Build output directory**: `dist`
- **Node version**: khuyến nghị 20+

Sau đó kết nối repo `Mvt1927/Mvt1927`, Cloudflare Pages sẽ build và deploy tự động.
