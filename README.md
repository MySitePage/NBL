
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Naliss by Lia | OC Nails & Toes Specialist</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Dancing+Script:wght@400;500;600;700&family=Poppins:wght@300;400;500;600&display=swap" rel="stylesheet">
    <style>
        /* Elegant Color Palette - UPDATED WITH PINK OUTLINES */
        :root {
            --soft-pink: #FFE4E9; /* Very light pink */
            --blush: #F8C8DC; /* Blush pink */
            --rose: #E8A0BF; /* Rose pink */
            --dusty-rose: #C86B85; /* Dusty rose */
            --taupe: #A67F78; /* Taupe brown */
            --cream: #FFF9F5; /* Cream background */
            --gold: #E6B87B; /* Soft gold */
            --text: #5D4037; /* Dark brown for text */
            --pink-outline: #FF69B4; /* Added for pink outlines */
            --transition: all 0.4s ease;
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        html {
            scroll-behavior: smooth;
        }
        
        body {
            font-family: 'Poppins', sans-serif;
            line-height: 1.7;
            color: var(--text);
            background-color: var(--cream);
            overflow-x: hidden;
        }
        
        h1, h2, h3, h4 {
            font-family: 'Dancing Script', cursive;
            font-weight: 600;
            margin-bottom: 1.2rem;
        }
        
        h1 {
            font-size: 4rem;
            line-height: 1.1;
        }
        
        h2 {
            font-size: 3rem;
            position: relative;
            display: inline-block;
            margin-bottom: 2rem;
        }
        
        h2:after {
            content: '';
            position: absolute;
            bottom: -10px;
            left: 0;
            width: 100px;
            height: 2px;
            background: var(--dusty-rose);
        }
        
        p {
            margin-bottom: 1.5rem;
            font-weight: 300;
        }
        
        a {
            text-decoration: none;
            color: inherit;
        }
        
        .container {
            width: 90%;
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }
        
        section {
            padding: 80px 0;
        }
        
        .btn {
            display: inline-flex;
            align-items: center;
            justify-content: center;
            background-color: var(--dusty-rose);
            color: white;
            padding: 14px 32px;
            border-radius: 30px;
            font-weight: 500;
            transition: var(--transition);
            border: none;
            cursor: pointer;
            font-size: 1rem;
            letter-spacing: 0.5px;
            box-shadow: 0 5px 15px rgba(200, 107, 133, 0.2);
        }
        
        .btn:hover {
            background-color: var(--rose);
            transform: translateY(-3px);
            box-shadow: 0 8px 20px rgba(200, 107, 133, 0.3);
        }
        
        .btn-outline {
            background-color: transparent;
            border: 2px solid var(--dusty-rose);
            color: var(--dusty-rose);
        }
        
        .btn-outline:hover {
            background-color: var(--dusty-rose);
            color: white;
        }
        
        .btn i {
            margin-right: 8px;
        }
        
        .section-title {
            text-align: center;
            margin-bottom: 3rem;
        }
        
        .section-title h2:after {
            left: 50%;
            transform: translateX(-50%);
        }
        
        /* Header */
        header {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            z-index: 1000;
            padding: 20px 0;
            background-color: rgba(255, 249, 245, 0.95);
            box-shadow: 0 3px 15px rgba(166, 127, 120, 0.08);
            transition: var(--transition);
        }
        
        .header-container {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        
        .logo {
            font-family: 'Dancing Script', cursive;
            font-size: 2.5rem;
            font-weight: 700;
            color: var(--dusty-rose);
            display: flex;
            align-items: center;
        }
        
        .logo span {
            color: var(--taupe);
        }
        
        .logo i {
            margin-right: 10px;
            color: var(--gold);
        }
        
        nav ul {
            display: flex;
            list-style: none;
        }
        
        nav ul li {
            margin-left: 35px;
        }
        
        nav ul li a {
            font-weight: 500;
            position: relative;
            padding: 5px 0;
            font-size: 1.05rem;
            color: var(--text);
        }
        
        nav ul li a:after {
            content: '';
            position: absolute;
            bottom: 0;
            left: 0;
            width: 0;
            height: 2px;
            background-color: var(--dusty-rose);
            transition: var(--transition);
        }
        
        nav ul li a:hover:after,
        nav ul li a.active:after {
            width: 100%;
        }
        
        .mobile-toggle {
            display: none;
            font-size: 1.5rem;
            cursor: pointer;
            color: var(--text);
        }
        
        /* Hero Section */
        .hero {
            height: 100vh;
            background: linear-gradient(rgba(255, 249, 245, 0.9), rgba(255, 249, 245, 0.8)), 
                        url('https://images.unsplash.com/photo-1604654894610-df63bc536371?ixlib=rb-4.0.3&auto=format&fit=crop&w=1770&q=80');
            background-size: cover;
            background-position: center;
            display: flex;
            align-items: center;
            position: relative;
            overflow: hidden;
        }
        
        .hero-content {
            max-width: 700px;
        }
        
        .hero-content h1 {
            margin-bottom: 1.5rem;
            color: var(--dusty-rose);
        }
        
        .hero-content p {
            font-size: 1.2rem;
            margin-bottom: 2.5rem;
            color: var(--taupe);
        }
        
        .hero-stats {
            display: flex;
            gap: 40px;
            margin-top: 3rem;
        }
        
        .stat-item {
            text-align: center;
        }
        
        .stat-number {
            font-size: 2.5rem;
            font-weight: 700;
            color: var(--dusty-rose);
            font-family: 'Dancing Script', cursive;
        }
        
        .stat-label {
            font-size: 0.9rem;
            text-transform: uppercase;
            letter-spacing: 1.5px;
            color: var(--taupe);
        }
        
        .hero-decoration {
            position: absolute;
            right: 5%;
            bottom: 0;
            width: 400px;
            height: 500px;
            background: url('https://images.unsplash.com/photo-160777909f53e0b0f00a92ec4b728e7f?ixlib=rb-4.0.3&auto=format&fit=crop&w=800&q=80') center/cover no-repeat;
            border-radius: 40% 40% 0 0;
            box-shadow: 0 20px 40px rgba(0, 0, 0, 0.08);
        }
        
        /* About Section */
        .about {
            background-color: var(--soft-pink);
            position: relative;
        }
        
        .about-container {
            display: flex;
            align-items: center;
            gap: 60px;
        }
        
        .about-image {
            flex: 1;
            border-radius: 20px;
            overflow: hidden;
            box-shadow: 0 15px 30px rgba(0, 0, 0, 0.1);
        }
        
        .about-image img {
            width: 100%;
            height: auto;
            display: block;
            transition: var(--transition);
        }
        
        .about-image:hover img {
            transform: scale(1.05);
        }
        
        .about-content {
            flex: 1;
        }
        
        .about-content h2 {
            margin-bottom: 1.5rem;
        }
        
        .about-features {
            margin-top: 2rem;
        }
        
        .feature-item {
            display: flex;
            align-items: center;
            margin-bottom: 1.5rem;
        }
        
        .feature-icon {
            width: 50px;
            height: 50px;
            background-color: var(--blush);
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            margin-right: 15px;
            color: var(--dusty-rose);
            font-size: 1.2rem;
        }
        
        /* Gallery Section - WITH PINK OUTLINES */
        .gallery {
            background-color: white;
        }
        
        .gallery-container {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            gap: 25px;
        }
        
        .gallery-item {
            border-radius: 15px;
            overflow: hidden;
            position: relative;
            height: 350px;
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.05);
            transition: var(--transition);
            /* PINK OUTLINE ADDED HERE */
            border: 3px solid var(--pink-outline);
        }
        
        .gallery-item:hover {
            transform: translateY(-8px);
            box-shadow: 0 15px 30px rgba(0, 0, 0, 0.1);
            /* THICKER OUTLINE ON HOVER */
            border: 4px solid var(--pink-outline);
        }
        
        .gallery-item img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            transition: var(--transition);
        }
        
        .gallery-item:hover img {
            transform: scale(1.1);
        }
        
        .gallery-overlay {
            position: absolute;
            bottom: 0;
            left: 0;
            right: 0;
            background: linear-gradient(to top, rgba(200, 107, 133, 0.8), transparent);
            color: white;
            padding: 25px 20px 15px;
            transform: translateY(20px);
            opacity: 0;
            transition: var(--transition);
        }
        
        .gallery-item:hover .gallery-overlay {
            transform: translateY(0);
            opacity: 1;
        }
        
        /* Services Section */
        .services {
            background-color: var(--soft-pink);
        }
        
        .services-container {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(350px, 1fr));
            gap: 30px;
        }
        
        .service-card {
            background-color: white;
            border-radius: 15px;
            overflow: hidden;
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.05);
            transition: var(--transition);
            padding: 40px 30px;
            text-align: center;
        }
        
        .service-card:hover {
            transform: translateY(-8px);
            box-shadow: 0 15px 35px rgba(0, 0, 0, 0.1);
        }
        
        .service-icon {
            width: 80px;
            height: 80px;
            background-color: var(--blush);
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            margin: 0 auto 25px;
            color: var(--dusty-rose);
            font-size: 2rem;
        }
        
        .service-card h3 {
            margin-bottom: 15px;
            color: var(--text);
        }
        
        .service-price {
            font-size: 1.8rem;
            font-weight: 700;
            color: var(--dusty-rose);
            margin: 15px 0;
            font-family: 'Dancing Script', cursive;
        }
        
        /* Pages */
        .page {
            display: none;
            min-height: calc(100vh - 80px);
            padding-top: 120px;
        }
        
        .page.active {
            display: block;
            animation: fadeIn 0.5s ease;
        }
        
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
        
        /* Booking Page */
        .booking-page {
            background-color: var(--soft-pink);
        }
        
        .booking-container {
            max-width: 1000px;
            margin: 0 auto;
            background-color: white;
            border-radius: 20px;
            padding: 60px;
            box-shadow: 0 20px 40px rgba(0, 0, 0, 0.05);
        }
        
        .form-row {
            display: flex;
            gap: 20px;
            margin-bottom: 25px;
        }
        
        .form-group {
            flex: 1;
        }
        
        .form-group label {
            display: block;
            margin-bottom: 8px;
            font-weight: 500;
            color: var(--text);
        }
        
        .form-control {
            width: 100%;
            padding: 15px 20px;
            border: 1px solid var(--blush);
            background-color: var(--cream);
            border-radius: 10px;
            color: var(--text);
            font-size: 1rem;
            font-family: 'Poppins', sans-serif;
            transition: var(--transition);
        }
        
        .form-control:focus {
            outline: none;
            border-color: var(--dusty-rose);
            box-shadow: 0 0 0 3px rgba(200, 107, 133, 0.1);
        }
        
        select.form-control {
            appearance: none;
            background-image: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='16' height='16' fill='%23C86B85' viewBox='0 0 16 16'%3E%3Cpath d='M7.247 11.14 2.451 5.658C1.885 5.013 2.345 4 3.204 4h9.592a1 1 0 0 1 .753 1.659l-4.796 5.48a1 1 0 0 1-1.506 0z'/%3E%3C/svg%3E");
            background-repeat: no-repeat;
            background-position: right 20px center;
            background-size: 16px;
        }
        
        .booking-info {
            margin-top: 40px;
            padding: 30px;
            background-color: var(--blush);
            border-radius: 15px;
        }
        
        .booking-info h3 {
            color: var(--dusty-rose);
            margin-bottom: 20px;
            font-size: 2rem;
        }
        
        .info-item {
            display: flex;
            align-items: flex-start;
            margin-bottom: 20px;
        }
        
        .info-icon {
            background-color: var(--dusty-rose);
            color: white;
            width: 40px;
            height: 40px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            margin-right: 15px;
            font-size: 1.2rem;
        }
        
        /* Contact Section */
        .contact {
            background-color: white;
        }
        
        .contact-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 40px;
        }
        
        .contact-form {
            background-color: var(--soft-pink);
            padding: 40px;
            border-radius: 15px;
        }
        
        .contact-info {
            padding: 20px;
        }
        
        .contact-item {
            display: flex;
            align-items: flex-start;
            margin-bottom: 30px;
        }
        
        .contact-icon {
            background-color: var(--blush);
            width: 50px;
            height: 50px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            margin-right: 15px;
            color: var(--dusty-rose);
            font-size: 1.2rem;
        }
        
        /* Footer */
        footer {
            background-color: var(--text);
            color: white;
            padding: 80px 0 30px;
        }
        
        .footer-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 40px;
            margin-bottom: 50px;
        }
        
        .footer-column h4 {
            color: var(--gold);
            margin-bottom: 25px;
            font-size: 1.5rem;
        }
        
        .footer-logo {
            font-family: 'Dancing Script', cursive;
            font-size: 2.5rem;
            font-weight: 700;
            color: white;
            margin-bottom: 20px;
            display: block;
        }
        
        .footer-logo span {
            color: var(--blush);
        }
        
        .social-links {
            display: flex;
            gap: 15px;
            margin-top: 20px;
        }
        
        .social-links a {
            display: inline-flex;
            align-items: center;
            justify-content: center;
            width: 45px;
            height: 45px;
            background-color: rgba(255, 255, 255, 0.1);
            border-radius: 50%;
            font-size: 1.2rem;
            transition: var(--transition);
        }
        
        .social-links a:hover {
            background-color: var(--dusty-rose);
            transform: translateY(-5px);
        }
        
        .footer-links {
            list-style: none;
        }
        
        .footer-links li {
            margin-bottom: 12px;
        }
        
        .footer-links a {
            transition: var(--transition);
        }
        
        .footer-links a:hover {
            color: var(--blush);
            padding-left: 5px;
        }
        
        .contact-info-list {
            list-style: none;
        }
        
        .contact-info-list li {
            display: flex;
            align-items: flex-start;
            margin-bottom: 20px;
        }
        
        .contact-info-list i {
            color: var(--gold);
            margin-right: 15px;
            font-size: 1.2rem;
            margin-top: 5px;
        }
        
        .copyright {
            text-align: center;
            padding-top: 30px;
            border-top: 1px solid rgba(255, 255, 255, 0.1);
            color: rgba(255, 255, 255, 0.6);
            font-size: 0.9rem;
        }
        
        /* Responsive Styles */
        @media (max-width: 1100px) {
            .hero-decoration {
                width: 350px;
                height: 450px;
            }
            
            h1 {
                font-size: 3.5rem;
            }
            
            h2 {
                font-size: 2.8rem;
            }
        }
        
        @media (max-width: 992px) {
            .hero-decoration {
                display: none;
            }
            
            .about-container {
                flex-direction: column;
            }
            
            .about-image {
                width: 100%;
                max-width: 500px;
            }
            
            .form-row {
                flex-direction: column;
                gap: 0;
            }
            
            .booking-container {
                padding: 40px;
            }
        }
        
        @media (max-width: 768px) {
            .mobile-toggle {
                display: block;
            }
            
            nav {
                position: fixed;
                top: 80px;
                left: 0;
                width: 100%;
                background-color: var(--cream);
                padding: 20px;
                transform: translateY(-100%);
                opacity: 0;
                transition: var(--transition);
                box-shadow: 0 10px 20px rgba(0, 0, 0, 0.1);
                z-index: 999;
            }
            
            nav.active {
                transform: translateY(0);
                opacity: 1;
            }
            
            nav ul {
                flex-direction: column;
            }
            
            nav ul li {
                margin: 15px 0;
            }
            
            h1 {
                font-size: 3rem;
            }
            
            h2 {
                font-size: 2.5rem;
            }
            
            section {
                padding: 60px 0;
            }
            
            .hero-stats {
                flex-direction: column;
                gap: 20px;
            }
            
            .page {
                padding-top: 100px;
            }
        }
        
        @media (max-width: 576px) {
            h1 {
                font-size: 2.5rem;
            }
            
            h2 {
                font-size: 2.2rem;
            }
            
            .btn {
                padding: 12px 25px;
            }
            
            .gallery-container {
                grid-template-columns: 1fr;
            }
            
            .services-container {
                grid-template-columns: 1fr;
            }
            
            .hero {
                height: auto;
                padding: 150px 0 100px;
            }
            
            .booking-container {
                padding: 30px 20px;
            }
        }
    </style>
</head>
<body>
    <!-- Header -->
    <header>
        <div class="container header-container">
            <a href="#home" class="logo" data-page="home">
                <i class="fas fa-spa"></i> Naliss<span>byLia</span>
            </a>
            
            <div class="mobile-toggle">
                <i class="fas fa-bars"></i>
            </div>
            
            <nav>
                <ul>
                    <li><a href="#home" class="nav-link active" data-page="home">Home</a></li>
                    <li><a href="#about" class="nav-link" data-page="about">About</a></li>
                    <li><a href="#gallery" class="nav-link" data-page="gallery">Gallery</a></li>
                    <li><a href="#services" class="nav-link" data-page="services">Services</a></li>
                    <li><a href="#booking" class="nav-link" data-page="booking">Booking</a></li>
                    <li><a href="#contact" class="nav-link" data-page="contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <!-- Home Page -->
    <section class="page active" id="home">
        <section class="hero">
            <div class="container">
                <div class="hero-content">
                    <h1>OC Nails & Toes Specialist</h1>
                    <p>Welcome to my home-based studio where I create beautiful nails with meticulous attention to detail. I specialize in custom designs, pedicures, and nail art that reflect your unique style.</p>
                    
                    <div class="hero-stats">
                        <div class="stat-item">
                            <div class="stat-number">355+</div>
                            <div class="stat-label">Creations</div>
                        </div>
                        <div class="stat-item">
                            <div class="stat-number">1,883</div>
                            <div class="stat-label">Followers</div>
                        </div>
                        <div class="stat-item">
                            <div class="stat-number">575</div>
                            <div class="stat-label">Following</div>
                        </div>
                    </div>
                    
                    <a href="#booking" class="btn nav-link" data-page="booking">
                        <i class="far fa-calendar-check"></i> Book Appointment
                    </a>
                </div>
                
                <div class="hero-decoration"></div>
            </div>
        </section>

        <!-- About Section -->
        <section class="about" id="about">
            <div class="container">
                <div class="about-container">
                    <div class="about-image">
                        <img src="https://www.dropbox.com/scl/fi/uzygrqt079oha5x46op0a/IMG_7388.jpeg?rlkey=i0ectcykrx6rm7i2yym3n9h34&st=21r0856i&raw=1" alt="Nail Technician">
                    </div>
                    
                    <div class="about-content">
                        <h2>Meet Lia</h2>
                        <p>Hello! I'm Lia, your Orange County nails and toes specialist. With a passion for nail art and an eye for detail, I transform nails into beautiful works of art.</p>
                        <p>My home-based studio offers a comfortable, private, and hygienic environment where you can relax while I create the perfect nails for you.</p>
                        
                        <div class="about-features">
                            <div class="feature-item">
                                <div class="feature-icon">
                                    <i class="fas fa-shield-alt"></i>
                                </div>
                                <div>
                                    <h4>Safety First</h4>
                                    <p>Face masks required. All tools are sterilized and disposable items are single-use only.</p>
                                </div>
                            </div>
                            
                            <div class="feature-item">
                                <div class="feature-icon">
                                    <i class="fas fa-home"></i>
                                </div>
                                <div>
                                    <h4>Home-Based Studio</h4>
                                    <p>Enjoy personalized service in a comfortable, private setting in Orange County.</p>
                                </div>
                            </div>
                            
                            <div class="feature-item">
                                <div class="feature-icon">
                                    <i class="fas fa-palette"></i>
                                </div>
                                <div>
                                    <h4>Custom Designs</h4>
                                    <p>Specializing in custom nail art that reflects your personality and style.</p>
                                </div>
                            </div>
                        </div>
                        
                        <a href="#gallery" class="btn btn-outline nav-link" data-page="gallery">View My Work</a>
                    </div>
                </div>
            </div>
        </section>

        <!-- Gallery Section WITH PINK OUTLINES AND UPDATED 6TH IMAGE -->
        <section class="gallery" id="gallery">
            <div class="container">
                <div class="section-title">
                    <h2>My Work</h2>
                    <p>Browse through my latest nail creations and get inspired for your next appointment.</p>
                </div>
                
                <div class="gallery-container">
                    <div class="gallery-item">
                        <img src="https://www.dropbox.com/scl/fi/qk51rx0q3odg06eni4w65/IMG_7382.jpeg?rlkey=mruvj49ij64mfxiewdd5c83pu&st=vog5akwy&raw=1" alt="Nail Design 1">
                        <div class="gallery-overlay">
                            <h4>French Tip Elegance</h4>
                            <p>Classic french tips with a modern twist</p>
                        </div>
                    </div>
                    
                    <div class="gallery-item">
                        <img src="https://www.dropbox.com/scl/fi/muj3fzyjy5kjruwh9ofaz/IMG_7381.jpeg?rlkey=624jv4kdf3ya1l1waazr0g28q&st=refzgl3h&raw=1" alt="Nail Design 2">
                        <div class="gallery-overlay">
                            <h4>Floral Nail Art</h4>
                            <p>Delicate hand-painted flowers</p>
                        </div>
                    </div>
                    
                    <div class="gallery-item">
                        <img src="https://www.dropbox.com/scl/fi/rd1iibea89ikl6gnr30t5/IMG_7383.jpeg?rlkey=zjvkf9vh2nf6uh31w7sccuyr5&st=2o5ucaa2&raw=1" alt="Nail Design 3">
                        <div class="gallery-overlay">
                            <h4>Glitter Gradient</h4>
                            <p>Sparkly ombre effect</p>
                        </div>
                    </div>
                    
                    <div class="gallery-item">
                        <img src="https://www.dropbox.com/scl/fi/9y70tpkjcy1khf0goitbg/IMG_7384.jpeg?rlkey=xajpabu2f6q7kltw6kxweah1r&st=15buvhqu&raw=1" alt="Nail Design 4">
                        <div class="gallery-overlay">
                            <h4>Geometric Design</h4>
                            <p>Modern geometric patterns</p>
                        </div>
                    </div>
                    
                    <div class="gallery-item">
                        <img src="https://www.dropbox.com/scl/fi/grm9g5tfdxhb0fpq7tniq/IMG_7386.jpeg?rlkey=5m5130o8sa58mpq2v9vppdalx&st=bpfmmpw7&raw=1" alt="Nail Design 5">
                        <div class="gallery-overlay">
                            <h4>Marble Effect</h4>
                            <p>Elegant marble nails</p>
                        </div>
                    </div>
                    
                    <!-- UPDATED 6TH IMAGE WITH YOUR NEW LINK -->
                    <div class="gallery-item">
                        <img src="https://www.dropbox.com/scl/fi/69ami1qcfzfumy1qrg7on/IMG_7389.jpeg?rlkey=f9a3iq7amkt3iysbslw2gq7ht&st=9c8sh53s&raw=1" alt="Nail Design 6">
                        <div class="gallery-overlay">
                            <h4>Custom Nail Art</h4>
                            <p>Beautiful custom design</p>
                        </div>
                    </div>
                </div>
            </div>
        </section>
    </section>

    <!-- About Page -->
    <section class="page" id="about-page">
        <div class="container">
            <div class="section-title">
                <h2>About Me</h2>
                <p>Get to know me and my nail artistry journey</p>
            </div>
            
            <div class="about-container">
                <div class="about-image">
                    <img src="https://www.dropbox.com/scl/fi/uzygrqt079oha5x46op0a/IMG_7388.jpeg?rlkey=i0ectcykrx6rm7i2yym3n9h34&st=21r0856i&raw=1" alt="Nail Technician">
                </div>
                
                <div class="about-content">
                    <h2>Meet Lia</h2>
                    <p>Hello! I'm Lia, your Orange County nails and toes specialist. With a passion for nail art and an eye for detail, I transform nails into beautiful works of art.</p>
                    <p>My home-based studio offers a comfortable, private, and hygienic environment where you can relax while I create the perfect nails for you.</p>
                    
                    <div class="about-features">
                        <div class="feature-item">
                            <div class="feature-icon">
                                <i class="fas fa-shield-alt"></i>
                            </div>
                            <div>
                                <h4>Safety First</h4>
                                <p>Face masks required. All tools are sterilized and disposable items are single-use only.</p>
                            </div>
                        </div>
                        
                        <div class="feature-item">
                            <div class="feature-icon">
                                <i class="fas fa-home"></i>
                            </div>
                            <div>
                                <h4>Home-Based Studio</h4>
                                <p>Enjoy personalized service in a comfortable, private setting in Orange County.</p>
                            </div>
                        </div>
                        
                        <div class="feature-item">
                            <div class="feature-icon">
                                <i class="fas fa-palette"></i>
                            </div>
                            <div>
                                <h4>Custom Designs</h4>
                                <p>Specializing in custom nail art that reflects your personality and style.</p>
                            </div>
                        </div>
                    </div>
                    
                    <a href="#booking" class="btn nav-link" data-page="booking">Book Appointment</a>
                </div>
            </div>
        </div>
    </section>

    <!-- Gallery Page -->
    <section class="page" id="gallery-page">
        <div class="container">
            <div class="section-title">
                <h2>Gallery</h2>
                <p>Browse through my latest nail creations</p>
            </div>
            
            <div class="gallery-container">
                <div class="gallery-item">
                    <img src="https://www.dropbox.com/scl/fi/qk51rx0q3odg06eni4w65/IMG_7382.jpeg?rlkey=mruvj49ij64mfxiewdd5c83pu&st=vog5akwy&raw=1" alt="Nail Design 1">
                    <div class="gallery-overlay">
                        <h4>French Tip Elegance</h4>
                        <p>Classic french tips with a modern twist</p>
                    </div>
                </div>
                
                <div class="gallery-item">
                    <img src="https://www.dropbox.com/scl/fi/muj3fzyjy5kjruwh9ofaz/IMG_7381.jpeg?rlkey=624jv4kdf3ya1l1waazr0g28q&st=refzgl3h&raw=1" alt="Nail Design 2">
                    <div class="gallery-overlay">
                        <h4>Floral Nail Art</h4>
                        <p>Delicate hand-painted flowers</p>
                    </div>
                </div>
                
                <div class="gallery-item">
                    <img src="https://www.dropbox.com/scl/fi/rd1iibea89ikl6gnr30t5/IMG_7383.jpeg?rlkey=zjvkf9vh2nf6uh31w7sccuyr5&st=2o5ucaa2&raw=1" alt="Nail Design 3">
                    <div class="gallery-overlay">
                        <h4>Glitter Gradient</h4>
                        <p>Sparkly ombre effect</p>
                    </div>
                </div>
                
                <div class="gallery-item">
                    <img src="https://www.dropbox.com/scl/fi/9y70tpkjcy1khf0goitbg/IMG_7384.jpeg?rlkey=xajpabu2f6q7kltw6kxweah1r&st=15buvhqu&raw=1" alt="Nail Design 4">
                    <div class="gallery-overlay">
                        <h4>Geometric Design</h4>
                        <p>Modern geometric patterns</p>
                    </div>
                </div>
                
                <div class="gallery-item">
                    <img src="https://www.dropbox.com/scl/fi/grm9g5tfdxhb0fpq7tniq/IMG_7386.jpeg?rlkey=5m5130o8sa58mpq2v9vppdalx&st=bpfmmpw7&raw=1" alt="Nail Design 5">
                    <div class="gallery-overlay">
                        <h4>Marble Effect</h4>
                        <p>Elegant marble nails</p>
                    </div>
                </div>
                
                <div class="gallery-item">
                    <img src="https://www.dropbox.com/scl/fi/69ami1qcfzfumy1qrg7on/IMG_7389.jpeg?rlkey=f9a3iq7amkt3iysbslw2gq7ht&st=9c8sh53s&raw=1" alt="Nail Design 6">
                    <div class="gallery-overlay">
                        <h4>Custom Nail Art</h4>
                        <p>Beautiful custom design</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Services Page -->
    <section class="page" id="services">
        <div class="container">
            <div class="section-title">
                <h2>My Services</h2>
                <p>I offer a range of nail services to keep your hands and feet looking beautiful.</p>
            </div>
            
            <div class="services-container">
                <div class="service-card">
                    <div class="service-icon">
                        <i class="fas fa-hand-sparkles"></i>
                    </div>
                    <h3>Classic Manicure</h3>
                    <p>Includes shaping, cuticle care, exfoliation, moisturizing massage, and polish application.</p>
                    <div class="service-price">$35+</div>
                    <a href="#booking" class="btn nav-link" data-page="booking">Book Now</a>
                </div>
                
                <div class="service-card">
                    <div class="service-icon">
                        <i class="fas fa-gem"></i>
                    </div>
                    <h3>Gel Manicure</h3>
                    <p>Long-lasting gel polish that stays perfect for up to 3 weeks. Chip-resistant and shiny.</p>
                    <div class="service-price">$50+</div>
                    <a href="#booking" class="btn nav-link" data-page="booking">Book Now</a>
                </div>
                
                <div class="service-card">
                    <div class="service-icon">
                        <i class="fas fa-foot-prints"></i>
                    </div>
                    <h3>Signature Pedicure</h3>
                    <p>Luxurious foot treatment including soak, exfoliation, massage, and polish application.</p>
                    <div class="service-price">$55+</div>
                    <a href="#booking" class="btn nav-link" data-page="booking">Book Now</a>
                </div>
                
                <div class="service-card">
                    <div class="service-icon">
                        <i class="fas fa-paint-brush"></i>
                    </div>
                    <h3>Nail Art Design</h3>
                    <p>Custom nail art including hand-painted designs, gems, foils, and intricate patterns.</p>
                    <div class="service-price">$10+</div>
                    <a href="#booking" class="btn nav-link" data-page="booking">Book Now</a>
                </div>
                
                <div class="service-card">
                    <div class="service-icon">
                        <i class="fas fa-plus-circle"></i>
                    </div>
                    <h3>Nail Extensions</h3>
                    <p>Acrylic or gel extensions to add length and strength to your natural nails.</p>
                    <div class="service-price">$70+</div>
                    <a href="#booking" class="btn nav-link" data-page="booking">Book Now</a>
                </div>
                
                <div class="service-card">
                    <div class="service-icon">
                        <i class="fas fa-heart"></i>
                    </div>
                    <h3>Nail Repair</h3>
                    <p>Fix broken or damaged nails with professional repair techniques.</p>
                    <div class="service-price">$15+</div>
                    <a href="#booking" class="btn nav-link" data-page="booking">Book Now</a>
                </div>
            </div>
        </div>
    </section>

    <!-- Booking Page -->
    <section class="page booking-page" id="booking">
        <div class="container">
            <div class="section-title">
                <h2>Book an Appointment</h2>
                <p>Ready to get beautiful nails? Fill out the form below to request an appointment.</p>
            </div>
            
            <div class="booking-container">
                <form id="bookingForm">
                    <div class="form-row">
                        <div class="form-group">
                            <label for="name">Full Name</label>
                            <input type="text" id="name" class="form-control" placeholder="Your name" required>
                        </div>
                        
                        <div class="form-group">
                            <label for="phone">Phone Number</label>
                            <input type="tel" id="phone" class="form-control" placeholder="(123) 456-7890" required>
                        </div>
                    </div>
                    
                    <div class="form-row">
                        <div class="form-group">
                            <label for="email">Email Address</label>
                            <input type="email" id="email" class="form-control" placeholder="you@example.com" required>
                        </div>
                        
                        <div class="form-group">
                            <label for="date">Preferred Date</label>
                            <input type="date" id="date" class="form-control" required>
                        </div>
                    </div>
                    
                    <div class="form-row">
                        <div class="form-group">
                            <label for="service">Service Type</label>
                            <select id="service" class="form-control" required>
                                <option value="">Select a service</option>
                                <option value="manicure">Classic Manicure</option>
                                <option value="gel-manicure">Gel Manicure</option>
                                <option value="pedicure">Signature Pedicure</option>
                                <option value="nail-art">Nail Art Design</option>
                                <option value="extensions">Nail Extensions</option>
                                <option value="repair">Nail Repair</option>
                                <option value="full-set">Full Set (Manicure + Pedicure)</option>
                            </select>
                        </div>
                        
                        <div class="form-group">
                            <label for="time">Preferred Time</label>
                            <select id="time" class="form-control" required>
                                <option value="">Select time</option>
                                <option value="10:00">10:00 AM</option>
                                <option value="11:00">11:00 AM</option>
                                <option value="12:00">12:00 PM</option>
                                <option value="13:00">1:00 PM</option>
                                <option value="14:00">2:00 PM</option>
                                <option value="15:00">3:00 PM</option>
                                <option value="16:00">4:00 PM</option>
                                <option value="17:00">5:00 PM</option>
                            </select>
                        </div>
                    </div>
                    
                    <div class="form-group">
                        <label for="message">Special Requests or Details</label>
                        <textarea id="message" class="form-control" rows="4" placeholder="Tell me about your nail ideas, any allergies, or special requirements..."></textarea>
                    </div>
                    
                    <button type="submit" class="btn" style="width: 100%;">
                        <i class="far fa-paper-plane"></i> Send Booking Request
                    </button>
                </form>
                
                <div class="booking-info">
                    <h3><i class="fas fa-info-circle"></i> Important Information</h3>
                    <div class="info-item">
                        <div class="info-icon">
                            <i class="fas fa-mask"></i>
                        </div>
                        <div>
                            <h4>Face Masks Required</h4>
                            <p>For the safety of both of us, face masks are required for all appointments.</p>
                        </div>
                    </div>
                    
                    <div class="info-item">
                        <div class="info-icon">
                            <i class="fas fa-home"></i>
                        </div>
                        <div>
                            <h4>Home-Based Studio</h4>
                            <p>I work from a comfortable, private home studio in Orange County. Address provided upon booking confirmation.</p>
                        </div>
                    </div>
                    
                    <div class="info-item">
                        <div class="info-icon">
                            <i class="fas fa-clock"></i>
                        </div>
                        <div>
                            <h4>Cancellation Policy</h4>
                            <p>24-hour notice required for cancellations or rescheduling to avoid fees.</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Page -->
    <section class="page contact" id="contact">
        <div class="container">
            <div class="section-title">
                <h2>Contact Me</h2>
                <p>Get in touch for any questions or to schedule your appointment</p>
            </div>
            
            <div class="contact-container">
                <div class="contact-form">
                    <h3>Send a Message</h3>
                    <form id="contactForm">
                        <div class="form-group">
                            <label for="contact-name">Name</label>
                            <input type="text" id="contact-name" class="form-control" required>
                        </div>
                        
                        <div class="form-group">
                            <label for="contact-email">Email</label>
                            <input type="email" id="contact-email" class="form-control" required>
                        </div>
                        
                        <div class="form-group">
                            <label for="contact-subject">Subject</label>
                            <input type="text" id="contact-subject" class="form-control" required>
                        </div>
                        
                        <div class="form-group">
                            <label for="contact-message">Message</label>
                            <textarea id="contact-message" class="form-control" rows="5" required></textarea>
                        </div>
                        
                        <button type="submit" class="btn">Send Message</button>
                    </form>
                </div>
                
                <div class="contact-info">
                    <h3>Contact Information</h3>
                    
                    <div class="contact-item">
                        <div class="contact-icon">
                            <i class="fas fa-map-marker-alt"></i>
                        </div>
                        <div>
                            <h4>Location</h4>
                            <p>Orange County, CA<br>Home Based Studio</p>
                        </div>
                    </div>
                    
                    <div class="contact-item">
                        <div class="contact-icon">
                            <i class="fas fa-phone"></i>
                        </div>
                        <div>
                            <h4>Phone</h4>
                            <p>(503) 555-NAIL</p>
                            <p>Text preferred for quickest response</p>
                        </div>
                    </div>
                    
                    <div class="contact-item">
                        <div class="contact-icon">
                            <i class="fas fa-envelope"></i>
                        </div>
                        <div>
                            <h4>Email</h4>
                            <p>lia@nalissbylia.com</p>
                        </div>
                    </div>
                    
                    <div class="contact-item">
                        <div class="contact-icon">
                            <i class="fas fa-clock"></i>
                        </div>
                        <div>
                            <h4>Hours</h4>
                            <p>Tuesday - Saturday: 10am - 6pm</p>
                            <p>Sunday & Monday: Closed</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <div class="container">
            <div class="footer-container">
                <div class="footer-column">
                    <a href="#home" class="footer-logo nav-link" data-page="home">Naliss<span>byLia</span></a>
                    <p>Orange County Nails & Toes Specialist creating beautiful, custom nail art in a comfortable home-based studio.</p>
                    
                    <div class="social-links">
                        <a href="#"><i class="fab fa-instagram"></i></a>
                        <a href="#"><i class="fab fa-tiktok"></i></a>
                        <a href="#"><i class="fab fa-pinterest"></i></a>
                        <a href="#"><i class="fab fa-facebook-f"></i></a>
                    </div>
                </div>
                
                <div class="footer-column">
                    <h4>Quick Links</h4>
                    <ul class="footer-links">
                        <li><a href="#home" class="nav-link" data-page="home">Home</a></li>
                        <li><a href="#about" class="nav-link" data-page="about">About Me</a></li>
                        <li><a href="#gallery" class="nav-link" data-page="gallery">Gallery</a></li>
                        <li><a href="#services" class="nav-link" data-page="services">Services</a></li>
                        <li><a href="#booking" class="nav-link" data-page="booking">Booking</a></li>
                        <li><a href="#contact" class="nav-link" data-page="contact">Contact</a></li>
                    </ul>
                </div>
                
                <div class="footer-column">
                    <h4>Contact Info</h4>
                    <ul class="contact-info-list">
                        <li>
                            <i class="fas fa-map-marker-alt"></i>
                            <div>
                                <strong>Location</strong>
                                <p>Orange County, CA<br>Home Based Studio</p>
                            </div>
                        </li>
                        <li>
                            <i class="fas fa-phone"></i>
                            <div>
                                <strong>Phone</strong>
                                <p>(503) 555-NAIL</p>
                            </div>
                        </li>
                        <li>
                            <i class="fas fa-envelope"></i>
                            <div>
                                <strong>Email</strong>
                                <p>lia@nalissbylia.com</p>
                            </div>
                        </li>
                    </ul>
                </div>
            </div>
            
            <div class="copyright">
                <p>&copy; 2023 Naliss by Lia. All rights reserved. | Orange County Nails & Toes Specialist</p>
                <p>Face masks required • Home Based Studio • ONLY ACCOUNT</p>
            </div>
        </div>
    </footer>

    <script>
        // Mobile Navigation Toggle
        const mobileToggle = document.querySelector('.mobile-toggle');
        const nav = document.querySelector('nav');
        
        mobileToggle.addEventListener('click', () => {
            nav.classList.toggle('active');
        });
        
        // Page Navigation
        const navLinks = document.querySelectorAll('.nav-link');
        const pages = document.querySelectorAll('.page');
        
        navLinks.forEach(link => {
            link.addEventListener('click', (e) => {
                e.preventDefault();
                
                // Get the target page id
                const targetPage = link.getAttribute('data-page');
                
                // Hide all pages
                pages.forEach(page => {
                    page.classList.remove('active');
                });
                
                // Show target page
                if(targetPage === 'about') {
                    document.getElementById('about-page').classList.add('active');
                } else if(targetPage === 'gallery') {
                    document.getElementById('gallery-page').classList.add('active');
                } else {
                    document.getElementById(targetPage).classList.add('active');
                }
                
                // Update active nav link
                navLinks.forEach(navLink => {
                    navLink.classList.remove('active');
                });
                link.classList.add('active');
                
                // Close mobile menu if open
                nav.classList.remove('active');
                
                // Scroll to top
                window.scrollTo(0, 0);
            });
        });
        
        // Form Submissions
        const bookingForm = document.getElementById('bookingForm');
        const contactForm = document.getElementById('contactForm');
        
        bookingForm.addEventListener('submit', (e) => {
            e.preventDefault();
            
            // Get form values
            const name = document.getElementById('name').value;
            const service = document.getElementById('service').value;
            
            // Show success message
            alert(`Thank you ${name}! Your ${service} appointment request has been sent. I'll contact you within 24 hours to confirm.`);
            
            // Reset form
            bookingForm.reset();
        });
        
        contactForm.addEventListener('submit', (e) => {
            e.preventDefault();
            alert('Thank you for your message! I\'ll respond as soon as possible.');
            contactForm.reset();
        });
        
        // Sticky header on scroll
        window.addEventListener('scroll', () => {
            const header = document.querySelector('header');
            if(window.scrollY > 100) {
                header.style.padding = '15px 0';
                header.style.boxShadow = '0 5px 15px rgba(166, 127, 120, 0.15)';
            } else {
                header.style.padding = '20px 0';
                header.style.boxShadow = '0 3px 15px rgba(166, 127, 120, 0.08)';
            }
        });
        
        // Set minimum date for booking to today
        const dateInput = document.getElementById('date');
        if(dateInput) {
            const today = new Date();
            const formattedDate = today.toISOString().split('T')[0];
            dateInput.min = formattedDate;
        }
        
        // Gallery image hover effect enhancement
        const galleryItems = document.querySelectorAll('.gallery-item');
        galleryItems.forEach(item => {
            item.addEventListener('mouseenter', () => {
                item.style.transform = 'translateY(-8px) scale(1.02)';
            });
            
            item.addEventListener('mouseleave', () => {
                item.style.transform = 'translateY(0) scale(1)';
            });
        });
        
        // Handle initial page load
        window.addEventListener('DOMContentLoaded', () => {
            // Check URL hash for direct page access
            const hash = window.location.hash.substring(1);
            if(hash && document.getElementById(hash)) {
                // Hide all pages
                pages.forEach(page => {
                    page.classList.remove('active');
                });
                
                // Show the page from hash
                document.getElementById(hash).classList.add('active');
                
                // Update active nav link
                navLinks.forEach(link => {
                    link.classList.remove('active');
                    if(link.getAttribute('data-page') === hash) {
                        link.classList.add('active');
                    }
                });
            }
        });
    </script>
</body>
</html>
