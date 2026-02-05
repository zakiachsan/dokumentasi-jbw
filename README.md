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

---

## Notion References

Templates ini juga direferensikan di Notion:

- **Product Plan**: https://www.notion.so/Ecobliss-PO-Logistics-Management-System-Product-Plan-2feb2f46cfa3818abbcce2410b436bb1
- **Wireframe Basic**: https://www.notion.so/Ecobliss-PO-System-Wireframe-2feb2f46cfa38125ad52eb7f104802c8
- **Wireframe Detailed**: https://www.notion.so/Ecobliss-PO-System-Wireframe-Detailed-2feb2f46cfa38160902dd8840391e162
- **Surat Penawaran**: https://www.notion.so/Template-Surat-Penawaran-JagoBikinWebsite-2feb2f46cfa381269a50d2657177ee53

---

## Last Updated
2026-02-05

**Author**: Zaki Achsan
**Company**: JagoBikinWebsite
