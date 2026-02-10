# Long-Term Memory

## ⚠️ Important Rules

### GitHub Push Policy
**ALWAYS confirm with Zaki before pushing code to GitHub.**

**Workflow:**
1. Make changes locally
2. Show git diff / summary of changes
3. Wait for Zaki's confirmation ("silakan" / "oke" / approval)
4. Only then: `git add` → `git commit` → `git push`

**Never push without confirmation first.**

---

## Style Preferences

### No Emojis/Emoticons
- Jangan gunakan emoji/emoticon di task names, messages, atau dokumentasi
- Gunakan teks plain saja

---

## Development Workflow

### Plan Before Execute
**Selalu buat plan terlebih dahulu sebelum eksekusi coding.**

**Flow:**
1. User request task development
2. Saya buatkan plan (langkah-langkah, approach, struktur)
3. User review dan approve/tidak approve
4. Setelah approval: baru eksekusi coding

**Never start coding without plan approval first.**

---

## 🔑 GitHub Accounts

| Account | Username | Token | Repos |
|---------|----------|-------|-------|
| Personal | zakiachsan27 | `[GITHUB_TOKEN_REDACTED]` | CallExpert |
| Client | zakiachsan | `[GITHUB_TOKEN_REDACTED]` | kilasindonesia, inidepok |

---

## 🔗 Integrations

### Trello
- Account: jagobikinwebsite
- Board: JagoBikinWebsite - Project Management
- API Key: `[TRELLO_API_KEY_REDACTED]`
- Token: `[TRELLO_TOKEN_REDACTED]`

### Notion
- Workspace: JagoBikinWebsite
- Token: `[NOTION_TOKEN_REDACTED]`
- Projects DB: `2fcb2f46-cfa3-81ea-91a7-db2682ea40e4`

---

## 👥 Clients & Projects

### Pak Dinata (kilasindonesia + inidepok)
- Two repos that share the same tasks
- Labels: `kilasindonesia`, `inidepok`
- Tasks:
  - ✅ Pagination
  - ✅ WhatsApp OG Image
  - ✅ Schedule Berita
  - ✅ CMS Tentang Kami
  - ✅ Read More Snippet
  - ✅ Redesign CMS

### Pak Juli
- Landing Page Ads
- Keyword Research
- Company Profile
- Google Ads
- Meta Ads
- Konten Iklan

### Pak Nicholas (PT Sentra Aircon Pratama - SAP)
- GitHub: https://github.com/zakiachsan/PT-Sentra-Aircon-Pratama.git
- CMS Kategori Artikel
- CMS Text Editor (Bullet List)
- CMS Portfolio (Design By & Sosmed)
- CMS Scheduled Article Validation
- CMS Product Tagline
- SEO & Google Crawl
- Kategori Produk (CMS & Website)
- Edit Halaman Tentang Kami
- Edit Background Homepage

### Bu Nisa (Taaruf Samara)
- GitHub: https://github.com/zakiachsan/Taaruf-Samara.git
- Matchmaking/Taaruf App
- OTP via email, face verification, KTP upload
- Premium features: 50rb subscription, 300k for 3x taaruf
- Referral system with withdrawal
- Self-value certification service
- Block/unblock users, chat with introduction message
- Promo banner CMS

---

### CallExpert (MentorinAja)
- GitHub: https://github.com/zakiachsan27/CallExpert.git
- Platform mentoring & konsultasi dengan expert
- Tech: React + Vite + Supabase + Capacitor
- Payment: Midtrans integration
- Meeting: Google Meet pool system (3 links)
- Features: Booking, Chat, Video Call, Digital Products

## 📁 Project Paths
- `/home/ubuntu/clawdbot-workspace/workspace/projects/kilasindonesia/web`
- `/home/ubuntu/clawdbot-workspace/workspace/projects/inidepok`
- `/home/ubuntu/clawdbot-workspace/workspace/projects/CallExpert`
- Scripts: `/home/ubuntu/clawdbot-workspace/workspace/scripts/`

---

## 🔄 Workflow

### Before Working on Any Task
1. Check Trello for task details
2. Confirm understanding with Zaki
3. Show proposed changes before pushing

### Testing Flow
1. Local development (npm run dev)
2. GitHub branch → PR
3. GitHub Actions → Deploy to production

---

## 💰 Payments
- Pak Juli: DP 2.500.000 received (2026-02-03)

---

## Templates

### Product Plan Template
**Reference:** Gunakan struktur ini untuk setiap product plan baru

**Template File:** `/home/ubuntu/clawdbot-workspace/workspace/templates/product-plan-template.md`

**Notion Example:** https://www.notion.so/Ecobliss-PO-Logistics-Management-System-Product-Plan-2feb2f46cfa3818abbcce2410b436bb1

**Struktur Wajib:**
1. Latar Belakang & Goals (numbered list)
2. Data/Context (table atau bullet list)
3. Fitur-Fitur Sistem (H3 per fitur + callout untuk benefit)
4. Tahap Pengembangan (toggle sections)
5. Langkah Selanjutnya (numbered list)

**Format:**
- Heading hierarchy: H1 → H2 → H3 → H4
- Tables untuk data terstruktur
- Callout boxes dengan emoji untuk benefit
- Toggle sections untuk tahap pengembangan
- Bullet/numbered lists untuk detail

### Wireframe Template
**Reference:** Gunakan struktur ini untuk setiap wireframe/mockup baru

**Template File:** `/home/ubuntu/clawdbot-workspace/workspace/templates/wireframe-template.md`

**Notion Examples:**
- Basic: https://www.notion.so/Ecobliss-PO-System-Wireframe-2feb2f46cfa38125ad52eb7f104802c8
- **Detailed (Reference Utama):** https://www.notion.so/Ecobliss-PO-System-Wireframe-Detailed-2feb2f46cfa38160902dd8840391e162

**Struktur Wajib:
1. Struktur Navigasi (tree diagram)
2. Dashboard Layout (key metrics + charts)
3. List View (table dengan filter/search)
4. Detail View (data + history)
5. Form / Input (fields + actions)
6. Import/Upload (multi-step process)
7. Mobile Responsive Layout

**Format:**
- ASCII art untuk wireframes
- Code blocks untuk layout
- Annotations di bawah setiap screen
- Mobile view (480px width)

---

### Wireframe Format Reference (Ecobliss Style)
**Format wireframe terbaru yang digunakan sebagai template untuk project-project selanjutnya.**

**Template File:** `/home/ubuntu/clawdbot-workspace/workspace/templates/wireframe-format-template.md`

**Reference Files:**
- HTML: `/home/ubuntu/clawdbot-workspace/workspace/projects/ecobliss-wireframe-browser.html`
- PDF: `/home/ubuntu/clawdbot-workspace/workspace/projects/ecobliss-wireframe-browser.pdf`

**Format Key Features:**
1. **Browser Frame** - Dots, address bar, app header, navigation menu
2. **Dashboard** - 4 metric cards (1 baris horizontal)
3. **List View** - Filter bar, data table dengan pagination
4. **Detail View** - Horizontal table layout (2 baris x 4 kolom)
5. **Form/Input** - Compact fields dengan minimal padding
6. **Step Wizard** - Multi-step indicator

**Design Specifications:**
- Page size: A4 Landscape
- 1 halaman = 1 screen
- Font size: 7-10px (compact tapi readable)
- Padding: 2-5px (minimalis)
- Color: Blue header (#1e3a5f), neutral backgrounds
- Status badges: Open (biru), Partial (kuning), Closed (hijau), Warning (merah)

**Contoh Screens:**
1. Dashboard - Metrics, tables, progress bars
2. PO List - Filter, table, pagination
3. PO Detail - Detail info, history, form
4. Import Data - 3-step wizard
5. Logistik & Kontrak - Tables, progress bars

---

### Template Surat Penawaran
**Format surat penawaran untuk JagoBikinWebsite.**

**Notion Template:** https://www.notion.so/Template-Surat-Penawaran-JagoBikinWebsite-2feb2f46cfa381269a50d2657177ee53

**Struktur Surat:**
1. **Header/Kop** - Logo, nama, tagline, alamat, kontak
2. **Judul** - SURAT PENAWARAN, nomor, tanggal
3. **Tujuan** - Yth. Bapak/Ibu [Nama], jabatan, alamat
4. **Pembuka** - Salam, perkenalan, maksud surat
5. **Tabel Penawaran** - No, Nama Paket, Spesifikasi, Qty, Harga, Total
6. **Keterangan** - PPN, domain/hosting, perubahan harga
7. **Syarat & Ketentuan** - Pembayaran (DP 50%), durasi, garansi, revisi
8. **Penutup** - Paragraf sopan
9. **Tanda Tangan** - Hormat kami, tanda tangan, cap, kontak

**Format Tabel:**
- 6 kolom: No, Nama Paket, Spesifikasi, Qty, Harga, Total
- Total keseluruhan + terbilang
- Rincian item dan harga detail

**HTML Template:** `/home/ubuntu/clawdbot-workspace/workspace/projects/surat-penawaran-jbw.html`

**PDF Output:** `/home/ubuntu/clawdbot-workspace/workspace/projects/surat-penawaran-jbw.pdf`

**Cara Edit:**
1. Buka file HTML
2. Edit isi sesuai client (gunakan text editor)
3. Convert ke PDF: `wkhtmltopdf --page-size A4 --margin-top 15mm --margin-bottom 15mm --margin-left 20mm --margin-right 20mm surat-penawaran-jbw.html output.pdf`

**Kontak Default:**
- Telepon: 6285694662592
- Email: jagobikinwebsite28@gmail.com
- Website: jagobikinwebsite.com
- Alamat: Green Andara Residence blok C6, No.7
- Tanda tangan: ZakiAchsan (font signature) + Muhammad Zaki Achsan

---

## 📁 Template Repository

Semua template tersimpan di workspace dengan struktur berikut:

```
workspace/
├── templates/
│   ├── product-plan-template.md          # Template Product Plan
│   ├── wireframe-template.md             # Template Wireframe Basic
│   └── wireframe-format-template.md      # Guidelines Wireframe Format
│
├── projects/
│   ├── surat-penawaran-jbw.html          # Template Surat Penawaran (FINAL)
│   ├── surat-penawaran-jbw.pdf           # PDF Surat Penawaran
│   ├── ecobliss-wireframe-browser.html   # Template Wireframe (FINAL)
│   └── ecobliss-wireframe-browser.pdf    # PDF Wireframe
│
└── templates-repo/                       # Git repo (local)
    ├── README.md
    ├── surat-penawaran-jbw.html
    ├── ecobliss-wireframe-browser.html
    ├── product-plan-template.md
    └── wireframe-format-template.md
```

### Backup Strategy

**Primary (Workspace):**
- All HTML templates in `/projects/` and `/templates/`
- PDF outputs in `/projects/`

**Secondary (Git):**
- Local git repo: `templates-repo/`
- Commit setiap perubahan besar
- Can be pushed to GitHub when needed

**Tertiary (Notion):**
- Notion pages untuk dokumentasi struktur
- Links ke file lokal
- Reference examples

**Quaternary (PDF Archives):**
- PDF versions sebagai snapshot final
- Bisa di-share ke client
- Tidak bisa diedit tapi aman sebagai referensi

### Cara Recovery Jika File Hilang

1. **Dari Workspace**: Copy dari `templates/` folder
2. **Dari Git**: `git clone` atau `git checkout` dari `templates-repo/`
3. **Dari PDF**: Convert PDF ke HTML (menggunakan tools online) lalu edit
4. **Dari Notion**: Recreate berdasarkan dokumentasi struktur

### Command Reference

**Convert Surat Penawaran HTML ke PDF:**
```bash
cd /home/ubuntu/clawdbot-workspace/workspace/projects
wkhtmltopdf --page-size A4 --margin-top 15mm --margin-bottom 15mm \
  --margin-left 20mm --margin-right 20mm \
  surat-penawaran-jbw.html surat-penawaran-[CLIENT].pdf
```

**Convert Wireframe HTML ke PDF:**
```bash
cd /home/ubuntu/clawdbot-workspace/workspace/projects
wkhtmltopdf --page-size A4 --orientation landscape \
  --margin-top 5mm --margin-bottom 5mm \
  --margin-left 5mm --margin-right 5mm \
  ecobliss-wireframe-browser.html wireframe-[PROJECT].pdf
```

**Backup to Git:**
```bash
cd /home/ubuntu/clawdbot-workspace/workspace/templates-repo
git add .
git commit -m "Update templates [DATE]"
```

---

## 💳 Bank Account Information

### Rekening Pembayaran JagoBikinWebsite

| Bank | No. Rekening | Atas Nama |
|------|-------------|-----------|
| BCA | 6755381296 | Muhammad Zaki Achsan |

**Catatan:** Informasi ini digunakan untuk pembayaran DP dan pelunasan project.

**History:**
- 2026-02-05: Ditambahkan rekening BCA 6755381296 a.n Muhammad Zaki Achsan

---

## 📄 Invoice Policy

### Jatuh Tempo
**Semua invoice: 7 hari** dari tanggal invoice diterbitkan.

### Template Invoice
Tersedia 3 template untuk berbagai tahap pembayaran:

| Template | File | Kegunaan |
|----------|------|----------|
| DP | `templates/invoice-template-dp.html` | Down payment awal project |
| Progress | `templates/invoice-template-progress.html` | Pembayaran tengah project |
| Final | `templates/invoice-template-final.html` | Pelunasan akhir project |
| Generic | `templates/invoice-template.html` | Template fleksibel (variable) |

**Format:** A4, Times New Roman, Tanda tangan Dancing Script (ZakiAchsan)

### Struktur Pembayaran (3 Fase)
1. **DP** - 30-50% (project dimulai)
2. **Progress** - 30-40% (project 50-70% selesai)
3. **Final** - Sisa (file diserahkan setelah pelunasan)

### Konversi ke PDF
```bash
cd /home/ubuntu/clawdbot-workspace/workspace/projects
wkhtmltopdf --page-size A4 --margin-top 10mm --margin-bottom 10mm \
  --margin-left 15mm --margin-right 15mm \
  invoice-[CLIENT].html invoice-[CLIENT].pdf
```

**History:**
- 2026-02-10: Update jatuh tempo dari 7 hari menjadi 3 hari untuk semua client
- 2026-02-10: Revert ke 7 hari, buat 3 template terpisah (DP/Progress/Final)

---

## Deployment Policy

### Revert Plan Required
**Selalu siapkan plan revert sebelum push ke production.**

Karena deployment langsung ke prod via GitHub Actions, setiap perubahan harus disertai dengan:

1. **Revert Command**: Siapkan perintah git revert/reset sebelum push
2. **Commit Tracking**: Catat commit ID sebelum dan sesudah perubahan
3. **Backup Branch**: Pertimbangkan buat branch backup jika perubahan besar

**Template Revert Plan:**
```
Revert Plan for [Feature/Bugfix]:
- Commit sebelum perubahan: [OLD_COMMIT_ID]
- Commit perubahan: [NEW_COMMIT_ID]
- Revert command: git revert [NEW_COMMIT_ID] --no-edit && git push
- Hard reset (if needed): git reset --hard [OLD_COMMIT_ID] && git push --force
```

**Contoh:**
- Mobile menu fix: `3836d46` (sebelum) → `637a32f` (sesudah)
- Revert: `git revert 637a32f 254516a --no-edit && git push origin main`
