# JagoBikinWebsite Templates

Repository ini berisi template-template standar yang digunakan oleh JagoBikinWebsite untuk dokumentasi project, wireframe, dan surat penawaran.

## Templates Tersedia

### 1. Surat Penawaran (HTML)
**File**: `surat-penawaran-jbw.html`

Template surat penawaran profesional dengan format:
- Kop surat (nama, alamat, kontak)
- Judul SURAT PENAWARAN
- Tujuan surat
- Tabel penawaran (6 kolom)
- Syarat & ketentuan
- Tanda tangan dengan font signature

**Cara penggunaan**:
1. Buka file HTML
2. Edit isi sesuai client/project
3. Print to PDF atau gunakan wkhtmltopdf

**Kontak default**:
- Telepon: 6285694662592
- Email: jagobikinwebsite28@gmail.com
- Website: jagobikinwebsite.com
- Alamat: Green Andara Residence blok C6, No.7

---

### 2. Wireframe Template (HTML)
**File**: `ecobliss-wireframe-browser.html`

Template wireframe/UI mockup dengan browser frame. Format ini digunakan sebagai referensi untuk semua project wireframe.

**Fitur**:
- Browser frame (dots, address bar)
- App header dan navigation
- Metric cards (4 dalam 1 baris)
- Data tables
- Detail view (horizontal layout)
- Form inputs
- Step wizard

**Screens included**:
1. Dashboard
2. PO List
3. PO Detail
4. Import Data
5. Logistik & Kontrak

**Cara penggunaan**:
1. Copy file sebagai base
2. Modifikasi konten sesuai project
3. Convert ke PDF dengan wkhtmltopdf

---

### 3. Product Plan Template (Markdown)
**File**: `product-plan-template.md`

Template untuk membuat dokumen product plan/project requirements.

**Struktur**:
1. Latar Belakang & Goals
2. Data/Context
3. Fitur-Fitur Sistem
4. Tahap Pengembangan
5. Langkah Selanjutnya

---

### 4. Wireframe Format Guidelines (Markdown)
**File**: `wireframe-format-template.md`

Panduan lengkap format wireframe termasuk:
- Browser frame specifications
- Layout structure
- Color palette
- Typography scale
- Spacing guidelines

---

### 5. Invoice Template (HTML)
**File**: `invoice-jbw.html`

Template invoice profesional dengan format:
- Header: Logo company + Judul INVOICE
- Issued To: Nama client & alamat
- Invoice Meta: Date, Due Date, Invoice #
- Tabel Items: Description, Qty, Total
- Total: Subtotal, Tax, Grand Total
- Payment Info: BCA 6755381296 a.n Muhammad Zaki Achsan
- Signature: ZakiAchsan (signature font)

**Placeholder yang perlu diisi:**
- [NAMA CLIENT / PT]
- [ALAMAT CLIENT]
- [DD.MM.YYYY] untuk date & due date
- [INV/XXX/2025] untuk nomor invoice
- [Deskripsi Item] & [HARGA]
- [SUBTOTAL] & [TOTAL]

**Cara penggunaan**:
1. Buka file HTML
2. Ganti placeholder [...] dengan data client
3. Edit items sesuai project
4. Update total harga
5. Convert ke PDF (lihat command di bawah)

---

### 6. Invoice Partial Payment Template (HTML)
**File**: `invoice-partial-payment-template.html`

Template invoice untuk penagihan sisa pembayaran (partial payment) dengan format:
- Header: Logo company + Judul INVOICE + Status Badge (Partial Payment)
- Issued To: Nama client & alamat
- Invoice Meta: Date, Due Date, Invoice #, Reference #
- Tabel Items: Description, Total
- **Payment History**: Menunjukkan pembayaran yang sudah diterima
- **Outstanding Balance**: Menunjukkan sisa tagihan yang belum dibayar
- Total Summary: Project Total, Amount Paid, Balance Due
- Payment Info: BCA 6755381296 a.n Muhammad Zaki Achsan
- Notes: Penjelasan tentang partial payment
- Signature: ZakiAchsan (signature font)

**Fitur khusus:**
- ✅ Menampilkan riwayat pembayaran (down payment)
- ✅ Menampilkan sisa tagihan yang harus dibayar
- ✅ Status badge "Partial Payment"
- ✅ Reference ke invoice sebelumnya
- ✅ Bahasa Inggris (lebih formal untuk corporate)

**Placeholder yang perlu diisi:**
- [NAMA CLIENT / PT]
- [ALAMAT CLIENT]
- [DD.MM.YYYY] untuk date & due date
- [INV/XXX/2026] untuk nomor invoice
- [Reference invoice sebelumnya]
- [Deskripsi Project]
- [Total Project], [Amount Paid], [Balance Due]

**Cara penggunaan**:
1. Buka file HTML
2. Ganti placeholder [...] dengan data client
3. Edit deskripsi project dan nama website
4. Update payment history (down payment yang sudah diterima)
5. Update outstanding balance (sisa yang harus dibayar)
6. Convert ke PDF

---

## Cara Convert HTML ke PDF

### Using wkhtmltopdf

**Surat Penawaran (A4)**:
```bash
wkhtmltopdf --page-size A4 --margin-top 15mm --margin-bottom 15mm \
  --margin-left 20mm --margin-right 20mm \
  surat-penawaran-jbw.html surat-penawaran.pdf
```

**Wireframe (A4 Landscape)**:
```bash
wkhtmltopdf --page-size A4 --orientation landscape \
  --margin-top 5mm --margin-bottom 5mm \
  --margin-left 5mm --margin-right 5mm \
  ecobliss-wireframe-browser.html wireframe.pdf
```

**Invoice (A4)**:
```bash
wkhtmltopdf --page-size A4 --margin-top 15mm --margin-bottom 15mm \
  --margin-left 20mm --margin-right 20mm \
  invoice-jbw.html invoice-client.pdf
```

**Invoice Partial Payment (A4)**:
```bash
wkhtmltopdf --page-size A4 --margin-top 15mm --margin-bottom 15mm \
  --margin-left 20mm --margin-right 20mm \
  invoice-partial-payment-template.html invoice-partial.pdf
```

---

## Notion References

Templates ini juga direferensikan di Notion:

- **Product Plan**: https://www.notion.so/Ecobliss-PO-Logistics-Management-System-Product-Plan-2feb2f46cfa3818abbcce2410b436bb1
- **Wireframe Basic**: https://www.notion.so/Ecobliss-PO-System-Wireframe-2feb2f46cfa38125ad52eb7f104802c8
- **Wireframe Detailed**: https://www.notion.so/Ecobliss-PO-System-Wireframe-Detailed-2feb2f46cfa38160902dd8840391e162
- **Surat Penawaran**: https://www.notion.so/Template-Surat-Penawaran-JagoBikinWebsite-2feb2f46cfa381269a50d2657177ee53

---

## Last Updated
2026-02-07

**Updates**:
- Added Invoice Template (invoice-jbw.html & invoice-jbw.pdf)
- Added Invoice Partial Payment Template (invoice-partial-payment-template.html & .pdf)
- Updated README with invoice templates documentation

**Author**: Zaki Achsan
**Company**: JagoBikinWebsite
