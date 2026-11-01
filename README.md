# 🔮 Mystic Matrix Frontend

Enchanted Fantasy Retail & AI Inventory Management Web & Android Application.  
Built with **React 18**, **Vite**, **Tailwind CSS**, **Clerk Authentication**, and **Capacitor 6**.

---

## 🚀 Deploying to Vercel

This repository is ready for deployment on [Vercel](https://vercel.com/).

### 1. Import Repository
1. In the [Vercel Dashboard](https://vercel.com/dashboard), click **Add New → Project**.
2. Select this repository: `https://github.com/Saina-Chourasia/mystic-matrix-frontend`.
3. Vercel automatically detects the **Vite** framework preset:
   - **Framework Preset**: `Vite`
   - **Build Command**: `npm run build`
   - **Output Directory**: `dist`

### 2. Configure Environment Variables
In the Vercel Project Settings **Environment Variables** tab, add:

| Variable | Value / Description |
| :--- | :--- |
| `VITE_API_URL` | Your Render backend URL (e.g., `https://mystic-matrix-backend.onrender.com`) |
| `VITE_CLERK_PUBLISHABLE_KEY` | Your Clerk Publishable Key (`pk_test_...`) |

Click **Deploy**!

---

## 📱 Native Android App (Capacitor)

The native Android project is included in the `android/` directory:
- **Package ID**: `com.mysticmatrix.app`
- **Application Name**: `Mystic Matrix`
- **Target SDK**: Android 34 (Android 14)

### Quick Commands
```bash
# Sync web changes to Android project
npm run build && npx cap sync android

# Open in Android Studio
npx cap open android
```

---

## 🛠️ Local Development

```bash
# Install dependencies
npm install

# Start Vite development server
npm run dev
```
Default port: `http://localhost:5173`.
