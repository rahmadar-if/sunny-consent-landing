# Sunny CRM - Consent & Campaign Landing Page

Landing page demo untuk alur WhatsApp Blasting & Consent Management (UU Perlindungan Data Pribadi / UU PDP).

---

## 🚀 Fitur Unggulan
1. **Otomatis Muncul Pop-up (Jeda 2.5 Detik)**: Pengunjung membaca landing page sejenak, lalu muncul form konfirmasi persetujuan secara halus (*modal slide-up*).
2. **Auto-fill via URL Query Parameter**:
   - Jika link dari WhatsApp memuat parameter:
     ```text
     https://<domain-vercel>/index.html?name=Budi%20Santoso&phone=081234567890
     ```
   - Form Nama & Nomor HP otomatis terisi lengkap, dan muncul notifikasi *"Data terisi otomatis dari tautan WhatsApp Anda"*.
3. **Persetujuan Regulasi UU PDP**:
   - Terdapat checkbox persetujuan wajib.
   - Tombol konfirmasi terkunci (*disabled*) hingga checkbox dicentang dan data terisi.
4. **Layar Sukses Realtime**:
   - Animasi checklist sukses & ringkasan profil pelanggan setelah data disetujui.

---

## 📦 Cara Deploy ke Vercel (1 Menit)

### Opsi A: Drag & Drop via Dashboard Vercel
1. Buka [https://vercel.com/dashboard](https://vercel.com/dashboard).
2. Klik **Add New...** > **Project**.
3. Import atau upload folder `sunny-consent-landing`.
4. Klik **Deploy**! (Website langsung aktif dengan domain `.vercel.app`).

### Opsi B: Menggunakan Vercel CLI
Jalankan di terminal PowerShell:
```powershell
cd "d:\2.PRESALES\Sunny DCP\SunnyCRM\sunny-consent-landing"
npx vercel
```
Ikuti instruksi singkat di terminal untuk publikasi langsung.
