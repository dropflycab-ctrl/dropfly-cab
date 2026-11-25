
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>DropFly CAB | Bengaluru Airport Cabs</title>
<style>
*{box-sizing:border-box;margin:0;padding:0}
body{font-family:Arial,sans-serif;background:#f7f8fc;color:#172033}
header{background:#101d35;color:white;padding:18px 6%;display:flex;justify-content:space-between;align-items:center}
.logo{font-size:25px;font-weight:800;color:#ffbd38}
.logo span{color:white}
header a{color:white;text-decoration:none;font-size:14px}
.hero{padding:75px 7%;background:linear-gradient(120deg,#101d35,#234c76);color:white}
.hero small{color:#ffbd38;font-weight:bold;letter-spacing:2px}
.hero h1{font-size:clamp(34px,7vw,55px);margin:18px 0;line-height:1.1}
.hero p{font-size:17px;line-height:1.7;color:#e1e8f2;max-width:520px}
.btn{display:inline-block;background:#ffbd38;color:#172033;padding:15px 25px;border-radius:9px;text-decoration:none;font-weight:bold;margin-top:25px}
section{padding:55px 7%}
.heading{text-align:center;margin-bottom:30px}
.heading h2{font-size:30px;margin-bottom:10px}
.heading p{color:#667085}
.cards{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:18px}
.card{background:white;padding:25px;border-radius:15px;box-shadow:0 5px 22px #14213d12}
.card .emoji{font-size:40px}
.card h3{margin:15px 0 10px}
.card p{color:#667085;line-height:1.6;font-size:14px}
.booking{background:#fff;border-radius:16px;padding:25px;max-width:650px;margin:auto;box-shadow:0 5px 25px #14213d12}
label{display:block;font-weight:bold;margin:15px 0 7px}
input,select{width:100%;padding:14px;border:1px solid #d5dbe5;border-radius:8px;font-size:15px;background:white}
button{width:100%;border:0;background:#ffbd38;padding:15px;border-radius:8px;font-weight:bold;font-size:16px;margin-top:20px}
footer{text-align:center;background:#101d35;color:#dce5f1;padding:30px 15px;line-height:2}
</style>
</head>
<body>
<header>
 <div class="logo">DROPFLY <span>CAB</span></div>
 <a href="#booking">BOOK A RIDE</a>
</header>

<div class="hero">
 <small>WELCOME TO DROPFLY CAB</small>
 <h1>Your Journey.<br>Our Responsibility.</h1>
 <p>Comfortable and convenient airport and city cab travel in Bengaluru. Choose a shared ride or book your personal cab.</p>
 <a class="btn" href="#booking">Book Your Ride →</a>
</div>

<section>
 <div class="heading">
  <h2>Choose Your Ride</h2>
  <p>Travel your way with DropFly CAB</p>
 </div>
 <div class="cards">
  <div class="card">
   <div class="emoji">🚕</div>
   <h3>Shared Cab</h3>
   <p>Affordable shared airport rides. Maximum 3 passengers.</p>
  </div>
  <div class="card">
   <div class="emoji">🚘</div>
   <h3>Personal Sedan</h3>
   <p>Private ride for up to 4 passengers with luggage.</p>
  </div>
  <div class="card">
   <div class="emoji">🚙</div>
   <h3>Personal SUV</h3>
   <p>Spacious private ride for up to 5 passengers.</p>
  </div>
 </div>
</section>

<section id="booking" style="background:#edf2f8">
 <div class="heading">
  <h2>Book Your Ride</h2>
  <p>Plan your Bengaluru airport journey</p>
 </div>
 <div class="booking">
  <label>Journey Type</label>
  <select>
   <option>City to Airport</option>
   <option>Airport to City</option>
  </select>
  <label>Cab Type</label>
  <select>
   <option>Shared Cab</option>
   <option>Personal Sedan</option>
   <option>Personal SUV</option>
  </select>
  <label>Pickup Location</label>
  <input placeholder="Enter pickup location">
  <label>Drop Location</label>
  <input placeholder="Enter drop location">
  <label>Travel Date</label>
  <input type="date">
  <label>Mobile Number</label>
  <input type="tel" placeholder="Enter mobile number">
  <button type="button" onclick="alert('Online booking is coming soon. Please contact DropFly CAB for now.')">Continue</button>
 </div>
</section>

<footer>
 <h2>DROPFLY CAB</h2>
 Bengaluru Airport & City Cab Service<br>
 © 2026 DropFly CAB. All rights reserved.
</footer>
</body>
</html>

