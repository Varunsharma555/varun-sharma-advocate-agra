<!DOCTYPE html><html lang="hi">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Varun Sharma - Advocate</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
  <style>
    body {margin:0;font-family:'Poppins',sans-serif;background:#f5f7fa;color:#333}
    header {background:linear-gradient(135deg,#1a237e,#3949ab);color:white;padding:40px 20px;text-align:center}
    nav {display:flex;justify-content:center;background:#222;flex-wrap:wrap}
    nav a {color:white;padding:12px 15px;text-decoration:none}
    nav a:hover {background:#3949ab}
    .container {max-width:1100px;margin:auto;padding:20px}
    .card {background:white;padding:20px;margin:15px 0;border-radius:12px;box-shadow:0 5px 15px rgba(0,0,0,0.1)}
    h2 {color:#1a237e}
    .btn {display:inline-block;padding:10px 20px;background:#25D366;color:white;border-radius:6px;text-decoration:none;margin-top:10px}
    input, textarea, select {width:100%;padding:10px;margin:8px 0;border-radius:6px;border:1px solid #ccc}
    button {background:#1a237e;color:white;padding:10px 20px;border:none;border-radius:6px;cursor:pointer}
    footer {background:#1a237e;color:white;text-align:center;padding:15px;margin-top:20px}
  </style>
</head>
<body><header>
  <h1>वरुण शर्मा एडवोकेट</h1>
  <p>जिला व सत्र न्यायालय, आगरा</p>
  <a class="btn" href="https://wa.me/919990680629" target="_blank">WhatsApp पर संपर्क करें</a>
</header><nav>
  <a href="#about">परिचय</a>
  <a href="#services">सेवाएं</a>
  <a href="#cases">केस</a>
  <a href="#booking">बुकिंग</a>
  <a href="#contact">संपर्क</a>
</nav><div class="container"><div class="card" id="about">
  <h2>मेरे बारे में</h2>
  <p>मैं वरुण शर्मा, जिला व सत्र न्यायालय आगरा में प्रैक्टिस करने वाला अधिवक्ता हूँ।</p>
</div><div class="card" id="services">
  <h2>मेरी सेवाएं</h2>
  <ul>
    <li>क्रिमिनल केस</li>
    <li>सिविल केस</li>
    <li>138 NI Act</li>
    <li>लीगल नोटिस</li>
  </ul>
</div><div class="card" id="cases">
  <h2>हाल के केस</h2>
  <p>✔ जमानत आदेश</p>
  <p>✔ FIR निरस्तीकरण</p>
</div><div class="card" id="booking">
  <h2>ऑनलाइन अपॉइंटमेंट बुक करें</h2>
  <form onsubmit="sendToWhatsApp(); return false;">
    <input type="text" id="name" placeholder="आपका नाम" required>
    <input type="tel" id="phone" placeholder="मोबाइल नंबर" required>
    <select id="case">
      <option>क्रिमिनल केस</option>
      <option>सिविल केस</option>
      <option>138 NI Act</option>
    </select>
    <textarea id="message" placeholder="अपनी समस्या लिखें"></textarea>
    <button type="submit">अपॉइंटमेंट भेजें</button>
  </form>
</div><div class="card" id="contact">
  <h2>संपर्क करें</h2>
  <p>📞 9990680629</p>
  <p>📍 जिला न्यायालय, आगरा</p>
</div></div><footer>
  <p>© 2026 Varun Sharma Advocate</p>
</footer><script>
function sendToWhatsApp(){
  var name=document.getElementById('name').value;
  var phone=document.getElementById('phone').value;
  var caseType=document.getElementById('case').value;
  var msg=document.getElementById('message').value;

  var url="https://wa.me/919990680629?text="
  +"Name: "+name+"%0A"
  +"Phone: "+phone+"%0A"
  +"Case: "+caseType+"%0A"
  +"Problem: "+msg;

  window.open(url,'_blank');
}
</script></body>
</html>
