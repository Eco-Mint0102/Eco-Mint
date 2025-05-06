<!DOCTYPE html>
 <html lang="en">
 <head>
   <meta charset="UTF-8" />
   <meta name="viewport" content="width=device-width, initial-scale=1.0" />
   <title>Eco-Mint | Sustainable Products</title>
   <style>
     body {
       margin: 0;
       font-family: 'Helvetica Neue', sans-serif;
       background-color: #f6fdf7;
       color: #2d3a2f;
     }
     header {
       background-color: #d2f5d2;
       padding: 1rem 2rem;
       display: flex;
       justify-content: space-between;
       align-items: center;
     }
     .logo {
       font-size: 1.8rem;
       font-weight: bold;
       color: #2e7d32;
     }
     nav a {
       margin: 0 1rem;
       text-decoration: none;
       color: #2d3a2f;
       font-weight: 500;
     }
     .hero {
       background: url('eco-mint-homepage.png') center/cover no-repeat;
       height: 80vh;
       display: flex;
       justify-content: center;
       align-items: center;
       text-align: center;
       color: #ffffff;
     }
     .hero h1 {
       font-size: 3rem;
       background-color: rgba(0, 0, 0, 0.5);
       padding: 1rem;
       border-radius: 10px;
     }
     section.products {
       padding: 3rem 2rem;
       background-color: #ffffff;
     }
     .products h2 {
       text-align: center;
       color: #2e7d32;
     }
     .product-grid {
       display: grid;
       grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
       gap: 2rem;
       margin-top: 2rem;
     }
     .product {
       background-color: #f1fdf1;
       padding: 1rem;
       border-radius: 10px;
       text-align: center;
       box-shadow: 0 2px 5px rgba(0,0,0,0.1);
     }
     .product img {
       width: 100%;
       height: auto;
       border-radius: 10px;
     }
     .product h3 {
       margin-top: 1rem;
       color: #2d3a2f;
     }
     .product p {
       font-size: 0.9rem;
       color: #5e6e58;
     }
     footer {
       background-color: #d2f5d2;
       text-align: center;
       padding: 1rem;
       font-size: 0.9rem;
       color: #2d3a2f;
     }
   </style>
 </head>
 <body>
   <header>
     <div class="logo">Eco-Mint</div>
     <nav>
       <a href="#">Home</a>
       <a href="#products">Products</a>
       <a href="#contact">Contact</a>
     </nav>
   </header>
 
   <div class="hero">
     <h1>Live Green. Buy Clean. Eco-Mint.</h1>
   </div>
 
   <section class="products" id="products">
     <h2>Our Eco-Friendly Products</h2>
     <div class="product-grid">
       <div class="product">
         <img src="https://via.placeholder.com/300x200" alt="Reusable Bottle">
         <h3>Reusable Bottle</h3>
         <p>Stay hydrated sustainably with our BPA-free reusable bottle.</p>
       </div>
       <div class="product">
         <img src="https://via.placeholder.com/300x200" alt="Bamboo Plate Set">
         <h3>Bamboo Plate Set</h3>
         <p>Eco-friendly bamboo tableware for every occasion.</p>
       </div>
       <div class="product">
         <img src="https://via.placeholder.com/300x200" alt="Natural Soap Bar">
         <h3>Natural Soap Bar</h3>
         <p>Clean your skin and the planet with our handmade soap bars.</p>
       </div>
     </div>
   </section>
 
   <footer>
     &copy; 2025 Eco-Mint. All rights reserved.
   </footer>
 </body>
 </html>
