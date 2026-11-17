<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=5.0">
    <title>ANCI DESIGN - Công Ty TNHH Tư Vấn Thiết Kế Và Xây Dựng ANCI DESIGN | ancidesign.com</title>
    <meta name="description" content="CÔNG TY TNHH TƯ VẤN THIẾT KẾ VÀ XÂY DỰNG ANCI DESIGN chuyên Thiết kế - Xây dựng - Nội thất Khách sạn, Biệt thự, Căn hộ, Văn phòng, Nhà phố tại Đà Nẵng. Địa chỉ: 44/03 đường K20, Phường Ngũ Hành Sơn, TP Đà Nẵng. Hotline: 0325 012 356 – 0584 168 652.">
    <meta name="keywords" content="ANCI DESIGN, ancidesign.com, thiết kế xây dựng Đà Nẵng, thi công trọn gói Đà Nẵng, xây nhà trọn gói Ngũ Hành Sơn, thiết kế kiến trúc nội thất Đà Nẵng">
    <link rel="canonical" href="https://ancidesign.com/">

    <!-- Open Graph / Thumbnail là ảnh Logo trang web khi gửi link chia sẻ -->
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://ancidesign.com/">
    <meta property="og:site_name" content="ancidesign.com">
    <meta property="og:title" content="CÔNG TY TNHH TƯ VẤN THIẾT KẾ VÀ XÂY DỰNG ANCI DESIGN">
    <meta property="og:description" content="Chuyên Tư vấn Thiết kế Kiến trúc - Thi công Xây dựng - Nội thất trọn gói tại Đà Nẵng. ĐC: 44/03 đường K20, P. Ngũ Hành Sơn, TP Đà Nẵng. ĐT: 0325 012 356 – 0584 168 652.">
    <meta property="og:image" content="https://drive.google.com/thumbnail?id=1bm609vf8SUuBIi5A51uu1jHUwK1eVQY&sz=w800">
    <meta property="og:image:alt" content="Logo Công Ty TNHH Tư Vấn Thiết Kế Và Xây Dựng ANCI DESIGN">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:title" content="CÔNG TY TNHH TƯ VẤN THIẾT KẾ VÀ XÂY DỰNG ANCI DESIGN">
    <meta name="twitter:description" content="Thiết kế Kiến trúc - Thi công Xây dựng - Nội thất chuyên nghiệp tại Đà Nẵng.">
    <meta name="twitter:image" content="https://drive.google.com/thumbnail?id=1bm609vf8SUuBIi5A51uu1jHUwK1eVQY&sz=w800">
    <link rel="icon" href="https://drive.google.com/thumbnail?id=1bm609vf8SUuBIi5A51uu1jHUwK1eVQY&sz=w200" type="image/png">

    <!-- Tailwind CSS & Font Awesome & Google Fonts -->
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">

    <style>
        :root {
            /* Bảng màu đồng bộ theo tông màu thương hiệu & kiến trúc xây dựng */
            --anci-primary: #0f2942;      /* Xanh Navy đậm kiến trúc */
            --anci-secondary: #c59434;    /* Vàng đồng sang trọng theo logo */
            --anci-secondary-dark: #a6781e;
            --anci-light: #f8fafc;
            --anci-border: #e2e8f0;
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        html, body {
            width: 100%;
            max-width: 100%;
            overflow-x: hidden;
            font-family: 'Inter', sans-serif;
            background-color: #ffffff;
            color: #1e293b;
            scroll-behavior: smooth;
        }

        /* Khung giao diện chuẩn Flatsome: rộng 95% trên máy tính, căn giữa tuyệt đối, không lệch phải */
        .flatsome-container {
            width: 95%;
            max-width: 95%;
            margin-left: auto;
            margin-right: auto;
        }

        @media (max-width: 767px) {
            .flatsome-container {
                width: 94%;
                max-width: 94%;
            }
        }

        /* Tối ưu thanh danh mục trên máy tính: chữ nhỏ gọn, nằm trên 1 hàng, không bao giờ tự ngắt chữ trong tên danh mục */
        .desktop-nav-list {
            display: flex;
            flex-wrap: wrap;
            align-items: center;
            justify-content: center;
            gap: 4px 14px;
        }

        .desktop-nav-item {
            white-space: nowrap;
            font-size: 12.5px;
            font-weight: 600;
            text-transform: uppercase;
            letter-spacing: 0.01em;
            color: var(--anci-primary);
            padding: 6px 4px;
            transition: color 0.2s ease, border-color 0.2s ease;
            border-bottom: 2px solid transparent;
            display: inline-flex;
            align-items: center;
            gap: 4px;
        }

        .desktop-nav-item:hover,
        .desktop-nav-item.active {
            color: var(--anci-secondary);
            border-bottom-color: var(--anci-secondary);
        }

        /* Dropdown menu chuẩn Flatsome */
        .nav-dropdown-wrap {
            position: relative;
        }

        .nav-dropdown-menu {
            display: none;
            position: absolute;
            top: 100%;
            left: 0;
            min-width: 220px;
            background: #ffffff;
            border: 1px solid #e2e8f0;
            box-shadow: 0 10px 25px rgba(15, 41, 66, 0.12);
            border-radius: 6px;
            padding: 6px 0;
            z-index: 100;
        }

        .nav-dropdown-wrap:hover .nav-dropdown-menu {
            display: block;
        }

        .nav-dropdown-link {
            display: block;
            padding: 8px 14px;
            font-size: 12.5px;
            font-weight: 500;
            color: #334155;
            white-space: nowrap;
            transition: all 0.15s ease;
        }

        .nav-dropdown-link:hover {
            background-color: #f8fafc;
            color: var(--anci-secondary);
            padding-left: 18px;
        }

        /* Nút danh mục lọc ở trang chủ nhỏ gọn, viết liền trên 1 hàng */
        .category-pill {
            white-space: nowrap;
            font-size: 12px;
            font-weight: 600;
            padding: 6px 12px;
            border-radius: 6px;
            border: 1px solid #cbd5e1;
            background: #ffffff;
            color: #334155;
            transition: all 0.2s ease;
            cursor: pointer;
            text-align: center;
        }

        .category-pill:hover,
        .category-pill.active {
            background: var(--anci-primary);
            color: #ffffff;
            border-color: var(--anci-primary);
        }

        /* 2 Banner tự trượt kích thước bằng nhau tuyệt đối trên cả máy tính và điện thoại */
        .hero-slider-wrapper {
            position: relative;
            width: 100%;
            height: 430px;
            overflow: hidden;
            border-radius: 10px;
            background-color: var(--anci-primary);
        }

        @media (max-width: 767px) {
            .hero-slider-wrapper {
                height: 360px;
            }
        }

        .hero-slide {
            position: absolute;
            inset: 0;
            width: 100%;
            height: 100%;
            opacity: 0;
            visibility: hidden;
            transition: opacity 0.7s ease-in-out, visibility 0.7s ease-in-out;
            display: flex;
            align-items: center;
            justify-content: center;
        }

        .hero-slide.active {
            opacity: 1;
            visibility: visible;
            z-index: 10;
        }

        /* Tiêu đề section kiểu Flatsome (Section Title) */
        .flatsome-section-title {
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 14px;
            margin-bottom: 10px;
        }

        .flatsome-section-title::before,
        .flatsome-section-title::after {
            content: "";
            flex: 1;
            max-width: 120px;
            height: 2px;
            background: linear-gradient(90deg, transparent, var(--anci-secondary), transparent);
        }

        /* Box sản phẩm / công trình chuẩn Flatsome: ảnh đồng nhất, tên hiển thị đầy đủ không cắt chữ */
        .flatsome-box {
            background: #ffffff;
            border: 1px solid #e2e8f0;
            border-radius: 8px;
            overflow: hidden;
            transition: transform 0.25s ease, box-shadow 0.25s ease;
            display: flex;
            flex-direction: column;
            height: 100%;
        }

        .flatsome-box:hover {
            transform: translateY(-3px);
            box-shadow: 0 10px 24px rgba(15, 41, 66, 0.1);
            border-color: var(--anci-secondary);
        }

        .flatsome-box-image {
            position: relative;
            width: 100%;
            aspect-ratio: 4 / 3;
            overflow: hidden;
            background-color: #f1f5f9;
        }

        .flatsome-box-image img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            transition: transform 0.4s ease;
        }

        .flatsome-box:hover .flatsome-box-image img {
            transform: scale(1.05);
        }

        .flatsome-box-text {
            padding: 10px 10px 12px;
            text-align: center;
            flex: 1;
            display: flex;
            flex-direction: column;
            justify-content: space-between;
        }

        /* Đảm bảo tên sản phẩm / công trình không bị tràn hoặc thiếu chữ trên điện thoại 2 cột */
        .product-title-full {
            font-size: 13.5px;
            font-weight: 700;
            line-height: 1.4;
            color: var(--anci-primary);
            word-break: break-word;
            overflow-wrap: break-word;
            white-space: normal;
            margin-bottom: 4px;
        }

        @media (max-width: 640px) {
            .product-title-full {
                font-size: 12px;
                line-height: 1.35;
            }
        }

        /* Nút liên hệ nổi bật Zalo, Facebook, Hotline */
        .floating-contact-bar {
            position: fixed;
            bottom: 18px;
            left: 14px;
            z-index: 90;
            display: flex;
            flex-direction: column;
            gap: 10px;
        }

        .floating-btn {
            display: inline-flex;
            align-items: center;
            gap: 8px;
            padding: 8px 14px 8px 10px;
            border-radius: 9999px;
            color: #ffffff;
            font-size: 12.5px;
            font-weight: 700;
            box-shadow: 0 6px 16px rgba(0, 0, 0, 0.22);
            transition: transform 0.2s ease;
            text-decoration: none;
        }

        .floating-btn:hover {
            transform: scale(1.04);
        }

        @media (max-width: 640px) {
            .floating-contact-bar {
                bottom: 12px;
                left: 10px;
                gap: 8px;
            }
            .floating-btn {
                padding: 7px 11px 7px 8px;
                font-size: 11.5px;
            }
        }
    </style>
</head>
<body>

    <!-- ==========================================
         TOP BAR CHUẨN FLATSOME (ĐỊA CHỈ & HOTLINE)
         ========================================== -->
    <div class="bg-[#0f2942] text-white text-xs py-2 border-b border-slate-700">
        <div class="flatsome-container flex flex-wrap items-center justify-between gap-2">
            <div class="flex flex-wrap items-center gap-3 md:gap-5">
                <span class="inline-flex items-center gap-1.5">
                    <i class="fa-solid fa-location-dot text-[#c59434]"></i>
                    <span>44/03 đường K20, Phường Ngũ Hành Sơn, TP Đà Nẵng</span>
                </span>
                <span class="hidden lg:inline-flex items-center gap-1.5">
                    <i class="fa-solid fa-globe text-[#c59434]"></i>
                    <span>ancidesign.com</span>
                </span>
            </div>
            <div class="flex items-center gap-3 md:gap-5 font-medium">
                <a href="tel:0325012356" class="hover:text-[#c59434] transition">
                    <i class="fa-solid fa-phone-volume text-[#c59434] mr-1"></i>0325 012 356 – 0584 168 652
                </a>
                <a href="https://www.facebook.com/Ancidesignandbuilding" target="_blank" rel="noopener noreferrer" class="hover:text-[#c59434] transition inline-flex items-center gap-1">
                    <i class="fa-brands fa-facebook"></i>
                    <span class="hidden sm:inline">Fanpage ANCI Design</span>
                </a>
            </div>
        </div>
    </div>

    <!-- ==========================================
         HEADER CHÍNH (LOGO NHỎ GỌN, MENU 1 HÀNG, KHÔNG CÓ NÚT GỌI NGAY ĐỂ TRÁNH TRÀN VIỀN)
         ========================================== -->
    <header class="sticky top-0 z-50 bg-white/95 backdrop-blur border-b border-slate-200 shadow-sm">
        <div class="flatsome-container py-2.5 flex items-center justify-between gap-3">
            <!-- Logo chỉnh gọn nhỏ lại -->
            <a href="#trang-chu" class="flex items-center gap-2.5 shrink-0 group">
                <div class="w-11 h-11 md:w-12 md:h-12 rounded-lg border border-slate-200 bg-white p-1 flex items-center justify-center overflow-hidden shadow-xs shrink-0">
                    <img id="site-logo-img"
                         src="https://drive.google.com/thumbnail?id=1bm609vf8SUuBIi5A51uu1jHUwK1eVQY&sz=w400"
                         data-drive-id="1bm609vf8SUuBIi5A51uu1jHUwK1eVQY"
                         alt="Logo ANCI DESIGN"
                         class="w-full h-full object-contain"
                         onerror="handleLogoFallback(this)">
                </div>
                <div class="leading-tight">
                    <span class="block text-sm md:text-base font-extrabold tracking-tight text-[#0f2942] group-hover:text-[#c59434] transition">ANCI DESIGN</span>
                    <span class="block text-[10px] md:text-[11px] font-semibold text-[#c59434] uppercase tracking-wider">Tư Vấn Thiết Kế & Xây Dựng</span>
                </div>
            </a>

            <!-- Danh mục trên máy tính: chữ nhỏ gọn, viết liền trên 1 hàng, không xuống dòng từng từ -->
            <nav class="hidden lg:block flex-1 px-2" aria-label="Menu chính">
                <ul class="desktop-nav-list">
                    <li><a href="#trang-chu" class="desktop-nav-item active">Trang chủ</a></li>
                    <li><a href="#gioi-thieu" class="desktop-nav-item">Giới thiệu</a></li>
                    <li class="nav-dropdown-wrap">
                        <a href="#cong-trinh-thuc-te" class="desktop-nav-item">
                            <span>Công trình thực tế</span>
                            <i class="fa-solid fa-chevron-down text-[9px]"></i>
                        </a>
                        <div class="nav-dropdown-menu">
                            <a href="#cong-trinh-thuc-te" onclick="filterConstruction('khach-san-can-ho')" class="nav-dropdown-link">Khách sạn – Căn hộ – Phòng trọ</a>
                            <a href="#cong-trinh-thuc-te" onclick="filterConstruction('biet-thu')" class="nav-dropdown-link">Biệt thự</a>
                            <a href="#cong-trinh-thuc-te" onclick="filterConstruction('nha-pho')" class="nav-dropdown-link">Nhà phố</a>
                            <a href="#cong-trinh-thuc-te" onclick="filterConstruction('van-phong')" class="nav-dropdown-link">Văn phòng</a>
                        </div>
                    </li>
                    <li><a href="#du-an-da-nang" class="desktop-nav-item">Dự án tại Đà Nẵng</a></li>
                    <li class="nav-dropdown-wrap">
                        <a href="#linh-vuc-hoat-dong" class="desktop-nav-item">
                            <span>Lĩnh vực hoạt động</span>
                            <i class="fa-solid fa-chevron-down text-[9px]"></i>
                        </a>
                        <div class="nav-dropdown-menu">
                            <a href="#linh-vuc-hoat-dong" class="nav-dropdown-link">Thiết kế Kiến trúc – Nội thất</a>
                            <a href="#linh-vuc-hoat-dong" class="nav-dropdown-link">Thi công phần thô</a>
                            <a href="#linh-vuc-hoat-dong" class="nav-dropdown-link">Thi công hoàn thiện</a>
                            <a href="#linh-vuc-hoat-dong" class="nav-dropdown-link">Thi công nội thất</a>
                        </div>
                    </li>
                    <li class="nav-dropdown-wrap">
                        <a href="#danh-muc-san-pham" class="desktop-nav-item">
                            <span>Mẫu thiết kế & Sản phẩm</span>
                            <i class="fa-solid fa-chevron-down text-[9px]"></i>
                        </a>
                        <div class="nav-dropdown-menu">
                            <a href="#danh-muc-san-pham" class="nav-dropdown-link">Mẫu thiết kế nhà phố</a>
                            <a href="#danh-muc-san-pham" class="nav-dropdown-link">Mẫu thiết kế biệt thự</a>
                            <a href="#danh-muc-san-pham" class="nav-dropdown-link">Mẫu thiết kế nội thất</a>
                        </div>
                    </li>
                    <li class="nav-dropdown-wrap">
                        <a href="#bang-bao-gia" class="desktop-nav-item">
                            <span>Báo giá</span>
                            <i class="fa-solid fa-chevron-down text-[9px]"></i>
                        </a>
                        <div class="nav-dropdown-menu">
                            <a href="#bang-bao-gia" class="nav-dropdown-link">Báo giá thiết kế kiến trúc</a>
                            <a href="#bang-bao-gia" class="nav-dropdown-link">Báo giá thi công phần thô</a>
                            <a href="#bang-bao-gia" class="nav-dropdown-link">Báo giá thi công hoàn thiện</a>
                            <a href="#bang-bao-gia" class="nav-dropdown-link">Báo giá thi công trọn gói</a>
                        </div>
                    </li>
                    <li><a href="#doi-tac" class="desktop-nav-item">Đối tác</a></li>
                    <li><a href="#tin-tuc" class="desktop-nav-item">Tin tức</a></li>
                    <li><a href="#lien-he" class="desktop-nav-item">Liên hệ</a></li>
                </ul>
            </nav>

            <!-- Nút mở Menu trên Điện thoại (Không để nút gọi ngay trên Header để tránh tràn viền) -->
            <button id="mobile-menu-toggle"
                    type="button"
                    aria-label="Mở danh mục"
                    class="lg:hidden inline-flex items-center gap-1.5 px-3 py-2 rounded-lg border border-slate-300 text-[#0f2942] text-xs font-bold hover:bg-slate-100">
                <i class="fa-solid fa-bars text-sm"></i>
                <span>DANH MỤC</span>
            </button>
        </div>

        <!-- Menu Danh mục trên Điện thoại (Chia bố cục gọn đẹp, dễ bấm) -->
        <div id="mobile-menu-drawer" class="hidden lg:hidden bg-white border-t border-slate-200 shadow-lg">
            <div class="flatsome-container py-3">
                <div class="grid grid-cols-2 gap-2">
                    <a href="#trang-chu" class="mobile-nav-link px-3 py-2 rounded-md bg-slate-50 text-xs font-semibold text-[#0f2942] hover:bg-[#0f2942] hover:text-white transition">Trang chủ</a>
                    <a href="#gioi-thieu" class="mobile-nav-link px-3 py-2 rounded-md bg-slate-50 text-xs font-semibold text-[#0f2942] hover:bg-[#0f2942] hover:text-white transition">Giới thiệu</a>
                    <a href="#cong-trinh-thuc-te" class="mobile-nav-link px-3 py-2 rounded-md bg-slate-50 text-xs font-semibold text-[#0f2942] hover:bg-[#0f2942] hover:text-white transition">Công trình thực tế</a>
                    <a href="#du-an-da-nang" class="mobile-nav-link px-3 py-2 rounded-md bg-slate-50 text-xs font-semibold text-[#0f2942] hover:bg-[#0f2942] hover:text-white transition">Dự án tại Đà Nẵng</a>
                    <a href="#linh-vuc-hoat-dong" class="mobile-nav-link px-3 py-2 rounded-md bg-slate-50 text-xs font-semibold text-[#0f2942] hover:bg-[#0f2942] hover:text-white transition">Lĩnh vực hoạt động</a>
                    <a href="#danh-muc-san-pham" class="mobile-nav-link px-3 py-2 rounded-md bg-slate-50 text-xs font-semibold text-[#0f2942] hover:bg-[#0f2942] hover:text-white transition">Mẫu thiết kế</a>
                    <a href="#bang-bao-gia" class="mobile-nav-link px-3 py-2 rounded-md bg-slate-50 text-xs font-semibold text-[#0f2942] hover:bg-[#0f2942] hover:text-white transition">Bảng báo giá</a>
                    <a href="#form-bao-gia" class="mobile-nav-link px-3 py-2 rounded-md bg-slate-50 text-xs font-semibold text-[#0f2942] hover:bg-[#0f2942] hover:text-white transition">Yêu cầu tư vấn</a>
                    <a href="#doi-tac" class="mobile-nav-link px-3 py-2 rounded-md bg-slate-50 text-xs font-semibold text-[#0f2942] hover:bg-[#0f2942] hover:text-white transition">Đối tác</a>
                    <a href="#tin-tuc" class="mobile-nav-link px-3 py-2 rounded-md bg-slate-50 text-xs font-semibold text-[#0f2942] hover:bg-[#0f2942] hover:text-white transition">Tin tức xây dựng</a>
                </div>
            </div>
        </div>
    </header>

    <!-- ==========================================
         SECTION 1: 2 ẢNH BANNER TỰ TRƯỢT KÍCH THƯỚC BẰNG NHAU
         (Hình ảnh và chữ nằm gọn bên trong, cách xa viền, không mất chữ trên ĐT & Máy tính)
         ========================================== -->
    <section id="trang-chu" class="py-3 md:py-4">
        <div class="flatsome-container">
            <div class="hero-slider-wrapper shadow-md">
                <!-- SLIDE 1 -->
                <div class="hero-slide active" data-slide="0">
                    <img src="https://drive.google.com/thumbnail?id=157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT&sz=w1600"
                         data-drive-id="157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT"
                         data-fallback="https://images.unsplash.com/photo-1600585154340-be6161a56a0c?auto=format&fit=crop&w=1600&q=80"
                         alt="Banner Thiết Kế Kiến Trúc & Thi Công Trọn Gói ANCI DESIGN"
                         class="absolute inset-0 w-full h-full object-cover"
                         onerror="handleDriveImgError(this)">
                    <div class="absolute inset-0 bg-gradient-to-r from-[#0f2942]/90 via-[#0f2942]/75 to-[#0f2942]/55"></div>

                    <!-- Khung nội dung cách xa viền ảnh banner (px-8 sm:px-14 md:px-24) để không bao giờ bị cắt chữ -->
                    <div class="relative z-10 w-full h-full flex items-center justify-center px-8 sm:px-14 md:px-24 py-6">
                        <div class="max-w-3xl text-center text-white">
                            <p class="text-[11px] sm:text-xs md:text-sm font-bold uppercase tracking-widest text-[#eab308] mb-2">
                                CÔNG TY TNHH TƯ VẤN THIẾT KẾ VÀ XÂY DỰNG ANCI DESIGN
                            </p>
                            <h1 class="text-lg sm:text-2xl md:text-4xl font-extrabold leading-snug mb-3">
                                THIẾT KẾ KIẾN TRÚC – THI CÔNG XÂY DỰNG – NỘI THẤT TRỌN GÓI TẠI ĐÀ NẴNG
                            </h1>
                            <p class="text-xs sm:text-sm md:text-base text-slate-200 leading-relaxed mb-5 max-w-2xl mx-auto">
                                Chuyên thiết kế và thi công Khách sạn, Biệt thự, Căn hộ, Văn phòng, Nhà phố chuẩn kỹ thuật – Tối ưu công năng – Cam kết tiến độ & chất lượng bền vững.
                            </p>
                            <div class="flex flex-wrap items-center justify-center gap-2.5 sm:gap-4">
                                <a href="#form-bao-gia" class="px-4 sm:px-6 py-2.5 rounded-lg bg-[#c59434] hover:bg-[#a6781e] text-white text-xs sm:text-sm font-bold transition shadow">
                                    NHẬN BÁO GIÁ MIỄN PHÍ
                                </a>
                                <a href="#cong-trinh-thuc-te" class="px-4 sm:px-6 py-2.5 rounded-lg bg-white/15 hover:bg-white/25 border border-white/40 text-white text-xs sm:text-sm font-semibold transition">
                                    XEM CÔNG TRÌNH THỰC TẾ
                                </a>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- SLIDE 2 (Kích thước bằng nhau 100%) -->
                <div class="hero-slide" data-slide="1">
                    <img src="https://drive.google.com/thumbnail?id=1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff&sz=w1600"
                         data-drive-id="1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff"
                         data-fallback="https://images.unsplash.com/photo-1600607687939-ce8a6c25118c?auto=format&fit=crop&w=1600&q=80"
                         alt="Banner Xây Nhà Trọn Gói Chìa Khóa Trao Tay ANCI DESIGN"
                         class="absolute inset-0 w-full h-full object-cover"
                         onerror="handleDriveImgError(this)">
                    <div class="absolute inset-0 bg-gradient-to-r from-[#0f2942]/90 via-[#0f2942]/75 to-[#0f2942]/55"></div>

                    <!-- Khung nội dung cách xa viền ảnh banner (px-8 sm:px-14 md:px-24) -->
                    <div class="relative z-10 w-full h-full flex items-center justify-center px-8 sm:px-14 md:px-24 py-6">
                        <div class="max-w-3xl text-center text-white">
                            <p class="text-[11px] sm:text-xs md:text-sm font-bold uppercase tracking-widest text-[#eab308] mb-2">
                                GIẢI PHÁP XÂY NHÀ TRỌN GÓI CHÌA KHÓA TRAO TAY – ANCIDESIGN.COM
                            </p>
                            <h2 class="text-lg sm:text-2xl md:text-4xl font-extrabold leading-snug mb-3">
                                UY TÍN TỪ TÂM – NÂNG TẦM KHÔNG GIAN SỐNG HIỆN ĐẠI & ĐẲNG CẤP
                            </h2>
                            <p class="text-xs sm:text-sm md:text-base text-slate-200 leading-relaxed mb-5 max-w-2xl mx-auto">
                                Địa chỉ: 44/03 đường K20, Phường Ngũ Hành Sơn, TP Đà Nẵng | Hotline tư vấn 24/7: 0325 012 356 – 0584 168 652.
                            </p>
                            <div class="flex flex-wrap items-center justify-center gap-2.5 sm:gap-4">
                                <a href="#du-an-da-nang" class="px-4 sm:px-6 py-2.5 rounded-lg bg-[#c59434] hover:bg-[#a6781e] text-white text-xs sm:text-sm font-bold transition shadow">
                                    DỰ ÁN TẠI ĐÀ NẴNG
                                </a>
                                <a href="#lien-he" class="px-4 sm:px-6 py-2.5 rounded-lg bg-white/15 hover:bg-white/25 border border-white/40 text-white text-xs sm:text-sm font-semibold transition">
                                    LIÊN HỆ TƯ VẤN NGAY
                                </a>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Nút điều hướng qua lại nằm gọn trong Banner -->
                <button type="button" onclick="changeSlide(-1)" aria-label="Slide trước"
                        class="absolute left-2 sm:left-4 top-1/2 -translate-y-1/2 z-20 w-8 h-8 sm:w-10 sm:h-10 rounded-full bg-black/35 hover:bg-[#c59434] text-white flex items-center justify-center transition">
                    <i class="fa-solid fa-chevron-left text-xs sm:text-sm"></i>
                </button>
                <button type="button" onclick="changeSlide(1)" aria-label="Slide tiếp theo"
                        class="absolute right-2 sm:right-4 top-1/2 -translate-y-1/2 z-20 w-8 h-8 sm:w-10 sm:h-10 rounded-full bg-black/35 hover:bg-[#c59434] text-white flex items-center justify-center transition">
                    <i class="fa-solid fa-chevron-right text-xs sm:text-sm"></i>
                </button>

                <!-- Chấm chỉ báo Slide -->
                <div class="absolute bottom-3 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2">
                    <button type="button" onclick="goToSlide(0)" class="slide-dot w-6 h-2 rounded-full bg-[#c59434] transition-all" aria-label="Banner 1"></button>
                    <button type="button" onclick="goToSlide(1)" class="slide-dot w-2.5 h-2 rounded-full bg-white/60 transition-all" aria-label="Banner 2"></button>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         SECTION 2: DỊCH VỤ TIÊU BIỂU & LĨNH VỰC HOẠT ĐỘNG (GIỐNG WEB MẪU TINTRUONGTHINH.COM)
         ========================================== -->
    <section id="linh-vuc-hoat-dong" class="py-8 bg-slate-50 border-y border-slate-200">
        <div class="flatsome-container">
            <div class="text-center mb-6">
                <div class="flatsome-section-title">
                    <h2 class="text-lg md:text-2xl font-extrabold text-[#0f2942] uppercase">Dịch Vụ Tiêu Biểu & Lĩnh Vực Hoạt Động</h2>
                </div>
                <p class="text-xs md:text-sm text-slate-600">Giải pháp toàn diện từ Tư vấn Thiết kế Kiến trúc – Thi công Xây dựng đến Hoàn thiện Nội thất</p>
            </div>

            <!-- Thanh danh mục dịch vụ nhỏ gọn trên máy tính & điện thoại -->
            <div class="flex flex-wrap items-center justify-center gap-2 mb-6">
                <a href="#cong-trinh-thuc-te" class="category-pill active">Thiết kế Kiến trúc – Nội thất</a>
                <a href="#cong-trinh-thuc-te" class="category-pill">Thi công phần thô</a>
                <a href="#cong-trinh-thuc-te" class="category-pill">Thi công hoàn thiện</a>
                <a href="#cong-trinh-thuc-te" class="category-pill">Thi công nội thất</a>
                <a href="#bang-bao-gia" class="category-pill">Xây nhà trọn gói</a>
            </div>

            <!-- 4 Lĩnh vực chủ lực: 2 cột trên điện thoại, 4 cột trên máy tính -->
            <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 md:gap-5">
                <div class="flatsome-box p-4 text-center">
                    <div class="w-12 h-12 mx-auto mb-3 rounded-full bg-[#0f2942] text-[#c59434] flex items-center justify-center text-lg">
                        <i class="fa-solid fa-compass-drafting"></i>
                    </div>
                    <h3 class="product-title-full uppercase">Thiết Kế Kiến Trúc – Nội Thất</h3>
                    <p class="text-xs text-slate-600 mt-1 leading-relaxed">
                        Bố trí công năng khoa học, chuẩn phong thủy, bản vẽ phối cảnh 3D sáng tạo cho Nhà phố, Biệt thự, Khách sạn, Căn hộ.
                    </p>
                </div>

                <div class="flatsome-box p-4 text-center">
                    <div class="w-12 h-12 mx-auto mb-3 rounded-full bg-[#0f2942] text-[#c59434] flex items-center justify-center text-lg">
                        <i class="fa-solid fa-trowel-bricks"></i>
                    </div>
                    <h3 class="product-title-full uppercase">Thi Công Phần Thô</h3>
                    <p class="text-xs text-slate-600 mt-1 leading-relaxed">
                        Kết cấu móng, cột, dầm, sàn bê tông cốt thép chuẩn kỹ thuật xây dựng, vật tư chính hãng, giám sát chặt chẽ từng hạng mục.
                    </p>
                </div>

                <div class="flatsome-box p-4 text-center">
                    <div class="w-12 h-12 mx-auto mb-3 rounded-full bg-[#0f2942] text-[#c59434] flex items-center justify-center text-lg">
                        <i class="fa-solid fa-paint-roller"></i>
                    </div>
                    <h3 class="product-title-full uppercase">Thi Công Hoàn Thiện</h3>
                    <p class="text-xs text-slate-600 mt-1 leading-relaxed">
                        Ốp lát, sơn bả, trần thạch cao, hệ thống điện nước M&E, cửa nhôm kính Xingfa và mặt tiền sắc nét theo đúng hồ sơ thiết kế.
                    </p>
                </div>

                <div class="flatsome-box p-4 text-center">
                    <div class="w-12 h-12 mx-auto mb-3 rounded-full bg-[#0f2942] text-[#c59434] flex items-center justify-center text-lg">
                        <i class="fa-solid fa-couch"></i>
                    </div>
                    <h3 class="product-title-full uppercase">Thi Công Nội Thất Trọn Gói</h3>
                    <p class="text-xs text-slate-600 mt-1 leading-relaxed">
                        Sản xuất và lắp đặt nội thất gỗ công nghiệp An Cường, gỗ tự nhiên cao cấp cho Phòng khách, Bếp, Phòng ngủ, Văn phòng.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         SECTION 3: GIỚI THIỆU CÔNG TY & 6 THẾ MẠNH CỦA ANCI DESIGN (MẪU TINTRUONGTHINH.COM)
         ========================================== -->
    <section id="gioi-thieu" class="py-10 bg-white">
        <div class="flatsome-container">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-center mb-10">
                <div class="lg:col-span-7">
                    <p class="text-xs font-bold uppercase tracking-wider text-[#c59434] mb-1">Về chúng tôi – ancidesign.com</p>
                    <h2 class="text-lg md:text-2xl font-extrabold text-[#0f2942] mb-3">
                        CÔNG TY TNHH TƯ VẤN THIẾT KẾ VÀ XÂY DỰNG ANCI DESIGN
                    </h2>
                    <p class="text-xs md:text-sm text-slate-700 leading-relaxed mb-3">
                        <strong>ANCI DESIGN</strong> chuyên <strong>Thiết kế – Xây dựng – Nội thất</strong> các công trình Khách sạn, Biệt thự, Căn hộ, Văn phòng, Nhà phố tại thành phố Đà Nẵng và khu vực miền Trung. Với tiêu chí <em>“Nhà ở Gia đình – Tiêu chuẩn Công trình”</em>, chúng tôi luôn mang đến trải nghiệm dịch vụ tận tâm, minh bạch và chuyên nghiệp cho Quý Khách hàng.
                    </p>
                    <p class="text-xs md:text-sm text-slate-700 leading-relaxed mb-4">
                        Đặt chữ <strong>“TÂM”</strong> và chữ <strong>“TÍN”</strong> lên hàng đầu để mỗi công trình luôn đạt tiêu chuẩn: <strong>AN TOÀN – CHẤT LƯỢNG – ĐÚNG TIẾN ĐỘ – TỐI ƯU CHI PHÍ</strong>.
                    </p>
                    <div class="grid grid-cols-2 sm:grid-cols-3 gap-3 text-xs bg-slate-50 p-3.5 rounded-lg border border-slate-200">
                        <div>
                            <span class="block text-slate-500">Mã số thuế:</span>
                            <strong class="text-[#0f2942]">0402288042</strong>
                        </div>
                        <div>
                            <span class="block text-slate-500">Hotline tư vấn:</span>
                            <strong class="text-[#0f2942]">0325 012 356 – 0584 168 652</strong>
                        </div>
                        <div class="col-span-2 sm:col-span-1">
                            <span class="block text-slate-500">Trụ sở Đà Nẵng:</span>
                            <strong class="text-[#0f2942]">44/03 đường K20, P. Ngũ Hành Sơn</strong>
                        </div>
                    </div>
                </div>
                <div class="lg:col-span-5">
                    <div class="flatsome-box overflow-hidden">
                        <div class="flatsome-box-image">
                            <img src="https://drive.google.com/thumbnail?id=1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz&sz=w1000"
                                 data-drive-id="1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz"
                                 data-fallback="https://images.unsplash.com/photo-1600596542815-ffad4c1539a9?auto=format&fit=crop&w=1000&q=80"
                                 alt="Công trình tiêu biểu Công ty TNHH Tư vấn Thiết kế và Xây dựng ANCI DESIGN"
                                 onerror="handleDriveImgError(this)">
                        </div>
                        <div class="p-3 bg-[#0f2942] text-white text-center text-xs font-semibold">
                            CÔNG TY TNHH TƯ VẤN THIẾT KẾ VÀ XÂY DỰNG ANCI DESIGN – ĐÀ NẴNG
                        </div>
                    </div>
                </div>
            </div>

            <!-- 6 Thế mạnh của chúng tôi (Giống cấu trúc web mẫu tintruongthinh.com) -->
            <div class="text-center mb-6">
                <div class="flatsome-section-title">
                    <h3 class="text-base md:text-xl font-extrabold text-[#0f2942] uppercase">Thế Mạnh Của Chúng Tôi</h3>
                </div>
            </div>
            <div class="grid grid-cols-2 lg:grid-cols-3 gap-3 md:gap-5">
                <div class="flatsome-box p-4">
                    <div class="flex items-center gap-2.5 mb-2">
                        <i class="fa-solid fa-user-tie text-[#c59434] text-lg"></i>
                        <h4 class="product-title-full m-0">Đội ngũ KTS, Kỹ sư chuyên nghiệp</h4>
                    </div>
                    <p class="text-xs text-slate-600 leading-relaxed">Kiến trúc sư sáng tạo cùng đội ngũ kỹ sư chỉ huy công trường giàu kinh nghiệm và thợ lành nghề.</p>
                </div>
                <div class="flatsome-box p-4">
                    <div class="flex items-center gap-2.5 mb-2">
                        <i class="fa-solid fa-layer-group text-[#c59434] text-lg"></i>
                        <h4 class="product-title-full m-0">Cập nhật xu hướng mới hiện đại</h4>
                    </div>
                    <p class="text-xs text-slate-600 leading-relaxed">Ứng dụng giải pháp không gian xanh, thông tầng lấy sáng tự nhiên và vật liệu xây dựng hiện đại.</p>
                </div>
                <div class="flatsome-box p-4">
                    <div class="flex items-center gap-2.5 mb-2">
                        <i class="fa-solid fa-clipboard-check text-[#c59434] text-lg"></i>
                        <h4 class="product-title-full m-0">Giám sát tiến độ chuẩn xác</h4>
                    </div>
                    <p class="text-xs text-slate-600 leading-relaxed">Báo cáo hình ảnh thi công thực tế hàng ngày giúp Chủ đầu tư dễ dàng theo dõi tiến độ từ xa.</p>
                </div>
                <div class="flatsome-box p-4">
                    <div class="flex items-center gap-2.5 mb-2">
                        <i class="fa-solid fa-shield-halved text-[#c59434] text-lg"></i>
                        <h4 class="product-title-full m-0">Bảo hành công trình lâu dài</h4>
                    </div>
                    <p class="text-xs text-slate-600 leading-relaxed">Chế độ bảo hành kết cấu và chống thấm dài hạn, hỗ trợ nhanh chóng với tinh thần trách nhiệm cao.</p>
                </div>
                <div class="flatsome-box p-4">
                    <div class="flex items-center gap-2.5 mb-2">
                        <i class="fa-solid fa-coins text-[#c59434] text-lg"></i>
                        <h4 class="product-title-full m-0">Chi phí hợp lý – Minh bạch</h4>
                    </div>
                    <p class="text-xs text-slate-600 leading-relaxed">Bóc tách dự toán chi tiết từng hạng mục vật tư, cam kết không phát sinh chi phí ngoài hợp đồng.</p>
                </div>
                <div class="flatsome-box p-4">
                    <div class="flex items-center gap-2.5 mb-2">
                        <i class="fa-solid fa-headset text-[#c59434] text-lg"></i>
                        <h4 class="product-title-full m-0">Hỗ trợ tư vấn miễn phí 24/7</h4>
                    </div>
                    <p class="text-xs text-slate-600 leading-relaxed">Khảo sát thực tế tại Đà Nẵng, tư vấn phương án thiết kế và thủ tục xin phép xây dựng tận tình.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         SECTION 4: HÌNH ẢNH THỰC TẾ THI CÔNG XÂY DỰNG (9 FILE GOOGLE DRIVE ĐƯỢC ĐƯA VÀO ĐÚNG DANH MỤC & TÊN SẢN PHẨM)
         - Điện thoại: 2 cột (grid-cols-2)
         - Máy tính: 3 cột (lg:grid-cols-3)
         - Không để nhãn dán đè lên ảnh trang chủ
         - Tên sản phẩm hiển thị đầy đủ, không tràn viền
         ========================================== -->
    <section id="cong-trinh-thuc-te" class="py-10 bg-slate-50 border-t border-slate-200">
        <div class="flatsome-container">
            <div class="text-center mb-5">
                <div class="flatsome-section-title">
                    <h2 class="text-lg md:text-2xl font-extrabold text-[#0f2942] uppercase">Công Trình Thực Tế Thi Công Xây Dựng</h2>
                </div>
                <p class="text-xs md:text-sm text-slate-600">Hình ảnh thực tế thi công phần thô, kết cấu và hoàn thiện công trình của ANCI DESIGN</p>
            </div>

            <!-- Danh mục lọc Công trình thực tế (Chữ nhỏ gọn, viết liền trên 1 hàng, không ngắt dòng tên danh mục) -->
            <div class="flex flex-wrap items-center justify-center gap-1.5 sm:gap-2 mb-6">
                <button type="button" onclick="filterConstruction('all')" data-filter="all" class="cons-filter-btn category-pill active">Tất cả</button>
                <button type="button" onclick="filterConstruction('khach-san-can-ho')" data-filter="khach-san-can-ho" class="cons-filter-btn category-pill">Khách sạn – Căn hộ – Phòng trọ</button>
                <button type="button" onclick="filterConstruction('biet-thu')" data-filter="biet-thu" class="cons-filter-btn category-pill">Biệt thự</button>
                <button type="button" onclick="filterConstruction('nha-pho')" data-filter="nha-pho" class="cons-filter-btn category-pill">Nhà phố</button>
                <button type="button" onclick="filterConstruction('van-phong')" data-filter="van-phong" class="cons-filter-btn category-pill">Văn phòng</button>
            </div>

            <!-- Grid 9 ảnh thực tế thi công xây dựng: 2 cột trên điện thoại, 3 cột trên máy tính -->
            <div id="construction-grid" class="grid grid-cols-2 lg:grid-cols-3 gap-3 md:gap-5">
                <!-- Ảnh thực tế 1: 13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz -->
                <article class="flatsome-box cons-item" data-category="nha-pho">
                    <div class="flatsome-box-image">
                        <img src="https://drive.google.com/thumbnail?id=13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz&sz=w1000"
                             data-drive-id="13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz"
                             data-fallback="https://images.unsplash.com/photo-1541888946425-d09bb18086f6?auto=format&fit=crop&w=900&q=80"
                             alt="Thi công phần thô và kết cấu móng nhà phố hiện đại 3 tầng"
                             onerror="handleDriveImgError(this)">
                    </div>
                    <div class="flatsome-box-text">
                        <div>
                            <h3 class="product-title-full">Thi Công Phần Thô & Kết Cấu Nhà Phố 3 Tầng – Ngũ Hành Sơn</h3>
                            <p class="text-[11px] text-slate-500">Danh mục: Nhà phố – Thi công phần thô</p>
                        </div>
                    </div>
                </article>

                <!-- Ảnh thực tế 2: 1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR -->
                <article class="flatsome-box cons-item" data-category="khach-san-can-ho">
                    <div class="flatsome-box-image">
                        <img src="https://drive.google.com/thumbnail?id=1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR&sz=w1000"
                             data-drive-id="1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR"
                             data-fallback="https://images.unsplash.com/photo-1503387762-592deb58ef4e?auto=format&fit=crop&w=900&q=80"
                             alt="Thi công cốp pha cốt thép sàn căn hộ cho thuê Đà Nẵng"
                             onerror="handleDriveImgError(this)">
                    </div>
                    <div class="flatsome-box-text">
                        <div>
                            <h3 class="product-title-full">Thi Công Kết Cấu Khung Bê Tông Căn Hộ Cho Thuê 5 Tầng</h3>
                            <p class="text-[11px] text-slate-500">Danh mục: Khách sạn – Căn hộ – Phòng trọ</p>
                        </div>
                    </div>
                </article>

                <!-- Ảnh thực tế 3: 1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv -->
                <article class="flatsome-box cons-item" data-category="biet-thu">
                    <div class="flatsome-box-image">
                        <img src="https://drive.google.com/thumbnail?id=1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv&sz=w1000"
                             data-drive-id="1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv"
                             data-fallback="https://images.unsplash.com/photo-1590674899484-d5640e854abe?auto=format&fit=crop&w=900&q=80"
                             alt="Thi công xây tường và hoàn thiện mặt tiền biệt thự hiện đại"
                             onerror="handleDriveImgError(this)">
                    </div>
                    <div class="flatsome-box-text">
                        <div>
                            <h3 class="product-title-full">Thi Công Xây Thô & Hoàn Thiện Biệt Thự Nghỉ Dưỡng 2 Mặt Tiền</h3>
                            <p class="text-[11px] text-slate-500">Danh mục: Biệt thự – Thi công trọn gói</p>
                        </div>
                    </div>
                </article>

                <!-- Ảnh thực tế 4: 1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_ -->
                <article class="flatsome-box cons-item" data-category="nha-pho">
                    <div class="flatsome-box-image">
                        <img src="https://drive.google.com/thumbnail?id=1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_&sz=w1000"
                             data-drive-id="1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_"
                             data-fallback="https://images.unsplash.com/photo-1581094794329-c8112a89af12?auto=format&fit=crop&w=900&q=80"
                             alt="Thi công đổ bê tông sàn và giám sát kỹ thuật nhà phố"
                             onerror="handleDriveImgError(this)">
                    </div>
                    <div class="flatsome-box-text">
                        <div>
                            <h3 class="product-title-full">Nghiệm Thu Cốt Thép & Đổ Bê Tông Sàn Nhà Phố Khu Nam Việt Á</h3>
                            <p class="text-[11px] text-slate-500">Danh mục: Nhà phố – Thi công phần thô</p>
                        </div>
                    </div>
                </article>

                <!-- Ảnh thực tế 5: 1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO -->
                <article class="flatsome-box cons-item" data-category="khach-san-can-ho">
                    <div class="flatsome-box-image">
                        <img src="https://drive.google.com/thumbnail?id=1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO&sz=w1000"
                             data-drive-id="1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO"
                             data-fallback="https://images.unsplash.com/photo-1545324418-cc1a3fa10c00?auto=format&fit=crop&w=900&q=80"
                             alt="Thi công hoàn thiện mặt tiền căn hộ dịch vụ và khách sạn"
                             onerror="handleDriveImgError(this)">
                    </div>
                    <div class="flatsome-box-text">
                        <div>
                            <h3 class="product-title-full">Thi Công Hoàn Thiện Căn Hộ Dịch Vụ & Khách Sạn Ven Biển</h3>
                            <p class="text-[11px] text-slate-500">Danh mục: Khách sạn – Căn hộ – Phòng trọ</p>
                        </div>
                    </div>
                </article>

                <!-- Ảnh thực tế 6: 1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t -->
                <article class="flatsome-box cons-item" data-category="van-phong">
                    <div class="flatsome-box-image">
                        <img src="https://drive.google.com/thumbnail?id=1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t&sz=w1000"
                             data-drive-id="1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t"
                             data-fallback="https://images.unsplash.com/photo-1497366216548-37526070297c?auto=format&fit=crop&w=900&q=80"
                             alt="Thi công cải tạo và hoàn thiện tòa nhà văn phòng công ty"
                             onerror="handleDriveImgError(this)">
                    </div>
                    <div class="flatsome-box-text">
                        <div>
                            <h3 class="product-title-full">Thi Công Xây Dựng & Hoàn Thiện Văn Phòng Kết Hợp Nhà Ở</h3>
                            <p class="text-[11px] text-slate-500">Danh mục: Văn phòng – Thi công hoàn thiện</p>
                        </div>
                    </div>
                </article>

                <!-- Ảnh thực tế 7: 1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_ -->
                <article class="flatsome-box cons-item" data-category="biet-thu">
                    <div class="flatsome-box-image">
                        <img src="https://drive.google.com/thumbnail?id=1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_&sz=w1000"
                             data-drive-id="1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_"
                             data-fallback="https://images.unsplash.com/photo-1600585154526-990dced4db0d?auto=format&fit=crop&w=900&q=80"
                             alt="Thi công hoàn thiện biệt thự phố sân vườn tại Đà Nẵng"
                             onerror="handleDriveImgError(this)">
                    </div>
                    <div class="flatsome-box-text">
                        <div>
                            <h3 class="product-title-full">Thi Công Trọn Gói Biệt Thự Sân Vườn Hiện Đại Khu Hòa Xuân</h3>
                            <p class="text-[11px] text-slate-500">Danh mục: Biệt thự – Thi công hoàn thiện</p>
                        </div>
                    </div>
                </article>

                <!-- Ảnh thực tế 8: 1wHGqk7znpnGmrOjz4_EdpHnHK8xKyxkT -->
                <article class="flatsome-box cons-item" data-category="nha-pho">
                    <div class="flatsome-box-image">
                        <img src="https://drive.google.com/thumbnail?id=1wHGqk7znpnGmrOjz4_EdpHnHK8xKyxkT&sz=w1000"
                             data-drive-id="1wHGqk7znpnGmrOjz4_EdpHnHK8xKyxkT"
                             data-fallback="https://images.unsplash.com/photo-1600566753376-12c8ab7fb75b?auto=format&fit=crop&w=900&q=80"
                             alt="Thi công nội thất và hoàn thiện không gian nhà phố hiện đại"
                             onerror="handleDriveImgError(this)">
                    </div>
                    <div class="flatsome-box-text">
                        <div>
                            <h3 class="product-title-full">Thi Công Hoàn Thiện & Lắp Đặt Nội Thất Nhà Phố 3 Tầng 1 Tum</h3>
                            <p class="text-[11px] text-slate-500">Danh mục: Nhà phố – Thi công nội thất</p>
                        </div>
                    </div>
                </article>

                <!-- Ảnh thực tế 9: 1-eBgG9wF3I6_gyPir2CmCnwJg4sP7Bnn -->
                <article class="flatsome-box cons-item" data-category="nha-pho">
                    <div class="flatsome-box-image">
                        <img src="https://drive.google.com/thumbnail?id=1-eBgG9wF3I6_gyPir2CmCnwJg4sP7Bnn&sz=w1000"
                             data-drive-id="1-eBgG9wF3I6_gyPir2CmCnwJg4sP7Bnn"
                             data-fallback="https://images.unsplash.com/photo-1600585152220-90363fe7e115?auto=format&fit=crop&w=900&q=80"
                             alt="Bàn giao công trình nhà phố trọn gói chìa khóa trao tay"
                             onerror="handleDriveImgError(this)">
                    </div>
                    <div class="flatsome-box-text">
                        <div>
                            <h3 class="product-title-full">Hoàn Thiện Bàn Giao Nhà Phố Hiện Đại Chìa Khóa Trao Tay</h3>
                            <p class="text-[11px] text-slate-500">Danh mục: Nhà phố – Xây nhà trọn gói</p>
                        </div>
                    </div>
                </article>
            </div>
        </div>
    </section>

    <!-- ==========================================
         SECTION 5: DANH MỤC CÁC DỰ ÁN Ở ĐÀ NẴNG (10 FILE GOOGLE DRIVE DỰ ÁN ĐÀ NẴNG)
         - Điện thoại: 2 cột (grid-cols-2)
         - Máy tính: 5 cột (lg:grid-cols-5)
         - Không gắn nhãn dán đè trên ảnh
         ========================================== -->
    <section id="du-an-da-nang" class="py-10 bg-white border-t border-slate-200">
        <div class="flatsome-container">
            <div class="text-center mb-6">
                <div class="flatsome-section-title">
                    <h2 class="text-lg md:text-2xl font-extrabold text-[#0f2942] uppercase">Các Dự Án Tiêu Biểu Tại Đà Nẵng</h2>
                </div>
                <p class="text-xs md:text-sm text-slate-600">Tổng hợp các dự án Thiết kế Kiến trúc & Thi công Xây dựng do ANCI DESIGN thực hiện tại TP Đà Nẵng</p>
            </div>

            <!-- Danh mục khu vực dự án Đà Nẵng (nhỏ gọn, 1 hàng) -->
            <div class="flex flex-wrap items-center justify-center gap-1.5 sm:gap-2 mb-6">
                <button type="button" onclick="filterDaNang('all')" data-dn-filter="all" class="dn-filter-btn category-pill active">Tất cả dự án Đà Nẵng</button>
                <button type="button" onclick="filterDaNang('ngu-hanh-son')" data-dn-filter="ngu-hanh-son" class="dn-filter-btn category-pill">Ngũ Hành Sơn</button>
                <button type="button" onclick="filterDaNang('cam-le-hoa-xuan')" data-dn-filter="cam-le-hoa-xuan" class="dn-filter-btn category-pill">Hòa Xuân – Cẩm Lệ</button>
                <button type="button" onclick="filterDaNang('son-tra-hai-chau')" data-dn-filter="son-tra-hai-chau" class="dn-filter-btn category-pill">Sơn Trà – Hải Châu</button>
            </div>

            <!-- Grid 10 Dự án tại Đà Nẵng: 2 cột trên điện thoại, 5 cột trên màn hình lớn -->
            <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-5 gap-3 md:gap-4">
                <!-- Dự án Đà Nẵng 1: 157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT -->
                <article class="flatsome-box dn-item" data-dn="ngu-hanh-son">
                    <div class="flatsome-box-image">
                        <img src="https://drive.google.com/thumbnail?id=157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT&sz=w900"
                             data-drive-id="157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT"
                             data-fallback="https://images.unsplash.com/photo-1600585154340-be6161a56a0c?auto=format&fit=crop&w=800&q=80"
                             alt="Dự án Nhà phố hiện đại Khu K20 Ngũ Hành Sơn Đà Nẵng"
                             onerror="handleDriveImgError(this)">
                    </div>
                    <div class="flatsome-box-text">
                        <h3 class="product-title-full">Dự Án Nhà Phố Hiện Đại Khu K20 – Ngũ Hành Sơn, Đà Nẵng</h3>
                        <p class="text-[11px] text-slate-500">Thiết kế & Thi công trọn gói</p>
                    </div>
                </article>

                <!-- Dự án Đà Nẵng 2: 1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff -->
                <article class="flatsome-box dn-item" data-dn="cam-le-hoa-xuan">
                    <div class="flatsome-box-image">
                        <img src="https://drive.google.com/thumbnail?id=1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff&sz=w900"
                             data-drive-id="1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff"
                             data-fallback="https://images.unsplash.com/photo-1600607687939-ce8a6c25118c?auto=format&fit=crop&w=800&q=80"
                             alt="Dự án Biệt thự phố Khu đô thị Nam Hòa Xuân Đà Nẵng"
                             onerror="handleDriveImgError(this)">
                    </div>
                    <div class="flatsome-box-text">
                        <h3 class="product-title-full">Dự Án Biệt Thự Phố Khu Đô Thị Nam Hòa Xuân – Đà Nẵng</h3>
                        <p class="text-[11px] text-slate-500">Kiến trúc & Nội thất cao cấp</p>
                    </div>
                </article>

                <!-- Dự án Đà Nẵng 3: 1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz -->
                <article class="flatsome-box dn-item" data-dn="son-tra-hai-chau">
                    <div class="flatsome-box-image">
                        <img src="https://drive.google.com/thumbnail?id=1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz&sz=w900"
                             data-drive-id="1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz"
                             data-fallback="https://images.unsplash.com/photo-1600596542815-ffad4c1539a9?auto=format&fit=crop&w=800&q=80"
                             alt="Dự án Căn hộ cho thuê cao cấp Sơn Trà Đà Nẵng"
                             onerror="handleDriveImgError(this)">
                    </div>
                    <div class="flatsome-box-text">
                        <h3 class="product-title-full">Dự Án Căn Hộ Dịch Vụ Cao Cấp Quận Sơn Trà – Đà Nẵng</h3>
                        <p class="text-[11px] text-slate-500">Khách sạn – Căn hộ cho thuê</p>
                    </div>
                </article>

                <!-- Dự án Đà Nẵng 4: 1I7lc3ghS0tyqh6Pq3xsZTidKsr0oT-8k -->
                <article class="flatsome-box dn-item" data-dn="ngu-hanh-son">
                    <div class="flatsome-box-image">
                        <img src="https://drive.google.com/thumbnail?id=1I7lc3ghS0tyqh6Pq3xsZTidKsr0oT-8k&sz=w900"
                             data-drive-id="1I7lc3ghS0tyqh6Pq3xsZTidKsr0oT-8k"
                             data-fallback="https://images.unsplash.com/photo-1600585154526-990dced4db0d?auto=format&fit=crop&w=800&q=80"
                             alt="Dự án Nhà phố 3 tầng Khu Nam Việt Á Ngũ Hành Sơn Đà Nẵng"
                             onerror="handleDriveImgError(this)">
                    </div>
                    <div class="flatsome-box-text">
                        <h3 class="product-title-full">Dự Án Nhà Phố 3 Tầng Khu Nam Việt Á – Ngũ Hành Sơn</h3>
                        <p class="text-[11px] text-slate-500">Thiết kế & Thi công hoàn thiện</p>
                    </div>
                </article>

                <!-- Dự án Đà Nẵng 5: 1Q8VoCbT7s09UNaoI8GNcYdvKpJ2wz78N -->
                <article class="flatsome-box dn-item" data-dn="cam-le-hoa-xuan">
                    <div class="flatsome-box-image">
                        <img src="https://drive.google.com/thumbnail?id=1Q8VoCbT7s09UNaoI8GNcYdvKpJ2wz78N&sz=w900"
                             data-drive-id="1Q8VoCbT7s09UNaoI8GNcYdvKpJ2wz78N"
                             data-fallback="https://images.unsplash.com/photo-1600566753190-17f0baa2a6c3?auto=format&fit=crop&w=800&q=80"
                             alt="Dự án Nhà phố lệch tầng thông thoáng tại Hòa Xuân Đà Nẵng"
                             onerror="handleDriveImgError(this)">
                    </div>
                    <div class="flatsome-box-text">
                        <h3 class="product-title-full">Dự Án Nhà Phố Lệch Tầng Hiện Đại Hòa Xuân – Đà Nẵng</h3>
                        <p class="text-[11px] text-slate-500">Xây nhà trọn gói</p>
                    </div>
                </article>

                <!-- Dự án Đà Nẵng 6: 1tkQlfZJTkaSunwOIMhfnzkEG2YHwxhML -->
                <article class="flatsome-box dn-item" data-dn="son-tra-hai-chau">
                    <div class="flatsome-box-image">
                        <img src="https://drive.google.com/thumbnail?id=1tkQlfZJTkaSunwOIMhfnzkEG2YHwxhML&sz=w900"
                             data-drive-id="1tkQlfZJTkaSunwOIMhfnzkEG2YHwxhML"
                             data-fallback="https://images.unsplash.com/photo-1600210492486-724fe5c67fb0?auto=format&fit=crop&w=800&q=80"
                             alt="Dự án Biệt thự 2 mặt tiền Quận Hải Châu Đà Nẵng"
                             onerror="handleDriveImgError(this)">
                    </div>
                    <div class="flatsome-box-text">
                        <h3 class="product-title-full">Dự Án Biệt Thự 2 Mặt Tiền Trung Tâm Hải Châu – Đà Nẵng</h3>
                        <p class="text-[11px] text-slate-500">Thiết kế Biệt thự cao cấp</p>
                    </div>
                </article>

                <!-- Dự án Đà Nẵng 7: 1An7LyMVwj3rhKZlsVnYQ2UrLe48IeTBF -->
                <article class="flatsome-box dn-item" data-dn="ngu-hanh-son">
                    <div class="flatsome-box-image">
                        <img src="https://drive.google.com/thumbnail?id=1An7LyMVwj3rhKZlsVnYQ2UrLe48IeTBF&sz=w900"
                             data-drive-id="1An7LyMVwj3rhKZlsVnYQ2UrLe48IeTBF"
                             data-fallback="https://images.unsplash.com/photo-1600585152220-90363fe7e115?auto=format&fit=crop&w=800&q=80"
                             alt="Dự án Homestay & Villa nghỉ dưỡng biển Mỹ Khê Đà Nẵng"
                             onerror="handleDriveImgError(this)">
                    </div>
                    <div class="flatsome-box-text">
                        <h3 class="product-title-full">Dự Án Villa & Homestay Nghỉ Dưỡng Biển Mỹ Khê – Đà Nẵng</h3>
                        <p class="text-[11px] text-slate-500">Thiết kế & Thi công trọn gói</p>
                    </div>
                </article>

                <!-- Dự án Đà Nẵng 8: 1R1Da04pAYI9-NJz1IsAfa7pVKkuK7J-A -->
                <article class="flatsome-box dn-item" data-dn="son-tra-hai-chau">
                    <div class="flatsome-box-image">
                        <img src="https://drive.google.com/thumbnail?id=1R1Da04pAYI9-NJz1IsAfa7pVKkuK7J-A&sz=w900"
                             data-drive-id="1R1Da04pAYI9-NJz1IsAfa7pVKkuK7J-A"
                             data-fallback="https://images.unsplash.com/photo-1600573472589-003525b2b729?auto=format&fit=crop&w=800&q=80"
                             alt="Dự án Văn phòng kết hợp căn hộ tại Hải Châu Đà Nẵng"
                             onerror="handleDriveImgError(this)">
                    </div>
                    <div class="flatsome-box-text">
                        <h3 class="product-title-full">Dự Án Tòa Nhà Văn Phòng & Căn Hộ Hải Châu – Đà Nẵng</h3>
                        <p class="text-[11px] text-slate-500">Thi công Văn phòng & Căn hộ</p>
                    </div>
                </article>

                <!-- Dự án Đà Nẵng 9: 1FdQEsiEBrIW5TiN22dvzV5g6amDPp-80 -->
                <article class="flatsome-box dn-item" data-dn="cam-le-hoa-xuan">
                    <div class="flatsome-box-image">
                        <img src="https://drive.google.com/thumbnail?id=1FdQEsiEBrIW5TiN22dvzV5g6amDPp-80&sz=w900"
                             data-drive-id="1FdQEsiEBrIW5TiN22dvzV5g6amDPp-80"
                             data-fallback="https://images.unsplash.com/photo-1600566753376-12c8ab7fb75b?auto=format&fit=crop&w=800&q=80"
                             alt="Dự án Nhà phố kết hợp kinh doanh Cẩm Lệ Đà Nẵng"
                             onerror="handleDriveImgError(this)">
                    </div>
                    <div class="flatsome-box-text">
                        <h3 class="product-title-full">Dự Án Nhà Phố Kết Hợp Kinh Doanh Quận Cẩm Lệ – Đà Nẵng</h3>
                        <p class="text-[11px] text-slate-500">Thiết kế Kiến trúc & Nội thất</p>
                    </div>
                </article>

                <!-- Dự án Đà Nẵng 10: 1So_3V4rw1y7lHegiIkYmh2Z9UIdozAL4 -->
                <article class="flatsome-box dn-item" data-dn="ngu-hanh-son">
                    <div class="flatsome-box-image">
                        <img src="https://drive.google.com/thumbnail?id=1So_3V4rw1y7lHegiIkYmh2Z9UIdozAL4&sz=w900"
                             data-drive-id="1So_3V4rw1y7lHegiIkYmh2Z9UIdozAL4"
                             data-fallback="https://images.unsplash.com/photo-1613490493576-7fde63acd811?auto=format&fit=crop&w=800&q=80"
                             alt="Dự án Biệt thự sân vườn Ngũ Hành Sơn Đà Nẵng"
                             onerror="handleDriveImgError(this)">
                    </div>
                    <div class="flatsome-box-text">
                        <h3 class="product-title-full">Dự Án Biệt Thự Sân Vườn Nghỉ Dưỡng Ngũ Hành Sơn – Đà Nẵng</h3>
                        <p class="text-[11px] text-slate-500">Chìa khóa trao tay</p>
                    </div>
                </article>
            </div>
        </div>
    </section>

    <!-- ==========================================
         SECTION 6: DANH MỤC SẢN PHẨM / MẪU THIẾT KẾ & BÁO GIÁ (LẤY TỪ WEB MẪU TINTRUONGTHINH.COM)
         - Điện thoại chia 2 cột, tên đầy đủ không tràn
         ========================================== -->
    <section id="danh-muc-san-pham" class="py-10 bg-slate-50 border-t border-slate-200">
        <div class="flatsome-container">
            <div class="text-center mb-6">
                <div class="flatsome-section-title">
                    <h2 class="text-lg md:text-2xl font-extrabold text-[#0f2942] uppercase">Danh Mục Mẫu Thiết Kế & Gói Dịch Vụ Xây Dựng</h2>
                </div>
                <p class="text-xs md:text-sm text-slate-600">Các gói sản phẩm thiết kế kiến trúc, nội thất và báo giá thi công chuẩn của ANCI DESIGN</p>
            </div>

            <!-- Sản phẩm chia 2 cột trên điện thoại, 4 cột trên máy tính -->
            <div id="bang-bao-gia" class="grid grid-cols-2 lg:grid-cols-4 gap-3 md:gap-5">
                <div class="flatsome-box">
                    <div class="flatsome-box-image">
                        <img src="https://drive.google.com/thumbnail?id=157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT&sz=w800"
                             data-drive-id="157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT"
                             data-fallback="https://images.unsplash.com/photo-1600585154340-be6161a56a0c?auto=format&fit=crop&w=800&q=80"
                             alt="Báo giá thiết kế kiến trúc nhà phố và biệt thự"
                             onerror="handleDriveImgError(this)">
                    </div>
                    <div class="flatsome-box-text">
                        <div>
                            <h3 class="product-title-full">Gói Thiết Kế Kiến Trúc & Hồ Sơ Kỹ Thuật Thi Công</h3>
                            <p class="text-xs text-[#c59434] font-bold mb-1">120.000đ – 180.000đ / m²</p>
                            <p class="text-[11px] text-slate-500">Miễn phí 100% phí thiết kế khi ký hợp đồng thi công trọn gói</p>
                        </div>
                        <a href="#form-bao-gia" class="mt-3 inline-block py-1.5 px-3 rounded bg-[#0f2942] hover:bg-[#c59434] text-white text-xs font-semibold transition">
                            Nhận báo giá
                        </a>
                    </div>
                </div>

                <div class="flatsome-box">
                    <div class="flatsome-box-image">
                        <img src="https://drive.google.com/thumbnail?id=13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz&sz=w800"
                             data-drive-id="13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz"
                             data-fallback="https://images.unsplash.com/photo-1541888946425-d09bb18086f6?auto=format&fit=crop&w=800&q=80"
                             alt="Báo giá thi công phần thô và nhân công hoàn thiện"
                             onerror="handleDriveImgError(this)">
                    </div>
                    <div class="flatsome-box-text">
                        <div>
                            <h3 class="product-title-full">Gói Thi Công Phần Thô & Nhân Công Hoàn Thiện</h3>
                            <p class="text-xs text-[#c59434] font-bold mb-1">3.600.000đ – 3.950.000đ / m²</p>
                            <p class="text-[11px] text-slate-500">Vật tư chuẩn chính hãng, bảo hành kết cấu lên đến 10 năm</p>
                        </div>
                        <a href="#form-bao-gia" class="mt-3 inline-block py-1.5 px-3 rounded bg-[#0f2942] hover:bg-[#c59434] text-white text-xs font-semibold transition">
                            Nhận báo giá
                        </a>
                    </div>
                </div>

                <div class="flatsome-box">
                    <div class="flatsome-box-image">
                        <img src="https://drive.google.com/thumbnail?id=1-eBgG9wF3I6_gyPir2CmCnwJg4sP7Bnn&sz=w800"
                             data-drive-id="1-eBgG9wF3I6_gyPir2CmCnwJg4sP7Bnn"
                             data-fallback="https://images.unsplash.com/photo-1600585152220-90363fe7e115?auto=format&fit=crop&w=800&q=80"
                             alt="Báo giá thi công hoàn thiện công trình"
                             onerror="handleDriveImgError(this)">
                    </div>
                    <div class="flatsome-box-text">
                        <div>
                            <h3 class="product-title-full">Gói Thi Công Hoàn Thiện Nhà Phố & Biệt Thự</h3>
                            <p class="text-xs text-[#c59434] font-bold mb-1">2.400.000đ – 3.200.000đ / m²</p>
                            <p class="text-[11px] text-slate-500">Ốp lát, sơn nước, thiết bị vệ sinh, cửa nhôm kính đồng bộ</p>
                        </div>
                        <a href="#form-bao-gia" class="mt-3 inline-block py-1.5 px-3 rounded bg-[#0f2942] hover:bg-[#c59434] text-white text-xs font-semibold transition">
                            Nhận báo giá
                        </a>
                    </div>
                </div>

                <div class="flatsome-box">
                    <div class="flatsome-box-image">
                        <img src="https://drive.google.com/thumbnail?id=1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff&sz=w800"
                             data-drive-id="1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff"
                             data-fallback="https://images.unsplash.com/photo-1600607687939-ce8a6c25118c?auto=format&fit=crop&w=800&q=80"
                             alt="Báo giá xây nhà trọn gói chìa khóa trao tay"
                             onerror="handleDriveImgError(this)">
                    </div>
                    <div class="flatsome-box-text">
                        <div>
                            <h3 class="product-title-full">Gói Xây Nhà Trọn Gói Chìa Khóa Trao Tay</h3>
                            <p class="text-xs text-[#c59434] font-bold mb-1">5.800.000đ – 7.200.000đ / m²</p>
                            <p class="text-[11px] text-slate-500">Bao gồm xin phép xây dựng, thiết kế 3D và thi công hoàn chỉnh</p>
                        </div>
                        <a href="#form-bao-gia" class="mt-3 inline-block py-1.5 px-3 rounded bg-[#0f2942] hover:bg-[#c59434] text-white text-xs font-semibold transition">
                            Nhận báo giá
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         SECTION 7: FORM YÊU CẦU TƯ VẤN & BÁO GIÁ + FANPAGE NGOÀI TRANG CHỦ
         ========================================== -->
    <section id="form-bao-gia" class="py-10 bg-[#0f2942] text-white">
        <div class="flatsome-container">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-start">
                <!-- Cột Form Yêu cầu tư vấn & Báo giá (Giống mẫu tintruongthinh.com) -->
                <div class="lg:col-span-7 bg-white text-slate-800 rounded-xl p-5 md:p-7 shadow-lg">
                    <p class="text-xs font-bold uppercase tracking-wider text-[#c59434] mb-1">Hỗ trợ nhanh 24/7</p>
                    <h2 class="text-lg md:text-2xl font-extrabold text-[#0f2942] mb-2 uppercase">Đăng Ký Yêu Cầu Tư Vấn & Báo Giá Miễn Phí</h2>
                    <p class="text-xs text-slate-600 mb-5">
                        Quý khách vui lòng để lại thông tin công trình, Kiến trúc sư trưởng của <strong>ANCI DESIGN</strong> sẽ liên hệ tư vấn và gửi bảng dự toán chi tiết.
                    </p>

                    <form id="quote-request-form" onsubmit="submitQuoteForm(event)" class="space-y-3.5">
                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-3.5">
                            <div>
                                <label class="block text-xs font-bold text-[#0f2942] mb-1">Họ và tên *</label>
                                <input type="text" id="cust-name" required placeholder="Nhập họ và tên của bạn"
                                       class="w-full px-3 py-2.5 text-xs md:text-sm rounded-lg border border-slate-300 focus:outline-none focus:border-[#c59434]">
                            </div>
                            <div>
                                <label class="block text-xs font-bold text-[#0f2942] mb-1">Số điện thoại *</label>
                                <input type="tel" id="cust-phone" required placeholder="Ví dụ: 0325 012 356"
                                       class="w-full px-3 py-2.5 text-xs md:text-sm rounded-lg border border-slate-300 focus:outline-none focus:border-[#c59434]">
                            </div>
                        </div>

                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-3.5">
                            <div>
                                <label class="block text-xs font-bold text-[#0f2942] mb-1">Loại công trình</label>
                                <select id="cust-type" class="w-full px-3 py-2.5 text-xs md:text-sm rounded-lg border border-slate-300 bg-white focus:outline-none focus:border-[#c59434]">
                                    <option value="Nhà phố">Nhà phố</option>
                                    <option value="Biệt thự">Biệt thự</option>
                                    <option value="Khách sạn – Căn hộ cho thuê – Phòng trọ">Khách sạn – Căn hộ cho thuê – Phòng trọ</option>
                                    <option value="Văn phòng">Văn phòng</option>
                                    <option value="Thi công nội thất">Thi công nội thất</option>
                                    <option value="Cải tạo sửa chữa">Cải tạo sửa chữa</option>
                                </select>
                            </div>
                            <div>
                                <label class="block text-xs font-bold text-[#0f2942] mb-1">Mức đầu tư dự kiến</label>
                                <select id="cust-budget" class="w-full px-3 py-2.5 text-xs md:text-sm rounded-lg border border-slate-300 bg-white focus:outline-none focus:border-[#c59434]">
                                    <option value="Chưa xác định">Chưa xác định</option>
                                    <option value="Dưới 500 triệu">Dưới 500 triệu</option>
                                    <option value="500 triệu - 1 tỷ">500 triệu – 1 tỷ</option>
                                    <option value="1 - 2 tỷ">1 – 2 tỷ</option>
                                    <option value="2 - 3 tỷ">2 – 3 tỷ</option>
                                    <option value="Trên 3 tỷ">Trên 3 tỷ</option>
                                </select>
                            </div>
                        </div>

                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-3.5">
                            <div>
                                <label class="block text-xs font-bold text-[#0f2942] mb-1">Email (nếu có)</label>
                                <input type="email" id="cust-email" placeholder="Nhập địa chỉ email"
                                       class="w-full px-3 py-2.5 text-xs md:text-sm rounded-lg border border-slate-300 focus:outline-none focus:border-[#c59434]">
                            </div>
                            <div>
                                <label class="block text-xs font-bold text-[#0f2942] mb-1">Địa điểm xây dựng & Diện tích</label>
                                <input type="text" id="cust-area" placeholder="VD: Ngũ Hành Sơn, Đà Nẵng - 5x20m"
                                       class="w-full px-3 py-2.5 text-xs md:text-sm rounded-lg border border-slate-300 focus:outline-none focus:border-[#c59434]">
                            </div>
                        </div>

                        <div>
                            <label class="block text-xs font-bold text-[#0f2942] mb-1">Nội dung yêu cầu chi tiết</label>
                            <textarea id="cust-note" rows="3" placeholder="Nhu cầu số tầng, số phòng ngủ, phong cách thiết kế mong muốn..."
                                      class="w-full px-3 py-2 text-xs md:text-sm rounded-lg border border-slate-300 focus:outline-none focus:border-[#c59434]"></textarea>
                        </div>

                        <button type="submit"
                                class="w-full py-3 px-5 rounded-lg bg-[#c59434] hover:bg-[#a6781e] text-white font-extrabold text-xs md:text-sm uppercase tracking-wider transition shadow">
                            GỬI YÊU CẦU NHẬN BÁO GIÁ NGAY
                        </button>
                    </form>

                    <!-- Hộp thông báo xác nhận gửi thành công (không dùng alert) -->
                    <div id="quote-success-box" class="hidden mt-4 p-3.5 rounded-lg bg-emerald-50 border border-emerald-300 text-emerald-800 text-xs">
                        <strong class="block mb-1"><i class="fa-solid fa-circle-check mr-1"></i>Đã tiếp nhận yêu cầu báo giá!</strong>
                        <span id="quote-success-detail"></span>
                    </div>
                </div>

                <!-- Cột Fanpage chính thức hiển thị ngay ngoài Trang chủ -->
                <div class="lg:col-span-5 bg-white text-slate-800 rounded-xl p-5 md:p-6 shadow-lg">
                    <p class="text-xs font-bold uppercase tracking-wider text-[#c59434] mb-1">Kết nối mạng xã hội</p>
                    <h3 class="text-base md:text-xl font-extrabold text-[#0f2942] mb-2 uppercase">Fanpage Chính Thức ANCI DESIGN</h3>
                    <p class="text-xs text-slate-600 mb-4">
                        Theo dõi Fanpage <strong>ANCI Design & Building</strong> để cập nhật hình ảnh công trường và các mẫu nhà đẹp mới nhất mỗi ngày.
                    </p>

                    <!-- Khung nhúng Facebook Fanpage trực tiếp ngoài trang chủ -->
                    <div class="w-full overflow-hidden rounded-lg border border-slate-200 bg-slate-50 mb-4 flex justify-center">
                        <iframe src="https://www.facebook.com/plugins/page.php?href=https%3A%2F%2Fwww.facebook.com%2FAncidesignandbuilding&tabs=timeline&width=340&height=320&small_header=false&adapt_container_width=true&hide_cover=false&show_facepile=true"
                                width="340"
                                height="320"
                                style="border:none;overflow:hidden;max-width:100%;"
                                scrolling="no"
                                frameborder="0"
                                allowfullscreen="true"
                                allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share"
                                title="Fanpage ANCI Design and Building"></iframe>
                    </div>

                    <div class="flex flex-wrap items-center justify-between gap-2 p-3 rounded-lg bg-slate-100 border border-slate-200">
                        <div class="text-xs">
                            <strong class="block text-[#0f2942]">ANCI Design & Building</strong>
                            <span class="text-slate-500">facebook.com/Ancidesignandbuilding</span>
                        </div>
                        <a href="https://www.facebook.com/Ancidesignandbuilding" target="_blank" rel="noopener noreferrer"
                           class="px-3.5 py-2 rounded-lg bg-[#1877F2] hover:bg-blue-700 text-white text-xs font-bold inline-flex items-center gap-1.5 transition">
                            <i class="fa-brands fa-facebook-f"></i>
                            <span>Mở Fanpage</span>
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         SECTION 8: DANH MỤC CÁC BÀI VIẾT TRANG CHỦ (TIN TỨC & KINH NGHIỆM XÂY DỰNG)
         - Điện thoại 2 cột, máy tính 4 cột
         ========================================== -->
    <section id="tin-tuc" class="py-10 bg-white border-t border-slate-200">
        <div class="flatsome-container">
            <div class="text-center mb-6">
                <div class="flatsome-section-title">
                    <h2 class="text-lg md:text-2xl font-extrabold text-[#0f2942] uppercase">Tin Tức & Cẩm Nang Xây Dựng</h2>
                </div>
                <p class="text-xs md:text-sm text-slate-600">Chia sẻ kinh nghiệm thiết kế kiến trúc, thi công phần thô và dự toán xây nhà tại Đà Nẵng</p>
            </div>

            <!-- Danh sách bài viết: 2 cột trên điện thoại, 4 cột trên máy tính -->
            <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 md:gap-5">
                <article class="flatsome-box">
                    <div class="flatsome-box-image">
                        <img src="https://drive.google.com/thumbnail?id=13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz&sz=w800"
                             data-drive-id="13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz"
                             data-fallback="https://images.unsplash.com/photo-1541888946425-d09bb18086f6?auto=format&fit=crop&w=800&q=80"
                             alt="Hướng dẫn bảo dưỡng bê tông móng và sàn đúng kỹ thuật"
                             onerror="handleDriveImgError(this)">
                    </div>
                    <div class="flatsome-box-text text-left">
                        <div>
                            <h3 class="product-title-full">Hướng Dẫn Bảo Dưỡng Bê Tông Móng Và Sàn Đúng Kỹ Thuật</h3>
                            <p class="text-xs text-slate-600 mt-1 line-clamp-3">
                                Quy trình giữ ẩm và bảo dưỡng bê tông sau khi đổ giúp kết cấu công trình đạt cường độ tối đa, chống nứt sàn hiệu quả.
                            </p>
                        </div>
                        <a href="#form-bao-gia" class="text-xs font-bold text-[#c59434] mt-2 inline-block hover:underline">Xem chi tiết →</a>
                    </div>
                </article>

                <article class="flatsome-box">
                    <div class="flatsome-box-image">
                        <img src="https://drive.google.com/thumbnail?id=157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT&sz=w800"
                             data-drive-id="157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT"
                             data-fallback="https://images.unsplash.com/photo-1600585154340-be6161a56a0c?auto=format&fit=crop&w=800&q=80"
                             alt="Kinh nghiệm xây nhà trọn gói tại Đà Nẵng tiết kiệm chi phí"
                             onerror="handleDriveImgError(this)">
                    </div>
                    <div class="flatsome-box-text text-left">
                        <div>
                            <h3 class="product-title-full">03 Lưu Ý Quan Trọng Khi Xây Nhà Trọn Gói Tại Đà Nẵng Chủ Đầu Tư Cần Biết</h3>
                            <p class="text-xs text-slate-600 mt-1 line-clamp-3">
                                Từ bước lập hồ sơ thiết kế, xin giấy phép xây dựng đến lựa chọn chủng loại vật tư phần thô và hoàn thiện minh bạch.
                            </p>
                        </div>
                        <a href="#form-bao-gia" class="text-xs font-bold text-[#c59434] mt-2 inline-block hover:underline">Xem chi tiết →</a>
                    </div>
                </article>

                <article class="flatsome-box">
                    <div class="flatsome-box-image">
                        <img src="https://drive.google.com/thumbnail?id=1wHGqk7znpnGmrOjz4_EdpHnHK8xKyxkT&sz=w800"
                             data-drive-id="1wHGqk7znpnGmrOjz4_EdpHnHK8xKyxkT"
                             data-fallback="https://images.unsplash.com/photo-1600566753376-12c8ab7fb75b?auto=format&fit=crop&w=800&q=80"
                             alt="Tâm lý học không gian và xu hướng thiết kế nội thất hiện đại"
                             onerror="handleDriveImgError(this)">
                    </div>
                    <div class="flatsome-box-text text-left">
                        <div>
                            <h3 class="product-title-full">Tâm Lý Học Không Gian: Thiết Kế Nội Thất Tác Động Đến Tổ Ấm Thế Nào?</h3>
                            <p class="text-xs text-slate-600 mt-1 line-clamp-3">
                                Cách kết hợp ánh sáng tự nhiên, thông gió và vật liệu mộc mạc giúp không gian sống luôn thư thái, sang trọng.
                            </p>
                        </div>
                        <a href="#form-bao-gia" class="text-xs font-bold text-[#c59434] mt-2 inline-block hover:underline">Xem chi tiết →</a>
                    </div>
                </article>

                <article class="flatsome-box">
                    <div class="flatsome-box-image">
                        <img src="https://drive.google.com/thumbnail?id=1I7lc3ghS0tyqh6Pq3xsZTidKsr0oT-8k&sz=w800"
                             data-drive-id="1I7lc3ghS0tyqh6Pq3xsZTidKsr0oT-8k"
                             data-fallback="https://images.unsplash.com/photo-1600585154526-990dced4db0d?auto=format&fit=crop&w=800&q=80"
                             alt="Giải pháp chống thấm nhà phố và biệt thự ven biển Đà Nẵng"
                             onerror="handleDriveImgError(this)">
                    </div>
                    <div class="flatsome-box-text text-left">
                        <div>
                            <h3 class="product-title-full">Giải Pháp Chống Thấm Tường Ngoài & Sân Thượng Bền Vững Cho Khí Hậu Miền Trung</h3>
                            <p class="text-xs text-slate-600 mt-1 line-clamp-3">
                                Quy trình thi công chống thấm nhiều lớp chuyên dụng cho các công trình nhà phố, biệt thự và khách sạn ven biển.
                            </p>
                        </div>
                        <a href="#form-bao-gia" class="text-xs font-bold text-[#c59434] mt-2 inline-block hover:underline">Xem chi tiết →</a>
                    </div>
                </article>
            </div>
        </div>
    </section>

    <!-- ==========================================
         SECTION 9: DANH MỤC CÁC ĐỐI TÁC CUNG ỨNG VẬT TƯ & NỘI THẤT
         ========================================== -->
    <section id="doi-tac" class="py-9 bg-slate-50 border-t border-slate-200">
        <div class="flatsome-container">
            <div class="text-center mb-6">
                <div class="flatsome-section-title">
                    <h2 class="text-lg md:text-2xl font-extrabold text-[#0f2942] uppercase">Đối Tác Vật Tư & Thương Hiệu Đồng Hành</h2>
                </div>
                <p class="text-xs md:text-sm text-slate-600">ANCI DESIGN cam kết sử dụng vật tư chính hãng từ các nhà sản xuất uy tín hàng đầu</p>
            </div>

            <!-- Grid Đối tác: 2 cột trên điện thoại, 5 cột trên máy tính -->
            <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-5 gap-3">
                <div class="flatsome-box p-3.5 text-center justify-center items-center">
                    <span class="text-sm font-extrabold text-[#0f2942] tracking-wide">THÉP HÒA PHÁT</span>
                    <span class="text-[11px] text-slate-500 mt-0.5">Đối tác Thép kết cấu</span>
                </div>
                <div class="flatsome-box p-3.5 text-center justify-center items-center">
                    <span class="text-sm font-extrabold text-[#0f2942] tracking-wide">GỖ AN CƯỜNG</span>
                    <span class="text-[11px] text-slate-500 mt-0.5">Đối tác Nội thất gỗ</span>
                </div>
                <div class="flatsome-box p-3.5 text-center justify-center items-center">
                    <span class="text-sm font-extrabold text-[#0f2942] tracking-wide">SƠN DULUX & JOTUN</span>
                    <span class="text-[11px] text-slate-500 mt-0.5">Đối tác Sơn hoàn thiện</span>
                </div>
                <div class="flatsome-box p-3.5 text-center justify-center items-center">
                    <span class="text-sm font-extrabold text-[#0f2942] tracking-wide">INAX & TOTO</span>
                    <span class="text-[11px] text-slate-500 mt-0.5">Thiết bị vệ sinh cao cấp</span>
                </div>
                <div class="flatsome-box p-3.5 text-center justify-center items-center col-span-2 sm:col-span-1">
                    <span class="text-sm font-extrabold text-[#0f2942] tracking-wide">NHÔM XINGFA – PANASONIC</span>
                    <span class="text-[11px] text-slate-500 mt-0.5">Hệ cửa & Thiết bị điện</span>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         SECTION 10: BẢN ĐỒ GOOGLE MAPS NGOÀI TRANG CHỦ
         (Địa chỉ: 44/03 đường K20, Phường Ngũ Hành Sơn, TP Đà Nẵng)
         ========================================== -->
    <section id="lien-he" class="py-10 bg-white border-t border-slate-200">
        <div class="flatsome-container">
            <div class="text-center mb-6">
                <div class="flatsome-section-title">
                    <h2 class="text-lg md:text-2xl font-extrabold text-[#0f2942] uppercase">Bản Đồ Chỉ Đường & Thông Tin Liên Hệ</h2>
                </div>
                <p class="text-xs md:text-sm text-slate-600">
                    Địa chỉ trụ sở: <strong>44/03 đường K20, Phường Ngũ Hành Sơn, TP Đà Nẵng</strong> | Điện thoại: <strong>0325 012 356 – 0584 168 652</strong>
                </p>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-12 gap-5 items-stretch">
                <!-- Thông tin liên hệ trực tiếp -->
                <div class="lg:col-span-4 flatsome-box p-5 justify-between">
                    <div>
                        <h3 class="text-sm md:text-base font-extrabold text-[#0f2942] uppercase mb-3">
                            CÔNG TY TNHH TƯ VẤN THIẾT KẾ VÀ XÂY DỰNG ANCI DESIGN
                        </h3>
                        <ul class="space-y-3 text-xs md:text-sm text-slate-700">
                            <li class="flex items-start gap-2.5">
                                <i class="fa-solid fa-location-dot text-[#c59434] mt-1"></i>
                                <span><strong>Địa chỉ:</strong> 44/03 đường K20, Phường Ngũ Hành Sơn, TP Đà Nẵng</span>
                            </li>
                            <li class="flex items-start gap-2.5">
                                <i class="fa-solid fa-phone text-[#c59434] mt-1"></i>
                                <span><strong>Điện thoại:</strong> <a href="tel:0325012356" class="font-bold text-[#0f2942] hover:text-[#c59434]">0325 012 356</a> – <a href="tel:0584168652" class="font-bold text-[#0f2942] hover:text-[#c59434]">0584 168 652</a></span>
                            </li>
                            <li class="flex items-start gap-2.5">
                                <i class="fa-solid fa-globe text-[#c59434] mt-1"></i>
                                <span><strong>Website:</strong> <a href="https://ancidesign.com" class="font-semibold text-[#0f2942] hover:text-[#c59434]">ancidesign.com</a></span>
                            </li>
                            <li class="flex items-start gap-2.5">
                                <i class="fa-brands fa-facebook text-[#c59434] mt-1"></i>
                                <span><strong>Fanpage:</strong> <a href="https://www.facebook.com/Ancidesignandbuilding" target="_blank" rel="noopener noreferrer" class="font-semibold text-[#0f2942] hover:text-[#c59434]">ANCI Design & Building</a></span>
                            </li>
                            <li class="flex items-start gap-2.5">
                                <i class="fa-solid fa-id-card text-[#c59434] mt-1"></i>
                                <span><strong>Mã số thuế:</strong> 0402288042</span>
                            </li>
                        </ul>
                    </div>

                    <div class="mt-5 pt-4 border-t border-slate-200 flex flex-wrap gap-2">
                        <a href="https://www.google.com/maps?q=44/03+đường+K20,+Phường+Ngũ+Hành+Sơn,+TP+Đà+Nẵng" target="_blank" rel="noopener noreferrer"
                           class="flex-1 text-center py-2.5 px-3 rounded-lg bg-[#0f2942] hover:bg-[#c59434] text-white text-xs font-bold transition">
                            <i class="fa-solid fa-map-location-dot mr-1"></i>Mở Google Maps Lớn
                        </a>
                    </div>
                </div>

                <!-- Bản đồ Google Map hiển thị trực tiếp ngoài trang chủ -->
                <div class="lg:col-span-8 flatsome-box overflow-hidden min-h-[320px]">
                    <iframe
                        src="https://maps.google.com/maps?q=44/03%20%C4%91%C6%B0%E1%BB%9Dng%20K20,%20Ng%C5%A9%20H%C3%A0nh%20S%C6%A1n,%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed"
                        width="100%"
                        height="100%"
                        style="border:0; min-height:330px;"
                        allowfullscreen=""
                        loading="lazy"
                        referrerpolicy="no-referrer-when-downgrade"
                        title="Bản đồ Google Maps 44/03 đường K20, Phường Ngũ Hành Sơn, TP Đà Nẵng">
                    </iframe>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         FOOTER CHUẨN FLATSOME (GIỐNG TINTRUONGTHINH.COM)
         ========================================== -->
    <footer class="bg-[#0b1f33] text-slate-200 pt-10 pb-20 md:pb-10 border-t-4 border-[#c59434]">
        <div class="flatsome-container">
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-6 pb-8 border-b border-slate-700">
                <!-- Cột 1 -->
                <div>
                    <h3 class="text-sm font-extrabold text-white uppercase mb-3">
                        CÔNG TY TNHH TƯ VẤN THIẾT KẾ VÀ XÂY DỰNG ANCI DESIGN
                    </h3>
                    <p class="text-xs text-slate-300 leading-relaxed mb-3">
                        Đơn vị uy tín chuyên Tư vấn Thiết kế Kiến trúc – Thi công Xây dựng – Nội thất trọn gói các công trình Nhà phố, Biệt thự, Căn hộ, Khách sạn, Văn phòng tại Đà Nẵng.
                    </p>
                    <p class="text-xs text-[#c59434] font-semibold">Website: ancidesign.com | MST: 0402288042</p>
                </div>

                <!-- Cột 2 -->
                <div>
                    <h4 class="text-sm font-extrabold text-white uppercase mb-3">Thông Tin Liên Hệ</h4>
                    <ul class="space-y-2 text-xs text-slate-300">
                        <li><strong>Trụ sở:</strong> 44/03 đường K20, Phường Ngũ Hành Sơn, TP Đà Nẵng</li>
                        <li><strong>Hotline 1:</strong> <a href="tel:0325012356" class="text-white font-semibold hover:text-[#c59434]">0325 012 356</a></li>
                        <li><strong>Hotline 2:</strong> <a href="tel:0584168652" class="text-white font-semibold hover:text-[#c59434]">0584 168 652</a></li>
                        <li><strong>Fanpage:</strong> <a href="https://www.facebook.com/Ancidesignandbuilding" target="_blank" rel="noopener noreferrer" class="hover:text-[#c59434] underline">facebook.com/Ancidesignandbuilding</a></li>
                    </ul>
                </div>

                <!-- Cột 3 -->
                <div>
                    <h4 class="text-sm font-extrabold text-white uppercase mb-3">Lĩnh Vực Hoạt Động</h4>
                    <ul class="space-y-2 text-xs text-slate-300">
                        <li><a href="#linh-vuc-hoat-dong" class="hover:text-[#c59434]">• Thiết kế Kiến trúc – Nội thất</a></li>
                        <li><a href="#linh-vuc-hoat-dong" class="hover:text-[#c59434]">• Thi công phần thô</a></li>
                        <li><a href="#linh-vuc-hoat-dong" class="hover:text-[#c59434]">• Thi công hoàn thiện</a></li>
                        <li><a href="#linh-vuc-hoat-dong" class="hover:text-[#c59434]">• Thi công nội thất trọn gói</a></li>
                        <li><a href="#du-an-da-nang" class="hover:text-[#c59434]">• Dự án xây dựng tại Đà Nẵng</a></li>
                    </ul>
                </div>

                <!-- Cột 4 -->
                <div>
                    <h4 class="text-sm font-extrabold text-white uppercase mb-3">Danh Mục Công Trình</h4>
                    <ul class="space-y-2 text-xs text-slate-300">
                        <li><a href="#cong-trinh-thuc-te" onclick="filterConstruction('khach-san-can-ho')" class="hover:text-[#c59434]">• Khách sạn – Căn hộ – Phòng trọ</a></li>
                        <li><a href="#cong-trinh-thuc-te" onclick="filterConstruction('biet-thu')" class="hover:text-[#c59434]">• Biệt thự hiện đại & sân vườn</a></li>
                        <li><a href="#cong-trinh-thuc-te" onclick="filterConstruction('nha-pho')" class="hover:text-[#c59434]">• Nhà phố trọn gói</a></li>
                        <li><a href="#cong-trinh-thuc-te" onclick="filterConstruction('van-phong')" class="hover:text-[#c59434]">• Văn phòng & Showroom</a></li>
                    </ul>
                </div>
            </div>

            <div class="pt-5 text-center text-xs text-slate-400">
                Copyright © 2026 <strong>CÔNG TY TNHH TƯ VẤN THIẾT KẾ VÀ XÂY DỰNG ANCI DESIGN (ancidesign.com)</strong>. All rights reserved.
            </div>
        </div>
    </footer>

    <!-- ==========================================
         CÁC NÚT LIÊN HỆ NỔI BẬT (ZALO, FACEBOOK, HOTLINE) TƯƠNG THÍCH MÁY TÍNH & ĐIỆN THOẠI
         ========================================== -->
    <div class="floating-contact-bar" aria-label="Liên hệ nhanh">
        <a href="https://zalo.me/0325012356" target="_blank" rel="noopener noreferrer"
           class="floating-btn bg-[#0068ff] hover:bg-blue-700">
            <span class="w-6 h-6 rounded-full bg-white text-[#0068ff] flex items-center justify-center font-extrabold text-[11px]">Z</span>
            <span>Chat Zalo: 0325 012 356</span>
        </a>

        <a href="https://www.facebook.com/Ancidesignandbuilding" target="_blank" rel="noopener noreferrer"
           class="floating-btn bg-[#1877F2] hover:bg-blue-800">
            <span class="w-6 h-6 rounded-full bg-white text-[#1877F2] flex items-center justify-center">
                <i class="fa-brands fa-facebook-f text-xs"></i>
            </span>
            <span>Fanpage ANCI Design</span>
        </a>

        <a href="tel:0325012356"
           class="floating-btn bg-[#c59434] hover:bg-[#a6781e]">
            <span class="w-6 h-6 rounded-full bg-white text-[#c59434] flex items-center justify-center">
                <i class="fa-solid fa-phone-volume text-xs"></i>
            </span>
            <span>0325 012 356 – 0584 168 652</span>
        </a>
    </div>

    <!-- ==========================================
         JAVASCRIPT XỬ LÝ SLIDER 2 BANNER, LỌC DANH MỤC, MENU MOBILE & FALLBACK ẢNH DRIVE
         ========================================== -->
    <script>
        // 1. Xử lý dự phòng thông minh cho Logo Google Drive
        function handleLogoFallback(imgEl) {
            const tried = imgEl.getAttribute('data-tried') || '0';
            const id = imgEl.getAttribute('data-drive-id');
            if (tried === '0') {
                imgEl.setAttribute('data-tried', '1');
                imgEl.src = 'https://lh3.googleusercontent.com/d/' + id + '=w400';
            } else {
                // Tạo biểu tượng SVG Logo ANCI DESIGN sắc nét nếu link Drive bị chặn quyền riêng tư
                const svgLogo = `<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 120 120">
                    <rect width="120" height="120" rx="16" fill="#0f2942"/>
                    <path d="M22 86 L60 26 L98 86 Z" fill="none" stroke="#c59434" stroke-width="7" stroke-linejoin="round"/>
                    <path d="M40 86 L60 52 L80 86" fill="none" stroke="#ffffff" stroke-width="5" stroke-linejoin="round"/>
                    <text x="60" y="106" text-anchor="middle" fill="#c59434" font-family="Inter, sans-serif" font-size="18" font-weight="800">ANCI</text>
                </svg>`;
                imgEl.src = 'data:image/svg+xml;utf8,' + encodeURIComponent(svgLogo);
            }
        }

        // 2. Xử lý dự phòng thông minh cho các ảnh Google Drive (thử lh3.googleusercontent.com trước khi dùng ảnh dự phòng)
        function handleDriveImgError(imgEl) {
            const step = imgEl.getAttribute('data-step') || '0';
            const id = imgEl.getAttribute('data-drive-id');
            const fallback = imgEl.getAttribute('data-fallback');
            if (step === '0' && id) {
                imgEl.setAttribute('data-step', '1');
                imgEl.src = 'https://lh3.googleusercontent.com/d/' + id + '=w1000';
            } else if (step !== '2' && fallback) {
                imgEl.setAttribute('data-step', '2');
                imgEl.src = fallback;
            }
        }

        // 3. Tự động trượt 2 Banner chuyên nghiệp
        let currentSlideIndex = 0;
        const slides = document.querySelectorAll('.hero-slide');
        const dots = document.querySelectorAll('.slide-dot');
        let slideInterval = null;

        function showSlide(index) {
            if (index >= slides.length) currentSlideIndex = 0;
            else if (index < 0) currentSlideIndex = slides.length - 1;
            else currentSlideIndex = index;

            slides.forEach((slide, idx) => {
                if (idx === currentSlideIndex) {
                    slide.classList.add('active');
                } else {
                    slide.classList.remove('active');
                }
            });

            dots.forEach((dot, idx) => {
                if (idx === currentSlideIndex) {
                    dot.className = 'slide-dot w-6 h-2 rounded-full bg-[#c59434] transition-all';
                } else {
                    dot.className = 'slide-dot w-2.5 h-2 rounded-full bg-white/60 transition-all';
                }
            });
        }

        function changeSlide(step) {
            showSlide(currentSlideIndex + step);
            restartSlideTimer();
        }

        function goToSlide(index) {
            showSlide(index);
            restartSlideTimer();
        }

        function restartSlideTimer() {
            if (slideInterval) clearInterval(slideInterval);
            slideInterval = setInterval(() => {
                showSlide(currentSlideIndex + 1);
            }, 5000);
        }

        // 4. Lọc danh mục Công trình thực tế
        function filterConstruction(category) {
            const items = document.querySelectorAll('.cons-item');
            const buttons = document.querySelectorAll('.cons-filter-btn');

            buttons.forEach(btn => {
                if (btn.getAttribute('data-filter') === category) {
                    btn.classList.add('active');
                } else {
                    btn.classList.remove('active');
                }
            });

            items.forEach(item => {
                const itemCat = item.getAttribute('data-category');
                if (category === 'all' || itemCat === category) {
                    item.style.display = 'flex';
                } else {
                    item.style.display = 'none';
                }
            });
        }

        // 5. Lọc danh mục Dự án tại Đà Nẵng
        function filterDaNang(area) {
            const items = document.querySelectorAll('.dn-item');
            const buttons = document.querySelectorAll('.dn-filter-btn');

            buttons.forEach(btn => {
                if (btn.getAttribute('data-dn-filter') === area) {
                    btn.classList.add('active');
                } else {
                    btn.classList.remove('active');
                }
            });

            items.forEach(item => {
                const itemArea = item.getAttribute('data-dn');
                if (area === 'all' || itemArea === area) {
                    item.style.display = 'flex';
                } else {
                    item.style.display = 'none';
                }
            });
        }

        // 6. Xử lý gửi Form Báo Giá
        function submitQuoteForm(event) {
            event.preventDefault();
            const name = document.getElementById('cust-name').value.trim();
            const phone = document.getElementById('cust-phone').value.trim();
            const type = document.getElementById('cust-type').value;
            const budget = document.getElementById('cust-budget').value;

            const box = document.getElementById('quote-success-box');
            const detail = document.getElementById('quote-success-detail');
            detail.textContent = `Cảm ơn ${name} (${phone}). Yêu cầu báo giá hạng mục "${type}" (Mức đầu tư: ${budget}) đã được gửi tới bộ phận Tư vấn Thiết kế & Xây dựng ANCI DESIGN. Chúng tôi sẽ liên hệ lại sớm nhất qua số 0325 012 356 – 0584 168 652.`;
            box.classList.remove('hidden');
            document.getElementById('quote-request-form').reset();
        }

        // 7. Khởi tạo sự kiện khi tải trang
        window.onload = function () {
            restartSlideTimer();

            const mobileBtn = document.getElementById('mobile-menu-toggle');
            const mobileDrawer = document.getElementById('mobile-menu-drawer');
            if (mobileBtn && mobileDrawer) {
                mobileBtn.addEventListener('click', () => {
                    mobileDrawer.classList.toggle('hidden');
                });
            }

            document.querySelectorAll('.mobile-nav-link').forEach(link => {
                link.addEventListener('click', () => {
                    if (mobileDrawer) mobileDrawer.classList.add('hidden');
                });
            });
        };
    </script>
</body>
</html>
