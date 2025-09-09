 .. raw:: html

    <style>
      :root{
        --brand:#173a67;       /* Deep Blue */
        --brand-2:#2e4e76;     /* Muted Blue */
        --accent:#28a745;      /* Green accent */
        --cta:#007bff;         /* Primary CTA */
        --text:#0f172a;
        --muted:#475569;
        --bg:#ffffff;
        --card:#f8fafc;
        --radius:14px;
        --shadow:0 6px 20px rgba(2,12,27,.08);
      }
      *{box-sizing:border-box}
      body{background:var(--bg); color:var(--text); font-family:system-ui,-apple-system,"Segoe UI",Roboto,Inter,Arial,sans-serif; line-height:1.6}
      .container{max-width:960px;margin:0 auto;padding:0 16px}
      /* Sticky Top Bar */
      .topbar{position:sticky;top:0;z-index:1000;background:rgba(255,255,255,.85);backdrop-filter:saturate(180%) blur(8px); border-bottom:1px solid #e2e8f0}
      .topbar-inner{display:flex;align-items:center;justify-content:space-between;padding:12px 0}
      .brand{font-weight:800;letter-spacing:.2px;color:var(--brand);text-decoration:none}
      .nav{display:flex;gap:14px;align-items:center}
      .nav a{color:var(--muted);text-decoration:none;font-weight:600}
      .nav a:hover{color:var(--brand)}
      .btn{display:inline-block;padding:12px 22px;border-radius:10px;font-weight:800;text-decoration:none;box-shadow:var(--shadow);transition:transform .2s ease,filter .2s ease}
      .btn:hover{transform:translateY(-1px);filter:brightness(.96)}
      .btn-cta{background:var(--cta); color:#fff}
      .btn-accent{background:var(--accent); color:#fff}
      .btn-dark{background:var(--brand); color:#fff}
      .btn-muted{background:#6c757d;color:#fff}
      /* Hero */
      .hero{padding:44px 0 12px}
      .hero-box{background:linear-gradient(180deg,#f1f5f9,transparent);border:1px solid #e2e8f0;border-radius:var(--radius);padding:36px;box-shadow:var(--shadow);text-align:center}
      .hero h1{font-size:32px;line-height:1.1;margin:0 0 10px}
      .hero p{color:var(--muted);margin:0 0 16px}
      .cta-row{display:flex;gap:12px;flex-wrap:wrap;justify-content:center;margin-top:8px}
      /* Sections */
      .section{padding:10px 0}
      .grid-3{display:grid;grid-template-columns:repeat(3,minmax(0,1fr));gap:16px}
      .card{background:var(--card);border:1px solid #e2e8f0;border-radius:var(--radius);padding:18px;box-shadow:var(--shadow)}
      .card h3{margin:0 0 6px;font-size:18px}
      .card p{margin:0;color:var(--muted)}
      /* Products */
      .products{padding-top:6px}
      .product-grid{display:grid;grid-template-columns:repeat(3,minmax(0,1fr));gap:16px}
      .product{background:#fff;border:1px solid #e2e8f0;border-radius:var(--radius);overflow:hidden;box-shadow:var(--shadow);display:flex;flex-direction:column}
      .product .body{padding:16px;display:flex;flex-direction:column;gap:8px}
      .product h4{margin:0;font-size:16px}
      .product .actions{margin-top:auto}
      .footer-cta{padding:18px 0;text-align:center}
      .backtotop{position:fixed;right:18px;bottom:18px;z-index:1000}
      @media (max-width:820px){
        .grid-3,.product-grid{grid-template-columns:1fr}
        .hero h1{font-size:26px}
      }
    </style>

.. raw:: html

    <!-- Sticky Top Navigation -->
    <div class="topbar">
      <div class="container topbar-inner">
        <a class="brand" href="#top">Jamaica Blue Mountain Coffee</a>
        <nav class="nav">
          <a href="#what-is">About</a>
          <a href="#brew">Brewing</a>
          <a href="#top-products">Products</a>
          <a class="btn btn-cta" href="https://mamrebluecoffee.com/collections/mamre-blue-coffee" target="_blank" rel="noopener">Explore Products</a>
        </nav>
      </div>
    </div>

.. _top:

.. raw:: html

    <!-- Hero -->
    <section class="hero">
      <div class="container">
        <div class="hero-box">
          <h1>How to Enjoy Jamaica Blue Mountain Coffee Easily</h1>
          <p>Discover the rich flavor, brewing tips, and top products — without the fuss.</p>
          <div class="cta-row">
            <a class="btn btn-accent" href="https://mamrebluecoffee.com/pages/about-jamaica-blue-mountain-coffee" target="_blank" rel="noopener">Learn About Jamaica Blue Mountain Coffee</a>
            <a class="btn btn-dark" href="#top-products">Browse Top Picks</a>
          </div>
        </div>
      </div>
    </section>

Discover the Rich Flavor, Brewing Tips, and Top Products
=======================================================

When it comes to the world’s most premium and luxurious coffees, **Jamaica Blue Mountain Coffee** stands out. Grown in the cool, misty peaks and rich volcanic soil of Jamaica’s Blue Mountains, this coffee is celebrated for its smooth flavor, balanced taste, and rich aroma. That’s why coffee lovers around the globe treasure it.

.. _what-is:

What Is Jamaica Blue Mountain Coffee?
-------------------------------------

Jamaica Blue Mountain Coffee is a rare and highly prized coffee grown exclusively in Jamaica’s Blue Mountain region, at elevations between 3,000 and 5,500 feet. The cool climate, misty conditions, and fertile volcanic soil allow the beans to mature slowly, developing a unique flavor that is smooth, mild, and free from bitterness. Protected by strict regulations, only coffee grown in this area can officially be called **Blue Mountain Coffee**, making it one of the world’s most authentic and luxurious coffees.

Why Choose Jamaica Blue Mountain Coffee?
----------------------------------------

- Smooth, mild taste with low acidity  
- Rich, aromatic flavor  
- Hand-picked and carefully processed  
- Rare and exclusive, offering a naturally balanced, never-bitter cup  

Taste Profile (At a Glance)
---------------------------

.. raw:: html

    <section class="section">
      <div class="container grid-3">
        <div class="card">
          <h3>Balanced & Smooth</h3>
          <p>Velvety body with a clean, never-bitter finish.</p>
        </div>
        <div class="card">
          <h3>Floral & Sweet Notes</h3>
          <p>Bright acidity with delicate sweetness.</p>
        </div>
        <div class="card">
          <h3>Versatile Brewing</h3>
          <p>Excellent in pour-over, French press, or drip.</p>
        </div>
      </div>
    </section>

.. _brew:

How to Brew Jamaica Blue Mountain Coffee
----------------------------------------

1. **Use Fresh Beans** – Always grind beans just before brewing.  
2. **Choose the Right Grind Size** – Medium for pour-over, coarse for French press.  
3. **Use Clean, Filtered Water** – Ideal temperature: 90–95°C (200°F).  
4. **Brewing Methods** – Pour-over, French press, or drip coffee.  
5. **Keep It Simple** – Avoid too much sugar or cream.  
6. **Enjoy Fresh** – Serve immediately for best aroma and flavor.  

.. _top-products:

Top Jamaica Blue Mountain Coffee Products
-----------------------------------------

Discover the finest selection of authentic Jamaica Blue Mountain Coffee, known for its smooth flavor and rich aroma. Whether you’re a seasoned coffee enthusiast or new to this premium brew, our curated collection offers something for everyone.

.. raw:: html

    <section class="products">
      <div class="container">
        <div class="product-grid">

          <article class="product">
            <div class="body">
              <h4>Mamre Blue – 100% Jamaica Blue Mountain Coffee Pods (Original) – 12 Count</h4>
              <p class="muted">Convenient pods, classic smooth cup.</p>
              <div class="actions">
                <a class="btn btn-cta" href="https://mamrebluecoffee.com/collections/mamre-blue-coffee" target="_blank" rel="noopener">View Product</a>
              </div>
            </div>
          </article>

          <article class="product">
            <div class="body">
              <h4>Mamre Blue – 100% Jamaica Blue Mountain Coffee Pods (Dark Roast) – 12 Count</h4>
              <p class="muted">Bolder profile with a silky finish.</p>
              <div class="actions">
                <a class="btn btn-cta" href="https://mamrebluecoffee.com/collections/mamre-blue-coffee" target="_blank" rel="noopener">View Product</a>
              </div>
            </div>
          </article>

          <article class="product">
            <div class="body">
              <h4>Mamre Blue – 100% Jamaica Blue Mountain Coffee Roasted &amp; Ground – 16oz</h4>
              <p class="muted">Ready to brew — smooth and aromatic.</p>
              <div class="actions">
                <a class="btn btn-cta" href="https://mamrebluecoffee.com/collections/mamre-blue-coffee" target="_blank" rel="noopener">View Product</a>
              </div>
            </div>
          </article>

          <article class="product">
            <div class="body">
              <h4>Mamre Blue – 100% Jamaica Blue Mountain Coffee Whole Beans – 16oz</h4>
              <p class="muted">Grind fresh for peak flavor.</p>
              <div class="actions">
                <a class="btn btn-cta" href="https://mamrebluecoffee.com/collections/mamre-blue-coffee" target="_blank" rel="noopener">View Product</a>
              </div>
            </div>
          </article>

          <article class="product">
            <div class="body">
              <h4>Mamre Blue – 100% Jamaica Blue Mountain Coffee Pods (24 Count)</h4>
              <p class="muted">Stock up for effortless mornings.</p>
              <div class="actions">
                <a class="btn btn-cta" href="https://mamrebluecoffee.com/collections/mamre-blue-coffee" target="_blank" rel="noopener">View Product</a>
              </div>
            </div>
          </article>

          <article class="product">
            <div class="body">
              <h4>Mamre Blue – 100% Jamaica Blue Mountain Coffee Roasted &amp; Ground – 8oz</h4>
              <p class="muted">Perfect size for gifting or trying.</p>
              <div class="actions">
                <a class="btn btn-cta" href="https://mamrebluecoffee.com/collections/mamre-blue-coffee" target="_blank" rel="noopener">View Product</a>
              </div>
            </div>
          </article>

          <article class="product">
            <div class="body">
              <h4>Mamre Blue – 14oz Double Walled Vacuum Insulated Stainless Steel Cup</h4>
              <p class="muted">Keeps your brew hot or cold longer.</p>
              <div class="actions">
                <a class="btn btn-cta" href="https://mamrebluecoffee.com/collections/mamre-blue-coffee" target="_blank" rel="noopener">View Product</a>
              </div>
            </div>
          </article>

          <article class="product">
            <div class="body">
              <h4>Mamre Blue – Portable Electric Grinder &amp; Brewer – All In One</h4>
              <p class="muted">Freshly ground and brewed anywhere.</p>
              <div class="actions">
                <a class="btn btn-cta" href="https://mamrebluecoffee.com/collections/mamre-blue-coffee" target="_blank" rel="noopener">View Product</a>
              </div>
            </div>
          </article>

          <article class="product">
            <div class="body">
              <h4>Mamre Blue – Portable Ground Coffee Brewer</h4>
              <p class="muted">Compact brewer for easy travel.</p>
              <div class="actions">
                <a class="btn btn-cta" href="https://mamrebluecoffee.com/collections/mamre-blue-coffee" target="_blank" rel="noopener">View Product</a>
              </div>
            </div>
          </article>

        </div>

        <div class="footer-cta">
          <a class="btn btn-accent" href="https://mamrebluecoffee.com/collections/mamre-blue-coffee" target="_blank" rel="noopener">🔗 View All Products</a>
          <a class="btn btn-dark" href="https://mamrebluecoffee.com/pages/brewing-guide" target="_blank" rel="noopener">🔗 Coffee Brewing Tips</a>
        </div>
      </div>
    </section>

Final Thoughts
--------------

**Jamaica Blue Mountain Coffee** is more than just a drink—it’s an experience. Its smooth, rich flavor and unique aroma make every cup special. Whether you’re brewing at home, enjoying it with friends, or giving it as a gift, this coffee offers a taste of luxury that’s hard to match.

The secret to the perfect cup? **Fresh beans, the right brewing method, and simple preparation.** Treat yourself to authentic Jamaica Blue Mountain Coffee, and savor every sip!

.. raw:: html

    <div class="backtotop">
      <a class="btn btn-muted" href="#top">↑ Back to Top</a>
    </div>


