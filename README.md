## 🚀 Cara Menjalankan Proxy-AJ

### **Metode 1: Menggunakan Script Instalasi (Recommended)**

```bash
# 1. Clone repository
git clone https://github.com/hanz-su/Proxy-AJ.git
cd Proxy-AJ

# 2. Jalankan script instalasi
bash install.sh
```

atau

```bash
chmod +x install.sh
./install.sh
```

### **Metode 2: Manual (Tanpa Script)**

```bash
# 1. Download repository
git clone https://github.com/hanz-su/Proxy-AJ.git
cd Proxy-AJ

# 2. Download proxy binary
wget https://github.com/hanz-su/Proxy-AJ/raw/main/proxy

# 3. Berikan permission
chmod +x proxy

# 4. Jalankan proxy
./proxy
```

---

## 📝 Penjelasan Script Instalasi:

Script `install.sh` akan secara otomatis:

1. ✅ Menghapus proxy lama (jika ada)
2. ✅ Download proxy binary terbaru dari repository
3. ✅ Memberikan permission execute (`chmod +x`)
4. ✅ Menampilkan pesan sukses

---

## ⚙️ File-file Penting:

| File | Fungsi |
|------|--------|
| **proxy** | Binary file utama (perlu didownload) |
| **file** | Konfigurasi proxy |
| **vars** | Variabel konfigurasi PC |
| **install.sh** | Script instalasi otomatis |

---

## ⚠️ Catatan Penting:

1. **Butuh Binary Proxy** - File `proxy` binary belum ada di repository. Anda perlu:
   - Menambahkan file proxy dari sumber original, atau
   - Membuat binary proxy sendiri

2. **Sistem Requirement**:
   - Linux/Termux (untuk menjalankan script bash)
   - `wget` atau `curl` untuk download

3. **Konfigurasi**:
   - Edit file `file` atau `vars` untuk mengubah konfigurasi
   - Ubah Discord links, Proxy Server, dll sesuai kebutuhan

---

**Sudah siap dijalankan! 🎉**
