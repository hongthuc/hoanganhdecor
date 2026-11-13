<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=5.0">
    <title>Hoàng Phan Decor | Thiết Kế Thi Công Shop Thời Trang, Cửa Hàng & Nội Ngoại Thất Đà Nẵng</title>
    <meta name="description" content="Hoàng Phan Decor (hoanganhdecor.com) chuyên Decor shop thời trang, cửa hàng, showroom, spa và hoàn thiện nội ngoại thất nhà ở, công ty uy tín tại Đà Nẵng. Hotline: 0905.733.107.">
    <meta name="keywords" content="Hoàng Phan Decor, hoanganhdecor.com, thiết kế shop Đà Nẵng, decor shop thời trang Đà Nẵng, thi công nội thất Đà Nẵng, hoàn thiện nội ngoại thất nhà ở công ty">
    <link rel="canonical" href="https://hoanganhdecor.com/">

    <!-- Open Graph / Thumbnail là ảnh Logo trang web khi gửi link qua Zalo, Facebook, Messenger -->
    <meta property="og:type" content="website">
    <meta property="og:site_name" content="Hoàng Phan Decor - hoanganhdecor.com">
    <meta property="og:url" content="https://hoanganhdecor.com/">
    <meta property="og:title" content="Hoàng Phan Decor - Chuyên Decor Shop Thời Trang, Cửa Hàng & Nội Ngoại Thất">
    <meta property="og:description" content="Chuyên thiết kế & thi công trọn gói Shop thời trang, Cửa hàng, Showroom, Spa, hoàn thiện nội ngoại thất nhà ở và công ty tại Đà Nẵng. Hotline: 0905.733.107">
    <meta property="og:image" content="https://drive.google.com/thumbnail?id=1kG1e9D3leasH81M_5yNsKd6mgcFKXgrY&sz=w1200">
    <meta property="og:image:secure_url" content="https://drive.google.com/thumbnail?id=1kG1e9D3leasH81M_5yNsKd6mgcFKXgrY&sz=w1200">
    <meta property="og:image:width" content="1200">
    <meta property="og:image:height" content="630">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:title" content="Hoàng Phan Decor | hoanganhdecor.com">
    <meta name="twitter:description" content="Chuyên Decor shop thời trang, cửa hàng, hoàn thiện nội ngoại thất nhà ở, công ty tại Đà Nẵng.">
    <meta name="twitter:image" content="https://drive.google.com/thumbnail?id=1kG1e9D3leasH81M_5yNsKd6mgcFKXgrY&sz=w1200">
    <link rel="icon" href="https://drive.google.com/thumbnail?id=1kG1e9D3leasH81M_5yNsKd6mgcFKXgrY&sz=w200">

    <!-- Google Fonts: Inter & Montserrat chuẩn Flatsome -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">

    <!-- FontAwesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                    },
                    colors: {
                        brand: {
                            gold: '#C89B3C',
                            goldDark: '#A67B22',
                            goldLight: '#F9F3E5',
                            navy: '#1A2530',
                            charcoal: '#232F3E',
                            accent: '#D97706'
                        }
                    }
                }
            }
        }
    </script>

    <style>
        /* Chống tràn viền và chống lệch phải tuyệt đối trên mọi thiết bị */
        *, *::before, *::after {
            box-sizing: border-box;
        }
        html, body {
            width: 100%;
            max-width: 100%;
            overflow-x: hidden;
            margin: 0;
            padding: 0;
            font-family: 'Inter', sans-serif;
            background-color: #F8FAFC;
            color: #1E293B;
            scroll-behavior: smooth;
        }

        /* Khung giao diện chuẩn Flatsome: 95% chiều ngang trên máy tính, 100% (có padding an toàn) trên điện thoại */
        .flatsome-container {
            width: 100%;
            max-width: 100%;
            padding-left: 12px;
            padding-right: 12px;
            margin-left: auto;
            margin-right: auto;
        }
        @media (min-width: 1024px) {
            .flatsome-container {
                width: 95%;
                max-width: 95%;
                padding-left: 0;
                padding-right: 0;
            }
        }

        /* Danh mục trên máy tính: chữ nhỏ gọn, viết liền trên 1 hàng, không bao giờ bị gãy dòng tên danh mục */
        .desktop-cat-nav {
            display: flex;
            flex-wrap: wrap;
            align-items: center;
            justify-content: center;
            gap: 4px 6px;
        }
        .desktop-cat-link {
            white-space: nowrap;
            font-size: 12px;
            font-weight: 600;
            padding: 6px 10px;
            border-radius: 6px;
            transition: all 0.2s ease;
            line-height: 1.2;
            display: inline-flex;
            align-items: center;
            gap: 5px;
        }
        .desktop-cat-link:hover, .desktop-cat-link.active {
            background-color: #C89B3C;
            color: #ffffff;
        }

        /* Danh mục icon ở trang chủ: chữ nhỏ gọn, không xuống dòng từng từ */
        .home-cat-pill {
            white-space: nowrap;
            overflow: hidden;
            text-overflow: ellipsis;
        }

        /* Tiêu đề Section chuẩn Flatsome UX Builder (Section Title Center) */
        .flatsome-section-title {
            display: flex;
            align-items: center;
            justify-content: space-between;
            border-bottom: 2px solid #E2E8F0;
            padding-bottom: 10px;
            margin-bottom: 20px;
            position: relative;
        }
        .flatsome-section-title::after {
            content: '';
            position: absolute;
            bottom: -2px;
            left: 0;
            width: 140px;
            height: 2px;
            background-color: #C89B3C;
        }

        /* Ảnh sản phẩm đồng nhất tỉ lệ khung hình 4:3 chuẩn Flatsome Box Image */
        .box-image-wrap {
            position: relative;
            width: 100%;
            aspect-ratio: 4 / 3;
            overflow: hidden;
            background-color: #E2E8F0;
            border-radius: 8px 8px 0 0;
        }
        .box-image-wrap img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            transition: transform 0.4s ease;
        }
        .flatsome-product-box:hover .box-image-wrap img {
            transform: scale(1.05);
        }

        /* Tên sản phẩm hiển thị đầy đủ, không bị cắt chữ (...) và không tràn khung */
        .product-title-full {
            white-space: normal;
            word-break: break-word;
            overflow-wrap: break-word;
            line-height: 1.4;
        }

        /* Hiệu ứng rung nhẹ cho nút Hotline/Zalo nổi bật */
        @keyframes pulse-ring {
            0% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(200, 155, 60, 0.7); }
            70% { transform: scale(1); box-shadow: 0 0 0 10px rgba(200, 155, 60, 0); }
            100% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(200, 155, 60, 0); }
        }
        .floating-pulse {
            animation: pulse-ring 2s infinite;
        }
    </style>
</head>
<body class="bg-slate-50 text-slate-800 antialiased">

    <!-- ==========================================
         TOP BAR (Chuẩn Flatsome Top Bar)
    =========================================== -->
    <div class="bg-brand-navy text-slate-200 text-xs py-2 border-b border-slate-700/80">
        <div class="flatsome-container flex flex-wrap items-center justify-between gap-2">
            <div class="flex items-center gap-3 sm:gap-5 truncate">
                <span class="inline-flex items-center gap-1.5 font-medium text-amber-400">
                    <i class="fa-solid fa-globe"></i> hoanganhdecor.com
                </span>
                <span class="hidden md:inline-flex items-center gap-1.5 text-slate-300">
                    <i class="fa-solid fa-location-dot text-amber-400"></i> 12 Huỳnh Thị Bảo Hoà, Phường Hòa Khánh, Tp.Đà Nẵng
                </span>
            </div>
            <div class="flex items-center gap-4 ml-auto">
                <a href="https://www.facebook.com/profile.php?id=100063673654222" target="_blank" rel="noopener noreferrer" class="hover:text-amber-400 transition-colors inline-flex items-center gap-1">
                    <i class="fa-brands fa-facebook"></i> <span class="hidden sm:inline">Fanpage Hoàng Phan Decor</span>
                </a>
                <span class="text-slate-600">|</span>
                <a href="#bang-gia-form" class="hover:text-amber-400 transition-colors font-medium text-amber-300">
                    <i class="fa-solid fa-calculator mr-1"></i>Nhận Báo Giá Thi Công
                </a>
            </div>
        </div>
    </div>

    <!-- ==========================================
         HEADER CHÍNH (Không để nút gọi ngay để tránh tràn viền, Logo nhỏ gọn)
    =========================================== -->
    <header class="bg-white sticky top-0 z-40 shadow-sm border-b border-slate-200">
        <!-- Tầng 1: Logo nhỏ gọn + Thanh tìm kiếm + Menu chính -->
        <div class="flatsome-container py-2.5 flex items-center justify-between gap-3">
            <!-- Logo Hoàng Phan Decor chỉnh gọn nhỏ lại -->
            <a href="#" class="flex items-center gap-2.5 shrink-0 group">
                <div class="w-10 h-10 sm:w-11 sm:h-11 rounded-lg border border-amber-500/40 bg-brand-navy p-0.5 flex items-center justify-center overflow-hidden shrink-0 shadow-sm">
                    <img 
                        src="https://drive.google.com/thumbnail?id=1kG1e9D3leasH81M_5yNsKd6mgcFKXgrY&sz=w400" 
                        onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1kG1e9D3leasH81M_5yNsKd6mgcFKXgrY=w400';"
                        alt="Logo Hoàng Phan Decor" 
                        class="w-full h-full object-contain rounded"
                    >
                </div>
                <div class="leading-tight">
                    <span class="block text-sm sm:text-base md:text-lg font-extrabold tracking-tight text-brand-navy group-hover:text-brand-goldDark transition-colors">
                        HOÀNG PHAN <span class="text-brand-gold">DECOR</span>
                    </span>
                    <span class="block text-[10px] sm:text-[11px] text-slate-500 font-medium">
                        Shop • Cửa Hàng • Nội Ngoại Thất
                    </span>
                </div>
            </a>

            <!-- Ô tìm kiếm danh mục/dự án (Hiển thị trên máy tính) -->
            <div class="hidden md:flex items-center flex-1 max-w-md mx-4">
                <div class="relative w-full">
                    <input 
                        type="text" 
                        id="searchInput"
                        oninput="filterProjectsBySearch(this.value)"
                        placeholder="Tìm mẫu shop thời trang, mỹ phẩm, spa, nội thất..." 
                        class="w-full pl-3.5 pr-9 py-1.5 text-xs bg-slate-100 border border-slate-300 rounded-full focus:outline-none focus:border-brand-gold focus:bg-white transition-all"
                    >
                    <button type="button" aria-label="Tìm kiếm" class="absolute right-3 top-1/2 -translate-y-1/2 text-slate-400 hover:text-brand-gold">
                        <i class="fa-solid fa-magnifying-glass text-xs"></i>
                    </button>
                </div>
            </div>

            <!-- Menu điều hướng trang (Không có nút gọi ngay để tránh tràn viền) -->
            <nav class="hidden xl:flex items-center gap-4 text-xs font-bold uppercase tracking-wide text-slate-700 shrink-0">
                <a href="#trang-chu" class="text-brand-goldDark hover:text-brand-gold transition-colors whitespace-nowrap">Trang Chủ</a>
                <a href="#du-an-da-nang" class="hover:text-brand-gold transition-colors whitespace-nowrap">Dự Án Đà Nẵng</a>
                <a href="#danh-muc-thiet-ke" class="hover:text-brand-gold transition-colors whitespace-nowrap">Thiết Kế Shop</a>
                <a href="#noi-ngoai-that" class="hover:text-brand-gold transition-colors whitespace-nowrap">Nội Ngoại Thất</a>
                <a href="#bang-gia-form" class="hover:text-brand-gold transition-colors whitespace-nowrap">Báo Giá</a>
                <a href="#bai-viet-moi" class="hover:text-brand-gold transition-colors whitespace-nowrap">Tin Tức</a>
                <a href="#lien-he-map" class="hover:text-brand-gold transition-colors whitespace-nowrap">Liên Hệ</a>
            </nav>

            <!-- Nút mở menu danh mục trên điện thoại -->
            <button 
                type="button" 
                onclick="toggleMobileMenu()"
                class="xl:hidden inline-flex items-center gap-1.5 px-3 py-1.5 rounded-lg bg-slate-100 hover:bg-amber-50 text-brand-navy border border-slate-200 text-xs font-bold shrink-0"
                aria-label="Mở danh mục"
            >
                <i class="fa-solid fa-bars text-sm text-brand-goldDark"></i>
                <span>DANH MỤC</span>
            </button>
        </div>

        <!-- Tầng 2: Thanh Danh Mục Sản Phẩm trên máy tính (Chữ nhỏ gọn, viết liền trên 1 hàng hoặc xuống hàng 2, tuyệt đối không gãy chữ trong tên danh mục) -->
        <div class="hidden md:block bg-brand-navy text-white border-t border-slate-800 py-1.5">
            <div class="flatsome-container">
                <div class="desktop-cat-nav" id="desktopCategoryBar">
                    <a href="#danh-muc-thiet-ke" onclick="filterByCategory('all', event)" class="desktop-cat-link active">
                        <i class="fa-solid fa-border-all text-[11px]"></i> Tất Cả Mẫu
                    </a>
                    <a href="#shop-thoi-trang" onclick="filterByCategory('Shop Thời Trang', event)" class="desktop-cat-link">
                        Shop Thời Trang
                    </a>
                    <a href="#shop-my-pham" onclick="filterByCategory('Shop Mỹ Phẩm', event)" class="desktop-cat-link">
                        Shop Mỹ Phẩm
                    </a>
                    <a href="#shop-dien-thoai" onclick="filterByCategory('Shop Điện Thoại', event)" class="desktop-cat-link">
                        Shop Điện Thoại
                    </a>
                    <a href="#shop-phu-kien" onclick="filterByCategory('Shop Phụ Kiện', event)" class="desktop-cat-link">
                        Shop Phụ Kiện
                    </a>
                    <a href="#shop-giay-dep" onclick="filterByCategory('Shop Giày Dép', event)" class="desktop-cat-link">
                        Shop Giày Dép
                    </a>
                    <a href="#thiet-ke-spa" onclick="filterByCategory('Spa & Nail', event)" class="desktop-cat-link">
                        Spa - Tiệm Nail
                    </a>
                    <a href="#salon-toc" onclick="filterByCategory('Salon Tóc', event)" class="desktop-cat-link">
                        Salon Tóc
                    </a>
                    <a href="#studio-ao-cuoi" onclick="filterByCategory('Studio Áo Cưới', event)" class="desktop-cat-link">
                        Studio Áo Cưới
                    </a>
                    <a href="#sieu-thi-mini" onclick="filterByCategory('Siêu Thị Mini', event)" class="desktop-cat-link">
                        Siêu Thị Mini
                    </a>
                    <a href="#showroom" onclick="filterByCategory('Showroom', event)" class="desktop-cat-link">
                        Showroom
                    </a>
                    <a href="#quan-cafe-fnb" onclick="filterByCategory('FnB - Cafe', event)" class="desktop-cat-link">
                        FnB - Cafe
                    </a>
                    <a href="#noi-ngoai-that" onclick="filterByCategory('Nội Ngoại Thất', event)" class="desktop-cat-link">
                        Nội Ngoại Thất Nhà Ở & Công Ty
                    </a>
                    <a href="#du-an-da-nang" class="desktop-cat-link text-amber-300">
                        Công Trình Thực Tế Đà Nẵng
                    </a>
                </div>
            </div>
        </div>

        <!-- Menu Danh Mục Sổ Xuống Trên Điện Thoại -->
        <div id="mobileMenuDrawer" class="hidden xl:hidden bg-white border-t border-slate-200 shadow-lg">
            <div class="flatsome-container py-3 space-y-3">
                <!-- Tìm kiếm trên điện thoại -->
                <div class="relative">
                    <input 
                        type="text" 
                        oninput="filterProjectsBySearch(this.value)"
                        placeholder="Tìm kiếm shop thời trang, nội thất, dự án..." 
                        class="w-full pl-3.5 pr-9 py-2 text-xs bg-slate-100 border border-slate-300 rounded-lg focus:outline-none focus:border-brand-gold"
                    >
                    <i class="fa-solid fa-magnifying-glass text-xs text-slate-400 absolute right-3 top-1/2 -translate-y-1/2"></i>
                </div>
                <!-- Lưới danh mục trên điện thoại -->
                <div class="grid grid-cols-2 sm:grid-cols-3 gap-1.5 text-xs font-semibold text-slate-700">
                    <a href="#du-an-da-nang" onclick="toggleMobileMenu()" class="px-2.5 py-2 rounded bg-amber-50 text-brand-goldDark whitespace-nowrap truncate">• Dự Án Tại Đà Nẵng</a>
                    <a href="#shop-thoi-trang" onclick="toggleMobileMenu()" class="px-2.5 py-2 rounded bg-slate-50 hover:bg-amber-50 whitespace-nowrap truncate">• Shop Thời Trang</a>
                    <a href="#shop-my-pham" onclick="toggleMobileMenu()" class="px-2.5 py-2 rounded bg-slate-50 hover:bg-amber-50 whitespace-nowrap truncate">• Shop Mỹ Phẩm</a>
                    <a href="#shop-dien-thoai" onclick="toggleMobileMenu()" class="px-2.5 py-2 rounded bg-slate-50 hover:bg-amber-50 whitespace-nowrap truncate">• Shop Điện Thoại</a>
                    <a href="#shop-phu-kien" onclick="toggleMobileMenu()" class="px-2.5 py-2 rounded bg-slate-50 hover:bg-amber-50 whitespace-nowrap truncate">• Shop Phụ Kiện</a>
                    <a href="#thiet-ke-spa" onclick="toggleMobileMenu()" class="px-2.5 py-2 rounded bg-slate-50 hover:bg-amber-50 whitespace-nowrap truncate">• Thiết Kế Spa - Nail</a>
                    <a href="#showroom" onclick="toggleMobileMenu()" class="px-2.5 py-2 rounded bg-slate-50 hover:bg-amber-50 whitespace-nowrap truncate">• Thiết Kế Showroom</a>
                    <a href="#noi-ngoai-that" onclick="toggleMobileMenu()" class="px-2.5 py-2 rounded bg-slate-50 hover:bg-amber-50 whitespace-nowrap truncate">• Nội Thất Nhà Ở</a>
                    <a href="#noi-ngoai-that" onclick="toggleMobileMenu()" class="px-2.5 py-2 rounded bg-slate-50 hover:bg-amber-50 whitespace-nowrap truncate">• Nội Thất Công Ty</a>
                    <a href="#bang-gia-form" onclick="toggleMobileMenu()" class="px-2.5 py-2 rounded bg-slate-50 hover:bg-amber-50 whitespace-nowrap truncate">• Bảng Giá & Tư Vấn</a>
                    <a href="#bai-viet-moi" onclick="toggleMobileMenu()" class="px-2.5 py-2 rounded bg-slate-50 hover:bg-amber-50 whitespace-nowrap truncate">• Tin Tức Decor</a>
                    <a href="#lien-he-map" onclick="toggleMobileMenu()" class="px-2.5 py-2 rounded bg-slate-50 hover:bg-amber-50 whitespace-nowrap truncate">• Bản Đồ & Liên Hệ</a>
                </div>
            </div>
        </div>
    </header>

    <!-- ==========================================
         BANNER SLIDER TỰ TRƯỢT (2 SLIDES KÍCH THƯỚC BẰNG NHAU)
         Thiết kế Banner Máy Tính và Banner Điện Thoại TÁCH BIỆT
         để chữ nằm gọn 100% bên trong ảnh banner, không tràn viền
    =========================================== -->
    <section id="trang-chu" class="py-3 md:py-4">
        <div class="flatsome-container">
            <div class="relative rounded-xl overflow-hidden shadow-md bg-brand-navy">

                <!-- 1. BANNER DÀNH RIÊNG CHO MÁY TÍNH (Desktop >= 768px: 2 ảnh kích thước bằng nhau đúng 380px) -->
                <div class="hidden md:block relative w-full h-[360px] lg:h-[400px] overflow-hidden">
                    <!-- Desktop Slide 1 -->
                    <div class="banner-slide-desktop absolute inset-0 w-full h-full transition-opacity duration-700 opacity-100 z-10">
                        <img 
                            src="https://drive.google.com/thumbnail?id=1wv3EVzvsQc5bE_5SE_nSeU9949rs5Ttl&sz=w1600"
                            onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1wv3EVzvsQc5bE_5SE_nSeU9949rs5Ttl=w1600';"
                            alt="Hoàng Phan Decor Thiết Kế Shop Thời Trang & Showroom" 
                            class="w-full h-full object-cover object-center"
                        >
                        <div class="absolute inset-0 bg-gradient-to-r from-brand-navy/95 via-brand-navy/80 to-brand-navy/25 flex items-center">
                            <!-- Khung chữ thu gọn, căn lề an toàn không bao giờ tràn viền -->
                            <div class="w-full max-w-2xl px-10 lg:px-14 py-6 text-white">
                                <p class="inline-block px-3 py-1 rounded bg-brand-gold text-white text-xs font-bold uppercase tracking-wider mb-2.5">
                                    HOÀNG PHAN DECOR • HOANGANHDECOR.COM
                                </p>
                                <h1 class="text-xl lg:text-2xl xl:text-3xl font-extrabold leading-snug mb-2.5 text-white">
                                    CHUYÊN DECOR SHOP THỜI TRANG, CỬA HÀNG & SHOWROOM TRỌN GÓI TẠI ĐÀ NẴNG
                                </h1>
                                <p class="text-xs lg:text-sm text-slate-200 leading-relaxed mb-4 max-w-xl">
                                    Tư vấn giải pháp không gian kinh doanh tối ưu chi phí, xưởng sản xuất trực tiếp tại Hòa Khánh - Đà Nẵng. Miễn phí 100% phí thiết kế 3D khi thi công trọn gói.
                                </p>
                                <div class="flex flex-wrap items-center gap-3 text-xs font-bold">
                                    <a href="#bang-gia-form" class="px-4 py-2.5 rounded-lg bg-brand-gold hover:bg-brand-goldDark text-white transition-colors shadow">
                                        NHẬN BÁO GIÁ NGAY
                                    </a>
                                    <a href="#du-an-da-nang" class="px-4 py-2.5 rounded-lg bg-white/15 hover:bg-white/25 text-white border border-white/30 transition-colors">
                                        XEM CÔNG TRÌNH THỰC TẾ
                                    </a>
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- Desktop Slide 2 (Kích thước bằng tuyệt đối Slide 1) -->
                    <div class="banner-slide-desktop absolute inset-0 w-full h-full transition-opacity duration-700 opacity-0 z-0">
                        <img 
                            src="https://drive.google.com/thumbnail?id=13jgchAVsd5mT8za7XSB8rsvskLKlbKyS&sz=w1600"
                            onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/13jgchAVsd5mT8za7XSB8rsvskLKlbKyS=w1600';"
                            alt="Hoàn Thiện Nội Ngoại Thất Nhà Ở Công Ty Đà Nẵng" 
                            class="w-full h-full object-cover object-center"
                        >
                        <div class="absolute inset-0 bg-gradient-to-r from-brand-navy/95 via-brand-navy/80 to-brand-navy/25 flex items-center">
                            <div class="w-full max-w-2xl px-10 lg:px-14 py-6 text-white">
                                <p class="inline-block px-3 py-1 rounded bg-amber-600 text-white text-xs font-bold uppercase tracking-wider mb-2.5">
                                    THIẾT KẾ & THI CÔNG TRỌN GÓI UY TÍN
                                </p>
                                <h2 class="text-xl lg:text-2xl xl:text-3xl font-extrabold leading-snug mb-2.5 text-white">
                                    HOÀN THIỆN NỘI NGOẠI THẤT NHÀ Ở, VĂN PHÒNG CÔNG TY & BẢNG HIỆU
                                </h2>
                                <p class="text-xs lg:text-sm text-slate-200 leading-relaxed mb-4 max-w-xl">
                                    Địa chỉ: 12 Huỳnh Thị Bảo Hoà, Phường Hòa Khánh, Tp.Đà Nẵng • Hotline: 0905.733.107. Cam kết đúng tiến độ, vật liệu chuẩn, bảo hành dài hạn.
                                </p>
                                <div class="flex flex-wrap items-center gap-3 text-xs font-bold">
                                    <a href="#noi-ngoai-that" class="px-4 py-2.5 rounded-lg bg-brand-gold hover:bg-brand-goldDark text-white transition-colors shadow">
                                        MẪU NỘI NGOẠI THẤT
                                    </a>
                                    <a href="#lien-he-map" class="px-4 py-2.5 rounded-lg bg-white/15 hover:bg-white/25 text-white border border-white/30 transition-colors">
                                        XEM ĐỊA CHỈ XƯỞNG
                                    </a>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- 2. BANNER THIẾT KẾ MỚI DÀNH RIÊNG CHO ĐIỆN THOẠI (Mobile < 768px: 2 ảnh kích thước bằng nhau đúng 230px, chữ nhỏ gọn nằm trọn bên trong) -->
                <div class="block md:hidden relative w-full h-[230px] overflow-hidden">
                    <!-- Mobile Slide 1 -->
                    <div class="banner-slide-mobile absolute inset-0 w-full h-full transition-opacity duration-700 opacity-100 z-10">
                        <img 
                            src="https://drive.google.com/thumbnail?id=1c954dUrUQmmKWRCTfqlZnANCflrRXZAX&sz=w800"
                            onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1c954dUrUQmmKWRCTfqlZnANCflrRXZAX=w800';"
                            alt="Banner Mobile Hoàng Phan Decor 1" 
                            class="w-full h-full object-cover object-center"
                        >
                        <div class="absolute inset-0 bg-brand-navy/80 p-4 flex flex-col justify-center items-center text-center">
                            <span class="px-2.5 py-0.5 rounded bg-brand-gold text-white text-[10px] font-bold uppercase tracking-wide mb-1.5">
                                HOÀNG PHAN DECOR - ĐÀ NẴNG
                            </span>
                            <h2 class="text-sm sm:text-base font-extrabold text-white leading-snug mb-1.5 px-2">
                                CHUYÊN DECOR SHOP THỜI TRANG & CỬA HÀNG TRỌN GÓI
                            </h2>
                            <p class="text-[11px] text-slate-200 leading-normal mb-2.5 px-2">
                                Miễn phí thiết kế 3D • Thi công nhanh tại Đà Nẵng • SĐT: 0905.733.107
                            </p>
                            <a href="#bang-gia-form" class="px-3.5 py-1.5 rounded-md bg-brand-gold text-white text-[11px] font-bold shadow">
                                NHẬN BÁO GIÁ NGAY
                            </a>
                        </div>
                    </div>

                    <!-- Mobile Slide 2 (Kích thước bằng tuyệt đối Mobile Slide 1) -->
                    <div class="banner-slide-mobile absolute inset-0 w-full h-full transition-opacity duration-700 opacity-0 z-0">
                        <img 
                            src="https://drive.google.com/thumbnail?id=1GDsxm71PFzCSGQR4X-e4oQxCIbgAnK86&sz=w800"
                            onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1GDsxm71PFzCSGQR4X-e4oQxCIbgAnK86=w800';"
                            alt="Banner Mobile Hoàng Phan Decor 2" 
                            class="w-full h-full object-cover object-center"
                        >
                        <div class="absolute inset-0 bg-brand-navy/80 p-4 flex flex-col justify-center items-center text-center">
                            <span class="px-2.5 py-0.5 rounded bg-amber-600 text-white text-[10px] font-bold uppercase tracking-wide mb-1.5">
                                HOANGANHDECOR.COM
                            </span>
                            <h2 class="text-sm sm:text-base font-extrabold text-white leading-snug mb-1.5 px-2">
                                HOÀN THIỆN NỘI NGOẠI THẤT NHÀ Ở & CÔNG TY UY TÍN
                            </h2>
                            <p class="text-[11px] text-slate-200 leading-normal mb-2.5 px-2">
                                12 Huỳnh Thị Bảo Hoà, P. Hòa Khánh, Đà Nẵng • Xưởng sản xuất trực tiếp
                            </p>
                            <a href="#du-an-da-nang" class="px-3.5 py-1.5 rounded-md bg-brand-gold text-white text-[11px] font-bold shadow">
                                XEM DỰ ÁN THỰC TẾ
                            </a>
                        </div>
                    </div>
                </div>

                <!-- Nút điều hướng Slide Trái/Phải & Chấm tròn -->
                <button type="button" onclick="prevBannerSlide()" aria-label="Slide trước" class="
```html
absolute left-2.5 top-1/2 -translate-y-1/2 z-20 w-8 h-8 rounded-full bg-black/40 hover:bg-brand-gold text-white flex items-center justify-center transition-colors">
                    <i class="fa-solid fa-chevron-left text-xs"></i>
                </button>
                <button type="button" onclick="nextBannerSlide()" aria-label="Slide tiếp" class="absolute right-2.5 top-1/2 -translate-y-1/2 z-20 w-8 h-8 rounded-full bg-black/40 hover:bg-brand-gold text-white flex items-center justify-center transition-colors">
                    <i class="fa-solid fa-chevron-right text-xs"></i>
                </button>
                <div class="absolute bottom-2.5 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2">
                    <button type="button" onclick="goToBannerSlide(0)" class="banner-dot w-2.5 h-2.5 rounded-full bg-brand-gold transition-all" aria-label="Slide 1"></button>
                    <button type="button" onclick="goToBannerSlide(1)" class="banner-dot w-2.5 h-2.5 rounded-full bg-white/50 transition-all" aria-label="Slide 2"></button>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         DANH MỤC SẢN PHẨM TRANG CHỦ (Lấy danh mục từ Pendecor.vn + Nội ngoại thất Hoàng Phan)
         Chữ danh mục nhỏ gọn, viết liền trên 1 hàng, không bị gãy dòng
    =========================================== -->
    <section class="py-4">
        <div class="flatsome-container">
            <div class="bg-white rounded-xl p-3.5 sm:p-5 shadow-sm border border-slate-200/80">
                <div class="flex items-center justify-between mb-3">
                    <h2 class="text-sm sm:text-base font-extrabold uppercase text-brand-navy flex items-center gap-2">
                        <i class="fa-solid fa-layer-group text-brand-gold"></i>
                        DANH MỤC THIẾT KẾ & THI CÔNG
                    </h2>
                    <span class="text-[11px] text-slate-500 hidden sm:inline">Chọn danh mục để xem nhanh mẫu thiết kế</span>
                </div>

                <!-- Lưới danh mục tối ưu cho cả máy tính (9 cột) và điện thoại (3 cột), tên danh mục gọn trên 1 hàng -->
                <div class="grid grid-cols-3 sm:grid-cols-4 md:grid-cols-6 lg:grid-cols-9 gap-2">
                    <a href="#shop-thoi-trang" class="group flex flex-col items-center justify-center p-2.5 rounded-lg bg-slate-50 hover:bg-brand-goldLight border border-slate-200/70 hover:border-brand-gold transition-all text-center">
                        <i class="fa-solid fa-shirt text-base text-brand-goldDark mb-1.5 group-hover:scale-110 transition-transform"></i>
                        <span class="home-cat-pill w-full text-[11px] font-semibold text-slate-700 group-hover:text-brand-navy">Shop Thời Trang</span>
                    </a>
                    <a href="#shop-my-pham" class="group flex flex-col items-center justify-center p-2.5 rounded-lg bg-slate-50 hover:bg-brand-goldLight border border-slate-200/70 hover:border-brand-gold transition-all text-center">
                        <i class="fa-solid fa-spray-can-sparkles text-base text-brand-goldDark mb-1.5 group-hover:scale-110 transition-transform"></i>
                        <span class="home-cat-pill w-full text-[11px] font-semibold text-slate-700 group-hover:text-brand-navy">Shop Mỹ Phẩm</span>
                    </a>
                    <a href="#shop-dien-thoai" class="group flex flex-col items-center justify-center p-2.5 rounded-lg bg-slate-50 hover:bg-brand-goldLight border border-slate-200/70 hover:border-brand-gold transition-all text-center">
                        <i class="fa-solid fa-mobile-screen-button text-base text-brand-goldDark mb-1.5 group-hover:scale-110 transition-transform"></i>
                        <span class="home-cat-pill w-full text-[11px] font-semibold text-slate-700 group-hover:text-brand-navy">Shop Điện Thoại</span>
                    </a>
                    <a href="#shop-phu-kien" class="group flex flex-col items-center justify-center p-2.5 rounded-lg bg-slate-50 hover:bg-brand-goldLight border border-slate-200/70 hover:border-brand-gold transition-all text-center">
                        <i class="fa-solid fa-glasses text-base text-brand-goldDark mb-1.5 group-hover:scale-110 transition-transform"></i>
                        <span class="home-cat-pill w-full text-[11px] font-semibold text-slate-700 group-hover:text-brand-navy">Shop Phụ Kiện</span>
                    </a>
                    <a href="#shop-giay-dep" class="group flex flex-col items-center justify-center p-2.5 rounded-lg bg-slate-50 hover:bg-brand-goldLight border border-slate-200/70 hover:border-brand-gold transition-all text-center">
                        <i class="fa-solid fa-shoe-prints text-base text-brand-goldDark mb-1.5 group-hover:scale-110 transition-transform"></i>
                        <span class="home-cat-pill w-full text-[11px] font-semibold text-slate-700 group-hover:text-brand-navy">Shop Giày Dép</span>
                    </a>
                    <a href="#thiet-ke-spa" class="group flex flex-col items-center justify-center p-2.5 rounded-lg bg-slate-50 hover:bg-brand-goldLight border border-slate-200/70 hover:border-brand-gold transition-all text-center">
                        <i class="fa-solid fa-spa text-base text-brand-goldDark mb-1.5 group-hover:scale-110 transition-transform"></i>
                        <span class="home-cat-pill w-full text-[11px] font-semibold text-slate-700 group-hover:text-brand-navy">Spa</span>
                    </a>
                    <a href="#thiet-ke-spa" class="group flex flex-col items-center justify-center p-2.5 rounded-lg bg-slate-50 hover:bg-brand-goldLight border border-slate-200/70 hover:border-brand-gold transition-all text-center">
                        <i class="fa-solid fa-hand-sparkles text-base text-brand-goldDark mb-1.5 group-hover:scale-110 transition-transform"></i>
                        <span class="home-cat-pill w-full text-[11px] font-semibold text-slate-700 group-hover:text-brand-navy">Tiệm Nail</span>
                    </a>
                    <a href="#salon-toc" class="group flex flex-col items-center justify-center p-2.5 rounded-lg bg-slate-50 hover:bg-brand-goldLight border border-slate-200/70 hover:border-brand-gold transition-all text-center">
                        <i class="fa-solid fa-scissors text-base text-brand-goldDark mb-1.5 group-hover:scale-110 transition-transform"></i>
                        <span class="home-cat-pill w-full text-[11px] font-semibold text-slate-700 group-hover:text-brand-navy">Salon Tóc</span>
                    </a>
                    <a href="#shop-phu-kien" class="group flex flex-col items-center justify-center p-2.5 rounded-lg bg-slate-50 hover:bg-brand-goldLight border border-slate-200/70 hover:border-brand-gold transition-all text-center">
                        <i class="fa-solid fa-paw text-base text-brand-goldDark mb-1.5 group-hover:scale-110 transition-transform"></i>
                        <span class="home-cat-pill w-full text-[11px] font-semibold text-slate-700 group-hover:text-brand-navy">Pet Shop</span>
                    </a>
                    <a href="#studio-ao-cuoi" class="group flex flex-col items-center justify-center p-2.5 rounded-lg bg-slate-50 hover:bg-brand-goldLight border border-slate-200/70 hover:border-brand-gold transition-all text-center">
                        <i class="fa-solid fa-camera-retro text-base text-brand-goldDark mb-1.5 group-hover:scale-110 transition-transform"></i>
                        <span class="home-cat-pill w-full text-[11px] font-semibold text-slate-700 group-hover:text-brand-navy">Studio Áo Cưới</span>
                    </a>
                    <a href="#sieu-thi-mini" class="group flex flex-col items-center justify-center p-2.5 rounded-lg bg-slate-50 hover:bg-brand-goldLight border border-slate-200/70 hover:border-brand-gold transition-all text-center">
                        <i class="fa-solid fa-basket-shopping text-base text-brand-goldDark mb-1.5 group-hover:scale-110 transition-transform"></i>
                        <span class="home-cat-pill w-full text-[11px] font-semibold text-slate-700 group-hover:text-brand-navy">Siêu Thị Mini</span>
                    </a>
                    <a href="#showroom" class="group flex flex-col items-center justify-center p-2.5 rounded-lg bg-slate-50 hover:bg-brand-goldLight border border-slate-200/70 hover:border-brand-gold transition-all text-center">
                        <i class="fa-solid fa-gem text-base text-brand-goldDark mb-1.5 group-hover:scale-110 transition-transform"></i>
                        <span class="home-cat-pill w-full text-[11px] font-semibold text-slate-700 group-hover:text-brand-navy">Tiệm Vàng</span>
                    </a>
                    <a href="#showroom" class="group flex flex-col items-center justify-center p-2.5 rounded-lg bg-slate-50 hover:bg-brand-goldLight border border-slate-200/70 hover:border-brand-gold transition-all text-center">
                        <i class="fa-solid fa-stethoscope text-base text-brand-goldDark mb-1.5 group-hover:scale-110 transition-transform"></i>
                        <span class="home-cat-pill w-full text-[11px] font-semibold text-slate-700 group-hover:text-brand-navy">Phòng Khám</span>
                    </a>
                    <a href="#sieu-thi-mini" class="group flex flex-col items-center justify-center p-2.5 rounded-lg bg-slate-50 hover:bg-brand-goldLight border border-slate-200/70 hover:border-brand-gold transition-all text-center">
                        <i class="fa-solid fa-capsules text-base text-brand-goldDark mb-1.5 group-hover:scale-110 transition-transform"></i>
                        <span class="home-cat-pill w-full text-[11px] font-semibold text-slate-700 group-hover:text-brand-navy">Nhà Thuốc</span>
                    </a>
                    <a href="#showroom" class="group flex flex-col items-center justify-center p-2.5 rounded-lg bg-slate-50 hover:bg-brand-goldLight border border-slate-200/70 hover:border-brand-gold transition-all text-center">
                        <i class="fa-solid fa-store text-base text-brand-goldDark mb-1.5 group-hover:scale-110 transition-transform"></i>
                        <span class="home-cat-pill w-full text-[11px] font-semibold text-slate-700 group-hover:text-brand-navy">Showroom</span>
                    </a>
                    <a href="#quan-cafe-fnb" class="group flex flex-col items-center justify-center p-2.5 rounded-lg bg-slate-50 hover:bg-brand-goldLight border border-slate-200/70 hover:border-brand-gold transition-all text-center">
                        <i class="fa-solid fa-mug-hot text-base text-brand-goldDark mb-1.5 group-hover:scale-110 transition-transform"></i>
                        <span class="home-cat-pill w-full text-[11px] font-semibold text-slate-700 group-hover:text-brand-navy">FnB - Cafe</span>
                    </a>
                    <a href="#noi-ngoai-that" class="group flex flex-col items-center justify-center p-2.5 rounded-lg bg-slate-50 hover:bg-brand-goldLight border border-slate-200/70 hover:border-brand-gold transition-all text-center">
                        <i class="fa-solid fa-house-chimney text-base text-brand-goldDark mb-1.5 group-hover:scale-110 transition-transform"></i>
                        <span class="home-cat-pill w-full text-[11px] font-semibold text-slate-700 group-hover:text-brand-navy">Nội Thất Nhà Ở</span>
                    </a>
                    <a href="#du-an-da-nang" class="group flex flex-col items-center justify-center p-2.5 rounded-lg bg-slate-50 hover:bg-brand-goldLight border border-slate-200/70 hover:border-brand-gold transition-all text-center">
                        <i class="fa-solid fa-building-circle-check text-base text-brand-goldDark mb-1.5 group-hover:scale-110 transition-transform"></i>
                        <span class="home-cat-pill w-full text-[11px] font-semibold text-slate-700 group-hover:text-brand-navy">Dự Án Đà Nẵng</span>
                    </a>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         SECTION 1: DANH MỤC CÁC DỰ ÁN Ở ĐÀ NẴNG (Ảnh thực tế từ Google Drive)
         Chia 2 cột trên điện thoại, 4 cột trên máy tính, KHÔNG nhãn dán, tên đầy đủ không tràn
    =========================================== -->
    <section id="du-an-da-nang" class="py-5">
        <div class="flatsome-container">
            <div class="flatsome-section-title">
                <h2 class="text-base sm:text-lg md:text-xl font-extrabold uppercase text-brand-navy">
                    CÔNG TRÌNH & DỰ ÁN THỰC TẾ TẠI ĐÀ NẴNG
                </h2>
                <a href="#bang-gia-form" class="text-xs font-bold text-brand-goldDark hover:text-brand-navy whitespace-nowrap">
                    Đăng ký khảo sát <i class="fa-solid fa-arrow-right ml-1"></i>
                </a>
            </div>

            <!-- Grid 2 cột trên điện thoại (grid-cols-2), 4 cột trên máy tính (lg:grid-cols-4) -->
            <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-3 sm:gap-4">
                <!-- Thực tế 1 -->
                <div class="flatsome-product-box bg-white rounded-lg border border-slate-200 shadow-sm hover:shadow-md transition-all flex flex-col">
                    <div class="box-image-wrap">
                        <img 
                            src="https://drive.google.com/thumbnail?id=1wv3EVzvsQc5bE_5SE_nSeU9949rs5Ttl&sz=w800" 
                            onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1wv3EVzvsQc5bE_5SE_nSeU9949rs5Ttl=w800';"
                            alt="Thiết Kế Thi Công Shop Thời Trang Nữ Hiện Đại Tại Hải Châu Đà Nẵng"
                            loading="lazy"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-brand-navy hover:text-brand-goldDark transition-colors">
                                Thiết Kế Thi Công Shop Thời Trang Nữ Hiện Đại Tại Hải Châu Đà Nẵng
                            </h3>
                            <p class="text-[11px] text-slate-500 mt-1">Hạng mục: Quầy thu ngân, kệ treo, ánh sáng & bảng hiệu</p>
                        </div>
                    </div>
                </div>

                <!-- Thực tế 2 -->
                <div class="flatsome-product-box bg-white rounded-lg border border-slate-200 shadow-sm hover:shadow-md transition-all flex flex-col">
                    <div class="box-image-wrap">
                        <img 
                            src="https://drive.google.com/thumbnail?id=13jgchAVsd5mT8za7XSB8rsvskLKlbKyS&sz=w800" 
                            onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/13jgchAVsd5mT8za7XSB8rsvskLKlbKyS=w800';"
                            alt="Hoàn Thiện Nội Thất Cửa Hàng & Tủ Kệ Trưng Bày Tại Liên Chiểu Đà Nẵng"
                            loading="lazy"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-brand-navy hover:text-brand-goldDark transition-colors">
                                Hoàn Thiện Nội Thất Cửa Hàng & Tủ Kệ Trưng Bày Tại Liên Chiểu Đà Nẵng
                            </h3>
                            <p class="text-[11px] text-slate-500 mt-1">Hạng mục: Hệ tủ MDF lõi xanh chống ẩm, đèn LED hắt kệ</p>
                        </div>
                    </div>
                </div>

                <!-- Thực tế 3 -->
                <div class="flatsome-product-box bg-white rounded-lg border border-slate-200 shadow-sm hover:shadow-md transition-all flex flex-col">
                    <div class="box-image-wrap">
                        <img 
                            src="https://drive.google.com/thumbnail?id=1c954dUrUQmmKWRCTfqlZnANCflrRXZAX&sz=w800" 
                            onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1c954dUrUQmmKWRCTfqlZnANCflrRXZAX=w800';"
                            alt="Decor Không Gian Showroom Mỹ Phẩm & Phụ Kiện Tại Thanh Khê Đà Nẵng"
                            loading="lazy"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-brand-navy hover:text-brand-goldDark transition-colors">
                                Decor Không Gian Showroom Mỹ Phẩm & Phụ Kiện Tại Thanh Khê Đà Nẵng
                            </h3>
                            <p class="text-[11px] text-slate-500 mt-1">Hạng mục: Thiết kế 3D, thi công vách logo, đảo trưng bày</p>
                        </div>
                    </div>
                </div>

                <!-- Thực tế 4 -->
                <div class="flatsome-product-box bg-white rounded-lg border border-slate-200 shadow-sm hover:shadow-md transition-all flex flex-col">
                    <div class="box-image-wrap">
                        <img 
                            src="https://drive.google.com/thumbnail?id=1GDsxm71PFzCSGQR4X-e4oQxCIbgAnK86&sz=w800" 
                            onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1GDsxm71PFzCSGQR4X-e4oQxCIbgAnK86=w800';"
                            alt="Thi Công Trọn Gói Cửa Hàng Thời Trang & Bảng Hiệu Quảng Cáo Đà Nẵng"
                            loading="lazy"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-brand-navy hover:text-brand-goldDark transition-colors">
                                Thi Công Trọn Gói Cửa Hàng Thời Trang & Bảng Hiệu Quảng Cáo Đà Nẵng
                            </h3>
                            <p class="text-[11px] text-slate-500 mt-1">Hạng mục: Cải tạo phần thô, mặt tiền Alu chữ nổi, nội thất shop</p>
                        </div>
                    </div>
                </div>

                <!-- Thực tế 5 -->
                <div class="flatsome-product-box bg-white rounded-lg border border-slate-200 shadow-sm hover:shadow-md transition-all flex flex-col">
                    <div class="box-image-wrap">
                        <img 
                            src="https://drive.google.com/thumbnail?id=16jmRHwZqTYGHlB9U-lxin2VZTwobwEUW&sz=w800" 
                            onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/16jmRHwZqTYGHlB9U-lxin2VZTwobwEUW=w800';"
                            alt="Thiết Kế Thi Công Nội Thất Văn Phòng Công Ty Tại Sơn Trà Đà Nẵng"
                            loading="lazy"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-brand-navy hover:text-brand-goldDark transition-colors">
                                Thiết Kế Thi Công Nội Thất Văn Phòng Công Ty Tại Sơn Trà Đà Nẵng
                            </h3>
                            <p class="text-[11px] text-slate-500 mt-1">Hạng mục: Quầy lễ tân, vách ngăn trang trí, bàn làm việc</p>
                        </div>
                    </div>
                </div>

                <!-- Thực tế 6 -->
                <div class="flatsome-product-box bg-white rounded-lg border border-slate-200 shadow-sm hover:shadow-md transition-all flex flex-col">
                    <div class="box-image-wrap">
                        <img 
                            src="https://drive.google.com/thumbnail?id=14J36h1Gn6nJEHu4_yQj4P11p9enPr5pP&sz=w800" 
                            onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/14J36h1Gn6nJEHu4_yQj4P11p9enPr5pP=w800';"
                            alt="Hoàn Thiện Nội Thất Phòng Khách & Tủ Bếp Nhà Phố Hòa Khánh Đà Nẵng"
                            loading="lazy"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-brand-navy hover:text-brand-goldDark transition-colors">
                                Hoàn Thiện Nội Thất Phòng Khách & Tủ Bếp Nhà Phố Hòa Khánh Đà Nẵng
                            </h3>
                            <p class="text-[11px] text-slate-500 mt-1">Hạng mục: Tủ bếp Acrylic, kệ tivi, lam sóng ốp tường</p>
                        </div>
                    </div>
                </div>

                <!-- Thực tế 7 -->
                <div class="flatsome-product-box bg-white rounded-lg border border-slate-200 shadow-sm hover:shadow-md transition-all flex flex-col">
                    <div class="box-image-wrap">
                        <img 
                            src="https://drive.google.com/thumbnail?id=1R6wUU4Ty3YNgLT2JDSuGAsohxJRCAs3c&sz=w800" 
                            onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1R6wUU4Ty3YNgLT2JDSuGAsohxJRCAs3c=w800';"
                            alt="Decor Tiệm Spa & Thẩm Mỹ Viện Phong Cách Hiện Đại Tại Cẩm Lệ Đà Nẵng"
                            loading="lazy"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-brand-navy hover:text-brand-goldDark transition-colors">
                                Decor Tiệm Spa & Thẩm Mỹ Viện Phong Cách Hiện Đại Tại Cẩm Lệ Đà Nẵng
                            </h3>
                            <p class="text-[11px] text-slate-500 mt-1">Hạng mục: Vách uốn cong nghệ thuật, sảnh đón khách, tủ mỹ phẩm</p>
                        </div>
                    </div>
                </div>

                <!-- Thực tế 8 -->
                <div class="flatsome-product-box bg-white rounded-lg border border-slate-200 shadow-sm hover:shadow-md transition-all flex flex-col">
                    <div class="box-image-wrap">
                        <img 
                            src="https://drive.google.com/thumbnail?id=1iDGy3qGrl7B825739Dso1dXUl5N5pjZp&sz=w800" 
                            onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1iDGy3qGrl7B825739Dso1dXUl5N5pjZp=w800';"
                            alt="Thiết Kế Thi Công Shop Điện Thoại & Phụ Kiện Công Nghệ Tại Đà Nẵng"
                            loading="lazy"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-brand-navy hover:text-brand-goldDark transition-colors">
                                Thiết Kế Thi Công Shop Điện Thoại & Phụ Kiện Công Nghệ Tại Đà Nẵng
                            </h3>
                            <p class="text-[11px] text-slate-500 mt-1">Hạng mục: Bàn trải nghiệm, tủ kính trưng bày, bảng hiệu LED</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         SECTION 2: SHOP THỜI TRANG (Giống mẫu Pendecor.vn + Ảnh thực tế Drive)
    =========================================== -->
    <section id="shop-thoi-trang" class="py-5 project-category-section" data-category="Shop Thời Trang">
        <div class="flatsome-container">
            <div class="flatsome-section-title" id="danh-muc-thiet-ke">
                <h2 class="text-base sm:text-lg md:text-xl font-extrabold uppercase text-brand-navy">
                    THIẾT KẾ & DECOR SHOP THỜI TRANG
                </h2>
                <a href="#bang-gia-form" class="text-xs font-bold text-brand-goldDark hover:text-brand-navy whitespace-nowrap">
                    Xem Thêm <i class="fa-solid fa-angle-right ml-1"></i>
                </a>
            </div>

            <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-3 sm:gap-4">
                <div class="flatsome-product-box bg-white rounded-lg border border-slate-200 shadow-sm hover:shadow-md transition-all flex flex-col">
                    <div class="box-image-wrap">
                        <img 
                            src="https://drive.google.com/thumbnail?id=1L-50zH_kYfXmupV2kAK43Ky0Ad6zgRvk&sz=w800" 
                            onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1L-50zH_kYfXmupV2kAK43Ky0Ad6zgRvk=w800';"
                            alt="Thiết Kế Shop Thời Trang Nữ Shochou Boutique"
                            loading="lazy"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1">
                        <h3 class="product-title-full text-xs sm:text-sm font-bold text-brand-navy hover:text-brand-goldDark">
                            Thiết Kế Shop Thời Trang Nữ Shochou Boutique
                        </h3>
                        <p class="text-[11px] text-slate-500 mt-1">Phong cách tối giản, sào treo inox mạ vàng sang trọng</p>
                    </div>
                </div>

                <div class="flatsome-product-box bg-white rounded-lg border border-slate-200 shadow-sm hover:shadow-md transition-all flex flex-col">
                    <div class="box-image-wrap">
                        <img 
                            src="https://drive.google.com/thumbnail?id=1D4UTUkj_2FmCcC9oJMCCwr4mM8YK2j5q&sz=w800" 
                            onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1D4UTUkj_2FmCcC9oJMCCwr4mM8YK2j5q=w800';"
                            alt="Thiết Kế Shop Thời Trang Pháp Phục Như Ý"
                            loading="lazy"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1">
                        <h3 class="product-title-full text-xs sm:text-sm font-bold text-brand-navy hover:text-brand-goldDark">
                            Thiết Kế Shop Thời Trang Pháp Phục Như Ý
                        </h3>
                        <p class="text-[11px] text-slate-500 mt-1">Tông màu gỗ ấm áp kết hợp ánh sáng dịu nhẹ</p>
                    </div>
                </div>

                <div class="flatsome-product-box bg-white rounded-lg border border-slate-200 shadow-sm hover:shadow-md transition-all flex flex-col">
                    <div class="box-image-wrap">
                        <img 
                            src="https://drive.google.com/thumbnail?id=17bzkccO8qBV0nlhzwO1rGdvVLB5Nrx6C&sz=w800" 
                            onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/17bzkccO8qBV0nlhzwO1rGdvVLB5Nrx6C=w800';"
                            alt="Thiết Kế Shop Thể Thao Confident Active Đà Nẵng"
                            loading="lazy"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1">
                        <h3 class="product-title-full text-xs sm:text-sm font-bold text-brand-navy hover:text-brand-goldDark">
                            Thiết Kế Shop Thể Thao Confident Active Đà Nẵng
                        </h3>
                        <p class="text-[11px] text-slate-500 mt-1">Không gian năng động, kệ trưng bày phân khu khoa học</p>
                    </div>
                </div>

                <div class="flatsome-product-box bg-white rounded-lg border border-slate-200 shadow-sm hover:shadow-md transition-all flex flex-col">
                    <div class="box-image-wrap">
                        <img 
                            src="https://drive.google.com/thumbnail?id=1wv3EVzvsQc5bE_5SE_nSeU9949rs5Ttl&sz=w800" 
                            onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1wv3EVzvsQc5bE_5SE_nSeU9949rs5Ttl=w800';"
                            alt="Thi Công Shop Thời Trang Trẻ Em Bebe Mít Kids"
                            loading="lazy"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1">
                        <h3 class="product-title-full text-xs sm:text-sm font-bold text-brand-navy hover:text-brand-goldDark">
                            Thi Công Shop Thời Trang Trẻ Em Bebe Mít Kids
                        </h3>
                        <p class="text-[11px] text-slate-500 mt-1">Tủ kệ bo tròn an toàn, màu sắc pastel nổi bật</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         SECTION 3: SHOP MỸ PHẨM, ĐIỆN THOẠI, PHỤ KIỆN & GIÀY DÉP
    =========================================== -->
    <section id="shop-my-pham" class="py-5 project-category-section" data-category="Shop Mỹ Phẩm">
        <div class="flatsome-container">
            <div class="flatsome-section-title" id="shop-dien-thoai">
                <h2 class="text-base sm:text-lg md:text-xl font-extrabold uppercase text-brand-navy">
                    SHOP MỸ PHẨM • ĐIỆN THOẠI • PHỤ KIỆN • GIÀY DÉP
                </h2>
                <a href="#bang-gia-form" class="text-xs font-bold text-brand-goldDark hover:text-brand-navy whitespace-nowrap">
                    Xem Thêm <i class="fa-solid fa-angle-right ml-1"></i>
                </a>
            </div>

            <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-3 sm:gap-4" id="shop-phu-kien">
                <div class="flatsome-product-box bg-white rounded-lg border border-slate-200 shadow-sm hover:shadow-md transition-all flex flex-col">
                    <div class="box-image-wrap">
                        <img 
                            src="https://drive.google.com/thumbnail?id=1c954dUrUQmmKWRCTfqlZnANCflrRXZAX&sz=w800" 
                            onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1c954dUrUQmmKWRCTfqlZnANCflrRXZAX=w800';"
                            alt="Thiết Kế Shop Mỹ Phẩm Dolami & Chloe Concept"
                            loading="lazy"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1">
                        <h3 class="product-title-full text-xs sm:text-sm font-bold text-brand-navy hover:text-brand-goldDark">
                            Thiết Kế Shop Mỹ Phẩm Dolami & Chloe Concept
                        </h3>
                        <p class="text-[11px] text-slate-500 mt-1">Hệ tủ trưng bày mỹ phẩm có đèn LED chiếu điểm cao cấp</p>
                    </div>
                </div>

                <div class="flatsome-product-box bg-white rounded-lg border border-slate-200 shadow-sm hover:shadow-md transition-all flex flex-col">
                    <div class="box-image-wrap">
                        <img 
                            src="https://drive.google.com/thumbnail?id=1iDGy3qGrl7B825739Dso1dXUl5N5pjZp&sz=w800" 
                            onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1iDGy3qGrl7B825739Dso1dXUl5N5pjZp=w800';"
                            alt="Thiết Kế Shop Điện Thoại TP Mobile & Thiện Apple"
                            loading="lazy"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1">
                        <h3 class="product-title-full text-xs sm:text-sm font-bold text-brand-navy hover:text-brand-goldDark">
                            Thiết Kế Shop Điện Thoại TP Mobile & Thiện Apple
                        </h3>
                        <p class="text-[11px] text-slate-500 mt-1">Tủ trưng bày kính cường lực, bàn trải nghiệm chuẩn hãng</p>
                    </div>
                </div>

                <div class="flatsome-product-box bg-white rounded-lg border border-slate-200 shadow-sm hover:shadow-md transition-all flex flex-col" id="shop-giay-dep">
                    <div class="box-image-wrap">
                        <img 
                            src="https://drive.google.com/thumbnail?id=13jgchAVsd5mT8za7XSB8rsvskLKlbKyS&sz=w800" 
                            onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/13jgchAVsd5mT8za7XSB8rsvskLKlbKyS=w800';"
                            alt="Thiết Kế Cửa Hàng Mắt Kính Camy Eyewears & Phụ Kiện"
                            loading="lazy"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1">
                        <h3 class="product-title-full text-xs sm:text-sm font-bold text-brand-navy hover:text-brand-goldDark">
                            Thiết Kế Cửa Hàng Mắt Kính Camy Eyewears & Phụ Kiện
                        </h3>
                        <p class="text-[11px] text-slate-500 mt-1">Tối ưu diện tích trưng bày với gương soi toàn thân hiện đại</p>
                    </div>
                </div>

                <div class="flatsome-product-box bg-white rounded-lg border border-slate-200 shadow-sm hover:shadow-md transition-all flex flex-col">
                    <div class="box-image-wrap">
                        <img 
                            src="https://drive.google.com/thumbnail?id=1GDsxm71PFzCSGQR4X-e4oQxCIbgAnK86&sz=w800" 
                            onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1GDsxm71PFzCSGQR4X-e4oQxCIbgAnK86=w800';"
                            alt="Thiết Kế Shop Giày Dép La Rose & Sneaker Store"
                            loading="lazy"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1">
                        <h3 class="product-title-full text-xs sm:text-sm font-bold text-brand-navy hover:text-brand-goldDark">
                            Thiết Kế Shop Giày Dép La Rose & Sneaker Store
                        </h3>
                        <p class="text-[11px] text-slate-500 mt-1">Kệ trưng bày giày âm tường kèm ghế thử giày bọc nệm êm</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         SECTION 4: SPA, TIỆM NAIL, SALON TÓC, STUDIO ÁO CƯỚI, SHOWROOM, SIÊU THỊ MINI, FNB
    =========================================== -->
    <section id="thiet-ke-spa" class="py-5 project-category-section" data-category="Spa & Nail">
        <div class="flatsome-container">
            <div class="flatsome-section-title" id="showroom">
                <h2 class="text-base sm:text-lg md:text-xl font-extrabold uppercase text-brand-navy">
                    SPA • TIỆM NAIL • STUDIO ÁO CƯỚI • SHOWROOM • SIÊU THỊ • FNB
                </h2>
                <a href="#bang-gia-form" class="text-xs font-bold text-brand-goldDark hover:text-brand-navy whitespace-nowrap">
                    Xem Thêm <i class="fa-solid fa-angle-right ml-1"></i>
                </a>
            </div>

            <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-3 sm:gap-4" id="studio-ao-cuoi">
                <div class="flatsome-product-box bg-white rounded-lg border border-slate-200 shadow-sm hover:shadow-md transition-all flex flex-col">
                    <div class="box-image-wrap">
                        <img 
                            src="https://drive.google.com/thumbnail?id=1R6wUU4Ty3YNgLT2JDSuGAsohxJRCAs3c&sz=w800" 
                            onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1R6wUU4Ty3YNgLT2JDSuGAsohxJRCAs3c=w800';"
                            alt="Thiết Kế Spa Art Deco Golden Elegance & Tiệm Nail"
                            loading="lazy"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1">
                        <h3 class="product-title-full text-xs sm:text-sm font-bold text-brand-navy hover:text-brand-goldDark">
                            Thiết Kế Spa Art Deco Golden Elegance & Tiệm Nail
                        </h3>
                        <p class="text-[11px] text-slate-500 mt-1">Không gian thư giãn chuẩn 5 sao, vách cong nghệ thuật</p>
                    </div>
                </div>

                <div class="flatsome-product-box bg-white rounded-lg border border-slate-200 shadow-sm hover:shadow-md transition-all flex flex-col" id="salon-toc">
                    <div class="box-image-wrap">
                        <img 
                            src="https://drive.google.com/thumbnail?id=1L-50zH_kYfXmupV2kAK43Ky0Ad6zgRvk&sz=w800" 
                            onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1L-50zH_kYfXmupV2kAK43Ky0Ad6zgRvk=w800';"
                            alt="Thiết Kế Studio Áo Cưới Lin Wedding & Salon Tóc"
                            loading="lazy"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1">
                        <h3 class="product-title-full text-xs sm:text-sm font-bold text-brand-navy hover:text-brand-goldDark">
                            Thiết Kế Studio Áo Cưới Lin Wedding & Salon Tóc
                        </h3>
                        <p class="text-[11px] text-slate-500 mt-1">Sảnh thử váy cưới lộng lẫy kết hợp khu vực makeup chuyên nghiệp</p>
                    </div>
                </div>

                <div class="flatsome-product-box bg-white rounded-lg border border-slate-200 shadow-sm hover:shadow-md transition-all flex flex-col" id="sieu-thi-mini">
                    <div class="box-image-wrap">
                        <img 
                            src="https://drive.google.com/thumbnail?id=1D4UTUkj_2FmCcC9oJMCCwr4mM8YK2j5q&sz=w800" 
                            onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1D4UTUkj_2FmCcC9oJMCCwr4mM8YK2j5q=w800';"
                            alt="Thiết Kế Showroom Trưng Bày & Siêu Thị Mini Bảo An"
                            loading="lazy"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1">
                        <h3 class="product-title-full text-xs sm:text-sm font-bold text-brand-navy hover:text-brand-goldDark">
                            Thiết Kế Showroom Trưng Bày & Siêu Thị Mini Bảo An
                        </h3>
                        <p class="text-[11px] text-slate-500 mt-1">Bố trí lối đi thông thoáng, kệ hàng đa năng tải trọng cao</p>
                    </div>
                </div>

                <div class="flatsome-product-box bg-white rounded-lg border border-slate-200 shadow-sm hover:shadow-md transition-all flex flex-col" id="quan-cafe-fnb">
                    <div class="box-image-wrap">
                        <img 
                            src="https://drive.google.com/thumbnail?id=17bzkccO8qBV0nlhzwO1rGdvVLB5Nrx6C&sz=w800" 
                            onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/17bzkccO8qBV0nlhzwO1rGdvVLB5Nrx6C=w800';"
                            alt="Thiết Kế Quán Cafe, Trà Sữa & Tiệm Bánh FnB Hiện Đại"
                            loading="lazy"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1">
                        <h3 class="product-title-full text-xs sm:text-sm font-bold text-brand-navy hover:text-brand-goldDark">
                            Thiết Kế Quán Cafe, Trà Sữa & Tiệm Bánh FnB Hiện Đại
                        </h3>
                        <p class="text-[11px] text-slate-500 mt-1">Quầy pha chế tiện lợi, góc check-in thu hút khách hàng trẻ</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         SECTION 5: HOÀN THIỆN NỘI NGOẠI THẤT NHÀ Ở & CÔNG TY (Thế mạnh Hoàng Phan Decor)
    =========================================== -->
    <section id="noi-ngoai-that" class="py-5 project-category-section" data-category="Nội Ngoại Thất">
        <div class="flatsome-container">
            <div class="flatsome-section-title">
                <h2 class="text-base sm:text-lg md:text-xl font-extrabold uppercase text-brand-navy">
                    HOÀN THIỆN NỘI NGOẠI THẤT NHÀ Ở & CÔNG TY
                </h2>
                <a href="#bang-gia-form" class="text-xs font-bold text-brand-goldDark hover:text-brand-navy whitespace-nowrap">
                    Nhận Báo Giá <i class="fa-solid fa-angle-right ml-1"></i>
                </a>
            </div>

            <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-3 sm:gap-4">
                <div class="flatsome-product-box bg-white rounded-lg border border-slate-200 shadow-sm hover:shadow-md transition-all flex flex-col">
                    <div class="box-image-wrap">
                        <img 
                            src="https://drive.google.com/thumbnail?id=14J36h1Gn6nJEHu4_yQj4P11p9enPr5pP&sz=w800" 
                            onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/14J36h1Gn6nJEHu4_yQj4P11p9enPr5pP=w800';"
                            alt="Hoàn Thiện Nội Thất Phòng Khách Nhà Phố & Biệt Thự Đà Nẵng"
                            loading="lazy"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1">
                        <h3 class="product-title-full text-xs sm:text-sm font-bold text-brand-navy hover:text-brand-goldDark">
                            Hoàn Thiện Nội Thất Phòng Khách Nhà Phố & Biệt Thự Đà Nẵng
                        </h3>
                        <p class="text-[11px] text-slate-500 mt-1">Thi công vách tivi, trần thạch cao, sàn gỗ và hệ tủ trang trí</p>
                    </div>
                </div>

                <div class="flatsome-product-box bg-white rounded-lg border border-slate-200 shadow-sm hover:shadow-md transition-all flex flex-col">
                    <div class="box-image-wrap">
                        <img 
                            src="https://drive.google.com/thumbnail?id=16jmRHwZqTYGHlB9U-lxin2VZTwobwEUW&sz=w800" 
                            onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/16jmRHwZqTYGHlB9U-lxin2VZTwobwEUW=w800';"
                            alt="Thiết Kế & Thi Công Nội Thất Văn Phòng Công Ty Chuyên Nghiệp"
                            loading="lazy"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1">
                        <h3 class="product-title-full text-xs sm:text-sm font-bold text-brand-navy hover:text-brand-goldDark">
                            Thiết Kế & Thi Công Nội Thất Văn Phòng Công Ty Chuyên Nghiệp
                        </h3>
                        <p class="text-[11px] text-slate-500 mt-1">Tối ưu công năng phòng họp, phòng giám đốc, khu làm việc</p>
                    </div>
                </div>

                <div class="flatsome-product-box bg-white rounded-lg border border-slate-200 shadow-sm hover:shadow-md transition-all flex flex-col">
                    <div class="box-image-wrap">
                        <img 
                            src="https://drive.google.com/thumbnail?id=1R6wUU4Ty3YNgLT2JDSuGAsohxJRCAs3c&sz=w800" 
                            onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1R6wUU4Ty3YNgLT2JDSuGAsohxJRCAs3c=w800';"
                            alt="Thi Công Tủ Bếp & Phòng Ngủ Trọn Gói Căn Hộ Chung Cư"
                            loading="lazy"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1">
                        <h3 class="product-title-full text-xs sm:text-sm font-bold text-brand-navy hover:text-brand-goldDark">
                            Thi Công Tủ Bếp & Phòng Ngủ Trọn Gói Căn Hộ Chung Cư
                        </h3>
                        <p class="text-[11px] text-slate-500 mt-1">Gỗ công nghiệp MDF chống ẩm phủ Melamine/Acrylic cao cấp</p>
                    </div>
                </div>

                <div class="flatsome-product-box bg-white rounded-lg border border-slate-200 shadow-sm hover:shadow-md transition-all flex flex-col">
                    <div class="box-image-wrap">
                        <img 
                            src="https://drive.google.com/thumbnail?id=1GDsxm71PFzCSGQR4X-e4oQxCIbgAnK86&sz=w800" 
                            onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1GDsxm71PFzCSGQR4X-e4oQxCIbgAnK86=w800';"
                            alt="Cải Tạo Mặt Tiền Ngoại Thất & Thi Công Bảng Hiệu Cửa Hàng"
                            loading="lazy"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1">
                        <h3 class="product-title-full text-xs sm:text-sm font-bold text-brand-navy hover:text-brand-goldDark">
                            Cải Tạo Mặt Tiền Ngoại Thất & Thi Công Bảng Hiệu Cửa Hàng
                        </h3>
                        <p class="text-[11px] text-slate-500 mt-1">Ốp mặt dựng Alu, lam nhôm, chữ nổi Inox đèn LED sáng chân</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         SECTION 6: BẢNG GIÁ THIẾT KẾ THI CÔNG & FORM YÊU CẦU BÁO GIÁ TRANG CHỦ
         (Theo cấu trúc Pendecor.vn + Form tương tác trực tiếp)
    =========================================== -->
    <section id="bang-gia-form" class="py-6 bg-slate-100 border-y border-slate-200">
        <div class="flatsome-container">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-5 items-start">
                <!-- Cột Trái (7/12): Bảng giá tham khảo & 6 cam kết vàng giống mẫu Pendecor -->
                <div class="lg:col-span-7 bg-white rounded-xl p-4 sm:p-6 shadow-sm border border-slate-200">
                    <h2 class="text-base sm:text-lg font-extrabold uppercase text-brand-navy mb-3 border-b border-slate-200 pb-2.5">
                        BẢNG GIÁ THIẾT KẾ CỬA HÀNG & THI CÔNG NỘI NGOẠI THẤT
                    </h2>

                    <div class="grid grid-cols-1 sm:grid-cols-2 gap-3 mb-4">
                        <div class="p-3.5 rounded-lg bg-amber-50/70 border border-amber-200">
                            <span class="text-xs font-bold uppercase text-slate-600 block">Chi phí thiết kế & dựng 3D</span>
                            <span class="text-lg sm:text-xl font-extrabold text-brand-goldDark block my-1">150.000 - 250.000đ/m²</span>
                            <span class="text-[11px] text-slate-600 block">Hoàn lại 50% - 100% chi phí thiết kế khi ký hợp đồng thi công trọn gói tại Hoàng Phan Decor.</span>
                        </div>
                        <div class="p-3.5 rounded-lg bg-slate-50 border border-slate-200">
                            <span class="text-xs font-bold uppercase text-slate-600 block">Ngân sách thi công trọn gói</span>
                            <span class="text-lg sm:text-xl font-extrabold text-brand-navy block my-1">3.500.000 - 9.000.000đ/m²</span>
                            <span class="text-[11px] text-slate-600 block">Gồm phần thô (trần, sàn, tường, kính) & nội ngoại thất (tủ kệ, quầy, đèn, bảng hiệu).</span>
                        </div>
                    </div>

                    <div class="space-y-2 text-xs text-slate-600 leading-relaxed mb-4">
                        <p><strong>• Phần thô:</strong> Cải tạo trần, sàn, sơn tường, vách ngăn thạch cao, cửa kính cường lực theo hiện trạng mặt bằng.</p>
                        <p><strong>• Phần nội ngoại thất:</strong> Sản xuất lắp đặt tủ, kệ, sào treo, quầy thu ngân, hệ thống đèn chiếu sáng, rèm, sofa và bảng hiệu quảng cáo mặt tiền.</p>
                    </div>

                    <h3 class="text-xs sm:text-sm font-extrabold uppercase text-brand-navy mb-2.5">
                        TẠI SAO KHÁCH HÀNG CHỌN HOÀNG PHAN DECOR?
                    </h3>
                    <div class="grid grid-cols-2 sm:grid-cols-3 gap-2.5 text-xs">
                        <div class="p-2.5 rounded bg-slate-50 border border-slate-200/80">
                            <i class="fa-solid fa-Screwdriver-wrench text-brand-gold mb-1 block"></i>
                            <strong class="block text-brand-navy">Trọn gói A-Z</strong>
                            <span class="text-[11px] text-slate-500">Từ khảo sát, vẽ 3D đến thi công hoàn thiện.</span>
                        </div>
                        <div class="p-2.5 rounded bg-slate-50 border border-slate-200/80">
                            <i class="fa-solid fa-industry text-brand-gold mb-1 block"></i>
                            <strong class="block text-brand-navy">Xưởng trực tiếp</strong>
                            <span class="text-[11px] text-slate-500">Xưởng tại Hòa Khánh giúp tối ưu 20-30% chi phí.</span>
                        </div>
                        <div class="p-2.5 rounded bg-slate-50 border border-slate-200/80">
                            <i class="fa-solid fa-gift text-brand-gold mb-1 block"></i>
                            <strong class="block text-brand-navy">Miễn phí 3D</strong>
                            <span class="text-[11px] text-slate-500">Trừ 100% phí thiết kế khi thi công trọn gói.</span>
                        </div>
                        <div class="p-2.5 rounded bg-slate-50 border border-slate-200/80">
                            <i class="fa-solid fa-clock-rotate-left text-brand-gold mb-1 block"></i>
                            <strong class="block text-brand-navy">Đúng tiến độ</strong>
                            <span class="text-[11px] text-slate-500">Bàn giao nhanh để khách kịp ngày khai trương.</span>
                        </div>
                        <div class="p-2.5 rounded bg-slate-50 border border-slate-200/80">
                            <i class="fa-solid fa-shield-halved text-brand-gold mb-1 block"></i>
                            <strong class="block text-brand-navy">Bảo hành uy tín</strong>
                            <span class="text-[11px] text-slate-500">Bảo hành 12-24 tháng, hỗ trợ bảo trì tận nơi.</span>
                        </div>
                        <div class="p-2.5 rounded bg-slate-50 border border-slate-200/80">
                            <i class="fa-solid fa-headset text-brand-gold mb-1 block"></i>
                            <strong class="block text-brand-navy">Tư vấn 24/7</strong>
                            <span class="text-[11px] text-slate-500">Khảo sát mặt bằng tận nơi miễn phí tại Đà Nẵng.</span>
                        </div>
                    </div>
                </div>

                <!-- Cột Phải (5/12): Form Yêu Cầu Tư Vấn & Báo Giá Trang Chủ -->
                <div class="lg:col-span-5 bg-brand-navy text-white rounded-xl p-4 sm:p-6 shadow-md">
                    <div class="mb-3">
                        <span class="inline-block px-2.5 py-0.5 rounded bg-brand-gold text-white text-[10px] font-bold uppercase mb-1">
                            NHẬN BÁO GIÁ TRONG 15 PHÚT
                        </span>
                        <h2 class="text-base sm:text-lg font-extrabold uppercase text-white">
                            FORM YÊU CẦU TƯ VẤN & BÁO GIÁ
                        </h2>
                        <p class="text-xs text-slate-300 mt-0.5">
                            Điền thông tin mặt bằng để kỹ sư Hoàng Phan Decor báo giá chi tiết:
                        </p>
                    </div>

                    <form id="quoteRequestForm" onsubmit="submitQuoteForm(event)" class="space-y-3 text-xs">
                        <div>
                            <label class="block font-semibold text-slate-200 mb-1">Họ và tên quý khách *</label>
                            <input 
                                type="text" 
                                id="custName" 
                                required 
                                placeholder="Nhập họ và tên..." 
                                class="w-full px-3 py-2 rounded-lg bg-slate-800 border border-slate-600 text-white placeholder-slate-400 focus:outline-none focus:border-brand-gold"
                            >
                        </div>
                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                            <div>
                                <label class="block font-semibold text-slate-200 mb-1">Số điện thoại / Zalo *</label>
                                <input 
                                    type="tel" 
                                    id="custPhone" 
                                    required 
                                    placeholder="Ví dụ: 0905733107" 
                                    class="w-full px-3 py-2 rounded-lg bg-slate-800 border border-slate-600 text-white placeholder-slate-400 focus:outline-none focus:border-brand-gold"
                                >
                            </div>
                            <div>
                                <label class="block font-semibold text-slate-200 mb-1">Diện tích dự kiến (m²)</label>
                                <input 
                                    type="number" 
                                    id="custArea" 
                                    min="10" 
                                    placeholder="Ví dụ: 45" 
                                    oninput="calculateQuickEstimate()"
                                    class="w-full px-3 py-2 rounded-lg bg-slate-800 border border-slate-600 text-white placeholder-slate-400 focus:outline-none focus:border-brand-gold"
                                >
                            </div>
                        </div>
                        <div>
                            <label class="block font-semibold text-slate-200 mb-1">Hạng mục cần thiết kế - thi công *</label>
                            <select 
                                id="custCategory" 
                                onchange="calculateQuickEstimate()"
                                class="w-full px-3 py-2 rounded-lg bg-slate-800 border border-slate-600 text-white focus:outline-none focus:border-brand-gold"
                            >
                                <option value="Decor Shop Thời Trang">Decor Shop Thời Trang</option>
                                <option value="Thiết Kế Shop Mỹ Phẩm / Phụ Kiện">Thiết Kế Shop Mỹ Phẩm / Phụ Kiện</option>
                                <option value="Thiết Kế Shop Điện Thoại / Showroom">Thiết Kế Shop Điện Thoại / Showroom</option>
                                <option value="Thiết Kế Spa / Tiệm Nail / Salon">Thiết Kế Spa / Tiệm Nail / Salon</option>
                                <option value="Hoàn Thiện Nội Ngoại Thất Nhà Ở">Hoàn Thiện Nội Ngoại Thất Nhà Ở</option>
                                <option value="Hoàn Thiện Nội Thất Văn Phòng Công Ty">Hoàn Thiện Nội Thất Văn Phòng Công Ty</option>
                                <option value="Làm Bảng Hiệu & Cải Tạo Cửa Hàng">Làm Bảng Hiệu & Cải Tạo Cửa Hàng</option>
                            </select>
                        </div>
                        <div>
                            <label class="block font-semibold text-slate-200 mb-1">Địa chỉ công trình & Yêu cầu chi tiết</label>
                            <textarea 
                                id="custNote" 
                                rows="2" 
                                placeholder="Ví dụ: Mặt bằng tại quận Hải Châu, Đà Nẵng, cần tư vấn trọn gói kệ trưng bày và bảng hiệu..." 
                                class="w-full px-3 py-2 rounded-lg bg-slate-800 border border-slate-600 text-white placeholder-slate-400 focus:outline-none focus:border-brand-gold"
                            ></textarea>
                        </div>

                        <!-- Kết quả dự toán tự động -->
                        <div id="quickEstimateBox" class="hidden p-2.5 rounded-lg bg-amber-500/15 border border-amber-400/40 text-amber-200 text-[11px]">
                            <i class="fa-solid fa-calculator mr-1"></i>
                            <span id="quickEstimateText"></span>
                        </div>

                        <button 
                            type="submit" 
                            class="w-full py-2.5 px-4 rounded-lg bg-brand-gold hover:bg-brand-goldDark text-white font-extrabold uppercase tracking-wide transition-colors shadow-md"
                        >
                            <i class="fa-solid fa-paper-plane mr-1.5"></i> GỬI YÊU CẦU & NHẬN BÁO GIÁ
                        </button>
                    </form>

                    <!-- Hộp thông báo xác nhận gửi thành công (thay thế alert) -->
                    <div id="quoteSuccessMessage" class="hidden mt-3 p-3 rounded-lg bg-emerald-600/25 border border-emerald-400 text-emerald-200 text-xs">
                        <p class="font-bold"><i class="fa-solid fa-circle-check mr-1"></i> Đã ghi nhận yêu cầu báo giá!</p>
                        <p class="mt-1 text-[11px]" id="quoteSummaryOutput"></p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         SECTION 7: DANH MỤC CÁC BÀI VIẾT TRANG CHỦ (Blog kinh nghiệm thiết kế shop & nội thất)
    =========================================== -->
    <section id="bai-viet-moi" class="py-5">
        <div class="flatsome-container">
            <div class="flatsome-section-title">
                <h2 class="text-base sm:text-lg md:text-xl font-extrabold uppercase text-brand-navy">
                    TIN TỨC & KINH NGHIỆM DECOR SHOP - NỘI THẤT
                </h2>
                <a href="#bang-gia-form" class="text-xs font-bold text-brand-goldDark hover:text-brand-navy whitespace-nowrap">
                    Tư Vấn Ngay <i class="fa-solid fa-angle-right ml-1"></i>
                </a>
            </div>

            <!-- Chia 2 cột trên điện thoại, 4 cột trên máy tính -->
            <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-4">
                <article class="bg-white rounded-lg border border-slate-200 shadow-sm hover:shadow-md transition-all flex flex-col overflow-hidden">
                    <div class="box-image-wrap">
                        <img 
                            src="https://drive.google.com/thumbnail?id=1wv3EVzvsQc5bE_5SE_nSeU9949rs5Ttl&sz=w600" 
                            onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1wv3EVzvsQc5bE_5SE_nSeU9949rs5Ttl=w600';"
                            alt="Kinh Nghiệm Decor Shop Thời Trang Nhỏ Đẹp Tối Ưu Chi Phí Tại Đà Nẵng"
                            loading="lazy"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-brand-navy hover:text-brand-goldDark">
                                Kinh Nghiệm Decor Shop Thời Trang Nhỏ Đẹp, Tối Ưu Chi Phí Tại Đà Nẵng
                            </h3>
                            <p class="text-[11px] text-slate-500 mt-1.5 line-clamp-2">
                                Bí quyết bố trí ánh sáng, sào treo quần áo và gương soi giúp cửa hàng 20m² - 40m² trông rộng gấp đôi.
                            </p>
                        </div>
                    </div>
                </article>

                <article class="bg-white rounded-lg border border-slate-200 shadow-sm hover:shadow-md transition-all flex flex-col overflow-hidden">
                    <div class="box-image-wrap">
                        <img 
                            src="https://drive.google.com/thumbnail?id=1c954dUrUQmmKWRCTfqlZnANCflrRXZAX&sz=w600" 
                            onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1c954dUrUQmmKWRCTfqlZnANCflrRXZAX=w600';"
                            alt="Top 15+ Mẫu Thiết Kế Cửa Hàng Mỹ Phẩm & Phụ Kiện Thu Hút Khách Hàng"
                            loading="lazy"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-brand-navy hover:text-brand-goldDark">
                                Top 15+ Mẫu Thiết Kế Cửa Hàng Mỹ Phẩm & Phụ Kiện Thu Hút Khách Hàng
                            </h3>
                            <p class="text-[11px] text-slate-500 mt-1.5 line-clamp-2">
                                Lựa chọn chất liệu tủ kệ MDF lõi xanh chống ẩm kết hợp đèn LED thanh giúp tôn vinh giá trị sản phẩm.
                            </p>
                        </div>
                    </div>
                </article>

                <article class="bg-white rounded-lg border border-slate-200 shadow-sm hover:shadow-md transition-all flex flex-col overflow-hidden">
                    <div class="box-image-wrap">
                        <img 
                            src="https://drive.google.com/thumbnail?id=14J36h1Gn6nJEHu4_yQj4P11p9enPr5pP&sz=w600" 
                            onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/14J36h1Gn6nJEHu4_yQj4P11p9enPr5pP=w600';"
                            alt="Báo Giá Hoàn Thiện Nội Ngoại Thất Nhà Ở & Văn Phòng Công Ty Trọn Gói"
                            loading="lazy"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-brand-navy hover:text-brand-goldDark">
                                Báo Giá Hoàn Thiện Nội Ngoại Thất Nhà Ở & Văn Phòng Công Ty Trọn Gói
                            </h3>
                            <p class="text-[11px] text-slate-500 mt-1.5 line-clamp-2">
                                Chi tiết quy trình thi công từ phần thô đến hoàn thiện nội thất gỗ công nghiệp tại xưởng Hòa Khánh.
                            </p>
                        </div>
                    </div>
                </article>

                <article class="bg-white rounded-lg border border-slate-200 shadow-sm hover:shadow-md transition-all flex flex-col overflow-hidden">
                    <div class="box-image-wrap">
                        <img 
                            src="https://drive.google.com/thumbnail?id=1GDsxm71PFzCSGQR4X-e4oQxCIbgAnK86&sz=w600" 
                            onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1GDsxm71PFzCSGQR4X-e4oQxCIbgAnK86=w600';"
                            alt="Cách Thiết Kế Mặt Tiền & Bảng Hiệu Cửa Hàng Chuẩn Phong Thủy Hút Tài Lộc"
                            loading="lazy"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-brand-navy hover:text-brand-goldDark">
                                Cách Thiết Kế Mặt Tiền & Bảng Hiệu Cửa Hàng Chuẩn Phong Thủy Hút Tài Lộc
                            </h3>
                            <p class="text-[11px] text-slate-500 mt-1.5 line-clamp-2">
                                Phối màu thương hiệu, kích thước Lỗ Ban cho quầy thu ngân và bảng hiệu quảng cáo ấn tượng.
                            </p>
                        </div>
                    </div>
                </article>
            </div>
        </div>
    </section>

    <!-- ==========================================
         SECTION 8: DANH MỤC CÁC ĐỐI TÁC (Đối tác vật tư & thương hiệu đồng hành)
    =========================================== -->
    <section id="doi-tac" class="py-5">
        <div class="flatsome-container">
            <div class="bg-white rounded-xl p-4 sm:p-5 border border-slate-200 shadow-sm">
                <div class="flatsome-section-title mb-4">
                    <h2 class="text-base sm:text-lg font-extrabold uppercase text-brand-navy">
                        ĐỐI TÁC VẬT LIỆU & THƯƠNG HIỆU ĐỒNG HÀNH
                    </h2>
                    <span class="text-xs text-slate-500 hidden sm:inline">Cam kết vật tư chính hãng 100%</span>
                </div>

                <div class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-6 gap-2.5 text-center">
                    <div class="p-3 rounded-lg bg-slate-50 border border-slate-200 flex flex-col items-center justify-center">
                        <span class="text-xs sm:text-sm font-extrabold text-brand-navy tracking-wide">GỖ AN CƯỜNG</span>
                        <span class="text-[10px] text-slate-500 mt-0.5">Đối tác gỗ MDF/HDF</span>
                    </div>
                    <div class="p-3 rounded-lg bg-slate-50 border border-slate-200 flex flex-col items-center justify-center">
                        <span class="text-xs sm:text-sm font-extrabold text-brand-navy tracking-wide">SƠN DULUX & JOTUN</span>
                        <span class="text-[10px] text-slate-500 mt-0.5">Sơn nội ngoại thất</span>
                    </div>
                    <div class="p-3 rounded-lg bg-slate-50 border border-slate-200 flex flex-col items-center justify-center">
                        <span class="text-xs sm:text-sm font-extrabold text-brand-navy tracking-wide">HÄFELE & BLUM</span>
                        <span class="text-[10px] text-slate-500 mt-0.5">Phụ kiện tủ kệ cao cấp</span>
                    </div>
                    <div class="p-3 rounded-lg bg-slate-50 border border-slate-200 flex flex-col items-center justify-center">
                        <span class="text-xs sm:text-sm font-extrabold text-brand-navy tracking-wide">VĨNH TƯỜNG</span>
                        <span class="text-[10px] text-slate-500 mt-0.5">Hệ trần & vách thạch cao</span>
                    </div>
                    <div class="p-3 rounded-lg bg-slate-50 border border-slate-200 flex flex-col items-center justify-center">
                        <span class="text-xs sm:text-sm font-extrabold text-brand-navy tracking-wide">RẠNG ĐÔNG & KINGLED</span>
                        <span class="text-[10px] text-slate-500 mt-0.5">Đèn rọi ray & LED shop</span>
                    </div>
                    <div class="p-3 rounded-lg bg-slate-50 border border-slate-200 flex flex-col items-center justify-center">
                        <span class="text-xs sm:text-sm font-extrabold text-brand-navy tracking-wide">NHÔM KÍNH XINGFA</span>
                        <span class="text-[10px] text-slate-500 mt-0.5">Mặt tiền kính cường lực</span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         SECTION 9: ĐƯA ẢNH GOOGLE MAP & FANPAGE RA NGOÀI TRANG CHỦ
    =========================================== -->
    <section id="lien-he-map" class="py-5">
        <div class="flatsome-container">
            <div class="flatsome-section-title">
                <h2 class="text-base sm:text-lg md:text-xl font-extrabold uppercase text-brand-navy">
                    BẢN ĐỒ GOOGLE MAP & FANPAGE HOÀNG PHAN DECOR
                </h2>
                <span class="text-xs font-bold text-brand-goldDark">12 Huỳnh Thị Bảo Hoà, P. Hòa Khánh, Đà Nẵng</span>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-12 gap-4 items-stretch">
                <!-- Cột Google Map ngoài trang chủ (7/12) -->
                <div class="lg:col-span-7 bg-white rounded-xl border border-slate-200 shadow-sm overflow-hidden flex flex-col">
                    <div class="p-3 bg-slate-50 border-b border-slate-200 flex flex-wrap items-center justify-between gap-2">
                        <div class="flex items-center gap-2 text-xs font-bold text-brand-navy">
                            <i class="fa-solid fa-map-location-dot text-brand-gold text-sm"></i>
                            <span>Địa chỉ: 12 Huỳnh Thị Bảo Hoà, Phường Hòa Khánh, Tp.Đà Nẵng</span>
                        </div>
                        <a 
                            href="https://www.google.com/maps/search/?api=1&query=12+Hu%E1%BB%B3nh+Th%E1%BB%8B+B%E1%BA%A3o+H%C3%B2a,+H%C3%B2a+Kh%C3%A1nh,+%C4%90%C3%A0+N%E1%BA%B5ng" 
                            target="_blank" 
                            rel="noopener noreferrer"
                            class="px-2.5 py-1 rounded bg-brand-navy hover:bg-brand-gold text-white text-[11px] font-semibold transition-colors"
                        >
                            <i class="fa-solid fa-diamond-turn-right mr-1"></i> Mở Google Maps Lớn
                        </a>
                    </div>
                    <div class="relative w-full h-[270px] sm:h-[310px] bg-slate-200 flex-1">
                        <iframe 
                            title="Google Map Hoàng Phan Decor 12 Huỳnh Thị Bảo Hoà Đà Nẵng"
                            src="https://maps.google.com/maps?q=12%20Hu%E1%BB%B3nh%20Th%E1%BB%8B%20B%E1%BA%A3o%20H%C3%B2a,%20H%C3%B2a%20Kh%C3%A1nh,%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed" 
                            class="w-full h-full border-0" 
                            allowfullscreen="" 
                            loading="lazy" 
                            referrerpolicy="no-referrer-when-downgrade">
                        </iframe>
                    </div>
                </div>

                <!-- Cột Fanpage Facebook đưa ra ngoài trang chủ (5/12) -->
                <div class="lg:col-span-5 bg-white rounded-xl border border-slate-200 shadow-sm overflow-hidden flex flex-col justify-between p-4">
                    <div>
                        <div class="flex items-center justify-between border-b border-slate-100 pb-3 mb-3">
                            <div class="flex items-center gap-2.5">
                                <img 
                                    src="https://drive.google.com/thumbnail?id=1kG1e9D3leasH81M_5yNsKd6mgcFKXgrY&sz=w200" 
                                    onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1kG1e9D3leasH81M_5yNsKd6mgcFKXgrY=w200';"
                                    alt="Logo Fanpage Hoàng Phan Decor" 
                                    class="w-11 h-11 rounded-full object-contain border border-amber-400 bg-brand-navy p-0.5 shrink-0"
                                >
                                <div>
                                    <h3 class="text-sm font-extrabold text-brand-navy flex items-center gap-1">
                                        Hoàng Phan Decor <i class="fa-solid fa-circle-check text-blue-600 text-xs"></i>
                                    </h3>
                                    <p class="text-[11px] text-slate-500">Chuyên Decor Shop & Nội Ngoại Thất Đà Nẵng</p>
                                </div>
                            </div>
                            <a 
                                href="https://www.facebook.com/profile.php?id=100063673654222" 
                                target="_blank" 
                                rel="noopener noreferrer"
                                class="px-3 py-1.5 rounded-lg bg-[#1877F2] hover:bg-blue-700 text-white text-xs font-bold inline-flex items-center gap-1.5 shadow-sm shrink-0"
                            >
                                <i class="fa-brands fa-facebook-f"></i> Theo Dõi
                            </a>
                        </div>

                        <!-- Khung nhúng trực tiếp Fanpage + Hình ảnh hoạt động thực tế trên Fanpage -->
                        <div class="rounded-lg overflow-hidden border border-slate-200 bg-slate-50 mb-3">
                            <div class="grid grid-cols-3 gap-1 p-1 bg-slate-200">
                                <img 
                                    src="https://drive.google.com/thumbnail?id=1wv3EVzvsQc5bE_5SE_nSeU9949rs5Ttl&sz=w400" 
                                    onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1wv3EVzvsQc5bE_5SE_nSeU9949rs5Ttl=w400';"
                                    alt="Ảnh Fanpage 1" 
                                    class="w-full h-20 object-cover rounded-sm"
                                >
                                <img 
                                    src="https://drive.google.com/thumbnail?id=13jgchAVsd5mT8za7XSB8rsvskLKlbKyS&sz=w400" 
                                    onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/13jgchAVsd5mT8za7XSB8rsvskLKlbKyS=w400';"
                                    alt="Ảnh Fanpage 2" 
                                    class="w-full h-20 object-cover rounded-sm"
                                >
                                <img 
                                    src="https://drive.google.com/thumbnail?id=1c954dUrUQmmKWRCTfqlZnANCflrRXZAX&sz=w400" 
                                    onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1c954dUrUQmmKWRCTfqlZnANCflrRXZAX=w400';"
                                    alt="Ảnh Fanpage 3" 
                                    class="w-full h-20 object-cover rounded-sm"
                                >
                            </div>
                            <div class="p-3 text-xs text-slate-600 space-y-1.5">
                                <p class="font-semibold text-brand-navy">
                                    Cập nhật tiến độ thi công thực tế mỗi ngày trên Fanpage chính thức của Hoàng Phan Decor:
                                </p>
                                <p class="text-[11px]">
                                    • Địa chỉ: 12 Huỳnh Thị Bảo Hoà, Phường Hòa Khánh, Tp.Đà Nẵng<br>
                                    • Hotline / Zalo: <strong class="text-brand-goldDark">0905.733.107</strong><br>
                                    • Website: <strong class="text-brand-navy">hoanganhdecor.com</strong>
                                </p>
                            </div>
                        </div>
                    </div>

                    <div class="grid grid-cols-2 gap-2.5 text-xs font-bold">
                        <a 
                            href="https://www.facebook.com/profile.php?id=100063673654222" 
                            target="_blank" 
                            rel="noopener noreferrer"
                            class="py-2.5 px-3 rounded-lg bg-[#1877F2] hover:bg-blue-700 text-white text-center transition-colors"
                        >
                            <i class="fa-brands fa-facebook mr-1"></i> Mở Trang Fanpage
                        </a>
                        <a 
                            href="https://zalo.me/0905733107" 
                            target="_blank" 
                            rel="noopener noreferrer"
                            class="py-2.5 px-3 rounded-lg bg-brand-gold hover:bg-brand-goldDark text-white text-center transition-colors"
                        >
                            <i class="fa-solid fa-comments mr-1"></i> Nhắn Tin Zalo
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         FOOTER CHUẨN FLATSOME (Đầy đủ thông tin Hoàng Phan Decor & Danh mục Pendecor)
    =========================================== -->
    <footer class="bg-brand-navy text-slate-300 pt-8 pb-6 border-t-4 border-brand-gold mt-4">
        <div class="flatsome-container">
            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-6 pb-6 border-b border-slate-700/80 text-xs">
                <!-- Cột 1: Thông tin công ty -->
                <div>
                    <div class="flex items-center gap-2.5 mb-3">
                        <img 
                            src="https://drive.google.com/thumbnail?id=1kG1e9D3leasH81M_5yNsKd6mgcFKXgrY&sz=w200" 
                            onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1kG1e9D3leasH81M_5yNsKd6mgcFKXgrY=w200';"
                            alt="Logo Hoàng Phan Decor Footer" 
                            class="w-10 h-10 rounded bg-white/10 p-0.5 object-contain border border-amber-400/50"
                        >
                        <div>
                            <h3 class="text-sm font-extrabold text-white uppercase">HOÀNG PHAN DECOR</h3>
                            <p class="text-[11px] text-amber-400">hoanganhdecor.com</p>
                        </div>
                    </div>
                    <p class="leading-relaxed text-slate-300 mb-3">
                        Đơn vị chuyên thiết kế, decor shop thời trang, cửa hàng, showroom, spa và hoàn thiện nội ngoại thất nhà ở, văn phòng công ty uy tín hàng đầu tại Đà Nẵng.
                    </p>
                    <ul class="space-y-1.5 text-slate-200">
                        <li><i class="fa-solid fa-location-dot text-amber-400 mr-1.5"></i> 12 Huỳnh Thị Bảo Hoà, Phường Hòa Khánh, Tp.Đà Nẵng</li>
                        <li><i class="fa-solid fa-phone-volume text-amber-400 mr-1.5"></i> Hotline / Zalo: <a href="tel:0905733107" class="font-bold text-amber-300 hover:underline">0905.733.107</a></li>
                        <li><i class="fa-solid fa-globe text-amber-400 mr-1.5"></i> Website: <a href="https://hoanganhdecor.com" class="hover:text-amber-300">hoanganhdecor.com</a></li>
                    </ul>
                </div>

                <!-- Cột 2: Dự Án Thiết Kế Shop -->
                <div>
                    <h4 class="text-sm font-extrabold text-white uppercase mb-3 border-l-3 border-brand-gold pl-2">
                        DỰ ÁN THIẾT KẾ SHOP
                    </h4>
                    <ul class="grid grid-cols-2 gap-1.5">
                        <li><a href="#shop-thoi-trang" class="hover:text-amber-400">• Shop Thời Trang</a></li>
                        <li><a href="#shop-my-pham" class="hover:text-amber-400">• Shop Mỹ Phẩm</a></li>
                        <li><a href="#shop-dien-thoai" class="hover:text-amber-400">• Shop Điện Thoại</a></li>
                        <li><a href="#shop-phu-kien" class="hover:text-amber-400">• Shop Phụ Kiện</a></li>
                        <li><a href="#shop-giay-dep" class="hover:text-amber-400">• Shop Giày Dép</a></li>
                        <li><a href="#thiet-ke-spa" class="hover:text-amber-400">• Thiết Kế Spa</a></li>
                        <li><a href="#thiet-ke-spa" class="hover:text-amber-400">• Thiết Kế Tiệm Nail</a></li>
                        <li><a href="#salon-toc" class="hover:text-amber-400">• Salon Tóc</a></li>
                        <li><a href="#studio-ao-cuoi" class="hover:text-amber-400">• Studio Áo Cưới</a></li>
                        <li><a href="#sieu-thi-mini" class="hover:text-amber-400">• Siêu Thị Mini</a></li>
                        <li><a href="#showroom" class="hover:text-amber-400">• Showroom</a></li>
                        <li><a href="#quan-cafe-fnb" class="hover:text-amber-400">• Quán Cafe - FnB</a></li>
                    </ul>
                </div>

                <!-- Cột 3: Hoàn Thiện Nội Ngoại Thất -->
                <div>
                    <h4 class="text-sm font-extrabold text-white uppercase mb-3">
                        NỘI NGOẠI THẤT & DỊCH VỤ
                    </h4>
                    <ul class="space-y-1.5">
                        <li><a href="#noi-ngoai-that" class="hover:text-amber-400">• Hoàn thiện nội thất nhà phố, biệt thự</a></li>
                        <li><a href="#noi-ngoai-that" class="hover:text-amber-400">• Thiết kế thi công nội thất văn phòng công ty</a></li>
                        <li><a href="#noi-ngoai-that" class="hover:text-amber-400">• Sản xuất tủ bếp, tủ áo, kệ trưng bày theo yêu cầu</a></li>
                        <li><a href="#du-an-da-nang" class="hover:text-amber-400">• Thi công mặt tiền Alu & bảng hiệu quảng cáo</a></li>
                        <li><a href="#bang-gia-form" class="hover:text-amber-400">• Bảng giá thiết kế & thi công trọn gói</a></li>
                        <li><a href="#du-an-da-nang" class="hover:text-amber-400">• Công trình thực tế tại Đà Nẵng</a></li>
                    </ul>
                </div>

                <!-- Cột 4: Kết nối nhanh -->
                <div>
                    <h4 class="text-sm font-extrabold text-white uppercase mb-3">
                        KẾT NỐI VỚI CHÚNG TÔI
                    </h4>
                    <p class="text-slate-300 mb-3 leading-relaxed">
                        Hỗ trợ tư vấn miễn phí qua Điện Thoại, Zalo và Facebook Messenger suốt 24/7 tại khu vực Đà Nẵng & Miền Trung.
                    </p>
                    <div class="flex flex-wrap items-center gap-2">
                        <a href="https://www.facebook.com/profile.php?id=100063673654222" target="_blank" rel="noopener noreferrer" class="px-3 py-2 rounded bg-[#1877F2] hover:bg-blue-700 text-white font-bold inline-flex items-center gap-1.5">
                            <i class="fa-brands fa-facebook-f"></i> Fanpage
                        </a>
                        <a href="https://zalo.me/0905733107" target="_blank" rel="noopener noreferrer" class="px-3 py-2 rounded bg-sky-500 hover:bg-sky-600 text-white font-bold inline-flex items-center gap-1.5">
                            <i class="fa-solid fa-comment-dots"></i> Zalo: 0905.733.107
                        </a>
                    </div>
                </div>
            </div>

            <div class="pt-4 flex flex-col sm:flex-row items-center justify-between text-[11px] text-slate-400 gap-2 text-center sm:text-left">
                <p>© Bản quyền thuộc về <strong>Hoàng Phan Decor (hoanganhdecor.com)</strong> - Địa chỉ: 12 Huỳnh Thị Bảo Hoà, Phường Hòa Khánh, Tp.Đà Nẵng.</p>
                <p>Hotline tư vấn & báo giá: <strong class="text-amber-400">0905.733.107</strong></p>
            </div>
        </div>
    </footer>

    <!-- ==========================================
         CÁC NÚT LIÊN HỆ NỔI BẬT (ZALO, FACEBOOK, HOTLINE)
         Tương thích hoàn hảo trên cả máy tính và điện thoại, nằm gọn trong khung nhìn
    =========================================== -->
    <div class="fixed bottom-4 right-3 sm:right-5 z-50 flex flex-col items-end gap-2.5">
        <!-- Nút Facebook Fanpage -->
        <a 
            href="https://www.facebook.com/profile.php?id=100063673654222" 
            target="_blank" 
            rel="noopener noreferrer"
            title="Fanpage Hoàng Phan Decor"
            class="flex items-center gap-2 bg-[#1877F2] hover:bg-blue-700 text-white px-3 py-2 rounded-full shadow-lg transition-transform hover:scale-105"
        >
            <i class="fa-brands fa-facebook-f text-sm w-4 text-center"></i>
            <span class="text-xs font-bold pr-1">Facebook</span>
        </a>

        <!-- Nút Chat Zalo -->
        <a 
            href="https://zalo.me/0905733107" 
            target="_blank" 
            rel="noopener noreferrer"
            title="Chat Zalo 0905.733.107"
            class="flex items-center gap-2 bg-[#0068FF] hover:bg-blue-600 text-white px-3 py-2 rounded-full shadow-lg transition-transform hover:scale-105"
        >
            <span class="font-extrabold text-[11px] bg-white text-[#0068FF] px-1.5 py-0.5 rounded-full leading-none">Zalo</span>
            <span class="text-xs font-bold pr-1">Chat Zalo</span>
        </a>

        <!-- Nút Gọi Hotline Nổi Bật -->
        <a 
            href="tel:0905733107" 
            title="Gọi ngay 0905.733.107"
            class="floating-pulse flex items-center gap-2 bg-brand-gold hover:bg-brand-goldDark text-white px-3.5 py-2.5 rounded-full shadow-xl transition-transform hover:scale-105"
        >
            <i class="fa-solid fa-phone-volume text-sm"></i>
            <span class="text-xs sm:text-sm font-extrabold tracking-wide">0905.733.107</span>
        </a>
    </div>

    <!-- ==========================================
         JAVASCRIPT ĐIỀU KHIỂN SLIDER TỰ TRƯỢT, BỘ LỌC & BÁO GIÁ TỰ ĐỘNG
    =========================================== -->
    <script>
        // 1. Tự động trượt 2 Banner trên cả Máy tính và Điện thoại
        let currentSlideIndex = 0;
        const totalBannerSlides = 2;
        let bannerInterval = null;

        function updateBannerDisplay(index) {
            const desktopSlides = document.querySelectorAll('.banner-slide-desktop');
            const mobileSlides = document.querySelectorAll('.banner-slide-mobile');
            const dots = document.querySelectorAll('.banner-dot');

            desktopSlides.forEach((slide, i) => {
                if (i === index) {
                    slide.classList.remove('opacity-0', 'z-0');
                    slide.classList.add('opacity-100', 'z-10');
                } else {
                    slide.classList.remove('opacity-100', 'z-10');
                    slide.classList.add('opacity-0', 'z-0');
                }
            });

            mobileSlides.forEach((slide, i) => {
                if (i === index) {
                    slide.classList.remove('opacity-0', 'z-0');
                    slide.classList.add('opacity-100', 'z-10');
                } else {
                    slide.classList.remove('opacity-100', 'z-10');
                    slide.classList.add('opacity-0', 'z-0');
                }
            });

            dots.forEach((dot, i) => {
                if (i === index) {
                    dot.classList.remove('bg-white/50');
                    dot.classList.add('bg-brand-gold');
                } else {
                    dot.classList.remove('bg-brand-gold');
                    dot.classList.add('bg-white/50');
                }
            });
        }

        function nextBannerSlide() {
            currentSlideIndex = (currentSlideIndex + 1) % totalBannerSlides;
            updateBannerDisplay(currentSlideIndex);
        }

        function prevBannerSlide() {
            currentSlideIndex = (currentSlideIndex - 1 + totalBannerSlides) % totalBannerSlides;
            updateBannerDisplay(currentSlideIndex);
        }

        function goToBannerSlide(index) {
            currentSlideIndex = index;
            updateBannerDisplay(currentSlideIndex);
            resetBannerTimer();
        }

        function resetBannerTimer() {
            if (bannerInterval) clearInterval(bannerInterval);
            bannerInterval = setInterval(nextBannerSlide, 4500);
        }

        // 2. Đóng/mở menu danh mục trên điện thoại
        function toggleMobileMenu() {
            const drawer = document.getElementById('mobileMenuDrawer');
            drawer.classList.toggle('hidden');
        }

        // 3. Lọc nhanh sản phẩm/dự án theo từ khóa tìm kiếm
        function filterProjectsBySearch(keyword) {
            const query = keyword.trim().toLowerCase();
            const cards = document.querySelectorAll('.flatsome-product-box');
            cards.forEach(card => {
                const text = card.innerText.toLowerCase();
                if (!query || text.includes(query)) {
                    card.classList.remove('hidden');
                } else {
                    card.classList.add('hidden');
                }
            });
        }

        // 4. Đánh dấu active trên thanh danh mục máy tính
        function filterByCategory(categoryName, event) {
            const links = document.querySelectorAll('.desktop-cat-link');
            links.forEach(l => l.classList.remove('active'));
            if (event && event.currentTarget) {
                event.currentTarget.classList.add('active');
            }
        }

        // 5. Tính toán nhanh chi phí dự kiến theo diện tích m2 trong Form báo giá
        function calculateQuickEstimate() {
            const areaInput = document.getElementById('custArea');
            const categorySelect = document.getElementById('custCategory');
            const estimateBox = document.getElementById('quickEstimateBox');
            const estimateText = document.getElementById('quickEstimateText');

            const area = parseFloat(areaInput.value);
            if (!area || area <= 0) {
                estimateBox.classList.add('hidden');
                return;
            }

            const designCost = (area * 180000).toLocaleString('vi-VN');
            estimateBox.classList.remove('hidden');
            estimateText.innerHTML = `Dự toán diện tích <strong>${area}m²</strong> (${categorySelect.value}): Phí thiết kế 3D khoảng <strong>${designCost}đ</strong> (Được <strong>miễn phí 100%</strong> khi thi công trọn gói tại Hoàng Phan Decor).`;
        }

        // 6. Xử lý gửi Form yêu cầu báo giá tại trang chủ
        function submitQuoteForm(event) {
            event.preventDefault();
            const name = document.getElementById('custName').value.trim();
            const phone = document.getElementById('custPhone').value.trim();
            const area = document.getElementById('custArea').value.trim() || 'Chưa xác định';
            const category = document.getElementById('custCategory').value;
            const note = document.getElementById('custNote').value.trim();

            const msgBox = document.getElementById('quoteSuccessMessage');
            const summaryOut = document.getElementById('quoteSummaryOutput');

            summaryOut.innerHTML = `Cảm ơn <strong>${name}</strong> (${phone})! Yêu cầu báo giá hạng mục <strong>${category}</strong> (Diện tích: ${area}m² ${note ? '- ' + note : ''}) đã được gửi tới bộ phận kỹ thuật Hoàng Phan Decor. Chúng tôi sẽ liên hệ lại qua SĐT/Zalo <strong>0905.733.107</strong> ngay lập tức.`;
            msgBox.classList.remove('hidden');
            document.getElementById('quoteRequestForm').reset();
            document.getElementById('quickEstimateBox').classList.add('hidden');
        }

        window.onload = function () {
            resetBannerTimer();
        };
    </script>
</body>
</html>
