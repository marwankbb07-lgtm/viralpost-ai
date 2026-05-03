<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>ViralPost AI</title>
</head>

<body style="font-family:Arial; text-align:center; background:#f4f8ff; padding:30px;">

  <h1 style="color:#1e66ff;">ViralPost AI 💄</h1>

  <p>اكتب الخدمة ديالك (مثال: صالون شعر في الرباط)</p>

  <textarea id="input" style="width:80%; height:100px; padding:10px;"></textarea>

  <br><br>

  <button onclick="generate()" style="padding:10px 20px; background:#1e66ff; color:white; border:none;">
    Generate
  </button>

  <div id="output" style="margin-top:20px; background:white; padding:20px; width:80%; margin:auto;"></div>

  <script>
    function generate() {
      let text = document.getElementById("input").value;

      let result = `
✨ Caption:
خدمة تجميل احترافية 💄 كتخليك تباني بأحسن إطلالة

📍 ${text}

🔥 Hashtags:
#Beauty #Salon #Morocco #GlowUp #Style

💡 فكرة Post:
صورة قبل/بعد + إضاءة ناعمة + ابتسامة الزبونة
      `;

      document.getElementById("output").innerText = result;
    }
  </script>

</body>
</html>
