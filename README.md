<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Family Registration Form</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f9f9f9;
      padding: 20px;
    }
    form {
      background: #fff;
      padding: 20px;
      max-width: 500px;
      margin: auto;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }
    label {
      margin-top: 15px;
      display: block;
      font-weight: bold;
    }
    input {
      width: 100%;
      padding: 10px;
      margin-top: 5px;
      margin-bottom: 10px;
    }
    button {
      background-color: #28a745;
      border: none;
      color: white;
      padding: 10px;
      width: 100%;
      font-size: 16px;
      border-radius: 5px;
    }
  </style>
</head>
<body>

  <form action="https://formsubmit.co/mufadh4@gmail.com" method="POST">
    <h2>Family Registration Form</h2>

    <label>1. Family Name</label>
    <input type="text" name="Family Name" required>

    <label>2. Adults 13 yrs above - Male</label>
    <input type="number" name="Adult Male" min="0">

    <label>2. Adults 13 yrs above - Female</label>
    <input type="number" name="Adult Female" min="0">

    <label>3. Kids 8 yrs above - Boys</label>
    <input type="number" name="Kids Boys" min="0">

    <label>3. Kids 8 yrs above - Girls</label>
    <input type="number" name="Kids Girls" min="0">

    <label>4. Infants 7 yrs below - Boys</label>
    <input type="number" name="Infants Boys" min="0">

    <label>4. Infants 7 yrs below - Girls</label>
    <input type="number" name="Infants Girls" min="0">

    <input type="hidden" name="_captcha" value="false">
    <button type="submit">Submit</button>
  </form>

</body>
</html>      
