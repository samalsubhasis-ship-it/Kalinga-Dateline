<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kalinga Datelines | News & Blog</title>
    <style>
        /* Global Styles */
        * { box-sizing: border-box; margin: 0; padding: 0; }
        body { font-family: 'Georgia', serif; line-height: 1.6; color: #222; background-color: #f7f7f7; padding: 0 15px; }
        a { text-decoration: none; color: #111; }
        a:hover { color: #c0392b; }
        ul { list-style: none; }

        /* Header & Branding */
        header { text-align: center; padding: 30px 0 15px 0; border-bottom: 4px double #111; max-width: 1200px; margin: 0 auto; background: #fff; }
        .site-title { font-size: 3.5rem; font-weight: 900; text-transform: uppercase; letter-spacing: -1px; font-family: 'Times New Roman', serif; }
        .site-tagline { font-style: italic; font-size: 1.1rem; color: #555; margin-top: 5px; }
        .site-meta { font-size: 0.9rem; text-transform: uppercase; letter-spacing: 1px; color: #777; margin-top: 10px; border-top: 1px solid #ddd; padding-top: 5px; }

        /* Navigation Menu */
        nav { max-width: 1200px; margin: 0 auto; background: #fff; border-bottom: 1px solid #111; position: sticky; top: 0; z-index: 100; }
        .menu { display: flex; justify-content: center; flex-wrap: wrap; padding: 10px 0; }
        .menu li { margin: 0 15px; }
        .menu a { font-family: Arial, sans-serif; font-weight: bold; text-transform: uppercase; font-size: 0.9rem; }

        /* Ticker / Banner */
        .ticker { max-width: 1200px; margin: 15px auto; background: #c0392b; color: #fff; padding: 8px 15px; font-family: Arial, sans-serif; font-size: 0.9rem; display: flex; }
        .ticker-title { font-weight: bold; text-transform: uppercase; margin-right: 10px; border-right: 1px solid #fff; padding-right: 10px; }

        /* Main Content Layout Container */
        .container { max-width: 1200px; margin: 0 auto; display: grid; grid-template-columns: 3fr 1fr; gap: 30px; }

        /* Main Content Area */
        main { background: #fff; padding: 20px; border: 1px solid #e0e0e0; }
        
        /* Featured Headline */
        .featured-story { border-bottom: 2px solid #eee; padding-bottom: 25px; margin-bottom: 25px; }
        .featured-img { width: 100%; height: 400px; background-color: #ddd; display: flex; align-items: center; justify-content: center; font-style: italic; color: #777; margin-bottom: 15px; font-family: Arial, sans-serif;}
        .featured-story h2 { font-size: 2.2rem; margin-bottom: 10px; line-height: 1.2; }
        .meta-info { font-family: Arial, sans-serif; font-size: 0.85rem; color: #777; margin-bottom: 10px; text-transform: uppercase; }
        .excerpt { font-size: 1.1rem; color: #333; }

        /* News & Blog Grid */
        .article-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 20px; }
        .post-card { border-bottom: 1px solid #eee; padding-bottom: 15px; }
        .post-thumb { width: 100%; height: 180px; background-color: #eee; display: flex; align-items: center; justify-content: center; font-style: italic; color: #888; margin-bottom: 10px; font-family: Arial, sans-serif;}
        .post-card h3 { font-size: 1.4rem; margin-bottom: 8px; line-height: 1.3; }

        /* Sidebar Area */
        aside { background: #fff; padding: 20px; border: 1px solid #e0e0e0; height: fit-content; }
        .widget { margin-bottom: 30px; }
        .widget-title { font-family: Arial, sans-serif; font-size: 1.1rem; text-transform: uppercase; border-bottom: 2px solid #111; padding-bottom: 5px; margin-bottom: 15px; letter-spacing: 0.5px; }
        
        /* Sidebar List Items */
        .trending-item { padding: 10px 0; border-bottom: 1px solid #eee; display: flex; align-items: flex-start; }
        .trending-number { font-size: 1.5rem; font-weight: bold; color: #c0392b; margin-right: 15px; font-family: Arial, sans-serif; }
        .trending-text h4 { font-size: 1rem; line-height: 1.3; }
        
        /* About Widget Box */
        .about-box { background: #f9f9f9; padding: 15px; border-left: 4px solid #c0392b; font-size: 0.95rem; }

        /* Footer */
        footer { max-width: 1200px; margin: 30px auto 0 auto; background: #111; color: #ccc; text-align: center; padding: 30px 15px; font-family: Arial, sans-serif; font-size: 0.9rem; }
        footer p { margin-bottom: 10px; }
        footer a { color: #fff; }

        /* Responsive adjustments for Tablets and Mobile Screens */
        @media (max-width: 900px) {
            .container { grid-template-columns: 1fr; }
            .site-title { font-size: 2.5rem; }
        }
        @media (max-width: 600px) {
            .article-grid { grid-template-columns: 1fr; }
            .menu { flex-direction: column; align-items: center; }
            .menu li { margin: 5px 0; }
        }
    </style>
</head>
<body>

    <!-- Newspaper Header Section -->
    <header>
        <div class="site-title"><a href="#">Kalinga Datelines</a></div>
        <div class="site-tagline">Truth, Tradition, and Timely Chronicles</div>
        <div class="site-meta">Bhubaneswar, Odisha &bull; Independent Journalism &bull; Free Press</div>
    </header>

    <!-- Main Menu Navigation bar -->
    <nav>
        <ul class="menu">
            <li><a href="#">Home</a></li>
            <li><a href="#">Odisha</a></li>
            <li><a href="#">National</a></li>
            <li><a href="#">Politics</a></li>
            <li><a href="#">Culture & Art</a></li>
            <li><a href="#">Opinion</a></li>
        </ul>
    </nav>

    <!-- Breaking News Ticker bar -->
    <div class="ticker">
        <span class="ticker-title">Breaking:</span>
        <marquee behavior="scroll" direction="left" scrollamount="5">
            Welcome to the launch of Kalinga Datelines. Bringing you verified stories and fresh insights daily.
        </marquee>
    </div>

    <!-- Main Container grid (Content left, Sidebar right) -->
    <div class="container">
        
        <!-- Main News Column -->
        <main>
            <!-- Big Featured Headline Post -->
            <article class="featured-story">
                <div class="featured-img">[Featured Image Placeholder - 1200x800]</div>
                <div class="meta-info">Odisha News &bull; By Staff Writer &bull; October 2026</div>
                <h2><a href="#">Preserving Heritage: The Evolving Cultural Landscapes of Ancient Kalinga</a></h2>
                <p class="excerpt">Explore the structural transformations, deep-rooted historical narratives, and ongoing community initiatives dedicated to safeguarding Odisha's monumental architecture and dynamic folk arts for future generations...</p>
            </article>

            <!-- Secondary Blog Post Cards Grid Grid Layout -->
            <div class="article-grid">
                
                <article class="post-card">
                    <div class="post-thumb">[Image Placeholder]</div>
                    <div class="meta-info">Economy &bull; 2 Days Ago</div>
                    <h3><a href="#">New Economic Corridors Set to Boost Regional Trade Hubs</a></h3>
                    <p>An in-depth report exploring upcoming infrastructure investments across the local districts.</p>
                </article>

                <article class="post-card">
                    <div class="post-thumb">[Image Placeholder]</div>
                    <div class="meta-info">Art & Culture &bull; 3 Days Ago</div>
                    <h3><a href="#">Handloom Weavers Showcase Rare Craft Traditions</a></h3>
                    <p>Celebrating the artisans keeping traditional intricate patterns alive against modern challenges.</p>
                </article>

                <article class="post-card">
                    <div class="post-thumb">[Image Placeholder]</div>
                    <div class="meta-info">Environment &bull; 5 Days Ago</div>
                    <h3><a href="#">Eco-Tourism Initiatives Expand Along the Coastline</a></h3>
                    <p>How low-impact travel structures are helping protect vulnerable regional marine biomes.</p>
                </article>

                <article class="post-card">
                    <div class="post-thumb">[Image Placeholder]</div>
                    <div class="meta-info">Tech & Trends &bull; 1 Week Ago</div>
                    <h3><a href="#">Digital Literacy Drives Change Across Rural Learning Centers</a></h3>
                    <p>New open-source software installations empower regional students to explore coding early.</p>
                </article>

            </div>
        </main>

        <!-- Sidebar Widgets Column -->
        <aside>
            <!-- About Section Widget -->
            <div class="widget">
                <h3 class="widget-title">About the Journal</h3>
                <div class="about-box">
                    <p><strong>Kalinga Datelines</strong> is dedicated to delivering independent journalism, comprehensive analysis, and narrative essays focusing on news, heritage, and contemporary socio-economic shifts.</p>
                </div>
            </div>

            <!-- Trending / Popular Articles List Widget -->
            <div class="widget">
                <h3 class="widget-title">Trending Stories</h3>
                
                <div class="trending-item">
                    <div class="trending-number">01</div>
                    <div class="trending-text">
                        <h4><a href="#">Discovering Lesser-Known Archeological Sites Near Mahanadi Valley</a></h4>
                    </div>
                </div>

                <div class="trending-item">
                    <div class="trending-number">02</div>
                    <div class="trending-text">
                        <h4><a href="#">Public Transits See Fleet Upgrades with Green Energy Integrations</a></h4>
                    </div>
