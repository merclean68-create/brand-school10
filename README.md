# brand-school10  
brandschool/
├── index.html
├── index-en.html
├── about-en.html
├── services-en.html
├── brands-en.html
├── contact-en.html
├── index-fr.html
├── about-fr.html
├── services-fr.html
├── brands-fr.html
├── contact-fr.html
├── index-ar.html
├── about-ar.html
├── services-ar.html
├── brands-ar.html
├── contact-ar.html
├── style.css
├── script.js
└── images/
    ├── mercedess-logo.png
    └── mercedess-background.jpg
    <!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Brand School – Choose Language</title>
<meta name="description" content="Welcome to Brand School. Choose your language to explore our brand services.">
<link rel="stylesheet" href="style.css">
<script src="script.js" defer></script>
</head>
<body>
<noscript>
<h1>Brand School</h1>
<p>Select your language:</p>
<ul>
  <li><a href="index-en.html">English</a></li>
  <li><a href="index-fr.html">Français</a></li>
  <li><a href="index-ar.html">العربية</a></li>
</ul>
</noscript>
</body>
</html>
document.addEventListener('DOMContentLoaded', () => {
  const userLang = navigator.language || navigator.userLanguage;
  if(userLang.startsWith('fr')){
    window.location.href = "index-fr.html";
  } else if(userLang.startsWith('ar')){
    window.location.href = "index-ar.html";
  } else {
    window.location.href = "index-en.html";
  }
});
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  line-height: 1.6;
  background: url('images/mercedess-background.jpg') no-repeat center center fixed;
  background-size: cover;
  color: #ffffff;
}

header {
  background-color: rgba(0,0,0,0.7);
  color: #ffffff;
  padding: 20px;
}

header img {
  height: 60px;
  vertical-align: middle;
}

header nav a {
  color: #c0c0c0;
  margin-right: 15px;
  text-decoration: none;
  font-weight: bold;
}

header nav a:hover {
  color: #ffffff;
}

main {
  padding: 30px;
  background-color: rgba(0,0,0,0.5);
  border-radius: 10px;
  margin: 20px;
}

footer {
  background-color: rgba(0,0,0,0.8);
  color: #c0c0c0;
  text-align: center;
  padding: 15px;
}

footer a {
  color: #c0c0c0;
  text-decoration: none;
}

footer a:hover {
  color: #ffffff;
}

.language-switcher {
  margin-top: 10px;
}

.language-switcher a {
  margin-right: 10px;
  text-decoration: underline;
  color: #c0c0c0;
}

/* RTL للعربية */
[dir="rtl"] {
  text-align: right;
}
<header>
  <img src="images/mercedess-logo.png" alt="Mercedess Logo">
  <h1>Brand School</h1>
  <nav>
    <a href="index-en.html">Home</a>
    <a href="about-en.html">About Us</a>
    <a href="services-en.html">Services</a>
    <a href="brands-en.html">Brands</a>
    <a href="contact-en.html">Contact</a>
    <a href="index-fr.html">Français</a>
    <a href="index-ar.html">العربية</a>
  </nav>
</header>

<footer>
  <p>© 2025 Brand School. جميع الحقوق محفوظة.</p>
  <p>تواصل معنا:</p>
  <ul>
    <li><a href="https://www.facebook.com/XxmerxX1/about" target="_blank">Facebook</a></li>
    <li><a href="mailto:merclean68@gmail.com">Email</a></li>
  </ul>
</footer>
<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>من نحن – Brand School</title>
<meta name="description" content="تعرف على مهمة Brand School لبناء هوية علامات تجارية قوية ومبتكرة.">
<link rel="stylesheet" href="style.css">
</head>
<body>
<header>
  <img src="images/mercedess-logo.png" alt="Mercedess Logo">
  <h1>Brand School</h1>
  <nav>
    <a href="index-ar.html">الرئيسية</a>
    <a href="about-ar.html">من نحن</a>
    <a href="services-ar.html">الخدمات</a>
    <a href="brands-ar.html">العلامات</a>
    <a href="contact-ar.html">اتصل بنا</a>
    <a href="index-en.html">English</a>
    <a href="index-fr.html">Français</a>
  </nav>
</header>
<main>
<h2>من نحن</h2>
<p>في Brand School، نعمل على بناء هوية قوية للعلامات التجارية لتتميز في السوق.</p>
</main>
<footer>
  <p>© 2025 Brand School. جميع الحقوق محفوظة.</p>
  <p>تواصل معنا:</p>
  <ul>
    <li><a href="https://www.facebook.com/XxmerxX1/about" target="_blank">Facebook</a></li>
    <li><a href="mailto:merclean68@gmail.com">Email</a></li>
  </ul>
</footer>
</body>
</html>
### AL ###
#Template for AL projects for Dynamics 365 Business Central
#launch.json folder
.vscode/
#Cache folder
.alcache/
#Symbols folder
.alpackages/
#Snapshots folder
.snapshots/
#Testing Output folder
.output/
#Extension App-file
*.app
#Rapid Application Development File
rad.json
#Translation Base-file
*.g.xlf
#License-file
*.flf
#Test results file
<img width="1300" height="1390" alt="image" src="https://github.com/user-attachments/assets/57e51684-3a55-4a98-9a34-1a8e6e441841" />
![letter-m-logo-concept-with-eagle-face-alphabet-m-falcon-icon-3AAF4C6 - Copie](https://github.com/user-attachments/assets/21c6d4bf-13ae-411a-88cb-debff54b8c4a)

