# Shop Public Ready

Website bán hàng full-stack mẫu:
- React + Vite frontend
- Node.js + Express backend
- SQLite database + Prisma
- JWT authentication
- User/Admin role
- Products, categories, cart, orders, inventory
- Security middleware, rate limiting, validation
- Docker Compose
- Có thể deploy frontend lên Vercel và backend lên Render/Railway.

## Chạy local

### Backend
```bash
cd backend
cp .env.example .env
npm install
npx prisma migrate dev --name init
npm run seed
npm run dev
```

### Frontend
```bash
cd frontend
npm install
npm run dev
```

Frontend: http://localhost:5173
Backend: http://localhost:4000

Tài khoản admin mẫu:
admin@example.com / Admin123!

Lưu ý: mật khẩu mẫu chỉ dùng để test, cần đổi trước khi public.
