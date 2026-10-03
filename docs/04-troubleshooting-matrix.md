# 🔍 Troubleshooting Matrix

| Gejala Error | Kemungkinan Penyebab Utama | Langkah Diagnosa & Solusi |
| :--- | :--- | :--- |
| **No Display (Kipas berputar, lampu menyala)** | - RAM kurang menancap presisi<br>- Kabel monitor colok ke Motherboard (bukan GPU)<br>- GPU sag / kurang pas di slot | 1. Tancapkan kabel monitor langsung ke port GPU.<br>2. Re-seat RAM (lepas, bersihkan pin dengan penghapus, pasang 1 keping dulu di slot A2).<br>3. Re-seat GPU dan pastikan kuncian PCIe mengklik. |
| **Debug LED Motherboard (EZ Debug LED)** | - **CPU:** Pin tertekuk / BIOS belum support<br>- **DRAM:** Inkompatibilitas XMP / slot salah<br>- **VGA:** GPU power belum terpasang<br>- **BOOT:** Media OS tidak terdeteksi | 1. **DRAM:** Clear CMOS (lepas baterai CR2032 5 menit).<br>2. **CPU:** Flash BIOS via tombol *Flash BIOS Button*.<br>3. **BOOT:** Cek mode BIOS (UEFI vs Legacy CSM). |
| **PC Mati mendadak saat Stress Test** | - Thermal Throttling Extreme (Overheat)<br>- PSU Over Current / Daya kurang<br>- Kabel 8-pin CPU/PCIe longgar | 1. Pantau suhu CPU/GPU di HWInfo sebelum PC mati.<br>2. Periksa apakah plastik dasar cooler lupa dilepas.<br>3. Ganti PSU dengan daya yang lebih besar/berkualitas. |
| **BSOD (Blue Screen) Berulang** | - Driver GPU/Chipset korup<br>- XMP RAM tidak stabil<br>- Bad Sector / SSD Corrupt | 1. Matikan profil XMP/EXPO di BIOS.<br>2. Jalankan `sfc /scannow` di Command Prompt.<br>3. Tes RAM menggunakan MemTest86. |
