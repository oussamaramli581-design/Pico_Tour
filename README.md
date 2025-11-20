<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TrailFinder | Your Journey, Our Promise (The Best of Spain's Nature)</title>
    
    <style>
        /* CSS for a professional, nature-inspired look */
        @import url('https://fonts.com/css2?family=Montserrat:wght@400;700&family=Roboto:wght@300;400&display=swap');
        
        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #F7F9FC; 
            color: #333;
            line-height: 1.6;
        }
        
        /* Emotive Header/Hero Section */
        header {
            background-color: #004D40; 
            color: white;
            padding: 80px 0;
            text-align: center;
            /* Placeholder: Use an inspiring image of a vast Spanish landscape */
            background-image: linear-gradient(rgba(0, 77, 64, 0.7), rgba(0, 77, 64, 0.8)), url('path/to/inspirational-granada-bg.jpg'); 
            background-size: cover;
            background-position: bottom;
        }
        header h1 {
            font-family: 'Montserrat', sans-serif;
            font-size: 3.5em;
            margin: 0;
            letter-spacing: 3px;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.5);
        }
        header h2 {
            font-weight: 300;
            font-size: 1.5em;
            margin-top: 15px;
        }
        
        /* Navigation (Same as before) */
        nav {
            background-color: #00796B; 
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
        }
        nav .nav-container {
            max-width: 1200px;
            margin: 0 auto;
            display: flex;
            justify-content: center;
            padding: 18px 20px;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 25px;
            font-weight: 700;
            transition: color 0.3s;
        }
        nav a:hover {
            color: #B2DFDB; 
        }
        
        /* Main Content Cards (Same as before) */
        .container {
            max-width: 1200px;
            margin: 50px auto;
            padding: 0 20px;
        }
        .segment-card {
            background-color: white;
            padding: 40px;
            margin-bottom: 40px;
            border-radius: 10px;
            box-shadow: 0 8px 25px rgba(0,0,0,0.15);
            border-left: 6px solid #FFC107; 
        }
        .segment-card h2 {
            font-family: 'Montserrat', sans-serif;
            color: #004D40;
            font-size: 2.2em;
            margin-top: 0;
            border-bottom: 2px solid #E0F2F1;
            padding-bottom: 10px;
        }
        
        /* New Styles for Destination Gallery */
        .destination-gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            margin-top: 30px;
        }
        .destination-item {
            background: #fff;
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 4px 12px rgba(0,0,0,0.1);
            text-align: center;
        }
        .destination-item img {
            width: 100%;
            height: 180px;
            object-fit: cover;
            display: block;
        }
        .destination-item h4 {
            font-family: 'Montserrat', sans-serif;
            color: #00796B;
            padding: 15px 10px;
            margin: 0;
            font-size: 1.1em;
        }

        /* Product and Strategy Lists (Same as before) */
        .product-item, .strategy-item {
            margin-bottom: 20px;
            padding: 15px;
            border-radius: 6px;
        }
        .product-item {
            background: #E0F2F1; 
            border-left: 4px solid #00796B;
        }
        .strategy-item {
            background: #F0F4F7; 
            border-left: 4px solid #004D40;
        }
        .product-item h4, .strategy-item h4 {
            color: #004D40;
            margin-top: 0;
            font-weight: 700;
        }

        /* Footer (Same as before) */
        footer {
            background-color: #333;
            color: #ccc;
            text-align: center;
            padding: 30px 0;
            margin-top: 50px;
            font-size: 0.9em;
        }
    </style>
</head>
<body>

    <header>
        <h1>Feel the Freedom. Travel with TrailFinder.</h1>
        <h2>Your Adventure is Our Priority. Personalized Assistance across all Spain.</h2>
    </header>

    <nav>
        <div class="nav-container">
            <a href="#mission">Our Promise</a>
            <a href="#destinations">Discover</a>
            <a href="#segment1">For the Brave</a>
            <a href="#segment2">For the Conscientious</a>
            <a href="#strategy">Our Plan</a>
        </div>
    </nav>

    <div class="container">
        
        <section id="mission" class="segment-card">
            <h2>🌍 Your Trustworthy Partner in Nature</h2>
            <p><strong>TrailFinder</strong> is not just an app; it is your digital guardian for Spain's most beautiful national parks and nature trails. Our headquarters are rooted in **Granada**, the gateway to the Sierra Nevada, but our **24/7 information and assistance services** cover every corner of Spain. We ensure your journey is **safe, affordable, and deeply authentic**.</p>
        </section>

        <hr>

        <section id="destinations" class="segment-card">
            <h2>⛰️ Discover Spain's Wilderness: Where We Guide You</h2>
            <p>From the high peaks of the Pyrenees to the volcanic trails of the Canaries, we specialize in the best of Spanish nature. **Your adventure starts here.**</p>
            
            <div class="destination-gallery">
                <div class="destination-item">
                    <img src="path/to/picos-de-europa-image.jpg" alt="Picos de Europa National Park, Asturias/Cantabria">
                    <h4>Picos de Europa: The Rugged North</h4>
                </div>
                <div class="destination-item">
                    <img src="path/to/sierra-nevada-image.jpg" alt="Sierra Nevada National Park, Granada">
                    <h4>Sierra Nevada: Peaks of the South (Near HQ)</h4>
                </div>
                <div class="destination-item">
                    <img src="path/to/ordesa-image.jpg" alt="Ordesa y Monte Perdido National Park, Pyrenees">
                    <h4>Ordesa Valley: Pyrenees Grandeur</h4>
                </div>
                <div class="destination-item">
                    <img src="path/to/teide-image.jpg" alt="Teide National Park, Tenerife, Canary Islands">
                    <h4>El Teide: Volcanic Island Trails</h4>
                </div>
            </div>
        </section>

        <hr>

        <section id="segment1" class="segment-card">
            <h2>🎒 The Brave Hearts: Budget Backpackers (18-30 yrs)</h2>
            <p><strong>Your Emotion: Freedom.</strong> We know you seek unforgettable adventures without breaking the bank. You want to explore freely and connect with the real Spain. We are here to remove the stress of logistics, so you can focus on the journey.</p>
            
            <h3>Our Specialized Services (Products)</h3>
            <div class="product-item">
                <h4>Routes of Pure Adventure & Savings</h4>
                <p>Discover **"Extreme Budget"** trails, connecting you with low-cost accommodation and smart travel hacks. **Travel smart, not rich.**</p>
            </div>
            <div class="product-item">
                <h4>Instant Safety & Support (24/7)</h4>
                <p>Our quick-chat assistance is your lifeline. No more doubts about bus times or emergency contacts. **Peace of mind is just a tap away.**</p>
            </div>

            <div class="strategy-item">
                <h4>Communication Plan: Social Impact</h4>
                <p>**Media:** **Social Media (TikTok, Reels)** and **Direct App Notifications**. </p>
                <p><strong>Justification:</strong> We use fast, highly visual content to match their digital habits and communicate the feeling of freedom instantly. **We speak their language.**</p>
            </div>
        </section>

        <hr>

        <section id="segment2" class="segment-card">
            <h2>🌳 The Conscientious Explorers: Responsible Ecotourists (30-50 yrs)</h2>
            <p><strong>Your Emotion: Integrity.</strong> You believe in travel that gives back. You want to delve deep into nature, ensuring your presence is respectful and sustainable. We provide the expert knowledge you need to travel with a clean conscience and high comfort.</p>
            
            <h3>Our Specialized Services (Products)</h3>
            <div class="product-item">
                <h4>Curated Sustainable Experiences</h4>
                <p>Access our **"Certified Low-Impact"** itineraries, detailing local conservation efforts and zero-waste trekking guidance. **Travel well, live better.**</p>
            </div>
            <div class="product-item">
                <h4>Premium Logistical Security</h4>
                <p>Enjoy **expert video consultations** with mountain guides for advanced weather checks and detailed equipment preparation. **Security is not an option; it's a guarantee.**</p>
            </div>

            <div class="strategy-item">
                <h4>Communication Plan: Credibility & Value</h4>
                <p>**Media:** **Expert Newsletters** (Direct Marketing) and **Specialized Publications** (Niche Media).</p>
                <p><strong>Justification:</strong> We rely on content and platforms that build **trust and authority** to validate our commitment to quality and sustainability. **We earn their respect.**</p>
            </div>
        </section>
        
        <hr>
        
        <section id="strategy" class="segment-card">
            <h2>🧭 Segmentation & Strategy Summary (Academic Compliance)</h2>
            <p>This entire model is built upon a robust marketing strategy, defined by:</p>
            
            <ul>
                <li>**Bases Used:** **Behavioural** (Price vs. Sustainability focus), **Demographic** (Age/Income), and **Geographic** (Nature focus).</li>
                <li>**Criteria Met:** Our strategy is **Measurable** (data available from INE/OAPN), **Substantial** (profitable volume/value), and **Accessible** (digital outreach).</li>
            </ul>
        </section>

    </div>

    <footer>
        <p>&copy; 2025 TrailFinder. Information and Tourism Assistance. | Headquartered in Granada, providing tours across all Spain.</p>
    </footer>

</body>
</html>
