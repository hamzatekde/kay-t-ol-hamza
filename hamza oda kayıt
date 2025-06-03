<!DOCTYPE html>
<html lang="tr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Hamza'nın Odaları - Kayıt Ol</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f0f4f8;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      padding: 20px;
    }
    .form-container {
      background-color: white;
      padding: 24px;
      border-radius: 12px;
      box-shadow: 0 6px 12px rgba(0, 0, 0, 0.1);
      width: 340px;
      text-align: center;
    }
    .form-container h1 {
      font-size: 22px;
      color: #333;
      margin-bottom: 10px;
    }
    .intro {
      font-size: 14px;
      color: #555;
      margin-bottom: 20px;
    }
    .form-group {
      text-align: left;
      margin-bottom: 15px;
    }
    label {
      display: block;
      margin-bottom: 5px;
    }
    input[type="text"], input[type="number"] {
      width: 100%;
      padding: 8px;
      border: 1px solid #ccc;
      border-radius: 6px;
    }
    button {
      width: 100%;
      padding: 10px;
      background-color: #007acc;
      color: white;
      border: none;
      border-radius: 6px;
      font-size: 16px;
      cursor: pointer;
    }
    button:hover {
      background-color: #005f99;
    }
    .success-message {
      display: none;
      margin-top: 15px;
      color: green;
      font-weight: bold;
    }
  </style>
</head>
<body>

  <div class="form-container">
    <h1>Hamza’nın Odalarına Hoş Geldin!</h1>
    <div class="intro">
      Eğlenceye hazır mısın?<br>
      Hemen kayıt ol, <strong>Hamza’nın özel odalarına katıl</strong> ve sürpriz aktiviteleri kaçırma! 🎉
    </div>

    <form id="kayitForm">
      <div class="form-group">
        <label for="ad">Ad:</label>
        <input type="text" id="ad" name="ad" required>
      </div>
      <div class="form-group">
        <label for="soyad">Soyad:</label>
        <input type="text" id="soyad" name="soyad" required>
      </div>
      <div class="form-group">
        <label for="yas">Yaş:</label>
        <input type="number" id="yas" name="yas" min="0" required>
      </div>
      <div class="form-group">
        <label for="meslek">Meslek:</label>
        <input type="text" id="meslek" name="meslek" required>
      </div>
      <button type="submit">Kaydol</button>
      <div class="success-message" id="basariMesaji">Teşekkürler, kayıt tamamlandı.</div>
    </form>
  </div>

  <script>
    document.getElementById("kayitForm").addEventListener("submit", function(e) {
      e.preventDefault();
      document.getElementById("basariMesaji").style.display = "block";
      this.reset();
    });
  </script>

</body>
</html>
