<!DOCTYPE html>
<html lang="si">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kumara Construction | ගෙදරක පදනමේ සිට සියලුම ඉදිකිරීම්</title>
    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Noto+Sans+Sinhala:wght@400;700&display=swap" rel="stylesheet">
    <!-- Font Awesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    
    <style>
        body { font-family: 'Noto Sans Sinhala', sans-serif; }
        .navbar { background-color: #002D62; } /* Navy Blue from logo */
        .hero-section {
            background: linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.6)), url('https://images.unsplash.com/photo-1503387762-592eda58ef47?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80');
            background-size: cover;
            color: white;
            padding: 100px 0;
            text-align: center;
        }
        .btn-primary { background-color: #f1c40f; border: none; color: #000; font-weight: bold; }
        .btn-primary:hover { background-color: #d4ac0d; }
        .service-card { border: none; transition: 0.3s; box-shadow: 0 4px 8px rgba(0,0,0,0.1); }
        .service-card:hover { transform: translateY(-10px); }
        .footer { background-color: #222; color: white; padding: 30px 0; }
    </style>
</head>
<body>

    <!-- Navbar -->
    <nav class="navbar navbar-expand-lg navbar-dark sticky-top">
        <div class="container">
            <a class="navbar-brand fw-bold" href="#">KUMARA CONSTRUCTION</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item"><a class="nav-link" href="#home">මුල් පිටුව</a></li>
                    <li class="nav-item"><a class="nav-link" href="#services">සේවාවන්</a></li>
                    <li class="nav-item"><a class="nav-link" href="#contact">සම්බන්ධ කරගන්න</a></li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section class="hero-section" id="home">
        <div class="container">
            <h1 class="display-4 fw-bold">කුමාර කන්ස්ට්‍රක්ෂන්</h1>
            <p class="lead">ගෙදරක පදනමේ සිට සියලුම ඉදිකිරීම් කටයුතු විශ්වාසවන්තව නිම කරවා ගැනීමට අපව අමතන්න.</p>
            <a href="https://wa.me/94756400137" class="btn btn-primary btn-lg mt-3"><i class="fab fa-whatsapp"></i> WhatsApp කරන්න</a>
        </div>
    </section>

    <!-- Services Section -->
    <section class="container my-5" id="services">
        <h2 class="text-center mb-5 fw-bold">අපගේ සේවාවන්</h2>
        <div class="row g-4">
            <div class="col-md-4">
                <div class="card service-card h-100 text-center p-4">
                    <i class="fas fa-home fa-3x mb-3 text-primary"></i>
                    <h4>නව නිවාස ඉදිකිරීම</h4>
                    <p>ඔබේ සිහින නිවස උසස් ප්‍රමිතියෙන් යුතුව නිම කර දෙනු ලැබේ.</p>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card service-card h-100 text-center p-4">
                    <i class="fas fa-tools fa-3x mb-3 text-primary"></i>
                    <h4>අලුත්වැඩියා කිරීම්</h4>
                    <p>පැරණි නිවාස අලුත්වැඩියා කිරීම සහ නවීකරණය කිරීම.</p>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card service-card h-100 text-center p-4">
                    <i class="fas fa-fill-drip fa-3x mb-3 text-primary"></i>
                    <h4>මේසන් සහ ටයිල් වැඩ</h4>
                    <p>සියලුම වර්ගයේ මේසන් වැඩ සහ ටයිල් ඇල්ලීමේ කටයුතු මැනවින් සිදු කරයි.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section class="bg-light py-5" id="contact">
        <div class="container text-center">
            <h2 class="fw-bold">අපව සම්බන්ධ කරගන්න</h2>
            <p class="mt-3">විශ්වාසවන්ත සේවාවක් සඳහා අදම කතා කරන්න</p>
            <h3><i class="fas fa-phone"></i> 075 640 0137</h3>
            <div class="mt-4">
                <a href="https://wa.me/94756400137" class="btn btn-success me-2"><i class="fab fa-whatsapp"></i> WhatsApp</a>
                <a href="tel:0756400137" class="btn btn-primary"><i class="fas fa-phone-alt"></i> Call Now</a>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="footer text-center">
        <div class="container">
            <p>© 2026 Kumara Construction. All Rights Reserved.</p>
            <small>Designed with passion</small>
        </div>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
