# 🚀 Belajar Command Git dengan Santai

Halo! 👋  
Ini adalah panduan singkat dan seru untuk mempelajari perintah-perintah dasar Git. Cocok banget buat kamu yang baru mulai ngulik version control!  

---

## 👤 1. Tambahkan Identitas User  
Pastikan kamu sudah memperkenalkan dirimu ke Git.  

```bash
git config --global user.email "yourmail@gmail.com"
git config --global user.name "your git username"
```

> 💡 **Tips:** Ini hanya perlu dilakukan sekali di komputer kamu (kecuali kamu mau ganti user).

---

## 🆕 2. Inisialisasi Repository  
Buat folder kamu jadi repository Git.  

```bash
git init
```

> 🎯 Sekarang folder kamu siap untuk di-track oleh Git.

---

## 🌐 3. Tambahkan Remote Repository  
Hubungkan repository lokal kamu ke repository online (GitHub, GitLab, dsb).  

```bash
git remote add origin <your-repo-link>
```

> 📌 Ganti `<your-repo-link>` dengan URL repository kamu.

---

## 🌱 4. Buat & Pindah Branch  
Bekerja di branch terpisah supaya lebih rapi.  

```bash
git branch <branch-name>
git checkout <branch-name>
```

> 💡 **Shortcut:** Kamu juga bisa langsung bikin dan pindah dengan:
> ```bash
> git checkout -b <branch-name>
> ```

---

## 🔍 5. Cek Status  
Lihat apa yang berubah sebelum commit.  

```bash
git status
```

> 🧐 Ini akan menunjukkan file yang sudah diubah, ditambahkan, atau dihapus.

---

## 📤 6. Push File ke Repository  
Saatnya upload pekerjaanmu!  

```bash
git add .
git commit -m "Pesan commit kamu"
git push origin <branch-name>
```

> ✅ **Pro Tips:**  
> - Gunakan pesan commit yang jelas supaya mudah dibaca.  
> - Pastikan branch yang kamu push sudah benar.

---

## 🎉 Penutup  
Sekarang kamu sudah tahu perintah Git dasar.  
Selamat bereksperimen, dan ingat: kalau ada error, baca pesan error-nya dulu – biasanya Git kasih clue buat solusinya.  

> 🏆 Konsistensi adalah kuncinya. Semakin sering kamu pakai Git, semakin cepat kamu paham!
