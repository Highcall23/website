<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>High Call Logistics</title>
  <link rel="stylesheet" href="style.css">
  <script src="thankyou.js" defer></script>
</head>
<body>

  <nav>
    <h1>High Call Logistics</h1>
    <ul>
      <li><a href="#about">About</a></li>
      <li><a href="#services">Services</a></li>
      <li><a href="#maintenance">Maintenance</a></li>
      <li><a href="#application">Credit App</a></li>
      <li><a href="#quote">Quote</a></li>
    </ul>
  </nav>

  <header>
    <h2>Specializing in Semi-Trailer Rentals and Leasing</h2>
  </header>

  <section id="about">
    <h2>About Us</h2>
    <p>High Call Logistics provides high-quality semi-trailer rentals and flexible leasing options tailored to your business needs. Our fleet includes dry vans and reefers maintained to the highest standards.</p>
  </section>

  <section id="services">
    <h2>Services</h2>
    <ul>
      <li>Short-Term Rentals</li>
      <li>Long-Term Leases</li>
      <li>Full Maintenance Plans</li>
      <li>Trailer Sales</li>
    </ul>
  </section>

  <section id="maintenance">
    <h2>Maintenance</h2>
    <button onclick="showTab('reefers')">Reefers</button>
    <button onclick="showTab('dryvans')">Dry Vans</button>
    <div id="reefers" class="tab-content">
      <p>Reefer maintenance includes refrigeration inspections, temperature calibration, and 24/7 emergency service.</p>
    </div>
    <div id="dryvans" class="tab-content" style="display:none">
      <p>Dry van maintenance features brake checks, tire inspections, structural assessments, and preventive services.</p>
    </div>
  </section>

  <section id="application">
    <h2>Credit Application</h2>
    <form onsubmit="return showThankYou()">
      <input type="text" name="businessName" placeholder="Business Name" required><br>
      <input type="email" name="email" placeholder="Email" required><br>
      <input type="tel" name="phone" placeholder="Phone Number" required><br>
      <textarea name="notes" placeholder="Additional Notes"></textarea><br>
      <button type="submit">Submit Application</button>
    </form>
  </section>

  <section id="quote">
    <h2>Get a Quote</h2>
    <form onsubmit="return showThankYou()">
      <input type="text" name="trailerType" placeholder="Trailer Type" required><br>
      <input type="text" name="rentalTerm" placeholder="Rental Term" required><br>
      <input type="text" name="location" placeholder="Location" required><br>
      <textarea name="details" placeholder="Additional Details"></textarea><br>
      <button type="submit">Request Quote</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2025 High Call Logistics. All rights reserved.</p>
  </footer>

</body>
</html>
# website
High Call Leasing Website
