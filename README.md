# gamzeweb
<!DOCTYPE html>
<html lang="tr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Gamze Çaylan | Mimarlık Yüksek Lisans Adayı</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f9f9f9;
      margin: 0;
      padding: 0;
      line-height: 1.6;
    }
    header {
      background: #004d40;
      color: white;
      padding: 1.5rem;
      text-align: center;
    }
    header nav ul {
      list-style: none;
      padding: 0;
      margin-top: 1rem;
      display: flex;
      justify-content: center;
      gap: 1.5rem;
    }
    header nav ul li a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }
    header nav ul li a:hover {
      color: #80cbc4;
      text-decoration: underline;
    }
    .container {
      max-width: 900px;
      margin: 2rem auto;
      background: white;
      padding: 2rem;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }
    h2 {
      border-bottom: 2px solid #004d40;
      padding-bottom: 0.5rem;
    }
    section {
      margin-bottom: 2rem;
    }
    ul {
      list-style-type: none;
      padding: 0;
    }
    ul li::before {
      content: "\2022";
      color: #004d40;
      font-weight: bold;
      display: inline-block; 
      width: 1em;
      margin-left: -1em;
    }
    .project-gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 1rem;
    }
    .project-gallery img {
      width: 100%;
      height: auto;
      border: 1px solid #ddd;
      border-radius: 4px;
      transition: transform 0.3s ease;
    }
    .project-gallery img:hover {
      transform: scale(1.05);
    }
    .caption {
      text-align: center;
      font-size: 0.9rem;
      margin-top: 0.5rem;
    }
    a {
      color: inherit;
      text-decoration: none;
    }
    a:hover {
      text-decoration: underline;
      color: #80cbc4;
    }
    footer {
      background:#004d40;
      color:white;
      text-align:center;
      padding:1rem;
      margin-top:2rem;
    }
  </style>
</head>
<body>

<header>
  <h1>Gamze Çaylan</h1>
  <p>Mimarlık Yüksek Lisans Adayı</p>
  <nav>
    <ul>
      <li><a href="#niyet">Niyet Mektubu</a></li>
      <li><a href="#ozgecmis">Özgeçmiş</a></li>
      <li><a href="#projeler">Projelerim</a></li>
      <li><a href="#iletisim">İletişim</a></li>
    </ul>
  </nav>
</header>

<div class="container">
  <section id="niyet">
    <h2>Niyet Mektubu</h2>
    <p>Ben Gamze Çaylan. Amasya Üniversitesi Mimarlık Fakültesi’nden mezun oldum. Mimarlık eğitimi süresince geliştirdiğim tasarım, analiz ve eleştirel düşünme becerileriyle birlikte, mesleğin yalnızca yapı tasarımıyla sınırlı kalmadığını; çevre, toplum ve kültürle etkileşim içerisinde, çok boyutlu bir alan olduğunu deneyimledim. Bu farkındalık doğrultusunda, mimarlık alanında özellikle sürdürülebilirlik ve çevresel sorumluluk çerçevesinde akademik olarak derinleşmeyi hedefliyorum.</p>
  </section>

  <section id="ozgecmis">
    <h2>Özgeçmiş</h2>
    <ul>
      <li><strong>Ad:</strong> Gamze Çaylan</li>
      <li><strong>Eğitim:</strong> Amasya Üniversitesi Mimarlık Fakültesi</li>
      <li><strong>Uzmanlık Alanları:</strong> Sürdürülebilir Mimari, Çevresel Tasarım, Kentsel Dönüşüm</li>
      <li><strong>Yazılımlar:</strong> AutoCAD, Revit, SketchUp, Adobe Photoshop, Rhino</li>
      <li><strong>Yabancı Dil:</strong> İngilizce (İyi seviye)</li>
    </ul>
  </section>

  <section id="projeler">
    <h2>Projelerim</h2>
    <div class="project-gallery">
      <div>
        <img src="project1.jpg" alt="Proje 1" />
        <div class="caption">Sürdürülebilir Konut Yerleşkesi</div>
      </div>
      <div>
        <img src="project2.jpg" alt="Proje 2" />
        <div class="caption">Doğal Malzeme Kullanımıyla Tasarım</div>
      </div>
      <div>
        <img src="project3.jpg" alt="Proje 3" />
        <div class="caption">Kentsel Dönüşüm Alanı Planlaması</div>
      </div>
      <div>
        <img src="WhatsApp Image 2025-05-30 at 03.10.25.jpeg" alt="Maketten Yapı Modeli" />
        <div class="caption">Topografya ile Entegre Strüktürel Tasarım</div>
      </div>
      <div>
        <img src="WhatsApp Image 2025-05-30 at 03.10.32.jpeg" alt="Modüler Yapı Modeli" />
        <div class="caption">Strüktürel ve Fonksiyonel Modülerlik</div>
      </div>
    </div>
  </section>

  <section id="iletisim">
    <h2>İletişim</h2>
    <p>Email: <a href="mailto:gamze.caylan1@gmail.com">gamze.caylan@example.com</a></p>
    <p>Telefon: +90 5516714420</p>
  </section>
</div>

<footer>
  <p>© 2025 Gamze Çaylan. Tüm hakları saklıdır.</p>
</footer>

</body>
</html>
