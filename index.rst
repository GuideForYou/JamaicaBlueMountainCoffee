.. raw:: html

    <style>
      :root{
        --brand:#173a67; --brand-2:#2e4e76; --accent:#28a745; --cta:#007bff;
        --text:#0f172a; --muted:#475569; --bg:#ffffff; --card:#f8fafc;
        --radius:14px; --shadow:0 6px 20px rgba(2,12,27,.08);
        --card-min-h:420px; /* unify product card heights */
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
      /* don't let nav hover affect buttons */
      .nav a:not(.btn):hover{color:var(--brand)}

      /* Buttons */
      .btn{display:inline-block;padding:12px 22px;border-radius:10px;font-weight:800;text-decoration:none;box-shadow:var(--shadow);transition:transform .2s ease,filter .2s ease}
      .btn:hover{transform:translateY(-1px);filter:brightness(.96)}
      .btn-cta{background:var(--cta)}
      .btn-accent{background:var(--accent)}
      .btn-dark{background:var(--brand)}
      .btn-muted{background:#6c757d}
      /* keep button TEXT white in every state */
      .btn, .btn:link, .btn:visited, .btn:hover, .btn:focus, .btn:focus-visible, .btn:active{
        color:#fff !important; text-decoration:none !important;
      }

      /* Hero (no hero image since you want only 3 product images) */
      .hero{padding:44px 0 6px}
      .hero-box{background:linear-gradient(180deg,#f1f5f9,transparent);border:1px solid #e2e8f0;border-radius:var(--radius);padding:24px;box-shadow:var(--shadow);text-align:center}
      .hero h1{font-size:32px;line-height:1.1;margin:0 0 8px}
      .hero p{color:var(--muted);margin:0 0 12px}
      .cta-row{display:flex;gap:12px;flex-wrap:wrap;justify-content:center;margin-top:8px}

      /* Sections */
      .section{padding:10px 0}
      .grid-3{display:grid;grid-template-columns:repeat(3,minmax(0,1fr));gap:16px}
      .card{background:var(--card);border:1px solid #e2e8f0;border-radius:var(--radius);padding:18px;box-shadow:var(--shadow)}
      .card h3{margin:0 0 6px;font-size:18px}
      .card p{margin:0;color:var(--muted)}

      /* Products */
      .products{padding-top:6px}
      .product-grid{
        display:grid;
        grid-template-columns:repeat(3, minmax(0,1fr)); /* exactly 3 cards */
        gap:16px;
        align-items:stretch;
      }
      .product{
        background:#fff;border:1px solid #e2e8f0;border-radius:var(--radius);
        overflow:hidden;box-shadow:var(--shadow);
        display:flex;flex-direction:column;height:100%;min-height:var(--card-min-h);
      }
      .media{aspect-ratio:1/1;background:#e2e8f0} /* square to match 1024x1024 */
      .media img{width:100%;height:100%;object-fit:cover;display:block}
      .product .body{padding:14px;display:flex;flex-direction:column;gap:8px;flex:1}
      .product h4{
        margin:0;font-size:16px;line-height:1.25;
        display:-webkit-box;-webkit-box-orient:vertical;overflow:hidden;
        -webkit-line-clamp:2;line-clamp:2;min-height:calc(2 * 1.25em);
      }
      .product p.muted{
        color:#475569;line-height:1.4;
        display:-webkit-box;-webkit-box-orient:vertical;overflow:hidden;
        -webkit-line-clamp:2;line-clamp:2;min-height:calc(2 * 1.4em);
      }
      .product .actions{margin-top:auto}
      .footer-cta{padding:18px 0;text-align:center}
      .backtotop{position:fixed;right:18px;bottom:18px;z-index:1000}

      @media (max-width:820px){
        .grid-3{grid-template-columns:1fr}
        .product-grid{grid-template-columns:1fr}
        .hero h1{font-size:26px}
        :root{ --card-min-h:360px; }
      }
    </style>

.. raw:: html

    <!-- Sticky Top Navigation -->
    <div class="topbar">
      <div class="container topbar-inner">
        <a class="brand" href="#top">Jamaica Blue Mountain Coffee</a>
        <nav class="nav">
          <a href="https://mamrebluecoffee.com">About</a>
          <a href="https://mamrebluecoffee.com">Brewing</a>
          <a href="https://mamrebluecoffee.com/collections/mamre-blue-coffee">Products</a>
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
            <a class="btn btn-accent" href="https://mamrebluecoffee.com/collections/mamre-blue-coffee" target="_blank" rel="noopener">Learn About Jamaica Blue Mountain Coffee</a>
            <a class="btn btn-dark" href="https://mamrebluecoffee.com/collections/mamre-blue-coffee">Browse Top Picks</a>
          </div>
        </div>
      </div>
    </section>

Discover the Rich Flavor, Brewing Tips, and Top Products
=======================================================

When it comes to the world’s most premium and luxurious coffees, **Jamaica Blue Mountain Coffee** stands out. Grown in the cool, misty peaks and rich volcanic soil of Jamaica’s Blue Mountains, this coffee is celebrated for its smooth flavor, balanced taste, and rich aroma.

.. _what-is:

What Is Jamaica Blue Mountain Coffee?
-------------------------------------

Jamaica Blue Mountain Coffee is a rare coffee grown exclusively in Jamaica’s Blue Mountain region (approx. 3,000–5,500 ft). The cool climate and volcanic soil let the beans mature slowly for a smooth, mild, never-bitter cup.

Why Choose Jamaica Blue Mountain Coffee?
----------------------------------------

- Smooth, mild taste with low acidity  
- Rich, aromatic flavor  
- Hand-picked and carefully processed  
- Rare and exclusive, naturally balanced cup  

.. _brew:

How to Brew Jamaica Blue Mountain Coffee
----------------------------------------

1. **Use Fresh Beans** – Grind just before brewing.  
2. **Right Grind** – Medium for pour-over, coarse for French press.  
3. **Water** – Filtered, 90–95°C (200°F).  
4. **Methods** – Pour-over, French press, or drip.  
5. **Keep It Simple** – Minimal sugar/cream.  
6. **Serve Fresh** – Enjoy immediately.  

.. _top-products:

Top Jamaica Blue Mountain Coffee Products
-----------------------------------------

.. raw:: html

    <section class="products">
      <div class="container">
        <div class="product-grid">

          <!-- Card 1 -->
          <article class="product">
            <div class="media">
              <img
                src="https://mamrebluecoffee.com/cdn/shop/files/Orange-004_1024x1024@2x.jpg?v=1739983249"
                alt="Original Pods - Jamaica Blue Mountain Coffee">
            </div>
            <div class="body">
              <h4>Original Pods (12 Ct)</h4>
              <p class="muted">Classic smooth cup in convenient single-serve pods.</p>
              <div class="actions">
                <a class="btn btn-cta" href="https://mamrebluecoffee.com/collections/mamre-blue-coffee" target="_blank" rel="noopener">View in Collection</a>
              </div>
            </div>
          </article>

          <!-- Card 2 -->
          <article class="product">
            <div class="media">
              <img
                src="https://mamrebluecoffee.com/cdn/shop/files/Dark-004_1024x1024@2x.jpg?v=1695607241"
                alt="Dark Roast Pods - Jamaica Blue Mountain Coffee">
            </div>
            <div class="body">
              <h4>Dark Roast Pods (12 Ct)</h4>
              <p class="muted">Deeper roast profile with a silky finish.</p>
              <div class="actions">
                <a class="btn btn-cta" href="https://mamrebluecoffee.com/collections/mamre-blue-coffee" target="_blank" rel="noopener">View in Collection</a>
              </div>
            </div>
          </article>

          <!-- Card 3 -->
          <article class="product">
            <div class="media">
              <img
                src="https://mamrebluecoffee.com/cdn/shop/products/Ground1_1024x1024@2x.jpg?v=1637211747"
                alt="Roasted & Ground 16oz - Jamaica Blue Mountain Coffee">
            </div>
            <div class="body">
              <h4>Roasted &amp; Ground – 16oz</h4>
              <p class="muted">Ready-to-brew pack for everyday luxury.</p>
              <div class="actions">
                <a class="btn btn-cta" href="https://mamrebluecoffee.com/collections/mamre-blue-coffee" target="_blank" rel="noopener">View in Collection</a>
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

**Jamaica Blue Mountain Coffee** is more than just a drink—it’s an experience. Its smooth, rich flavor and unique aroma make every cup special. Treat yourself to authentic Jamaica Blue Mountain Coffee, and savor every sip!

.. raw:: html

    <div class="backtotop">
      <a class="btn btn-muted" href="#top">↑ Back to Top</a>
    </div>



