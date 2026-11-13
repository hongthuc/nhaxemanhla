<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>Nhà Xe Mạnh La - Chuyên Tuyến Đà Nẵng Đi Thái Bình | nhaxemanhla.com</title>
    <meta name="description" content="Nhà xe Mạnh La (nhaxemanhla.com) chuyên tuyến Đà Nẵng đi Thái Bình và ngược lại. Xe giường nằm cao cấp, Limousine phòng VIP, nhận gửi hàng hóa, xe máy uy tín. Địa chỉ: 117 Lương Trúc Đàm, Phường Hòa Khánh, TP. Đà Nẵng. Hotline: 0988.026.577 - 0981.068.333.">

    <!-- THUMBNAIL KHI GỬI LINK TRANG WEB LÀ ẢNH LOGO TRANG WEB -->
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://nhaxemanhla.com/">
    <meta property="og:title" content="Nhà Xe Mạnh La - Chuyên Tuyến Đà Nẵng ⇄ Thái Bình | nhaxemanhla.com">
    <meta property="og:description" content="Hệ thống xe giường nằm & Limousine VIP chuyên tuyến Đà Nẵng - Thái Bình. Đón trả tận tâm, nhận gửi hàng hóa & xe máy siêu tốc. Đ/c: 117 Lương Trúc Đàm, P. Hòa Khánh, TP. Đà Nẵng.">
    <meta property="og:image" content="https://drive.google.com/thumbnail?id=1KOwoeHiDvElLvRAo4KmImG7UqxNjcPNW&sz=w800">
    <meta property="og:image:alt" content="Logo Nhà Xe Mạnh La nhaxemanhla.com">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:image" content="https://drive.google.com/thumbnail?id=1KOwoeHiDvElLvRAo4KmImG7UqxNjcPNW&sz=w800">
    <link rel="icon" type="image/png" href="https://drive.google.com/thumbnail?id=1KOwoeHiDvElLvRAo4KmImG7UqxNjcPNW&sz=w200">
    <link rel="apple-touch-icon" href="https://drive.google.com/thumbnail?id=1KOwoeHiDvElLvRAo4KmImG7UqxNjcPNW&sz=w200">

    <!-- Tailwind CSS & Font Inter + FontAwesome -->
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                    },
                    colors: {
                        brand: {
                            gold: '#D97706',      /* Màu vàng cam chủ đạo đồng bộ Văn Minh & Logo */
                            goldLight: '#FEF3C7',
                            amber: '#F59E0B',
                            red: '#B91C1C',       /* Màu đỏ thương hiệu vận tải Mạnh La */
                            redDark: '#991B1B',
                            navy: '#0F2942',      /* Màu xanh đậm tiêu đề chuẩn Flatsome */
                            green: '#15803D'
                        }
                    }
                }
            }
        }
    </script>

    <style>
        /* ĐẢM BẢO GIAO DIỆN KHÔNG TRÀN VIỀN, KHÔNG LỆCH SANG PHẢI TRÊN MỌI THIẾT BỊ */
        *, *::before, *::after {
            box-sizing: border-box;
        }
        html, body {
            width: 100%;
            max-width: 100%;
            overflow-x: hidden !important;
            margin: 0;
            padding: 0;
            font-family: 'Inter', sans-serif;
            background-color: #F8FAFC;
            color: #1E293B;
            scroll-behavior: smooth;
        }

        /* KHUNG GIAO DIỆN TRÊN MÁY TÍNH BẰNG 95% KÍCH THƯỚC MÀN HÌNH MÁY TÍNH */
        .flatsome-container {
            width: 100%;
            padding-left: 10px;
            padding-right: 10px;
            margin-left: auto;
            margin-right: auto;
        }
        @media (min-width: 1024px) {
            .flatsome-container {
                width: 95% !important;
                max-width: 95% !important;
                padding-left: 0;
                padding-right: 0;
            }
        }

        /* TÊN DANH MỤC TRÊN MÁY TÍNH VIẾT LIỀN TRÊN 1 HÀNG, KHÔNG ĐƯỢC XUỐNG DÒNG TÊN DANH MỤC */
        .desktop-nav-list {
            display: flex;
            flex-wrap: wrap;
            align-items: center;
            justify-content: center;
            gap: 4px;
        }
        .desktop-nav-item {
            white-space: nowrap !important;
            display: inline-flex;
            align-items: center;
            gap: 5px;
            font-size: 12.5px;
            font-weight: 600;
            padding: 7px 10px;
            border-radius: 6px;
            transition: all 0.2s ease;
            line-height: 1.2;
        }
        @media (min-width: 1280px) {
            .desktop-nav-item {
                font-size: 13px;
                padding: 8px 12px;
            }
        }

        /* TÊN SẢN PHẨM ĐẦY ĐỦ CHỮ, KHÔNG BỊ TRÀN RA NGOÀI HOẶC THIẾU CHỮ */
        .product-title-full {
            white-space: normal !important;
            word-wrap: break-word !important;
            overflow-wrap: break-word !important;
            display: block !important;
            overflow: visible !important;
            text-overflow: clip !important;
            line-height: 1.38;
        }

        /* HIỆU ỨNG NHẤP NHÁY NHẸ CHO NÚT NỔI */
        @keyframes pulseRing {
            0% { box-shadow: 0 0 0 0 rgba(185, 28, 28, 0.5); }
            70% { box-shadow: 0 0 0 10px rgba(185, 28, 28, 0); }
            100% { box-shadow: 0 0 0 0 rgba(185, 28, 28, 0); }
        }
        .floating-pulse {
            animation: pulseRing 2s infinite;
        }
    </style>
</head>
<body class="bg-slate-50 text-slate-800 antialiased">

    <!-- =====================================================================
         FLATSOME HEADER WRAPPER (ĐƠN GIẢN, DỄ DÀNG LÀM LẠI TRÊN UX BUILDER)
         Không có thanh công cụ UX Builder ở dòng trên cùng, không để nút Gọi ngay trên Header
    ====================================================================== -->
    <header id="header" class="w-full bg-white shadow-sm sticky top-0 z-40 border-b border-amber-200">
        
        <!-- TOP BAR (THÔNG TIN NHÀ XE MẠNH LA) -->
        <div class="bg-brand-navy text-white text-[11px] sm:text-xs py-1.5">
            <div class="flatsome-container flex flex-wrap items-center justify-between gap-2">
                <div class="flex items-center gap-2 sm:gap-4 truncate max-w-full">
                    <span class="inline-flex items-center gap-1 font-medium text-amber-300">
                        <i class="fa-solid fa-globe"></i> nhaxemanhla.com
                    </span>
                    <span class="hidden md:inline-flex items-center gap-1 text-slate-200">
                        <i class="fa-solid fa-location-dot text-amber-400"></i>
                        117 Lương Trúc Đàm, Phường Hòa Khánh, Tp.Đà Nẵng
                    </span>
                </div>
                <div class="flex items-center gap-3 ml-auto">
                    <span class="inline-flex items-center gap-1 text-amber-300 font-semibold">
                        <i class="fa-solid fa-phone-volume"></i> 0988.026.577 - 0981.068.333
                    </span>
                    <a href="https://www.facebook.com/manh.hoangvan.16503323/" target="_blank" rel="noopener noreferrer" class="hidden sm:inline-flex items-center gap-1 bg-blue-600 hover:bg-blue-500 text-white px-2 py-0.5 rounded text-[11px] font-medium transition">
                        <i class="fa-brands fa-facebook"></i> Facebook Nhà Xe
                    </a>
                </div>
            </div>
        </div>

        <!-- HEADER MAIN: LOGO CHỈNH GỌN NHỎ LẠI & DANH MỤC TRÊN MÁY TÍNH (KHÔNG ĐỂ NÚT GỌI NGAY) -->
        <div class="flatsome-container py-2">
            <div class="flex items-center justify-between gap-2">
                
                <!-- LOGO NHÀ XE MẠNH LA (GỌN NHỎ, RÕ NÉT) -->
                <a href="#trang-chu" class="flex items-center gap-2.5 shrink-0 group">
                    <div class="w-10 h-10 sm:w-11 sm:h-11 rounded-lg border border-amber-300 bg-amber-50 p-0.5 flex items-center justify-center overflow-hidden shrink-0 shadow-sm">
                        <img src="https://drive.google.com/thumbnail?id=1KOwoeHiDvElLvRAo4KmImG7UqxNjcPNW&sz=w400"
                             onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1KOwoeHiDvElLvRAo4KmImG7UqxNjcPNW';"
                             alt="Logo Nhà Xe Mạnh La"
                             class="w-full h-full object-contain rounded">
                    </div>
                    <div class="leading-tight">
                        <span class="block text-sm sm:text-base font-extrabold text-brand-red tracking-tight uppercase">
                            NHÀ XE MẠNH LA
                        </span>
                        <span class="block text-[10px] sm:text-[11px] font-semibold text-brand-gold">
                            Chuyên Tuyến Đà Nẵng ⇄ Thái Bình
                        </span>
                    </div>
                </a>

                <!-- MENU DANH MỤC TRÊN MÁY TÍNH: VIẾT LIỀN TRÊN 1 HÀNG, CHỮ NHỎ GỌN, KHÔNG XUỐNG DÒNG TÊN DANH MỤC -->
                <nav class="hidden lg:block flex-1 pl-3" aria-label="Danh mục chính trên máy tính">
                    <ul class="desktop-nav-list">
                        <li>
                            <a href="#trang-chu" class="desktop-nav-item bg-amber-500 text-white shadow-sm">
                                <i class="fa-solid fa-house text-[11px]"></i>Trang chủ
                            </a>
                        </li>
                        <li>
                            <a href="#lich-trinh" class="desktop-nav-item text-slate-700 hover:bg-amber-50 hover:text-brand-red">
                                <i class="fa-solid fa-route text-brand-gold text-[11px]"></i>Lịch trình Đà Nẵng - Thái Bình
                            </a>
                        </li>
                        <li>
                            <a href="#tien-ich-xe" class="desktop-nav-item text-slate-700 hover:bg-amber-50 hover:text-brand-red">
                                <i class="fa-solid fa-bus text-brand-gold text-[11px]"></i>Tiện ích dòng xe
                            </a>
                        </li>
                        <li>
                            <a href="#dich-vu-gui-hang" class="desktop-nav-item text-slate-700 hover:bg-amber-50 hover:text-brand-red">
                                <i class="fa-solid fa-box-open text-brand-gold text-[11px]"></i>Gửi hàng &amp; Trung chuyển
                            </a>
                        </li>
                        <li>
                            <a href="#he-thong-van-phong" class="desktop-nav-item text-slate-700 hover:bg-amber-50 hover:text-brand-red">
                                <i class="fa-solid fa-building text-brand-gold text-[11px]"></i>Hệ thống văn phòng
                            </a>
                        </li>
                        <li>
                            <a href="#form-bao-gia" class="desktop-nav-item text-slate-700 hover:bg-amber-50 hover:text-brand-red">
                                <i class="fa-solid fa-file-signature text-brand-gold text-[11px]"></i>Yêu cầu &amp; Báo giá
                            </a>
                        </li>
                        <li>
                            <a href="#tin-tuc" class="desktop-nav-item text-slate-700 hover:bg-amber-50 hover:text-brand-red">
                                <i class="fa-solid fa-newspaper text-brand-gold text-[11px]"></i>Tin tức
                            </a>
                        </li>
                        <li>
                            <a href="#doi-tac" class="desktop-nav-item text-slate-700 hover:bg-amber-50 hover:text-brand-red">
                                <i class="fa-solid fa-handshake text-brand-gold text-[11px]"></i>Đối tác
                            </a>
                        </li>
                        <li>
                            <a href="#ban-do-lien-he" class="desktop-nav-item text-slate-700 hover:bg-amber-50 hover:text-brand-red">
                                <i class="fa-solid fa-map-location-dot text-brand-gold text-[11px]"></i>Bản đồ &amp; Liên hệ
                            </a>
                        </li>
                    </ul>
                </nav>

                <!-- NÚT MỞ MENU DANH MỤC TRÊN ĐIỆN THOẠI (KHÔNG ĐỂ NÚT GỌI NGAY ĐỂ TRÁNH TRÀN VIỀN) -->
                <button id="mobileMenuBtn" type="button" onclick="toggleMobileMenu()" class="lg:hidden inline-flex items-center gap-1.5 px-2.5 py-1.5 rounded-lg bg-amber-50 border border-amber-300 text-brand-navy text-xs font-bold">
                    <i class="fa-solid fa-bars text-sm text-brand-red"></i>
                    <span>Danh mục</span>
                </button>
            </div>

            <!-- MENU DANH MỤC MỞ RỘNG TRÊN ĐIỆN THOẠI (THIẾT KẾ ĐẸP, CHỮ NHỎ GỌN) -->
            <div id="mobileMenuPanel" class="hidden lg:hidden mt-2 pt-2 border-t border-slate-200">
                <div class="grid grid-cols-2 gap-1.5 text-xs font-semibold">
                    <a href="#trang-chu" onclick="toggleMobileMenu()" class="flex items-center gap-1.5 p-2 rounded-lg bg-amber-50 text-brand-red">
                        <i class="fa-solid fa-house text-brand-gold"></i> Trang chủ
                    </a>
                    <a href="#lich-trinh" onclick="toggleMobileMenu()" class="flex items-center gap-1.5 p-2 rounded-lg bg-slate-100 text-slate-700">
                        <i class="fa-solid fa-route text-brand-gold"></i> Lịch trình tuyến xe
                    </a>
                    <a href="#tien-ich-xe" onclick="toggleMobileMenu()" class="flex items-center gap-1.5 p-2 rounded-lg bg-slate-100 text-slate-700">
                        <i class="fa-solid fa-bus text-brand-gold"></i> Tiện ích dòng xe
                    </a>
                    <a href="#dich-vu-gui-hang" onclick="toggleMobileMenu()" class="flex items-center gap-1.5 p-2 rounded-lg bg-slate-100 text-slate-700">
                        <i class="fa-solid fa-box-open text-brand-gold"></i> Gửi hàng &amp; Xe máy
                    </a>
                    <a href="#he-thong-van-phong" onclick="toggleMobileMenu()" class="flex items-center gap-1.5 p-2 rounded-lg bg-slate-100 text-slate-700">
                        <i class="fa-solid fa-building text-brand-gold"></i> Hệ thống văn phòng
                    </a>
                    <a href="#form-bao-gia" onclick="toggleMobileMenu()" class="flex items-center gap-1.5 p-2 rounded-lg bg-slate-100 text-slate-700">
                        <i class="fa-solid fa-file-signature text-brand-gold"></i> Yêu cầu &amp; Báo giá
                    </a>
                    <a href="#tin-tuc" onclick="toggleMobileMenu()" class="flex items-center gap-1.5 p-2 rounded-lg bg-slate-100 text-slate-700">
                        <i class="fa-solid fa-newspaper text-brand-gold"></i> Bài viết trang chủ
                    </a>
                    <a href="#ban-do-lien-he" onclick="toggleMobileMenu()" class="flex items-center gap-1.5 p-2 rounded-lg bg-slate-100 text-slate-700">
                        <i class="fa-solid fa-map-location-dot text-brand-gold"></i> Bản đồ &amp; Facebook
                    </a>
                </div>
            </div>
        </div>
    </header>

    <!-- =====================================================================
         SECTION HERO: 2 ẢNH BANNER TỰ TRƯỢT CHUYÊN NGHIỆP KÍCH THƯỚC BẰNG NHAU
         - Thiết kế riêng ảnh banner trên Máy tính (Desktop) và Điện thoại (Mobile)
         - Chữ bên trong ảnh được chỉnh nhỏ gọn, nằm trọn 100% trong khung banner, không tràn viền
    ====================================================================== -->
    <section id="trang-chu" class="w-full pt-3 pb-2">
        <div class="flatsome-container">
            <div class="relative w-full overflow-hidden rounded-xl shadow-md border border-amber-300 bg-brand-navy">

                <!-- ================== SLIDE 1 ================== -->
                <div class="banner-slide w-full transition-opacity duration-500 block" data-slide="0">
                    
                    <!-- BANNER MÁY TÍNH (DESKTOP) - SLIDE 1 (Cố định chiều cao 360px bằng nhau) -->
                    <div class="hidden md:grid md:grid-cols-12 w-full h-[360px] bg-gradient-to-r from-[#0F2942] via-[#1E3A5F] to-[#7C2D12] relative overflow-hidden">
                        <!-- Cột chữ bên trái: chữ nhỏ gọn, nằm gọn trong khung -->
                        <div class="col-span-7 flex flex-col justify-center px-8 py-5 text-white z-10 overflow-hidden">
                            <div class="inline-flex items-center gap-2 bg-amber-500/20 border border-amber-400/50 text-amber-300 text-xs font-bold px-3 py-1 rounded-full w-fit mb-2">
                                <i class="fa-solid fa-star"></i> NHÀ XE MẠNH LA - NHAXEMANHLA.COM
                            </div>
                            <h1 class="text-xl lg:text-2xl font-extrabold text-white leading-snug mb-2">
                                CHUYÊN TUYẾN ĐÀ NẴNG ⇄ THÁI BÌNH
                                <span class="block text-amber-400 text-base lg:text-lg font-bold mt-0.5">
                                    XE GIƯỜNG NẰM CAO CẤP &amp; LIMOUSINE PHÒNG VIP
                                </span>
                            </h1>
                            <p class="text-xs lg:text-sm text-slate-200 leading-relaxed mb-3 max-w-xl">
                                Khởi hành đều đặn mỗi ngày. Giường nằm bọc da êm ái, Wifi tốc độ cao, nước suối, khăn lạnh miễn phí. Hỗ trợ đón trả khách tận tình tại Hòa Khánh - Đà Nẵng và Bến xe Thái Bình.
                            </p>
                            <div class="grid grid-cols-2 gap-2 text-xs bg-black/30 p-3 rounded-lg border border-white/15 max-w-xl">
                                <div>
                                    <span class="text-amber-300 font-bold block"><i class="fa-solid fa-phone"></i> Tổng đài đặt vé 24/7:</span>
                                    <span class="font-bold text-white">0988.026.577 - 0981.068.333</span>
                                </div>
                                <div>
                                    <span class="text-amber-300 font-bold block"><i class="fa-solid fa-location-dot"></i> Văn phòng Đà Nẵng:</span>
                                    <span class="text-white">117 Lương Trúc Đàm, P. Hòa Khánh</span>
                                </div>
                            </div>
                        </div>
                        <!-- Cột ảnh thực tế bên phải -->
                        <div class="col-span-5 h-[360px] p-4 flex items-center justify-center relative">
                            <div class="w-full h-full rounded-xl overflow-hidden border-2 border-amber-400 shadow-lg bg-slate-900 relative">
                                <img src="https://drive.google.com/thumbnail?id=1-uJDzUOYJMYYpwz1s2cHTXJKkbv92FFw&sz=w1200"
                                     onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1-uJDzUOYJMYYpwz1s2cHTXJKkbv92FFw';"
                                     alt="Xe khách Mạnh La chuyên tuyến Đà Nẵng đi Thái Bình"
                                     class="w-full h-full object-cover">
                                <div class="absolute bottom-2 left-2 right-2 bg-black/70 backdrop-blur-sm text-white text-[11px] px-2.5 py-1 rounded text-center font-medium">
                                    Hình ảnh xe thực tế Nhà xe Mạnh La - Tuyến Đà Nẵng ⇄ Thái Bình
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- BANNER ĐIỆN THOẠI (MOBILE) - SLIDE 1 (Thiết kế riêng cho ĐT, cao 250px bằng nhau, chữ nhỏ gọn không tràn viền) -->
                    <div class="block md:hidden w-full h-[250px] bg-gradient-to-b from-[#0F2942] to-[#7C2D12] relative overflow-hidden p-3 flex flex-col justify-between">
                        <div class="flex items-center gap-2.5 h-[135px]">
                            <div class="w-[58%] pr-1 text-white overflow-hidden">
                                <span class="inline-block bg-amber-500 text-slate-950 text-[10px] font-extrabold px-2 py-0.5 rounded mb-1">
                                    NHAXEMANHLA.COM
                                </span>
                                <h2 class="text-[13px] font-extrabold text-amber-300 leading-tight mb-1">
                                    XE MẠNH LA: ĐÀ NẴNG ⇄ THÁI BÌNH
                                </h2>
                                <p class="text-[11px] text-slate-100 leading-snug">
                                    Xe Giường Nằm &amp; Phòng VIP chạy hàng ngày. Đón trả Hòa Khánh &amp; BX Thái Bình.
                                </p>
                            </div>
                            <div class="w-[42%] h-full rounded-lg overflow-hidden border border-amber-400 shrink-0 bg-slate-800">
                                <img src="https://drive.google.com/thumbnail?id=1-uJDzUOYJMYYpwz1s2cHTXJKkbv92FFw&sz=w800"
                                     onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1-uJDzUOYJMYYpwz1s2cHTXJKkbv92FFw';"
                                     alt="Ảnh thực tế Nhà xe Mạnh La"
                                     class="w-full h-full object-cover">
                            </div>
                        </div>
                        <div class="bg-black/45 border border-amber-400/40 rounded-lg px-2.5 py-1.5 text-white text-[11px] leading-tight">
                            <div class="font-bold text-amber-300 truncate">
                                <i class="fa-solid fa-phone"></i> SĐT: 0988.026.577 - 0981.068.333
                            </div>
                            <div class="text-[10px] text-slate-200 truncate mt-0.5">
                                <i class="fa-solid fa-location-dot text-amber-400"></i> Đ/c: 117 Lương Trúc Đàm, P. Hòa Khánh, TP. Đà Nẵng
                            </div>
                        </div>
                    </div>
                </div>

                <!-- ================== SLIDE 2 ================== -->
                <div class="banner-slide w-full transition-opacity duration-500 hidden" data-slide="1">
                    
                    <!-- BANNER MÁY TÍNH (DESKTOP) - SLIDE 2 (Cố định chiều cao 360px bằng nhau) -->
                    <div class="hidden md:grid md:grid-cols-12 w-full h-[360px] bg-gradient-to-r from-[#7F1D1D] via-[#991B1B] to-[#0F2942] relative overflow-hidden">
                        <div class="col-span-7 flex flex-col justify-center px-8 py-5 text-white z-10 overflow-hidden">
                            <div class="inline-flex items-center gap-2 bg-white/15 border border-amber-300/50 text-amber-300 text-xs font-bold px-3 py-1 rounded-full w-fit mb-2">
                                <i class="fa-solid fa-truck-fast"></i> VẬN CHUYỂN HÀNG HÓA &amp; XE MÁY BẮC - TRUNG
                            </div>
                            <h2 class="text-xl lg:text-2xl font-extrabold text-white leading-snug mb-2">
                                NHẬN KÝ GỬI HÀNG HÓA - BƯU KIỆN - XE MÁY
                                <span class="block text-amber-300 text-base lg:text-lg font-bold mt-0.5">
                                    GIAO NHẬN NHANH ĐÀ NẴNG ⇄ THÁI BÌNH TRONG NGÀY
                                </span>
                            </h2>
                            <p class="text-xs lg:text-sm text-slate-100 leading-relaxed mb-3 max-w-xl">
                                Khoang gầm xe rộng rãi, nhận chở xe máy bọc lót kỹ càng, hàng ghép, bưu kiện hỏa tốc và thu hộ COD. Cam kết an toàn, đúng hẹn, cước phí hợp lý nhất tuyến.
                            </p>
                            <div class="grid grid-cols-2 gap-2 text-xs bg-black/30 p-3 rounded-lg border border-white/15 max-w-xl">
                                <div>
                                    <span class="text-amber-300 font-bold block"><i class="fa-solid fa-headset"></i> Hotline gửi hàng &amp; đặt vé:</span>
                                    <span class="font-bold text-white">0988.026.577 - 0981.068.333</span>
                                </div>
                                <div>
                                    <span class="text-amber-300 font-bold block"><i class="fa-solid fa-clock"></i> Lịch xe xuất bến:</span>
                                    <span class="text-white">Chạy cố định hàng ngày 2 chiều</span>
                                </div>
                            </div>
                        </div>
                        <div class="col-span-5 h-[360px] p-4 flex items-center justify-center relative">
                            <div class="w-full h-full rounded-xl overflow-hidden border-2 border-amber-400 shadow-lg bg-slate-900 relative">
                                <img src="https://drive.google.com/thumbnail?id=1HW9BYDZavyYc6PVfGIf0OiVj9Z6_DFY3&sz=w1200"
                                     onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1HW9BYDZavyYc6PVfGIf0OiVj9Z6_DFY3';"
                                     alt="Dịch vụ gửi hàng và xe giường nằm Mạnh La"
                                     class="w-full h-full object-cover">
                                <div class="absolute bottom-2 left-2 right-2 bg-black/70 backdrop-blur-sm text-white text-[11px] px-2.5 py-1 rounded text-center font-medium">
                                    Tiện nghi hiện đại - Khoang hành lý &amp; gửi hàng an toàn
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- BANNER ĐIỆN THOẠI (MOBILE) - SLIDE 2 (Cao 250px bằng đúng Slide 1, chữ nhỏ gọn không tràn viền) -->
                    <div class="block md:hidden w-full h-[250px] bg-gradient-to-b from-[#7F1D1D] to-[#0F2942] relative overflow-hidden p-3 flex flex-col justify-between">
                        <div class="flex items-center gap-2.5 h-[135px]">
                            <div class="w-[58%] pr-1 text-white overflow-hidden">
                                <span class="inline-block bg-amber-400 text-slate-950 text-[10px] font-extrabold px-2 py-0.5 rounded mb-1">
                                    VẬN TẢI MẠNH LA
                                </span>
                                <h2 class="text-[13px] font-extrabold text-amber-300 leading-tight mb-1">
                                    GỬI HÀNG HÓA &amp; XE MÁY SIÊU TỐC
                                </h2>
                                <p class="text-[11px] text-slate-100 leading-snug">
                                    Nhận bưu kiện, xe máy, hàng cồng kềnh tuyến Đà Nẵng ⇄ Thái Bình an toàn 100%.
                                </p>
                            </div>
                            <div class="w-[42%] h-full rounded-lg overflow-hidden border border-amber-400 shrink-0 bg-slate-800">
                                <img src="https://drive.google.com/thumbnail?id=1HW9BYDZavyYc6PVfGIf0OiVj9Z6_DFY3&sz=w800"
                                     onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1HW9BYDZavyYc6PVfGIf0OiVj9Z6_DFY3';"
                                     alt="Vận chuyển hàng hóa Nhà xe Mạnh La"
                                     class="w-full h-full object-cover">
                            </div>
                        </div>
                        <div class="bg-black/45 border border-amber-400/40 rounded-lg px-2.5 py-1.5 text-white text-[11px] leading-tight">
                            <div class="font-bold text-amber-300 truncate">
                                <i class="fa-solid fa-phone"></i> Gọi báo giá: 0988.026.577 - 0981.068.333
                            </div>
                            <div class="text-[10px] text-slate-200 truncate mt-0.5">
                                <i class="fa-solid fa-location-dot text-amber-400"></i> Nhận hàng: 117 Lương Trúc Đàm, Hòa Khánh, Đà Nẵng
                            </div>
                        </div>
                    </div>
                </div>

                <!-- NÚT ĐIỀU HƯỚNG SLIDER BANNER -->
                <button type="button" onclick="changeSlide(-1)" aria-label="Banner trước" class="absolute left-2 top-1/2 -translate-y-1/2 w-7 h-7 sm:w-8 sm:h-8 rounded-full bg-black/40 hover:bg-black/70 text-white flex items-center justify-center text-xs z-20 transition">
                    <i class="fa-solid fa-chevron-left"></i>
                </button>
                <button type="button" onclick="changeSlide(1)" aria-label="Banner tiếp" class="absolute right-2 top-1/2 -translate-y-1/2 w-7 h-7 sm:w-8 sm:h-8 rounded-full bg-black/40 hover:bg-black/70 text-white flex items-center justify-center text-xs z-20 transition">
                    <i class="fa-solid fa-chevron-right"></i>
                </button>

                <!-- CHẤM CHỈ BÁO SLIDE -->
                <div class="absolute bottom-2 left-1/2 -translate-x-1/2 flex items-center gap-2 z-20">
                    <button type="button" onclick="goToSlide(0)" class="banner-dot w-2.5 h-2.5 rounded-full bg-amber-400 transition" aria-label="Slide 1"></button>
                    <button type="button" onclick="goToSlide(1)" class="banner-dot w-2.5 h-2.5 rounded-full bg-white/50 transition" aria-label="Slide 2"></button>
                </div>
            </div>
        </div>
    </section>

    <!-- =====================================================================
         THANH TÌM VÉ XE & TRA CỨU LỊCH TRÌNH (THEO MẪU WEB VANMINH76.VN)
    ====================================================================== -->
    <section class="w-full py-2">
        <div class="flatsome-container">
            <div class="bg-white rounded-xl shadow-sm border border-amber-300 p-3 sm:p-4">
                <div class="flex items-center justify-between flex-wrap gap-2 mb-2.5 pb-2 border-b border-slate-100">
                    <div class="flex items-center gap-2 text-xs sm:text-sm font-extrabold text-brand-navy">
                        <i class="fa-solid fa-ticket text-brand-gold"></i>
                        <span>ĐẶT VÉ XE &amp; TRA CỨU TUYẾN ĐÀ NẴNG ⇄ THÁI BÌNH</span>
                    </div>
                    <span class="text-[11px] font-semibold text-brand-red">
                        <i class="fa-solid fa-headset"></i> Hỗ trợ giữ chỗ: 0988.026.577 - 0981.068.333
                    </span>
                </div>
                <form onsubmit="handleQuickSearch(event)" class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-5 gap-2.5">
                    <div>
                        <label class="block text-[11px] font-semibold text-slate-600 mb-1">Điểm khởi hành *</label>
                        <select id="searchFrom" class="w-full rounded-lg border border-slate-300 px-2.5 py-2 text-xs font-medium text-slate-800 focus:outline-none focus:border-brand-gold">
                            <option value="Đà Nẵng (117 Lương Trúc Đàm - Hòa Khánh)">Đà Nẵng (117 Lương Trúc Đàm - Hòa Khánh)</option>
                            <option value="Bến xe Trung tâm TP. Đà Nẵng">Bến xe Trung tâm TP. Đà Nẵng</option>
                            <option value="Thái Bình (Bến xe Thái Bình)">Thái Bình (Bến xe Thái Bình)</option>
                            <option value="Ninh Bình / Nam Định (Dọc QL1A)">Ninh Bình / Nam Định (Dọc QL1A)</option>
                            <option value="Thanh Hóa / Nghệ An / Hà Tĩnh">Thanh Hóa / Nghệ An / Hà Tĩnh</option>
                        </select>
                    </div>
                    <div>
                        <label class="block text-[11px] font-semibold text-slate-600 mb-1">Điểm đến *</label>
                        <select id="searchTo" class="w-full rounded-lg border border-slate-300 px-2.5 py-2 text-xs font-medium text-slate-800 focus:outline-none focus:border-brand-gold">
                            <option value="Thái Bình (Bến xe Thái Bình)">Thái Bình (Bến xe Thái Bình)</option>
                            <option value="Đà Nẵng (117 Lương Trúc Đàm - Hòa Khánh)">Đà Nẵng (117 Lương Trúc Đàm - Hòa Khánh)</option>
                            <option value="Bến xe Trung tâm TP. Đà Nẵng">Bến xe Trung tâm TP. Đà Nẵng</option>
                            <option value="Thanh Hóa / Nghệ An / Hà Tĩnh">Thanh Hóa / Nghệ An / Hà Tĩnh</option>
                            <option value="Ninh Bình / Nam Định">Ninh Bình / Nam Định</option>
                        </select>
                    </div>
                    <div>
                        <label class="block text-[11px] font-semibold text-slate-600 mb-1">Loại dịch vụ *</label>
                        <select id="searchService" class="w-full rounded-lg border border-slate-300 px-2.5 py-2 text-xs font-medium text-slate-800 focus:outline-none focus:border-brand-gold">
                            <option value="Xe Giường Nằm Cao Cấp (550.000đ)">Xe Giường Nằm Cao Cấp (550.000đ)</option>
                            <option value="Xe Limousine Phòng VIP (700.000đ)">Xe Limousine Phòng VIP (700.000đ)</option>
                            <option value="Ký Gửi Hàng Hóa / Bưu Kiện">Ký Gửi Hàng Hóa / Bưu Kiện</option>
                            <option value="Vận Chuyển Xe Máy Bắc - Nam">Vận Chuyển Xe Máy Bắc - Nam</option>
                        </select>
                    </div>
                    <div>
                        <label class="block text-[11px] font-semibold text-slate-600 mb-1">Số điện thoại khách hàng *</label>
                        <input id="searchPhone" type="tel" required placeholder="Nhập SĐT để nhà xe gọi lại..." class="w-full rounded-lg border border-slate-300 px-2.5 py-2 text-xs text-slate-800 focus:outline-none focus:border-brand-gold">
                    </div>
                    <div class="flex items-end">
                        <button type="submit" class="w-full rounded-lg bg-brand-red hover:bg-brand-redDark text-white font-bold text-xs py-2.5 px-3 transition shadow-sm flex items-center justify-center gap-1.5">
                            <i class="fa-solid fa-magnifying-glass"></i> ĐẶT VÉ / BÁO GIÁ NGAY
                        </button>
                    </div>
                </form>
            </div>
        </div>
    </section>

    <!-- =====================================================================
         DANH MỤC SẢN PHẨM & DỊCH VỤ Ở TRANG CHỦ (CHỮ NHỎ GỌN, ĐẸP TRÊN PC & ĐT)
         Lấy theo cấu trúc danh mục của web mẫu vanminh76.vn
    ====================================================================== -->
    <section class="w-full py-2">
        <div class="flatsome-container">
            <div class="bg-white rounded-xl border border-slate-200 p-3 shadow-sm">
                <div class="flex items-center justify-between mb-2">
                    <h2 class="text-xs sm:text-sm font-extrabold text-brand-navy uppercase tracking-tight">
                        <i class="fa-solid fa-layer-group text-brand-gold mr-1"></i> Danh Mục Dịch Vụ Nhà Xe Mạnh La
                    </h2>
                    <span class="text-[11px] text-slate-500">Chọn nhanh danh mục</span>
                </div>
                <div class="grid grid-cols-2 sm:grid-cols-4 lg:grid-cols-8 gap-2">
                    <a href="#lich-trinh" class="flex flex-col items-center justify-center p-2 rounded-lg bg-amber-50/70 hover:bg-amber-100 border border-amber-200 text-center transition">
                        <i class="fa-solid fa-bus-simple text-brand-red text-sm mb-1"></i>
                        <span class="text-[11px] font-bold text-slate-800 leading-tight">Xe Đà Nẵng - Thái Bình</span>
                    </a>
                    <a href="#lich-trinh" class="flex flex-col items-center justify-center p-2 rounded-lg bg-amber-50/70 hover:bg-amber-100 border border-amber-200 text-center transition">
                        <i class="fa-solid fa-arrow-right-arrow-left text-brand-gold text-sm mb-1"></i>
                        <span class="text-[11px] font-bold text-slate-800 leading-tight">Xe Thái Bình - Đà Nẵng</span>
                    </a>
                    <a href="#tien-ich-xe" class="flex flex-col items-center justify-center p-2 rounded-lg bg-amber-50/70 hover:bg-amber-100 border border-amber-200 text-center transition">
                        <i class="fa-solid fa-bed text-brand-red text-sm mb-1"></i>
                        <span class="text-[11px] font-bold text-slate-800 leading-tight">Dòng Xe VIP Cabin</span>
                    </a>
                    <a href="#tien-ich-xe" class="flex flex-col items-center justify-center p-2 rounded-lg bg-amber-50/70 hover:bg-amber-100 border border-amber-200 text-center transition">
                        <i class="fa-solid fa-couch text-brand-gold text-sm mb-1"></i>
                        <span class="text-[11px] font-bold text-slate-800 leading-tight">Xe 34 &amp; 38 Giường</span>
                    </a>
                    <a href="#dich-vu-gui-hang" class="flex flex-col items-center justify-center p-2 rounded-lg bg-amber-50/70 hover:bg-amber-100 border border-amber-200 text-center transition">
                        <i class="fa-solid fa-boxes-packing text-brand-red text-sm mb-1"></i>
                        <span class="text-[11px] font-bold text-slate-800 leading-tight">Chuyển Phát Hàng Hóa</span>
                    </a>
                    <a href="#dich-vu-gui-hang" class="flex flex-col items-center justify-center p-2 rounded-lg bg-amber-50/70 hover:bg-amber-100 border border-amber-200 text-center transition">
                        <i class="fa-solid fa-motorcycle text-brand-gold text-sm mb-1"></i>
                        <span class="text-[11px] font-bold text-slate-800 leading-tight">Gửi Xe Máy Bắc Nam</span>
                    </a>
                    <a href="#he-thong-van-phong" class="flex flex-col items-center justify-center p-2 rounded-lg bg-amber-50/70 hover:bg-amber-100 border border-amber-200 text-center transition">
                        <i class="fa-solid fa-van-shuttle text-brand-red text-sm mb-1"></i>
                        <span class="text-[11px] font-bold text-slate-800 leading-tight">Trung Chuyển Tận Nơi</span>
                    </a>
                    <a href="#form-bao-gia" class="flex flex-col items-center justify-center p-2 rounded-lg bg-amber-50/70 hover:bg-amber-100 border border-amber-200 text-center transition">
                        <i class="fa-solid fa-file-invoice-dollar text-brand-gold text-sm mb-1"></i>
                        <span class="text-[11px] font-bold text-slate-800 leading-tight">Báo Giá Hợp Đồng</span>
                    </a>
                </div>
            </div>
        </div>
    </section>

    <!-- =====================================================================
         SECTION 1: TUYẾN XE PHỔ BIẾN & GIÁ VÉ NIÊM YẾT (GIỐNG WEB MẪU VANMINH76.VN)
         - Sản phẩm chia thành 2 cột trên điện thoại (grid-cols-2), 4 cột trên máy tính (lg:grid-cols-4)
         - Không để các nhãn dán ở trang chủ
         - Tên sản phẩm hiển thị đầy đủ, không bị tràn hoặc thiếu chữ
         - Sử dụng toàn bộ ảnh thực tế trong 5 link Google Drive của khách hàng
    ====================================================================== -->
    <section id="lich-trinh" class="w-full py-4">
        <div class="flatsome-container">
            <!-- Tiêu đề Section chuẩn Flatsome -->
            <div class="flex flex-col sm:flex-row sm:items-center justify-between gap-2 mb-3 pb-2 border-b-2 border-brand-gold">
                <div>
                    <h2 class="text-sm sm:text-base lg:text-lg font-extrabold text-brand-navy uppercase">
                        <i class="fa-solid fa-route text-brand-red mr-1.5"></i> Tuyến Phổ Biến &amp; Lịch Trình Xe Mạnh La
                    </h2>
                    <p class="text-[11px] sm:text-xs text-slate-600">
                        Chuyên tuyến cố định Đà Nẵng ⇄ Thái Bình - Khởi hành hàng ngày, đón trả khách tại 117 Lương Trúc Đàm, Hòa Khánh
                    </p>
                </div>
                <a href="tel:0988026577" class="text-xs font-bold text-brand-red hover:underline shrink-0">
                    Tổng đài: 0988.026.577 - 0981.068.333 <i class="fa-solid fa-arrow-right ml-1"></i>
                </a>
            </div>

            <!-- GRID SẢN PHẨM: 2 CỘT TRÊN ĐIỆN THOẠI (grid-cols-2), 4 CỘT TRÊN MÁY TÍNH (lg:grid-cols-4) -->
            <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-2.5 sm:gap-4">

                <!-- Sản phẩm 1 (Ảnh Drive 1: 1-uJDzUOYJMYYpwz1s2cHTXJKkbv92FFw) -->
                <div class="bg-white rounded-xl border border-slate-200 shadow-sm overflow-hidden flex flex-col justify-between p-2 sm:p-3 hover:border-brand-gold transition">
                    <div>
                        <div class="w-full h-28 sm:h-40 rounded-lg overflow-hidden bg-slate-100 mb-2">
                            <img src="https://drive.google.com/thumbnail?id=1-uJDzUOYJMYYpwz1s2cHTXJKkbv92FFw&sz=w800"
                                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1-uJDzUOYJMYYpwz1s2cHTXJKkbv92FFw';"
                                 alt="Tuyến Đà Nẵng đi Thái Bình Xe Giường Nằm 38 Chỗ"
                                 class="w-full h-full object-cover">
                        </div>
                        <h3 class="product-title-full text-xs sm:text-sm font-bold text-brand-navy mb-1">
                            Tuyến Đà Nẵng Đi Thái Bình - Xe Giường Nằm Cao Cấp 38 Chỗ
                        </h3>
                        <div class="text-[11px] text-slate-600 space-y-0.5 mb-2">
                            <p><i class="fa-solid fa-clock text-brand-gold w-3.5"></i> Xuất bến Đà Nẵng: 17h00 - 17h15</p>
                            <p><i class="fa-solid fa-location-dot text-brand-red w-3.5"></i> Đón: 117 Lương Trúc Đàm &amp; BX Đà Nẵng</p>
                            <p><i class="fa-solid fa-road text-slate-500 w-3.5"></i> Cự ly: ~650km (Cao tốc &amp; QL1A)</p>
                        </div>
                    </div>
                    <div class="pt-2 border-t border-slate-100">
                        <div class="text-xs sm:text-sm font-extrabold text-brand-red mb-1.5">
                            550.000đ / Lượt
                        </div>
                        <button type="button" onclick="selectServiceToForm('Tuyến Đà Nẵng Đi Thái Bình - Xe Giường Nằm 38 Chỗ (550.000đ)')" class="w-full py-1.5 px-2 rounded-lg bg-brand-gold hover:bg-amber-600 text-white font-bold text-[11px] sm:text-xs transition">
                            Đặt vé ngay
                        </button>
                    </div>
                </div>

                <!-- Sản phẩm 2 (Ảnh Drive 2: 1HW9BYDZavyYc6PVfGIf0OiVj9Z6_DFY3) -->
                <div class="bg-white rounded-xl border border-slate-200 shadow-sm overflow-hidden flex flex-col justify-between p-2 sm:p-3 hover:border-brand-gold transition">
                    <div>
                        <div class="w-full h-28 sm:h-40 rounded-lg overflow-hidden bg-slate-100 mb-2">
                            <img src="https://drive.google.com/thumbnail?id=1HW9BYDZavyYc6PVfGIf0OiVj9Z6_DFY3&sz=w800"
                                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1HW9BYDZavyYc6PVfGIf0OiVj9Z6_DFY3';"
                                 alt="Tuyến Thái Bình đi Đà Nẵng Xe Giường Nằm 38 Chỗ"
                                 class="w-full h-full object-cover">
                        </div>
                        <h3 class="product-title-full text-xs sm:text-sm font-bold text-brand-navy mb-1">
                            Tuyến Thái Bình Đi Đà Nẵng - Xe Giường Nằm Cao Cấp 38 Chỗ
                        </h3>
                        <div class="text-[11px] text-slate-600 space-y-0.5 mb-2">
                            <p><i class="fa-solid fa-clock text-brand-gold w-3.5"></i> Xuất bến Thái Bình: 15h00 - 17h15</p>
                            <p><i class="fa-solid fa-location-dot text-brand-red w-3.5"></i> Đón: Bến xe Thái Bình (Lý Thường Kiệt)</p>
                            <p><i class="fa-solid fa-road text-slate-500 w-3.5"></i> Trả: Hòa Khánh &amp; BX Trung tâm Đà Nẵng</p>
                        </div>
                    </div>
                    <div class="pt-2 border-t border-slate-100">
                        <div class="text-xs sm:text-sm font-extrabold text-brand-red mb-1.5">
                            550.000đ / Lượt
                        </div>
                        <button type="button" onclick="selectServiceToForm('Tuyến Thái Bình Đi Đà Nẵng - Xe Giường Nằm 38 Chỗ (550.000đ)')" class="w-full py-1.5 px-2 rounded-lg bg-brand-gold hover:bg-amber-600 text-white font-bold text-[11px] sm:text-xs transition">
                            Đặt vé ngay
                        </button>
                    </div>
                </div>

                <!-- Sản phẩm 3 (Ảnh Drive 3: 1M9DjgIH268z_04t8GobbfHRB4pgTSkcN) -->
                <div class="bg-white rounded-xl border border-slate-200 shadow-sm overflow-hidden flex flex-col justify-between p-2 sm:p-3 hover:border-brand-gold transition">
                    <div>
                        <div class="w-full h-28 sm:h-40 rounded-lg overflow-hidden bg-slate-100 mb-2">
                            <img src="https://drive.google.com/thumbnail?id=1M9DjgIH268z_04t8GobbfHRB4pgTSkcN&sz=w800"
                                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1M9DjgIH268z_04t8GobbfHRB4pgTSkcN';"
                                 alt="Xe Limousine VIP 22 Cabin Phòng Đôi Đà Nẵng Thái Bình"
                                 class="w-full h-full object-cover">
                        </div>
                        <h3 class="product-title-full text-xs sm:text-sm font-bold text-brand-navy mb-1">
                            Tuyến Đà Nẵng ⇄ Thái Bình - Xe Limousine VIP 22 Cabin Phòng
                        </h3>
                        <div class="text-[11px] text-slate-600 space-y-0.5 mb-2">
                            <p><i class="fa-solid fa-tv text-brand-gold w-3.5"></i> Cabin riêng tư, rèm che, sạc USB, Wifi</p>
                            <p><i class="fa-solid fa-location-dot text-brand-red w-3.5"></i> Đón trả tận nơi nội thành Hòa Khánh</p>
                            <p><i class="fa-solid fa-utensils text-slate-500 w-3.5"></i> Gồm khăn lạnh, nước suối, bảo hiểm</p>
                        </div>
                    </div>
                    <div class="pt-2 border-t border-slate-100">
                        <div class="text-xs sm:text-sm font-extrabold text-brand-red mb-1.5">
                            700.000đ / Lượt
                        </div>
                        <button type="button" onclick="selectServiceToForm('Tuyến Đà Nẵng ⇄ Thái Bình - Xe Limousine VIP 22 Phòng (700.000đ)')" class="w-full py-1.5 px-2 rounded-lg bg-brand-gold hover:bg-amber-600 text-white font-bold text-[11px] sm:text-xs transition">
                            Đặt vé ngay
                        </button>
                    </div>
                </div>

                <!-- Sản phẩm 4 (Ảnh Drive 4: 1yfVWo_SvJJSMXONltqQOJh98eTW5zlb4) -->
                <div class="bg-white rounded-xl border border-slate-200 shadow-sm overflow-hidden flex flex-col justify-between p-2 sm:p-3 hover:border-brand-gold transition">
                    <div>
                        <div class="w-full h-28 sm:h-40 rounded-lg overflow-hidden bg-slate-100 mb-2">
                            <img src="https://drive.google.com/thumbnail?id=1yfVWo_SvJJSMXONltqQOJh98eTW5zlb4&sz=w800"
                                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1yfVWo_SvJJSMXONltqQOJh98eTW5zlb4';"
                                 alt="Xe Giường Nằm 34 Phòng Cao Cấp Đà Nẵng Thái Bình"
                                 class="w-full h-full object-cover">
                        </div>
                        <h3 class="product-title-full text-xs sm:text-sm font-bold text-brand-navy mb-1">
                            Tuyến Đà Nẵng ⇄ Thái Bình - Xe Giường Nằm 34 Chỗ Đời Mới
                        </h3>
                        <div class="text-[11px] text-slate-600 space-y-0.5 mb-2">
                            <p><i class="fa-solid fa-bed text-brand-gold w-3.5"></i> Giường nằm bọc da rộng rãi, êm ái</p>
                            <p><i class="fa-solid fa-clock text-brand-red w-3.5"></i> Thời gian di chuyển: 12 - 14 tiếng</p>
                            <p><i class="fa-solid fa-shield-halved text-slate-500 w-3.5"></i> Camera giám sát &amp; GPS hành trình</p>
                        </div>
                    </div>
                    <div class="pt-2 border-t border-slate-100">
                        <div class="text-xs sm:text-sm font-extrabold text-brand-red mb-1.5">
                            600.000đ / Lượt
                        </div>
                        <button type="button" onclick="selectServiceToForm('Tuyến Đà Nẵng ⇄ Thái Bình - Xe Giường Nằm 34 Chỗ (600.000đ)')" class="w-full py-1.5 px-2 rounded-lg bg-brand-gold hover:bg-amber-600 text-white font-bold text-[11px] sm:text-xs transition">
                            Đặt vé ngay
                        </button>
                    </div>
                </div>

                <!-- Sản phẩm 5 (Ảnh Drive 5: 19ag9REQSxaHgHkcwwKMMbl-_fKHa94NG) -->
                <div class="bg-white rounded-xl border border-slate-200 shadow-sm overflow-hidden flex flex-col justify-between p-2 sm:p-3 hover:border-brand-gold transition">
                    <div>
                        <div class="w-full h-28 sm:h-40 rounded-lg overflow-hidden bg-slate-100 mb-2">
                            <img src="https://drive.google.com/thumbnail?id=19ag9REQSxaHgHkcwwKMMbl-_fKHa94NG&sz=w800"
                                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/19ag9REQSxaHgHkcwwKMMbl-_fKHa94NG';"
                                 alt="Tuyến Đà Nẵng đi Nam Định Ninh Bình Thái Bình"
                                 class="w-full h-full object-cover">
                        </div>
                        <h3 class="product-title-full text-xs sm:text-sm font-bold text-brand-navy mb-1">
                            Tuyến Đà Nẵng ⇄ Ninh Bình - Nam Định - Thái Bình
                        </h3>
                        <div class="text-[11px] text-slate-600 space-y-0.5 mb-2">
                            <p><i class="fa-solid fa-route text-brand-gold w-3.5"></i> Lộ trình: Hầm Hải Vân - QL1A - Cao tốc</p>
                            <p><i class="fa-solid fa-location-dot text-brand-red w-3.5"></i> Hỗ trợ đón khách dọc tuyến Quốc lộ</p>
                            <p><i class="fa-solid fa-suitcase text-slate-500 w-3.5"></i> Miễn phí 15-17kg hành lý xách tay</p>
                        </div>
                    </div>
                    <div class="pt-2 border-t border-slate-100">
                        <div class="text-xs sm:text-sm font-extrabold text-brand-red mb-1.5">
                            500.000đ - 550.000đ
                        </div>
                        <button type="button" onclick="selectServiceToForm('Tuyến Đà Nẵng ⇄ Ninh Bình - Nam Định - Thái Bình')" class="w-full py-1.5 px-2 rounded-lg bg-brand-gold hover:bg-amber-600 text-white font-bold text-[11px] sm:text-xs transition">
                            Đặt vé ngay
                        </button>
                    </div>
                </div>

                <!-- Sản phẩm 6 (Ảnh Drive 1: 1-uJDzUOYJMYYpwz1s2cHTXJKkbv92FFw) -->
                <div class="bg-white rounded-xl border border-slate-200 shadow-sm overflow-hidden flex flex-col justify-between p-2 sm:p-3 hover:border-brand-gold transition">
                    <div>
                        <div class="w-full h-28 sm:h-40 rounded-lg overflow-hidden bg-slate-100 mb-2">
                            <img src="https://drive.google.com/thumbnail?id=1-uJDzUOYJMYYpwz1s2cHTXJKkbv92FFw&sz=w800"
                                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1-uJDzUOYJMYYpwz1s2cHTXJKkbv92FFw';"
                                 alt="Tuyến Đà Nẵng đi Thanh Hóa Nghệ An Hà Tĩnh"
                                 class="w-full h-full object-cover">
                        </div>
                        <h3 class="product-title-full text-xs sm:text-sm font-bold text-brand-navy mb-1">
                            Tuyến Đà Nẵng ⇄ Hà Tĩnh - Nghệ An - Thanh Hóa
                        </h3>
                        <div class="text-[11px] text-slate-600 space-y-0.5 mb-2">
                            <p><i class="fa-solid fa-clock text-brand-gold w-3.5"></i> Khởi hành hàng ngày từ Hòa Khánh</p>
                            <p><i class="fa-solid fa-location-dot text-brand-red w-3.5"></i> Trả khách dọc QL1A &amp; điểm dừng nghỉ</p>
                            <p><i class="fa-solid fa-wifi text-slate-500 w-3.5"></i> Tiện ích: Wifi, cổng sạc, chăn đắp sạch</p>
                        </div>
                    </div>
                    <div class="pt-2 border-t border-slate-100">
                        <div class="text-xs sm:text-sm font-extrabold text-brand-red mb-1.5">
                            400.000đ - 450.000đ
                        </div>
                        <button type="button" onclick="selectServiceToForm('Tuyến Đà Nẵng ⇄ Hà Tĩnh - Nghệ An - Thanh Hóa')" class="w-full py-1.5 px-2 rounded-lg bg-brand-gold hover:bg-amber-600 text-white font-bold text-[11px] sm:text-xs transition">
                            Đặt vé ngay
                        </button>
                    </div>
                </div>

                <!-- Sản phẩm 7 (Ảnh Drive 2: 1HW9BYDZavyYc6PVfGIf0OiVj9Z6_DFY3) -->
                <div class="bg-white rounded-xl border border-slate-200 shadow-sm overflow-hidden flex flex-col justify-between p-2 sm:p-3 hover:border-brand-gold transition">
                    <div>
                        <div class="w-full h-28 sm:h-40 rounded-lg overflow-hidden bg-slate-100 mb-2">
                            <img src="https://drive.google.com/thumbnail?id=1HW9BYDZavyYc6PVfGIf0OiVj9Z6_DFY3&sz=w800"
                                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1HW9BYDZavyYc6PVfGIf0OiVj9Z6_DFY3';"
                                 alt="Vé Khứ Hồi Tuyến Đà Nẵng Thái Bình"
                                 class="w-full h-full object-cover">
                        </div>
                        <h3 class="product-title-full text-xs sm:text-sm font-bold text-brand-navy mb-1">
                            Combo Vé Khứ Hồi Tuyến Đà Nẵng ⇄ Thái Bình (Ưu Đãi 10%)
                        </h3>
                        <div class="text-[11px] text-slate-600 space-y-0.5 mb-2">
                            <p><i class="fa-solid fa-percent text-brand-gold w-3.5"></i> Giảm 10% khi đặt vé khứ hồi 2 chiều</p>
                            <p><i class="fa-solid fa-check text-brand-red w-3.5"></i> Ưu tiên chọn giường tầng 1 phía trước</p>
                            <p><i class="fa-solid fa-rotate text-slate-500 w-3.5"></i> Hỗ trợ đổi ngày đi linh hoạt miễn phí</p>
                        </div>
                    </div>
                    <div class="pt-2 border-t border-slate-100">
                        <div class="text-xs sm:text-sm font-extrabold text-brand-red mb-1.5">
                            990.000đ / Khứ hồi
                        </div>
                        <button type="button" onclick="selectServiceToForm('Combo Vé Khứ Hồi Tuyến Đà Nẵng ⇄ Thái Bình')" class="w-full py-1.5 px-2 rounded-lg bg-brand-gold hover:bg-amber-600 text-white font-bold text-[11px] sm:text-xs transition">
                            Đặt vé ngay
                        </button>
                    </div>
                </div>

                <!-- Sản phẩm 8 (Ảnh Drive 3: 1M9DjgIH268z_04t8GobbfHRB4pgTSkcN) -->
                <div class="bg-white rounded-xl border border-slate-200 shadow-sm overflow-hidden flex flex-col justify-between p-2 sm:p-3 hover:border-brand-gold transition">
                    <div>
                        <div class="w-full h-28 sm:h-40 rounded-lg overflow-hidden bg-slate-100 mb-2">
                            <img src="https://drive.google.com/thumbnail?id=1M9DjgIH268z_04t8GobbfHRB4pgTSkcN&sz=w800"
                                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1M9DjgIH268z_04t8GobbfHRB4pgTSkcN';"
                                 alt="Đặt Vé Gia Đình Sinh Viên Khu Công Nghiệp Hòa Khánh"
                                 class="w-full h-full object-cover">
                        </div>
                        <h3 class="product-title-full text-xs sm:text-sm font-bold text-brand-navy mb-1">
                            Vé Đoàn Gia Đình &amp; Công Nhân KCN Hòa Khánh Về Thái Bình
                        </h3>
                        <div class="text-[11px] text-slate-600 space-y-0.5 mb-2">
                            <p><i class="fa-solid fa-users text-brand-gold w-3.5"></i> Ưu đãi nhóm từ 3 khách trở lên</p>
                            <p><i class="fa-solid fa-location-dot text-brand-red w-3.5"></i> Đón tận nơi 117 Lương Trúc Đàm, Hòa Khánh</p>
                            <p><i class="fa-solid fa-paw text-slate-500 w-3.5"></i> Hỗ trợ mang nhiều hành lý về quê</p>
                        </div>
                    </div>
                    <div class="pt-2 border-t border-slate-100">
                        <div class="text-xs sm:text-sm font-extrabold text-brand-red mb-1.5">
                            Liên hệ giá ưu đãi
                        </div>
                        <button type="button" onclick="selectServiceToForm('Vé Đoàn Gia Đình & Công Nhân KCN Hòa Khánh Về Thái Bình')" class="w-full py-1.5 px-2 rounded-lg bg-brand-gold hover:bg-amber-600 text-white font-bold text-[11px] sm:text-xs transition">
                            Nhận báo giá
                        </button>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- =====================================================================
         SECTION 2: TIỆN ÍCH XE & HÌNH ẢNH THỰC TẾ NHÀ XE MẠNH LA (LẤY TỪ 5 FILE GOOGLE DRIVE)
         Tương ứng danh mục "Tiện ích xe" trên vanminh76.vn (Chia 2 cột trên điện thoại)
    ====================================================================== -->
    <section id="tien-ich-xe" class="w-full py-4 bg-amber-50/50 border-y border-amber-200/70">
        <div class="flatsome-container">
            <div class="flex flex-col sm:flex-row sm:items-center justify-between gap-2 mb-3 pb-2 border-b-2 border-brand-gold">
                <div>
                    <h2 class="text-sm sm:text-base lg:text-lg font-extrabold text-brand-navy uppercase">
                        <i class="fa-solid fa-bus text-brand-red mr-1.5"></i> Tiện Ích Xe &amp; Hình Ảnh Thực Tế Nhà Xe Mạnh La
                    </h2>
                    <p class="text-[11px] sm:text-xs text-slate-600">
                        Hình ảnh thực tế đội xe giường nằm, nội thất khoang xe và khoang hành lý chuyên tuyến Đà Nẵng ⇄ Thái Bình
                    </p>
                </div>
            </div>

            <!-- Chia 2 cột trên điện thoại (grid-cols-2), 5 ảnh thực tế hiển thị rõ ràng -->
            <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-5 gap-2.5 sm:gap-3.5">
                
                <!-- Ảnh thực tế 1 -->
                <div class="bg-white rounded-xl border border-slate-200 p-2 sm:p-2.5 shadow-sm flex flex-col justify-between">
                    <div>
                        <div class="w-full h-28 sm:h-36 rounded-lg overflow-hidden bg-slate-100 mb-2">
                            <img src="https://drive.google.com/thumbnail?id=1-uJDzUOYJMYYpwz1s2cHTXJKkbv92FFw&sz=w800"
                                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1-uJDzUOYJMYYpwz1s2cHTXJKkbv92FFw';"
                                 alt="Ngoại thất xe giường nằm Mạnh La Đà Nẵng Thái Bình"
                                 class="w-full h-full object-cover">
                        </div>
                        <h3 class="product-title-full text-xs sm:text-[13px] font-bold text-brand-navy mb-1">
                            Dòng Xe Giường Nằm Chuyên Tuyến Đà Nẵng - Thái Bình
                        </h3>
                        <p class="text-[11px] text-slate-600 leading-snug">
                            Xe đời mới vận hành êm ái, bảo dưỡng định kỳ nghiêm ngặt trước mỗi chuyến đi dài.
                        </p>
                    </div>
                </div>

                <!-- Ảnh thực tế 2 -->
                <div class="bg-white rounded-xl border border-slate-200 p-2 sm:p-2.5 shadow-sm flex flex-col justify-between">
                    <div>
                        <div class="w-full h-28 sm:h-36 rounded-lg overflow-hidden bg-slate-100 mb-2">
                            <img src="https://drive.google.com/thumbnail?id=1HW9BYDZavyYc6PVfGIf0OiVj9Z6_DFY3&sz=w800"
                                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1HW9BYDZavyYc6PVfGIf0OiVj9Z6_DFY3';"
                                 alt="Hệ thống giường nằm bọc da cao cấp Nhà xe Mạnh La"
                                 class="w-full h-full object-cover">
                        </div>
                        <h3 class="product-title-full text-xs sm:text-[13px] font-bold text-brand-navy mb-1">
                            Khoang Giường Nằm Bọc Da Êm Ái &amp; Rộng Rãi
                        </h3>
                        <p class="text-[11px] text-slate-600 leading-snug">
                            Giường ngả sâu thoải mái, chăn gối giặt sạch thơm tho sau từng lượt hành trình.
                        </p>
                    </div>
                </div>

                <!-- Ảnh thực tế 3 -->
                <div class="bg-white rounded-xl border border-slate-200 p-2 sm:p-2.5 shadow-sm flex flex-col justify-between">
                    <div>
                        <div class="w-full h-28 sm:h-36 rounded-lg overflow-hidden bg-slate-100 mb-2">
                            <img src="https://drive.google.com/thumbnail?id=1M9DjgIH268z_04t8GobbfHRB4pgTSkcN&sz=w800"
                                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1M9DjgIH268z_04t8GobbfHRB4pgTSkcN';"
                                 alt="Dòng xe Cabin VIP Limousine Mạnh La"
                                 class="w-full h-full object-cover">
                        </div>
                        <h3 class="product-title-full text-xs sm:text-[13px] font-bold text-brand-navy mb-1">
                            Tiện Nghi Phòng Cabin VIP &amp; Điều Hòa Đa Vùng
                        </h3>
                        <p class="text-[11px] text-slate-600 leading-snug">
                            Trang bị cổng sạc điện thoại, đèn đọc sách, rèm che riêng tư và Wifi miễn phí suốt tuyến.
                        </p>
                    </div>
                </div>

                <!-- Ảnh thực tế 4 -->
                <div class="bg-white rounded-xl border border-slate-200 p-2 sm:p-2.5 shadow-sm flex flex-col justify-between">
                    <div>
                        <div class="w-full h-28 sm:h-36 rounded-lg overflow-hidden bg-slate-100 mb-2">
                            <img src="https://drive.google.com/thumbnail?id=1yfVWo_SvJJSMXONltqQOJh98eTW5zlb4&sz=w800"
                                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1yfVWo_SvJJSMXONltqQOJh98eTW5zlb4';"
                                 alt="Điểm đón trả khách và bốc xếp hành lý Mạnh La"
                                 class="w-full h-full object-cover">
                        </div>
                        <h3 class="product-title-full text-xs sm:text-[13px] font-bold text-brand-navy mb-1">
                            Đón Trả Khách Đúng Giờ Tại Đà Nẵng &amp; Thái Bình
                        </h3>
                        <p class="text-[11px] text-slate-600 leading-snug">
                            Đội ngũ tài xế và phụ xe giàu kinh nghiệm, phục vụ chu đáo, tận tâm với hành khách.
                        </p>
                    </div>
                </div>

                <!-- Ảnh thực tế 5 -->
                <div class="bg-white rounded-xl border border-slate-200 p-2 sm:p-2.5 shadow-sm flex flex-col justify-between col-span-2 md:col-span-1">
                    <div>
                        <div class="w-full h-28 sm:h-36 rounded-lg overflow-hidden bg-slate-100 mb-2">
                            <img src="https://drive.google.com/thumbnail?id=19ag9REQSxaHgHkcwwKMMbl-_fKHa94NG&sz=w800"
                                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/19ag9REQSxaHgHkcwwKMMbl-_fKHa94NG';"
                                 alt="Khoang hầm xe gửi hàng hóa và xe máy Nhà xe Mạnh La"
                                 class="w-full h-full object-cover">
                        </div>
                        <h3 class="product-title-full text-xs sm:text-[13px] font-bold text-brand-navy mb-1">
                            Hầm Hàng Rộng Rãi Chuyên Chở Xe Máy &amp; Kiện Hàng
                        </h3>
                        <p class="text-[11px] text-slate-600 leading-snug">
                            Nhận ký gửi hàng hóa, bưu kiện, xe máy nguyên chiếc có bọc lót chống trầy xước an toàn.
                        </p>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- =====================================================================
         SECTION 3: DỊCH VỤ VẬN TẢI HÀNG HÓA, GỬI XE MÁY & TRUNG CHUYỂN
         Chia 2 cột trên điện thoại, 4 cột trên máy tính, tên sản phẩm đầy đủ không cắt chữ
    ====================================================================== -->
    <section id="dich-vu-gui-hang" class="w-full py-4">
        <div class="flatsome-container">
            <div class="flex flex-col sm:flex-row sm:items-center justify-between gap-2 mb-3 pb-2 border-b-2 border-brand-gold">
                <div>
                    <h2 class="text-sm sm:text-base lg:text-lg font-extrabold text-brand-navy uppercase">
                        <i class="fa-solid fa-boxes-stacked text-brand-red mr-1.5"></i> Dịch Vụ Gửi Hàng Hóa - Xe Máy &amp; Trung Chuyển
                    </h2>
                    <p class="text-[11px] sm:text-xs text-slate-600">
                        Nhận gửi hàng tại 117 Lương Trúc Đàm, Phường Hòa Khánh, TP. Đà Nẵng và Bến xe Thái Bình
                    </p>
                </div>
            </div>

            <div class="grid grid-cols-2 lg:grid-cols-4 gap-2.5 sm:gap-4">
                
                <!-- Dịch vụ 1 -->
                <div class="bg-white rounded-xl border border-slate-200 p-2.5 sm:p-3.5 shadow-sm flex flex-col justify-between">
                    <div>
                        <div class="w-full h-28 sm:h-36 rounded-lg overflow-hidden bg-slate-100 mb-2">
                            <img src="https://drive.google.com/thumbnail?id=19ag9REQSxaHgHkcwwKMMbl-_fKHa94NG&sz=w800"
                                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/19ag9REQSxaHgHkcwwKMMbl-_fKHa94NG';"
                                 alt="Chuyển phát nhanh bưu kiện Đà Nẵng Thái Bình"
                                 class="w-full h-full object-cover">
                        </div>
                        <h3 class="product-title-full text-xs sm:text-sm font-bold text-brand-navy mb-1">
                            Chuyển Phát Nhanh Bưu Kiện &amp; Tài Liệu Đà Nẵng ⇄ Thái Bình
                        </h3>
                        <p class="text-[11px] text-slate-600 mb-2 leading-relaxed">
                            Nhận gửi giấy tờ, quà quê, thực phẩm đông lạnh, bưu phẩm hỏa tốc theo xe khách chỉ 12 - 14 tiếng nhận hàng.
                        </p>
                    </div>
                    <div class="pt-2 border-t border-slate-100">
                        <div class="text-xs font-extrabold text-brand-red mb-1.5">Cước phí từ 50.000đ</div>
                        <button type="button" onclick="selectServiceToForm('Chuyển Phát Nhanh Bưu Kiện Đà Nẵng ⇄ Thái Bình')" class="w-full py-1.5 px-2 rounded-lg bg-brand-navy hover:bg-slate-800 text-white font-bold text-[11px] sm:text-xs transition">
                            Báo giá gửi hàng
                        </button>
                    </div>
                </div>

                <!-- Dịch vụ 2 -->
                <div class="bg-white rounded-xl border border-slate-200 p-2.5 sm:p-3.5 shadow-sm flex flex-col justify-between">
                    <div>
                        <div class="w-full h-28 sm:h-36 rounded-lg overflow-hidden bg-slate-100 mb-2">
                            <img src="https://drive.google.com/thumbnail?id=1yfVWo_SvJJSMXONltqQOJh98eTW5zlb4&sz=w800"
                                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1yfVWo_SvJJSMXONltqQOJh98eTW5zlb4';"
                                 alt="Vận chuyển xe máy từ Đà Nẵng về Thái Bình"
                                 class="w-full h-full object-cover">
                        </div>
                        <h3 class="product-title-full text-xs sm:text-sm font-bold text-brand-navy mb-1">
                            Nhận Gửi Xe Máy &amp; Xe Đạp Điện Dưới Gầm Xe An Toàn
                        </h3>
                        <p class="text-[11px] text-slate-600 mb-2 leading-relaxed">
                            Hỗ trợ bọc lót bìa chống trầy xước, chằng buộc chắc chắn cho sinh viên, người lao động gửi xe máy về quê.
                        </p>
                    </div>
                    <div class="pt-2 border-t border-slate-100">
                        <div class="text-xs font-extrabold text-brand-red mb-1.5">Báo giá theo dòng xe</div>
                        <button type="button" onclick="selectServiceToForm('Vận Chuyển Xe Máy Tuyến Đà Nẵng ⇄ Thái Bình')" class="w-full py-1.5 px-2 rounded-lg bg-brand-navy hover:bg-slate-800 text-white font-bold text-[11px] sm:text-xs transition">
                            Báo giá gửi xe máy
                        </button>
                    </div>
                </div>

                <!-- Dịch vụ 3 -->
                <div class="bg-white rounded-xl border border-slate-200 p-2.5 sm:p-3.5 shadow-sm flex flex-col justify-between">
                    <div>
                        <div class="w-full h-28 sm:h-36 rounded-lg overflow-hidden bg-slate-100 mb-2">
                            <img src="https://drive.google.com/thumbnail?id=1-uJDzUOYJMYYpwz1s2cHTXJKkbv92FFw&sz=w800"
                                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1-uJDzUOYJMYYpwz1s2cHTXJKkbv92FFw';"
                                 alt="Trung chuyển đón trả khách tận nơi Hòa Khánh Đà Nẵng"
                                 class="w-full h-full object-cover">
                        </div>
                        <h3 class="product-title-full text-xs sm:text-sm font-bold text-brand-navy mb-1">
                            Dịch Vụ Trung Chuyển Đón Trả Khách Khu Vực Hòa Khánh &amp; Thái Bình
                        </h3>
                        <p class="text-[11px] text-slate-600 mb-2 leading-relaxed">
                            Hỗ trợ đón trả tận tình quanh khu vực 117 Lương Trúc Đàm, Hòa Khánh, Bến xe Đà Nẵng và nội thành Thái Bình.
                        </p>
                    </div>
                    <div class="pt-2 border-t border-slate-100">
                        <div class="text-xs font-extrabold text-brand-green mb-1.5">Hỗ trợ khách đặt trước</div>
                        <button type="button" onclick="selectServiceToForm('Đăng Ký Trung Chuyển Đón Trả Tận Nơi')" class="w-full py-1.5 px-2 rounded-lg bg-brand-navy hover:bg-slate-800 text-white font-bold text-[11px] sm:text-xs transition">
                            Đăng ký điểm đón
                        </button>
                    </div>
                </div>

                <!-- Dịch vụ 4 -->
                <div class="bg-white rounded-xl border border-slate-200 p-2.5 sm:p-3.5 shadow-sm flex flex-col justify-between">
                    <div>
                        <div class="w-full h-28 sm:h-36 rounded-lg overflow-hidden bg-slate-100 mb-2">
                            <img src="https://drive.google.com/thumbnail?id=1HW9BYDZavyYc6PVfGIf0OiVj9Z6_DFY3&sz=w800"
                                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1HW9BYDZavyYc6PVfGIf0OiVj9Z6_DFY3';"
                                 alt="Nhận gửi hàng kinh doanh và thu hộ COD"
                                 class="w-full h-full object-cover">
                        </div>
                        <h3 class="product-title-full text-xs sm:text-sm font-bold text-brand-navy mb-1">
                            Vận Chuyển Hàng Ghép Kinh Doanh &amp; Nhận Thu Hộ Tiền Hàng
                        </h3>
                        <p class="text-[11px] text-slate-600 mb-2 leading-relaxed">
                            Nhận vận chuyển hàng sỉ, linh kiện, máy móc, nông sản số lượng lớn giữa Đà Nẵng và Thái Bình, có biên nhận rõ ràng.
                        </p>
                    </div>
                    <div class="pt-2 border-t border-slate-100">
                        <div class="text-xs font-extrabold text-brand-red mb-1.5">Ưu đãi khách gửi thường xuyên</div>
                        <button type="button" onclick="selectServiceToForm('Báo Giá Gửi Hàng Ghép Kinh Doanh Số Lượng Lớn')" class="w-full py-1.5 px-2 rounded-lg bg-brand-navy hover:bg-slate-800 text-white font-bold text-[11px] sm:text-xs transition">
                            Nhận báo giá sỉ
                        </button>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- =====================================================================
         SECTION 4: HỆ THỐNG VĂN PHÒNG & ĐIỂM ĐÓN TRẢ (THEO MẪU VANMINH76.VN)
    ====================================================================== -->
    <section id="he-thong-van-phong" class="w-full py-4 bg-white border-y border-slate-200">
        <div class="flatsome-container">
            <div class="flex flex-col sm:flex-row sm:items-center justify-between gap-2 mb-3 pb-2 border-b-2 border-brand-gold">
                <div>
                    <h2 class="text-sm sm:text-base lg:text-lg font-extrabold text-brand-navy uppercase">
                        <i class="fa-solid fa-building-flag text-brand-red mr-1.5"></i> Hệ Thống Văn Phòng &amp; Điểm Đón Trả Nhà Xe Mạnh La
                    </h2>
                    <p class="text-[11px] sm:text-xs text-slate-600">
                        Quý khách có thể liên hệ trực tiếp tại văn phòng hoặc đặt vé qua tổng đài để được nhân viên giữ giường tốt nhất
                    </p>
                </div>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-3 gap-3">
                <!-- Văn phòng 1: Trụ sở chính Đà Nẵng -->
                <div class="rounded-xl border border-amber-300 bg-amber-50/40 p-3.5 shadow-sm">
                    <div class="flex items-center gap-2 text-brand-red font-extrabold text-xs sm:text-sm mb-1.5">
                        <i class="fa-solid fa-location-dot"></i>
                        <span>VĂN PHÒNG ĐÀ NẴNG (TRỤ SỞ CHÍNH)</span>
                    </div>
                    <p class="text-xs font-semibold text-slate-800 mb-1">
                        📍 Địa chỉ: 117 Lương Trúc Đàm, Phường Hòa Khánh, Tp.Đà Nẵng
                    </p>
                    <p class="text-xs text-slate-600 mb-2">
                        📞 Điện thoại: <a href="tel:0988026577" class="font-bold text-brand-red">0988.026.577</a> - <a href="tel:0981068333" class="font-bold text-brand-red">0981.068.333</a>
                    </p>
                    <div class="flex flex-wrap gap-2">
                        <a href="https://share.google/INCCvImO1tohry08J" target="_blank" rel="noopener noreferrer" class="inline-flex items-center gap-1 text-[11px] font-bold bg-brand-navy text-white px-2.5 py-1.5 rounded-lg hover:bg-slate-800 transition">
                            <i class="fa-solid fa-map"></i> Mở bằng Google Maps
                        </a>
                        <a href="tel:0988026577" class="inline-flex items-center gap-1 text-[11px] font-bold bg-brand-gold text-white px-2.5 py-1.5 rounded-lg hover:bg-amber-600 transition">
                            <i class="fa-solid fa-phone"></i> Liên hệ văn phòng
                        </a>
                    </div>
                </div>

                <!-- Văn phòng 2: Điểm đón Bến xe Đà Nẵng -->
                <div class="rounded-xl border border-slate-200 bg-slate-50 p-3.5 shadow-sm">
                    <div class="flex items-center gap-2 text-brand-navy font-extrabold text-xs sm:text-sm mb-1.5">
                        <i class="fa-solid fa-bus"></i>
                        <span>ĐIỂM ĐÓN BẾN XE TRUNG TÂM ĐÀ NẴNG</span>
                    </div>
                    <p class="text-xs font-semibold text-slate-800 mb-1">
                        📍 Địa chỉ: Bến xe Trung tâm TP. Đà Nẵng (Tôn Đức Thắng, Liên Chiểu) &amp; Dọc Nguyễn Lương Bằng
                    </p>
                    <p class="text-xs text-slate-600 mb-2">
                        📞 Đặt vé &amp; gửi hàng: <a href="tel:0988026577" class="font-bold text-brand-red">0988.026.577</a> - <a href="tel:0981068333" class="font-bold text-brand-red">0981.068.333</a>
                    </p>
                    <div class="flex flex-wrap gap-2">
                        <a href="#form-bao-gia" class="inline-flex items-center gap-1 text-[11px] font-bold bg-brand-red text-white px-2.5 py-1.5 rounded-lg hover:bg-brand-redDark transition">
                            <i class="fa-solid fa-ticket"></i> Đặt chỗ trước
                        </a>
                    </div>
                </div>

                <!-- Văn phòng 3: Đầu bến Thái Bình -->
                <div class="rounded-xl border border-slate-200 bg-slate-50 p-3.5 shadow-sm">
                    <div class="flex items-center gap-2 text-brand-navy font-extrabold text-xs sm:text-sm mb-1.5">
                        <i class="fa-solid fa-flag-checkered"></i>
                        <span>ĐIỂM ĐÓN TRẢ ĐẦU BẾN THÁI BÌNH</span>
                    </div>
                    <p class="text-xs font-semibold text-slate-800 mb-1">
                        📍 Địa chỉ: Bến xe khách Thái Bình (Đường Lý Thường Kiệt, TP. Thái Bình) &amp; các điểm dọc tuyến
                    </p>
                    <p class="text-xs text-slate-600 mb-2">
                        📞 Hotline nhà xe: <a href="tel:0981068333" class="font-bold text-brand-red">0981.068.333</a> - <a href="tel:0988026577" class="font-bold text-brand-red">0988.026.577</a>
                    </p>
                    <div class="flex flex-wrap gap-2">
                        <a href="#form-bao-gia" class="inline-flex items-center gap-1 text-[11px] font-bold bg-brand-red text-white px-2.5 py-1.5 rounded-lg hover:bg-brand-redDark transition">
                            <i class="fa-solid fa-paper-plane"></i> Yêu cầu đón khách
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- =====================================================================
         SECTION 5: FORM YÊU CẦU & BÁO GIÁ TRANG CHỦ + FACEBOOK + ẢNH GOOGLE MAP TRANG CHỦ
         Đầy đủ 3 yêu cầu quan trọng:
         1. Form yêu cầu và báo giá trang chủ
         2. Đưa Facebook https://www.facebook.com/manh.hoangvan.16503323/ ra ngoài trang chủ
         3. Đưa ảnh Google Map & bản đồ định vị 117 Lương Trúc Đàm ra ngoài trang chủ
    ====================================================================== -->
    <section id="form-bao-gia" class="w-full py-5">
        <div class="flatsome-container">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-4">
                
                <!-- CỘT TRÁI (5/12): FORM YÊU CẦU ĐẶT VÉ & BÁO GIÁ GỬI HÀNG TRANG CHỦ -->
                <div class="lg:col-span-5 bg-white rounded-xl border-2 border-brand-gold shadow-sm p-4">
                    <div class="border-b border-slate-200 pb-2.5 mb-3">
                        <h2 class="text-sm sm:text-base font-extrabold text-brand-navy uppercase flex items-center gap-2">
                            <i class="fa-solid fa-file-signature text-brand-red"></i>
                            Form Yêu Cầu Đặt Vé &amp; Báo Giá
                        </h2>
                        <p class="text-[11px] text-slate-600 mt-0.5">
                            Điền thông tin bên dưới, Nhà xe Mạnh La sẽ liên hệ xác nhận giường nằm / báo giá cước gửi hàng ngay lập tức!
                        </p>
                    </div>

                    <form id="quoteForm" onsubmit="handleQuoteSubmit(event)" class="space-y-2.5 text-xs">
                        <div>
                            <label class="block font-bold text-slate-700 mb-1">Họ và tên quý khách *</label>
                            <input type="text" id="custName" required placeholder="Ví dụ: Anh Nam / Chị Lan..." class="w-full rounded-lg border border-slate-300 px-3 py-2 focus:outline-none focus:border-brand-gold">
                        </div>

                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-2.5">
                            <div>
                                <label class="block font-bold text-slate-700 mb-1">Số điện thoại / Zalo *</label>
                                <input type="tel" id="custPhone" required placeholder="Nhập SĐT liên hệ..." class="w-full rounded-lg border border-slate-300 px-3 py-2 focus:outline-none focus:border-brand-gold">
                            </div>
                            <div>
                                <label class="block font-bold text-slate-700 mb-1">Ngày khởi hành / Gửi hàng</label>
                                <input type="date" id="custDate" class="w-full rounded-lg border border-slate-300 px-3 py-2 focus:outline-none focus:border-brand-gold">
                            </div>
                        </div>

                        <div>
                            <label class="block font-bold text-slate-700 mb-1">Dịch vụ cần yêu cầu / Báo giá *</label>
                            <select id="custService" class="w-full rounded-lg border border-slate-300 px-3 py-2 font-medium focus:outline-none focus:border-brand-gold">
                                <option value="Đặt vé Xe Giường Nằm Đà Nẵng -> Thái Bình (550.000đ)">Đặt vé Xe Giường Nằm Đà Nẵng → Thái Bình (550.000đ)</option>
                                <option value="Đặt vé Xe Giường Nằm Thái Bình -> Đà Nẵng (550.000đ)">Đặt vé Xe Giường Nằm Thái Bình → Đà Nẵng (550.000đ)</option>
                                <option value="Đặt vé Xe Limousine Phòng VIP (700.000đ)">Đặt vé Xe Limousine Phòng VIP (700.000đ)</option>
                                <option value="Yêu cầu báo giá gửi hàng hóa / bưu kiện">Yêu cầu báo giá gửi hàng hóa / bưu kiện</option>
                                <option value="Yêu cầu báo giá gửi xe máy Đà Nẵng ⇄ Thái Bình">Yêu cầu báo giá gửi xe máy Đà Nẵng ⇄ Thái Bình</option>
                                <option value="Đặt vé đoàn / Gia đình / Công nhân KCN Hòa Khánh">Đặt vé đoàn / Gia đình / Công nhân KCN Hòa Khánh</option>
                            </select>
                        </div>

                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-2.5">
                            <div>
                                <label class="block font-bold text-slate-700 mb-1">Số lượng vé / Kiện hàng</label>
                                <input type="text" id="custQty" placeholder="VD: 2 vé giường tầng 1 / 1 xe máy" class="w-full rounded-lg border border-slate-300 px-3 py-2 focus:outline-none focus:border-brand-gold">
                            </div>
                            <div>
                                <label class="block font-bold text-slate-700 mb-1">Điểm đón / Điểm nhận hàng</label>
                                <input type="text" id="custPickup" placeholder="VD: 117 Lương Trúc Đàm, Hòa Khánh" class="w-full rounded-lg border border-slate-300 px-3 py-2 focus:outline-none focus:border-brand-gold">
                            </div>
                        </div>

                        <div>
                            <label class="block font-bold text-slate-700 mb-1">Ghi chú thêm (nếu có)</label>
                            <textarea id="custNote" rows="2" placeholder="Nhập yêu cầu chi tiết (chọn giường, loại hàng hóa, giờ đón...)" class="w-full rounded-lg border border-slate-300 px-3 py-2 focus:outline-none focus:border-brand-gold"></textarea>
                        </div>

                        <button type="submit" class="w-full py-2.5 px-4 rounded-lg bg-brand-red hover:bg-brand-redDark text-white font-extrabold text-xs sm:text-sm uppercase tracking-wide transition shadow flex items-center justify-center gap-2">
                            <i class="fa-solid fa-paper-plane"></i> GỬI YÊU CẦU &amp; NHẬN BÁO GIÁ NGAY
                        </button>
                    </form>

                    <!-- Hộp thông báo kết quả gửi form (thay cho alert) -->
                    <div id="formSuccessBox" class="hidden mt-3 p-3 rounded-lg bg-green-50 border border-green-300 text-green-900 text-xs">
                        <div class="font-bold text-green-800 mb-1">
                            <i class="fa-solid fa-circle-check"></i> Đã ghi nhận yêu cầu thành công!
                        </div>
                        <p id="formSuccessText" class="mb-2 leading-relaxed"></p>
                        <div class="flex flex-wrap gap-2">
                            <a href="tel:0988026577" class="inline-flex items-center gap-1 bg-brand-red text-white font-bold px-2.5 py-1 rounded text-[11px]">
                                <i class="fa-solid fa-phone"></i> Gọi ngay: 0988.026.577
                            </a>
                            <a href="https://zalo.me/0988026577" target="_blank" rel="noopener noreferrer" class="inline-flex items-center gap-1 bg-blue-600 text-white font-bold px-2.5 py-1 rounded text-[11px]">
                                <i class="fa-solid fa-comment-dots"></i> Nhắn Zalo xác nhận
                            </a>
                        </div>
                    </div>
                </div>

                <!-- CỘT PHẢI (7/12): ĐƯA FACEBOOK & ẢNH GOOGLE MAP RA NGOÀI TRANG CHỦ -->
                <div id="ban-do-lien-he" class="lg:col-span-7 flex flex-col gap-4">
                    
                    <!-- KHỐI FACEBOOK NHÀ XE MẠNH LA NGOÀI TRANG CHỦ -->
                    <div class="bg-white rounded-xl border border-slate-200 shadow-sm p-3.5">
                        <div class="flex flex-col sm:flex-row sm:items-center justify-between gap-2 pb-2.5 mb-3 border-b border-slate-100">
                            <div class="flex items-center gap-2">
                                <div class="w-9 h-9 rounded-full bg-blue-600 text-white flex items-center justify-center text-base shrink-0">
                                    <i class="fa-brands fa-facebook-f"></i>
                                </div>
                                <div>
                                    <h3 class="text-xs sm:text-sm font-extrabold text-brand-navy uppercase">
                                        Facebook Chính Thức - Nhà Xe Mạnh La
                                    </h3>
                                    <p class="text-[11px] text-slate-500">
                                        Cập nhật lịch trình xe chạy, giờ xuất bến &amp; hình ảnh thực tế mỗi ngày
                                    </p>
                                </div>
                            </div>
                            <a href="https://www.facebook.com/manh.hoangvan.16503323/" target="_blank" rel="noopener noreferrer" class="inline-flex items-center justify-center gap-1.5 px-3 py-1.5 rounded-lg bg-blue-600 hover:bg-blue-700 text-white text-xs font-bold transition shrink-0">
                                <i class="fa-brands fa-facebook"></i> Truy Cập Facebook Nhà Xe
                            </a>
                        </div>

                        <div class="grid grid-cols-1 sm:grid-cols-12 gap-3 items-center bg-blue-50/60 border border-blue-200 rounded-lg p-3">
                            <div class="sm:col-span-3 flex items-center justify-center">
                                <img src="https://drive.google.com/thumbnail?id=1KOwoeHiDvElLvRAo4KmImG7UqxNjcPNW&sz=w400"
                                     onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1KOwoeHiDvElLvRAo4KmImG7UqxNjcPNW';"
                                     alt="Facebook Nhà xe Mạnh La"
                                     class="w-16 h-16 object-contain rounded-lg bg-white p-1 border border-blue-200 shadow-sm">
                            </div>
                            <div class="sm:col-span-9 text-xs space-y-1">
                                <div class="font-extrabold text-blue-900 text-sm">
                                    Hoàng Văn Mạnh (Nhà Xe Mạnh La Đà Nẵng - Thái Bình)
                                </div>
                                <p class="text-slate-700 leading-snug">
                                    Kết nối trực tiếp qua Facebook để xem lịch xe chạy thực tế, nhắn tin đặt giường nằm và kiểm tra lộ trình đơn hàng.
                                </p>
                                <div class="pt-1 flex flex-wrap items-center gap-2">
                                    <a href="https://www.facebook.com/manh.hoangvan.16503323/" target="_blank" rel="noopener noreferrer" class="text-[11px] font-bold text-blue-700 underline break-all">
                                        https://www.facebook.com/manh.hoangvan.16503323/
                                    </a>
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- KHỐI ẢNH GOOGLE MAP & BẢN ĐỒ ĐỊA CHỈ 117 LƯƠNG TRÚC ĐÀM NGOÀI TRANG CHỦ -->
                    <div class="bg-white rounded-xl border border-slate-200 shadow-sm p-3.5 flex-1 flex flex-col justify-between">
                        <div class="flex flex-col sm:flex-row sm:items-center justify-between gap-2 pb-2.5 mb-2.5 border-b border-slate-100">
                            <div>
                                <h3 class="text-xs sm:text-sm font-extrabold text-brand-navy uppercase flex items-center gap-1.5">
                                    <i class="fa-solid fa-map-location-dot text-brand-red"></i>
                                    Bản Đồ Google Map - Văn Phòng Nhà Xe Mạnh La
                                </h3>
                                <p class="text-[11px] text-slate-600 font-medium mt-0.5">
                                    Địa chỉ: <strong>117 Lương Trúc Đàm, Phường Hòa Khánh, Tp.Đà Nẵng</strong>
                                </p>
                            </div>
                            <a href="https://share.google/INCCvImO1tohry08J" target="_blank" rel="noopener noreferrer" class="inline-flex items-center justify-center gap-1.5 px-3 py-1.5 rounded-lg bg-brand-green hover:bg-green-800 text-white text-xs font-bold transition shrink-0">
                                <i class="fa-solid fa-diamond-turn-right"></i> Chỉ Đường Google Map
                            </a>
                        </div>

                        <!-- Bản đồ Google Map trực quan & thẻ ảnh chỉ đường trên trang chủ -->
                        <div class="w-full rounded-lg overflow-hidden border border-slate-300 bg-slate-100 relative">
                            <iframe
                                title="Bản đồ Google Map Nhà Xe Mạnh La 117 Lương Trúc Đàm, Hòa Khánh, Đà Nẵng"
                                src="https://maps.google.com/maps?q=117%20L%C6%B0%C6%A1ng%20Tr%C3%BAc%20%C4%90%C3%A0m,%20H%C3%B2a%20Kh%C3%A1nh,%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed"
                                class="w-full h-[220px] sm:h-[240px] border-0 block"
                                loading="lazy"
                                referrerpolicy="no-referrer-when-downgrade">
                            </iframe>
                            <!-- Thanh thông tin ghim trực tiếp dưới ảnh bản đồ -->
                            <div class="bg-slate-900 text-white px-3 py-2 flex flex-wrap items-center justify-between gap-2 text-[11px]">
                                <div>
                                    <i class="fa-solid fa-location-crosshairs text-amber-400 mr-1"></i>
                                    <strong>Vị trí:</strong> 117 Lương Trúc Đàm, P. Hòa Khánh, TP. Đà Nẵng
                                </div>
                                <a href="https://share.google/INCCvImO1tohry08J" target="_blank" rel="noopener noreferrer" class="text-amber-300 hover:underline font-bold">
                                    Xem trên Google Maps (share.google/INCCvImO1tohry08J) <i class="fa-solid fa-up-right-from-square ml-0.5"></i>
                                </a>
                            </div>
                        </div>
                    </div>

                </div>
            </div>
        </div>
    </section>

    <!-- =====================================================================
         SECTION 6: DANH MỤC CÁC BÀI VIẾT TRANG CHỦ (TIN TỨC & CẨM NANG HÀNH TRÌNH)
         Chia 2 cột trên điện thoại (grid-cols-2), 4 cột trên máy tính (lg:grid-cols-4)
    ====================================================================== -->
    <section id="tin-tuc" class="w-full py-4 bg-white border-t border-slate-200">
        <div class="flatsome-container">
            <div class="flex flex-col sm:flex-row sm:items-center justify-between gap-2 mb-3 pb-2 border-b-2 border-brand-gold">
                <div>
                    <h2 class="text-sm sm:text-base lg:text-lg font-extrabold text-brand-navy uppercase">
                        <i class="fa-solid fa-newspaper text-brand-red mr-1.5"></i> Danh Mục Bài Viết &amp; Tin Tức Nhà Xe Mạnh La
                    </h2>
                    <p class="text-[11px] sm:text-xs text-slate-600">
                        Kinh nghiệm đặt vé xe Đà Nẵng - Thái Bình, lịch chạy xe lễ Tết và hướng dẫn gửi hàng hóa an toàn
                    </p>
                </div>
            </div>

            <div class="grid grid-cols-2 lg:grid-cols-4 gap-2.5 sm:gap-4">
                
                <!-- Bài viết 1 -->
                <article class="bg-slate-50 rounded-xl border border-slate-200 overflow-hidden p-2 sm:p-3 flex flex-col justify-between hover:border-brand-gold transition">
                    <div>
                        <div class="w-full h-28 sm:h-36 rounded-lg overflow-hidden bg-slate-200 mb-2">
                            <img src="https://drive.google.com/thumbnail?id=1-uJDzUOYJMYYpwz1s2cHTXJKkbv92FFw&sz=w800"
                                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1-uJDzUOYJMYYpwz1s2cHTXJKkbv92FFw';"
                                 alt="Lịch trình và giá vé xe Mạnh La Đà Nẵng đi Thái Bình"
                                 class="w-full h-full object-cover">
                        </div>
                        <span class="text-[10px] font-semibold text-brand-gold block mb-1">
                            <i class="fa-regular fa-calendar"></i> Cẩm nang tuyến xe
                        </span>
                        <h3 class="product-title-full text-xs sm:text-sm font-bold text-brand-navy mb-1">
                            Lịch Trình Chi Tiết &amp; Giá Vé Xe Khách Mạnh La Tuyến Đà Nẵng Đi Thái Bình Mới Nhất
                        </h3>
                        <p class="text-[11px] text-slate-600 leading-relaxed">
                            Tổng hợp giờ xe xuất bến tại 117 Lương Trúc Đàm (Hòa Khánh) và Bến xe Thái Bình cùng lộ trình di chuyển qua QL1A.
                        </p>
                    </div>
                    <div class="pt-2 mt-2 border-t border-slate-200">
                        <a href="#form-bao-gia" class="text-[11px] font-bold text-brand-red hover:underline">
                            Đọc chi tiết &amp; Đặt vé <i class="fa-solid fa-angle-right"></i>
                        </a>
                    </div>
                </article>

                <!-- Bài viết 2 -->
                <article class="bg-slate-50 rounded-xl border border-slate-200 overflow-hidden p-2 sm:p-3 flex flex-col justify-between hover:border-brand-gold transition">
                    <div>
                        <div class="w-full h-28 sm:h-36 rounded-lg overflow-hidden bg-slate-200 mb-2">
                            <img src="https://drive.google.com/thumbnail?id=19ag9REQSxaHgHkcwwKMMbl-_fKHa94NG&sz=w800"
                                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/19ag9REQSxaHgHkcwwKMMbl-_fKHa94NG';"
                                 alt="Kinh nghiệm gửi xe máy từ Đà Nẵng về Thái Bình"
                                 class="w-full h-full object-cover">
                        </div>
                        <span class="text-[10px] font-semibold text-brand-gold block mb-1">
                            <i class="fa-regular fa-calendar"></i> Dịch vụ gửi hàng
                        </span>
                        <h3 class="product-title-full text-xs sm:text-sm font-bold text-brand-navy mb-1">
                            Hướng Dẫn Thủ Tục Gửi Xe Máy &amp; Hàng Cồng Kềnh Tuyến Đà Nẵng ⇄ Thái Bình An Toàn
                        </h3>
                        <p class="text-[11px] text-slate-600 leading-relaxed">
                            Quy trình bọc lót chống trầy xước, rút xăng an toàn phòng cháy nổ và ghi phiếu biên nhận khi gửi xe máy dưới gầm xe.
                        </p>
                    </div>
                    <div class="pt-2 mt-2 border-t border-slate-200">
                        <a href="#form-bao-gia" class="text-[11px] font-bold text-brand-red hover:underline">
                            Xem hướng dẫn gửi hàng <i class="fa-solid fa-angle-right"></i>
                        </a>
                    </div>
                </article>

                <!-- Bài viết 3 -->
                <article class="bg-slate-50 rounded-xl border border-slate-200 overflow-hidden p-2 sm:p-3 flex flex-col justify-between hover:border-brand-gold transition">
                    <div>
                        <div class="w-full h-28 sm:h-36 rounded-lg overflow-hidden bg-slate-200 mb-2">
                            <img src="https://drive.google.com/thumbnail?id=1M9DjgIH268z_04t8GobbfHRB4pgTSkcN&sz=w800"
                                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1M9DjgIH268z_04t8GobbfHRB4pgTSkcN';"
                                 alt="Điểm đón trả khách tại Phường Hòa Khánh Đà Nẵng"
                                 class="w-full h-full object-cover">
                        </div>
                        <span class="text-[10px] font-semibold text-brand-gold block mb-1">
                            <i class="fa-regular fa-calendar"></i> Tin tức nhà xe
                        </span>
                        <h3 class="product-title-full text-xs sm:text-sm font-bold text-brand-navy mb-1">
                            Điểm Đón Khách &amp; Nhận Hàng Tại 117 Lương Trúc Đàm, Phường Hòa Khánh, TP. Đà Nẵng
                        </h3>
                        <p class="text-[11px] text-slate-600 leading-relaxed">
                            Thuận tiện cho sinh viên các trường đại học, công nhân KCN Hòa Khánh gửi đồ và đón xe về quê Thái Bình nhanh chóng.
                        </p>
                    </div>
                    <div class="pt-2 mt-2 border-t border-slate-200">
                        <a href="#ban-do-lien-he" class="text-[11px] font-bold text-brand-red hover:underline">
                            Xem vị trí trên bản đồ <i class="fa-solid fa-angle-right"></i>
                        </a>
                    </div>
                </article>

                <!-- Bài viết 4 -->
                <article class="bg-slate-50 rounded-xl border border-slate-200 overflow-hidden p-2 sm:p-3 flex flex-col justify-between hover:border-brand-gold transition">
                    <div>
                        <div class="w-full h-28 sm:h-36 rounded-lg overflow-hidden bg-slate-200 mb-2">
                            <img src="https://drive.google.com/thumbnail?id=1HW9BYDZavyYc6PVfGIf0OiVj9Z6_DFY3&sz=w800"
                                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1HW9BYDZavyYc6PVfGIf0OiVj9Z6_DFY3';"
                                 alt="Lưu ý đặt vé xe dịp Lễ Tết tuyến Đà Nẵng Thái Bình"
                                 class="w-full h-full object-cover">
                        </div>
                        <span class="text-[10px] font-semibold text-brand-gold block mb-1">
                            <i class="fa-regular fa-calendar"></i> Khuyến mãi &amp; Ưu đãi
                        </span>
                        <h3 class="product-title-full text-xs sm:text-sm font-bold text-brand-navy mb-1">
                            Kinh Nghiệm Đặt Vé Xe Giường Nằm Mạnh La Dịp Lễ Tết &amp; Ưu Đãi Vé Khứ Hồi 10%
                        </h3>
                        <p class="text-[11px] text-slate-600 leading-relaxed">
                            Chủ động gọi hotline 0988.026.577 - 0981.068.333 chính thức của nhà xe để giữ giường tầng 1 và nhận ưu đãi khứ hồi.
                        </p>
                    </div>
                    <div class="pt-2 mt-2 border-t border-slate-200">
                        <a href="tel:0988026577" class="text-[11px] font-bold text-brand-red hover:underline">
                            Liên hệ giữ vé sớm <i class="fa-solid fa-angle-right"></i>
                        </a>
                    </div>
                </article>

            </div>
        </div>
    </section>

    <!-- =====================================================================
         SECTION 7: DANH MỤC CÁC ĐỐI TÁC ĐỒNG HÀNH
    ====================================================================== -->
    <section id="doi-tac" class="w-full py-4 bg-slate-100 border-t border-slate-200">
        <div class="flatsome-container">
            <div class="flex flex-col sm:flex-row sm:items-center justify-between gap-2 mb-3">
                <div>
                    <h2 class="text-sm sm:text-base font-extrabold text-brand-navy uppercase">
                        <i class="fa-solid fa-handshake text-brand-gold mr-1.5"></i> Danh Mục Các Đối Tác Đồng Hành
                    </h2>
                    <p class="text-[11px] text-slate-600">
                        Hợp tác cùng các bến xe, đơn vị vận tải và cổng thanh toán uy tín trên toàn quốc
                    </p>
                </div>
            </div>

            <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-2.5">
                <div class="bg-white rounded-lg border border-slate-200 p-3 text-center flex flex-col items-center justify-center shadow-sm">
                    <i class="fa-solid fa-building-columns text-brand-navy text-lg mb-1"></i>
                    <span class="text-xs font-extrabold text-slate-800">BX Trung Tâm Đà Nẵng</span>
                    <span class="text-[10px] text-slate-500">Đối tác bến bãi</span>
                </div>
                <div class="bg-white rounded-lg border border-slate-200 p-3 text-center flex flex-col items-center justify-center shadow-sm">
                    <i class="fa-solid fa-warehouse text-brand-red text-lg mb-1"></i>
                    <span class="text-xs font-extrabold text-slate-800">Bến Xe Thái Bình</span>
                    <span class="text-[10px] text-slate-500">Đối tác vận hành</span>
                </div>
                <div class="bg-white rounded-lg border border-slate-200 p-3 text-center flex flex-col items-center justify-center shadow-sm">
                    <i class="fa-solid fa-bus-simple text-brand-gold text-lg mb-1"></i>
                    <span class="text-xs font-extrabold text-slate-800">Thaco Bus Việt Nam</span>
                    <span class="text-[10px] text-slate-500">Đối tác phương tiện</span>
                </div>
                <div class="bg-white rounded-lg border border-slate-200 p-3 text-center flex flex-col items-center justify-center shadow-sm">
                    <i class="fa-solid fa-gas-pump text-blue-600 text-lg mb-1"></i>
                    <span class="text-xs font-extrabold text-slate-800">Petrolimex</span>
                    <span class="text-[10px] text-slate-500">Đối tác nhiên liệu</span>
                </div>
                <div class="bg-white rounded-lg border border-slate-200 p-3 text-center flex flex-col items-center justify-center shadow-sm">
                    <i class="fa-solid fa-shield-heart text-green-600 text-lg mb-1"></i>
                    <span class="text-xs font-extrabold text-slate-800">Bảo Hiểm PVI</span>
                    <span class="text-[10px] text-slate-500">Bảo hiểm hành khách</span>
                </div>
                <div class="bg-white rounded-lg border border-slate-200 p-3 text-center flex flex-col items-center justify-center shadow-sm">
                    <i class="fa-solid fa-qrcode text-purple-600 text-lg mb-1"></i>
                    <span class="text-xs font-extrabold text-slate-800">VietQR &amp; Ngân Hàng</span>
                    <span class="text-[10px] text-slate-500">Thanh toán 24/7</span>
                </div>
            </div>
        </div>
    </section>

    <!-- =====================================================================
         FOOTER CHUẨN FLATSOME (THEO MẪU VANMINH76.VN)
    ====================================================================== -->
    <footer class="w-full bg-brand-navy text-slate-200 pt-8 pb-20 lg:pb-8 border-t-4 border-brand-gold">
        <div class="flatsome-container">
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-6 pb-6 border-b border-slate-700">
                
                <!-- Cột 1: Thông tin thương hiệu + Logo -->
                <div>
                    <div class="flex items-center gap-2.5 mb-3">
                        <div class="w-11 h-11 rounded-lg bg-white p-0.5 flex items-center justify-center shrink-0">
                            <img src="https://drive.google.com/thumbnail?id=1KOwoeHiDvElLvRAo4KmImG7UqxNjcPNW&sz=w300"
                                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1KOwoeHiDvElLvRAo4KmImG7UqxNjcPNW';"
                                 alt="Logo Nhà Xe Mạnh La"
                                 class="w-full h-full object-contain rounded">
                        </div>
                        <div>
                            <h3 class="text-sm font-extrabold text-amber-400 uppercase">NHÀ XE MẠNH LA</h3>
                            <p class="text-[11px] text-slate-300">Website: nhaxemanhla.com</p>
                        </div>
                    </div>
                    <p class="text-xs text-slate-300 leading-relaxed mb-3">
                        Đơn vị vận tải hành khách giường nằm cao cấp, Limousine VIP và chuyển phát hàng hóa uy tín chuyên tuyến <strong>Đà Nẵng ⇄ Thái Bình</strong>.
                    </p>
                </div>

                <!-- Cột 2: Thông tin liên hệ -->
                <div>
                    <h4 class="text-xs sm:text-sm font-extrabold text-amber-400 uppercase mb-3">Thông Tin Liên Hệ</h4>
                    <ul class="space-y-2 text-xs">
                        <li class="flex items-start gap-2">
                            <i class="fa-solid fa-location-dot text-amber-400 mt-1"></i>
                            <span>Địa chỉ: 117 Lương Trúc Đàm, Phường Hòa Khánh, Tp.Đà Nẵng</span>
                        </li>
                        <li class="flex items-center gap-2">
                            <i class="fa-solid fa-phone-volume text-amber-400"></i>
                            <span>Hotline: <strong class="text-white">0988.026.577 - 0981.068.333</strong></span>
                        </li>
                        <li class="flex items-center gap-2">
                            <i class="fa-solid fa-globe text-amber-400"></i>
                            <span>Website: <a href="https://nhaxemanhla.com" class="text-amber-300 hover:underline">nhaxemanhla.com</a></span>
                        </li>
                        <li class="flex items-center gap-2">
                            <i class="fa-brands fa-facebook text-amber-400"></i>
                            <a href="https://www.facebook.com/manh.hoangvan.16503323/" target="_blank" rel="noopener noreferrer" class="text-amber-300 hover:underline truncate">
                                fb.com/manh.hoangvan.16503323
                            </a>
                        </li>
                    </ul>
                </div>

                <!-- Cột 3: Danh mục dịch vụ -->
                <div>
                    <h4 class="text-xs sm:text-sm font-extrabold text-amber-400 uppercase mb-3">Danh Mục Dịch Vụ</h4>
                    <ul class="space-y-1.5 text-xs">
                        <li><a href="#lich-trinh" class="hover:text-amber-300 transition"><i class="fa-solid fa-angle-right text-amber-400 mr-1"></i> Xe giường nằm Đà Nẵng - Thái Bình</a></li>
                        <li><a href="#lich-trinh" class="hover:text-amber-300 transition"><i class="fa-solid fa-angle-right text-amber-400 mr-1"></i> Xe giường nằm Thái Bình - Đà Nẵng</a></li>
                        <li><a href="#tien-ich-xe" class="hover:text-amber-300 transition"><i class="fa-solid fa-angle-right text-amber-400 mr-1"></i> Dòng xe Limousine Phòng VIP</a></li>
                        <li><a href="#dich-vu-gui-hang" class="hover:text-amber-300 transition"><i class="fa-solid fa-angle-right text-amber-400 mr-1"></i> Gửi hàng hóa &amp; Xe máy Bắc - Nam</a></li>
                        <li><a href="#form-bao-gia" class="hover:text-amber-300 transition"><i class="fa-solid fa-angle-right text-amber-400 mr-1"></i> Yêu cầu đặt vé &amp; Báo giá</a></li>
                    </ul>
                </div>

                <!-- Cột 4: Hỗ trợ khách hàng -->
                <div>
                    <h4 class="text-xs sm:text-sm font-extrabold text-amber-400 uppercase mb-3">Cam Kết Phục Vụ</h4>
                    <ul class="space-y-1.5 text-xs text-slate-300">
                        <li><i class="fa-solid fa-circle-check text-amber-400 mr-1.5"></i> Giữ đúng vị trí giường đã đặt</li>
                        <li><i class="fa-solid fa-circle-check text-amber-400 mr-1.5"></i> Không nhồi nhét khách dọc đường</li>
                        <li><i class="fa-solid fa-circle-check text-amber-400 mr-1.5"></i> Hàng hóa, xe máy nguyên vẹn 100%</li>
                        <li><i class="fa-solid fa-circle-check text-amber-400 mr-1.5"></i> Giá vé niêm yết minh bạch, rõ ràng</li>
                    </ul>
                </div>

            </div>

            <div class="pt-4 flex flex-col sm:flex-row items-center justify-between gap-2 text-[11px] text-slate-400 text-center sm:text-left">
                <p>© Bản quyền thuộc về <strong class="text-white">Nhà Xe Mạnh La (nhaxemanhla.com)</strong> - Chuyên tuyến Đà Nẵng ⇄ Thái Bình.</p>
                <p>Địa chỉ: 117 Lương Trúc Đàm, Phường Hòa Khánh, Tp.Đà Nẵng | ĐT: 0988.026.577 - 0981.068.333</p>
            </div>
        </div>
    </footer>

    <!-- =====================================================================
         CÁC NÚT LIÊN HỆ NỔI BẬT (ZALO, FACEBOOK, HOTLINE)
         Tương thích hoàn hảo trên cả máy tính và điện thoại, không gây tràn viền
    ====================================================================== -->
    <div class="fixed right-2.5 bottom-4 z-50 flex flex-col items-end gap-2">
        
        <!-- Nút Facebook nổi -->
        <a href="https://www.facebook.com/manh.hoangvan.16503323/" target="_blank" rel="noopener noreferrer"
           class="flex items-center gap-2 bg-[#1877F2] hover:bg-blue-700 text-white px-3 py-2 rounded-full shadow-lg transition transform hover:scale-105"
           title="Facebook Nhà Xe Mạnh La">
            <i class="fa-brands fa-facebook-f text-sm w-4 text-center"></i>
            <span class="text-[11px] font-bold">Facebook</span>
        </a>

        <!-- Nút Zalo nổi -->
        <a href="https://zalo.me/0988026577" target="_blank" rel="noopener noreferrer"
           class="flex items-center gap-2 bg-[#0068FF] hover:bg-blue-600 text-white px-3 py-2 rounded-full shadow-lg transition transform hover:scale-105"
           title="Nhắn Zalo 0988.026.577">
            <span class="font-extrabold text-xs bg-white text-[#0068FF] px-1.5 py-0.5 rounded-full leading-none">Zalo</span>
            <span class="text-[11px] font-bold">0988.026.577</span>
        </a>

        <!-- Nút Hotline 1 nổi -->
        <a href="tel:0988026577"
           class="floating-pulse flex items-center gap-2 bg-brand-red hover:bg-brand-redDark text-white px-3 py-2 rounded-full shadow-lg transition transform hover:scale-105"
           title="Gọi 0988.026.577">
            <i class="fa-solid fa-phone-volume text-xs"></i>
            <span class="text-[11px] font-extrabold">0988.026.577</span>
        </a>

        <!-- Nút Hotline 2 nổi -->
        <a href="tel:0981068333"
           class="flex items-center gap-2 bg-brand-gold hover:bg-amber-600 text-white px-3 py-2 rounded-full shadow-lg transition transform hover:scale-105"
           title="Gọi 0981.068.333">
            <i class="fa-solid fa-phone text-xs"></i>
            <span class="text-[11px] font-extrabold">0981.068.333</span>
        </a>
    </div>

    <!-- =====================================================================
         JAVASCRIPT ĐIỀU KHIỂN SLIDER BANNER TỰ TRƯỢT, MENU ĐT & FORM BÁO GIÁ
    ====================================================================== -->
    <script>
        // 1. Đóng/mở danh mục trên điện thoại
        function toggleMobileMenu() {
            var panel = document.getElementById('mobileMenuPanel');
            if (panel) {
                panel.classList.toggle('hidden');
            }
        }

        // 2. Điều khiển 2 ảnh banner tự trượt chuyên nghiệp
        var currentSlide = 0;
        var slides = document.querySelectorAll('.banner-slide');
        var dots = document.querySelectorAll('.banner-dot');
        var slideInterval = null;

        function showSlide(index) {
            if (!slides.length) return;
            currentSlide = (index + slides.length) % slides.length;
            for (var i = 0; i < slides.length; i++) {
                if (i === currentSlide) {
                    slides[i].classList.remove('hidden');
                    slides[i].classList.add('block');
                } else {
                    slides[i].classList.remove('block');
                    slides[i].classList.add('hidden');
                }
            }
            for (var j = 0; j < dots.length; j++) {
                if (j === currentSlide) {
                    dots[j].classList.remove('bg-white/50');
                    dots[j].classList.add('bg-amber-400');
                } else {
                    dots[j].classList.remove('bg-amber-400');
                    dots[j].classList.add('bg-white/50');
                }
            }
        }

        function changeSlide(step) {
            showSlide(currentSlide + step);
            resetAutoSlide();
        }

        function goToSlide(index) {
            showSlide(index);
            resetAutoSlide();
        }

        function resetAutoSlide() {
            if (slideInterval) clearInterval(slideInterval);
            slideInterval = setInterval(function () {
                showSlide(currentSlide + 1);
            }, 4500);
        }

        // 3. Chọn nhanh sản phẩm/tuyến xe xuống Form Yêu cầu & Báo giá
        function selectServiceToForm(serviceName) {
            var formSection = document.getElementById('form-bao-gia');
            var noteInput = document.getElementById('custNote');
            var nameInput = document.getElementById('custName');
            if (noteInput) {
                noteInput.value = 'Đăng ký: ' + serviceName;
            }
            if (formSection) {
                formSection.scrollIntoView({ behavior: 'smooth' });
            }
            setTimeout(function () {
                if (nameInput) nameInput.focus();
            }, 500);
        }

        // 4. Xử lý thanh tìm kiếm & đặt vé nhanh đầu trang
        function handleQuickSearch(event) {
            event.preventDefault();
            var from = document.getElementById('searchFrom').value;
            var to = document.getElementById('searchTo').value;
            var service = document.getElementById('searchService').value;
            var phone = document.getElementById('searchPhone').value;

            var custPhone = document.getElementById('custPhone');
            var custPickup = document.getElementById('custPickup');
            var custNote = document.getElementById('custNote');

            if (custPhone) custPhone.value = phone;
            if (custPickup) custPickup.value = from + ' → ' + to;
            if (custNote) custNote.value = 'Yêu cầu đặt nhanh: ' + service + ' (' + from + ' đi ' + to + ')';

            var formSection = document.getElementById('form-bao-gia');
            if (formSection) {
                formSection.scrollIntoView({ behavior: 'smooth' });
            }
        }

        // 5. Xử lý gửi Form Yêu cầu & Báo giá trên trang chủ (không dùng alert)
        function handleQuoteSubmit(event) {
            event.preventDefault();
            var name = document.getElementById('custName').value.trim();
            var phone = document.getElementById('custPhone').value.trim();
            var service = document.getElementById('custService').value;
            var qty = document.getElementById('custQty').value.trim();
            var pickup = document.getElementById('custPickup').value.trim();

            var box = document.getElementById('formSuccessBox');
            var text = document.getElementById('formSuccessText');
            if (box && text) {
                text.textContent = 'Cảm ơn ' + name + ' (' + phone + '). Yêu cầu "' + service + '"' +
                    (qty ? ' - Số lượng: ' + qty : '') +
                    (pickup ? ' - Điểm đón: ' + pickup : '') +
                    ' đã được chuyển tới bộ phận điều hành Nhà xe Mạnh La (0988.026.577 - 0981.068.333).';
                box.classList.remove('hidden');
            }
        }

        window.onload = function () {
            resetAutoSlide();
        };
    </script>
</body>
</html>
