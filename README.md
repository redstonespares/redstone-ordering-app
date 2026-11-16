

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="theme-color" content="#c90019">
<title>Redstone Holdings | Motorcycle Spares</title>
<meta name="description" content="Shop CG150 motorcycle spare parts from Redstone Holdings. Collection and nationwide delivery in South Africa.">

<style>
:root {
  --red: #d00020;
  --dark: #111214;
  --black: #080808;
  --white: #fff;
  --grey: #f1f1f1;
  --muted: #777;
}
* { box-sizing: border-box; }
body {
  margin: 0;
  font-family: Arial, Helvetica, sans-serif;
  color: var(--dark);
  background: #f5f5f5;
}
a { text-decoration: none; color: inherit; }
button, input, select, textarea { font: inherit; }
button { cursor: pointer; }

.topbar {
  background: var(--red);
  color: white;
  text-align: center;
  padding: 9px;
  font-size: 13px;
  font-weight: bold;
}
header {
  background: var(--black);
  color: white;
  padding: 17px 5%;
  display: flex;
  justify-content: space-between;
  align-items: center;
  gap: 15px;
}
.brand {
  display: flex;
  align-items: center;
  gap: 12px;
}
.logo {
  width: 55px;
  height: 55px;
  object-fit: contain;
}
.brand-mark {
  background: var(--red);
  font-weight: 900;
  font-size: 23px;
  padding: 13px;
  border-radius: 5px;
}
.brand h1 {
  font-size: 20px;
  margin: 0;
  font-weight: 900;
}
.brand small {
  display: block;
  color: #ccc;
  font-size: 10px;
  letter-spacing: 2px;
  margin-top: 5px;
}
nav {
  display: flex;
  gap: 20px;
  align-items: center;
  font-size: 14px;
  font-weight: bold;
}
nav a:hover { color: #ff344c; }
.cart-button {
  background: var(--red);
  border: 0;
  color: white;
  padding: 11px 16px;
  border-radius: 5px;
  font-weight: bold;
}

.hero {
  background:
    linear-gradient(90deg, rgba(0,0,0,.94), rgba(0,0,0,.48)),
    url("https://images.unsplash.com/photo-1558981806-ec527fa84c39?auto=format&fit=crop&w=1600&q=85");
  background-size: cover;
  background-position: center;
  color: white;
  padding: 75px 7%;
}
.hero h2 {
  font-size: clamp(34px, 6vw, 58px);
  max-width: 650px;
  margin: 0 0 15px;
  line-height: 1.05;
  font-weight: 900;
}
.hero h2 span { color: #ff263f; }
.hero p {
  color: #ddd;
  max-width: 520px;
  line-height: 1.7;
}
.primary-button {
  display: inline-block;
  background: var(--red);
  color: white;
  padding: 14px 22px;
  border-radius: 4px;
  border: none;
  font-weight: bold;
  margin-top: 15px;
}
.primary-button:hover { background: #a90018; }

.features {
  background: white;
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  text-align: center;
  padding: 24px 5%;
  gap: 15px;
}
.feature strong { display: block; margin-bottom: 6px; }
.feature small { color: var(--muted); }

.section {
  padding: 45px 5%;
  max-width: 1300px;
  margin: auto;
}
.section-title {
  font-size: 28px;
  font-weight: 900;
  margin: 0 0 8px;
}
.section-subtitle {
  color: var(--muted);
  margin-bottom: 25px;
}
.search-row {
  display: flex;
  gap: 10px;
  margin-bottom: 25px;
}
.search-row input, .search-row select {
  padding: 13px;
  border: 1px solid #ddd;
  border-radius: 5px;
  background: white;
  min-width: 0;
}
.search-row input { flex: 1; }

.products {
  display: grid;
  grid-template-columns: repeat(4, minmax(0, 1fr));
  gap: 18px;
}
.product {
  background: white;
  border-radius: 7px;
  overflow: hidden;
  border: 1px solid #e6e6e6;
  display: flex;
  flex-direction: column;
}
.product-picture {
  height: 155px;
  display: grid;
  place-items: center;
  background: #ededed;
  font-size: 65px;
}
.product-info {
  padding: 16px;
  display: flex;
  flex-direction: column;
  flex: 1;
}
.product-category {
  color: var(--red);
  text-transform: uppercase;
  font-size: 10px;
  font-weight: bold;
  letter-spacing: 1px;
}
.product h3 {
  font-size: 16px;
  margin: 8px 0;
}
.product-description {
  color: var(--muted);
  font-size: 12px;
  line-height: 1.5;
  flex: 1;
}
.price {
  font-size: 20px;
  font-weight: 900;
  margin: 12px 0;
}
.add-button {
  background: var(--dark);
  color: white;
  border: 0;
  padding: 12px;
  border-radius: 4px;
  font-weight: bold;
}
.add-button:hover { background: var(--red); }

.cart-section {
  background: white;
  border-radius: 8px;
  padding: 24px;
  margin-top: 45px;
}
.cart-item {
  display: flex;
  justify-content: space-between;
  gap: 12px;
  border-bottom: 1px solid #eee;
  padding: 13px 0;
  align-items: center;
}
.cart-item button {
  border: 0;
  background: #eee;
  padding: 6px 10px;
  border-radius: 4px;
}
.cart-total {
  font-size: 21px;
  font-weight: 900;
  text-align: right;
  padding: 20px 0;
}
.checkout-form {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 13px;
  margin-top: 20px;
}
.checkout-form input,
.checkout-form select,
.checkout-form textarea {
  width: 100%;
  padding: 13px;
  border: 1px solid #ddd;
  border-radius: 5px;
  background: white;
}
.checkout-form textarea { grid-column: 1 / -1; }
.checkout-actions {
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
}
.email-button {
  background: #333;
  color: white;
  border: none;
  padding: 14px 20px;
  border-radius: 4px;
  font-weight: bold;
}

.contact {
  background: #171717;
  color: white;
  padding: 45px 7%;
}
.contact h2 { font-size: 28px; }
.contact-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 20px;
}
.contact-item {
  background: #252525;
  padding: 20px;
  border-left: 4px solid var(--red);
  overflow-wrap: anywhere;
}
.contact-item small {
  display: block;
  color: #bbb;
  margin-bottom: 8px;
}
.contact a { color: white; }
.contact a:hover { color: #ff5267; }

footer {
  background: #050505;
  color: #aaa;
  padding: 20px;
  text-align: center;
  font-size: 12px;
}
.notice {
  font-size: 12px;
  color: #777;
  line-height: 1.6;
  margin-top: 12px;
}

@media(max-width: 850px) {
  .products { grid-template-columns: repeat(2, 1fr); }
  nav { gap: 10px; }
  .contact-grid { grid-template-columns: 1fr; }
}
@media(max-width: 550px) {
  header { flex-wrap: wrap; }
  nav { width: 100%; justify-content: space-between; }
  .brand h1 { font-size: 17px; }
  .hero { padding: 55px 6%; }
  .features { grid-template-columns: 1fr; }
  .products { gap: 10px; }
  .product-picture { height: 115px; font-size: 48px; }
  .product-info { padding: 11px; }
  .product h3 { font-size: 14px; }
  .search-row { flex-direction: column; }
  .checkout-form { grid-template-columns: 1fr; }
  .checkout-form textarea { grid-column: auto; }
  .section { padding: 35px 4%; }
}
</style>
</head>

<body>

<div class="topbar">
  MOTORCYCLE SPARES & REPAIRS | SOUTH AFRICA
</div>

<header>
  <div class="brand">
    <img class="logo" src="redstone-logo.png"
         alt="Redstone logo"
         onerror="this.style.display='none'">
    <div class="brand-mark">RH</div>
    <div>
      <h1>REDSTONE HOLDINGS</h1>
      <small>MOTORCYCLE SPARES & REPAIRS</small>
    </div>
  </div>

  <nav>
    <a href="#home">HOME</a>
    <a href="#products">SHOP</a>
    <a href="#contact">CONTACT</a>
    <button class="cart-button" onclick="goToCart()">
      CART (<span id="cart-count">0</span>)
    </button>
  </nav>
</header>

<section class="hero" id="home">
  <h2>QUALITY MOTORCYCLE <span>SPARE PARTS.</span></h2>
  <p>
    Your trusted destination for CG150 motorcycle spare parts.
    Quality parts, competitive prices and reliable service.
  </p>
  <a class="primary-button" href="#products">SHOP NOW</a>
</section>

<section class="features">
  <div class="feature">
    <strong>🏍️ CG150 SPECIALISTS</strong>
    <small>Motorcycle spare parts</small>
  </div>
  <div class="feature">
    <strong>🚚 NATIONWIDE DELIVERY</strong>
    <small>Courier delivery available</small>
  </div>
  <div class="feature">
    <strong>📦 COLLECTION AVAILABLE</strong>
    <small>Collect your order</small>
  </div>
</section>

<main class="section" id="products">
  <h2 class="section-title">SHOP MOTORCYCLE SPARES</h2>
  <p class="section-subtitle">
    Find the parts you need for your CG150 motorcycle.
  </p>

  <div class="search-row">
    <input id="search" type="search"
      placeholder="Search motorcycle parts..."
      oninput="renderProducts()">

    <select id="category" onchange="renderProducts()">
      <option value="all">All categories</option>
      <option value="Engine">Engine parts</option>
      <option value="Clutch">Clutch parts</option>
      <option value="Brakes">Brake parts</option>
      <option value="Electrical">Electrical parts</option>
      <option value="Service">Service parts</option>
      <option value="Drive">Drive parts</option>
    </select>
  </div>

  <div class="products" id="products-list"></div>

  <section class="cart-section" id="cart">
    <h2 class="section-title">YOUR SHOPPING CART</h2>
    <div id="cart-items">Your cart is empty.</div>
    <div class="cart-total" id="cart-total">Total: R0.00</div>

    <h3>DELIVERY & CUSTOMER DETAILS</h3>
    <div class="checkout-form">
      <input id="customer-name" placeholder="Full name *" required>
      <input id="customer-phone" type="tel" placeholder="Your phone number *" required>

      <select id="delivery">
        <option value="Collection">Collection</option>
        <option value="Nationwide courier delivery">Nationwide courier delivery</option>
      </select>

      <input id="customer-address"
        placeholder="Delivery address (if courier selected)">

      <textarea id="order-notes" rows="3"
        placeholder="Order notes or additional information"></textarea>
    </div>

    <div class="checkout-actions">
      <button class="primary-button" onclick="sendWhatsAppOrder()">
        ORDER VIA WHATSAPP
      </button>
      <button class="email-button" onclick="sendEmailOrder()">
        ORDER VIA EMAIL
      </button>
    </div>

    <p class="notice">
      Delivery charges will be confirmed before payment.
      EFT banking details will be provided when your order is confirmed.
      Prices are displayed in South African Rand (ZAR).
      Items marked "Price to be confirmed" need a price added before purchase.
    </p>
  </section>
</main>

<section class="contact" id="contact">
  <h2>CONTACT REDSTONE HOLDINGS</h2>
  <p>We are ready to assist with your motorcycle spare parts requirements.</p>

  <div class="contact-grid">
    <div class="contact-item">
      <small>WHATSAPP / PHONE</small>
      <strong><a href="https://wa.me/27823423940">082 342 3940</a></strong>
    </div>

    <div class="contact-item">
      <small>EMAIL ADDRESS</small>
      <strong>
        <a href="mailto:tshidisomolomo26@gmail.com">
          tshidisomolomo26@gmail.com
        </a>
      </strong>
    </div>

    <div class="contact-item">
      <small>DELIVERY</small>
      <strong>Collection & nationwide courier</strong>
    </div>
  </div>
</section>

<footer>
  © <span id="year"></span> REDSTONE HOLDINGS.
  ALL RIGHTS RESERVED.
  <br> MOTORCYCLE SPARES & REPAIRS | SOUTH AFRICA
</footer>

<script>
// ====================================
// REDSTONE HOLDINGS PRODUCT CATALOGUE
// Add your actual prices below.
// Use numbers, for example: price: 150
// ====================================

const products = [
  {
    id: 1,
    name: "CG150 Piston Kit",
    category: "Engine",
    description: "Piston, rings and related engine components.",
    price: null,
    icon: "⚙️"
  },
  {
    id: 2,
    name: "CG150 Clutch Plates",
    category: "Clutch",
    description: "Motorcycle clutch replacement components.",
    price: null,
    icon: "🔩"
  },
  {
    id: 3,
    name: "CG150 Brake Shoes",
    category: "Brakes",
    description: "Replacement brake shoes.",
    price: null,
    icon: "🛠️"
  },
  {
    id: 4,
    name: "CG150 Chain & Sprocket Kit",
    category: "Drive",
    description: "Drive chain and sprocket replacement kit.",
    price: null,
    icon: "⛓️"
  },
  {
    id: 5,
    name: "CG150 CDI Unit",
    category: "Electrical",
    description: "Electronic ignition replacement unit.",
    price: null,
    icon: "🔌"
  },
  {
    id: 6,
    name: "CG150 Stator Coil",
    category: "Electrical",
    description: "Motorcycle charging and electrical component.",
    price: null,
    icon: "⚡"
  },
  {
    id: 7,
    name: "CG150 Air Filter",
    category: "Service",
    description: "Replacement engine air filter.",
    price: null,
    icon: "🔧"
  },
  {
    id: 8,
    name: "CG150 Spark Plug",
    category: "Service",
    description: "Replacement motorcycle spark plug.",
    price: null,
    icon: "🔩"
  }
];

let cart = [];

function formatPrice(price) {
  return "R" + Number(price).toFixed(2);
}

function renderProducts() {
  const search = document.getElementById("search")
    .value.toLowerCase();

  const category = document.getElementById("category").value;

  const filtered = products.filter(product => {
    const matchesSearch =
      product.name.toLowerCase().includes(search) ||
      product.description.toLowerCase().includes(search);

    const matchesCategory =
      category === "all" || product.category === category;

    return matchesSearch && matchesCategory;
  });

  const container = document.getElementById("products-list");

  if (filtered.length === 0) {
    container.innerHTML = "<p>No matching products found.</p>";
    return;
  }

  container.innerHTML = filtered.map(product => `
    <article class="product">
      <div class="product-picture">${product.icon}</div>
      <div class="product-info">
        <span class="product-category">${product.category}</span>
        <h3>${product.name}</h3>
        <p class="product-description">${product.description}</p>
        <div class="price">
          ${product.price === null
            ? "Price to be confirmed"
            : formatPrice(product.price)}
        </div>
        <button class="add-button"
          onclick="addToCart(${product.id})">
          ADD TO CART
        </button>
      </div>
    </article>
  `).join("");
}

function addToCart(id) {
  const product = products.find(p => p.id === id);

  const existing = cart.find(item => item.id === id);

  if (existing) {
    existing.quantity++;
  } else {
    cart.push({...product, quantity: 1});
  }

  renderCart();
}

function changeQuantity(id, amount) {
  const item = cart.find(p => p.id === id);
  if (!item) return;

  item.quantity += amount;

  if (item.quantity <= 0) {
    cart = cart.filter(p => p.id !== id);
  }

  renderCart();
}

function renderCart() {
  const container = document.getElementById("cart-items");

  document.getElementById("cart-count").textContent =
    cart.reduce((sum, item) => sum + item.quantity, 0);

  if (cart.length === 0) {
    container.innerHTML = "Your cart is empty.";
    document.getElementById("cart-total").textContent =
      "Total: R0.00";
    return;
  }

  container.innerHTML = cart.map(item => `
    <div class="cart-item">
      <div>
        <strong>${item.name}</strong><br>
        <small>
          ${item.price === null
            ? "Price to be confirmed"
            : formatPrice(item.price)}
        </small>
      </div>
      <div>
        <button onclick="changeQuantity(${item.id},-1)">−</button>
        <strong>${item.quantity}</strong>
        <button onclick="changeQuantity(${item.id},1)">+</button>
      </div>
    </div>
  `).join("");

  const total = cart.reduce((sum, item) =>
    sum + (Number(item.price) || 0) * item.quantity, 0);

  const hasMissingPrice = cart.some(item => item.price === null);

  document.getElementById("cart-total").textContent =
    hasMissingPrice
      ? "Total: Price to be confirmed"
      : "Total: " + formatPrice(total);
}

function goToCart() {
  document.getElementById("cart").scrollIntoView({
    behavior: "smooth"
  });
}

function getOrderMessage() {
  if (cart.length === 0) {
    alert("Please add products to your cart first.");
    return null;
  }

  const name = document.getElementById("customer-name").value.trim();
  const phone = document.getElementById("customer-phone").value.trim();

  if (!name || !phone) {
    alert("Please enter your name and phone number.");
    return null;
  }

  const delivery = document.getElementById("delivery").value;
  const address = document.getElementById("customer-address").value.trim();
  const notes = document.getElementById("order-notes").value.trim();

  if (delivery === "Nationwide courier delivery" && !address) {
    alert("Please enter your delivery address.");
    return null;
  }

  const lines = cart.map(item => {
    const price = item.price === null
      ? "Price to be confirmed"
      : formatPrice(item.price);

    return `${item.name} x ${item.quantity} - ${price}`;
  });

  const hasMissingPrice = cart.some(item => item.price === null);

  const total = cart.reduce((sum, item) =>
    sum + (Number(item.price) || 0) * item.quantity, 0);

  return `
REDSTONE HOLDINGS
MOTORCYCLE SPARES & REPAIRS

NEW ORDER

Customer: ${name}
Phone: ${phone}

PRODUCTS:
${lines.join("\n")}

Total: ${hasMissingPrice
  ? "To be confirmed"
  : formatPrice(total)}

Delivery: ${delivery}
Address: ${address || "Collection"}

Notes: ${notes || "None"}

Please confirm availability, final pricing and payment details.

Thank you.
  `.trim();
}

function sendWhatsAppOrder() {
  const message = getOrderMessage();
  if (!message) return;

  const url = "https://wa.me/27823423940?text=" +
    encodeURIComponent(message);

  window.open(url, "_blank");
}

function sendEmailOrder() {
  const message = getOrderMessage();
  if (!message) return;

  const url = "mailto:tshidisomolomo26@gmail.com" +
    "?subject=" + encodeURIComponent("New Redstone Holdings Order") +
    "&body=" + encodeURIComponent(message);

  window.location.href = url;
}

document.getElementById("year").textContent =
  new Date().getFullYear();

renderProducts();
renderCart();
</script>

</body>
</html>
