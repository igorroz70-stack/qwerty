<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Стяжка пола в Донецке | Профессиональные услуги по устройству полов</title>
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;500;600;700&family=Roboto:wght@300;400;500&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        :root {
            --primary: #E67E22;
            --secondary: #2C3E50;
            --accent: #2980B9;
            --light: #F9F9F9;
            --dark: #333333;
            --gray: #777777;
            --shadow: 0 5px 15px rgba(0,0,0,0.08);
            --transition: all 0.3s ease;
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Roboto', sans-serif;
            color: var(--dark);
            line-height: 1.6;
            background-color: white;
            overflow-x: hidden;
        }
        
        h1, h2, h3, h4, h5, h6 {
            font-family: 'Montserrat', sans-serif;
            font-weight: 700;
            margin-bottom: 1rem;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 15px;
        }
        
        .section {
            padding: 80px 0;
        }
        
        .section-title {
            text-align: center;
            margin-bottom: 50px;
            font-size: 2.2rem;
            color: var(--secondary);
            position: relative;
        }
        
        .section-title::after {
            content: '';
            display: block;
            width: 60px;
            height: 4px;
            background: var(--primary);
            margin: 15px auto;
            border-radius: 2px;
        }
        
        .btn {
            display: inline-flex;
            align-items: center;
            gap: 10px;
            background: var(--primary);
            color: white;
            padding: 14px 28px;
            border-radius: 4px;
            text-decoration: none;
            font-weight: 600;
            transition: var(--transition);
            border: none;
            cursor: pointer;
            box-shadow: var(--shadow);
            text-transform: uppercase;
            font-size: 14px;
        }
        
        .btn:hover {
            background: #D35400;
            transform: translateY(-2px);
        }
        
        .btn-outline {
            background: transparent;
            border: 2px solid var(--primary);
            color: var(--primary);
        }
        
        .btn-outline:hover {
            background: var(--primary);
            color: white;
        }
        
        /* Header */
        header {
            background: white;
            padding: 15px 0;
            position: fixed;
            width: 100%;
            top: 0;
            z-index: 1000;
            box-shadow: var(--shadow);
            transition: var(--transition);
        }
        
        .header-container {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        
        .logo {
            display: flex;
            align-items: center;
            gap: 10px;
            font-size: 1.5rem;
            font-weight: 700;
            color: var(--secondary);
            text-decoration: none;
        }
        
        .logo-img {
            width: 40px;
            height: 40px;
            background: var(--primary);
            border-radius: 4px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            font-size: 1rem;
        }
        
        nav ul {
            display: flex;
            list-style: none;
            gap: 25px;
        }
        
        nav ul li a {
            color: var(--secondary);
            text-decoration: none;
            font-weight: 500;
            transition: var(--transition);
            position: relative;
            font-size: 15px;
        }
        
        nav ul li a::after {
            content: '';
            position: absolute;
            bottom: -5px;
            left: 0;
            width: 0;
            height: 2px;
            background: var(--primary);
            transition: var(--transition);
        }
        
        nav ul li a:hover::after {
            width: 100%;
        }
        
        .header-contact {
            display: flex;
            flex-direction: column;
            align-items: flex-end;
            gap: 5px;
        }
        
        .phone {
            font-weight: 700;
            font-size: 1.1rem;
            color: var(--secondary);
            text-decoration: none;
        }
        
        .callback {
            font-size: 0.85rem;
            color: var(--primary);
            text-decoration: none;
            font-weight: 500;
        }
        
        .mobile-menu-btn {
            display: none;
            font-size: 1.5rem;
            background: none;
            border: none;
            color: var(--secondary);
            cursor: pointer;
        }
        
        /* Hero Section */
        .hero {
            background: linear-gradient(rgba(0, 0, 0, 0.7), rgba(0, 0, 0, 0.7)), url('https://images.unsplash.com/photo-1595428774223-ef52624120d2?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1770&q=80') no-repeat center center/cover;
            color: white;
            text-align: center;
            padding: 160px 0 100px;
            margin-top: 70px;
        }
        
        .hero-content {
            max-width: 800px;
            margin: 0 auto;
        }
        
        .hero h1 {
            font-size: 2.8rem;
            margin-bottom: 20px;
            line-height: 1.2;
        }
        
        .hero p {
            font-size: 1.2rem;
            margin-bottom: 40px;
            opacity: 0.9;
        }
        
        .hero-buttons {
            display: flex;
            gap: 15px;
            justify-content: center;
            margin-bottom: 50px;
        }
        
        .hero-features {
            display: flex;
            justify-content: center;
            gap: 40px;
            margin-top: 30px;
        }
        
        .hero-feature {
            display: flex;
            align-items: center;
            gap: 10px;
            font-size: 1rem;
        }
        
        .hero-feature i {
            color: var(--primary);
            font-size: 1.3rem;
        }
        
        /* Advantages */
        .advantages {
            background: var(--light);
            position: relative;
        }
        
        .advantages-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 25px;
        }
        
        .advantage-item {
            background: white;
            padding: 30px 25px;
            border-radius: 8px;
            text-align: center;
            box-shadow: var(--shadow);
            transition: var(--transition);
        }
        
        .advantage-item:hover {
            transform: translateY(-5px);
        }
        
        .advantage-icon {
            width: 70px;
            height: 70px;
            background: rgba(230, 126, 34, 0.1);
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            margin: 0 auto 20px;
            font-size: 1.8rem;
            color: var(--primary);
        }
        
        .advantage-item h3 {
            margin-bottom: 15px;
            color: var(--secondary);
            font-size: 1.2rem;
        }
        
        .advantage-item p {
            color: var(--gray);
            font-size: 0.95rem;
        }
        
        /* Services */
        .services {
            background: white;
        }
        
        .services-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
            gap: 25px;
        }
        
        .service-item {
            background: white;
            border-radius: 8px;
            overflow: hidden;
            box-shadow: var(--shadow);
            transition: var(--transition);
            border: 1px solid #eee;
        }
        
        .service-item:hover {
            transform: translateY(-5px);
        }
        
        .service-img {
            height: 200px;
            overflow: hidden;
            position: relative;
        }
        
        .service-img img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            transition: var(--transition);
        }
        
        .service-item:hover .service-img img {
            transform: scale(1.05);
        }
        
        .service-content {
            padding: 20px;
        }
        
        .service-content h3 {
            color: var(--secondary);
            margin-bottom: 12px;
            font-size: 1.3rem;
        }
        
        .service-content p {
            color: var(--gray);
            margin-bottom: 15px;
            font-size: 0.95rem;
        }
        
        .service-features {
            margin: 15px 0;
        }
        
        .service-feature {
            display: flex;
            align-items: center;
            gap: 8px;
            margin-bottom: 8px;
            color: var(--gray);
            font-size: 0.9rem;
        }
        
        .service-feature i {
            color: var(--primary);
            font-size: 0.8rem;
        }
        
        .price {
            color: var(--primary);
            font-weight: 700;
            font-size: 1.2rem;
            margin: 15px 0;
            display: block;
        }
        
        /* About */
        .about {
            background: var(--light);
        }
        
        .about-content {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 40px;
            align-items: center;
        }
        
        .about-text h2 {
            color: var(--secondary);
            margin-bottom: 20px;
            font-size: 2rem;
        }
        
        .about-text p {
            margin-bottom: 20px;
            color: var(--gray);
            line-height: 1.7;
        }
        
        .about-stats {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 15px;
            margin: 30px 0;
        }
        
        .stat-item {
            text-align: center;
            padding: 15px;
            background: white;
            border-radius: 8px;
            box-shadow: var(--shadow);
        }
        
        .stat-number {
            font-size: 2rem;
            font-weight: 700;
            color: var(--primary);
            margin-bottom: 5px;
        }
        
        .stat-text {
            color: var(--gray);
            font-size: 0.85rem;
        }
        
        .about-img {
            position: relative;
        }
        
        .about-img-main {
            border-radius: 8px;
            overflow: hidden;
            box-shadow: var(--shadow);
        }
        
        .about-img-main img {
            width: 100%;
            height: auto;
            display: block;
        }
        
        /* Portfolio */
        .portfolio {
            background: white;
        }
        
        .portfolio-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
        }
        
        .portfolio-item {
            position: relative;
            border-radius: 8px;
            overflow: hidden;
            height: 250px;
            cursor: pointer;
        }
        
        .portfolio-img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            transition: var(--transition);
        }
        
        .portfolio-overlay {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: linear-gradient(to top, rgba(44, 62, 80, 0.9), transparent);
            color: white;
            display: flex;
            flex-direction: column;
            justify-content: flex-end;
            padding: 20px;
            opacity: 0;
            transition: var(--transition);
        }
        
        .portfolio-item:hover .portfolio-overlay {
            opacity: 1;
        }
        
        .portfolio-item:hover .portfolio-img {
            transform: scale(1.1);
        }
        
        .portfolio-category {
            background: var(--primary);
            color: white;
            padding: 4px 12px;
            border-radius: 20px;
            font-size: 0.75rem;
            margin-bottom: 10px;
            display: inline-block;
        }
        
        /* Testimonials */
        .testimonials {
            background: var(--light);
            position: relative;
        }
        
        .testimonials-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
            gap: 25px;
        }
        
        .testimonial-item {
            background: white;
            padding: 25px;
            border-radius: 8px;
            box-shadow: var(--shadow);
            position: relative;
        }
        
        .testimonial-text {
            font-style: italic;
            margin-bottom: 20px;
            color: var(--gray);
            line-height: 1.7;
        }
        
        .testimonial-author {
            display: flex;
            align-items: center;
            gap: 12px;
        }
        
        .author-avatar {
            width: 45px;
            height: 45px;
            border-radius: 50%;
            overflow: hidden;
            background: #eee;
            display: flex;
            align-items: center;
            justify-content: center;
            color: var(--primary);
            font-size: 1.2rem;
        }
        
        .author-info h4 {
            margin-bottom: 5px;
            color: var(--secondary);
        }
        
        .author-role {
            color: var(--primary);
            font-size: 0.8rem;
        }
        
        /* Contacts */
        .contacts {
            background: white;
        }
        
        .contact-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 40px;
        }
        
        .contact-info h3 {
            color: var(--secondary);
            margin-bottom: 20px;
        }
        
        .contact-item {
            display: flex;
            align-items: center;
            gap: 15px;
            margin-bottom: 20px;
        }
        
        .contact-icon {
            width: 45px;
            height: 45px;
            background: rgba(230, 126, 34, 0.1);
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            color: var(--primary);
            font-size: 1.1rem;
        }
        
        .contact-details h4 {
            margin-bottom: 5px;
            color: var(--secondary);
        }
        
        .contact-details p {
            color: var(--gray);
        }
        
        .social-links {
            display: flex;
            gap: 12px;
            margin-top: 25px;
        }
        
        .social-link {
            width: 40px;
            height: 40px;
            background: var(--light);
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            color: var(--secondary);
            text-decoration: none;
            transition: var(--transition);
        }
        
        .social-link:hover {
            background: var(--primary);
            color: white;
        }
        
        .contact-form {
            background: var(--light);
            padding: 25px;
            border-radius: 8px;
        }
        
        .contact-form h3 {
            color: var(--secondary);
            margin-bottom: 20px;
        }
        
        .form-group {
            margin-bottom: 15px;
        }
        
        .form-group input,
        .form-group textarea {
            width: 100%;
            padding: 12px 15px;
            border: 1px solid #ddd;
            border-radius: 4px;
            font-family: 'Roboto', sans-serif;
            transition: var(--transition);
            font-size: 0.95rem;
        }
        
        .form-group input:focus,
        .form-group textarea:focus {
            outline: none;
            border-color: var(--primary);
        }
        
        .form-group textarea {
            height: 120px;
            resize: vertical;
        }
        
        .map-container {
            height: 300px;
            background: #eee;
            border-radius: 8px;
            overflow: hidden;
            margin-top: 30px;
        }
        
        /* Footer */
        footer {
            background: var(--secondary);
            color: white;
            padding: 50px 0 20px;
        }
        
        .footer-content {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 30px;
            margin-bottom: 30px;
        }
        
        .footer-logo {
            display: flex;
            align-items: center;
            gap: 10px;
            font-size: 1.3rem;
            font-weight: 700;
            color: white;
            margin-bottom: 15px;
        }
        
        .footer-about p {
            opacity: 0.8;
            margin-bottom: 15px;
            font-size: 0.9rem;
        }
        
        .footer-heading {
            color: white;
            margin-bottom: 15px;
            font-size: 1.1rem;
        }
        
        .footer-links {
            list-style: none;
        }
        
        .footer-links li {
            margin-bottom: 8px;
        }
        
        .footer-links a {
            color: rgba(255, 255, 255, 0.8);
            text-decoration: none;
            transition: var(--transition);
            font-size: 0.9rem;
        }
        
        .footer-links a:hover {
            color: var(--primary);
        }
        
        .footer-bottom {
            text-align: center;
            padding-top: 20px;
            border-top: 1px solid rgba(255, 255, 255, 0.1);
            font-size: 0.85rem;
            opacity: 0.7;
        }
        
        /* Animations */
        @keyframes fadeInUp {
            from {
                opacity: 0;
                transform: translateY(20px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }
        
        /* Responsive */
        @media (max-width: 992px) {
            .about-content,
            .contact-grid {
                grid-template-columns: 1fr;
            }
            
            .hero h1 {
                font-size: 2.2rem;
            }
            
            .hero-features {
                flex-direction: column;
                gap: 15px;
            }
            
            nav ul {
                display: none;
            }
            
            .mobile-menu-btn {
                display: block;
            }
        }
        
        @media (max-width: 768px) {
            .section {
                padding: 60px 0;
            }
            
            .section-title {
                font-size: 1.8rem;
            }
            
            .hero {
                padding: 130px 0 70px;
            }
            
            .hero h1 {
                font-size: 1.8rem;
            }
            
            .hero p {
                font-size: 1rem;
            }
            
            .hero-buttons {
                flex-direction: column;
                align-items: center;
            }
            
            .about-stats {
                grid-template-columns: 1fr;
                gap: 10px;
            }
            
            .footer-content {
                grid-template-columns: 1fr;
                text-align: center;
            }
        }
    </style>
</head>
<body>
    <!-- Header -->
    <header id="header">
        <div class="container header-container">
            <a href="#" class="logo">
                <div class="logo-img">
                    <i class="fas fa-home"></i>
                </div>
                СтяжкаДон
            </a>
            <nav>
                <ul>
                    <li><a href="#main">Главная</a></li>
                    <li><a href="#services">Услуги</a></li>
                    <li><a href="#about">О нас</a></li>
                    <li><a href="#portfolio">Работы</a></li>
                    <li><a href="#testimonials">Отзывы</a></li>
                    <li><a href="#contacts">Контакты</a></li>
                </ul>
            </nav>
            <div class="header-contact">
                <a href="tel:+79491234567" class="phone">+7 (949) 123-45-67</a>
                <a href="#contacts" class="callback">Заказать звонок</a>
            </div>
            <button class="mobile-menu-btn">
                <i class="fas fa-bars"></i>
            </button>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="hero" id="main">
        <div class="container">
            <div class="hero-content">
                <h1>Профессиональная стяжка пола в Донецке</h1>
                <p>Качественные услуги по устройству полов любой сложности. Гарантия на все работы до 5 лет! Современное оборудование и материалы.</p>
                <div class="hero-buttons">
                    <a href="#contacts" class="btn">
                        <i class="fas fa-calculator"></i>Рассчитать стоимость
                    </a>
                    <a href="#services" class="btn btn-outline">
                        <i class="fas fa-list"></i>Наши услуги
                    </a>
                </div>
                <div class="hero-features">
                    <div class="hero-feature">
                        <i class="fas fa-check-circle"></i>
                        <span>Гарантия 5 лет</span>
                    </div>
                    <div class="hero-feature">
                        <i class="fas fa-clock"></i>
                        <span>Работаем с 2010 года</span>
                    </div>
                    <div class="hero-feature">
                        <i class="fas fa-ruble-sign"></i>
                        <span>Лучшие цены в Донецке</span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Advantages -->
    <section class="section advantages">
        <div class="container">
            <h2 class="section-title">Почему выбирают нас</h2>
            <div class="advantages-grid">
                <div class="advantage-item">
                    <div class="advantage-icon">
                        <i class="fas fa-user-tie"></i>
                    </div>
                    <h3>Опытные мастера</h3>
                    <p>Работаем с 2010 года, выполнили более 1000 объектов в Донецке и области</p>
                </div>
                <div class="advantage-item">
                    <div class="advantage-icon">
                        <i class="fas fa-tools"></i>
                    </div>
                    <h3>Современное оборудование</h3>
                    <p>Используем немецкое оборудование для идеально ровной стяжки</p>
                </div>
                <div class="advantage-item">
                    <div class="advantage-icon">
                        <i class="fas fa-medal"></i>
                    </div>
                    <h3>Качественные материалы</h3>
                    <p>Работаем с проверенными поставщиками строительных материалов</p>
                </div>
                <div class="advantage-item">
                    <div class="advantage-icon">
                        <i class="fas fa-shield-alt"></i>
                    </div>
                    <h3>Гарантия 5 лет</h3>
                    <p>Даем официальную гарантию на все виды работ по договору</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Services -->
    <section class="section services" id="services">
        <div class="container">
            <h2 class="section-title">Наши услуги</h2>
            <div class="services-grid">
                <div class="service-item">
                    <div class="service-img">
                        <img src="https://images.unsplash.com/photo-1595428774223-ef52624120d2?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1770&q=80" alt="Цементная стяжка">
                    </div>
                    <div class="service-content">
                        <h3>Цементная стяжка пола</h3>
                        <p>Классическая цементная стяжка для выравнивания пола под любое покрытие.</p>
                        <div class="service-features">
                            <div class="service-feature">
                                <i class="fas fa-check"></i>
                                <span>Толщина от 3 см</span>
                            </div>
                            <div class="service-feature">
                                <i class="fas fa-check"></i>
                                <span>Высыхание 28 дней</span>
                            </div>
                            <div class="service-feature">
                                <i class="fas fa-check"></i>
                                <span>Под любое покрытие</span>
                            </div>
                        </div>
                        <span class="price">от 350 руб/м²</span>
                        <a href="#contacts" class="btn">Заказать</a>
                    </div>
                </div>
                <div class="service-item">
                    <div class="service-img">
                        <img src="https://images.unsplash.com/photo-1633380114351-4d6c2c6c15d2?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1770&q=80" alt="Полусухая стяжка">
                    </div>
                    <div class="service-content">
                        <h3>Полусухая стяжка пола</h3>
                        <p>Современная технология с минимальным содержанием воды для быстрого монтажа.</p>
                        <div class="service-features">
                            <div class="service-feature">
                                <i class="fas fa-check"></i>
                                <span>Толщина от 4 см</span>
                            </div>
                            <div class="service-feature">
                                <i class="fas fa-check"></i>
                                <span>Высыхание 7 дней</span>
                            </div>
                            <div class="service-feature">
                                <i class="fas fa-check"></i>
                                <span>Минимальная усадка</span>
                            </div>
                        </div>
                        <span class="price">от 450 руб/м²</span>
                        <a href="#contacts" class="btn">Заказать</a>
                    </div>
                </div>
                <div class="service-item">
                    <div class="service-img">
                        <img src="https://images.unsplash.com/photo-1620641788421-7a1c342ea42e?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1770&q=80" alt="Напольные покрытия">
                    </div>
                    <div class="service-content">
                        <h3>Укладка напольных покрытий</h3>
                        <p>Профессиональная укладка ламината, плитки, линолеума и других покрытий.</p>
                        <div class="service-features">
                            <div class="service-feature">
                                <i class="fas fa-check"></i>
                                <span>Любые покрытия</span>
                            </div>
                            <div class="service-feature">
                                <i class="fas fa-check"></i>
                                <span>Качественный монтаж</span>
                            </div>
                            <div class="service-feature">
                                <i class="fas fa-check"></i>
                                <span>Гарантия на работы</span>
                            </div>
                        </div>
                        <span class="price">от 250 руб/м²</span>
                        <a href="#contacts" class="btn">Заказать</a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- About -->
    <section class="section about" id="about">
        <div class="container">
            <h2 class="section-title">О нашей компании</h2>
            <div class="about-content">
                <div class="about-text">
                    <h2>Профессиональная стяжка пола в Донецке</h2>
                    <p>Мы специализируемся на устройстве стяжки пола любой сложности. Наша команда опытных мастеров работает с 2010 года и за это время мы выполнили более 1000 успешных проектов.</p>
                    <p>Используем только современное оборудование и качественные материалы от проверенных поставщиков. Предоставляем официальную гарантию на все виды работ.</p>
                    <div class="about-stats">
                        <div class="stat-item">
                            <div class="stat-number">12+</div>
                            <div class="stat-text">лет опыта</div>
                        </div>
                        <div class="stat-item">
                            <div class="stat-number">1000+</div>
                            <div class="stat-text">выполненных объектов</div>
                        </div>
                        <div class="stat-item">
                            <div class="stat-number">5 лет</div>
                            <div class="stat-text">гарантии на работы</div>
                        </div>
                    </div>
                    <a href="#contacts" class="btn">Связаться с нами</a>
                </div>
                <div class="about-img">
                    <div class="about-img-main">
                        <img src="https://images.unsplash.com/photo-1558618047-3c8c76ca7d13?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1064&q=80" alt="Наша команда">
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Portfolio -->
    <section class="section portfolio" id="portfolio">
        <div class="container">
            <h2 class="section-title">Наши работы</h2>
            <div class="portfolio-grid">
                <div class="portfolio-item">
                    <img src="https://images.unsplash.com/photo-1595428774223-ef52624120d2?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1770&q=80" alt="Работа 1" class="portfolio-img">
                    <div class="portfolio-overlay">
                        <span class="portfolio-category">Цементная стяжка</span>
                        <h3>Квартира на проспекте Мира</h3>
                    </div>
                </div>
                <div class="portfolio-item">
                    <img src="https://images.unsplash.com/photo-1633380114351-4d6c2c6c15d2?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1770&q=80" alt="Работа 2" class="portfolio-img">
                    <div class="portfolio-overlay">
                        <span class="portfolio-category">Полусухая стяжка</span>
                        <h3>Офис в центре Донецка</h3>
                    </div>
                </div>
                <div class="portfolio-item">
                    <img src="https://images.unsplash.com/photo-1620641788421-7a1c342ea42e?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1770&q=80" alt="Работа 3" class="portfolio-img">
                    <div class="portfolio-overlay">
                        <span class="portfolio-category">Укладка покрытий</span>
                        <h3>Коттедж в пригороде</h3>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Testimonials -->
    <section class="section testimonials" id="testimonials">
        <div class="container">
            <h2 class="section-title">Отзывы клиентов</h2>
            <div class="testimonials-grid">
                <div class="testimonial-item">
                    <div class="testimonial-text">
                        "Заказывал стяжку пола в новой квартире. Сделали все качественно и в срок. Цена соответствовала озвученной ранее. Рекомендую эту компанию!"
                    </div>
                    <div class="testimonial-author">
                        <div class="author-avatar">
                            <i class="fas fa-user"></i>
                        </div>
                        <div class="author-info">
                            <h4>Андрей Смирнов</h4>
                            <span class="author-role">Владелец квартиры</span>
                        </div>
                    </div>
                </div>
                <div class="testimonial-item">
                    <div class="testimonial-text">
                        "Работали с этой компанией при ремонте офиса. Сделали полусухую стяжку в кратчайшие сроки без потери качества. Буду обращаться еще."
                    </div>
                    <div class="testimonial-author">
                        <div class="author-avatar">
                            <i class="fas fa-user"></i>
                        </div>
                        <div class="author-info">
                            <h4>Ольга Иванова</h4>
                            <span class="author-role">Директор компании</span>
                        </div>
                    </div>
                </div>
                <div class="testimonial-item">
                    <div class="testimonial-text">
                        "Очень доволен результатом. Делали стяжку в частном доме. Работали аккуратно, убрали после себя. Цена адекватная. Гарантию дали письменно."
                    </div>
                    <div class="testimonial-author">
                        <div class="author-avatar">
                            <i class="fas fa-user"></i>
                        </div>
                        <div class="author-info">
                            <h4>Дмитрий Петров</h4>
                            <span class="author-role">Частный заказчик</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contacts -->
    <section class="section contacts" id="contacts">
        <div class="container">
            <h2 class="section-title">Контакты</h2>
            <div class="contact-grid">
                <div class="contact-info">
                    <h3>Свяжитесь с нами</h3>
                    <div class="contact-item">
                        <div class="contact-icon">
                            <i class="fas fa-map-marker-alt"></i>
                        </div>
                        <div class="contact-details">
                            <h4>Адрес</h4>
                            <p>г. Донецк, ул. Артема, 125</p>
                        </div>
                    </div>
                    <div class="contact-item">
                        <div class="contact-icon">
                            <i class="fas fa-phone"></i>
                        </div>
                        <div class="contact-details">
                            <h4>Телефон</h4>
                            <p>+7 (949) 123-45-67</p>
                        </div>
                    </div>
                    <div class="contact-item">
                        <div class="contact-icon">
                            <i class="fas fa-envelope"></i>
                        </div>
                        <div class="contact-details">
                            <h4>Email</h4>
                            <p>info@styazhkadon.ru</p>
                        </div>
                    </div>
                    <div class="contact-item">
                        <div class="contact-icon">
                            <i class="fas fa-clock"></i>
                        </div>
                        <div class="contact-details">
                            <h4>Время работы</h4>
                            <p>Пн-Пт: 9:00 - 18:00, Сб: 10:00 - 16:00</p>
                        </div>
                    </div>
                    <div class="social-links">
                        <a href="#" class="social-link"><i class="fab fa-vk"></i></a>
                        <a href="#" class="social-link"><i class="fab fa-instagram"></i></a>
                        <a href="#" class="social-link"><i class="fab fa-whatsapp"></i></a>
                        <a href="#" class="social-link"><i class="fab fa-telegram"></i></a>
                    </div>
                </div>
                <div class="contact-form">
                    <h3>Оставьте заявку</h3>
                    <form>
                        <div class="form-group">
                            <input type="text" placeholder="Ваше имя" required>
                        </div>
                        <div class="form-group">
                            <input type="tel" placeholder="Ваш телефон" required>
                        </div>
                        <div class="form-group">
                            <textarea placeholder="Сообщение"></textarea>
                        </div>
                        <button type="submit" class="btn">Отправить заявку</button>
                    </form>
                </div>
            </div>
            <div class="map-container">
                <!-- Здесь будет карта -->
                <div style="width: 100%; height: 100%; background: #eee; display: flex; align-items: center; justify-content: center;">
                    <p>Карта Донецка</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <div class="container">
            <div class="footer-content">
                <div class="footer-about">
                    <a href="#" class="footer-logo">
                        <div class="logo-img">
                            <i class="fas fa-home"></i>
                        </div>
                        СтяжкаДон
                    </a>
                    <p>Профессиональные услуги по устройству стяжки пола в Донецке и области. Работаем с 2010 года.</p>
                </div>
                <div class="footer-links">
                    <h4 class="footer-heading">Услуги</h4>
                    <ul>
                        <li><a href="#">Цементная стяжка</a></li>
                        <li><a href="#">Полусухая стяжка</a></li>
                        <li><a href="#">Укладка покрытий</a></li>
                        <li><a href="#">Ремонт полов</a></li>
                    </ul>
                </div>
                <div class="footer-links">
                    <h4 class="footer-heading">Компания</h4>
                    <ul>
                        <li><a href="#">О нас</a></li>
                        <li><a href="#">Наши работы</a></li>
                        <li><a href="#">Отзывы</a></li>
                        <li><a href="#">Контакты</a></li>
                    </ul>
                </div>
                <div class="footer-links">
                    <h4 class="footer-heading">Контакты</h4>
                    <ul>
                        <li><a href="tel:+79491234567">+7 (949) 123-45-67</a></li>
                        <li><a href="mailto:info@styazhkadon.ru">info@styazhkadon.ru</a></li>
                        <li>г. Донецк, ул. Артема, 125</li>
                    </ul>
                </div>
            </div>
            <div class="footer-bottom">
                <p>&copy; 2023 СтяжкаДон. Все права защищены.</p>
            </div>
        </div>
    </footer>

    <script>
        // Simple JavaScript for header scroll effect
        window.addEventListener('scroll', function() {
            const header = document.getElementById('header');
            if (window.scrollY > 50) {
                header.style.padding = '10px 0';
                header.style.boxShadow = '0 2px 10px rgba(0,0,0,0.1)';
            } else {
                header.style.padding = '15px 0';
                header.style.boxShadow = '0 5px 15px rgba(0,0,0,0.08)';
            }
        });
    </script>
</body>
</html>
