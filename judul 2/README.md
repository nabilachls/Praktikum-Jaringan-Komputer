# Judul 2 Praktikum Jaringan Komputer - VLAN dan Crimping

## 🖼️ Topologi Jaringan

Berikut adalah diagram skema topologi jaringan yang telah dibuat pada Cisco Packet Tracer:

![Topologi Jaringan Judul 2](./Screenshot%202026-10-08%20201054.png)

### Komponen Perangkat:
- **PC-A:** Generic PC (PC-PT) - Client pada VLAN 10 (Operations) terhubung ke Switch2 pada port FastEthernet0/6
- **Switch2 (S1):** Cisco Catalyst 2960-24TT - Switch 1 dengan konfigurasi VLAN 10 dan VLAN 99 (Management), terhubung ke Switch3 via Trunk port FastEthernet0/1
- **Switch3 (S2):** Cisco Catalyst 2960-24TT - Switch 2 dengan konfigurasi VLAN 10 dan VLAN 99 (Management), terhubung ke Switch2 via Trunk port FastEthernet0/1
- **PC-B:** Generic PC (PC-PT) - Client pada VLAN 10 (Operations) terhubung ke Switch3 pada port FastEthernet0/18

---

## 📁 Berkas Simulasi

File proyek simulasi Cisco Packet Tracer dapat diunduh dan dibuka langsung:
- **File PKT:** [`judul2pjk.pkt`](./judul2pjk.pkt)

---

## 🎥 Video Demonstrasi

Demonstrasi simulasi dan pengujian koneksi (konfigurasi VLAN, trunking, dan uji ping) dapat disaksikan melalui video YouTube berikut:

[![Demo Video Praktikum 2](https://img.youtube.com/vi/3sQ_u75AonM/maxresdefault.jpg)](https://youtu.be/3sQ_u75AonM)

🔗 **Link Video YouTube:** [https://youtu.be/3sQ_u75AonM](https://youtu.be/3sQ_u75AonM)

---
