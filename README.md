<html lang="vi">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=5.0">
  <title>CÔNG TY TNHH THƯƠNG MẠI XÂY DỰNG THIÊN TIẾN - thientien.com | Ke Cân Bằng, Keo Chà Ron Epoxy, Keo Ốp Lát Gạch Đá Đà Nẵng</title>
  <meta name="description" content="CÔNG TY TNHH THƯƠNG MẠI XÂY DỰNG THIÊN TIẾN (thientien.com) - Chuyên Ke Cân Bằng, Keo chà ron Epoxy, Keo ốp lát gạch, đá: Dán cực nhanh, bền đẹp, tiết kiệm nhân công tại 72 Lê Hiến Mai, Hòa Khánh, Đà Nẵng. Hotline: 0966.961.431 - 0901.172.864.">

  <!-- Open Graph / Thumbnail là ảnh Logo trang web khi gửi link chia sẻ -->
  <meta property="og:type" content="website">
  <meta property="og:url" content="https://thientien.com/">
  <meta property="og:site_name" content="thientien.com - VLXD Thiên Tiến Đà Nẵng">
  <meta property="og:title" content="CÔNG TY TNHH THƯƠNG MẠI XÂY DỰNG THIÊN TIẾN - Chuyên Ke Cân Bằng, Keo Chà Ron Epoxy, Keo Ốp Lát Gạch Đá">
  <meta property="og:description" content="Dán cực nhanh, bền đẹp, tiết kiệm nhân công. Địa chỉ: 72 Lê Hiến Mai, Hòa Khánh, Đà Nẵng. ĐT: 0966.961.431 - 0901.172.864">
  <meta property="og:image" content="https://lh3.googleusercontent.com/d/1FRGwVdVqrXcQ0bFAU2c6FB6eHPbnT2y8">
  <meta property="og:image:secure_url" content="https:// drive.google.com/thumbnail?id=1FRGwVdVqrXcQ0bFAU2c6FB6eHPbnT2y8&sz=w800">
  <meta name="twitter:card" content="summary_large_image">
  <meta name="twitter:image" content="https://lh3.googleusercontent.com/d/1FRGwVdVqrXcQ0bFAU2c6FB6eHPbnT2y8">
  <link rel="icon" href="https://lh3.googleusercontent.com/d/1FRGwVdVqrXcQ0bFAU2c6FB6eHPbnT2y8">

  <!-- Tailwind CSS & Font Inter + FontAwesome -->
  <script src="https://cdn.tailwindcss.com"></script>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

  <style>
    /* Reset chuẩn chống tràn viền & chống lệch phải trên mọi thiết bị */
    *, *::before, *::after {
      box-sizing: border-box;
    }
    html, body {
      margin: 0;
      padding: 0;
      width: 100%;
      max-width: 100%;
      overflow-x: hidden;
      font-family: 'Inter', -apple-system, BlinkMacSystemFont, sans-serif;
      background-color: #f4f6f9;
      color: #1e293b;
      scroll-behavior: smooth;
    }

    /* Chiều ngang giao diện trên máy tính bằng 95% kích thước màn hình máy tính, căn giữa tuyệt đối */
    .flatsome-container {
      width: 95%;
      max-width: 95%;
      margin-left: auto;
      margin-right: auto;
    }

    /* Màu chủ đạo theo tông Logo Thiên Tiến & mẫu vlxdthailan.com */
    :root {
      --brand-blue: #004a8f;
      --brand-blue-dark: #00356b;
      --brand-red: #d9232a;
      --brand-green: #00843d;
    }

    /* Tối ưu thanh danh mục trên máy tính: chữ nhỏ gọn, viết liền trên 1 hàng, không xuống dòng trong tên danh mục */
    .desktop-nav-item {
      white-space: nowrap;
      font-size: 12.5px;
      line-height: 1.2;
      padding: 9px 11px;
      font-weight: 600;
      transition: all 0.2s ease;
      display: inline-flex;
      align-items: center;
      gap: 5px;
      border-radius: 6px;
    }
    .desktop-nav-item:hover, .desktop-nav-item.active {
      background-color: rgba(255, 255, 255, 0.16);
      color: #fde047;
    }

    /* Chữ danh mục ở trang chủ nhỏ gọn, không xuống dòng tên danh mục */
    .home-cat-pill {
      white-space: nowrap;
      font-size: 12px;
      font-weight: 600;
      line-height: 1.2;
      transition: all 0.2s ease;
    }

    /* Flatsome Section Title Style (Đơn giản để dựng lại trên UX Builder) */
    .ux-section-title {
      display: flex;
      align-items: center;
      justify-content: space-between;
      border-bottom: 2px solid #004a8f;
      margin-bottom: 16px;
      background: #ffffff;
      border-radius: 8px 8px 0 0;
      padding: 10px 14px;
    }
    .ux-section-title h2 {
      margin: 0;
      font-size: 15px;
      font-weight: 800;
      text-transform: uppercase;
      color: #004a8f;
      display: flex;
      align-items: center;
      gap: 8px;
    }
    @media (min-width: 768px) {
      .ux-section-title h2 {
        font-size: 17px;
      }
    }

    /* Flatsome Sale Bubble góc trên bên trái */
    .flatsome-badge-sale {
      position: absolute;
      top: 8px;
      left: 8px;
      z-index: 10;
      background-color: #d9232a;
      color: #ffffff;
      font-weight: 700;
      font-size: 11px;
      width: 38px;
      height: 38px;
      border-radius: 9999px;
      display: flex;
      align-items: center;
      justify-content: center;
      box-shadow: 0 2px 6px rgba(217, 35, 42, 0.35);
      line-height: 1;
    }

    /* Thẻ sản phẩm Flatsome Box: Tên sản phẩm hiển thị đầy đủ, không bị tràn hoặc thiếu chữ */
    .product-box {
      background: #ffffff;
      border: 1px solid #e2e8f0;
      border-radius: 8px;
      overflow: hidden;
      display: flex;
      flex-direction: column;
      height: 100%;
      transition: transform 0.2s ease, box-shadow 0.2s ease;
    }
    .product-box:hover {
      transform: translateY(-3px);
      box-shadow: 0 8px 20px rgba(0, 74, 143, 0.12);
      border-color: #93c5fd;
    }
    .product-title-full {
      font-size: 13px;
      line-height: 1.4;
      font-weight: 600;
      color: #1e293b;
      word-break: break-word;
      overflow-wrap: break-word;
      white-space: normal;
      margin-bottom: 6px;
    }
    @media (min-width: 768px) {
      .product-title-full {
        font-size: 13.5px;
      }
    }

    /* Banner Slider bằng nhau tuyệt đối trên cả điện thoại và máy tính */
    .banner-viewport {
      position: relative;
      width: 100%;
      height: 300px;
      border-radius: 10px;
      overflow: hidden;
    }
    @media (min-width: 640px) {
      .banner-viewport {
        height: 340px;
      }
    }
    @media (min-width: 1024px) {
      .banner-viewport {
        height: 390px;
      }
    }
    .banner-slide {
      position: absolute;
      inset: 0;
      width: 100%;
      height: 100%;
      opacity: 0;
      pointer-events: none;
      transition: opacity 0.6s ease-in-out;
    }
    .banner-slide.active {
      opacity: 1;
      pointer-events: auto;
      z-index: 5;
    }

    /* Nút liên hệ nổi bật hiệu ứng sóng */
    @keyframes pulseRing {
      0% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(217, 35, 42, 0.6); }
      70% { transform: scale(1); box-shadow: 0 0 0 10px rgba(217, 35, 42, 0); }
      100% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(217, 35, 42, 0); }
    }
    .pulse-btn {
      animation: pulseRing 2s infinite;
    }
  </style>
</head>
<body>

  <!-- =====================================================================
       1. TOP BAR (Đơn giản chuẩn Flatsome - Không có thanh UX Builder)
       ===================================================================== -->
  <div class="bg-[#00356b] text-white text-xs py-1.5 border-b border-blue-800">
    <div class="flatsome-container flex flex-wrap items-center justify-between gap-2">
      <div class="flex items-center gap-2 truncate">
        <span class="font-semibold text-yellow-300"><i class="fa-solid fa-building-shield mr-1"></i>CÔNG TY TNHH THƯƠNG MẠI XÂY DỰNG THIÊN TIẾN</span>
        <span class="hidden lg:inline text-blue-200">|</span>
        <span class="hidden lg:inline text-blue-100">Chuyên Ke Cân Bằng, Keo Chà Ron Epoxy, Keo Ốp Lát Gạch, Đá</span>
      </div>
      <div class="flex items-center gap-3 text-[11.5px] sm:text-xs">
        <span class="hidden sm:inline-flex items-center gap-1 text-blue-100">
          <i class="fa-solid fa-location-dot text-yellow-400"></i> 72 Lê Hiến Mai, Hòa Khánh, Đà Nẵng
        </span>
        <span class="text-blue-300 hidden sm:inline">|</span>
        <a href="https://thientien.com" class="text-yellow-300 font-semibold hover:underline">thientien.com</a>
      </div>
    </div>
  </div>

  <!-- =====================================================================
       2. HEADER CHÍNH (Logo gọn nhỏ, Không để nút Gọi ngay để tránh tràn viền)
       ===================================================================== -->
  <header class="bg-white shadow-sm sticky top-0 z-40">
    <div class="flatsome-container py-2.5 flex items-center justify-between gap-3">
      
      <!-- Logo Thiên Tiến chỉnh gọn nhỏ lại -->
      <a href="#top" class="flex items-center gap-2.5 shrink-0 group">
        <div class="w-11 h-11 md:w-12 md:h-12 rounded-lg border border-slate-200 bg-white p-0.5 flex items-center justify-center overflow-hidden shrink-0 shadow-xs">
          <img 
            src="https://lh3.googleusercontent.com/d/1FRGwVdVqrXcQ0bFAU2c6FB6eHPbnT2y8" 
            alt="Logo Công Ty TNHH Thương Mại Xây Dựng Thiên Tiến" 
            class="w-full h-full object-contain"
            onerror="handleDriveImageFallback(this, '1FRGwVdVqrXcQ0bFAU2c6FB6eHPbnT2y8', 'THIÊN TIẾN')"
          >
        </div>
        <div class="min-w-0">
          <div class="text-xs sm:text-sm md:text-base font-extrabold text-[#004a8f] leading-tight tracking-tight truncate">
            VLXD THIÊN TIẾN
          </div>
          <div class="text-[10.5px] sm:text-xs font-semibold text-[#d9232a] leading-tight truncate">
            thientien.com • Đà Nẵng
          </div>
        </div>
      </a>

      <!-- Thanh tìm kiếm sản phẩm (Giống vlxdthailan.com) -->
      <div class="flex-1 max-w-xl mx-1 sm:mx-4">
        <form onsubmit="handleSearchSubmit(event)" class="relative flex items-center w-full">
          <input 
            id="searchInput"
            type="text" 
            placeholder="Tìm ke cân bằng, keo chà ron Epoxy, keo dán gạch Cá Sấu..." 
            class="w-full text-xs sm:text-sm bg-slate-100 border border-slate-300 rounded-l-lg py-2 px-3 focus:outline-none focus:border-[#004a8f] focus:bg-white text-slate-800"
          >
          <button 
            type="submit" 
            aria-label="Tìm kiếm"
            class="bg-[#004a8f] hover:bg-[#00356b] text-white px-3.5 py-2 rounded-r-lg text-xs sm:text-sm font-semibold transition shrink-0"
          >
            <i class="fa-solid fa-magnifying-glass"></i>
          </button>
        </form>
      </div>

      <!-- Thông tin địa chỉ ngắn trên máy tính & Nút mở Menu trên điện thoại (Không để nút Gọi ngay trên Header) -->
      <div class="hidden xl:flex items-center gap-4 text-xs text-slate-600 shrink-0">
        <a href="#bando-fanpage" class="flex items-center gap-1.5 hover:text-[#004a8f] font-medium">
          <i class="fa-solid fa-map-location-dot text-[#004a8f] text-base"></i>
          <span>72 Lê Hiến Mai, Đà Nẵng</span>
        </a>
        <a href="#baogia" class="bg-slate-100 hover:bg-slate-200 text-[#004a8f] font-bold px-3 py-2 rounded-lg transition">
          <i class="fa-solid fa-file-invoice mr-1"></i>Nhận Báo Giá
        </a>
      </div>

      <!-- Nút mở Danh mục trên Điện Thoại -->
      <button 
        type="button" 
        onclick="toggleMobileMenu()" 
        class="lg:hidden bg-[#004a8f] text-white px-3 py-2 rounded-lg text-xs font-bold flex items-center gap-1.5 shrink-0"
        aria-label="Mở danh mục"
      >
        <i class="fa-solid fa-bars text-sm"></i>
        <span>DANH MỤC</span>
      </button>
    </div>

    <!-- ===================================================================
         3. THANH DANH MỤC TRÊN MÁY TÍNH (Chữ nhỏ gọn, viết liền trên 1 hàng
            hoặc xuống hàng 2 nguyên cụm, tuyệt đối không xuống dòng tên danh mục)
         =================================================================== -->
    <nav class="hidden lg:block bg-[#004a8f] text-white border-t border-blue-900">
      <div class="flatsome-container py-1 flex flex-wrap items-center justify-start gap-x-1 gap-y-1">
        <a href="#top" onclick="filterByCategory('all')" class="desktop-nav-item active">
          <i class="fa-solid fa-house"></i> TRANG CHỦ
        </a>
        <a href="#ve-chung-toi" class="desktop-nav-item">
          VỀ CHÚNG TÔI
        </a>
        <a href="#san-pham" onclick="filterByCategory('ke-can-bang')" class="desktop-nav-item">
          <i class="fa-solid fa-border-all text-yellow-300"></i> KE CÂN BẰNG & DỤNG CỤ ỐP LÁT
        </a>
        <a href="#san-pham" onclick="filterByCategory('keo-cha-ron')" class="desktop-nav-item">
          <i class="fa-solid fa-wand-magic-sparkles text-yellow-300"></i> KEO CHÀ RON / KEO CHÍT MẠCH EPOXY
        </a>
        <a href="#san-pham" onclick="filterByCategory('keo-dan-gach')" class="desktop-nav-item">
          <i class="fa-solid fa-layer-group text-yellow-300"></i> KEO DÁN GẠCH ĐÁ
        </a>
        <a href="#san-pham" onclick="filterByCategory('chong-tham')" class="desktop-nav-item">
          <i class="fa-solid fa-shield-halved text-yellow-300"></i> CHỐNG THẤM
        </a>
        <a href="#san-pham" onclick="filterByCategory('hoa-chat')" class="desktop-nav-item">
          <i class="fa-solid fa-flask text-yellow-300"></i> HOÁ CHẤT XÂY DỰNG
        </a>
        <a href="#cua-hang" class="desktop-nav-item">
          HÌNH ẢNH CỬA HÀNG
        </a>
        <a href="#doi-tac" class="desktop-nav-item">
          ĐỐI TÁC
        </a>
        <a href="#tin-tuc" class="desktop-nav-item">
          TIN TỨC
        </a>
        <a href="#baogia" class="desktop-nav-item">
          BÁO GIÁ & LIÊN HỆ
        </a>
      </div>
    </nav>

    <!-- ===================================================================
         DANH MỤC MENU TRÊN ĐIỆN THOẠI (Thiết kế gọn đẹp, dễ bấm)
         =================================================================== -->
    <div id="mobileMenuDrawer" class="hidden lg:hidden bg-white border-t border-slate-200 shadow-lg">
      <div class="flatsome-container py-3">
        <div class="text-xs font-bold text-slate-400 uppercase mb-2 px-1">Danh mục sản phẩm & Trang</div>
        <div class="grid grid-cols-2 gap-2 text-xs font-semibold">
          <a href="#san-pham" onclick="filterByCategory('all'); toggleMobileMenu();" class="p-2.5 rounded-lg bg-blue-50 text-[#004a8f] flex items-center gap-2">
            <i class="fa-solid fa-grip"></i> Tất Cả Sản Phẩm
          </a>
          <a href="#san-pham" onclick="filterByCategory('ke-can-bang'); toggleMobileMenu();" class="p-2.5 rounded-lg bg-slate-100 text-slate-800 flex items-center gap-2">
            <i class="fa-solid fa-border-all text-[#004a8f]"></i> Ke Cân Bằng Gạch
          </a>
          <a href="#san-pham" onclick="filterByCategory('keo-cha-ron'); toggleMobileMenu();" class="p-2.5 rounded-lg bg-slate-100 text-slate-800 flex items-center gap-2">
            <i class="fa-solid fa-fill-drip text-[#d9232a]"></i> Keo Chà Ron Epoxy
          </a>
          <a href="#san-pham" onclick="filterByCategory('keo-dan-gach'); toggleMobileMenu();" class="p-2.5 rounded-lg bg-slate-100 text-slate-800 flex items-center gap-2">
            <i class="fa-solid fa-layer-group text-[#00843d]"></i> Keo Dán Gạch Đá
          </a>
          <a href="#san-pham" onclick="filterByCategory('chong-tham'); toggleMobileMenu();" class="p-2.5 rounded-lg bg-slate-100 text-slate-800 flex items-center gap-2">
            <i class="fa-solid fa-droplet-slash text-blue-600"></i> Chống Thấm
          </a>
          <a href="#san-pham" onclick="filterByCategory('hoa-chat'); toggleMobileMenu();" class="p-2.5 rounded-lg bg-slate-100 text-slate-800 flex items-center gap-2">
            <i class="fa-solid fa-flask text-amber-600"></i> Hoá Chất Xây Dựng
          </a>
          <a href="#cua-hang" onclick="toggleMobileMenu();" class="p-2.5 rounded-lg bg-slate-100 text-slate-800 flex items-center gap-2">
            <i class="fa-solid fa-store text-[#004a8f]"></i> Ảnh Cửa Hàng
          </a>
          <a href="#doi-tac" onclick="toggleMobileMenu();" class="p-2.5 rounded-lg bg-slate-100 text-slate-800 flex items-center gap-2">
            <i class="fa-solid fa-handshake text-[#004a8f]"></i> Đối Tác Phân Phối
          </a>
          <a href="#tin-tuc" onclick="toggleMobileMenu();" class="p-2.5 rounded-lg bg-slate-100 text-slate-800 flex items-center gap-2">
            <i class="fa-solid fa-newspaper text-[#004a8f]"></i> Bài Viết Mới
          </a>
          <a href="#baogia" onclick="toggleMobileMenu();" class="p-2.5 rounded-lg bg-[#d9232a] text-white flex items-center gap-2">
            <i class="fa-solid fa-paper-plane"></i> Yêu Cầu Báo Giá
          </a>
        </div>
      </div>
    </div>
  </header>

  <!-- =====================================================================
       4. 2 ẢNH BANNER TỰ TRƯỢT CHUYÊN NGHIỆP KÍCH THƯỚC BẰNG NHAU
          (Hình ảnh & chữ nằm trọn trong banner, chữ cách xa viền, không mất chữ)
       ===================================================================== -->
  <section id="top" class="mt-3">
    <div class="flatsome-container">
      <div class="banner-viewport shadow-md">

        <!-- SLIDE 1: Chuyên Ke Cân Bằng, Keo Chà Ron Epoxy, Keo Ốp Lát Gạch Đá -->
        <div class="banner-slide active bg-gradient-to-r from-[#002f5f] via-[#004a8f] to-[#0066b2] text-white flex items-center">
          <!-- Khoảng đệm px-6 sm:px-12 md:px-16 giữ chữ cách xa viền ảnh banner -->
          <div class="w-full h-full px-6 py-5 sm:px-12 md:px-16 md:py-8 grid grid-cols-1 md:grid-cols-12 items-center gap-4">
            <div class="md:col-span-7 flex flex-col justify-center space-y-2 sm:space-y-3">
              <div class="inline-flex items-center gap-2 bg-yellow-400 text-[#00356b] font-extrabold text-[11px] sm:text-xs px-3 py-1 rounded-full w-fit">
                <span>THIENTIEN.COM • VLXD THIÊN TIẾN ĐÀ NẴNG</span>
              </div>
              <h1 class="text-base sm:text-2xl lg:text-3xl font-extrabold leading-snug text-white">
                CÔNG TY TNHH THƯƠNG MẠI XÂY DỰNG THIÊN TIẾN
              </h1>
              <p class="text-xs sm:text-sm lg:text-base text-yellow-300 font-bold leading-relaxed">
                Chuyên Ke Cân Bằng, Keo Chà Ron Epoxy, Keo Ốp Lát Gạch, Đá: Dán Cực Nhanh – Bền Đẹp – Tiết Kiệm Nhân Công
              </p>
              <div class="text-[11px] sm:text-xs text-blue-100 space-y-1 pt-0.5">
                <div><i class="fa-solid fa-location-dot text-yellow-400 mr-1.5"></i>Địa chỉ: 72 Lê Hiến Mai, Hòa Khánh, Đà Nẵng</div>
                <div><i class="fa-solid fa-phone-volume text-yellow-400 mr-1.5"></i>Hotline / Zalo: <strong>0966.961.431 - 0901.172.864</strong></div>
              </div>
              <div class="pt-1 flex flex-wrap items-center gap-2.5">
                <a href="#san-pham" class="bg-[#d9232a] hover:bg-red-700 text-white text-xs sm:text-sm font-bold px-4 py-2 rounded-lg transition shadow">
                  Xem Sản Phẩm
                </a>
                <a href="#baogia" class="bg-white text-[#004a8f] hover:bg-yellow-300 text-xs sm:text-sm font-bold px-4 py-2 rounded-lg transition">
                  Nhận Báo Giá Ngay
                </a>
              </div>
            </div>

            <!-- Cụm ảnh thực tế nằm gọn bên trong Banner 1 -->
            <div class="hidden md:grid md:col-span-5 grid-cols-2 gap-2.5 p-2 bg-white/10 rounded-xl border border-white/20">
              <div class="bg-white rounded-lg p-1.5 h-32 lg:h-36 flex items-center justify-center overflow-hidden">
                <img src="https://lh3.googleusercontent.com/d/1aOVcsvLkloQrljF9f6yhMXmDrhz4O_LO" alt="Ke cân bằng gạch Thiên Tiến" class="w-full h-full object-contain" onerror="handleDriveImageFallback(this, '1aOVcsvLkloQrljF9f6yhMXmDrhz4O_LO', 'Ke Cân Bằng')">
              </div>
              <div class="bg-white rounded-lg p-1.5 h-32 lg:h-36 flex items-center justify-center overflow-hidden">
                <img src="https://lh3.googleusercontent.com/d/16nopd10IJNHmanj20BIjYIL6kRkr0gyF" alt="Keo chà ron Epoxy Thiên Tiến" class="w-full h-full object-contain" onerror="handleDriveImageFallback(this, '16nopd10IJNHmanj20BIjYIL6kRkr0gyF', 'Keo Epoxy')">
              </div>
              <div class="bg-white rounded-lg p-1.5 h-32 lg:h-36 flex items-center justify-center overflow-hidden">
                <img src="https://lh3.googleusercontent.com/d/15h6ByzEzXdeJernXzIqDQG2_TphphG9C" alt="Keo dán gạch đá Thiên Tiến" class="w-full h-full object-contain" onerror="handleDriveImageFallback(this, '15h6ByzEzXdeJernXzIqDQG2_TphphG9C', 'Keo Dán Gạch')">
              </div>
              <div class="bg-white rounded-lg p-1.5 h-32 lg:h-36 flex items-center justify-center overflow-hidden">
                <img src="https://lh3.googleusercontent.com/d/1hbeMNQzqyu7Fa4hQ43I79GsHPm4eWZG9" alt="Dụng cụ ốp lát Thiên Tiến" class="w-full h-full object-contain" onerror="handleDriveImageFallback(this, '1hbeMNQzqyu7Fa4hQ43I79GsHPm4eWZG9', 'Phụ Kiện Ốp Lát')">
              </div>
            </div>
          </div>
        </div>

        <!-- SLIDE 2: Tổng Kho Phân Phối Keo Cá Sấu, Cotto, Weber & Phụ Kiện Ốp Lát -->
        <div class="banner-slide bg-gradient-to-r from-[#0f3d3e] via-[#00695c] to-[#004a8f] text-white flex items-center">
          <!-- Khoảng đệm px-6 sm:px-12 md:px-16 giữ chữ cách xa viền ảnh banner -->
          <div class="w-full h-full px-6 py-5 sm:px-12 md:px-16 md:py-8 grid grid-cols-1 md:grid-cols-12 items-center gap-4">
            <div class="md:col-span-7 flex flex-col justify-center space-y-2 sm:space-y-3">
              <div class="inline-flex items-center gap-2 bg-white text-[#00695c] font-extrabold text-[11px] sm:text-xs px-3 py-1 rounded-full w-fit">
                <span>TỔNG KHO PHÂN PHỐI SỈ & LẺ TẠI ĐÀ NẴNG</span>
              </div>
              <h2 class="text-base sm:text-2xl lg:text-3xl font-extrabold leading-snug text-white">
                KEO DÁN GẠCH CÁ SẤU, COTTO, WEBER & KE CÂN BẰNG GẠCH
              </h2>
              <p class="text-xs sm:text-sm lg:text-base text-emerald-200 font-semibold leading-relaxed">
                Giải pháp thi công ốp lát gạch khổ lớn, chống thấm, chà ron Epoxy chống bám bẩn – Giao hàng tận công trình Đà Nẵng & Miền Trung
              </p>
              <div class="text-[11px] sm:text-xs text-emerald-100 space-y-1 pt-0.5">
                <div><i class="fa-solid fa-warehouse text-yellow-300 mr-1.5"></i>Kho hàng sẵn số lượng lớn tại: 72 Lê Hiến Mai, Hòa Khánh, Đà Nẵng</div>
                <div><i class="fa-solid fa-headset text-yellow-300 mr-1.5"></i>Tư vấn kỹ thuật & Báo giá đại lý: <strong>0966.961.431 - 0901.172.864</strong></div>
              </div>
              <div class="pt-1 flex flex-wrap items-center gap-2.5">
                <a href="#cua-hang" class="bg-yellow-400 hover:bg-yellow-300 text-slate-900 text-xs sm:text-sm font-bold px-4 py-2 rounded-lg transition shadow">
                  Xem Kho Hàng Thực Tế
                </a>
                <a href="#bando-fanpage" class="bg-white/20 hover:bg-white/30 text-white text-xs sm:text-sm font-bold px-4 py-2 rounded-lg transition border border-white/40">
                  Xem Bản Đồ Đường Đi
                </a>
              </div>
            </div>

            <!-- Cụm ảnh thực tế cửa hàng & sản phẩm nằm gọn bên trong Banner 2 -->
            <div class="hidden md:grid md:col-span-5 grid-cols-2 gap-2.5 p-2 bg-white/10 rounded-xl border border-white/20">
              <div class="bg-white rounded-lg p-1.5 h-32 lg:h-36 flex items-center justify-center overflow-hidden">
                <img src="https://lh3.googleusercontent.com/d/1QXRVO5z-x2uKV0fXiw4HkgVlwVgdDc2i" alt="Cửa hàng Thiên Tiến Đà Nẵng" class="w-full h-full object-cover rounded" onerror="handleDriveImageFallback(this, '1QXRVO5z-x2uKV0fXiw4HkgVlwVgdDc2i', 'Cửa Hàng Thiên Tiến')">
              </div>
              <div class="bg-white rounded-lg p-1.5 h-32 lg:h-36 flex items-center justify-center overflow-hidden">
                <img src="https://lh3.googleusercontent.com/d/185nfwS4qj-KSNSzQvGXv12n0wnkAb05L" alt="Sản phẩm thực tế Thiên Tiến" class="w-full h-full object-contain" onerror="handleDriveImageFallback(this, '185nfwS4qj-KSNSzQvGXv12n0wnkAb05L', 'Keo Ốp Lát')">
              </div>
              <div class="bg-white rounded-lg p-1.5 h-32 lg:h-36 flex items-center justify-center overflow-hidden">
                <img src="https://lh3.googleusercontent.com/d/1P4RbqBqplmfy9RNb04FNqPDMQ8cDAavK" alt="Sản phẩm thực tế Thiên Tiến" class="w-full h-full object-contain" onerror="handleDriveImageFallback(this, '1P4RbqBqplmfy9RNb04FNqPDMQ8cDAavK', 'Keo Chà Ron')">
              </div>
              <div class="bg-white rounded-lg p-1.5 h-32 lg:h-36 flex items-center justify-center overflow-hidden">
                <img src="https://lh3.googleusercontent.com/d/1jJ4aUZpDSkXBEmPHwWPwD_K_Rbu0so1N" alt="Kho hàng Thiên Tiến" class="w-full h-full object-cover rounded" onerror="handleDriveImageFallback(this, '1jJ4aUZpDSkXBEmPHwWPwD_K_Rbu0so1N', 'Kho Hàng Thiên Tiến')">
              </div>
            </div>
          </div>
        </div>

        <!-- Nút điều hướng trái/phải & chấm tròn chỉ báo Slide -->
        <button type="button" onclick="changeBannerSlide(-1)" aria-label="Slide trước" class="absolute left-2 top-1/2 -translate-y-1/2 z-20 w-8 h-8 rounded-full bg-black/35 hover:bg-black/60 text-white flex items-center justify-center transition">
          <i class="fa-solid fa-chevron-left text-xs"></i>
        </button>
        <button type="button" onclick="changeBannerSlide(1)" aria-label="Slide tiếp" class="absolute right-2 top-1/2 -translate-y-1/2 z-20 w-8 h-8 rounded-full bg-black/35 hover:bg-black/60 text-white flex items-center justify-center transition">
          <i class="fa-solid fa-chevron-right text-xs"></i>
        </button>
        <div class="absolute bottom-2.5 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2">
          <button type="button" onclick="goToBannerSlide(0)" class="banner-dot w-2.5 h-2.5 rounded-full bg-yellow-400 transition" aria-label="Banner 1"></button>
          <button type="button" onclick="goToBannerSlide(1)" class="banner-dot w-2.5 h-2.5 rounded-full bg-white/50 transition" aria-label="Banner 2"></button>
        </div>

      </div>
    </div>
  </section>

  <!-- =====================================================================
       5. DANH MỤC SẢN PHẨM TRANG CHỦ (Lấy chuẩn từ web mẫu vlxdthailan.com,
          chữ danh mục ở trang chủ nhỏ gọn, viết liền trên 1 hàng không xuống dòng)
       ===================================================================== -->
  <section id="danh-muc-trang-chu" class="mt-4">
    <div class="flatsome-container">
      <div class="bg-white rounded-lg p-3 border border-slate-200 shadow-xs">
        <div class="flex items-center justify-between mb-2.5 pb-1.5 border-b border-slate-100">
          <h2 class="text-xs sm:text-sm font-extrabold text-[#004a8f] uppercase flex items-center gap-1.5">
            <i class="fa-solid fa-layer-group text-[#d9232a]"></i> DANH MỤC SẢN PHẨM CHÍNH HÃNG
          </h2>
          <span class="text-[11px] text-slate-500 hidden sm:inline">Chọn danh mục để lọc nhanh sản phẩm</span>
        </div>

        <!-- Danh sách nút danh mục chữ nhỏ gọn, nằm liền trên hàng, không bị rớt chữ -->
        <div class="flex flex-wrap items-center gap-1.5 sm:gap-2">
          <button type="button" onclick="filterByCategory('all')" data-cat="all" class="cat-filter-btn home-cat-pill px-3 py-2 rounded-lg bg-[#004a8f] text-white border border-[#004a8f]">
            Tất Cả Sản Phẩm (16)
          </button>
          <button type="button" onclick="filterByCategory('ke-can-bang')" data-cat="ke-can-bang" class="cat-filter-btn home-cat-pill px-3 py-2 rounded-lg bg-slate-100 hover:bg-blue-50 text-slate-800 border border-slate-200">
            Ke Cân Bằng & Dụng Cụ Thi Công
          </button>
          <button type="button" onclick="filterByCategory('keo-cha-ron')" data-cat="keo-cha-ron" class="cat-filter-btn home-cat-pill px-3 py-2 rounded-lg bg-slate-100 hover:bg-blue-50 text-slate-800 border border-slate-200">
            Keo Chà Ron / Keo Chít Mạch Epoxy
          </button>
          <button type="button" onclick="filterByCategory('keo-dan-gach')" data-cat="keo-dan-gach" class="cat-filter-btn home-cat-pill px-3 py-2 rounded-lg bg-slate-100 hover:bg-blue-50 text-slate-800 border border-slate-200">
            Keo Dán Gạch Cá Sấu
          </button>
          <button type="button" onclick="filterByCategory('keo-cotto-weber')" data-cat="keo-cotto-weber" class="cat-filter-btn home-cat-pill px-3 py-2 rounded-lg bg-slate-100 hover:bg-blue-50 text-slate-800 border border-slate-200">
            Keo Dán Gạch Cotto & Weber
          </button>
          <button type="button" onclick="filterByCategory('chong-tham')" data-cat="chong-tham" class="cat-filter-btn home-cat-pill px-3 py-2 rounded-lg bg-slate-100 hover:bg-blue-50 text-slate-800 border border-slate-200">
            Chống Thấm Thái Lan
          </button>
          <button type="button" onclick="filterByCategory('hoa-chat')" data-cat="hoa-chat" class="cat-filter-btn home-cat-pill px-3 py-2 rounded-lg bg-slate-100 hover:bg-blue-50 text-slate-800 border border-slate-200">
            Hoá Chất Xây Dựng & Vữa Rót
          </button>
        </div>
      </div>
    </div>
  </section>

  <!-- =====================================================================
       6. KHU VỰC SẢN PHẨM TRANG CHỦ CHUẨN FLATSOME
          - Điện thoại chia 2 cột (grid-cols-2), Máy tính chia 5 cột (lg:grid-cols-5)
          - Có % giảm giá giống Flatsome ở góc trên bên trái
          - Không để các nhãn dán rườm rà khác ở trang chủ
          - Tên sản phẩm hiển thị đầy đủ, không bị tràn hoặc thiếu chữ
       ===================================================================== -->
  <main id="san-pham" class="mt-5 space-y-6">

    <!-- KHỐI 1: 10 SẢN PHẨM THỰC TẾ TẠI CỬA HÀNG THIÊN TIẾN (Từ 10 file Google Drive) -->
    <section class="flatsome-container" data-section-cat="ke-can-bang keo-cha-ron keo-dan-gach">
      <div class="ux-section-title">
        <h2><i class="fa-solid fa-star text-[#d9232a]"></i> SẢN PHẨM THỰC TẾ CHỦ LỰC TẠI THIÊN TIẾN ĐÀ NẴNG</h2>
        <a href="#baogia" class="text-xs font-bold text-[#004a8f] hover:text-[#d9232a] whitespace-nowrap">Nhận báo giá sỉ ›</a>
      </div>
      <div id="realProductsGrid" class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-4 lg:grid-cols-5 gap-2.5 sm:gap-3.5">
        <!-- Được render tự động bằng JS từ 10 ảnh thực tế Google Drive -->
      </div>
    </section>

    <!-- KHỐI 2: DANH MỤC KEO DÁN GẠCH CÁ SẤU, COTTO, WEBER & CHỐNG THẤM, HOÁ CHẤT (Từ mẫu vlxdthailan.com) -->
    <section class="flatsome-container" data-section-cat="keo-dan-gach keo-cotto-weber chong-tham hoa-chat">
      <div class="ux-section-title">
        <h2><i class="fa-solid fa-layer-group text-[#00843d]"></i> KEO DÁN GẠCH CÁ SẤU, COTTO, WEBER & HOÁ CHẤT XÂY DỰNG</h2>
        <a href="#baogia" class="text-xs font-bold text-[#004a8f] hover:text-[#d9232a] whitespace-nowrap">Tư vấn định mức ›</a>
      </div>
      <div id="catalogProductsGrid" class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-4 lg:grid-cols-5 gap-2.5 sm:gap-3.5">
        <!-- Được render tự động bằng JS -->
      </div>
    </section>

  </main>

  <!-- =====================================================================
       7. HÌNH ẢNH THỰC TẾ CỬA HÀNG & KHO HÀNG THIÊN TIẾN (3 ảnh từ Google Drive)
       ===================================================================== -->
  <section id="cua-hang" class="mt-7">
    <div class="flatsome-container">
      <div class="ux-section-title">
        <h2><i class="fa-solid fa-store text-[#004a8f]"></i> HÌNH ẢNH THỰC TẾ CỬA HÀNG VLXD THIÊN TIẾN - 72 LÊ HIẾN MAI, ĐÀ NẴNG</h2>
        <span class="text-xs font-semibold text-slate-500 hidden sm:inline">Kho hàng luôn sẵn số lượng lớn</span>
      </div>

      <div class="grid grid-cols-1 md:grid-cols-3 gap-3.5">
        <!-- Ảnh cửa hàng 1 -->
        <div class="bg-white rounded-lg border border-slate-200 overflow-hidden shadow-xs">
          <div class="h-56 sm:h-64 w-full bg-slate-100 overflow-hidden">
            <img 
              src="https://lh3.googleusercontent.com/d/1QXRVO5z-x2uKV0fXiw4HkgVlwVgdDc2i" 
              alt="Cửa hàng Công ty TNHH Thương Mại Xây Dựng Thiên Tiến - 72 Lê Hiến Mai Đà Nẵng" 
              class="w-full h-full object-cover hover:scale-105 transition duration-300"
              onerror="handleDriveImageFallback(this, '1QXRVO5z-x2uKV0fXiw4HkgVlwVgdDc2i', 'Cửa Hàng Thiên Tiến 1')"
            >
          </div>
          <div class="p-3">
            <h3 class="text-xs sm:text-sm font-bold text-[#004a8f]">Cửa Hàng Trưng Bày & Phân Phối VLXD Thiên Tiến</h3>
            <p class="text-xs text-slate-600 mt-1">Đầy đủ mẫu mã ke cân bằng, nêm lát gạch, kìm bấm ke, keo chà ron Epoxy và keo dán gạch đá chính hãng tại 72 Lê Hiến Mai.</p>
          </div>
        </div>

        <!-- Ảnh cửa hàng 2 -->
        <div class="bg-white rounded-lg border border-slate-200 overflow-hidden shadow-xs">
          <div class="h-56 sm:h-64 w-full bg-slate-100 overflow-hidden">
            <img 
              src="https://lh3.googleusercontent.com/d/1jJ4aUZpDSkXBEmPHwWPwD_K_Rbu0so1N" 
              alt="Kho hàng keo dán gạch và phụ kiện ốp lát Thiên Tiến Đà Nẵng" 
              class="w-full h-full object-cover hover:scale-105 transition duration-300"
              onerror="handleDriveImageFallback(this, '1jJ4aUZpDSkXBEmPHwWPwD_K_Rbu0so1N', 'Cửa Hàng Thiên Tiến 2')"
            >
          </div>
          <div class="p-3">
            <h3 class="text-xs sm:text-sm font-bold text-[#004a8f]">Tổng Kho Keo Ốp Lát Gạch Đá & Phụ Kiện Thi Công</h3>
            <p class="text-xs text-slate-600 mt-1">Nguồn hàng dồi dào phục vụ nhanh chóng cho các đại lý, nhà thầu xây dựng và đội thợ ốp lát tại Đà Nẵng & Miền Trung.</p>
          </div>
        </div>

        <!-- Ảnh cửa hàng 3 -->
        <div class="bg-white rounded-lg border border-slate-200 overflow-hidden shadow-xs">
          <div class="h-56 sm:h-64 w-full bg-slate-100 overflow-hidden">
            <img 
              src="https://lh3.googleusercontent.com/d/10w3-TjwyzDONXmKosrnu8_4HXt0ax2rR" 
              alt="Giao hàng keo ốp lát và ke cân bằng Thiên Tiến" 
              class="w-full h-full object-cover hover:scale-105 transition duration-300"
              onerror="handleDriveImageFallback(this, '10w3-TjwyzDONXmKosrnu8_4HXt0ax2rR', 'Cửa Hàng Thiên Tiến 3')"
            >
          </div>
          <div class="p-3">
            <h3 class="text-xs sm:text-sm font-bold text-[#004a8f]">Hỗ Trợ Giao Hàng Nhanh Tận Chân Công Trình</h3>
            <p class="text-xs text-slate-600 mt-1">Cam kết sản phẩm chất lượng cao: Dán cực nhanh, bền đẹp, tiết kiệm nhân công và tối ưu chi phí cho chủ đầu tư.</p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- =====================================================================
       8. VỀ CHÚNG TÔI & FORM YÊU CẦU BÁO GIÁ TRANG CHỦ
       ===================================================================== -->
  <section id="ve-chung-toi" class="mt-7">
    <div class="flatsome-container">
      <div class="grid grid-cols-1 lg:grid-cols-12 gap-4">

        <!-- Giới thiệu Công ty TNHH Thương Mại Xây Dựng Thiên Tiến -->
        <div class="lg:col-span-6 bg-white rounded-lg border border-slate-200 p-4 sm:p-5 shadow-xs flex flex-col justify-between">
          <div>
            <div class="flex items-center gap-3 pb-3 mb-3 border-b border-slate-100">
              <img 
                src="https://lh3.googleusercontent.com/d/1FRGwVdVqrXcQ0bFAU2c6FB6eHPbnT2y8" 
                alt="Logo Thiên Tiến" 
                class="w-12 h-12 object-contain rounded border border-slate-200 p-1"
                onerror="handleDriveImageFallback(this, '1FRGwVdVqrXcQ0bFAU2c6FB6eHPbnT2y8', 'THIÊN TIẾN')"
              >
              <div>
                <h2 class="text-sm sm:text-base font-extrabold text-[#004a8f] uppercase">
                  CÔNG TY TNHH THƯƠNG MẠI XÂY DỰNG THIÊN TIẾN
                </h2>
                <p class="text-xs text-slate-500 font-medium">MST: 0402131605 • Website: thientien.com</p>
              </div>
            </div>

            <p class="text-xs sm:text-sm text-slate-700 leading-relaxed mb-3">
              <strong>CÔNG TY TNHH THƯƠNG MẠI XÂY DỰNG THIÊN TIẾN</strong> là đơn vị uy tín hàng đầu tại Đà Nẵng chuyên cung cấp sỉ & lẻ <strong>Ke Cân Bằng Gạch, Keo Chà Ron Epoxy 2 Thành Phần, Keo Ốp Lát Gạch Đá (Cá Sấu Thái Lan, Cotto, Weber, Sika)</strong> và các dòng hóa chất chống thấm, dụng cụ thi công ốp lát chuyên nghiệp.
            </p>

            <div class="grid grid-cols-1 sm:grid-cols-2 gap-2.5 my-3">
              <div class="p-2.5 rounded-lg bg-blue-50/70 border border-blue-100">
                <div class="text-xs font-bold text-[#004a8f]"><i class="fa-solid fa-bolt text-[#d9232a] mr-1"></i>Dán Cực Nhanh</div>
                <p class="text-[11.5px] text-slate-600 mt-0.5">Độ bám dính siêu cường cho gạch khổ lớn, đá granite, marble, gạch chồng gạch.</p>
              </div>
              <div class="p-2.5 rounded-lg bg-blue-50/70 border border-blue-100">
                <div class="text-xs font-bold text-[#004a8f]"><i class="fa-solid fa-gem text-[#00843d] mr-1"></i>Bền Đẹp Vĩnh Cửu</div>
                <p class="text-[11.5px] text-slate-600 mt-0.5">Mạch gạch phẳng đều tuyệt đối, ron Epoxy bóng mịn chống thấm và chống ố mốc.</p>
              </div>
              <div class="p-2.5 rounded-lg bg-blue-50/70 border border-blue-100">
                <div class="text-xs font-bold text-[#004a8f]"><i class="fa-solid fa-users-gear text-amber-600 mr-1"></i>Tiết Kiệm Nhân Công</div>
                <p class="text-[11.5px] text-slate-600 mt-0.5">Rút ngắn 40% thời gian căn chỉnh gạch, nâng cao năng suất cho đội thợ thi công.</p>
              </div>
              <div class="p-2.5 rounded-lg bg-blue-50/70 border border-blue-100">
                <div class="text-xs font-bold text-[#004a8f]"><i class="fa-solid fa-truck-fast text-blue-600 mr-1"></i>Giá Sỉ Tận Kho</div>
                <p class="text-[11.5px] text-slate-600 mt-0.5">Chiết khấu cao cho nhà thầu, đại lý và giao hàng nhanh tận nơi tại Đà Nẵng.</p>
              </div>
            </div>
          </div>

          <div class="bg-slate-50 p-3 rounded-lg border border-slate-200 text-xs space-y-1">
            <div><strong><i class="fa-solid fa-location-dot text-[#d9232a] mr-1.5"></i>Địa chỉ:</strong> 72 Lê Hiến Mai, Hòa Khánh, Đà Nẵng</div>
            <div><strong><i class="fa-solid fa-phone text-[#00843d] mr-1.5"></i>Điện thoại / Zalo:</strong> <a href="tel:0966961431" class="text-[#d9232a] font-bold">0966.961.431</a> - <a href="tel:0901172864" class="text-[#004a8f] font-bold">0901.172.864</a></div>
            <div><strong><i class="fa-brands fa-facebook text-blue-600 mr-1.5"></i>Fanpage:</strong> <a href="https://www.facebook.com/keoplatdanang" target="_blank" rel="noopener" class="text-[#004a8f] hover:underline font-medium">facebook.com/keoplatdanang</a></div>
          </div>
        </div>

        <!-- FORM YÊU CẦU VÀ BÁO GIÁ TRANG CHỦ -->
        <div id="baogia" class="lg:col-span-6 bg-white rounded-lg border-2 border-[#004a8f] p-4 sm:p-5 shadow-xs">
          <div class="border-b border-slate-200 pb-2.5 mb-3">
            <h2 class="text-sm sm:text-base font-extrabold text-[#004a8f] uppercase flex items-center gap-2">
              <i class="fa-solid fa-file-signature text-[#d9232a]"></i> FORM YÊU CẦU TƯ VẤN VÀ BÁO GIÁ NHANH
            </h2>
            <p class="text-xs text-slate-600 mt-0.5">Để lại thông tin, Thiên Tiến sẽ liên hệ báo giá sỉ & lẻ tốt nhất trong vòng 5 phút!</p>
          </div>

          <form id="quoteForm" onsubmit="handleQuoteSubmit(event)" class="space-y-3 text-xs sm:text-sm">
            <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
              <div>
                <label class="block font-semibold text-slate-700 mb-1">Họ và tên quý khách <span class="text-red-500">*</span></label>
                <input id="quoteName" type="text" required placeholder="Nhập họ và tên..." class="w-full border border-slate-300 rounded-lg px-3 py-2 focus:outline-none focus:border-[#004a8f]">
              </div>
              <div>
                <label class="block font-semibold text-slate-700 mb-1">Số điện thoại / Zalo <span class="text-red-500">*</span></label>
                <input id="quotePhone" type="tel" required placeholder="Ví dụ: 0966961431" class="w-full border border-slate-300 rounded-lg px-3 py-2 focus:outline-none focus:border-[#004a8f]">
              </div>
            </div>

            <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
              <div>
                <label class="block font-semibold text-slate-700 mb-1">Danh mục sản phẩm cần báo giá</label>
                <select id="quoteCategory" class="w-full border border-slate-300 rounded-lg px-3 py-2 bg-white focus:outline-none focus:border-[#004a8f]">
                  <option value="Ke cân bằng gạch, Nêm, Kìm bấm ke">Ke cân bằng gạch, Nêm, Kìm bấm ke</option>
                  <option value="Keo chà ron Epoxy 2 thành phần">Keo chà ron Epoxy 2 thành phần</option>
                  <option value="Keo dán gạch đá Cá Sấu / Cotto / Weber">Keo dán gạch đá Cá Sấu / Cotto / Weber</option>
                  <option value="Chống thấm & Hoá chất xây dựng">Chống thấm & Hoá chất xây dựng</option>
                  <option value="Đăng ký đại lý / Báo giá tổng hợp công trình">Đăng ký đại lý / Báo giá tổng hợp công trình</option>
                </select>
              </div>
              <div>
                <label class="block font-semibold text-slate-700 mb-1">Số lượng / Diện tích thi công (m²)</label>
                <input id="quoteQty" type="text" placeholder="Ví dụ: 150 m² hoặc 30 bao keo..." class="w-full border border-slate-300 rounded-lg px-3 py-2 focus:outline-none focus:border-[#004a8f]">
              </div>
            </div>

            <div>
              <label class="block font-semibold text-slate-700 mb-1">Nội dung yêu cầu chi tiết / Địa chỉ giao hàng</label>
              <textarea id="quoteNote" rows="2" placeholder="Nhập kích thước gạch (60x60, 80x80, 60x120...), màu keo ron hoặc địa chỉ công trình tại Đà Nẵng..." class="w-full border border-slate-300 rounded-lg px-3 py-2 focus:outline-none focus:border-[#004a8f]"></textarea>
            </div>

            <div id="quoteSuccessBox" class="hidden p-3 rounded-lg bg-emerald-50 border border-emerald-300 text-emerald-800 text-xs font-medium"></div>

            <div class="flex flex-wrap items-center gap-2 pt-1">
              <button type="submit" class="bg-[#d9232a] hover:bg-red-700 text-white font-bold px-5 py-2.5 rounded-lg transition shadow flex items-center gap-2">
                <i class="fa-solid fa-paper-plane"></i> GỬI YÊU CẦU BÁO GIÁ
              </button>
              <a href="https://zalo.me/0966961431" target="_blank" rel="noopener" class="bg-[#004a8f] hover:bg-[#00356b] text-white font-bold px-4 py-2.5 rounded-lg transition flex items-center gap-1.5">
                <i class="fa-solid fa-comment-dots"></i> Chat Zalo: 0966.961.431
              </a>
            </div>
          </form>
        </div>

      </div>
    </div>
  </section>

  <!-- =====================================================================
       9. DANH MỤC CÁC BÀI VIẾT TRANG CHỦ (Tin tức & Giải pháp thi công)
       ===================================================================== -->
  <section id="tin-tuc" class="mt-7">
    <div class="flatsome-container">
      <div class="ux-section-title">
        <h2><i class="fa-solid fa-newspaper text-[#004a8f]"></i> BÀI VIẾT & KINH NGHIỆM THI CÔNG ỐP LÁT MỚI NHẤT</h2>
        <span class="text-xs text-slate-500 hidden sm:inline">Góc tư vấn kỹ thuật Thiên Tiến</span>
      </div>

      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-3.5">
        <!-- Bài viết 1 -->
        <article class="bg-white rounded-lg border border-slate-200 overflow-hidden shadow-xs flex flex-col justify-between">
          <div>
            <div class="h-40 bg-slate-100 overflow-hidden relative">
              <img src="https://lh3.googleusercontent.com/d/1aOVcsvLkloQrljF9f6yhMXmDrhz4O_LO" alt="Hướng dẫn dùng ke cân bằng" class="w-full h-full object-contain p-2 bg-white" onerror="handleDriveImageFallback(this, '1aOVcsvLkloQrljF9f6yhMXmDrhz4O_LO', 'Bài Viết 1')">
              <span class="absolute bottom-2 left-2 bg-[#004a8f] text-white text-[10.5px] font-bold px-2 py-0.5 rounded">Kỹ thuật ốp lát</span>
            </div>
            <div class="p-3">
              <h3 class="text-xs sm:text-sm font-bold text-slate-800 hover:text-[#004a8f] leading-snug">
                Hướng dẫn sử dụng Ke Cân Bằng và Nêm Lát Gạch giúp mặt sàn phẳng đẹp tuyệt đối
              </h3>
              <p class="text-xs text-slate-600 mt-1.5 leading-relaxed">
                Cách tính định mức số lượng ke cân bằng theo từng kích thước gạch 60x60, 80x80, 60x120 giúp tiết kiệm tối đa nhân công...
              </p>
            </div>
          </div>
          <div class="px-3 pb-3 pt-1">
            <button type="button" onclick="openArticleModal(0)" class="text-xs font-bold text-[#d9232a] hover:underline">Đọc chi tiết →</button>
          </div>
        </article>

        <!-- Bài viết 2 -->
        <article class="bg-white rounded-lg border border-slate-200 overflow-hidden shadow-xs flex flex-col justify-between">
          <div>
            <div class="h-40 bg-slate-100 overflow-hidden relative">
              <img src="https://lh3.googleusercontent.com/d/16nopd10IJNHmanj20BIjYIL6kRkr0gyF" alt="Keo chà ron Epoxy 2 thành phần" class="w-full h-full object-contain p-2 bg-white" onerror="handleDriveImageFallback(this, '16nopd10IJNHmanj20BIjYIL6kRkr0gyF', 'Bài Viết 2')">
              <span class="absolute bottom-2 left-2 bg-[#d9232a] text-white text-[10.5px] font-bold px-2 py-0.5 rounded">Keo Chà Ron Epoxy</span>
            </div>
            <div class="p-3">
              <h3 class="text-xs sm:text-sm font-bold text-slate-800 hover:text-[#004a8f] leading-snug">
                Vì sao Keo Chà Ron Epoxy 2 thành phần thay thế hoàn toàn bột chà ron truyền thống?
              </h3>
              <p class="text-xs text-slate-600 mt-1.5 leading-relaxed">
                Khả năng chống thấm nước 100%, chống bám bẩn đen mạch, bề mặt bóng như men sứ cho phòng khách, nhà tắm, sảnh lớn...
              </p>
            </div>
          </div>
          <div class="px-3 pb-3 pt-1">
            <button type="button" onclick="openArticleModal(1)" class="text-xs font-bold text-[#d9232a] hover:underline">Đọc chi tiết →</button>
          </div>
        </article>

        <!-- Bài viết 3 -->
        <article class="bg-white rounded-lg border border-slate-200 overflow-hidden shadow-xs flex flex-col justify-between">
          <div>
            <div class="h-40 bg-slate-100 overflow-hidden relative">
              <img src="https://lh3.googleusercontent.com/d/15h6ByzEzXdeJernXzIqDQG2_TphphG9C" alt="Keo dán gạch đá khổ lớn" class="w-full h-full object-contain p-2 bg-white" onerror="handleDriveImageFallback(this, '15h6ByzEzXdeJernXzIqDQG2_TphphG9C', 'Bài Viết 3')">
              <span class="absolute bottom-2 left-2 bg-[#00843d] text-white text-[10.5px] font-bold px-2 py-0.5 rounded">Keo Dán Gạch Đá</span>
            </div>
            <div class="p-3">
              <h3 class="text-xs sm:text-sm font-bold text-slate-800 hover:text-[#004a8f] leading-snug">
                Nguyên nhân gạch ốp lát bị bộp, phồng rộp và giải pháp dùng Keo Dán Gạch Cá Sấu, Cotto
              </h3>
              <p class="text-xs text-slate-600 mt-1.5 leading-relaxed">
                Gạch Porcelain và đá tự nhiên ít hút nước cần sử dụng keo dán gạch chuyên dụng có độ bám dính polymer cao...
              </p>
            </div>
          </div>
          <div class="px-3 pb-3 pt-1">
            <button type="button" onclick="openArticleModal(2)" class="text-xs font-bold text-[#d9232a] hover:underline">Đọc chi tiết →</button>
          </div>
        </article>

        <!-- Bài viết 4 -->
        <article class="bg-white rounded-lg border border-slate-200 overflow-hidden shadow-xs flex flex-col justify-between">
          <div>
            <div class="h-40 bg-slate-100 overflow-hidden relative">
              <img src="https://lh3.googleusercontent.com/d/1QXRVO5z-x2uKV0fXiw4HkgVlwVgdDc2i" alt="Bảng giá keo dán gạch Đà Nẵng" class="w-full h-full object-cover" onerror="handleDriveImageFallback(this, '1QXRVO5z-x2uKV0fXiw4HkgVlwVgdDc2i', 'Bài Viết 4')">
              <span class="absolute bottom-2 left-2 bg-amber-600 text-white text-[10.5px] font-bold px-2 py-0.5 rounded">Báo Giá Đà Nẵng</span>
            </div>
            <div class="p-3">
              <h3 class="text-xs sm:text-sm font-bold text-slate-800 hover:text-[#004a8f] leading-snug">
                Địa chỉ mua Ke Cân Bằng, Keo Dán Gạch, Keo Chà Ron Epoxy uy tín giá sỉ tại Đà Nẵng
              </h3>
              <p class="text-xs text-slate-600 mt-1.5 leading-relaxed">
                Công ty TNHH Thương Mại Xây Dựng Thiên Tiến (72 Lê Hiến Mai, Hòa Khánh, Đà Nẵng) cung cấp trọn bộ vật tư ốp lát chính hãng...
              </p>
            </div>
          </div>
          <div class="px-3 pb-3 pt-1">
            <button type="button" onclick="openArticleModal(3)" class="text-xs font-bold text-[#d9232a] hover:underline">Đọc chi tiết →</button>
          </div>
        </article>
      </div>
    </div>
  </section>

  <!-- =====================================================================
       10. DANH MỤC CÁC ĐỐI TÁC & THƯƠNG HIỆU PHÂN PHỐI
       ===================================================================== -->
  <section id="doi-tac" class="mt-7">
    <div class="flatsome-container">
      <div class="ux-section-title">
        <h2><i class="fa-solid fa-handshake text-[#004a8f]"></i> ĐỐI TÁC & THƯƠNG HIỆU PHÂN PHỐI CHÍNH HÃNG</h2>
        <span class="text-xs text-slate-500 hidden sm:inline">Cam kết chính hãng 100%</span>
      </div>

      <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-3">
        <div class="bg-white rounded-lg border border-slate-200 p-3.5 text-center hover:border-[#004a8f] transition">
          <div class="text-base font-black text-[#00843d] tracking-tight">CROCODILE</div>
          <div class="text-[11px] font-semibold text-slate-500 mt-1">Keo Cá Sấu Thái Lan</div>
        </div>
        <div class="bg-white rounded-lg border border-slate-200 p-3.5 text-center hover:border-[#004a8f] transition">
          <div class="text-base font-black text-[#d9232a] tracking-tight">COTTO - SCG</div>
          <div class="text-[11px] font-semibold text-slate-500 mt-1">Keo Dán Gạch Thái Lan</div>
        </div>
        <div class="bg-white rounded-lg border border-slate-200 p-3.5 text-center hover:border-[#004a8f] transition">
          <div class="text-base font-black text-[#004a8f] tracking-tight">WEBER</div>
          <div class="text-[11px] font-semibold text-slate-500 mt-1">Tập Đoàn Saint-Gobain</div>
        </div>
        <div class="bg-white rounded-lg border border-slate-200 p-3.5 text-center hover:border-[#004a8f] transition">
          <div class="text-base font-black text-amber-600 tracking-tight">SIKA</div>
          <div class="text-[11px] font-semibold text-slate-500 mt-1">Hoá Chất & Chống Thấm</div>
        </div>
        <div class="bg-white rounded-lg border border-slate-200 p-3.5 text-center hover:border-[#004a8f] transition">
          <div class="text-base font-black text-blue-700 tracking-tight">MAPEI</div>
          <div class="text-[11px] font-semibold text-slate-500 mt-1">Keo Ốp Lát Cao Cấp</div>
        </div>
        <div class="bg-white rounded-lg border border-slate-200 p-3.5 text-center hover:border-[#004a8f] transition">
          <div class="text-base font-black text-emerald-700 tracking-tight">PANDA</div>
          <div class="text-[11px] font-semibold text-slate-500 mt-1">Keo Dán Gạch & Ron</div>
        </div>
      </div>
    </div>
  </section>

  <!-- =====================================================================
       11. ĐƯA GOOGLE MAP VÀ FANPAGE FACEBOOK RA NGOÀI TRANG CHỦ
       ===================================================================== -->
  <section id="bando-fanpage" class="mt-7 mb-8">
    <div class="flatsome-container">
      <div class="ux-section-title">
        <h2><i class="fa-solid fa-map-location-dot text-[#d9232a]"></i> BẢN ĐỒ GOOGLE MAPS & FANPAGE FACEBOOK CHÍNH THỨC</h2>
        <span class="text-xs text-slate-500 hidden sm:inline">72 Lê Hiến Mai, Hòa Khánh, Đà Nẵng</span>
      </div>

      <div class="grid grid-cols-1 lg:grid-cols-12 gap-4">

        <!-- CỘT 1: BẢN ĐỒ GOOGLE MAPS TRỰC TIẾP NGOÀI TRANG CHỦ -->
        <div class="lg:col-span-7 bg-white rounded-lg border border-slate-200 p-3.5 shadow-xs flex flex-col justify-between">
          <div>
            <div class="flex flex-wrap items-center justify-between gap-2 mb-2.5">
              <div>
                <h3 class="text-xs sm:text-sm font-extrabold text-[#004a8f] uppercase">
                  <i class="fa-solid fa-location-dot text-[#d9232a] mr-1"></i>Địa Chỉ Kho & Cửa Hàng: 72 Lê Hiến Mai, Hòa Khánh, Đà Nẵng
                </h3>
                <p class="text-[11.5px] text-slate-600">Cửa Hàng VLXD Thiên Tiến - Ke cân bằng gạch, Keo dán gạch Đà Nẵng</p>
              </div>
              <a 
                href="https://share.google/G5rwLiRcNdIYIXYJo" 
                target="_blank" 
                rel="noopener" 
                class="bg-[#004a8f] hover:bg-[#00356b] text-white text-xs font-bold px-3 py-1.5 rounded-lg transition inline-flex items-center gap-1.5"
              >
                <i class="fa-solid fa-diamond-turn-right"></i> Mở Google Maps Chỉ Đường
              </a>
            </div>

            <!-- Google Maps Embed trực tiếp 72 Lê Hiến Mai, Hòa Khánh, Đà Nẵng -->
            <div class="w-full h-64 sm:h-72 rounded-lg overflow-hidden border border-slate-300 relative bg-slate-100">
              <iframe 
                title="Bản đồ Công ty TNHH Thương Mại Xây Dựng Thiên Tiến - 72 Lê Hiến Mai, Hòa Khánh, Đà Nẵng"
                src="https://maps.google.com/maps?q=72%20L%C3%AA%20Hi%E1%BA%BFn%20Mai,%20H%C3%B2a%20Kh%C3%A1nh,%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed" 
                class="w-full h-full border-0" 
                allowfullscreen="" 
                loading="lazy" 
                referrerpolicy="no-referrer-when-downgrade"
              ></iframe>
            </div>
          </div>

          <div class="mt-2.5 pt-2 border-t border-slate-100 flex flex-wrap items-center justify-between gap-2 text-xs text-slate-600">
            <span><i class="fa-solid fa-clock text-[#00843d] mr-1"></i>Giờ mở cửa: Phục vụ tất cả các ngày trong tuần</span>
            <a href="https://share.google/G5rwLiRcNdIYIXYJo" target="_blank" rel="noopener" class="font-bold text-[#d9232a] hover:underline">
              Link Map: https://share.google/G5rwLiRcNdIYIXYJo
            </a>
          </div>
        </div>

        <!-- CỘT 2: FANPAGE FACEBOOK TRỰC TIẾP NGOÀI TRANG CHỦ -->
        <div class="lg:col-span-5 bg-white rounded-lg border border-slate-200 p-3.5 shadow-xs flex flex-col justify-between">
          <div>
            <div class="flex flex-wrap items-center justify-between gap-2 mb-2.5">
              <div>
                <h3 class="text-xs sm:text-sm font-extrabold text-[#004a8f] uppercase">
                  <i class="fa-brands fa-facebook text-blue-600 mr-1"></i>Fanpage Facebook Chính Thức
                </h3>
                <p class="text-[11.5px] text-slate-600">Ke cộng, ke cân bằng gạch, Keo dán gạch Đà Nẵng</p>
              </div>
              <a 
                href="https://www.facebook.com/keoplatdanang" 
                target="_blank" 
                rel="noopener" 
                class="bg-[#1877F2] hover:bg-blue-700 text-white text-xs font-bold px-3 py-1.5 rounded-lg transition inline-flex items-center gap-1.5"
              >
                <i class="fa-brands fa-facebook-f"></i> Theo Dõi Fanpage
              </a>
            </div>

            <!-- Thẻ Fanpage trực quan + Nhúng Facebook Plugin -->
            <div class="rounded-lg border border-slate-200 overflow-hidden bg-slate-50">
              <!-- Header Fanpage thực tế với ảnh cửa hàng & logo Thiên Tiến -->
              <div class="relative h-28 bg-gradient-to-r from-[#00356b] to-[#004a8f] overflow-hidden">
                <img 
                  src="https://lh3.googleusercontent.com/d/1QXRVO5z-x2uKV0fXiw4HkgVlwVgdDc2i" 
                  alt="Ảnh bìa Fanpage Thiên Tiến" 
                  class="w-full h-full object-cover opacity-55"
                  onerror="handleDriveImageFallback(this, '1QXRVO5z-x2uKV0fXiw4HkgVlwVgdDc2i', 'Fanpage Thiên Tiến')"
                >
                <div class="absolute inset-0 bg-gradient-to-t from-black/75 via-black/30 to-transparent flex items-end p-3">
                  <div class="flex items-center gap-2.5">
                    <img 
                      src="https://lh3.googleusercontent.com/d/1FRGwVdVqrXcQ0bFAU2c6FB6eHPbnT2y8" 
                      alt="Logo Fanpage" 
                      class="w-12 h-12 rounded-full border-2 border-white bg-white object-contain p-0.5 shrink-0"
                      onerror="handleDriveImageFallback(this, '1FRGwVdVqrXcQ0bFAU2c6FB6eHPbnT2y8', 'Logo')"
                    >
                    <div class="text-white min-w-0">
                      <a href="https://www.facebook.com/keoplatdanang" target="_blank" rel="noopener" class="font-bold text-xs sm:text-sm hover:underline block truncate">
                        Ke cộng, ke cân bằng gạch, Keo dán gạch Đà Nẵng
                      </a>
                      <span class="text-[11px] text-blue-200 block">@keoplatdanang • Cửa hàng VLXD Thiên Tiến</span>
                    </div>
                  </div>
                </div>
              </div>

              <!-- Facebook Page Plugin Iframe -->
              <div class="w-full flex justify-center bg-white py-2 overflow-hidden">
                <iframe 
                  title="Fanpage Ke cộng, ke cân bằng gạch, Keo dán gạch Đà Nẵng"
                  src="https://www.facebook.com/plugins/page.php?href=https%3A%2F%2Fwww.facebook.com%2Fkeoplatdanang&tabs=timeline&width=340&height=180&small_header=true&adapt_container_width=true&hide_cover=false&show_facepile=true" 
                  width="340" 
                  height="180" 
                  style="border:none;overflow:hidden;max-width:100%;" 
                  scrolling="no" 
                  frameborder="0" 
                  allowfullscreen="true" 
                  allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share"
                ></iframe>
              </div>
            </div>
          </div>

          <div class="mt-2.5 pt-2 border-t border-slate-100 flex flex-wrap items-center justify-between gap-2 text-xs">
            <span class="text-slate-600"><i class="fa-solid fa-check-circle text-blue-600 mr-1"></i>Cập nhật hàng về & công trình mỗi ngày</span>
            <a href="https://www.facebook.com/keoplatdanang" target="_blank" rel="noopener" class="font-bold text-[#004a8f] hover:underline">
              facebook.com/keoplatdanang
            </a>
          </div>
        </div>

      </div>
    </div>
  </section>

  <!-- =====================================================================
       12. FOOTER CHUẨN FLATSOME (Giống bố cục vlxdthailan.com)
       ===================================================================== -->
  <footer class="bg-[#002b54] text-white pt-8 pb-20 md:pb-8 border-t-4 border-[#d9232a]">
    <div class="flatsome-container">
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-12 gap-6 pb-6 border-b border-blue-800/80">

        <!-- Thông tin công ty -->
        <div class="lg:col-span-5 space-y-2.5">
          <div class="flex items-center gap-3">
            <img 
              src="https://lh3.googleusercontent.com/d/1FRGwVdVqrXcQ0bFAU2c6FB6eHPbnT2y8" 
              alt="Logo Công Ty TNHH Thương Mại Xây Dựng Thiên Tiến" 
              class="w-11 h-11 rounded-lg bg-white p-1 object-contain shrink-0"
              onerror="handleDriveImageFallback(this, '1FRGwVdVqrXcQ0bFAU2c6FB6eHPbnT2y8', 'THIÊN TIẾN')"
            >
            <div>
              <h3 class="text-sm sm:text-base font-extrabold text-yellow-300 leading-snug">
                CÔNG TY TNHH THƯƠNG MẠI XÂY DỰNG THIÊN TIẾN
              </h3>
              <p class="text-xs text-blue-200">Website chính thức: <strong>thientien.com</strong></p>
            </div>
          </div>
          <p class="text-xs text-blue-100 leading-relaxed">
            Chuyên Ke Cân Bằng, Keo chà ron Epoxy, Keo ốp lát gạch, đá: Dán cực nhanh, bền đẹp, tiết kiệm nhân công. Nhà phân phối uy tín các dòng keo dán gạch Cá Sấu (Crocodile), Cotto, Weber, chống thấm và hóa chất xây dựng tại Đà Nẵng.
          </p>
          <ul class="text-xs text-blue-100 space-y-1.5 pt-1">
            <li><i class="fa-solid fa-location-dot text-yellow-400 w-5"></i><strong>Địa chỉ:</strong> 72 Lê Hiến Mai, Hòa Khánh, Đà Nẵng</li>
            <li><i class="fa-solid fa-phone-volume text-yellow-400 w-5"></i><strong>Hotline / Zalo:</strong> <a href="tel:0966961431" class="text-yellow-300 font-bold hover:underline">0966.961.431</a> - <a href="tel:0901172864" class="text-yellow-300 font-bold hover:underline">0901.172.864</a></li>
            <li><i class="fa-solid fa-globe text-yellow-400 w-5"></i><strong>Website:</strong> <a href="https://thientien.com" class="hover:underline">https://thientien.com</a></li>
            <li><i class="fa-brands fa-facebook text-yellow-400 w-5"></i><strong>Fanpage:</strong> <a href="https://www.facebook.com/keoplatdanang" target="_blank" rel="noopener" class="hover:underline">facebook.com/keoplatdanang</a></li>
          </ul>
        </div>

        <!-- Danh mục sản phẩm (Giống vlxdthailan.com) -->
        <div class="lg:col-span-4 space-y-2">
          <h4 class="text-xs sm:text-sm font-extrabold uppercase text-yellow-300 border-b border-blue-800 pb-1.5">
            DANH MỤC SẢN PHẨM
          </h4>
          <ul class="grid grid-cols-1 sm:grid-cols-2 gap-1.5 text-xs text-blue-100">
            <li><a href="#san-pham" onclick="filterByCategory('ke-can-bang')" class="hover:text-yellow-300">› Ke Cân Bằng Lát Gạch</a></li>
            <li><a href="#san-pham" onclick="filterByCategory('ke-can-bang')" class="hover:text-yellow-300">› Nêm Cân Bằng & Kìm Bấm</a></li>
            <li><a href="#san-pham" onclick="filterByCategory('keo-cha-ron')" class="hover:text-yellow-300">› Keo Chà Ron Epoxy 2 Thành Phần</a></li>
            <li><a href="#san-pham" onclick="filterByCategory('keo-cha-ron')" class="hover:text-yellow-300">› Keo Chà Ron Cá Sấu Thái Lan</a></li>
            <li><a href="#san-pham" onclick="filterByCategory('keo-dan-gach')" class="hover:text-yellow-300">› Keo Dán Gạch Cá Sấu</a></li>
            <li><a href="#san-pham" onclick="filterByCategory('keo-cotto-weber')" class="hover:text-yellow-300">› Keo Dán Gạch Cotto Thái Lan</a></li>
            <li><a href="#san-pham" onclick="filterByCategory('keo-cotto-weber')" class="hover:text-yellow-300">› Keo Dán Gạch Weber</a></li>
            <li><a href="#san-pham" onclick="filterByCategory('chong-tham')" class="hover:text-yellow-300">› Vật Liệu Chống Thấm</a></li>
            <li><a href="#san-pham" onclick="filterByCategory('hoa-chat')" class="hover:text-yellow-300">› Vữa Rót Không Co Ngót</a></li>
            <li><a href="#san-pham" onclick="filterByCategory('ke-can-bang')" class="hover:text-yellow-300">› Dụng Cụ Thi Công Ốp Lát</a></li>
          </ul>
        </div>

        <!-- Chính sách khách hàng (Giống vlxdthailan.com) -->
        <div class="lg:col-span-3 space-y-2">
          <h4 class="text-xs sm:text-sm font-extrabold uppercase text-yellow-300 border-b border-blue-800 pb-1.5">
            CHÍNH SÁCH & HỖ TRỢ
          </h4>
          <ul class="space-y-1.5 text-xs text-blue-100">
            <li><a href="#baogia" class="hover:text-yellow-300">› Chính sách vận chuyển & giao hàng</a></li>
            <li><a href="#baogia" class="hover:text-yellow-300">› Chính sách chiết khấu đại lý & nhà thầu</a></li>
            <li><a href="#baogia" class="hover:text-yellow-300">› Chính sách thanh toán linh hoạt</a></li>
            <li><a href="#baogia" class="hover:text-yellow-300">› Chính sách bảo hành & đổi trả hàng</a></li>
            <li><a href="#bando-fanpage" class="hover:text-yellow-300">› Chỉ đường Google Maps đến kho</a></li>
          </ul>
        </div>

      </div>

      <div class="pt-4 flex flex-col sm:flex-row items-center justify-between text-xs text-blue-200 gap-2">
        <div>© Bản quyền thuộc về <strong>CÔNG TY TNHH THƯƠNG MẠI XÂY DỰNG THIÊN TIẾN</strong> (thientien.com).</div>
        <div>Địa chỉ: 72 Lê Hiến Mai, Hòa Khánh, Đà Nẵng | ĐT: 0966.961.431 - 0901.172.864</div>
      </div>
    </div>
  </footer>

  <!-- =====================================================================
       13. CÁC NÚT LIÊN HỆ NỔI BẬT (ZALO, FACEBOOK, HOTLINE)
           Tương thích tuyệt đối trên cả máy tính và điện thoại, không tràn viền
       ===================================================================== -->
  <div class="fixed left-3 bottom-4 z-50 flex flex-col gap-2.5">
    <!-- Nút Zalo -->
    <a 
      href="https://zalo.me/0966961431" 
      target="_blank" 
      rel="noopener"
      class="flex items-center gap-2 bg-[#0068ff] hover:bg-blue-700 text-white rounded-full p-2 sm:pr-3.5 shadow-lg transition group"
      title="Chat Zalo 0966.961.431"
    >
      <span class="w-8 h-8 rounded-full bg-white text-[#0068ff] font-black text-xs flex items-center justify-center shrink-0">
        Zalo
      </span>
      <span class="hidden sm:inline text-xs font-bold whitespace-nowrap">Chat Zalo: 0966.961.431</span>
    </a>

    <!-- Nút Facebook Fanpage -->
    <a 
      href="https://www.facebook.com/keoplatdanang" 
      target="_blank" 
      rel="noopener"
      class="flex items-center gap-2 bg-[#1877F2] hover:bg-blue-800 text-white rounded-full p-2 sm:pr-3.5 shadow-lg transition"
      title="Fanpage Facebook Thiên Tiến"
    >
      <span class="w-8 h-8 rounded-full bg-white text-[#1877F2] text-base flex items-center justify-center shrink-0">
        <i class="fa-brands fa-facebook-f"></i>
      </span>
      <span class="hidden sm:inline text-xs font-bold whitespace-nowrap">Fanpage Thiên Tiến</span>
    </a>

    <!-- Nút Hotline 1 -->
    <a 
      href="tel:0966961431" 
      class="pulse-btn flex items-center gap-2 bg-[#d9232a] hover:bg-red-700 text-white rounded-full p-2 pr-3.5 shadow-lg transition"
      title="Gọi ngay 0966.961.431"
    >
      <span class="w-8 h-8 rounded-full bg-white text-[#d9232a] text-sm flex items-center justify-center shrink-0">
        <i class="fa-solid fa-phone-volume"></i>
      </span>
      <span class="text-xs font-extrabold whitespace-nowrap">0966.961.431</span>
    </a>

    <!-- Nút Hotline 2 -->
    <a 
      href="tel:0901172864" 
      class="flex items-center gap-2 bg-[#00843d] hover:bg-emerald-800 text-white rounded-full p-2 pr-3.5 shadow-lg transition"
      title="Gọi ngay 0901.172.864"
    >
      <span class="w-8 h-8 rounded-full bg-white text-[#00843d] text-sm flex items-center justify-center shrink-0">
        <i class="fa-solid fa-phone"></i>
      </span>
      <span class="text-xs font-extrabold whitespace-nowrap">0901.172.864</span>
    </a>
  </div>

  <!-- =====================================================================
       MODAL XEM CHI TIẾT SẢN PHẨM / BÀI VIẾT (Thay thế hoàn toàn alert)
       ===================================================================== -->
  <div id="infoModal" class="fixed inset-0 bg-black/60 z-50 hidden items-center justify-center p-3">
    <div class="bg-white rounded-xl max-w-lg w-full p-4 sm:p-5 shadow-2xl border border-slate-200 max-h-[90vh] overflow-y-auto">
      <div class="flex items-start justify-between gap-2 border-b border-slate-200 pb-2.5 mb-3">
        <h3 id="modalTitle" class="text-sm sm:text-base font-extrabold text-[#004a8f]"></h3>
        <button type="button" onclick="closeInfoModal()" class="text-slate-400 hover:text-slate-700 text-lg leading-none px-1.5">
          <i class="fa-solid fa-xmark"></i>
        </button>
      </div>
      <div id="modalBody" class="text-xs sm:text-sm text-slate-700 space-y-3"></div>
      <div class="mt-4 pt-3 border-t border-slate-200 flex flex-wrap items-center justify-end gap-2">
        <a href="tel:0966961431" class="bg-[#d9232a] text-white text-xs font-bold px-3.5 py-2 rounded-lg">
          <i class="fa-solid fa-phone mr-1"></i>Gọi 0966.961.431
        </a>
        <a href="https://zalo.me/0966961431" target="_blank" rel="noopener" class="bg-[#004a8f] text-white text-xs font-bold px-3.5 py-2 rounded-lg">
          Chat Zalo Báo Giá
        </a>
        <button type="button" onclick="closeInfoModal()" class="bg-slate-200 text-slate-700 text-xs font-bold px-3.5 py-2 rounded-lg">
          Đóng
        </button>
      </div>
    </div>
  </div>

  <!-- =====================================================================
       JAVASCRIPT XỬ LÝ DỮ LIỆU SẢN PHẨM, ĐA TẦNG ẢNH GOOGLE DRIVE & SLIDER
       ===================================================================== -->
  <script>
    // Cơ chế tự động chuyển đổi link ảnh Google Drive đa tầng để luôn hiển thị mượt mà
    function handleDriveImageFallback(imgEl, driveId, labelText) {
      const step = parseInt(imgEl.getAttribute('data-fallback-step') || '0', 10);
      if (step === 0) {
        imgEl.setAttribute('data-fallback-step', '1');
        imgEl.src = 'https://drive.google.com/thumbnail?id=' + driveId + '&sz=w1000';
      } else if (step === 1) {
        imgEl.setAttribute('data-fallback-step', '2');
        imgEl.src = 'https://drive.google.com/uc?export=view&id=' + driveId;
      } else {
        imgEl.onerror = null;
        const encoded = encodeURIComponent(labelText || 'VLXD Thiên Tiến');
        imgEl.src = 'https://placehold.co/500x500/004a8f/ffffff?text=' + encoded;
      }
    }

    // 10 SẢN PHẨM THỰC TẾ LẤY TỪ 10 FILE GOOGLE DRIVE CỦA NGƯỜI DÙNG
    // Phân bổ chính xác vào các danh mục: Ke Cân Bằng, Keo Chà Ron Epoxy, Keo Ốp Lát Gạch Đá
    const realDriveProducts = [
      {
        id: 'sp-drive-1',
        driveId: '1aOVcsvLkloQrljF9f6yhMXmDrhz4O_LO',
        name: 'Ke Cân Bằng Lát Gạch Đá Phẳng Đều Đủ Kích Cỡ (1mm - 1.5mm - 2mm)',
        category: 'ke-can-bang',
        categoryLabel: 'Ke Cân Bằng & Dụng Cụ',
        oldPrice: '95.000đ',
        newPrice: '75.000đ / bịch',
        discount: '-21%',
        desc: 'Ke nhựa cân bằng gạch nguyên sinh dẻo dai, giúp căn chỉnh mặt phẳng gạch ốp lát cực nhanh, đều mạch và tiết kiệm nhân công.'
      },
      {
        id: 'sp-drive-2',
        driveId: '16nopd10IJNHmanj20BIjYIL6kRkr0gyF',
        name: 'Nêm Cân Bằng Gạch Tái Sử Dụng Loại Dày Chịu Lực Cao',
        category: 'ke-can-bang',
        categoryLabel: 'Ke Cân Bằng & Dụng Cụ',
        oldPrice: '110.000đ',
        newPrice: '85.000đ / bịch',
        discount: '-23%',
        desc: 'Nêm nhựa răng cưa dày dặn, tái sử dụng nhiều lần, kết hợp cùng ke cân bằng giữ hai viên gạch phẳng tuyệt đối khi keo khô.'
      },
      {
        id: 'sp-drive-3',
        driveId: '15h6ByzEzXdeJernXzIqDQG2_TphphG9C',
        name: 'Kìm Bấm Ke Cân Bằng Gạch Chuyên Dụng Cán Bọc Nhựa Êm Tay',
        category: 'ke-can-bang',
        categoryLabel: 'Ke Cân Bằng & Dụng Cụ',
        oldPrice: '150.000đ',
        newPrice: '115.000đ / cây',
        discount: '-23%',
        desc: 'Kìm rút ke cân bằng có ốc điều chỉnh lực siết chuẩn xác, giúp đẩy nêm vào ke nhanh gấp 3 lần và không làm sứt mẻ men gạch.'
      },
      {
        id: 'sp-drive-4',
        driveId: '1hbeMNQzqyu7Fa4hQ43I79GsHPm4eWZG9',
        name: 'Ke Chữ Thập Lát Gạch (Ke Cộng Nhựa Căn Đường Ron 1.5mm - 2mm - 3mm)',
        category: 'ke-can-bang',
        categoryLabel: 'Ke Cân Bằng & Dụng Cụ',
        oldPrice: '45.000đ',
        newPrice: '35.000đ / bịch',
        discount: '-22%',
        desc: 'Ke cộng chữ thập căn chỉnh đường ron gạch thẳng tắp, chuẩn kích thước cho cả gạch lát nền và gạch ốp tường.'
      },
      {
        id: 'sp-drive-5',
        driveId: '185nfwS4qj-KSNSzQvGXv12n0wnkAb05L',
        name: 'Keo Chà Ron Epoxy 2 Thành Phần Cao Cấp Chống Thấm & Chống Bám Bẩn',
        category: 'keo-cha-ron',
        categoryLabel: 'Keo Chà Ron Epoxy',
        oldPrice: '220.000đ',
        newPrice: '175.000đ / tuýp đôi',
        discount: '-20%',
        desc: 'Keo chít mạch Epoxy 2 thành phần bóng mịn như men sứ, chống thấm nước 100%, chống nấm mốc đen mạch, bền màu trên 15 năm.'
      },
      {
        id: 'sp-drive-6',
        driveId: '1P4RbqBqplmfy9RNb04FNqPDMQ8cDAavK',
        name: 'Bộ Súng Bắn Keo Chà Ron Epoxy 2 Thành Phần & Bi Cầu Vết Mạch Ron',
        category: 'keo-cha-ron',
        categoryLabel: 'Keo Chà Ron Epoxy',
        oldPrice: '195.000đ',
        newPrice: '155.000đ / bộ',
        discount: '-21%',
        desc: 'Dụng cụ thi công ron Epoxy chuyên nghiệp gồm súng bơm keo 2 thành phần, bộ bi cầu miết mạch và dao sủi keo thừa.'
      },
      {
        id: 'sp-drive-7',
        driveId: '192gYtipz1psUUHCR8njq9FvQQTlRuEz3',
        name: 'Keo Dán Gạch Đá Siêu Bám Dính Chuyên Dụng Gạch Khổ Lớn (Bao 25kg)',
        category: 'keo-dan-gach',
        categoryLabel: 'Keo Dán Gạch Đá',
        oldPrice: '265.000đ',
        newPrice: '215.000đ / bao',
        discount: '-19%',
        desc: 'Keo ốp lát gạch đá cường độ bám dính cao, dán cực nhanh, chống trượt và chống bong tróc cho gạch Granite, Porcelain, đá tự nhiên.'
      },
      {
        id: 'sp-drive-8',
        driveId: '1h99_nf2-InRhHgr5nkxsk1pUJj9U8i7K',
        name: 'Keo Dán Gạch Cá Sấu Thái Lan Crocodile Chính Hãng (Bao 20kg - 25kg)',
        category: 'keo-dan-gach',
        categoryLabel: 'Keo Dán Gạch Cá Sấu',
        oldPrice: '290.000đ',
        newPrice: '240.000đ / bao',
        discount: '-17%',
        desc: 'Keo dán gạch Cá Sấu Thái Lan chính hãng dùng cho nội ngoại thất, độ bám dính gấp 4 lần hồ dầu xi măng truyền thống.'
      },
      {
        id: 'sp-drive-9',
        driveId: '17weNbSbD9e-RlW58g4PU8r8joPnJzKNX',
        name: 'Keo Chà Ron Cá Sấu Crocodile Silver Premium Plus Chống Rêu Mốc',
        category: 'keo-cha-ron',
        categoryLabel: 'Keo Chà Ron Cá Sấu',
        oldPrice: '85.000đ',
        newPrice: '68.000đ / bao 1kg',
        discount: '-20%',
        desc: 'Keo chà ron kháng khuẩn chống nấm mốc công nghệ Microban Thái Lan, đường ron mịn đẹp và không bị rạn nứt.'
      },
      {
        id: 'sp-drive-10',
        driveId: '1aKtkIgF8aHwNVIzerwNIguZ7hols7IdT',
        name: 'Bàn Bả Răng Cưa Inox & Phụ Kiện Trét Keo Ốp Lát Gạch Đá Chuyên Nghiệp',
        category: 'ke-can-bang',
        categoryLabel: 'Ke Cân Bằng & Dụng Cụ',
        oldPrice: '90.000đ',
        newPrice: '70.000đ / cái',
        discount: '-22%',
        desc: 'Bàn bả răng cưa thép không gỉ giúp trải đều lớp keo dán gạch trên bề mặt sàn và tường, phủ kín 100% lưng gạch.'
      }
    ];

    // DANH MỤC SẢN PHẨM MỞ RỘNG THEO MẪU VLXDTHAILAN.COM
    const catalogProducts = [
      {
        id: 'sp-cat-1',
        driveId: '1h99_nf2-InRhHgr5nkxsk1pUJj9U8i7K',
        name: 'Keo Dán Gạch Cá Sấu Red Crocodile (Cá Sấu Đỏ - Bao 25kg)',
        category: 'keo-dan-gach',
        categoryLabel: 'Keo Dán Gạch Cá Sấu',
        oldPrice: '340.000đ',
        newPrice: '285.000đ / bao',
        discount: '-16%',
        desc: 'Chuyên dùng cho gạch Porcelain và gạch kích thước lớn nội ngoại thất, độ bám dính siêu cao.'
      },
      {
        id: 'sp-cat-2',
        driveId: '192gYtipz1psUUHCR8njq9FvQQTlRuEz3',
        name: 'Keo Dán Gạch Cotto Vàng (Yellow) & Cotto Xanh Thái Lan (Bao 25kg)',
        category: 'keo-cotto-weber',
        categoryLabel: 'Keo Dán Gạch Cotto',
        oldPrice: '250.000đ',
        newPrice: '198.000đ / bao',
        discount: '-21%',
        desc: 'Thương hiệu Cotto SCG Thái Lan chính hãng, thi công nhanh gọn, chống trượt gạch ốp tường hiệu quả.'
      },
      {
        id: 'sp-cat-3',
        driveId: '15h6ByzEzXdeJernXzIqDQG2_TphphG9C',
        name: 'Keo Dán Gạch Weber (Webertai Vis / Webertai Gres / Webertai Flex)',
        category: 'keo-cotto-weber',
        categoryLabel: 'Keo Dán Gạch Weber',
        oldPrice: '310.000đ',
        newPrice: '255.000đ / bao',
        discount: '-18%',
        desc: 'Giải pháp ốp lát gạch đá cao cấp từ tập đoàn Saint-Gobain Pháp, chuyên trị gạch khổ lớn và khu vực ẩm ướt.'
      },
      {
        id: 'sp-cat-4',
        driveId: '185nfwS4qj-KSNSzQvGXv12n0wnkAb05L',
        name: 'Chống Thấm Đàn Hồi 2 Thành Phần Crocodile Flex Shield 2K Thái Lan',
        category: 'chong-tham',
        categoryLabel: 'Chống Thấm Thái Lan',
        oldPrice: '890.000đ',
        newPrice: '740.000đ / bộ',
        discount: '-17%',
        desc: 'Vật liệu chống thấm gốc xi măng - polymer 2 thành phần siêu đàn hồi cho nhà vệ sinh, ban công, sân thượng, hồ bơi.'
      },
      {
        id: 'sp-cat-5',
        driveId: '17weNbSbD9e-RlW58g4PU8r8joPnJzKNX',
        name: 'Vữa Rót Không Co Ngót Crocodile GP Grout & Vữa Sửa Chữa Kết Cấu',
        category: 'hoa-chat',
        categoryLabel: 'Hoá Chất Xây Dựng',
        oldPrice: '320.000đ',
        newPrice: '265.000đ / bao',
        discount: '-17%',
        desc: 'Vữa rót tự chảy không co ngót cường độ cao dùng cho bệ máy, cổ ống xuyên sàn, mạch ngừng bê tông.'
      }
    ];

    // Hàm tạo HTML thẻ sản phẩm chuẩn Flatsome (Không nhãn dán thừa, chỉ có % giảm giá góc trên bên trái)
    function createProductCardHTML(item) {
      return `
        <div class="product-box" data-product-cat="${item.category}" data-product-name="${item.name.toLowerCase()}">
          <!-- Khung ảnh sản phẩm + % giảm giá góc trên bên trái giống Flatsome -->
          <div class="relative w-full pt-[92%] bg-white border-b border-slate-100 overflow-hidden">
            <div class="flatsome-badge-sale">${item.discount}</div>
            <img 
              src="https://lh3.googleusercontent.com/d/${item.driveId}" 
              alt="${item.name}" 
              class="absolute inset-0 w-full h-full object-contain p-2.5 hover:scale-105 transition duration-300"
              loading="lazy"
              onerror="handleDriveImageFallback(this, '${item.driveId}', '${item.categoryLabel}')"
            >
          </div>

          <!-- Nội dung sản phẩm: Tên sản phẩm đầy đủ không bị cắt chữ -->
          <div class="p-2.5 sm:p-3 flex-1 flex flex-col justify-between">
            <div>
              <div class="text-[10.5px] font-semibold text-slate-400 uppercase mb-1">${item.categoryLabel}</div>
              <h3 class="product-title-full">
                ${item.name}
              </h3>
            </div>

            <div class="pt-2 mt-1 border-t border-slate-100">
              <!-- Giá gốc & Giá giảm chuẩn Flatsome -->
              <div class="flex flex-wrap items-baseline gap-1.5 mb-2">
                <span class="text-[11px] text-slate-400 line-through">${item.oldPrice}</span>
                <span class="text-xs sm:text-sm font-extrabold text-[#d9232a]">${item.newPrice}</span>
              </div>

              <div class="grid grid-cols-2 gap-1.5">
                <button 
                  type="button" 
                  onclick="openProductModal('${item.id}')" 
                  class="bg-slate-100 hover:bg-slate-200 text-[#004a8f] text-[11px] font-bold py-1.5 px-2 rounded transition text-center"
                >
                  Chi tiết
                </button>
                <a 
                  href="#baogia" 
                  onclick="prefillQuoteProduct('${item.name.replace(/'/g, "\\'")}')"
                  class="bg-[#004a8f] hover:bg-[#d9232a] text-white text-[11px] font-bold py-1.5 px-2 rounded transition text-center"
                >
                  Đặt mua
                </a>
              </div>
            </div>
          </div>
        </div>
      `;
    }

    // Khởi tạo danh sách sản phẩm khi tải trang
    function renderAllProducts() {
      const realGrid = document.getElementById('realProductsGrid');
      const catGrid = document.getElementById('catalogProductsGrid');
      if (realGrid) {
        realGrid.innerHTML = realDriveProducts.map(createProductCardHTML).join('');
      }
      if (catGrid) {
        catGrid.innerHTML = catalogProducts.map(createProductCardHTML).join('');
      }
    }

    // Lọc sản phẩm theo danh mục
    function filterByCategory(categorySlug) {
      const buttons = document.querySelectorAll('.cat-filter-btn');
      buttons.forEach(btn => {
        if (btn.getAttribute('data-cat') === categorySlug) {
          btn.className = 'cat-filter-btn home-cat-pill px-3 py-2 rounded-lg bg-[#004a8f] text-white border border-[#004a8f]';
        } else {
          btn.className = 'cat-filter-btn home-cat-pill px-3 py-2 rounded-lg bg-slate-100 hover:bg-blue-50 text-slate-800 border border-slate-200';
        }
      });

      const cards = document.querySelectorAll('.product-box');
      cards.forEach(card => {
        const cardCat = card.getAttribute('data-product-cat');
        if (categorySlug === 'all' || cardCat === categorySlug) {
          card.style.display = 'flex';
        } else {
          card.style.display = 'none';
        }
      });
    }

    // Tìm kiếm sản phẩm
    function handleSearchSubmit(e) {
      e.preventDefault();
      const keyword = (document.getElementById('searchInput').value || '').trim().toLowerCase();
      const cards = document.querySelectorAll('.product-box');
      cards.forEach(card => {
        const name = card.getAttribute('data-product-name') || '';
        if (!keyword || name.includes(keyword)) {
          card.style.display = 'flex';
        } else {
          card.style.display = 'none';
        }
      });
      document.getElementById('san-pham').scrollIntoView({ behavior: 'smooth' });
    }

    // Bật/tắt menu trên điện thoại
    function toggleMobileMenu() {
      const drawer = document.getElementById('mobileMenuDrawer');
      if (drawer) {
        drawer.classList.toggle('hidden');
      }
    }

    // Điều khiển Banner tự trượt 2 slide
    let currentBannerIndex = 0;
    let bannerTimer = null;

    function showBannerSlide(index) {
      const slides = document.querySelectorAll('.banner-slide');
      const dots = document.querySelectorAll('.banner-dot');
      if (!slides.length) return;
      currentBannerIndex = (index + slides.length) % slides.length;
      slides.forEach((slide, i) => {
        slide.classList.toggle('active', i === currentBannerIndex);
      });
      dots.forEach((dot, i) => {
        dot.className = i === currentBannerIndex
          ? 'banner-dot w-2.5 h-2.5 rounded-full bg-yellow-400 transition'
          : 'banner-dot w-2.5 h-2.5 rounded-full bg-white/50 transition';
      });
    }

    function changeBannerSlide(step) {
      showBannerSlide(currentBannerIndex + step);
      resetBannerInterval();
    }

    function goToBannerSlide(index) {
      showBannerSlide(index);
      resetBannerInterval();
    }

    function resetBannerInterval() {
      if (bannerTimer) clearInterval(bannerTimer);
      bannerTimer = setInterval(() => {
        showBannerSlide(currentBannerIndex + 1);
      }, 5500);
    }

    // Điền sẵn tên sản phẩm vào form báo giá
    function prefillQuoteProduct(productName) {
      const noteEl = document.getElementById('quoteNote');
      if (noteEl) {
        noteEl.value = 'Tôi cần tư vấn & báo giá sản phẩm: ' + productName;
      }
    }

    // Xử lý gửi Form Báo Giá (Không dùng alert)
    function handleQuoteSubmit(e) {
      e.preventDefault();
      const name = document.getElementById('quoteName').value.trim();
      const phone = document.getElementById('quotePhone').value.trim();
      const cat = document.getElementById('quoteCategory').value;
      const qty = document.getElementById('quoteQty').value.trim();
      const box = document.getElementById('quoteSuccessBox');

      box.innerHTML = `
        <div class="font-bold text-emerald-900 mb-1"><i class="fa-solid fa-circle-check mr-1"></i>Đã tiếp nhận yêu cầu báo giá thành công!</div>
        <div>Cảm ơn anh/chị <strong>${name}</strong> (SĐT: <strong>${phone}</strong>). Bộ phận kinh doanh <strong>VLXD Thiên Tiến</strong> sẽ liên hệ tư vấn danh mục <strong>${cat}</strong> ${qty ? '(' + qty + ')' : ''} ngay lập tức. Cần gấp vui lòng gọi <a href="tel:0966961431" class="underline font-bold">0966.961.431</a> hoặc <a href="tel:0901172864" class="underline font-bold">0901.172.864</a>.</div>
      `;
      box.classList.remove('hidden');
    }

    // Xem chi tiết sản phẩm trong Modal
    function openProductModal(productId) {
      const all = [...realDriveProducts, ...catalogProducts];
      const item = all.find(p => p.id === productId);
      if (!item) return;

      document.getElementById('modalTitle').textContent = item.name;
      document.getElementById('modalBody').innerHTML = `
        <div class="w-full h-56 bg-slate-50 rounded-lg border border-slate-200 flex items-center justify-center p-2">
          <img src="https://lh3.googleusercontent.com/d/${item.driveId}" alt="${item.name}" class="max-h-full max-w-full object-contain" onerror="handleDriveImageFallback(this, '${item.driveId}', '${item.categoryLabel}')">
        </div>
        <div class="flex items-center gap-3">
          <span class="bg-[#d9232a] text-white text-xs font-bold px-2.5 py-1 rounded-full">Giảm ${item.discount}</span>
          <span class="text-slate-400 line-through text-xs">${item.oldPrice}</span>
          <span class="text-base font-extrabold text-[#d9232a]">${item.newPrice}</span>
        </div>
        <p class="leading-relaxed">${item.desc}</p>
        <div class="bg-blue-50 p-3 rounded-lg border border-blue-100 text-xs space-y-1">
          <div><strong>Đơn vị phân phối:</strong> CÔNG TY TNHH THƯƠNG MẠI XÂY DỰNG THIÊN TIẾN</div>
          <div><strong>Địa chỉ kho:</strong> 72 Lê Hiến Mai, Hòa Khánh, Đà Nẵng</div>
          <div><strong>Hotline / Zalo:</strong> 0966.961.431 - 0901.172.864</div>
        </div>
      `;
      const modal = document.getElementById('infoModal');
      modal.classList.remove('hidden');
      modal.classList.add('flex');
    }

    // Dữ liệu chi tiết 4 bài viết trang chủ
    const articlesData = [
      {
        title: 'Hướng dẫn sử dụng Ke Cân Bằng và Nêm Lát Gạch giúp mặt sàn phẳng đẹp tuyệt đối',
        content: 'Ke cân bằng gạch kết hợp cùng nêm nhựa và kìm bấm ke là giải pháp thi công ốp lát hiện đại giúp bề mặt sàn và tường phẳng đều tuyệt đối, không bị chênh mí giữa các viên gạch khổ lớn (60x60, 80x80, 60x120, 100x100). Nhờ đó thợ thi công rút ngắn được 40% thời gian căn chỉnh và tiết kiệm tối đa chi phí nhân công.'
      },
      {
        title: 'Vì sao Keo Chà Ron Epoxy 2 thành phần thay thế hoàn toàn bột chà ron truyền thống?',
        content: 'Keo chà ron Epoxy 2 thành phần có cấu tạo từ nhựa Epoxy cao cấp và chất đóng rắn, tạo nên đường mạch bóng mịn như men sứ, chống thấm nước 100%, không bị ố vàng hay đen mạch sau nhiều năm sử dụng. Đặc biệt phù hợp cho phòng khách, phòng tắm, bếp và sảnh khách sạn.'
      },
      {
        title: 'Nguyên nhân gạch ốp lát bị bộp, phồng rộp và giải pháp dùng Keo Dán Gạch Cá Sấu, Cotto',
        content: 'Các dòng gạch Porcelain, Granite và đá tự nhiên ngày nay có kết cấu đặc chắc, ít hút nước nên hồ dầu xi măng truyền thống không thể bám dính bền vững. Sử dụng keo dán gạch chuyên dụng Cá Sấu (Crocodile), Cotto hoặc Weber giúp tăng độ bám dính gấp 3-4 lần, chống trượt và chống bong tróc vĩnh viễn.'
      },
      {
        title: 'Địa chỉ mua Ke Cân Bằng, Keo Dán Gạch, Keo Chà Ron Epoxy uy tín giá sỉ tại Đà Nẵng',
        content: 'CÔNG TY TNHH THƯƠNG MẠI XÂY DỰNG THIÊN TIẾN (72 Lê Hiến Mai, Hòa Khánh, Đà Nẵng - Hotline: 0966.961.431 - 0901.172.864) là tổng kho phân phối trực tiếp ke cân bằng gạch, keo chà ron Epoxy, keo dán gạch Cá Sấu, Cotto, Weber chính hãng với mức chiết khấu tốt nhất cho đại lý và nhà thầu.'
      }
    ];

    function openArticleModal(idx) {
      const art = articlesData[idx];
      if (!art) return;
      document.getElementById('modalTitle').textContent = art.title;
      document.getElementById('modalBody').innerHTML = `
        <p class="leading-relaxed">${art.content}</p>
        <div class="bg-slate-100 p-3 rounded-lg text-xs space-y-1">
          <div><strong>Tư vấn kỹ thuật miễn phí:</strong> 0966.961.431 - 0901.172.864</div>
          <div><strong>Địa chỉ:</strong> 72 Lê Hiến Mai, Hòa Khánh, Đà Nẵng (thientien.com)</div>
        </div>
      `;
      const modal = document.getElementById('infoModal');
      modal.classList.remove('hidden');
      modal.classList.add('flex');
    }

    function closeInfoModal() {
      const modal = document.getElementById('infoModal');
      modal.classList.add('hidden');
      modal.classList.remove('flex');
    }

    window.onload = function () {
      renderAllProducts();
      resetBannerInterval();
    };
  </script>
</body>
</html>
