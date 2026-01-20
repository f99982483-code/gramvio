<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>GRAMVIO - Instagram Followers Growth</title>
  <style>
    body { margin:0; font-family: Arial, sans-serif; background:#f5f5f5; color:#222; }
    header { background:#111; color:#fff; padding:20px; display:flex; align-items:center; justify-content:space-between; }
    header img { height:50px; }
    nav a { color:#fff; margin-left:20px; text-decoration:none; font-weight:bold; }
    section { padding:40px 20px; max-width:900px; margin:auto; }
    .card { background:#fff; padding:20px; border-radius:10px; box-shadow:0 4px 10px rgba(0,0,0,0.1); margin-bottom:20px; }
    input, select { width:100%; padding:10px; margin:10px 0; border-radius:6px; border:1px solid #ccc; }
    button { background:#111; color:#fff; padding:10px 20px; border:none; border-radius:6px; cursor:pointer; }
    button:hover { background:#333; }
    footer { background:#111; color:#aaa; text-align:center; padding:15px; }
  </style>
</head>
<body>

<header>
  <img src="logop.png" alt="GRAMVIO Logo">
  <nav>
    <a href="#home">Home</a>
    <a href="#pricing">Pricing</a>
    <a href="#payment">Payment</a>
  </nav>
</header>

<section id="home">
  <div class="card">
    <h2>Grow Your Instagram</h2>
    <p>Enter your details below to get started:</p>
    <form id="orderForm">
      <label>Name</label>
      <input type="text" placeholder="Enter your name" required>

      <label>Instagram Username</label>
      <input type="text" placeholder="@yourusername" required>

      <label>Mobile Number</label>
      <input type="tel" placeholder="Enter mobile number" required>

      <label>Instagram Followers Range</label>
      <select required>
        <option value="">Select followers range</option>
        <option value="1K-5K">1K - 5K</option>
        <option value="5K-10K">5K - 10K</option>
        <option value="10K-25K">10K - 25K</option>
        <option value="25K-50K">25K - 50K</option>
        <option value="50K-100K">50K - 100K</option>
        <option value="100K+">100K+</option>
      </select>

      <button type="submit">Order Now on WhatsApp</button>
    </form>
  </div>
</section>

<section id="pricing">
  <div class="card">
    <h3>Pricing</h3>
    <p><strong>1K Instagram Followers – ₹25</strong></p>
    <p>Fast delivery • No password required • Safe & secure</p>
  </div>
</section>

<section id="payment">
  <div class="card">
    <h2>Payment Methods</h2>
    <p>Complete your payment using any method below and send screenshot on WhatsApp:</p>
    <ul>
      <li><strong>UPI:</strong> yourupi@bank</li>
      <li><strong>PhonePe:</strong> +91 XXXXX XXXXX</li>
      <li><strong>Google Pay:</strong> +91 XXXXX XXXXX</li>
    </ul>
    <p><em>After payment, delivery starts within minutes.</em></p>
  </div>
</section>

<footer>
  <p>© 2026 GRAMVIO. All rights reserved.</p>
</footer>

<script>
  // WhatsApp order button functionality using Varma's number
  document.getElementById('orderForm').addEventListener('submit', function(e) {
    e.preventDefault();
    const name = this[0].value;
    const insta = this[1].value;
    const mobile = this[2].value;
    const followers = this[3].value;
    const message = `Name: ${name}%0AInstagram: ${insta}%0AMobile: ${mobile}%0AFollowers: ${followers}`;
    window.open(`https://wa.me/919703760912?text=${message}`, '_blank');
  });
</script>

</body>
</html>

