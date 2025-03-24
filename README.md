<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Free online video downloader tool - Download videos from multiple platforms with quality options and compression settings">
    <meta name="keywords" content="video downloader, youtube downloader, mp4 downloader, free video download, online video converter">
    <meta name="author" content="VideoDownloaderPro">
    <meta name="robots" content="index, follow">
    <meta property="og:title" content="Free Online Video Downloader Tool">
    <meta property="og:description" content="Download videos from multiple platforms with quality options">
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://yourdomain.com">
    <meta property="og:image" content="https://yourdomain.com/images/video-downloader-preview.jpg">
    
    <title>Free Online Video Downloader Tool | Download Videos in HD Quality</title>
    
    <!-- Favicon -->
    <link rel="icon" href="favicon.ico" type="image/x-icon">
    
    <!-- Canonical URL -->
    <link rel="canonical" href="https://yourdomain.com">
    
    <!-- Structured Data -->
    <script type="application/ld+json">
    {
      "@context": "https://schema.org",
      "@type": "WebApplication",
      "name": "Video Downloader Pro",
      "url": "https://yourdomain.com",
      "description": "Free online tool to download videos from multiple platforms",
      "applicationCategory": "UtilityApplication",
      "operatingSystem": "Web Browser"
    }
    </script>
    
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;500;700&display=swap" rel="stylesheet">
    
    <!-- Font Awesome -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    
    <style>
        :root {
            --primary-color: #4285f4;
            --secondary-color: #34a853;
            --accent-color: #ea4335;
            --light-color: #f8f9fa;
            --dark-color: #202124;
            --gray-color: #5f6368;
            --border-radius: 8px;
            --box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            --transition: all 0.3s ease;
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Roboto', sans-serif;
            line-height: 1.6;
            color: var(--dark-color);
            background-color: #f5f5f5;
        }
        
        .container {
            width: 100%;
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 15px;
        }
        
        header {
            background-color: white;
            box-shadow: var(--box-shadow);
            position: sticky;
            top: 0;
            z-index: 100;
        }
        
        .header-content {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 15px 0;
        }
        
        .logo {
            display: flex;
            align-items: center;
            text-decoration: none;
        }
        
        .logo img {
            height: 40px;
            margin-right: 10px;
        }
        
        .logo h1 {
            font-size: 1.5rem;
            color: var(--primary-color);
            font-weight: 700;
        }
        
        nav ul {
            display: flex;
            list-style: none;
        }
        
        nav ul li {
            margin-left: 20px;
        }
        
        nav ul li a {
            text-decoration: none;
            color: var(--gray-color);
            font-weight: 500;
            transition: var(--transition);
        }
        
        nav ul li a:hover {
            color: var(--primary-color);
        }
        
        .mobile-menu-btn {
            display: none;
            background: none;
            border: none;
            font-size: 1.5rem;
            color: var(--gray-color);
            cursor: pointer;
        }
        
        .hero {
            background: linear-gradient(135deg, var(--primary-color), var(--secondary-color));
            color: white;
            padding: 60px 0;
            text-align: center;
            margin-bottom: 30px;
        }
        
        .hero h2 {
            font-size: 2.5rem;
            margin-bottom: 20px;
        }
        
        .hero p {
            font-size: 1.1rem;
            max-width: 700px;
            margin: 0 auto 30px;
        }
        
        .main-content {
            display: flex;
            flex-wrap: wrap;
            gap: 30px;
            margin-bottom: 30px;
        }
        
        .download-section {
            flex: 1;
            min-width: 300px;
            background-color: white;
            border-radius: var(--border-radius);
            box-shadow: var(--box-shadow);
            padding: 30px;
        }
        
        .ad-section {
            flex: 0 0 300px;
            background-color: white;
            border-radius: var(--border-radius);
            box-shadow: var(--box-shadow);
            padding: 20px;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            min-height: 250px;
        }
        
        .ad-placeholder {
            width: 100%;
            height: 100%;
            background-color: #f0f0f0;
            display: flex;
            align-items: center;
            justify-content: center;
            border: 1px dashed #ccc;
            color: var(--gray-color);
            font-size: 0.9rem;
        }
        
        .form-group {
            margin-bottom: 20px;
        }
        
        .form-group label {
            display: block;
            margin-bottom: 8px;
            font-weight: 500;
        }
        
        .url-input {
            display: flex;
            width: 100%;
        }
        
        .url-input input {
            flex: 1;
            padding: 12px 15px;
            border: 1px solid #ddd;
            border-radius: var(--border-radius) 0 0 var(--border-radius);
            font-size: 1rem;
            outline: none;
            transition: var(--transition);
        }
        
        .url-input input:focus {
            border-color: var(--primary-color);
        }
        
        .url-input button {
            padding: 12px 20px;
            background-color: var(--primary-color);
            color: white;
            border: none;
            border-radius: 0 var(--border-radius) var(--border-radius) 0;
            cursor: pointer;
            font-weight: 500;
            transition: var(--transition);
        }
        
        .url-input button:hover {
            background-color: #3367d6;
        }
        
        .options-group {
            margin-top: 30px;
        }
        
        .option-card {
            background-color: var(--light-color);
            border-radius: var(--border-radius);
            padding: 20px;
            margin-bottom: 15px;
            cursor: pointer;
            transition: var(--transition);
        }
        
        .option-card:hover {
            background-color: #e8f0fe;
        }
        
        .option-card.active {
            background-color: #e8f0fe;
            border-left: 4px solid var(--primary-color);
        }
        
        .option-card h3 {
            font-size: 1.1rem;
            margin-bottom: 5px;
            color: var(--dark-color);
        }
        
        .option-card p {
            font-size: 0.9rem;
            color: var(--gray-color);
        }
        
        .compression-slider {
            width: 100%;
            margin-top: 15px;
        }
        
        .compression-slider input {
            width: 100%;
        }
        
        .compression-levels {
            display: flex;
            justify-content: space-between;
            margin-top: 5px;
            font-size: 0.8rem;
            color: var(--gray-color);
        }
        
        .download-btn {
            display: block;
            width: 100%;
            padding: 15px;
            background-color: var(--secondary-color);
            color: white;
            border: none;
            border-radius: var(--border-radius);
            font-size: 1.1rem;
            font-weight: 500;
            cursor: pointer;
            transition: var(--transition);
            margin-top: 20px;
            text-align: center;
            text-decoration: none;
        }
        
        .download-btn:hover {
            background-color: #2d9248;
        }
        
        .result-section {
            display: none;
            margin-top: 30px;
            background-color: white;
            border-radius: var(--border-radius);
            box-shadow: var(--box-shadow);
            padding: 30px;
        }
        
        .result-section h3 {
            margin-bottom: 20px;
            color: var(--primary-color);
        }
        
        .video-preview {
            width: 100%;
            max-width: 500px;
            margin: 0 auto 20px;
            border-radius: var(--border-radius);
            overflow: hidden;
        }
        
        .video-preview video {
            width: 100%;
            display: block;
        }
        
        .download-options {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
            gap: 15px;
            margin-top: 20px;
        }
        
        .download-option {
            background-color: var(--light-color);
            border-radius: var(--border-radius);
            padding: 15px;
            text-align: center;
        }
        
        .download-option p {
            margin-bottom: 10px;
            font-size: 0.9rem;
        }
        
        .download-option-btn {
            display: inline-block;
            padding: 8px 15px;
            background-color: var(--primary-color);
            color: white;
            border-radius: var(--border-radius);
            text-decoration: none;
            font-size: 0.9rem;
            transition: var(--transition);
        }
        
        .download-option-btn:hover {
            background-color: #3367d6;
        }
        
        .features {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
            gap: 30px;
            margin: 40px 0;
        }
        
        .feature-card {
            background-color: white;
            border-radius: var(--border-radius);
            box-shadow: var(--box-shadow);
            padding: 25px;
            text-align: center;
            transition: var(--transition);
        }
        
        .feature-card:hover {
            transform: translateY(-5px);
        }
        
        .feature-icon {
            font-size: 2.5rem;
            color: var(--primary-color);
            margin-bottom: 15px;
        }
        
        .feature-card h3 {
            margin-bottom: 15px;
            color: var(--dark-color);
        }
        
        .feature-card p {
            color: var(--gray-color);
            font-size: 0.95rem;
        }
        
        .ad-banner {
            width: 100%;
            background-color: white;
            border-radius: var(--border-radius);
            box-shadow: var(--box-shadow);
            padding: 20px;
            margin: 30px 0;
            text-align: center;
        }
        
        .how-to-use {
            background-color: white;
            border-radius: var(--border-radius);
            box-shadow: var(--box-shadow);
            padding: 30px;
            margin-bottom: 30px;
        }
        
        .how-to-use h2 {
            margin-bottom: 20px;
            color: var(--primary-color);
        }
        
        .steps {
            display: grid;
            gap: 20px;
        }
        
        .step {
            display: flex;
            gap: 15px;
        }
        
        .step-number {
            flex-shrink: 0;
            width: 30px;
            height: 30px;
            background-color: var(--primary-color);
            color: white;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-weight: bold;
        }
        
        .step-content h3 {
            margin-bottom: 5px;
            color: var(--dark-color);
        }
        
        .step-content p {
            color: var(--gray-color);
            font-size: 0.95rem;
        }
        
        footer {
            background-color: var(--dark-color);
            color: white;
            padding: 40px 0 20px;
        }
        
        .footer-content {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 30px;
            margin-bottom: 30px;
        }
        
        .footer-column h3 {
            margin-bottom: 20px;
            font-size: 1.2rem;
            color: #fff;
        }
        
        .footer-column ul {
            list-style: none;
        }
        
        .footer-column ul li {
            margin-bottom: 10px;
        }
        
        .footer-column ul li a {
            color: #bdc1c6;
            text-decoration: none;
            transition: var(--transition);
        }
        
        .footer-column ul li a:hover {
            color: white;
        }
        
        .social-links {
            display: flex;
            gap: 15px;
        }
        
        .social-links a {
            color: white;
            font-size: 1.2rem;
            transition: var(--transition);
        }
        
        .social-links a:hover {
            color: var(--primary-color);
        }
        
        .copyright {
            text-align: center;
            padding-top: 20px;
            border-top: 1px solid #3c4043;
            color: #bdc1c6;
            font-size: 0.9rem;
        }
        
        @media (max-width: 992px) {
            .main-content {
                flex-direction: column;
            }
            
            .ad-section {
                flex: 1;
                width: 100%;
            }
        }
        
        @media (max-width: 768px) {
            .header-content {
                padding: 10px 0;
            }
            
            nav {
                position: fixed;
                top: 60px;
                left: 0;
                width: 100%;
                background-color: white;
                box-shadow: var(--box-shadow);
                padding: 20px;
                transform: translateY(-150%);
                transition: var(--transition);
                z-index: 99;
            }
            
            nav.active {
                transform: translateY(0);
            }
            
            nav ul {
                flex-direction: column;
            }
            
            nav ul li {
                margin: 0 0 15px 0;
            }
            
            .mobile-menu-btn {
                display: block;
            }
            
            .hero h2 {
                font-size: 2rem;
            }
            
            .hero p {
                font-size: 1rem;
            }
            
            .download-options {
                grid-template-columns: 1fr;
            }
        }
        
        @media (max-width: 576px) {
            .logo h1 {
                font-size: 1.2rem;
            }
            
            .hero {
                padding: 40px 0;
            }
            
            .hero h2 {
                font-size: 1.8rem;
            }
            
            .download-section, .ad-section, .how-to-use {
                padding: 20px;
            }
            
            .feature-card {
                padding: 20px;
            }
        }
        
        /* Loading animation */
        .loader {
            display: none;
            width: 50px;
            height: 50px;
            border: 5px solid #f3f3f3;
            border-top: 5px solid var(--primary-color);
            border-radius: 50%;
            animation: spin 1s linear infinite;
            margin: 20px auto;
        }
        
        @keyframes spin {
            0% { transform: rotate(0deg); }
            100% { transform: rotate(360deg); }
        }
        
        /* Breadcrumbs */
        .breadcrumbs {
            padding: 15px 0;
            font-size: 0.9rem;
        }
        
        .breadcrumbs a {
            color: var(--primary-color);
            text-decoration: none;
        }
        
        .breadcrumbs span {
            color: var(--gray-color);
            margin: 0 5px;
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <div class="header-content">
                <a href="index.html" class="logo">
                    <img src="logo.png" alt="Video Downloader Pro Logo">
                    <h1>VideoDownloaderPro</h1>
                </a>
                
                <button class="mobile-menu-btn" id="mobileMenuBtn">
                    <i class="fas fa-bars"></i>
                </button>
                
                <nav id="mainNav">
                    <ul>
                        <li><a href="index.html">Home</a></li>
                        <li><a href="how-to-use.html">How to Use</a></li>
                        <li><a href="supported-sites.html">Supported Sites</a></li>
                        <li><a href="faq.html">FAQ</a></li>
                        <li><a href="contact.html">Contact</a></li>
                    </ul>
                </nav>
            </div>
        </div>
    </header>
    
    <div class="breadcrumbs container">
        <a href="index.html">Home</a>
        <span>/</span>
        <span>Video Downloader</span>
    </div>
    
    <section class="hero">
        <div class="container">
            <h2>Download Videos from Any Platform</h2>
            <p>Fast, secure and free video downloader tool that supports YouTube, Facebook, Instagram, TikTok and many more platforms.</p>
        </div>
    </section>
    
    <div class="container">
        <div class="main-content">
            <section class="download-section">
                <h2>Video Downloader</h2>
                <p>Paste the video URL below to download</p>
                
                <div class="form-group">
                    <label for="video-url">Video URL</label>
                    <div class="url-input">
                        <input type="url" id="video-url" placeholder="https://www.youtube.com/watch?v=..." required>
                        <button id="fetch-btn">Fetch Video</button>
                    </div>
                </div>
                
                <div class="options-group">
                    <h3>Download Options</h3>
                    
                    <div class="option-card active" id="quality-option">
                        <h3>Video Quality</h3>
                        <p>Select the desired video quality for download</p>
                        
                        <div class="quality-options" id="quality-options">
                            <!-- Options will be dynamically added here -->
                        </div>
                    </div>
                    
                    <div class="option-card" id="compression-option">
                        <h3>Compression Level</h3>
                        <p>Optimize video file size (higher compression = smaller file)</p>
                        
                        <input type="range" min="0" max="100" value="50" class="compression-slider" id="compression-slider">
                        <div class="compression-levels">
                            <span>Low</span>
                            <span>Medium</span>
                            <span>High</span>
                        </div>
                    </div>
                    
                    <div class="option-card" id="format-option">
                        <h3>Output Format</h3>
                        <p>Select your preferred video format</p>
                        
                        <div class="format-options" id="format-options">
                            <!-- Options will be dynamically added here -->
                        </div>
                    </div>
                </div>
                
                <button class="download-btn" id="download-btn">Download Video</button>
                
                <div class="loader" id="loader"></div>
                
                <div class="result-section" id="result-section">
                    <h3>Download Options</h3>
                    <div class="video-preview">
                        <video controls id="video-preview">
                            Your browser does not support the video tag.
                        </video>
                    </div>
                    
                    <div class="download-options" id="download-options">
                        <!-- Download options will be dynamically added here -->
                    </div>
                </div>
            </section>
            
            <section class="ad-section">
                <!-- Replace with your Google AdSense ad unit -->
                <div class="ad-placeholder">
                    <p>Advertisement Space</p>
                </div>
                <!-- Google AdSense code would go here -->
                <!--
                <script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-YOUR_PUBLISHER_ID"
                    crossorigin="anonymous"></script>
                <ins class="adsbygoogle"
                    style="display:block"
                    data-ad-client="ca-pub-YOUR_PUBLISHER_ID"
                    data-ad-slot="YOUR_AD_SLOT_ID"
                    data-ad-format="auto"
                    data-full-width-responsive="true"></ins>
                <script>
                    (adsbygoogle = window.adsbygoogle || []).push({});
                </script>
                -->
            </section>
        </div>
        
        <div class="ad-banner">
            <!-- Horizontal ad banner -->
            <div class="ad-placeholder">
                <p>Advertisement Banner</p>
            </div>
            <!-- Google AdSense code would go here -->
        </div>
        
        <section class="features">
            <div class="feature-card">
                <div class="feature-icon">
                    <i class="fas fa-bolt"></i>
                </div>
                <h3>Fast Downloads</h3>
                <p>Download videos at high speed with our optimized servers and technology.</p>
            </div>
            
            <div class="feature-card">
                <div class="feature-icon">
                    <i class="fas fa-shield-alt"></i>
                </div>
                <h3>Safe & Secure</h3>
                <p>100% secure downloads with no malware or viruses. Your privacy is protected.</p>
            </div>
            
            <div class="feature-card">
                <div class="feature-icon">
                    <i class="fas fa-mobile-alt"></i>
                </div>
                <h3>Mobile Friendly</h3>
                <p>Works perfectly on all devices including smartphones and tablets.</p>
            </div>
            
            <div class="feature-card">
                <div class="feature-icon">
                    <i class="fas fa-infinity"></i>
                </div>
                <h3>Unlimited Downloads</h3>
                <p>No restrictions on the number of videos you can download.</p>
            </div>
        </section>
        
        <section class="how-to-use">
            <h2>How to Download Videos</h2>
            
            <div class="steps">
                <div class="step">
                    <div class="step-number">1</div>
                    <div class="step-content">
                        <h3>Copy Video URL</h3>
                        <p>Go to YouTube, Facebook, Instagram or any supported site and copy the video URL from the address bar.</p>
                    </div>
                </div>
                
                <div class="step">
                    <div class="step-number">2</div>
                    <div class="step-content">
                        <h3>Paste URL</h3>
                        <p>Paste the video URL in the input field above and click "Fetch Video".</p>
                    </div>
                </div>
                
                <div class="step">
                    <div class="step-number">3</div>
                    <div class="step-content">
                        <h3>Select Options</h3>
                        <p>Choose your preferred quality, format and compression level.</p>
                    </div>
                </div>
                
                <div class="step">
                    <div class="step-number">4</div>
                    <div class="step-content">
                        <h3>Download</h3>
                        <p>Click the download button and save your video to your device.</p>
                    </div>
                </div>
            </div>
        </section>
    </div>
    
    <footer>
        <div class="container">
            <div class="footer-content">
                <div class="footer-column">
                    <h3>VideoDownloaderPro</h3>
                    <p>The fastest and most secure online video downloader tool. Download videos from multiple platforms in HD quality.</p>
                    <div class="social-links">
                        <a href="#"><i class="fab fa-facebook-f"></i></a>
                        <a href="#"><i class="fab fa-twitter"></i></a>
                        <a href="#"><i class="fab fa-instagram"></i></a>
                        <a href="#"><i class="fab fa-youtube"></i></a>
                    </div>
                </div>
                
                <div class="footer-column">
                    <h3>Quick Links</h3>
                    <ul>
                        <li><a href="index.html">Home</a></li>
                        <li><a href="how-to-use.html">How to Use</a></li>
                        <li><a href="supported-sites.html">Supported Sites</a></li>
                        <li><a href="faq.html">FAQ</a></li>
                        <li><a href="contact.html">Contact Us</a></li>
                    </ul>
                </div>
                
                <div class="footer-column">
                    <h3>Legal</h3>
                    <ul>
                        <li><a href="terms.html">Terms of Service</a></li>
                        <li><a href="privacy.html">Privacy Policy</a></li>
                        <li><a href="dmca.html">DMCA</a></li>
                        <li><a href="copyright.html">Copyright</a></li>
                    </ul>
                </div>
                
                <div class="footer-column">
                    <h3>Support</h3>
                    <ul>
                        <li><a href="contact.html">Contact</a></li>
                        <li><a href="report.html">Report Issue</a></li>
                        <li><a href="suggestions.html">Suggestions</a></li>
                    </ul>
                </div>
            </div>
            
            <div class="copyright">
                <p>&copy; 2023 VideoDownloaderPro. All rights reserved.</p>
            </div>
        </div>
    </footer>
    
    <script>
        // Mobile menu toggle
        document.getElementById('mobileMenuBtn').addEventListener('click', function() {
            document.getElementById('mainNav').classList.toggle('active');
        });
        
        // Option card selection
        const optionCards = document.querySelectorAll('.option-card');
        optionCards.forEach(card => {
            card.addEventListener('click', function() {
                optionCards.forEach(c => c.classList.remove('active'));
                this.classList.add('active');
            });
        });
        
        // Simulate video fetching and processing
        document.getElementById('fetch-btn').addEventListener('click', function() {
            const videoUrl = document.getElementById('video-url').value;
            
            if (!videoUrl) {
                alert('Please enter a valid video URL');
                return;
            }
            
            // Show loading animation
            document.getElementById('loader').style.display = 'block';
            document.getElementById('download-btn').style.display = 'none';
            
            // Simulate API call delay
            setTimeout(function() {
                // Hide loader
                document.getElementById('loader').style.display = 'none';
                
                // Show download button
                document.getElementById('download-btn').style.display = 'block';
                
                // Populate quality options (simulated)
                const qualityOptions = document.getElementById('quality-options');
                qualityOptions.innerHTML = `
                    <div class="quality-option">
                        <input type="radio" id="quality-1080" name="quality" checked>
                        <label for="quality-1080">1080p (HD)</label>
                    </div>
                    <div class="quality-option">
                        <input type="radio" id="quality-720" name="quality">
                        <label for="quality-720">720p (HD)</label>
                    </div>
                    <div class="quality-option">
                        <input type="radio" id="quality-480" name="quality">
                        <label for="quality-480">480p</label>
                    </div>
                    <div class="quality-option">
                        <input type="radio" id="quality-360" name="quality">
                        <label for="quality-360">360p</label>
                    </div>
                `;
                
                // Populate format options (simulated)
                const formatOptions = document.getElementById('format-options');
                formatOptions.innerHTML = `
                    <div class="format-option">
                        <input type="radio" id="format-mp4" name="format" checked>
                        <label for="format-mp4">MP4</label>
                    </div>
                    <div class="format-option">
                        <input type="radio" id="format-webm" name="format">
                        <label for="format-webm">WEBM</label>
                    </div>
                    <div class="format-option">
                        <input type="radio" id="format-mp3" name="format">
                        <label for="format-mp3">MP3 (Audio Only)</label>
                    </div>
                `;
                
                // Show success message
                alert('Video information fetched successfully! Select your options and click Download.');
            }, 2000);
        });
        
        // Simulate download process
        document.getElementById('download-btn').addEventListener('click', function() {
            // Show loading animation
            document.getElementById('loader').style.display = 'block';
            this.style.display = 'none';
            
            // Get selected options
            const compressionLevel = document.getElementById('compression-slider').value;
            const selectedQuality = document.querySelector('input[name="quality"]:checked').id;
            const selectedFormat = document.querySelector('input[name="format"]:checked').id;
            
            // Simulate processing delay
            setTimeout(function() {
                // Hide loader
                document.getElementById('loader').style.display = 'none';
                
                // Show result section
                document.getElementById('result-section').style.display = 'block';
                
                // Set video preview (simulated)
                document.getElementById('video-preview').src = 'sample-video.mp4';
                
                // Populate download options (simulated)
                const downloadOptions = document.getElementById('download-options');
                downloadOptions.innerHTML = `
                    <div class="download-option">
                        <p>High Quality (${selectedQuality.replace('quality-', '')})</p>
                        <a href="#" class="download-option-btn">Download MP4</a>
                    </div>
                    <div class="download-option">
                        <p>Medium Quality (720p)</p>
                        <a href="#" class="download-option-btn">Download MP4</a>
                    </div>
                    <div class="download-option">
                        <p>Audio Only (MP3)</p>
                        <a href="#" class="download-option-btn">Download MP3</a>
                    </div>
                    <div class="download-option">
                        <p>Compressed (Level ${compressionLevel})</p>
                        <a href="#" class="download-option-btn">Download MP4</a>
                    </div>
                `;
                
                // Scroll to result section
                document.getElementById('result-section').scrollIntoView({ behavior: 'smooth' });
            }, 3000);
        });
        
        // Initialize Google AdSense (uncomment and replace with your actual AdSense code)
        /*
        (function() {
            const script = document.createElement('script');
            script.async = true;
            script.src = 'https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-YOUR_PUBLISHER_ID';
            script.crossOrigin = 'anonymous';
            document.head.appendChild(script);
            
            // Initialize ad units
            const adUnits = document.querySelectorAll('.adsbygoogle');
            adUnits.forEach(unit => {
                (adsbygoogle = window.adsbygoogle || []).push({});
            });
        })();
        */
    </script>
</body>
</html>
