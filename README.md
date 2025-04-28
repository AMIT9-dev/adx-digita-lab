<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AdX Digital Lab | Professional Digital Marketing Services</title>
    <meta name="description" content="Boost your business with our expert digital marketing services including Facebook Ads, Google Ads, and social media marketing">
    <style>
        :root {
            --primary: #2563eb;
            --secondary: #1e40af;
            --dark: #111827;
            --light: #f3f4f6;
            --accent: #f59e0b;
        }
        
        body {
            background-color: var(--dark);
            color: var(--light);
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 0;
            line-height: 1.6;
        }
        
        header {
            background: linear-gradient(135deg, var(--primary), var(--secondary));
            padding: 2rem 1rem;
            text-align: center;
            position: relative;
            overflow: hidden;
        }
        
        header::after {
            content: '';
            position: absolute;
            bottom: 0;
            left: 0;
            right: 0;
            height: 10px;
            background: var(--accent);
        }
        
        header h1 {
            margin: 0;
            font-size: 2.8rem;
            font-weight: 700;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
        }
        
        header p {
            font-size: 1.2rem;
            margin: 0.5rem 0 0;
            opacity: 0.9;
        }
        
        nav {
            background-color: rgba(30, 64, 175, 0.9);
            padding: 1rem;
            position: sticky;
            top: 0;
            z-index: 100;
            backdrop-filter: blur(5px);
        }
        
        nav ul {
            display: flex;
            justify-content: center;
            list-style: none;
            margin: 0;
            padding: 0;
            gap: 2rem;
        }
        
        nav a {
            color: white;
            text-decoration: none;
            font-weight: 600;
            padding: 0.5rem 1rem;
            border-radius: 4px;
            transition: all 0.3s ease;
        }
        
        nav a:hover {
            background-color: var(--accent);
            color: var(--dark);
        }
        
        section {
            padding: 4rem 1rem;
            max-width: 1200px;
            margin: 0 auto;
        }
        
        .section-title {
            text-align: center;
            margin-bottom: 3rem;
            position: relative;
        }
        
        .section-title h2 {
            color: var(--primary);
            font-size: 2.2rem;
            display: inline-block;
            margin: 0;
        }
        
        .section-title h2::after {
            content: '';
            display: block;
            width: 60px;
            height: 4px;
            background: var(--accent);
            margin: 0.5rem auto 0;
        }
        
        .services-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
            margin-top: 2rem;
        }
        
        .service-card {
            background-color: #1f2937;
            border-radius: 8px;
            padding: 2rem;
            transition: transform 0.3s ease;
            border-left: 4px solid var(--accent);
        }
        
        .service-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 20px rgba(0,0,0,0.2);
        }
        
        .service-card h3 {
            color: var(--primary);
            margin-top: 0;
        }
        
        .portfolio-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 1.5rem;
        }
        
        .portfolio-item {
            position: relative;
            border-radius: 8px;
            overflow: hidden;
            height: 250px;
        }
        
        .portfolio-item img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            transition: transform 0.3s ease;
        }
        
        .portfolio-item:hover img {
            transform: scale(1.05);
        }
        
        .portfolio-overlay {
            position: absolute;
            bottom: 0;
            left: 0;
            right: 0;
            background: linear-gradient(to top, rgba(0,0,0,0.8), transparent);
            padding: 1rem;
            color: white;
        }
        
        .contact-form {
            max-width: 600px;
            margin: 0 auto;
            background-color: #1f2937;
            padding: 2rem;
            border-radius: 8px;
        }
        
        .form-group {
            margin-bottom: 1.5rem;
        }
        
        .form-group label {
            display: block;
            margin-bottom: 0.5rem;
            font-weight: 600;
        }
        
        .form-group input,
        .form-group textarea,
        .form-group select {
            width: 100%;
            padding: 0.8rem;
            border: 1px solid #374151;
            border-radius: 4px;
            background-color: #111827;
            color: white;
        }
        
        .form-group textarea {
            min-height: 120px;
        }
        
        .btn {
            display: inline-block;
            background-color: var(--primary);
            color: white;
            padding: 0.8rem 2rem;
            border: none;
            border-radius: 4px;
            font-weight: 600;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }
        
        .btn:hover {
            background-color: var(--secondary);
        }
        
        .btn-accent {
            background-color: var(--accent);
            color: var(--dark);
        }
        
        .btn-accent:hover {
            background-color: #e67e22;
        }
        
        footer {
            background-color: #030712;
            padding: 3rem 1rem;
            text-align: center;
        }
        
        .social-links {
            display: flex;
            justify-content: center;
            gap: 1.5rem;
            margin: 1.5rem 0;
        }
        
        .social-links a {
            color: white;
            font-size: 1.5rem;
            transition: color 0.3s ease;
        }
        
        .social-links a:hover {
            color: var(--accent);
        }
        
        .copyright {
            opacity: 0.7;
            font-size: 0.9rem;
        }
        
        @media (max-width: 768px) {
            header h1 {
                font-size: 2rem;
            }
            
            nav ul {
                flex-direction: column;
                gap: 0.5rem;
                align-items: center;
            }
            
            section {
                padding: 2rem 1rem;
            }
        }
    </style>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
</head>
<body>

    <header>
        <h1>AdX Digital Lab</h1>
        <p>Transform Your Business with Data-Driven Digital Marketing</p>
    </header>

    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#services">Services</a></li>
            <li><a href="#portfolio">Portfolio</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <section id="home">
        <div class="section-title">
            <h2>Digital Marketing That Delivers Results</h2>
        </div>
        <div style="text-align: center; max-width: 800px; margin: 0 auto;">
            <p>We specialize in creating high-converting digital marketing campaigns that help businesses grow their online presence, generate leads, and increase sales. Our data-driven approach ensures you get the best return on your advertising investment.</p>
            <a href="#contact" class="btn btn-accent" style="margin-top: 1.5rem;">Get a Free Consultation</a>
        </div>
    </section>

    <section id="services" style="background-color: #111827;">
        <div class="section-title">
            <h2>Our Services</h2>
        </div>
        <div class="services-grid">
            <div class="service-card">
                <h3>Facebook & Instagram Ads</h3>
                <p>Targeted advertising campaigns to reach your ideal customers on social media platforms with precision and measurable results.</p>
            </div>
            <div class="service-card">
                <h3>Google Ads Management</h3>
                <p>Search, display, and shopping ads that capture high-intent customers actively searching for your products or services.</p>
            </div>
            <div class="service-card">
                <h3>YouTube Video Ads</h3>
                <p>Engaging video campaigns that tell your brand story and drive conversions through the power of sight, sound, and motion.</p>
            </div>
            <div class="service-card">
                <h3>Lead Generation</h3>
                <p>Strategies designed to capture high-quality leads and turn them into paying customers through optimized funnels.</p>
            </div>
            <div class="service-card">
                <h3>Retargeting Campaigns</h3>
                <p>Reconnect with visitors who didn't convert and bring them back to complete their purchase or inquiry.</p>
            </div>
            <div class="service-card">
                <h3>Conversion Rate Optimization</h3>
                <p>Improve your website's ability to turn visitors into customers through data-driven testing and optimization.</p>
            </div>
        </div>
    </section>

    <section id="portfolio">
        <div class="section-title">
            <h2>Our Portfolio</h2>
        </div>
        <div class="portfolio-grid">
            <div class="portfolio-item">
                <img src="https://images.unsplash.com/photo-1551288049-bebda4e38f71?ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=60" alt="E-commerce Campaign">
                <div class="portfolio-overlay">
                    <h3>E-commerce Store</h3>
                    <p>300% ROI increase in 3 months</p>
                </div>
            </div>
            <div class="portfolio-item">
                <img src="https://images.unsplash.com/photo-1551434678-e076c223a692?ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=60" alt="Local Business Campaign">
                <div class="portfolio-overlay">
                    <h3>Local Service Business</h3>
                    <p>50+ new clients monthly</p>
                </div>
            </div>
            <div class="portfolio-item">
                <img src="https://images.unsplash.com/photo-1522202176988-66273c2fd55f?ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=60" alt="App Launch Campaign">
                <div class="portfolio-overlay">
                    <h3>Mobile App Launch</h3>
                    <p>10,000+ downloads in first month</p>
                </div>
            </div>
        </div>
    </section>

    <section id="about" style="background-color: #111827;">
        <div class="section-title">
            <h2>About Us</h2>
        </div>
        <div style="max-width: 800px; margin: 0 auto;">
            <p>AdX Digital Lab was founded with a mission to help businesses of all sizes succeed in the digital space. With over 5 years of experience and 200+ successful campaigns, we've developed proven strategies that deliver real results.</p>
            <p>Our team consists of certified digital marketing specialists who stay ahead of industry trends and platform updates to ensure your campaigns perform at their peak potential.</p>
            <p style="margin-top: 2rem;"><strong>Why choose us?</strong></p>
            <ul style="text-align: left;">
                <li>Transparent reporting and analytics</li>
                <li>Custom strategies tailored to your business</li>
                <li>Continuous optimization for maximum results</li>
                <li>Dedicated account management</li>
                <li>Proven track record of success</li>
            </ul>
        </div>
    </section>

    <section id="contact">
        <div class="section-title">
            <h2>Contact Us</h2>
        </div>
        <div class="contact-form">
            <form>
                <div class="form-group">
                    <label for="name">Your Name</label>
                    <input type="text" id="name" required>
                </div>
                <div class="form-group">
                    <label for="email">Email Address</label>
                    <input type="email" id="email" required>
                </div>
                <div class="form-group">
                    <label for="phone">Phone Number</label>
                    <input type="tel" id="phone">
                </div>
                <div class="form-group">
                    <label for="service">Service Interested In</label>
                    <select id="service">
                        <option value="">Select a service</option>
                        <option value="facebook">Facebook/Instagram Ads</option>
                        <option value="google">Google Ads</option>
                        <option value="youtube">YouTube Ads</option>
                        <option value="leadgen">Lead Generation</option>
                        <option value="full">Full Marketing Strategy</option>
                    </select>
                </div>
                <div class="form-group">
                    <label for="message">Your Message</label>
                    <textarea id="message" required></textarea>
                </div>
                <button type="submit" class="btn">Send Message</button>
            </form>
        </div>
        <div style="text-align: center; margin-top: 2rem;">
            <p>Or reach out directly:</p>
            <p><i class="fas fa-envelope"></i> adxamit2@gmail.com</p>
            <p><i class="fas fa-phone"></i> +880 1602831953</p>
            <div class="social-links">
                <a href="#"><i class="fab fa-facebook"></i></a>
                <a href="#"><i class="fab fa-linkedin"></i></a>
                <a href="#"><i class="fab fa-instagram"></i></a>
                <a href="#"><i class="fab fa-whatsapp"></i></a>
            </div>
        </div>
    </section>

    <footer>
        <div style="max-width: 800px; margin: 0 auto;">
            <h3>AdX Digital Lab</h3>
            <p>Your trusted partner for digital marketing success</p>
            <div class="social-links">
                <a href="#"><i class="fab fa-facebook"></i></a>
                <a href="#"><i class="fab fa-linkedin"></i></a>
                <a href="#"><i class="fab fa-instagram"></i></a>
                <a href="#"><i class="fab fa-whatsapp"></i></a>
            </div>
            <p class="copyright">© 2023 AdX Digital Lab. All rights reserved.</p>
        </div>
    </footer>

</body>
</html>
