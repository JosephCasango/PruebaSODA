
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>

/* ----------------------Barra Principal--------------------------------*/

/* From Uiverse.io by faxriddin20 */ 
.button-BarraPri {
  display: flex;
  background-color: black;
  width: 250px;
  height: 40px;
  align-items: center;
  justify-content: space-around;
  border-radius: 10px;
}

.buttonBarra {
  outline: 0 !important;
  border: 0 !important;
  width: 40px;
  height: 40px;
  border-radius: 50%;
  background-color: transparent;
  display: flex;
  align-items: center;
  justify-content: center;
  color: #fff;
  transition: all ease-in-out 0.3s;
  cursor: pointer;
}

.buttonBarra:hover {
  transform: translateY(-3px);
}

.iconBarra {
  font-size: 20px;
}

/* -------------------Lupa Productos-----------------------------------*/

.cardinal {
  overflow: hidden;
  border-radius: 0.5rem;
    box-shadow: rgb(0,0,0,0.7) 0px 0px 0px ,rgb(0,0,0,0.7) -1px 1px 15px;
  background-color: #fff;
  color: #212121;
}

.imageProduc {
  height: 8rem;
  width: 100%;
  object-fit: cover;
  background-color: rgb(204, 0, 255);
  background-image: linear-gradient(to right, rgb(255, 174, 0), rgb(204, 0, 255));
}

.TextPro {
  padding: 1rem;
  text-align: center;
}

.textOri {
  font-size: 0.875rem;
  line-height: 1.25rem;
  font-weight: 600;
  letter-spacing: 0.1em;
  text-transform: uppercase;
}

.text2Ori {
  margin-top: 1rem;
  font-weight: 900;
  text-transform: uppercase;
}

.text2Ori span:first-child {
  font-size: 2.25rem;
  line-height: 2.5rem;
  font-weight: 900;
}

.text2Ori span:last-child {
  margin-top: 0.5rem;
  display: block;
  font-size: 0.875rem;
  line-height: 1.25rem;
}

.action {
  margin-top: 1rem;
  display: inline-block;
  width: 100%;
  background-color: rgb(0, 0, 0);
  padding-top: 1rem;
  padding-bottom: 1rem;
  border-radius: 4px;
  font-size: 0.875rem;
  line-height: 1.25rem;
  font-weight: 700;
  letter-spacing: 0.1em;
  text-transform: uppercase;
  color: rgba(255, 255, 255, 1);
  text-decoration: none;
}


/* From Uiverse.io by Yaya12085 */ 
.cardinal {
  overflow: hidden;
  border-radius: 0.5rem;
  max-width: 300px;
  background-color: #fff;
  color: #212121;
}

.imageProduc {
  height: 8rem;
  width: 100%;
  object-fit: cover;
  background-color: rgb(204, 0, 255);
  background-image: linear-gradient(to right, rgb(255, 174, 0), rgb(204, 0, 255));
}

.TextPro {
  padding: 1rem;
  text-align: center;
}

.textOri {
  font-size: 0.875rem;
  line-height: 1.25rem;
  font-weight: 600;
  letter-spacing: 0.1em;
  text-transform: uppercase;
}

.text2Ori {
  margin-top: 1rem;
  font-weight: 900;
  text-transform: uppercase;
}

.text2Ori span:first-child {
  font-size: 2.25rem;
  line-height: 2.5rem;
  font-weight: 900;
}

.text2Ori span:last-child {
  margin-top: 0.5rem;
  display: block;
  font-size: 0.875rem;
  line-height: 1.25rem;
}

.actionButon {
  margin-top: 1rem;
  display: inline-block;
  width: 100%;
  background-color: rgb(0, 0, 0);
  padding-top: 1rem;
  padding-bottom: 1rem;
  border-radius: 4px;
  font-size: 0.875rem;
  line-height: 1.25rem;
  font-weight: 700;
  letter-spacing: 0.1em;
  text-transform: uppercase;
  color: rgba(255, 255, 255, 1);
  text-decoration: none;
}

.date {
  margin-top: 1rem;
  font-size: 0.75rem;
  line-height: 1rem;
  font-weight: 500;
  text-transform: uppercase;
  color: rgba(156, 163, 175, 1);
}








/* ------------------------------------------------------*/
* {box-sizing: border-box}

/* Set height of body and the document to 100% */
body, html {
  height: 100%;
  margin: 0;
  font-family: Arial;
}

/* Style tab links */
.tablink {
  background-color: #555;
  color: white;
  float: left;
  border: none;
  outline: none;
  cursor: pointer;
  padding: 14px 16px;
  font-size: 17px;
  width: 25%;
}

.tablink:hover {
  background-color: #777;
}

/* Style the tab content (and add height:100% for full page content) */
.tabcontent {
  color: white;
  display: none;
  padding: 100px 20px;
  height: 100%;
}

#Inicio {background-color: white;}
#News {background-color: white;}
#Contact {background-color: blue;}
#About {background-color: orange;}
</style>
</head>
<body>


<center>

<!-- Barra Casita -->
<div class="button-BarraPri">
  <button class="buttonBarra" class="tablink" onclick="openPage('Inicio')" id="defaultOpen">
    <svg
      class="iconBarra"
      stroke="currentColor"
      fill="currentColor"
      stroke-width="0"
      viewBox="0 0 1024 1024"
      height="1em"
      width="1em"
      xmlns="http://www.w3.org/2000/svg"
    >
      <path
        d="M946.5 505L560.1 118.8l-25.9-25.9a31.5 31.5 0 0 0-44.4 0L77.5 505a63.9 63.9 0 0 0-18.8 46c.4 35.2 29.7 63.3 64.9 63.3h42.5V940h691.8V614.3h43.4c17.1 0 33.2-6.7 45.3-18.8a63.6 63.6 0 0 0 18.7-45.3c0-17-6.7-33.1-18.8-45.2zM568 868H456V664h112v204zm217.9-325.7V868H632V640c0-22.1-17.9-40-40-40H432c-22.1 0-40 17.9-40 40v228H238.1V542.3h-96l370-369.7 23.1 23.1L882 542.3h-96.1z"
      ></path>
    </svg>
  </button>
  
  <!-- Barra Lupa -->
  
  <button class="buttonBarra" class="tablink" onclick="openPage('News')">
    <svg
      class="iconBarra"
      stroke="currentColor"
      fill="none"
      stroke-width="2"
      viewBox="0 0 24 24"
      aria-hidden="true"
      height="1em"
      width="1em"
      xmlns="http://www.w3.org/2000/svg"
    >
      <path
        stroke-linecap="round"
        stroke-linejoin="round"
        d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z"
      ></path>
    </svg>
  </button>
  
  <!-- Barra Creditos -->
  
  
  <button class="buttonBarra" class="tablink" onclick="openPage('Contact')">
    <svg
      class="iconBarra"
      stroke="currentColor"
      fill="currentColor"
      stroke-width="0"
      viewBox="0 0 24 24"
      height="1em"
      width="1em"
      xmlns="http://www.w3.org/2000/svg"
    >
      <path
        d="M12 2.5a5.5 5.5 0 0 1 3.096 10.047 9.005 9.005 0 0 1 5.9 8.181.75.75 0 1 1-1.499.044 7.5 7.5 0 0 0-14.993 0 .75.75 0 0 1-1.5-.045 9.005 9.005 0 0 1 5.9-8.18A5.5 5.5 0 0 1 12 2.5ZM8 8a4 4 0 1 0 8 0 4 4 0 0 0-8 0Z"
      ></path>
    </svg>
  </button>

<!-- Barra Carrito -->

  <button class="buttonBarra" class="tablink" onclick="openPage('About')">
    <svg
      class="iconBarra"
      stroke="currentColor"
      fill="none"
      stroke-width="2"
      viewBox="0 0 24 24"
      stroke-linecap="round"
      stroke-linejoin="round"
      height="1em"
      width="1em"
      xmlns="http://www.w3.org/2000/svg"
    >
      <circle cx="9" cy="21" r="1"></circle>
      <circle cx="20" cy="21" r="1"></circle>
      <path
        d="M1 1h4l2.68 13.39a2 2 0 0 0 2 1.61h9.72a2 2 0 0 0 2-1.61L23 6H6"
      ></path>
    </svg>
  </button>
</div>
</center>







<div id="Inicio" class="tabcontent">
  <h3>Home</h3>
  <p>Home is where the heart is..</p>
</div>




<div id="News" class="tabcontent">


 
<div class="cardinal">
<br>
  <div class="imageProduc"> <img src="https://i.pinimg.com/564x/c4/bf/3e/c4bf3e878a02a0acb2a3a8dab4dc2504.jpg" alt="Girl in a jacket" width="230" height="170"></div>
  <br>
  <div class="TextPro">
    <p class="textOri">
      
    </p>

    <div class="text2Ori">
      <span>
        $25
      </span>
      <span>Coca cola de lata</span>
    </div>

    <a class="actionButon" href="">
      Agregar
    </a>
   <p class="date">
      Coca cola de 350 ml
    </p>
  </div>
</div>
    
  </div>
</div>


</div>





<div id="Contact" class="tabcontent">
  <h3>Contact</h3>
  <p>Get in touch, or swing by for a cup of coffee.</p>
</div>

<div id="About" class="tabcontent">
  <h3>About</h3>
  <p>Who we are and what we do.</p>
</div>

<script>
function openPage(pageName,elmnt,color) {
  var i, tabcontent, tablinks;
  tabcontent = document.getElementsByClassName("tabcontent");
  for (i = 0; i < tabcontent.length; i++) {
    tabcontent[i].style.display = "none";
  }
  tablinks = document.getElementsByClassName("tablink");
  for (i = 0; i < tablinks.length; i++) {
    tablinks[i].style.backgroundColor = "";
  }
  document.getElementById(pageName).style.display = "block";
  elmnt.style.backgroundColor = color;
}

// Get the element with id="defaultOpen" and click on it
document.getElementById("defaultOpen").click();
</script>
   
</body>
</html> 
