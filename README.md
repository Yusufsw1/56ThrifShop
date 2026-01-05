# 👕 56ThrifShop: Curated Thrift & E-Commerce Experience



**56ThrifShop** adalah platform e-commerce khusus produk thrifting yang dibangun dengan fokus pada kecepatan dan user experience yang elegan. Aplikasi ini menghubungkan inventory barang unik dengan sistem pembayaran yang terintegrasi.

## 🚀 Fitur Unggulan
- **Seamless Authentication**: Integrasi dengan Supabase Auth untuk keamanan akun pengguna.
- **Dynamic Catalog**: Fetching data produk secara real-time dari PostgreSQL.
- **Shopping Cart System**: Pengelolaan keranjang belanja yang persisten di sisi klien.
- **Optimized Image Loading**: Menggunakan Next/Image untuk performa loading gambar produk yang cepat.
- **Responsive Web Design**: Pengalaman belanja yang konsisten di perangkat mobile maupun desktop.

## 🛠️ Tech Stack
- **Framework**: [Next.js 14](https://nextjs.org/) (App Router)
- **Styling**: [Tailwind CSS](https://tailwindcss.com/) & [Shadcn/UI](https://ui.shadcn.com/)
- **Database**: [Supabase](https://supabase.com/) (PostgreSQL)
- **Validation**: [Zod](https://zod.dev/) & [React Hook Form](https://react-hook-form.com/)
- **State**: React Context / Zustand

## 📦 Struktur Folder
```text
├── app/              # Routing & Server Components
├── components/       # UI Components (Button, Input, Card, dll)
├── lib/              # Konfigurasi Supabase & Utility functions
├── public/           # Aset gambar & icon
└── hooks/            # Custom React hooks
```

🏁 Cara Menjalankan Lokal
1. Clone repository:
   ```bash
   git clone [https://github.com/Yusufsw1/56ThrifShop.git](https://github.com/Yusufsw1/56ThrifShop.git)

2. Install dependensi:
   ```bash
    npm install

3. Set .env.local dengan kredensial Supabase Anda.
   
4. Jalankan aplikasi:
   ```bash
   npm run dev

🤝 Contact
Yusuf - [GitHub Profile](https://github.com/Yusufsw1)

Project Link: [github.com/Yusufsw1/56ThrifShop](https://github.com/Yusufsw1/56ThrifShop)
