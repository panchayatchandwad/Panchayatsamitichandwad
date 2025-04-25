<!DOCTYPE html>
<html lang="mr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>पंचायत समिती चांदवड | Panchayat Samiti Chandwad</title>
    <meta name="description" content="चांदवड तालुक्यातील पंचायत समितीची अधिकृत वेबसाइट. ग्रामीण विकास, कृषी विकास, जलव्यवस्थापन आणि नागरिकांसाठी सेवा.">
    <meta name="keywords" content="पंचायत समिती, चांदवड, नाशिक, ग्रामीण विकास, महाराष्ट्र, Panchayat Samiti, Chandwad, Nashik">
    <meta name="author" content="पंचायत समिती चांदवड">
    <meta name="robots" content="index, follow">
    <link rel="canonical" href="https://www.chandwadpanchayatsamiti.gov.in/">
    <!-- Open Graph Tags for Social Media -->
    <meta property="og:title" content="पंचायत समिती चांदवड | Panchayat Samiti Chandwad">
    <meta property="og:description" content="चांदवड तालुक्यातील पंचायत समितीची अधिकृत वेबसाइट. ग्रामीण विकास, कृषी विकास, जलव्यवस्थापन आणि नागरिकांसाठी सेवा.">
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://www.chandwadpanchayatsamiti.gov.in/">
    <meta property="og:image" content="https://www.chandwadpanchayatsamiti.gov.in/images/logo.jpg">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Arial', sans-serif;
        }
        
        body {
            background-color: #f5f5f5;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }
        
        /* Header Styles */
        header {
            background-color: #138808; /* Indian flag green */
            color: white;
            padding: 15px 0;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }
        
        .header-top {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding-bottom: 10px;
            border-bottom: 1px solid rgba(255, 255, 255, 0.3);
        }
        
        .logo {
            display: flex;
            align-items: center;
            gap: 10px;
        }
        
        .logo img {
            height: 60px;
            width: auto;
        }
        
        .site-title {
            font-size: 1.8rem;
        }
        
        .site-subtitle {
            font-size: 1rem;
            opacity: 0.9;
        }
        
        .header-right {
            display: flex;
            align-items: center;
            gap: 20px;
        }
        
        .language-switch {
            padding: 5px 10px;
            background-color: white;
            color: #138808;
            border: none;
            border-radius: 4px;
            cursor: pointer;
            font-weight: bold;
        }
        
        /* Navigation Styles */
        nav {
            padding: 15px 0;
        }
        
        .nav-list {
            list-style: none;
            display: flex;
            justify-content: center;
            gap: 30px;
        }
        
        .nav-list li a {
            color: white;
            text-decoration: none;
            font-size: 1.1rem;
            font-weight: bold;
            transition: opacity 0.3s;
        }
        
        .nav-list li a:hover {
            opacity: 0.8;
        }
        
        /* Hero Section */
        .hero {
            background: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), url('/api/placeholder/1200/400') center/cover;
            color: white;
            padding: 60px 0;
            text-align: center;
        }
        
        .hero h1 {
            font-size: 2.5rem;
            margin-bottom: 20px;
        }
        
        .hero p {
            font-size: 1.2rem;
            max-width: 800px;
            margin: 0 auto 30px;
        }
        
        .btn {
            display: inline-block;
            padding: 12px 25px;
            background-color: #FF9933; /* Indian flag saffron */
            color: white;
            text-decoration: none;
            border-radius: 4px;
            font-weight: bold;
            transition: background-color 0.3s;
        }
        
        .btn:hover {
            background-color: #e88a2a;
        }
        
        /* Services Section */
        .services {
            padding: 60px 0;
            background-color: white;
        }
        
        .section-title {
            text-align: center;
            margin-bottom: 40px;
            color: #333;
        }
        
        .section-title h2 {
            font-size: 2rem;
            position: relative;
            display: inline-block;
            padding-bottom: 10px;
        }
        
        .section-title h2:after {
            content: "";
            position: absolute;
            bottom: 0;
            left: 50%;
            transform: translateX(-50%);
            width: 80px;
            height: 3px;
            background-color: #FF9933;
        }
        
        .services-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 30px;
        }
        
        .service-card {
            background-color: #f9f9f9;
            border-radius: 8px;
            padding: 25px;
            text-align: center;
            box-shadow: 0 3px 10px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s;
        }
        
        .service-card:hover {
            transform: translateY(-5px);
        }
        
        .service-icon {
            font-size: 2.5rem;
            color: #138808;
            margin-bottom: 15px;
        }
        
        .service-card h3 {
            margin-bottom: 15px;
            color: #333;
        }
        
        .service-card p {
            color: #666;
            line-height: 1.6;
        }
        
        /* Announcements Section */
        .announcements {
            padding: 60px 0;
            background-color: #f5f5f5;
        }
        
        .announcement-list {
            background-color: white;
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 3px 10px rgba(0, 0, 0, 0.1);
        }
        
        .announcement-item {
            padding: 20px;
            border-bottom: 1px solid #eee;
        }
        
        .announcement-item:last-child {
            border-bottom: none;
        }
        
        .announcement-date {
            color: #FF9933;
            font-weight: bold;
            margin-bottom: 8px;
        }
        
        .announcement-title {
            margin-bottom: 10px;
            color: #333;
        }
        
        .announcement-content {
            color: #666;
            line-height: 1.6;
        }
        
        /* Contact Section */
        .contact {
            padding: 60px 0;
            background-color: white;
        }
        
        .contact-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
        }
        
        .contact-info {
            background-color: #f9f9f9;
            border-radius: 8px;
            padding: 30px;
            box-shadow: 0 3px 10px rgba(0, 0, 0, 0.1);
        }
        
        .contact-info h3 {
            color: #333;
            margin-bottom: 20px;
            padding-bottom: 10px;
            border-bottom: 2px solid #eee;
        }
        
        .contact-detail {
            display: flex;
            margin-bottom: 15px;
            color: #666;
        }
        
        .contact-icon {
            margin-right: 15px;
            color: #138808;
            font-size: 1.2rem;
        }
        
        .contact-form {
            background-color: #f9f9f9;
            border-radius: 8px;
            padding: 30px;
            box-shadow: 0 3px 10px rgba(0, 0, 0, 0.1);
        }
        
        .form-group {
            margin-bottom: 20px;
        }
        
        .form-group label {
            display: block;
            margin-bottom: 8px;
            color: #333;
        }
        
        .form-control {
            width: 100%;
            padding: 12px;
            border: 1px solid #ddd;
            border-radius: 4px;
            font-size: 1rem;
        }
        
        textarea.form-control {
            height: 120px;
            resize: vertical;
        }
        
        .btn-submit {
            background-color: #138808;
            border: none;
            cursor: pointer;
            font-size: 1rem;
        }
        
        .btn-submit:hover {
            background-color: #0e6606;
        }
        
        /* Footer Styles */
        footer {
            background-color: #333;
            color: white;
            padding: 40px 0 20px;
        }
        
        .footer-content {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 30px;
            margin-bottom: 30px;
        }
        
        .footer-section h3 {
            margin-bottom: 20px;
            position: relative;
            padding-bottom: 10px;
        }
        
        .footer-section h3:after {
            content: "";
            position: absolute;
            bottom: 0;
            left: 0;
            width: 50px;
            height: 2px;
            background-color: #FF9933;
        }
        
        .footer-links {
            list-style: none;
        }
        
        .footer-links li {
            margin-bottom: 10px;
        }
        
        .footer-links li a {
            color: #ccc;
            text-decoration: none;
            transition: color 0.3s;
        }
        
        .footer-links li a:hover {
            color: white;
        }
        
        .social-links {
            display: flex;
            gap: 15px;
            margin-top: 20px;
        }
        
        .social-links a {
            display: inline-block;
            height: 40px;
            width: 40px;
            background-color: rgba(255, 255, 255, 0.1);
            border-radius: 50%;
            color: white;
            text-align: center;
            line-height: 40px;
            transition: background-color 0.3s;
        }
        
        .social-links a:hover {
            background-color: #FF9933;
        }
        
        .footer-bottom {
            text-align: center;
            padding-top: 20px;
            border-top: 1px solid rgba(255, 255, 255, 0.1);
        }
        
        .footer-bottom p {
            color: #ccc;
        }
        
        /* Responsive Styles */
        @media (max-width: 768px) {
            .header-top {
                flex-direction: column;
                text-align: center;
                gap: 15px;
            }
            
            .logo {
                justify-content: center;
            }
            
            .nav-list {
                flex-direction: column;
                gap: 10px;
                text-align: center;
            }
            
            .hero h1 {
                font-size: 2rem;
            }
            
            .hero p {
                font-size: 1rem;
            }
        }
    </style>
    <!-- Google Search Console Verification (You'll need to replace this with your actual verification code) -->
    <meta name="google-site-verification" content="your-verification-code-here">
</head>
<body>
    <!-- Header Section -->
    <header>
        <div class="container">
            <div class="header-top">
                <div class="logo">
                    <img src="/api/placeholder/60/60" alt="पंचायत समिती चांदवड लोगो">
                    <div>
                        <div class="site-title">पंचायत समिती चांदवड</div>
                        <div class="site-subtitle">नाशिक जिल्हा, महाराष्ट्र</div>
                    </div>
                </div>
                <div class="header-right">
                    <button class="language-switch">English</button>
                </div>
            </div>
            <nav>
                <ul class="nav-list">
                    <li><a href="#home">मुख्यपृष्ठ</a></li>
                    <li><a href="#about">आमच्याबद्दल</a></li>
                    <li><a href="#services">सेवा</a></li>
                    <li><a href="#announcements">सूचना</a></li>
                    <li><a href="#departments">विभाग</a></li>
                    <li><a href="#documents">दस्तऐवज</a></li>
                    <li><a href="#contact">संपर्क</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <!-- Hero Section -->
    <section id="home" class="hero">
        <div class="container">
            <h1>चांदवड पंचायत समितीमध्ये आपले स्वागत आहे</h1>
            <p>चांदवड तालुक्यातील विकास आणि प्रशासन यांच्या समन्वयासाठी कार्यरत. आमच्या डिजिटल सेवांचा लाभ घ्या.</p>
            <a href="#services" class="btn">सेवा पहा</a>
        </div>
    </section>

    <!-- Services Section -->
    <section id="services" class="services">
        <div class="container">
            <div class="section-title">
                <h2>आमच्या सेवा</h2>
            </div>
            <div class="services-grid">
                <div class="service-card">
                    <div class="service-icon">📝</div>
                    <h3>दाखले</h3>
                    <p>जात प्रमाणपत्र, उत्पन्न प्रमाणपत्र, रहिवासी प्रमाणपत्र आणि इतर महत्त्वपूर्ण दस्तावेज</p>
                </div>
                <div class="service-card">
                    <div class="service-icon">🏠</div>
                    <h3>ग्रामीण विकास</h3>
                    <p>ग्रामीण विकास योजना, निधी वितरण आणि पायाभूत सुविधा विकास</p>
                </div>
                <div class="service-card">
                    <div class="service-icon">💧</div>
                    <h3>जलव्यवस्थापन</h3>
                    <p>पाणीपुरवठा योजना, जलसंधारण आणि सिंचन व्यवस्थापन</p>
                </div>
                <div class="service-card">
                    <div class="service-icon">🌱</div>
                    <h3>कृषी सहाय्य</h3>
                    <p>शेतकरी कल्याण योजना, अनुदान आणि आधुनिक शेती तंत्रज्ञान</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Announcements Section -->
    <section id="announcements" class="announcements">
        <div class="container">
            <div class="section-title">
                <h2>महत्त्वाच्या सूचना</h2>
            </div>
            <div class="announcement-list">
                <div class="announcement-item">
                    <div class="announcement-date">15 एप्रिल 2025</div>
                    <h3 class="announcement-title">पाणी वापर संघ सभा</h3>
                    <div class="announcement-content">
                        <p>चांदवड तालुक्यातील सर्व पाणी वापर संघांची त्रैमासिक सभा दिनांक 25 एप्रिल 2025 रोजी सकाळी 11:00 वाजता पंचायत समिती सभागृहात आयोजित करण्यात आली आहे.</p>
                    </div>
                </div>
                <div class="announcement-item">
                    <div class="announcement-date">10 एप्रिल 2025</div>
                    <h3 class="announcement-title">कृषी अभियंता भरती</h3>
                    <div class="announcement-content">
                        <p>पंचायत समिती चांदवड अंतर्गत कृषी विभागात कृषी अभियंता पदासाठी अर्ज मागवण्यात येत आहेत. अधिक माहितीसाठी कृपया विभागीय कार्यालयाशी संपर्क साधा.</p>
                    </div>
                </div>
                <div class="announcement-item">
                    <div class="announcement-date">5 एप्रिल 2025</div>
                    <h3 class="announcement-title">ग्राम सभा कार्यक्रम</h3>
                    <div class="announcement-content">
                        <p>मे महिन्यात होणाऱ्या ग्राम सभांचे वेळापत्रक जाहीर करण्यात आले आहे. सर्व ग्रामपंचायतींनी निर्धारित तारखांना सभा आयोजित करून सर्व नागरिकांना सहभागी होण्याचे आवाहन करावे.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="contact">
        <div class="container">
            <div class="section-title">
                <h2>संपर्क करा</h2>
            </div>
            <div class="contact-grid">
                <div class="contact-info">
                    <h3>संपर्क माहिती</h3>
                    <div class="contact-detail">
                        <span class="contact-icon">📍</span>
                        <span>पंचायत समिती कार्यालय, चांदवड तालुका, नाशिक जिल्हा, महाराष्ट्र - 423104</span>
                    </div>
                    <div class="contact-detail">
                        <span class="contact-icon">📞</span>
                        <span>02556-245678</span>
                    </div>
                    <div class="contact-detail">
                        <span class="contact-icon">📧</span>
                        <span>ps.chandwad@maharashtra.gov.in</span>
                    </div>
                    <div class="contact-detail">
                        <span class="contact-icon">🕒</span>
                        <span>कार्यालयीन वेळ: सकाळी 10:00 ते संध्याकाळी 5:30 (सोमवार ते शनिवार)</span>
                    </div>
                </div>
                <div class="contact-form">
                    <h3>प्रश्न विचारा</h3>
                    <form>
                        <div class="form-group">
                            <label for="name">पूर्ण नाव</label>
                            <input type="text" id="name" class="form-control" required>
                        </div>
                        <div class="form-group">
                            <label for="email">ई-मेल</label>
                            <input type="email" id="email" class="form-control" required>
                        </div>
                        <div class="form-group">
                            <label for="phone">मोबाईल नंबर</label>
                            <input type="tel" id="phone" class="form-control">
                        </div>
                        <div class="form-group">
                            <label for="subject">विषय</label>
                            <input type="text" id="subject" class="form-control" required>
                        </div>
                        <div class="form-group">
                            <label for="message">संदेश</label>
                            <textarea id="message" class="form-control" required></textarea>
                        </div>
                        <button type="submit" class="btn btn-submit">पाठवा</button>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer Section -->
    <footer>
        <div class="container">
            <div class="footer-content">
                <div class="footer-section">
                    <h3>त्वरित लिंक्स</h3>
                    <ul class="footer-links">
                        <li><a href="#home">मुख्यपृष्ठ</a></li>
                        <li><a href="#services">सेवा</a></li>
                        <li><a href="#announcements">सूचना</a></li>
                        <li><a href="#contact">संपर्क</a></li>
                    </ul>
                </div>
                <div class="footer-section">
                    <h3>उपयुक्त लिंक्स</h3>
                    <ul class="footer-links">
                        <li><a href="#">महाराष्ट्र शासन</a></li>
                        <li><a href="#">नाशिक जिल्हा परिषद</a></li>
                        <li><a href="#">राष्ट्रीय ग्रामीण विकास संस्था</a></li>
                        <li><a href="#">तक्रार नोंदवा</a></li>
                    </ul>
                </div>
                <div class="footer-section">
                    <h3>अधिक माहिती</h3>
                    <ul class="footer-links">
                        <li><a href="#">नियम आणि अटी</a></li>
                        <li><a href="#">गोपनीयता धोरण</a></li>
                        <li><a href="#">RTI माहिती</a></li>
                        <li><a href="#">अधिकृत दस्तावेज</a></li>
                    </ul>
                </div>
                <div class="footer-section">
                    <h3>आमच्याशी जोडून रहा</h3>
                    <p>आमच्या सोशल मीडिया प्लॅटफॉर्मवर आमचे अनुसरण करा आणि नवीनतम अपडेट्स मिळवा.</p>
                    <div class="social-links">
                        <a href="#">F</a>
                        <a href="#">T</a>
                        <a href="#">I</a>
                        <a href="#">Y</a>
                    </div>
                </div>
            </div>
            <div class="footer-bottom">
                <p>&copy; 2025 पंचायत समिती चांदवड. सर्व हक्क राखीव.</p>
            </div>
        </div>
    </footer>
</body>
</html>
