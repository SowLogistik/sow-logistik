!DOCTYPE html>
<html lang="de">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Sow Logistik e.K</title>
<style>
body {
margin: 0;
font-family: Arial, sans-serif;
background: #f5f5f5;
color: #333;
}
header {
background: linear-gradient(to right, black, red, gold);
color: white;
padding: 60px 20px;
text-align: center;
}
nav {
text-align: right;
padding: 10px 20px;
background: #111;
}
nav button {
margin-left: 5px;
padding: 5px 10px;
cursor: pointer;
}
section {
padding: 40px 20px;
max-width: 1000px;
margin: auto;
}
.services ul {
list-style: none;
padding: 0;
}
.services li {
background: white;
margin: 10px 0;
padding: 15px;
border-left: 5px solid #c00;
}
.contact {
background: #222;
color: white;
}
footer {
text-align: center;
padding: 20px;
background: #000;
color: white;
}
</style>
</head>

<body>

<nav>
<button onclick="setLang('de')">DE</button>
<button onclick="setLang('en')">EN</button>
<button onclick="setLang('fr')">FR</button>
</nav>

<header>
<h1 id="title">Sow Logistik e.K</h1>
<p id="slogan">Ihr zuverlässiger Partner für Logistik & Transport</p>
</header>

<section class="services">
<h2 id="servicesTitle">Unsere Leistungen</h2>
<ul id="servicesList">
<li>An- und Verkauf</li>
<li>Umzugsservice</li>
<li>Abschlepp- und Transportservice</li>
<li>Container Service</li>
<li>LKW Fahren & Verschiffung</li>
<li>Export & Import</li>
<li>Test & Zertifizierung von Elektrogeräten aller Art</li>
<li>Cargo, Seefracht & Luftfracht</li>
</ul>
</section>

<section>
<h2 id="aboutTitle">Über uns</h2>
<p id="aboutText">
Sow Logistik e.K ist ein internationales Logistikunternehmen mit Sitz in Bonn.
Wir bieten zuverlässige Transportlösungen in Europa und weltweit.
</p>
</section>

<section class="contact">
<h2 id="contactTitle">Kontakt</h2>
<p>
<strong>Ibrahima Sory Sow</strong><br>
Kesselgasse 1A<br>
53111 Bonn<br><br>
TEL: +49 176 32310930<br>
E-Mail: <a href="mailto:ibrahimdian@web.de" style="color:#ffd700;">ibrahimdian@web.de</a>
</p>
</section>

<footer>
© 2025 Sow Logistik e.K
</footer>

<script>
const content = {
de: {
title: "Sow Logistik e.K",
slogan: "Ihr zuverlässiger Partner für Logistik & Transport",
servicesTitle: "Unsere Leistungen",
aboutTitle: "Über uns",
aboutText: "Sow Logistik e.K ist ein internationales Logistikunternehmen mit Sitz in Bonn."
},
en: {
title: "Sow Logistics e.K",
slogan: "Your reliable logistics and transport partner",
servicesTitle: "Our Services",
aboutTitle: "About Us",
aboutText: "Sow Logistics e.K is an international logistics company based in Bonn."
},
fr: {
title: "Sow Logistique e.K",
slogan: "Votre partenaire fiable en logistique et transport",
servicesTitle: "Nos services",
aboutTitle: "À propos de nous",
aboutText: "Sow Logistique e.K est une entreprise internationale basée à Bonn."
}
};

function setLang(lang) {
document.getElementById("title").innerText = content[lang].title;
document.getElementById("slogan").innerText = content[lang].slogan;
document.getElementById("servicesTitle").innerText = content[lang].servicesTitle;
document.getElementById("aboutTitle").innerText = content[lang].aboutTitle;
document.getElementById("aboutText").innerText = content[lang].aboutText;
}
</script>

</body>
</html>

Gesendet mit der WEB.DE Mail App
