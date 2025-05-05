<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Explore the weapons and military equipment of the Kazakh Khanate, reflecting the spirit of steppe warriors.">
    <meta name="author" content="Nurmuhammad Nazirov">
    <title>Kazakh Khanate Weapons</title>
    <style>
        /* CSS Reset */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Arial', sans-serif;
            background-color: #f5f5f5;
            color: #333;
            line-height: 1.6;
        }
        
        /* Header Styles */
        header {
            background: linear-gradient(rgba(0, 0, 0, 0.7), rgba(0, 0, 0, 0.7)), url('https://images.unsplash.com/photo-1604977048617-3fe9b644a6cd?ixlib=rb-4.0.3&auto=format&fit=crop&w=1950&q=80') no-repeat center center/cover;
            color: #fff;
            text-align: center;
            padding: 100px 20px;
            position: relative;
        }
        
        header h1 {
            font-size: 2.8rem;
            margin-bottom: 15px;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
        }
        
        header p {
            font-size: 1.2rem;
            max-width: 800px;
            margin: 0 auto;
            text-shadow: 1px 1px 2px rgba(0, 0, 0, 0.5);
        }
        
        /* Author Credit */
        .author-credit {
            position: absolute;
            bottom: 20px;
            right: 20px;
            background-color: rgba(0, 0, 0, 0.5);
            padding: 5px 10px;
            border-radius: 5px;
            font-style: italic;
        }
        
        /* Navigation */
        nav {
            background-color: #3a2f1e;
            position: sticky;
            top: 0;
            z-index: 100;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.2);
        }
        
        .nav-container {
            display: flex;
            justify-content: center;
            max-width: 1200px;
            margin: 0 auto;
        }
        
        nav a {
            color: #fff;
            text-decoration: none;
            padding: 15px 20px;
            display: inline-block;
            transition: all 0.3s ease;
            font-weight: bold;
        }
        
        nav a:hover {
            color: #d4a373;
            background-color: rgba(255, 255, 255, 0.1);
        }
        
        nav a.active {
            border-bottom: 3px solid #d4a373;
        }
        
        /* Language Switcher */
        .language-switcher {
            position: absolute;
            top: 20px;
            right: 20px;
            z-index: 10;
        }
        
        .language-switcher select {
            padding: 8px 12px;
            font-size: 16px;
            background-color: rgba(58, 47, 30, 0.8);
            color: #fff;
            border: 1px solid #d4a373;
            border-radius: 4px;
            cursor: pointer;
            transition: all 0.3s ease;
        }
        
        .language-switcher select:hover {
            background-color: rgba(58, 47, 30, 1);
        }
        
        /* Main Content */
        .container {
            max-width: 1200px;
            margin: 20px auto;
            padding: 0 20px;
        }
        
        .steppe-spirit {
            font-style: italic;
            color: #6d5637;
            text-align: center;
            margin: 30px 0;
            font-size: 1.2rem;
            padding: 15px;
            background-color: rgba(212, 163, 115, 0.1);
            border-radius: 8px;
        }
        
        section {
            margin-bottom: 40px;
            background-color: #fff;
            padding: 30px;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        
        section:hover {
            transform: translateY(-5px);
            box-shadow: 0 6px 12px rgba(0, 0, 0, 0.15);
        }
        
        /* Gray background for Introduction section */
        #introduction {
            background-color: #e0e0e0;
        }
        
        section h2 {
            color: #3a2f1e;
            border-bottom: 2px solid #d4a373;
            padding-bottom: 10px;
            margin-bottom: 20px;
            font-size: 1.8rem;
        }
        
        section p {
            margin-bottom: 20px;
        }
        
        section ul {
            list-style-position: inside;
            margin-bottom: 20px;
        }
        
        section li {
            margin-bottom: 12px;
            padding-left: 10px;
        }
        
        /* Weapon Categories */
        .weapon-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
            gap: 20px;
            margin-top: 25px;
        }
        
        .weapon-card {
            background-color: #f9f5f0;
            border-radius: 8px;
            padding: 20px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease;
        }
        
        .weapon-card:hover {
            transform: translateY(-5px);
        }
        
        .weapon-card h3 {
            color: #6d5637;
            margin-bottom: 10px;
            border-bottom: 1px solid #d4a373;
            padding-bottom: 5px;
        }
        
        .weapon-icon {
            font-size: 2rem;
            color: #3a2f1e;
            margin-bottom: 10px;
            display: block;
            text-align: center;
        }
        
        /* Maps Container */
        .maps-container {
            display: flex;
            flex-direction: column;
            gap: 30px;
            margin: 30px 0;
        }
        
        .historical-map {
            border: 3px solid #3a2f1e;
            border-radius: 8px;
            padding: 5px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            width: 100%;
            max-width: 800px;
            margin: 0 auto;
            display: block;
            transition: transform 0.3s ease;
        }
        
        .historical-map:hover {
            transform: scale(1.02);
        }
        
        .google-map {
            width: 100%;
            height: 400px;
            border: 3px solid #3a2f1e;
            border-radius: 8px;
            overflow: hidden;
        }
        
        .map-caption {
            font-style: italic;
            text-align: center;
            margin-top: 10px;
            color: #555;
        }
        
        .territory-highlight {
            margin-top: 20px;
            padding: 20px;
            background-color: rgba(212, 163, 115, 0.1);
            border-left: 4px solid #d4a373;
            border-radius: 0 8px 8px 0;
        }
        
        .territory-highlight h3 {
            color: #6d5637;
            margin-bottom: 10px;
        }
        
        /* Timeline */
        .timeline {
            position: relative;
            max-width: 1000px;
            margin: 40px auto;
            padding: 20px 0;
        }
        
        .timeline::after {
            content: '';
            position: absolute;
            width: 6px;
            background-color: #d4a373;
            top: 0;
            bottom: 0;
            left: 50%;
            margin-left: -3px;
            border-radius: 10px;
        }
        
        .timeline-item {
            padding: 10px 40px;
            position: relative;
            width: 50%;
            box-sizing: border-box;
        }
        
        .timeline-item::after {
            content: '';
            position: absolute;
            width: 20px;
            height: 20px;
            background-color: #fff;
            border: 4px solid #d4a373;
            top: 15px;
            border-radius: 50%;
            z-index: 1;
        }
        
        .left {
            left: 0;
        }
        
        .right {
            left: 50%;
        }
        
        .left::after {
            right: -10px;
        }
        
        .right::after {
            left: -10px;
        }
        
        .timeline-content {
            padding: 20px;
            background-color: #fff;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        
        .timeline-content h3 {
            color: #3a2f1e;
            margin-bottom: 10px;
        }
        
        /* Turkestan Highlight */
        .turkestan-highlight {
            background-color: rgba(255, 0, 0, 0.2);
            border: 2px solid red;
            border-radius: 50%;
            width: 20px;
            height: 20px;
            position: absolute;
            transform: translate(-50%, -50%);
        }
        
        /* Footer */
        footer {
            background-color: #3a2f1e;
            color: #fff;
            text-align: center;
            padding: 40px 0;
            margin-top: 40px;
        }
        
        .footer-content {
            max-width: 1200px;
            margin: 0 auto;
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            gap: 30px;
            padding: 0 20px;
        }
        
        .footer-section h3 {
            color: #d4a373;
            margin-bottom: 15px;
            border-bottom: 1px solid rgba(255, 255, 255, 0.1);
            padding-bottom: 10px;
        }
        
        .footer-section p {
            margin-bottom: 10px;
        }
        
        .social-icons {
            display: flex;
            justify-content: center;
            gap: 15px;
            margin-top: 15px;
        }
        
        .social-icons a {
            color: #fff;
            font-size: 1.5rem;
            transition: color 0.3s ease;
        }
        
        .social-icons a:hover {
            color: #d4a373;
        }
        
        .copyright {
            margin-top: 30px;
            padding-top: 20px;
            border-top: 1px solid rgba(255, 255, 255, 0.1);
        }
        
        /* Back to Top Button */
        .back-to-top {
            position: fixed;
            bottom: 20px;
            right: 20px;
            background-color: #3a2f1e;
            color: #fff;
            width: 50px;
            height: 50px;
            border-radius: 50%;
            display: flex;
            justify-content: center;
            align-items: center;
            text-decoration: none;
            font-size: 1.5rem;
            opacity: 0;
            transition: opacity 0.3s ease, background-color 0.3s ease;
            z-index: 99;
        }
        
        .back-to-top.visible {
            opacity: 1;
        }
        
        .back-to-top:hover {
            background-color: #d4a373;
        }
        
        /* Animation */
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }
        
        .fade-in {
            animation: fadeIn 1s ease forwards;
        }
        
        /* Responsive Design */
        @media (max-width: 768px) {
            header {
                padding: 60px 20px;
            }
            
            header h1 {
                font-size: 2rem;
            }
            
            .nav-container {
                flex-direction: column;
            }
            
            nav a {
                padding: 10px;
                display: block;
                text-align: center;
            }
            
            .timeline::after {
                left: 40px;
            }
            
            .timeline-item {
                width: 100%;
                padding-left: 80px;
                padding-right: 20px;
            }
            
            .timeline-item::after {
                left: 30px;
            }
            
            .right {
                left: 0;
            }
            
            .left::after, .right::after {
                left: 30px;
            }
            
            .language-switcher {
                top: 10px;
                right: 10px;
            }
            
            .language-switcher select {
                padding: 5px 8px;
                font-size: 14px;
            }
            
            .google-map {
                height: 300px;
            }
            
            .footer-content {
                grid-template-columns: 1fr;
            }
            
            .author-credit {
                position: static;
                margin-top: 20px;
                text-align: center;
            }
        }
    </style>
</head>
<body>
    <header>
        <div class="language-switcher">
            <select id="language" onchange="changeLanguage()">
                <option value="en">English</option>
                <option value="tr">Türkçe</option>
                <option value="kk">Қазақша</option>
            </select>
        </div>
        <h1 id="header-title" class="fade-in">Weapons of the Kazakh Khanate</h1>
        <p id="header-subtitle" class="fade-in">Discover the Art and Spirit of Steppe Warriors</p>
        <div class="author-credit">Created by: Nurmuhammad Nazirov</div>
    </header>
    
    <nav>
        <div class="nav-container">
            <a href="#introduction" id="nav-intro" class="active">Introduction</a>
            <a href="#timeline" id="nav-timeline">Timeline</a>
            <a href="#light-weapons" id="nav-light">Light Weapons</a>
            <a href="#heavy-weapons" id="nav-heavy">Heavy Weapons</a>
            <a href="#defensive-gear" id="nav-defense">Defensive Gear</a>
            <a href="#conclusion" id="nav-conclusion">Conclusion</a>
        </div>
    </nav>
    
    <div class="container">
        <p class="steppe-spirit fade-in" id="steppe-spirit">"Forged in the heart of the steppe, the weapons of the Kazakh Khanate embody the courage and resilience of its warriors."</p>
        
        <section id="introduction" class="fade-in">
            <h2 id="intro-title">Introduction</h2>
            <p id="intro-text">The Kazakh Khanate (1465–1847), founded by Kerei and Janibek Khans, was a powerful state in Central Asia. Its military prowess was deeply tied to the effectiveness of its weapons, tailored to the nomadic lifestyle, regional geography, and external threats. This website explores the types, technologies, and tactical significance of the Kazakh Khanate's weapons, revealing the military culture and technological capabilities of the Kazakh people.</p>
            
            <div class="maps-container">
                <div>
                    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/5/5f/Kazakh_Khanate_18th_century.png/800px-Kazakh_Khanate_18th_century.png" alt="Historical Map of the Kazakh Khanate" class="historical-map">
                    <p class="map-caption">Historical map of the Kazakh Khanate territories in the 18th century</p>
                </div>
                
                <div>
                    <div class="google-map" id="google-map">
                        <!-- Google Maps embed showing modern-day Kazakhstan and surrounding territories with Turkestan highlighted -->
                        <iframe id="map-iframe" src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d11781093.655456294!2d56.03529255!3d48.16199595!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x38a91007ecfca947%3A0x5f7b842fe4b30e1b!2sKazakhstan!5e0!3m2!1sen!2sus!4v1651562184432!5m2!1sen!2sus" width="100%" height="100%" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
                    </div>
                    <p class="map-caption" id="map-caption">Modern-day map of Kazakhstan, with Turkestan city highlighted in red</p>
                </div>
                
                <div class="territory-highlight" id="territory-highlight">
                    <h3>Kazakh Khanate Territories</h3>
                    <p>The Kazakh Khanate's historical territory included present-day Kazakhstan, parts of Uzbekistan, Kyrgyzstan, and western China. The Khanate was traditionally divided into three main hordes (zhuz): the Senior Zhuz (southeastern), Middle Zhuz (central and northern), and Junior Zhuz (western), each with their own distinctive military traditions.</p>
                </div>
            </div>
        </section>
        
        <section id="timeline" class="fade-in">
            <h2 id="timeline-title">Historical Timeline</h2>
            <p id="timeline-text">The evolution of military technology in the Kazakh Khanate was shaped by historical events and regional influences.</p>
            
            <div class="timeline">
                <div class="timeline-item left">
                    <div class="timeline-content">
                        <h3>1465</h3>
                        <p id="timeline-1">Foundation of the Kazakh Khanate by Kerei and Janibek Khans. Early weapons were primarily traditional steppe nomadic arms like composite bows and sabers.</p>
                    </div>
                </div>
                <div class="timeline-item right">
                    <div class="timeline-content">
                        <h3>16th Century</h3>
                        <p id="timeline-2">Development of distinctive Kazakh military equipment influenced by conflicts with neighboring states and Mongol heritage.</p>
                    </div>
                </div>
                <div class="timeline-item left">
                    <div class="timeline-content">
                        <h3>17th Century</h3>
                        <p id="timeline-3">Introduction of early firearms through trade routes and military exchanges with Russia, China, and Central Asian states.</p>
                    </div>
                </div>
                <div class="timeline-item right">
                    <div class="timeline-content">
                        <h3>18th Century</h3>
                        <p id="timeline-4">Refinement of metalwork techniques, leading to improved quality of bladed weapons and defensive equipment.</p>
                    </div>
                </div>
                <div class="timeline-item left">
                    <div class="timeline-content">
                        <h3>19th Century</h3>
                        <p id="timeline-5">Increasing adoption of modern weapons and gradual decline of traditional arms as Russian influence expanded.</p>
                    </div>
                </div>
                <div class="timeline-item right">
                    <div class="timeline-content">
                        <h3>1847</h3>
                        <p id="timeline-6">The end of the Kazakh Khanate's independence, marking a transition in military equipment and traditions.</p>
                    </div>
                </div>
            </div>
        </section>
        
        <section id="light-weapons" class="fade-in">
            <h2 id="light-weapons-title">Light Weapons</h2>
            <p id="light-weapons-text">Light weapons were the backbone of the Kazakh warriors' arsenal, designed for mobility and precision across the vast steppe landscape. These weapons enabled the horsemen to strike quickly and effectively against various opponents.</p>
            
            <div class="weapon-grid">
                <div class="weapon-card">
                    <span class="weapon-icon">🏹</span>
                    <h3>Composite Bow</h3>
                    <p id="light-weapons-bow">Made from wood, bone, horn, sinew, and glue, the Kazakh composite bow was short (110–130 cm) but powerful, capable of piercing armor at 300–350 meters. These bows could be used effectively from horseback and were the primary ranged weapon of steppe warriors.</p>
                </div>
                
                <div class="weapon-card">
                    <span class="weapon-icon">🔪</span>
                    <h3>Arrow Types</h3>
                    <p id="light-weapons-arrows">Included piercing arrows, broadhead arrows, whistling arrows for psychological effects, and incendiary arrows for sieges. Each type served specific tactical purposes and could be quickly accessed from quivers during battle.</p>
                </div>
                
                <div class="weapon-card">
                    <span class="weapon-icon">⚔️</span>
                    <h3>Swords and Daggers</h3>
                    <p id="light-weapons-sword">Curved sabers, straight double-edged swords, and daggers like the kenzhik were common, often decorated with silver or precious stones. These weapons reflected the status of their owners and were crafted with exceptional attention to balance and cutting power.</p>
                </div>
                
                <div class="weapon-card">
                    <span class="weapon-icon">🔱</span>
                    <h3>Spears</h3>
                    <p id="light-weapons-spear">Long naiyza (250–300 cm) and shorter sungi were used by cavalry, with some featuring hooks to unhorse enemies. Spearheads were designed to penetrate armor and could be used for both thrusting and throwing techniques in combat.</p>
                </div>
                
                <div class="weapon-card">
                    <span class="weapon-icon">🪓</span>
                    <h3>Maces and Axes</h3>
                    <p id="light-weapons-mace">Shokpar (maces) and aybalta (axes) were effective against armored foes, showcasing advanced metallurgy. These impact weapons could crush or penetrate armor that might resist cutting weapons and were often carried as secondary arms.</p>
                </div>
            </div>
        </section>
        
        <section id="heavy-weapons" class="fade-in">
            <h2 id="heavy-weapons-title">Heavy Weapons</h2>
            <p id="heavy-weapons-text">Heavy weapons, though less common due to the nomadic lifestyle, played a role in sieges and major battles. As the Khanate developed, these weapons became increasingly important for territorial defense and expansion.</p>
            
            <div class="weapon-grid">
                <div class="weapon-card">
                    <span class="weapon-icon">💣</span>
                    <h3>Artillery</h3>
                    <p id="heavy-weapons-artillery">Light cannons (zenbirek) and camel-mounted zambyrak were used, often acquired from neighboring regions. These portable artillery pieces allowed for surprising mobility on the battlefield while providing significant firepower against fortifications.</p>
                </div>
                
                <div class="weapon-card">
                    <span class="weapon-icon">🔫</span>
                    <h3>Firearms</h3>
                    <p id="heavy-weapons-firearms">Matchlock and flintlock muskets (multyk) and short-barreled tupek were adopted in the 17th–18th centuries. As firearms technology spread throughout Central Asia, Kazakh warriors integrated these weapons alongside traditional arms.</p>
                </div>
                
                <div class="weapon-card">
                    <span class="weapon-icon">🏯</span>
                    <h3>Siege Equipment</h3>
                    <p id="heavy-weapons-siege">Tools like taran (battering rams) and mobile towers were used to breach fortifications. When confronting settled civilizations, the Kazakh forces developed techniques and equipment for overcoming defensive structures.</p>
                </div>
                
                <div class="weapon-card">
                    <span class="weapon-icon">🐎</span>
                    <h3>Cavalry Gear</h3>
                    <p id="heavy-weapons-cavalry">Specialized weapons like syryk (long lances) and arkan (lassos) enhanced the cavalry's effectiveness. Mounted warriors could deploy these tools to control the battlefield and capture enemies or their mounts alive when necessary.</p>
                </div>
            </div>
        </section>
        
        <section id="defensive-gear" class="fade-in">
            <h2 id="defensive-gear-title">Defensive Gear</h2>
            <p id="defensive-gear-text">Defensive equipment was lightweight yet effective, ensuring mobility for steppe warriors while providing crucial protection in battle. Kazakh armor reflected a balance between protection and the need for agility on horseback.</p>
            
            <div class="weapon-grid">
                <div class="weapon-card">
                    <span class="weapon-icon">👕</span>
                    <h3>Armor</h3>
                    <p id="defensive-gear-armor">Chainmail (badana), plate armor (kurysh), and lamellar armor (kireuke) were designed to balance protection and mobility. Elite warriors often wore multiple layers of protection, with silk undergarments to help prevent infection from arrow wounds.</p>
                </div>
                
                <div class="weapon-card">
                    <span class="weapon-icon">🛡️</span>
                    <h3>Shields</h3>
                    <p id="defensive-gear-shield">Round or oval shields (kalkan), made of steel or wood, were often decorated to reflect status. Some shields incorporated hardened leather or metal bosses and were light enough to be maneuvered quickly on horseback.</p>
                </div>
                
                <div class="weapon-card">
                    <span class="weapon-icon">⛑️</span>
                    <h3>Helmets</h3>
                    <p id="defensive-gear-helmet">Dulyga (spherical helmets) and toghylga (flat-topped) featured ear guards and neck protection, some adorned with gold or gems. Helmet design evolved to protect against the most common battlefield threats while still allowing good visibility and hearing.</p>
                </div>
            </div>
        </section>
        
        <section id="conclusion" class="fade-in">
            <h2 id="conclusion-title">Conclusion</h2>
            <p id="conclusion-text">The weapons of the Kazakh Khanate represented a blend of tradition and innovation, adapted to the unique challenges of steppe warfare. From the composite bow to early firearms, Kazakh warriors maintained a sophisticated arsenal that allowed them to defend their territory and build a lasting legacy in Central Asian military history.</p>
        </section>
    </div>
    
    <footer>
        <div class="footer-content">
            <div class="footer-section">
                <h3 id="footer-about">About This Project</h3>
                <p id="footer-about-text">This educational resource aims to preserve and share knowledge about the historical military technology of the Kazakh Khanate. It is designed for students, historians, and enthusiasts interested in Central Asian history.</p>
            </div>
            
            <div class="footer-section">
                <h3 id="footer-contact">Contact</h3>
                <p id="footer-contact-text">For inquiries or further information, please contact us at:</p>
                <p>Email: nurmuhammadnazirov497@gmail.com</p>
            </div>
            
            <div class="footer-section">
                <h3 id="footer-follow">Follow Us</h3>
                <p id="footer-follow-text">Stay updated with our latest research and publications:</p>
                <div class="social-icons">
                    <a href="#" title="Facebook"><i class="fab fa-facebook"></i></a>
                    <a href="#" title="Twitter"><i class="fab fa-twitter"></i></a>
                    <a href="#" title="Instagram"><i class="fab fa-instagram"></i></a>
                </div>
            </div>
        </div>
        <div class="copyright">
            <p id="copyright-text">&copy; 2025 Kazakh Khanate Historical Research. All rights reserved.</p>
        </div>
    </footer>
    
    <a href="#" class="back-to-top" id="back-to-top">↑</a>
    
    <script>
        // Language translations
        const translations = {
            en: {
                "header-title": "Weapons of the Kazakh Khanate",
                "header-subtitle": "Discover the Art and Spirit of Steppe Warriors",
                "nav-intro": "Introduction",
                "nav-timeline": "Timeline",
                "nav-light": "Light Weapons",
                "nav-heavy": "Heavy Weapons",
                "nav-defense": "Defensive Gear",
                "nav-conclusion": "Conclusion",
                "steppe-spirit": "\"Forged in the heart of the steppe, the weapons of the Kazakh Khanate embody the courage and resilience of its
