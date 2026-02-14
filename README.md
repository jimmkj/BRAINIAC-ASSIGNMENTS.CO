<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Quality Assignment Help Services | Professional Academic Assistance</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&family=Montserrat:wght@400;500;700&display=swap" rel="stylesheet">
    <style>
        :root {
            --primary: #6a11cb;
            --secondary: #2575fc;
            --accent1: #ff5e62;
            --accent2: #ff9966;
            --accent3: #00c9ff;
            --accent4: #92fe9d;
            --dark: #2d2b55;
            --light: #f8f9fa;
            --success: #4CAF50;
            --warning: #FFC107;
            --danger: #F44336;
            --text: #333;
            --shadow: rgba(0, 0, 0, 0.1);
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Poppins', sans-serif;
            background: linear-gradient(135deg, #f5f7fa 0%, #e4edf5 100%);
            color: var(--text);
            line-height: 1.6;
            overflow-x: hidden;
        }
        
        .container {
            width: 90%;
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }
        
        /* Header Styles */
        header {
            background: linear-gradient(to right, var(--primary), var(--secondary));
            color: white;
            padding: 20px 0;
            box-shadow: 0 4px 20px rgba(0, 0, 0, 0.15);
            position: sticky;
            top: 0;
            z-index: 1000;
        }
        
        .header-content {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        
        .logo {
            font-family: 'Montserrat', sans-serif;
            font-size: 28px;
            font-weight: 700;
            display: flex;
            align-items: center;
            gap: 10px;
        }
        
        .logo i {
            color: var(--accent4);
        }
        
        nav ul {
            display: flex;
            list-style: none;
            gap: 30px;
        }
        
        nav a {
            color: white;
            text-decoration: none;
            font-weight: 500;
            font-size: 16px;
            transition: all 0.3s;
            padding: 8px 0;
            position: relative;
        }
        
        nav a:hover {
            color: var(--accent4);
        }
        
        nav a::after {
            content: '';
            position: absolute;
            bottom: 0;
            left: 0;
            width: 0;
            height: 2px;
            background: var(--accent4);
            transition: width 0.3s;
        }
        
        nav a:hover::after {
            width: 100%;
        }
        
        .cta-button {
            background: var(--accent1);
            color: white;
            border: none;
            padding: 12px 28px;
            border-radius: 50px;
            font-weight: 600;
            cursor: pointer;
            transition: all 0.3s;
            box-shadow: 0 4px 15px rgba(255, 94, 98, 0.3);
        }
        
        .cta-button:hover {
            background: var(--accent2);
            transform: translateY(-3px);
            box-shadow: 0 6px 20px rgba(255, 94, 98, 0.4);
        }
        
        /* Notification Banner */
        .notification-banner {
            position: relative;
            height: 60px;
            background: rgba(45, 43, 85, 0.95);
            overflow: hidden;
            border-bottom: 2px solid var(--accent3);
        }
        
        .notification-track {
            display: flex;
            position: absolute;
            top: 0;
            left: 0;
            height: 100%;
            align-items: center;
            gap: 40px;
            padding: 0 20px;
            animation: scrollLeft 40s linear infinite;
        }
        
        @keyframes scrollLeft {
            0% { transform: translateX(100%); }
            100% { transform: translateX(-100%); }
        }
        
        .notification-item {
            display: flex;
            align-items: center;
            gap: 12px;
            white-space: nowrap;
            padding: 8px 20px;
            background: rgba(255, 255, 255, 0.1);
            border-radius: 30px;
            border-left: 4px solid var(--accent3);
            animation: pulseItem 3s infinite;
        }
        
        @keyframes pulseItem {
            0% { box-shadow: 0 0 0 0 rgba(0, 201, 255, 0.4); }
            70% { box-shadow: 0 0 0 10px rgba(0, 201, 255, 0); }
            100% { box-shadow: 0 0 0 0 rgba(0, 201, 255, 0); }
        }
        
        .notification-icon {
            font-size: 18px;
        }
        
        .notification-text {
            font-weight: 600;
            font-size: 15px;
            color: white;
        }
        
        .notification-grade {
            color: var(--accent4);
            font-weight: 700;
        }
        
        .notification-payment {
            color: #92fe9d;
            font-weight: 700;
        }
        
        .notification-order {
            color: #ff9966;
            font-weight: 700;
        }
        
        .notification-completed {
            color: #00c9ff;
            font-weight: 700;
        }
        
        /* Hero Section */
        .hero {
            padding: 80px 0 60px;
            text-align: center;
            background: linear-gradient(to bottom right, #ffffff, #f0f7ff);
            position: relative;
            overflow: hidden;
        }
        
        .hero h1 {
            font-size: 42px;
            color: var(--dark);
            margin-bottom: 20px;
            line-height: 1.2;
        }
        
        .hero p {
            font-size: 18px;
            max-width: 800px;
            margin: 0 auto 40px;
            color: #555;
        }
        
        .highlight {
            color: var(--primary);
            font-weight: 700;
        }
        
        /* Live Statistics Section */
        .stats-section {
            background: var(--dark);
            padding: 50px 0;
            border-radius: 20px;
            margin: 30px auto 60px;
            box-shadow: 0 15px 30px rgba(0, 0, 0, 0.2);
            position: relative;
            overflow: hidden;
            max-width: 1100px;
        }
        
        .stats-section h2 {
            text-align: center;
            color: white;
            font-size: 32px;
            margin-bottom: 40px;
            position: relative;
        }
        
        .stats-section h2::after {
            content: '';
            display: block;
            width: 80px;
            height: 4px;
            background: linear-gradient(to right, var(--accent3), var(--accent4));
            margin: 15px auto;
            border-radius: 2px;
        }
        
        .stats-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 30px;
            margin-bottom: 40px;
        }
        
        .stat-box {
            background: rgba(255, 255, 255, 0.1);
            backdrop-filter: blur(10px);
            border-radius: 15px;
            padding: 25px;
            text-align: center;
            color: white;
            border: 1px solid rgba(255, 255, 255, 0.1);
            transition: transform 0.3s;
            position: relative;
            overflow: hidden;
        }
        
        .stat-box:hover {
            transform: translateY(-10px);
        }
        
        .stat-box h3 {
            font-size: 20px;
            margin-bottom: 15px;
            color: var(--accent4);
        }
        
        .stat-value {
            font-size: 48px;
            font-weight: 700;
            margin: 15px 0;
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 10px;
        }
        
        .stat-subtext {
            font-size: 16px;
            opacity: 0.8;
        }
        
        .grade-indicator {
            display: inline-block;
            background: linear-gradient(to right, var(--accent3), var(--accent4));
            color: var(--dark);
            padding: 5px 15px;
            border-radius: 20px;
            font-weight: 600;
            margin-top: 10px;
        }
        
        .live-badge {
            position: absolute;
            top: 15px;
            right: 15px;
            background: var(--danger);
            color: white;
            padding: 5px 10px;
            border-radius: 20px;
            font-size: 12px;
            font-weight: 600;
            display: flex;
            align-items: center;
            gap: 5px;
            animation: pulse 2s infinite;
        }
        
        @keyframes pulse {
            0% { opacity: 1; }
            50% { opacity: 0.7; }
            100% { opacity: 1; }
        }
        
        /* Services Section */
        .services {
            padding: 80px 0;
            background: white;
            border-radius: 20px;
            margin-bottom: 60px;
            box-shadow: 0 10px 30px var(--shadow);
        }
        
        .section-title {
            text-align: center;
            margin-bottom: 50px;
        }
        
        .section-title h2 {
            font-size: 36px;
            color: var(--dark);
            margin-bottom: 15px;
        }
        
        .section-title p {
            color: #666;
            max-width: 700px;
            margin: 0 auto;
        }
        
        .services-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            gap: 25px;
        }
        
        .service-card {
            background: linear-gradient(135deg, #f8faff 0%, #f0f5ff 100%);
            border-radius: 15px;
            padding: 25px;
            transition: all 0.3s;
            border-left: 5px solid var(--primary);
            position: relative;
            overflow: hidden;
        }
        
        .service-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 15px 30px rgba(0, 0, 0, 0.1);
        }
        
        .service-card i {
            font-size: 32px;
            color: var(--primary);
            margin-bottom: 20px;
        }
        
        .service-card h3 {
            font-size: 20px;
            margin-bottom: 15px;
            color: var(--dark);
        }
        
        .service-card p {
            color: #666;
            font-size: 15px;
        }
        
        /* Testimonials */
        .testimonials {
            padding: 80px 0;
            background: linear-gradient(to right, #f8f9fa, #e9ecef);
            border-radius: 20px;
            margin-bottom: 60px;
        }
        
        .testimonials-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(320px, 1fr));
            gap: 25px;
        }
        
        .testimonial-card {
            background: white;
            border-radius: 15px;
            padding: 25px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.05);
            transition: transform 0.3s;
        }
        
        .testimonial-card:hover {
            transform: translateY(-10px);
        }
        
        .testimonial-header {
            display: flex;
            align-items: center;
            margin-bottom: 15px;
        }
        
        .testimonial-avatar {
            width: 50px;
            height: 50px;
            border-radius: 50%;
            background: linear-gradient(to right, var(--accent1), var(--accent2));
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            font-weight: 600;
            font-size: 20px;
            margin-right: 15px;
        }
        
        .testimonial-info h4 {
            color: var(--dark);
            font-size: 18px;
        }
        
        .testimonial-info p {
            color: #777;
            font-size: 14px;
        }
        
        .testimonial-text {
            font-style: italic;
            color: #555;
            line-height: 1.7;
        }
        
        /* Footer */
        footer {
            background: linear-gradient(to right, var(--dark), #1a1a2e);
            color: white;
            padding: 60px 0 30px;
        }
        
        .footer-content {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 40px;
            margin-bottom: 40px;
        }
        
        .footer-column h3 {
            font-size: 20px;
            margin-bottom: 25px;
            position: relative;
            padding-bottom: 10px;
        }
        
        .footer-column h3::after {
            content: '';
            position: absolute;
            bottom: 0;
            left: 0;
            width: 50px;
            height: 3px;
            background: var(--accent3);
        }
        
        .footer-column ul {
            list-style: none;
        }
        
        .footer-column ul li {
            margin-bottom: 12px;
        }
        
        .footer-column ul li a {
            color: #ddd;
            text-decoration: none;
            transition: color 0.3s;
        }
        
        .footer-column ul li a:hover {
            color: var(--accent3);
        }
        
        .whatsapp-button {
            display: inline-flex;
            align-items: center;
            gap: 10px;
            background: #25D366;
            color: white;
            padding: 12px 25px;
            border-radius: 50px;
            text-decoration: none;
            font-weight: 600;
            margin-top: 15px;
            transition: all 0.3s;
        }
        
        .whatsapp-button:hover {
            background: #128C7E;
            transform: translateY(-3px);
        }
        
        .copyright {
            text-align: center;
            padding-top: 30px;
            border-top: 1px solid rgba(255, 255, 255, 0.1);
            color: #aaa;
            font-size: 14px;
        }
        
        /* Responsive */
        @media (max-width: 992px) {
            .header-content {
                flex-direction: column;
                gap: 20px;
            }
            
            nav ul {
                flex-wrap: wrap;
                justify-content: center;
            }
            
            .hero h1 {
                font-size: 36px;
            }
            
            .notification-banner {
                height: 50px;
            }
            
            .notification-text {
                font-size: 14px;
            }
        }
        
        @media (max-width: 768px) {
            .stats-container {
                grid-template-columns: 1fr;
            }
            
            .hero h1 {
                font-size: 32px;
            }
            
            .hero p {
                font-size: 16px;
            }
            
            .notification-banner {
                height: 45px;
            }
            
            .notification-track {
                gap: 30px;
                animation: scrollLeft 30s linear infinite;
            }
        }
        
        @media (max-width: 576px) {
            .container {
                width: 95%;
                padding: 0 15px;
            }
            
            .stat-value {
                font-size: 40px;
            }
            
            .section-title h2 {
                font-size: 28px;
            }
            
            .notification-banner {
                height: 40px;
            }
            
            .notification-item {
                padding: 6px 15px;
            }
            
            .notification-text {
                font-size: 13px;
            }
            
            .notification-track {
                gap: 20px;
                animation: scrollLeft 25s linear infinite;
            }
        }
    </style>
</head>
<body>
    <!-- Header -->
    <header>
        <div class="container header-content">
            <div class="logo">
                <i class="fas fa-graduation-cap"></i>
                <span>Quality Assignment Help</span>
            </div>
            <nav>
                <ul>
                    <li><a href="#home">Home</a></li>
                    <li><a href="#services">Services</a></li>
                    <li><a href="#stats">Live Stats</a></li>
                    <li><a href="#testimonials">Testimonials</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
            <!-- CORRECTED WHATSAPP DM LINK (UPDATED PHONE NUMBER) -->
            <button class="cta-button" onclick="window.open('https://api.whatsapp.com/send?phone=+254715869346&text=Hello%20brainiactutors%20i%20need%20Assignment%20help', '_blank')">
                <i class="fab fa-whatsapp"></i> WhatsApp Now
            </button>
        </div>
    </header>

    <!-- Notification Banner -->
    <div class="notification-banner">
        <div class="notification-track" id="notificationTrack">
            <!-- Notifications will be generated dynamically by JavaScript -->
        </div>
    </div>

    <!-- Hero Section -->
    <section class="hero" id="home">
        <div class="container">
            <h1>Professional <span class="highlight">Assignment Help Services</span> for Academic Success</h1>
            <p>Get expert assistance with assignments, quizzes, research papers, online classes, and more. Our team of professionals ensures top-quality work with guaranteed grades above 68/100.</p>
            <!-- CORRECTED WHATSAPP DM LINK (UPDATED PHONE NUMBER) -->
            <button class="cta-button" onclick="window.open('https://api.whatsapp.com/send?phone=+254715869346&text=Hello%20brainiactutors%20i%20need%20Assignment%20help', '_blank')">
                <i class="fab fa-whatsapp"></i> Get Help Now
            </button>
        </div>
    </section>

    <!-- Live Statistics Section -->
    <section class="stats-section" id="stats">
        <div class="container">
            <h2>Live Assignment Statistics</h2>
            <div class="stats-container">
                <!-- Grades Stat -->
                <div class="stat-box">
                    <div class="live-badge">
                        <i class="fas fa-circle"></i> LIVE
                    </div>
                    <h3>Average Grades</h3>
                    <div class="stat-value">
                        <i class="fas fa-chart-line"></i>
                        <span id="gradeValue">76</span>/100
                    </div>
                    <div class="stat-subtext">Guaranteed grades above 68/100</div>
                    <div class="grade-indicator">Excellent</div>
                </div>
                
                <!-- Assignments Today Stat -->
                <div class="stat-box">
                    <div class="live-badge">
                        <i class="fas fa-circle"></i> LIVE
                    </div>
                    <h3>Assignments Today</h3>
                    <div class="stat-value">
                        <i class="fas fa-tasks"></i>
                        <span id="assignmentsToday">12</span>
                    </div>
                    <div class="stat-subtext">Orders being processed today</div>
                    <div class="grade-indicator">+6 New Today</div>
                </div>
                
                <!-- In Progress Stat -->
                <div class="stat-box">
                    <div class="live-badge">
                        <i class="fas fa-circle"></i> LIVE
                    </div>
                    <h3>Active Assignments</h3>
                    <div class="stat-value">
                        <i class="fas fa-cogs"></i>
                        <span id="activeAssignments">8</span>
                    </div>
                    <div class="stat-subtext">Being actively worked on</div>
                    <div class="grade-indicator">In Progress</div>
                </div>
                
                <!-- Waiting Stat -->
                <div class="stat-box">
                    <div class="live-badge">
                        <i class="fas fa-circle"></i> LIVE
                    </div>
                    <h3>Waiting Assignments</h3>
                    <div class="stat-value">
                        <i class="fas fa-clock"></i>
                        <span id="waitingAssignments">4</span>
                    </div>
                    <div class="stat-subtext">Available for assignment</div>
                    <div class="grade-indicator">Available Now</div>
                </div>
            </div>
        </div>
    </section>

    <!-- Services Section -->
    <section class="services" id="services">
        <div class="container">
            <div class="section-title">
                <h2>Our Premium Services</h2>
                <p>We provide comprehensive academic assistance across all subjects and assignment types</p>
            </div>
            <div class="services-grid">
                <div class="service-card">
                    <i class="fas fa-file-alt"></i>
                    <h3>Assignments</h3>
                    <p>All types of assignments with proper formatting and references included.</p>
                </div>
                
                <div class="service-card">
                    <i class="fas fa-question-circle"></i>
                    <h3>Quizzes, Tests & Final Exams</h3>
                    <p>Comprehensive assistance with quizzes, tests, and final examinations.</p>
                </div>
                
                <div class="service-card">
                    <i class="fas fa-project-diagram"></i>
                    <h3>Projects</h3>
                    <p>Complete project development from planning to final submission.</p>
                </div>
                
                <div class="service-card">
                    <i class="fas fa-search"></i>
                    <h3>Research Papers</h3>
                    <p>In-depth research papers with proper citations and academic rigor.</p>
                </div>
                
                <div class="service-card">
                    <i class="fas fa-code"></i>
                    <h3>Programming & Data Analysis</h3>
                    <p>R, Python, Java, C++, Stata, SPSS, Matlab, and all data analysis tasks.</p>
                </div>
                
                <div class="service-card">
                    <i class="fas fa-pen-fancy"></i>
                    <h3>Essays</h3>
                    <p>Well-structured essays with strong arguments and academic tone.</p>
                </div>
                
                <div class="service-card">
                    <i class="fas fa-laptop-house"></i>
                    <h3>Online Classes</h3>
                    <p>Complete online class management including discussions and assignments.</p>
                </div>
                
                <div class="service-card">
                    <i class="fas fa-flask"></i>
                    <h3>Science Subjects</h3>
                    <p>Biology, Chemistry, Physics, and all related science disciplines.</p>
                </div>
                
                <div class="service-card">
                    <i class="fas fa-chart-bar"></i>
                    <h3>Business & Economics</h3>
                    <p>Finance, Accounting, Economics, and all business-related subjects.</p>
                </div>
                
                <div class="service-card">
                    <i class="fas fa-calculator"></i>
                    <h3>All Mathematics</h3>
                    <p>Algebra, Calculus, Statistics, and all math-related topics covered.</p>
                </div>
                
                <div class="service-card">
                    <i class="fas fa-brain"></i>
                    <h3>Humanities & Social Sciences</h3>
                    <p>Philosophy, Psychology, Sociology, History, Government, and more.</p>
                </div>
                
                <div class="service-card">
                    <i class="fas fa-file-signature"></i>
                    <h3>Reports & Presentations</h3>
                    <p>Professional reports, presentations, and discussion posts.</p>
                </div>
            </div>
            
            <!-- Quality Assurance Section -->
            <div style="background: linear-gradient(135deg, #e3f2fd, #f3e5f5); padding: 30px; border-radius: 15px; margin-top: 40px; text-align: center;">
                <h3 style="color: var(--primary); margin-bottom: 15px;">Our Quality Guarantee</h3>
                <div style="display: flex; flex-wrap: wrap; justify-content: center; gap: 30px; margin-top: 20px;">
                    <div style="display: flex; align-items: center; gap: 10px;">
                        <i class="fas fa-check-circle" style="color: var(--success); font-size: 24px;"></i>
                        <span style="font-weight: 600;">💯 No Plagiarism</span>
                    </div>
                    <div style="display: flex; align-items: center; gap: 10px;">
                        <i class="fas fa-sync-alt" style="color: var(--secondary); font-size: 24px;"></i>
                        <span style="font-weight: 600;">✍️ Updates and Corrections</span>
                    </div>
                    <div style="display: flex; align-items: center; gap: 10px;">
                        <i class="fas fa-clock" style="color: var(--accent1); font-size: 24px;"></i>
                        <span style="font-weight: 600;">✍️ Urgent Requests Accepted</span>
                    </div>
                    <div style="display: flex; align-items: center; gap: 10px;">
                        <i class="fas fa-dollar-sign" style="color: var(--accent4); font-size: 24px;"></i>
                        <span style="font-weight: 600;">Good Quality & Good Prices</span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Testimonials Section -->
    <section class="testimonials" id="testimonials">
        <div class="container">
            <div class="section-title">
                <h2>Student Testimonials</h2>
                <p>See what our clients are saying about our services</p>
            </div>
            <div class="testimonials-grid">
                <div class="testimonial-card">
                    <div class="testimonial-header">
                        <div class="testimonial-avatar">JS</div>
                        <div class="testimonial-info">
                            <h4>James Smith</h4>
                            <p>Economics Student</p>
                        </div>
                    </div>
                    <p class="testimonial-text">"I have cleared the remaining amount for my research paper. The quality was exceptional and I scored 82/100. Thank you for the excellent work!"</p>
                </div>
                
                <div class="testimonial-card">
                    <div class="testimonial-header">
                        <div class="testimonial-avatar">MR</div>
                        <div class="testimonial-info">
                            <h4>Maria Rodriguez</h4>
                            <p>Computer Science Student</p>
                        </div>
                    </div>
                    <p class="testimonial-text">"The Python coding assignment was completed before the deadline. The code was well-documented and I got 79/100. I'll definitely use this service again."</p>
                </div>
                
                <div class="testimonial-card">
                    <div class="testimonial-header">
                        <div class="testimonial-avatar">TK</div>
                        <div class="testimonial-info">
                            <h4>Thomas Kim</h4>
                            <p>Engineering Student</p>
                        </div>
                    </div>
                    <p class="testimonial-text">"I've sent the remaining payment for my Calculus assignment. The solutions were detailed and I scored 85/100. Highly recommended for math assignments!"</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer id="contact">
        <div class="container">
            <div class="footer-content">
                <div class="footer-column">
                    <h3>Contact Us</h3>
                    <p>Get in touch with us for any academic assistance needs.</p>
                    <!-- CORRECTED WHATSAPP DM LINK (UPDATED PHONE NUMBER) -->
                    <a href="https://api.whatsapp.com/send?phone=+254715869346&text=Hello%20brainiactutors%20i%20need%20Assignment%20help" class="whatsapp-button" target="_blank">
                        <i class="fab fa-whatsapp"></i> WhatsApp Direct
                    </a>
                    <br>
                    <!-- GROUP LINK (unchanged) -->
                    <a href="https://chat.whatsapp.com/K4pGzREL0Io5XN9v5McvbQ" class="whatsapp-button" target="_blank" style="background: #075E54; margin-top: 10px;">
                        <i class="fab fa-whatsapp"></i> WhatsApp Group
                    </a>
                </div>
                
                <div class="footer-column">
                    <h3>Quick Links</h3>
                    <ul>
                        <li><a href="#home">Home</a></li>
                        <li><a href="#services">Services</a></li>
                        <li><a href="#stats">Live Statistics</a></li>
                        <li><a href="#testimonials">Testimonials</a></li>
                    </ul>
                </div>
                
                <div class="footer-column">
                    <h3>Our Services</h3>
                    <ul>
                        <li><a href="#services">Assignments</a></li>
                        <li><a href="#services">Research Papers</a></li>
                        <li><a href="#services">Online Classes</a></li>
                        <li><a href="#services">Programming Help</a></li>
                    </ul>
                </div>
                
                <div class="footer-column">
                    <h3>Quality Guarantee</h3>
                    <ul>
                        <li>✅ Grades Above 68/100</li>
                        <li>✅ No Plagiarism</li>
                        <li>✅ Updates and Corrections</li>
                        <li>✅ Urgent Requests Accepted</li>
                        <li>✅ Good Quality & Good Prices</li>
                    </ul>
                </div>
            </div>
            
            <div class="copyright">
                <p>&copy; 2023 Quality Assignment Help Services. All rights reserved.</p>
                <p>Professional academic assistance for students worldwide.</p>
            </div>
        </div>
    </footer>

    <script>
        // Animated live statistics
        document.addEventListener('DOMContentLoaded', function() {
            const gradeValue = document.getElementById('gradeValue');
            const assignmentsToday = document.getElementById('assignmentsToday');
            const activeAssignments = document.getElementById('activeAssignments');
            const waitingAssignments = document.getElementById('waitingAssignments');
            
            // Function to animate counting
            function animateCounter(element, start, end, duration) {
                let startTimestamp = null;
                const step = (timestamp) => {
                    if (!startTimestamp) startTimestamp = timestamp;
                    const progress = Math.min((timestamp - startTimestamp) / duration, 1);
                    const value = Math.floor(progress * (end - start) + start);
                    element.textContent = value;
                    if (progress < 1) {
                        window.requestAnimationFrame(step);
                    }
                };
                window.requestAnimationFrame(step);
            }
            
            // Initial animation
            animateCounter(gradeValue, 68, 76, 2000);
            animateCounter(assignmentsToday, 0, 12, 1500);
            animateCounter(activeAssignments, 0, 8, 1800);
            animateCounter(waitingAssignments, 0, 4, 1200);
            
            // Update statistics every 30 seconds to simulate live updates
            setInterval(() => {
                // Generate random but realistic variations
                const newGrade = Math.min(Math.max(76 + Math.floor(Math.random() * 7) - 3, 70), 85);
                const newAssignmentsToday = Math.min(Math.max(12 + Math.floor(Math.random() * 5) - 2, 6), 20);
                const newActive = Math.min(Math.max(8 + Math.floor(Math.random() * 5) - 2, 5), 15);
                const newWaiting = Math.min(Math.max(4 + Math.floor(Math.random() * 3) - 1, 2), 8);
                
                // Animate to new values
                animateCounter(gradeValue, parseInt(gradeValue.textContent), newGrade, 1000);
                animateCounter(assignmentsToday, parseInt(assignmentsToday.textContent), newAssignmentsToday, 1000);
                animateCounter(activeAssignments, parseInt(activeAssignments.textContent), newActive, 1000);
                animateCounter(waitingAssignments, parseInt(waitingAssignments.textContent), newWaiting, 1000);
            }, 30000);
            
            // Notification System
            const notificationTrack = document.getElementById('notificationTrack');
            
            // Notification data
            const notifications = [
                { icon: "fas fa-check-circle", text: "Assignment Completed", type: "completed", grade: "78/100" },
                { icon: "fas fa-file-alt", text: "New Order Received", type: "order", subject: "Calculus Assignment" },
                { icon: "fas fa-money-bill-wave", text: "Payment Confirmed", type: "payment", student: "Maria R." },
                { icon: "fas fa-chart-line", text: "Grade Achieved", type: "grade", grade: "82/100" },
                { icon: "fas fa-user-graduate", text: "I have cleared the remaining amount", type: "payment", student: "James S." },
                { icon: "fas fa-tasks", text: "Assignment In Progress", type: "completed", subject: "Research Paper" },
                { icon: "fas fa-clock", text: "Urgent Request Accepted", type: "order", time: "3hr deadline" },
                { icon: "fas fa-code", text: "Programming Assignment Delivered", type: "completed", subject: "Python Code" },
                { icon: "fas fa-flask", text: "Lab Report Submitted", type: "completed", grade: "79/100" },
                { icon: "fas fa-book", text: "Essay Delivered", type: "completed", subject: "Philosophy Essay" }
            ];
            
            // Function to create notification element
            function createNotificationElement(notification) {
                const notificationEl = document.createElement('div');
                notificationEl.className = 'notification-item';
                
                let notificationHTML = `
                    <i class="${notification.icon} notification-icon"></i>
                    <span class="notification-text">${notification.text}`;
                
                // Add additional info based on type
                if (notification.type === "grade" && notification.grade) {
                    notificationHTML += ` - <span class="notification-grade">${notification.grade}</span>`;
                } else if (notification.type === "payment" && notification.student) {
                    notificationHTML += ` - <span class="notification-payment">${notification.student}</span>`;
                } else if (notification.type === "order" && notification.subject) {
                    notificationHTML += ` - <span class="notification-order">${notification.subject}</span>`;
                } else if (notification.type === "completed" && notification.grade) {
                    notificationHTML += ` - <span class="notification-completed">${notification.grade}</span>`;
                } else if (notification.type === "completed" && notification.subject) {
                    notificationHTML += ` - <span class="notification-completed">${notification.subject}</span>`;
                } else if (notification.type === "order" && notification.time) {
                    notificationHTML += ` - <span class="notification-order">${notification.time}</span>`;
                }
                
                notificationHTML += `</span>`;
                notificationEl.innerHTML = notificationHTML;
                
                return notificationEl;
            }
            
            // Populate notification track with multiple copies for seamless scrolling
            function populateNotifications() {
                notificationTrack.innerHTML = '';
                
                // Add 3 sets of notifications for continuous scrolling
                for (let i = 0; i < 3; i++) {
                    notifications.forEach(notification => {
                        notificationTrack.appendChild(createNotificationElement(notification));
                    });
                }
            }
            
            // Initialize notifications
            populateNotifications();
            
            // Add a new random notification periodically
            setInterval(() => {
                const randomNotification = notifications[Math.floor(Math.random() * notifications.length)];
                const newNotification = createNotificationElement(randomNotification);
                notificationTrack.appendChild(newNotification);
            }, 8000);
        });
    </script>
</body>
</html>
