# mercadoenviosfloripa
Venta productos 
git init
git add .
git commit -m "Primer commit - web MercadoLocal completa"
git branch -M main
git remote add origin https://github.com/TU_USUARIO/mercado-local.git
git push -u origin main
mercado-local/
├─ backend/
│  ├─ server.js
│  ├─ package.json
│  ├─ routes/
│  │   ├─ auth.js
│  │   └─ products.js
│  └─ models/
│      ├─ User.js
│      └─ Product.js
├─ frontend/
│  ├─ package.json
│  ├─ vite.config.js
│  └─ src/
│      ├─ App.jsx
│      ├─ index.jsx
│      ├─ firebase.js
│      ├─ pages/
│      │   ├─ Home.jsx
│      │   ├─ LoginRegister.jsx
│      │   └─ Dashboard.jsx
│      └─ components/
│          ├─ Navbar.jsx
│          ├─ ProductCard.jsx
│          ├─ UploadForm.jsx
│          └─ Filters.jsx
