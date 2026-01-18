# Rara Live Demo — One‑Click Deploy

Ini adalah **Frontend + Backend** untuk Rara AI (GLM‑4.5)  
Fitur:
- Jawaban otomatis 100% jujur (Honesty Module)  
- Status jawaban: Fakta / Asumsi / Opini / Risiko  
- History jawaban tersimpan di browser

---

## 🔌 Deploy Backend (Railway)

Klik tombol berikut untuk deploy backend Rara AI:

[![Deploy on Railway](https://railway.app/button.svg)](https://railway.app/new/template?template=https://github.com/<USERNAME>/<REPO_NAME>)

> Ganti `<USERNAME>` dan `<REPO_NAME>` dengan nama GitHub kamu.

Backend otomatis deploy karena sudah ada **server.js** dan **package.json**.

---

## ⚡ Deploy Frontend (Netlify)

Klik tombol berikut untuk deploy frontend:

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/<USERNAME>/<REPO_NAME>)

> Setelah backend live, update `API_URL` di `frontend/index.html`  
> dengan domain backend Railway kamu sebelum deploy.

---

## 📌 Cara Pakai Setelah Deploy

1. Backend Rails selesai deploy → dapat URL publik (_Railway_)  
2. Ganti `API_URL` di `frontend/index.html` → pakai backend URL  
3. Deploy frontend ke Netlify  
4. Buka link frontend → Rara langsung live

---

## Struktur Repo

