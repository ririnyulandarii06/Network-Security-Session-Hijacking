Network-Security-Session-Hijacking

**Oleh:**
* **Nama:** [Ririn Yulandari]
* **NIM:** [105841117923]

---
Proyek ini mendokumentasikan proses simulasi serangan Man-in-the-Middle (MITM) untuk melakukan Session Hijacking pada protokol Telnet yang tidak terenkripsi menggunakan Kali Linux.

🛠️ Alat yang Digunakan
Kali Linux sebagai mesin penyerang.

Bettercap untuk melakukan ARP Spoofing dan Sniffing.

Wireshark untuk analisis paket data lebih mendalam.

Telnet sebagai protokol target serangan.

🚀 Langkah-langkah Simulasi
Konfigurasi Jalur Data: Mengaktifkan IP Forwarding pada sistem agar paket dapat diteruskan melalui mesin penyerang.

ARP Spoofing: Mengelabui tabel ARP pada Client dan Server agar semua lalu lintas data melewati Kali Linux.

Packet Sniffing: Menangkap lalu lintas data secara real-time untuk mendapatkan informasi sensitif.

Analisis Data: Menggunakan fitur "Follow TCP Stream" pada Wireshark untuk melihat username dan password dalam bentuk teks biasa (cleartext).

📊 Hasil Analisis
Berdasarkan pengujian, protokol Telnet terbukti sangat rentan karena mengirimkan data tanpa enkripsi, sehingga kredensial pengguna dapat dicuri dengan mudah melalui teknik MITM.
