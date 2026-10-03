# ⚙️ BIOS & OS Configuration Protocol

### Phase 1: BIOS / UEFI Setup
1. **Update BIOS:** Lakukan update BIOS ke versi stabil terbaru via USB Flashdrive (FAT32) jika diperlukan support CPU generasi baru.
2. **Enable XMP / EXPO:** Aktifkan profil Extreme Memory Profile (Intel) atau EXPO (AMD) agar RAM berjalan pada kecepatan advertised.
3. **Resizable BAR / Above 4G Decoding:** Pastikan fitur ini **Enabled** untuk performa GPU modern (NVIDIA RTX / AMD Radeon).
4. **Boot Order:** Set USB Flashdrive Bootable sebagai prioritas boot pertama.
5. **Fan Curve Setup:** Atur profile fan PWM (Silent / Balanced / Performance) berdasarkan sensor suhu CPU.

### Phase 2: OS Installation & Drivers
1. **Windows Installation:** Install Windows (Clean Install) via bootable USB Media Creation Tool.
2. **Chipset Driver:** Install Chipset Driver terbaru langsung dari website produsen (Intel/AMD), bukan dari Windows Update.
3. **GPU Driver:** Install GPU Driver versi WHQL terbaru (NVIDIA GeForce Experience/App atau AMD Adrenalin).
4. **Audio & LAN/Wi-Fi Driver:** Install driver jaringan & audio resmi dari halaman support motherboard.

### Phase 3: OS Optimization
- [ ] Matikan Startup App yang tidak diperlukan pada Task Manager.
- [ ] Aktifkan Power Plan **High Performance** atau **Balanced**.
- [ ] Pastikan Refresh Rate monitor sudah diatur ke maksimum pada Display Settings.
- [ ] Verifikasi Windows Defender & Windows Update berjalan terbaru.
