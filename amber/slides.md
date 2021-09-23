---
# try also 'default' to start simple
theme: seriph
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: images/fondo.jpeg
# apply any windi css classes to the current slide
class: 'text-center'
# https://sli.dev/custom/highlighters.html
highlighter: shiki
# show line numbers in code blocks
lineNumbers: false
# some information about the slides, markdown enabled
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
# persist drawings in exports and build
drawings:
  persist: false
---

# Presentación Grupo de Trabajo

Integrantes del grupo CiberSecFIIS

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    Press Space for next page <carbon:arrow-right class="inline"/>
  </span>
</div>

<div class="abs-br m-6 flex gap-2">
  <button @click="$slidev.nav.openInEditor()" title="Open in Editor" class="text-xl icon-btn opacity-50 !border-none !hover:text-white">
    <carbon:edit />
  </button>
  <a href="https://github.com/slidevjs/slidev" target="_blank" alt="GitHub"
    class="text-xl icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-logo-github />
  </a>
</div>


---

# Joseph Mottoccanche 

<br>
<div class="box">
  <div class="left">
    <div class="content">
      <br>
      <img src=images/foto_recortada.jpg>
      <br>
      <div id=texto2>Estudiante de 7mo ciclo <br>
      de Ingeniería de Sistemas.</div>
    </div>
  </div>
  <div class="right">
    <div class="content">
      <h3>Capacitaciones</h3>
      <br>
      <h4>Creando una trayectoria Profesional en Ciberseguridad</h4>
      <div id="texto">Organización de los Estados Americanos (OEA)</div>
      <h4>Capacitación Ciberseguridad y Ethical Hacking</h4>
      <div id="texto">Kunak Consulting</div>
      <br>
      <h3>Proyectos Personales</h3>
      <br>
      <h4>HockuAPP</h4>
      <div id="texto">Aplicación para la compra de productos en la UNI</div>
      <h4>Taller de Introducción Linux</h4>
      <div id="texto">Taller dictado semestralmente en la FIIS por parte de Nixvoid</div>
    </div>
  </div>
</div>

<br>
<div>

</div>

<style>
#texto2{
  text-align:center;
}
h1 {
  background-color: #a6b6e3;
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent; 
  -moz-text-fill-color: transparent;
}
h3{
  font-weight:bold;
  background-color: #444b64;
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent; 
  -moz-text-fill-color: transparent;

}
h4{
  font-weight:bold;
  background-color: #717da5;
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent; 
  -moz-text-fill-color: transparent;
}
img{
  width:90%;
  height:auto;
  margin:auto;
  display:block;
  border-radius:5px;
  /*box-shadow:5px 5px 0px #424242;*/

}
.box {
    overflow: hidden;
}
.content {
    font-size: 15px;
    line-height: 20px;
    padding: 0 20px;
    text-align: justify;
}
.left {
    float: left;
    width: 30%;SS
}
.left .content {
    border-right: 5px solid #a6b6e3  ;
}
.right {
    float: right;
    width: 70%;
}
</style>


---

# Habilidades 

<div class="box">
  <div class="left">
    <div class="content">
      <p>BASH</p>
        <div class="container">
          <div class="skills bash">70%</div>
        </div>
      <p>Manejo de Sistemas Linux</p>
        <div class="container">
          <div class="skills Manejo_Linux">90%</div>
        </div>
      <p>Redes</p>
        <div class="container">
          <div class="skills redes">60%</div>
        </div>
      <p>Latex</p>
        <div class="container">
          <div class="skills latex">70%</div>
        </div>
      <p>C++</p>
        <div class="container">
          <div class="skills c">60%</div>
        </div>
    </div>
  </div>
  <div class="right">
    <div class="content">
    </div>
  </div>
</div>


<style>
* {box-sizing:border-box}

.container {
  width: 100%; /* Full width */
  background-color: #ddd; /* Grey background */
  border-radius:10px;
  height: 3%;
}
.skills {
  text-align: right; /* Right-align text */
  padding-top: 2px; /* Add top padding */
  padding-bottom: 2px; /* Add bottom padding */
  color: white; /* White text color */
  border-radius:10px;
  height: 20%;
  font-size: xx-small;
}
.bash {width: 70%; background-color: #3F448C;} 
.Manejo_Linux {width: 90%; background-color: #5a61bd;} 
.redes {width: 60%; background-color: #3F448C;} 
.latex {width: 70%; background-color: #5a61bd;}
.c {width: 60%; background-color: #5a61bd;} 
</style>
<style>
h1 {
  background-color: #a6b6e3;
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent; 
  -moz-text-fill-color: transparent;
}
</style>
<style>
  .box {
    overflow: hidden;
}
.content {
    font-size: 15px;
    line-height: 20px;
    padding: 0 20px;
    text-align: justify;
}
.left {
    float: left;
    width: 65%;SS
}
.right {
    float: right;
    width: 35%;
}
</style>

---

# Cristhian Bonilla

<br>
<div class="box">
  <div class="left">
    <div class="content">
      <br>
      <img src=images/cristhian.jpg>
      <br>
      <div id=texto2>Estudiante de 7mo ciclo <br>
      de Ingeniería de Sistemas.</div>
    </div>
  </div>
  <div class="right">
    <div class="content">
      <h3>Logros</h3>
      <br>
      <h4>1er Puesto en el examen Programación Competitiva</h4>
      <div id="texto">FIIS</div>
      <h4>Participación en el grupo de Desarrollo Web</h4>
      <div id="texto">Núcleo FIIS</div>
      <br>
      <h3>Certificaciones</h3>
      <br>
      <h4>Hacking Ético de Redes Wifi Básico </h4>
      <div id="texto">Hacker Mentor</div>
    </div>
  </div>
</div>

<br>
<div>

</div>

<style>
#texto2{
  text-align:center;
}
h1 {
  background-color: #a6b6e3;
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent; 
  -moz-text-fill-color: transparent;
}
h3{
  font-weight:bold;
  background-color: #444b64;
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent; 
  -moz-text-fill-color: transparent;

}
h4{
  font-weight:bold;
  background-color: #717da5;
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent; 
  -moz-text-fill-color: transparent;
}
img{
  width:90%;
  height:auto;
  margin:auto;
  display:block;
  border-radius:5px;
  /*box-shadow:5px 5px 0px #424242;*/

}
.box {
    overflow: hidden;
}
.content {
    font-size: 15px;
    line-height: 20px;
    padding: 0 20px;
    text-align: justify;
}
.left {
    float: left;
    width: 30%;SS
}
.left .content {
    border-right: 5px solid #a6b6e3  ;
}
.right {
    float: right;
    width: 70%;
}
</style>

---

# Habilidades 

<div class="box">
  <div class="left">
    <div class="content">
      <p>BASH</p>
        <div class="container">
          <div class="skills bash">40%</div>
        </div>
      <p>Manejo de Sistemas Linux</p>
        <div class="container">
          <div class="skills Manejo_Linux">40%</div>
        </div>
      <p>Python</p>
        <div class="container">
          <div class="skills python">50%</div>
        </div>
      <p>PostgreSQL</p>
        <div class="container">
          <div class="skills PostgreSQL">50%</div>
        </div>
      <p>C++</p>
        <div class="container">
          <div class="skills c">55%</div>
        </div>
    </div>
  </div>
  <div class="right">
    <div class="content">
    </div>
  </div>
</div>


<style>
* {box-sizing:border-box}

.container {
  width: 100%; /* Full width */
  background-color: #ddd; /* Grey background */
  border-radius:10px;
  height: 3%;
}
.skills {
  text-align: right; /* Right-align text */
  padding-top: 2px; /* Add top padding */
  padding-bottom: 2px; /* Add bottom padding */
  color: white; /* White text color */
  border-radius:10px;
  height: 20%;
  font-size: xx-small;
}
.bash {width: 40%; background-color: #3F448C;} 
.Manejo_Linux {width: 40%; background-color: #5a61bd;} 
.python {width: 50%; background-color: #3F448C;} 
.PostgreSQL {width: 50%; background-color: #5a61bd;}
.c {width: 55%; background-color: #5a61bd;} 
</style>
<style>
h1 {
  background-color: #a6b6e3;
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent; 
  -moz-text-fill-color: transparent;
}
</style>
<style>
  .box {
    overflow: hidden;
}
.content {
    font-size: 15px;
    line-height: 20px;
    padding: 0 20px;
    text-align: justify;
}
.left {
    float: left;
    width: 65%;SS
}
.right {
    float: right;
    width: 35%;
}
</style>

---

# Elian Paucar

<br>
<div class="box">
  <div class="left">
    <div class="content">
      <br>
      <img src=images/elian2.jpg>
      <br>
      <div id=texto2>Estudiante de 7mo ciclo <br>
      de Ingeniería de Sistemas.</div>
    </div>
  </div>
  <div class="right">
    <div class="content">
      <h3>Logros y Certificaciones</h3>
      <br>
      <h4>5to puesto Torneo Nacional Hacking 2020</h4>
      <div id="texto">EnHacke</div>
      <h4>Cyber Security Foundation - CSFPC™</h4>
      <div id="texto">Certiprof</div>
      <h4>CCNA v7: Introduction to Networks</h4>
      <div id="texto">Cisco Networking Academy</div>
      <h4>Certificado CyberApocalypse CTF 2021</h4>
      <div id="texto">HackTheBox</div>
      <br>
    </div>
  </div>
</div>

<br>
<div>

</div>

<style>
#texto2{
  text-align:center;
}
h1 {
  background-color: #a6b6e3;
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent; 
  -moz-text-fill-color: transparent;
}
h3{
  font-weight:bold;
  background-color: #444b64;
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent; 
  -moz-text-fill-color: transparent;

}
h4{
  font-weight:bold;
  background-color: #717da5;
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent; 
  -moz-text-fill-color: transparent;
}
img{
  width:90%;
  height:auto;
  margin:auto;
  display:block;
  border-radius:5px;
  /*box-shadow:5px 5px 0px #424242;*/

}
.box {
    overflow: hidden;
}
.content {
    font-size: 15px;
    line-height: 20px;
    padding: 0 20px;
    text-align: justify;
}
.left {
    float: left;
    width: 30%;SS
}
.left .content {
    border-right: 5px solid #a6b6e3  ;
}
.right {
    float: right;
    width: 70%;
}
</style>

---

# Habilidades 

<div class="box">
  <div class="left">
    <div class="content">
      <p>Oracle</p>
        <div class="container">
          <div class="skills Oracle">40%</div>
        </div>
      <p>Manejo de Sistemas Linux</p>
        <div class="container">
          <div class="skills Manejo_Linux">50%</div>
        </div>
      <p>Python</p>
        <div class="container">
          <div class="skills python">50%</div>
        </div>
      <p>Redes</p>
        <div class="container">
          <div class="skills redes">45%</div>
        </div>
      <p>C++</p>
        <div class="container">
          <div class="skills c">60%</div>
        </div>
    </div>
  </div>
  <div class="right">
    <div class="content">
    </div>
  </div>
</div>


<style>
* {box-sizing:border-box}

.container {
  width: 100%; /* Full width */
  background-color: #ddd; /* Grey background */
  border-radius:10px;
  height: 3%;
}
.skills {
  text-align: right; /* Right-align text */
  padding-top: 2px; /* Add top padding */
  padding-bottom: 2px; /* Add bottom padding */
  color: white; /* White text color */
  border-radius:10px;
  height: 20%;
  font-size: xx-small;
}
.Oracle {width: 40%; background-color: #3F448C;} 
.Manejo_Linux {width: 50%; background-color: #5a61bd;} 
.python {width: 50%; background-color: #3F448C;} 
.redes {width: 45%; background-color: #5a61bd;}
.c {width: 60%; background-color: #5a61bd;} 
</style>
<style>
h1 {
  background-color: #a6b6e3;
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent; 
  -moz-text-fill-color: transparent;
}
</style>
<style>
  .box {
    overflow: hidden;
}
.content {
    font-size: 15px;
    line-height: 20px;
    padding: 0 20px;
    text-align: justify;
}
.left {
    float: left;
    width: 65%;SS
}
.right {
    float: right;
    width: 35%;
}
</style>

---

# Juan Mora

<br>
<div class="box">
  <div class="left">
    <div class="content">
      <br>
      <img src=images/Juan_mora.jpg>
      <br>
      <div id=texto2>Estudiante de 8vo ciclo <br>
      de Ingeniería de Sistemas.</div>
    </div>
  </div>
  <div class="right">
    <div class="content">
      <br>
      <h3>Logros y Certificaciones</h3>
      <br>
      <h4>Creando una Trayectoria Profesional en Ciberseguridad</h4>
      <div id="texto">Organización de los Estados Americanos (OEA) </div>
      <h4>Cyber Security Foundation - CSFPC™</h4>
      <div id="texto">Certiprof</div>
      <h4>Certificado CyberApocalypse CTF 2021</h4>
      <div id="texto">HackTheBox</div>
      <h4>19no puesto Torneo Nacional Hacking 2020</h4>
      <div id="texto">EnHacke</div>
      <br>
    </div>
  </div>
</div>

<br>
<div>

</div>

<style>
#texto2{
  text-align:center;
}
h1 {
  background-color: #a6b6e3;
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent; 
  -moz-text-fill-color: transparent;
}
h3{
  font-weight:bold;
  background-color: #444b64;
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent; 
  -moz-text-fill-color: transparent;

}
h4{
  font-weight:bold;
  background-color: #717da5;
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent; 
  -moz-text-fill-color: transparent;
}
img{
  width:90%;
  height:auto;
  margin:auto;
  display:block;
  border-radius:5px;
  /*box-shadow:5px 5px 0px #424242;*/

}
.box {
    overflow: hidden;
}
.content {
    font-size: 15px;
    line-height: 20px;
    padding: 0 20px;
    text-align: justify;
}
.left {
    float: left;
    width: 30%;SS
}
.left .content {
    border-right: 5px solid #a6b6e3  ;
}
.right {
    float: right;
    width: 70%;
}
</style>

---

# Habilidades 

<div class="box">
  <div class="left">
    <div class="content">
      <p>Python</p>
        <div class="container">
          <div class="skills python">90%</div>
        </div>
      <p>Manejo de Sistemas Linux</p>
        <div class="container">
          <div class="skills Manejo_Linux">60%</div>
        </div>
      <p>bash</p>
        <div class="container">
          <div class="skills bash">70%</div>
        </div>
      <p>PHP</p>
        <div class="container">
          <div class="skills php">50%</div>
        </div>
      <p>MySQL</p>
        <div class="container">
          <div class="skills mysql">70%</div>
        </div>
    </div>
  </div>
  <div class="right">
    <div class="content">
    </div>
  </div>
</div>


<style>
* {box-sizing:border-box}

.container {
  width: 100%; /* Full width */
  background-color: #ddd; /* Grey background */
  border-radius:10px;
  height: 3%;
}
.skills {
  text-align: right; /* Right-align text */
  padding-top: 2px; /* Add top padding */
  padding-bottom: 2px; /* Add bottom padding */
  color: white; /* White text color */
  border-radius:10px;
  height: 20%;
  font-size: xx-small;
}
.python {width: 90%; background-color: #3F448C;} 
.Manejo_Linux {width: 60%; background-color: #5a61bd;} 
.bash {width: 70%; background-color: #3F448C;} 
.php {width: 50%; background-color: #5a61bd;}
.mysql {width: 70%; background-color: #5a61bd;} 
</style>
<style>
h1 {
  background-color: #a6b6e3;
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent; 
  -moz-text-fill-color: transparent;
}
</style>
<style>
  .box {
    overflow: hidden;
}
.content {
    font-size: 15px;
    line-height: 20px;
    padding: 0 20px;
    text-align: justify;
}
.left {
    float: left;
    width: 65%;SS
}
.right {
    float: right;
    width: 35%;
}
</style>

---

# Jesus Lujan

<br>
<div class="box">
  <div class="left">
    <div class="content">
      <br>
      <img src=images/jesus.jpg>
      <br>
      <div id=texto2>Estudiante de 5to ciclo <br>
      de Ingeniería de Sistemas.</div>
    </div>
  </div>
  <div class="right">
    <div class="content">
      <br>
      <h3>Logros y Certificaciones</h3>
      <br>
      <h4>Creando una Trayectoria Profesional en Ciberseguridad</h4>
      <div id="texto">Organización de los Estados Americanos (OEA) </div>
      <h4>Cyber Security Foundation - CSFPC™</h4>
      <div id="texto">Certiprof</div>
      <h4>Google IT Automation Professional Certificate</h4>
      <div id="texto">Coursera</div>
      <h4>Cybersecurity Essentials</h4>
      <div id="texto">Cisco</div>
      <h4>Certificado CyberApocalypse CTF 2021</h4>
      <div id="texto">HackTheBox</div>
      <br>
    </div>
  </div>
</div>

<br>
<div>

</div>

<style>
#texto2{
  text-align:center;
}
h1 {
  background-color: #a6b6e3;
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent; 
  -moz-text-fill-color: transparent;
}
h3{
  font-weight:bold;
  background-color: #444b64;
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent; 
  -moz-text-fill-color: transparent;

}
h4{
  font-weight:bold;
  background-color: #717da5;
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent; 
  -moz-text-fill-color: transparent;
}
img{
  width:90%;
  height:auto;
  margin:auto;
  display:block;
  border-radius:5px;
  /*box-shadow:5px 5px 0px #424242;*/

}
.box {
    overflow: hidden;
}
.content {
    font-size: 15px;
    line-height: 20px;
    padding: 0 20px;
    text-align: justify;
}
.left {
    float: left;
    width: 30%;SS
}
.left .content {
    border-right: 5px solid #a6b6e3  ;
}
.right {
    float: right;
    width: 70%;
}
</style>

---

# Habilidades 

<div class="box">
  <div class="left">
    <div class="content">
      <p>Python</p>
        <div class="container">
          <div class="skills python">80%</div>
        </div>
      <p>Manejo de Sistemas Linux</p>
        <div class="container">
          <div class="skills Manejo_Linux">70%</div>
        </div>
      <p>Latex</p>
        <div class="container">
          <div class="skills bash">50%</div>
        </div>
      <p>Ms Office</p>
        <div class="container">
          <div class="skills php">60%</div>
        </div>
      <p>Pentesting</p>
        <div class="container">
          <div class="skills mysql">60%</div>
        </div>
    </div>
  </div>
  <div class="right">
    <div class="content">
    </div>
  </div>
</div>


<style>
* {box-sizing:border-box}

.container {
  width: 100%; /* Full width */
  background-color: #ddd; /* Grey background */
  border-radius:10px;
  height: 3%;
}
.skills {
  text-align: right; /* Right-align text */
  padding-top: 2px; /* Add top padding */
  padding-bottom: 2px; /* Add bottom padding */
  color: white; /* White text color */
  border-radius:10px;
  height: 20%;
  font-size: xx-small;
}
.python {width: 80%; background-color: #3F448C;} 
.Manejo_Linux {width: 70%; background-color: #5a61bd;} 
.bash {width: 50%; background-color: #3F448C;} 
.php {width: 60%; background-color: #5a61bd;}
.mysql {width: 60%; background-color: #5a61bd;} 
</style>
<style>
h1 {
  background-color: #a6b6e3;
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent; 
  -moz-text-fill-color: transparent;
}
</style>
<style>
  .box {
    overflow: hidden;
}
.content {
    font-size: 15px;
    line-height: 20px;
    padding: 0 20px;
    text-align: justify;
}
.left {
    float: left;
    width: 65%;SS
}
.right {
    float: right;
    width: 35%;
}
</style>