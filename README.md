- 👋 Hi, I’m @KHAITBOEV21
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
KHAITBOEV21/KHAITBOEV21 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Qarz va Kredit Boshqaruvi</title>
  <style>
    /* CSS styles go here */
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
    }
    
    .container {
      max-width: 800px;
      margin: 0 auto;
      padding: 20px;
    }
    
    h1 {
      text-align: center;
      margin-bottom: 20px;
    }
    
    .form-group {
      margin-bottom: 20px;
    }
    
    label {
      display: block;
      font-weight: bold;
      margin-bottom: 5px;
    }
    
    input, select {
      width: 100%;
      padding: 10px;
      border: 1px solid #ccc;
      border-radius: 4px;
    }
    
    button {
      display: block;
      width: 100%;
      padding: 10px;
      background-color: #4CAF50;
      color: white;
      border: none;
      border-radius: 4px;
      cursor: pointer;
    }
    
    /* Add more styles as needed */
  </style>
</head>
<body>
  <div class="container">
    <h1>Qarz va Kredit Boshqaruvi</h1>
    
    <div id="user-profile">
      <h2>Foydalanuvchi profili</h2>
      <form>
        <div class="form-group">
          <label for="name">Ism</label>
          <input type="text" id="name" name="name" required>
        </div>
        <div class="form-group">
          <label for="phone">Telefon raqami</label>
          <input type="tel" id="phone" name="phone" required>
        </div>
        <div class="form-group">
          <label for="email">Email</label>
          <input type="email" id="email" name="email" required>
        </div>
        <button type="submit">Saqlash</button>
      </form>
    </div>
    
    <div id="loan-list">
      <h2>Qarzlar ro'yxati</h2>
      <table>
        <thead>
          <tr>
            <th>Qarz egasi</th>
            <th>Qarz summasi</th>
            <th>Olgan sanasi</th>
            <th>Qaytarish muddati</th>
          </tr>
        </thead>
        <tbody id="loan-table-body">
          <!-- Loan data will be dynamically added here -->
        </tbody>
      </table>
      <button id="add-loan">Yangi qarz qo'shish</button>
    </div>
    
    <div id="payment-tracker">
      <h2>Kredit/qarz to'lovlari</h2>
      <table>
        <thead>
          <tr>
            <th>Kredit/qarz</th>
            <th>To'lov sanasi</th>
            <th>To'lov miqdori</th>
            <th>To'lov</th>
          </tr>
        </thead>
        <tbody id="payment-table-body">
          <!-- Payment data will be dynamically added here -->
        </tbody>
      </table>
    </div>
    
    <div id="debtor-list">
      <h2>Qarizdorlar ro'yxati</h2>
      <table>
        <thead>
          <tr>
            <th>Qarizdor nomi</th>
            <th>Qarz summasi</th>
            <th>Olgan sanasi</th>
            <th>Harakatlar</th>
          </tr>
        </thead>
        <tbody id="debtor-table-body">
          <!-- Debtor data will be dynamically added here -->
        </tbody>
      </table>
      <button id="add-debtor">Yangi qarizdor qo'shish</button>
    </div>
  </div>

  <script>
    // JavaScript code goes here
    // Add event listeners, data manipulation, and other functionality
  </script>
</body>
</html>
