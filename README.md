# README - Hoan Pham Downloader

![Version](https://img.shields.io/badge/version-1.0.0-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![Status](https://img.shields.io/badge/status-active-success)

> Trang web tải video đa nền tảng với giao diện Dark Mode hiện đại, lấy cảm hứng từ "Hoan Pham Downloader".

---

## 📋 Mục lục

- [Giới thiệu](#-giới-thiệu)
- [Tính năng chính](#-tính-năng-chính)
- [Giao diện](#-giao-diện)
- [Công nghệ sử dụng](#-công-nghệ-sử-dụng)
- [Cài đặt & Chạy thử](#-cài-đặt--chạy-thử)
- [Cấu trúc dự án](#-cấu-trúc-dự-án)
- [Hướng dẫn sử dụng](#-hướng-dẫn-sử-dụng)
- [Tùy chỉnh](#-tùy-chỉnh)
- [Roadmap](#-roadmap)
- [Đóng góp](#-đóng-góp)
- [License](#-license)
- [Tác giả](#-tác-giả)

---

## 🎯 Giới thiệu

**Hoan Pham Downloader** là một giao diện web (frontend) mô phỏng công cụ tải video đa nền tảng, cho phép người dùng dán liên kết từ các mạng xã hội phổ biến như **YouTube, TikTok, Instagram, Facebook, Reddit, Vimeo, SoundCloud** và tải xuống với nhiều tùy chọn chất lượng.

Dự án tập trung vào **trải nghiệm người dùng (UX)** và **giao diện (UI)** với phong cách Dark Mode hiện đại, gradient tím-hồng, và các hiệu ứng chuyển động mượt mà.

> ⚠️ **Lưu ý**: Đây là dự án **demo frontend**. Quá trình phân tích và tải video được **mô phỏng** bằng JavaScript. Để hoạt động thực tế, cần tích hợp backend xử lý (ví dụ: `yt-dlp`, `youtube-dl`, API bên thứ ba...).

---

## ✨ Tính năng chính

### 🎨 Giao diện (UI/UX)
- ✅ Dark Mode hiện đại với nền tối `#0d0e15`
- ✅ Gradient Purple/Pink (`#a855f7` → `#ec4899`) làm điểm nhấn
- ✅ Hiệu ứng mượt mà: hover, active, transition
- ✅ Responsive hoàn hảo (Mobile-first, hỗ trợ Desktop)
- ✅ Toast notification giả lập
- ✅ Progress bar động với animation

### 🔧 Chức năng
- ✅ **Tab Navigation**: Chuyển đổi giữa "Một liên kết" / "Nhiều liên kết"
- ✅ **Auto-detect Platform**: Tự động nhận diện nền tảng từ URL
- ✅ **Paste từ Clipboard**: Nút dán nhanh với Clipboard API
- ✅ **Video Preview Card**: Hiển thị thumbnail, tiêu đề, thông tin video
- ✅ **Chọn định dạng**: Video / Âm thanh
- ✅ **Chọn chất lượng**: 1024p, 720p, 480p, 144p, Original
- ✅ **Progress Bar**: Mô phỏng tiến trình tải 0% → 100%
- ✅ **Online Counter**: Số người online tự động thay đổi
- ✅ **Horizontal Toolbar**: Danh sách nền tảng hỗ trợ cuộn ngang

### 🌐 Nền tảng được hỗ trợ

| Nền tảng | Icon | Màu nhận diện |
|----------|------|---------------|
| YouTube | `fa-youtube` | 🔴 Red |
| TikTok | `fa-tiktok` | ⚪ White |
| Instagram | `fa-instagram` | 💗 Pink |
| Facebook | `fa-facebook` | 🔵 Blue |
| Reddit | `fa-reddit` | 🟠 Orange |
| Vimeo | `fa-vimeo` | 🔵 Light Blue |
| SoundCloud | `fa-soundcloud` | 🟠 Orange |

---

## 🖼 Giao diện

### Bố cục trang (từ trên xuống)

| # | Khu vực | Mô tả |
|---|---------|-------|
| 1 | **Header** | Logo chữ `H` gradient + tên "Hoan Pham Downloader" bên trái, badge "🟢 4 đang online" bên phải |
| 2 | **Slogan** | Tiêu đề gradient: "NỘI DUNG BẠN YÊU THÍCH, LUÔN SẴN SÀNG" + mô tả phụ |
| 3 | **Tab Navigation** | 2 nút bo tròn: `🔗 Một liên kết` và `📑 Nhiều liên kết` |
| 4 | **Input Area** | Ô nhập link lớn + nút dán 📋 + badge nhận diện nền tảng |
| 5 | **CTA Button** | Nút "⬇️ Tải xuống" gradient tím-hồng |
| 6 | **Video Card** | Thumbnail + tiêu đề + chọn Video/Âm thanh + dropdown chất lượng + nút "💾 Lưu tập" + progress bar |
| 7 | **Toolbar** | Dải icon mạng xã hội cuộn ngang: YT, TT, IG, FB, RD, VM, SC... |
| 8 | **Footer** | `hoanpham-downloader.vercel.app` bên trái, `🔒 Riêng tư` bên phải |

### Preview giao diện
