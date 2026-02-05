# Wireframe Template Format

Format standar untuk membuat wireframe UI/UX. Template ini digunakan sebagai referensi untuk setiap project baru.

---

## Format Wireframe

### 1. Browser Frame
Setiap wireframe harus ditampilkan dalam frame browser untuk memberikan konteks website:

```
+----------------------------------------------------------+
|  [●] [●] [●]  https://domain.com/page                    |
+----------------------------------------------------------+
|  APP HEADER - System Name                    User | Role |
+----------------------------------------------------------+
|  Menu1 | Menu2 | Menu3 | Menu4 | Menu5 | Menu6 | Menu7   |
+----------------------------------------------------------+
|                                                          |
|  CONTENT AREA                                            |
|                                                          |
+----------------------------------------------------------+
|  Footer info                                    Page X   |
+----------------------------------------------------------+
```

**Komponen Browser Frame:**
- **Browser Dots**: Red, yellow, green (macOS style)
- **Address Bar**: URL lengkap ke halaman
- **App Header**: Background biru gelap, system name, user info
- **Navigation**: Menu items dengan active state
- **Content Area**: Area utama konten
- **Footer**: Info tambahan dan page number

---

### 2. Layout Structure

#### Header Section
- **Page Title**: H1 dengan border bottom
- **Back Navigation**: Link kembali (jika applicable)

#### Content Sections

**A. Metric Cards (Dashboard)**
```
+--------+  +--------+  +--------+  +--------+
| VALUE  |  | VALUE  |  | VALUE  |  | VALUE  |
| Label  |  | Label  |  | Label  |  | Label  |
+--------+  +--------+  +--------+  +--------+
```
- 4 cards dalam 1 baris horizontal
- Background light gray
- Border radius 6px
- Value: font besar (24-28px), bold, warna biru
- Label: font kecil (10-11px), gray

**B. Data Tables**
```
+-------------------------------------------+
| Header Panel                              |
+-------------------------------------------+
| Col1 | Col2 | Col3 | Col4 | Col5 | Action|
+-------------------------------------------+
| Data | Data | Data | Data | Data | [Btn] |
| Data | Data | Data | Data | Data | [Btn] |
+-------------------------------------------+
| Pagination: [<] [1] [2] [3] ... [>]       |
+-------------------------------------------+
```
- Header dengan background abu-abu muda
- Compact font (9-10px)
- Padding minimal (3-5px)
- Badges untuk status
- Action buttons di kolom terakhir

**C. Detail View (Horizontal Table)**
```
Label1: [Value]    Label2: [Value]    Label3: [Value]    Label4: [Value]
Label5: [Value]    Label6: [Value]    Label7: [Value]    Label8: [Value]
```
- Menggunakan tabel HTML (bukan grid)
- 2 baris x 4 kolom (atau sesuai kebutuhan)
- Label: font 8px, gray, uppercase
- Value: font 9-10px, bold, dark
- Padding: 2px 4px

**D. Two Column Layout**
```
+------------------+  +------------------+
|   Panel Left     |  |   Panel Right    |
|                  |  |                  |
|   Content        |  |   Content        |
|                  |  |                  |
+------------------+  +------------------+
```
- Flex/grid 2 kolom
- Gap: 8-12px
- Equal height panels

**E. Form Inputs**
```
Label:
[Input Field                    ]

Label:
[Dropdown              [v]]

[Button]
```
- Label: font 8px, gray
- Input: padding 2-4px, font 9px
- Full width dalam container

**F. Step Wizard**
```
+--------+  +--------+  +--------+
|   1    |  |   2    |  |   3    |
|  Step  |  |  Step  |  |  Step  |
|  Name  |  |  Name  |  |  Name  |
+--------+  +--------+  +--------+
```
- 3 steps horizontal
- Active step: background biru, white text
- Inactive: background gray, border

**G. Progress Bar**
```
Label                    XX%
[████████████████░░░░░░░░░░]
Subtitle info
```
- Height: 6-8px
- Fill color: green
- Background: light gray
- Label dan percentage di atas

---

### 3. Color Palette

**Primary Colors:**
- Header Blue: `#1e3a5f`
- Nav Blue: `#2c5282`
- Primary Button: `#2563eb`
- Success: `#10b981`
- Warning: `#f59e0b`
- Danger: `#dc2626`

**Neutral Colors:**
- Background: `#f9fafb` / `#f3f4f6`
- Border: `#e5e7eb`
- Text Dark: `#1f2937`
- Text Gray: `#6b7280`
- Text Light: `#9ca3af`

**Status Badges:**
- Open: bg `#dbeafe`, text `#1d4ed8`
- Partial: bg `#fef3c7`, text `#92400e`
- Closed: bg `#d1fae5`, text `#047857`
- Warning: bg `#fee2e2`, text `#dc2626`

---

### 4. Typography Scale

| Element | Size | Weight | Color |
|---------|------|--------|-------|
| Page Title | 16px | Bold | `#1e3a5f` |
| Panel Header | 10-11px | Semi-bold | `#374151` |
| Table Header | 9-10px | Semi-bold | `#4b5563` |
| Table Data | 9px | Normal | `#1f2937` |
| Metric Value | 24-28px | Bold | `#2563eb` |
| Metric Label | 10-11px | Normal | `#6b7280` |
| Form Label | 8px | Normal | `#6b7280` |
| Badge | 8px | Medium | various |
| Button | 9px | Medium | white/gray |

---

### 5. Spacing Guidelines

**Container:**
- Page padding: 5-8mm
- Panel margin bottom: 6-10px

**Panel:**
- Header padding: 3-4px vertical, 8-10px horizontal
- Body padding: 6-10px

**Components:**
- Card padding: 10-12px
- Table cell padding: 3-5px
- Button padding: 3-4px vertical, 8-10px horizontal
- Input padding: 2-4px
- Gap between elements: 6-12px

---

### 6. Screen Checklist

Setiap screen wireframe harus mencakup:

- [ ] Browser frame dengan dots dan address bar
- [ ] App header dengan system name dan user info
- [ ] Navigation menu dengan active state
- [ ] Page title
- [ ] Main content area
- [ ] Page footer

**Konten per screen type:**

**Dashboard:**
- [ ] 4 metric cards (1 baris)
- [ ] Chart/visualization (jika ada)
- [ ] Data tables
- [ ] Warning/alerts section

**List View:**
- [ ] Filter bar (search, dropdowns, buttons)
- [ ] Data table
- [ ] Pagination
- [ ] Action buttons

**Detail View:**
- [ ] Detail info (horizontal table layout)
- [ ] Related data tables
- [ ] Action buttons
- [ ] Form inputs (jika ada)

**Form/Input:**
- [ ] Step indicator (jika multi-step)
- [ ] Form fields dengan labels
- [ ] Action buttons
- [ ] Validation messages (jika ada)

---

### 7. Contoh Lengkap

Lihat implementasi lengkap di:
- **HTML Template**: `ecobliss-wireframe-browser.html`
- **PDF Output**: `ecobliss-wireframe-browser.pdf`

**Screens yang tersedia:**
1. Dashboard - Metrics, tables, charts
2. List View - Filter, table, pagination
3. Detail View - Detail info, history, form
4. Import Wizard - Step indicator, upload, preview
5. Additional - Logistik, kontrak, forecast

---

### 8. Tips

1. **Selalu gunakan browser frame** - Memberikan konteks website
2. **Font size minimal 7-8px** - Tetap readable saat di-print
3. **Padding minimalis** - 2-5px untuk compact layout
4. **Gunakan tabel untuk detail** - Lebih efisien dari grid
5. **Two columns untuk layout kompleks** - Hemat space vertikal
6. **Page footer dengan info** - Page number, timestamps
7. **Test print** - Pastikan semua muat di 1 halaman A4 landscape

---

**Last Updated**: 2026-02-05  
**Reference Project**: Ecobliss PO System Wireframe
