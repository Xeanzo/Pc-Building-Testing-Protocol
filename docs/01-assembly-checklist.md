# 🛠️ Step-by-Step Assembly Checklist

### Phase 1: Preparation & Safety
- [ ] Area kerja bersih, teratur, dan terhindar dari akumulasi listrik statis (ESD).
- [ ] Baut casing, stand-off, bracket CPU cooler, dan cable ties disiapkan.
- [ ] Verifikasi ketersediaan I/O Shield (jika tidak terintegrasi di motherboard).

### Phase 2: Out-of-Case Component Assembly
- [ ] Buka pengunci soket CPU, pasang CPU sesuai penanda segitiga di sudut.
- [ ] Pasang RAM pada slot A2 & B2 hingga pengunci berbunyi "klik" penuh.
- [ ] Pasang SSD M.2 NVMe utama pada slot M.2 teratas (slot PCIe direct to CPU) lengkap dengan thermal pad heatsink.
- [ ] Pasang CPU Cooler / Water Block AIO (Pastikan plastik pelindung murni tembaga dibuka).
- [ ] Tancapkan kabel 24-Pin ATX dan 8-Pin CPU dari PSU ke motherboard.
- [ ] Tancapkan GPU pada slot PCIe x16 teratas, hubungkan kabel PCIe power.
- [ ] **Shorting Power SW Pin:** Lakukan booting di luar casing untuk memastikan BIOS beroperasi (POST Success).

### Phase 3: In-Case Installation
- [ ] Pasang PSU ke casing beserta kabel modular yang dibutuhkan.
- [ ] Pasang stand-off motherboard pada casing sesuai form factor (ATX/mATX/ITX).
- [ ] Masukkan motherboard ke casing dan kencangkan baut secara menyilang (cross-tightening).
- [ ] Pasang kipas casing (Case Fans) sesuai konfigurasi airflow (Intake vs Exhaust).
- [ ] Pasang Radiator AIO di posisi Atas (Top) atau Depan (Front dengan selang di bawah).

### Phase 4: Cable Management & Final Hookup
- [ ] Pasang Front Panel Header (Power SW, Reset SW, Power LED, HDD LED).
- [ ] Pasang Front Panel Audio Header (HD Audio) & USB 2.0 / USB 3.0 / Type-C.
- [ ] Sambungkan power kabel PCIe GPU (Gunakan kabel terpisah dari PSU, hindari *daisy-chain/pigtail* untuk GPU dengan TDP >220W).
- [ ] Rapikan kabel di bagian belakang casing menggunakan zip-ties / Velcro.
- [ ] Pastikan tidak ada kabel yang tersangkut di bilah kipas.
