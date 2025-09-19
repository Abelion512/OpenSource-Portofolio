# OpenSource • Portofolio 

Portofolio statis yang menampilkan **Apps**, **Films**, **Music**, dan **Skills** dengan gaya **glassmorphism**, animasi **GSAP + ScrollTrigger**, serta **Tailwind CSS**.  
Live: https://abelion512.github.io/OpenSource-Portofolio/ 

---  

## ✨ Fitur 
- **Dark/Light Mode** toggle dengan persist `localStorage`
- **Animasi halus** (reveal on scroll, parallax background)
- **Section Music** dengan **audio preview** (play/pause & ducking)
- **Skills sebagai XP bar** (data dummy, mudah dikustom)
- **Data dummy** untuk Apps/Films/Music agar cepat disesuaikan
- **Tanpa framework** (HTML5 + Vanilla JS + GSAP + Tailwind CDN)

## 🗂️ Struktur Proyek (ringkas)
```text
OpenSource-Portofolio/
├── assets/
│   └── logo.svg
├── music/
│   └── *.mp3
└── index.html
```

## 🚀 Cara Menjalankan        
**1. Clone repo**  
 ```text
git clone https://github.com/abelion512/OpenSource-Portofolio.git
cd OpenSource-Portofolio
```
   
**2. Jalankan lokal**  
  - Buka langsung `index.html` di browser, atau    
  - Gunakan server lokal (contoh dengan Python):
```text
python -m http.server 5173
```
lalu akses [http://localhost:5173](http://localhost:5173)    
    
## 🛠️ Kustomisasi    
- Ubah data dummy (Apps/Films/Music/Skills) di `<script>` dalam `index.html`.   
- Tambahkan atau ganti file audio di folder `music/`.   
- Ganti logo di `assets/logo.svg`.  
      
## 📸 Preview   
- Tambahkan screenshot (`assets/preview.jpg`) agar pengunjung repo bisa langsung lihat tampilan UI.  
    
## 🤝 Kontribusi   
1. Fork repo ini   
2. Buat branch baru (`feat/...` atau `fix/...`)  
3. Commit dengan pesan jelas (`feat: ...`, `fix: ...`, `docs: ...`)   
4. Buka Pull Request ke branch `main`  
   
     
## 📄 Lisensi     
MIT — bebas digunakan, diubah, dan disebarkan. Sertakan atribusi bila dipakai ulang.  
    
## 🙌 Kredit        
- **UI/UX**: Glassmorphism + Tailwind CSS  
- **Animasi**: GSAP + ScrollTrigger 
- **Inspirasi**: Proyek portofolio open-source untuk belajar & showcase
