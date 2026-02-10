# Supply Chain Management System 🚚⚡

![Node.js](https://img.shields.io/badge/Node.js-18-green)
![React](https://img.shields.io/badge/React-18-blue)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-14-blue)
![License](https://img.shields.io/badge/License-MIT-yellow)
![Status](https://img.shields.io/badge/Status-Production%20Ready-success)

Sistem manajemen rantai pasokan dan kualitas makanan yang komprehensif dengan fitur AI monitoring, e-catalog terkunci, dan blind receiving system.

## ✨ Fitur Utama

### 🔒 Modul Integrasi SPPG & Koperasi
- **e-Catalog Locked Price**: Harga terkunci berdasarkan kontrak
- **Auto PO Generator**: Pesanan otomatis berdasarkan kebutuhan
- **Digital Scale Integration**: Integrasi timbangan Bluetooth/IoT
- **Blind Receiving**: Petugas tidak tahu jumlah yang diharapkan
- **Double Verification**: Validasi oleh 2 petugas berbeda
- **Real-time Return**: Potongan otomatis untuk barang rusak

### 📱 Modul Penerima Manfaat
- **QR Code Unique ID**: Setiap box makanan memiliki QR unik
- **Photo Evidence**: Foto dengan geotagging saat penyerahan
- **Review & Rating**: Sistem feedback otomatis
- **Random Audit**: Verifikasi acak oleh owner
- **Anti-Fiktif**: Validasi data penerima manfaat

### 📊 Modul Monitoring Owner
- **Variance Analysis Dashboard**: Grafik planned vs actual
- **AI Anomaly Detection**: Deteksi penyimpangan otomatis
- **Non-Cash Policy**: Semua transaksi via transfer
- **Access Hierarchy**: Approval berjenjang untuk perubahan data

## 🏗️ Arsitektur Teknologi
┌─────────────────┐ ┌─────────────────┐ ┌─────────────────┐
│ Frontend │ │ Backend API │ │ Database │
│ React 18 │────│ Node.js/ │────│ PostgreSQL 14 │
│ Material-UI │ │ Express.js │ │ │
│ Recharts │ │ WebSocket │ └─────────────────┘
└─────────────────┘ └─────────────────┘ │
│ │ │
└──────────────────────┼─────────────────────┘
│
┌─────────────────┐
│ Monitoring │
│ & Analytics │
│ AI Detection │
└─────────────────┘
