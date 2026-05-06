[Mobile Shop.html  .html](https://github.com/user-attachments/files/27433675/Mobile.Shop.html.html)
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TechZone Gadget Store | Latest Electronics 2026</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Segoe UI', Arial, sans-serif;
            line-height: 1.6;
            background: #f4f7fa;
            color: #333;
        }
        
        /* Header & Navigation */
        header {
            background: #0a192f;
            color: white;
            padding: 1rem 0;
            position: sticky;
            top: 0;
            z-index: 100;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
        }
        
        nav {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            flex-wrap: wrap;
        }
        
        .logo {
            font-size: 1.8rem;
            font-weight: bold;
            color: #64ffda;
        }
        
        .nav-links {
            list-style: none;
            display: flex;
            gap: 1.5rem;
        }
        
        .nav-links a {
            color: white;
            text-decoration: none;
            font-weight: 500;
            transition: color 0.3s;
        }
        
        .nav-links a:hover {
            color: #64ffda;
        }
        
        /* Hero Banner */
        .hero {
            background: linear-gradient(135deg, #0a192f 0%, #112240 100%);
            color: white;
            text-align: center;
            padding: 4rem 20px;
        }
        
        .hero h1 {
            font-size: 2.5rem;
            margin-bottom: 1rem;
        }
        
        .badge {
            display: inline-block;
            background: #ff4757;
            color: white;
            padding: 0.3rem 1rem;
            border-radius: 20px;
            font-size: 0.9rem;
            margin-top: 1rem;
        }
        
        /* Main Content */
        main {
            max-width: 1200px;
            margin: 2rem auto;
            padding: 0 20px;
        }
        
        .category {
            margin-bottom: 3rem;
        }
        
        .category h2 {
            font-size: 2rem;
            color: #0a192f;
            border-left: 5px solid #64ffda;
            padding-left: 1rem;
            margin-bottom: 1.5rem;
        }
        
        .product-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 1.5rem;
        }
        
        .product-card {
            background: white;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 4px 15px rgba(0,0,0,0.08);
            transition: transform 0.3s, box-shadow 0.3s;
        }
        
        .product-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 25px rgba(0,0,0,0.15);
        }
        
        .product-card img {
            width: 100%;
            height: 200px;
            object-fit: cover;
        }
        
        .product-info {
            padding: 1.2rem;
        }
        
        .product-info h3 {
            color: #0a192f;
            margin-bottom: 0.5rem;
        }
        
        .price {
            font-size: 1.3rem;
            color: #2ecc71;
            font-weight: bold;
            margin: 0.5rem 0;
        }
        
        .stock {
            display: inline-block;
            padding: 0.2rem 0.8rem;
            border-radius: 5px;
            font-size: 0.85rem;
            font-weight: 600;
        }
        
        .in-stock {
            background: #d4edda;
            color: #155724;
        }
        
        .low-stock {
            background: #fff3cd;
            color: #856404;
        }
        
        .offer-tag {
            background: #ff4757;
            color: white;
            padding: 0.2rem 0.6rem;
            border-radius: 5px;
            font-size: 0.8rem;
            margin-left: 0.5rem;
        }
        
        .new-tag {
            background: #3742fa;
            color: white;
            padding: 0.2rem 0.6rem;
            border-radius: 5px;
            font-size: 0.8rem;
            margin-left: 0.5rem;
        }
        
        /* Footer */
        footer {
            background: #0a192f;
            color: #8892b0;
            text-align: center;
            padding: 2rem 20px;
            margin-top: 3rem;
        }
        
        footer a {
            color: #64ffda;
            text-decoration: none;
        }
        
        /* Mobile Responsive */
        @media (max-width: 768px) {
            .nav-links {
                margin-top: 1rem;
                width: 100%;
                justify-content: center;
            }
            .hero h1 {
                font-size: 2rem;
            }
        }
    </style>
</head>
<body>
    <header>
        <nav>
            <div class="logo">TechZone ⚡</div>
            <ul class="nav-links">
                <li><a href="#smartphones">Smartphones</a></li>
                <li><a href="#laptops">Laptops</a></li>
                <li><a href="#audio">Audio</a></li>
                <li><a href="#wearables">Wearables</a></li>
                <li><a href="#gaming">Gaming</a></li>
            </ul>
        </nav>
    </header>

    <section class="hero">
        <h1>Welcome to TechZone Gadget Store</h1>
        <p>Your #1 Destination for Latest Electronics in Sri Lanka</p>
        <span class="badge">🔥 May Mega Sale - Up to 40% OFF</span>
    </section>

    <main>
        <!-- Smartphones -->
        <section id="smartphones" class="category">
            <h2>Smartphones</h2>
            <div class="product-grid">
                <article class="product-card">
                    <img src="https://images.unsplash.com/photo-1511707171634-5f897ff02aa9?w=400" alt="Galaxy S26 Ultra">
                    <div class="product-info">
                        <h3>Samsung Galaxy S26 Ultra <span class="new-tag">NEW</span></h3>
                        <p>200MP Camera, Snapdragon 8 Gen 4, 5000mAh, AI Features</p>
                        <p class="price">Rs. 329,999 <span class="offer-tag">10% OFF</span></p>
                        <span class="stock in-stock">In Stock</span>
                    </div>
                </article>

                <article class="product-card">
                    <img src="https://images.unsplash.com/photo-1592750475338-74b7b21085ab?w=400" alt="iPhone 17 Pro">
                    <div class="product-info">
                        <h3>iPhone 17 Pro Max</h3>
                        <p>A19 Bionic, Titanium Body, 48MP Pro Camera, USB-C</p>
                        <p class="price">Rs. 389,999</p>
                        <span class="stock in-stock">In Stock</span>
                    </div>
                </article>

                <article class="product-card">
                    <img src="https://images.unsplash.com/photo-1574944985070-8f3ebc6b79d2?w=400" alt="Pixel 9 Pro">
                    <div class="product-info">
                        <h3>Google Pixel 9 Pro <span class="offer-tag">HOT DEAL</span></h3>
                        <p>Tensor G5, Best AI Camera, 7 Years Updates, Pure Android</p>
                        <p class="price">Rs. 274,999</p>
                        <span class="stock low-stock">Only 3 Left</span>
                    </div>
                </article>
            </div>
        </section>

        <!-- Laptops -->
        <section id="laptops" class="category">
            <h2>Laptops</h2>
            <div class="product-grid">
                <article class="product-card">
                    <img src="https://images.unsplash.com/photo-1496181133206-80ce9b88a853?w=400" alt="MacBook Air M4">
                    <div class="product-info">
                        <h3>MacBook Air M4 <span class="new-tag">NEW</span></h3>
                        <p>Apple M4 Chip, 18hr Battery, 13.6" Liquid Retina, 16GB RAM</p>
                        <p class="price">Rs. 349,999</p>
                        <span class="stock in-stock">In Stock</span>
                    </div>
                </article>

                <article class="product-card">
                    <img src="https://images.unsplash.com/photo-1588872657578-7efd1f1555ed?w=400" alt="Dell XPS 14">
                    <div class="product-info">
                        <h3>Dell XPS 14 Plus</h3>
                        <p>Intel Ultra 7, RTX 4050, 32GB RAM, 1TB SSD, OLED Display</p>
                        <p class="price">Rs. 425,000 <span class="offer-tag">5% OFF</span></p>
                        <span class="stock in-stock">In Stock</span>
                    </div>
                </article>

                <article class="product-card">
                    <img src="https://images.unsplash.com/photo-1541807084-5c52b6b3adef?w=400" alt="ASUS ROG">
                    <div class="product-info">
                        <h3>ASUS ROG Zephyrus G16</h3>
                        <p>Ryzen 9, RTX 4070, 240Hz Display, Gaming Beast</p>
                        <p class="price">Rs. 499,999</p>
                        <span class="stock low-stock">Only 2 Left</span>
                    </div>
                </article>
            </div>
        </section>

        <!-- Audio & Headphones -->
        <section id="audio" class="category">
            <h2>Audio & Headphones</h2>
            <div class="product-grid">
                <article class="product-card">
                    <img src="https://images.unsplash.com/photo-1505740420928-5e560c06d30e?w=400" alt="Sony WH-1000XM6">
                    <div class="product-info">
                        <h3>Sony WH-1000XM6 <span class="new-tag">NEW</span></h3>
                        <p>Industry Leading Noise Cancelling, 40hr Battery, Hi-Res Audio</p>
                        <p class="price">Rs. 89,999</p>
                        <span class="stock in-stock">In Stock</span>
                    </div>
                </article>

                <article class="product-card">
                    <img src="https://images.unsplash.com/photo-1606220588913-b3aacb4d2f46?w=400" alt="AirPods Pro 3">
                    <div class="product-info">
                        <h3>Apple AirPods Pro 3</h3>
                        <p>USB-C, Adaptive Audio, Lossless Audio, 2x ANC</p>
                        <p class="price">Rs. 72,999 <span class="offer-tag">15% OFF</span></p>
                        <span class="stock in-stock">In Stock</span>
                    </div>
                </article>

                <article class="product-card">
                    <img src="https://images.unsplash.com/photo-1545127398-14699f92334b?w=400" alt="JBL Speaker">
                    <div class="product-info">
                        <h3>JBL Charge 6 Bluetooth Speaker</h3>
                        <p>20hr Playtime, Waterproof IP67, PartyBoost, Powerbank</p>
                        <p class="price">Rs. 34,999</p>
                        <span class="stock in-stock">In Stock</span>
                    </div>
                </article>
            </div>
        </section>

        <!-- Smartwatches / Wearables -->
        <section id="wearables" class="category">
            <h2>Smartwatches & Wearables</h2>
            <div class="product-grid">
                <article class="product-card">
                    <img src="https://images.unsplash.com/photo-1579586337278-3befd40fd17a?w=400" alt="Apple Watch">
                    <div class="product-info">
                        <h3>Apple Watch Series 11 <span class="new-tag">NEW</span></h3>
                        <p>Blood Pressure Monitor, S11 Chip, Brighter Display, 36hr Battery</p>
                        <p class="price">Rs. 129,999</p>
                        <span class="stock in-stock">In Stock</span>
                    </div>
                </article>

                <article class="product-card">
                    <img src="https://images.unsplash.com/photo-1557438159-51eec7a6c9e8?w=400" alt="Galaxy Watch">
                    <div class="product-info">
                        <h3>Samsung Galaxy Watch 7 Pro</h3>
                        <p>Wear OS, ECG, Body Composition, Sapphire Glass</p>
                        <p class="price">Rs. 84,999</p>
                        <span class="stock in-stock">In Stock</span>
                    </div>
                </article>

                <article class="product-card">
                    <img src="https://images.unsplash.com/photo-1508685096489-7a5d006b6292?w=400" alt="Garmin">
                    <div class="product-info">
                        <h3>Garmin Forerunner 965 <span class="offer-tag">SPECIAL</span></h3>
                        <p>AMOLED, GPS, 31hr Battery, Advanced Running Metrics</p>
                        <p class="price">Rs. 164,999</p>
                        <span class="stock low-stock">Only 5 Left</span>
                    </div>
                </article>
            </div>
        </section>

        <!-- Gaming Accessories -->
        <section id="gaming" class="category">
            <h2>Gaming Accessories</h2>
            <div class="product-grid">
                <article class="product-card">
                    <img src="https://images.unsplash.com/photo-1612287230202-1ff1d85d1bdf?w=400" alt="PS5 Controller">
                    <div class="product-info">
                        <h3>PS5 DualSense Edge Pro <span class="new-tag">NEW</span></h3>
                        <p>Customizable Buttons, Replaceable Sticks, Pro Controller</p>
                        <p class="price">Rs. 64,999</p>
                        <span class="stock in-stock">In Stock</span>
                    </div>
                </article>

                <article class="product-card">
                    <img src="https://images.unsplash.com/photo-1615663245857-ac93bb7c39e7?w=400" alt="Gaming Mouse">
                    <div class="product-info">
                        <h3>Logitech G Pro X Superlight 2</h3>
                        <p>60g, HERO 2 Sensor, 95hr Battery, Esports Mouse</p>
                        <p class="price">Rs. 42,999 <span class="offer-tag">20% OFF</span></p>
                        <span class="stock in-stock">In Stock</span>
                    </div>
                </article>

                <article class="product-card">
                    <img src="https://images.unsplash.com/photo-1547394765-185e1e68f34e?w=400" alt="Gaming Keyboard">
                    <div class="product-info">
                        <h3>Razer Huntsman V3 Pro</h3>
                        <p>Analog Optical Switches, Rapid Trigger, RGB, Wrist Rest</p>
                        <p class="price">Rs. 54,999</p>
                        <span class="stock in-stock">In Stock</span>
                    </div>
                </article>
            </div>
        </section>
    </main>

    <footer>
        <p>&copy; 2026 TechZone Gadget Store | Colombo, Sri Lanka</p>
        <p>Contact: <a href="mailto:info@techzone.lk">info@techzone.lk</a> | Tel: 011-2345678</p>
        <p>Special Offers Updated Weekly | Free Delivery Above Rs. 50,000</p>
    </footer>
</body>
</html>
