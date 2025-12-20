# Youth-Camp-Registration-Form
The Youth Camp Registration Form collects participant and parent/guardian details, emergency contacts, medical and allergy information, session selection, consents, and payment details to ensure safety, clear communication, and organized camp management.
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Youth Camp Registration Form</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f4f6f8;
      padding: 20px;
    }
    form {
      max-width: 700px;
      margin: auto;
      background: #fff;
      padding: 20px;
      border-radius: 8px;
    }
    h2 {
      text-align: center;
    }
    label {
      display: block;
      margin-top: 12px;
      font-weight: bold;
    }
    input, select, textarea {
      width: 100%;
      padding: 8px;
      margin-top: 5px;
    }
    .row {
      display: flex;
      gap: 10px;
    }
    .row div {
      flex: 1;
    }
    button {
      margin-top: 20px;
      width: 100%;
      padding: 12px;
      background: #007bff;
      color: white;
      border: none;
      font-size: 16px;
      cursor: pointer;
    }
    button:hover {
      background: #0056b3;
    }
  </style>
</head>
<body>

<form>
  <h2>Youth Camp Registration Form</h2>

  <!-- Camper Information -->
  <label>Camper Full Name</label>
  <input type="text" required>

  <div class="row">
    <div>
      <label>Date of Birth</label>
      <input type="date" required>
    </div>
    <div>
      <label>Gender</label>
      <select>
        <option value="">Select</option>
        <option>Male</option>
        <option>Female</option>
        <option>Other</option>
      </select>
    </div>
  </div>

  <label>Grade</label>
  <input type="text">

  <label>T-Shirt Size</label>
  <select>
    <option>YS</option>
    <option>YM</option>
    <option>YL</option>
    <option>AS</option>
    <option>AM</option>
    <option>AL</option>
  </select>

  <!-- Address -->
  <label>Address</label>
  <input type="text" placeholder="Street Address">

  <div class="row">
    <div><input type="text" placeholder="City"></div>
    <div><input type="text" placeholder="State"></div>
    <div><input type="text" placeholder="Zip"></div>
  </div>

  <!-- Parent / Guardian -->
  <label>Parent / Guardian Name</label>
  <input type="text" required>

  <label>Phone Number</label>
  <input type="tel" required>

  <label>Email</label>
  <input type="email" required>

  <!-- Emergency -->
  <label>Emergency Contact Name</label>
  <input type="text">

  <label>Emergency Contact Phone</label>
  <input type="tel">

  <!-- Medical -->
  <label>Medical Conditions / Allergies</label>
  <textarea rows="3"></textarea>

  <!-- Consent -->
  <label>
    <input type="checkbox" required>
    I consent to my child’s participation in the youth camp.
  </label>

  <button type="submit">Submit Registration</button>
</form>

</body>
</html>
