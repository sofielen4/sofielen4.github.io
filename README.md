# sofielen4.github.io
Mi CV Sofi Botto

<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sofi Botto</title>
    <link rel="icon" type="image/x-icon" href="LentesCV.png">
    <link rel="stylesheet" href="EstiloCV.CSS">
    <script>
      function Experiencia() {
        document.getElementById("SegundaParte").innerHTML = "<b>Directora de Mujeres e Igualdad.</b> <br> Municipalidad de Rosario. Agosto 2020-Diciembre 2022. <br><br><b>Asesoría Concejala Verónica Irizar. </b><br> Concejo Municipal de Rosario. Enero-Agosto 2020. <br><br> <b>Integrante Equipo de Fortalecimiento Institucional <br> en Subsec. de Políticas de Género.</b><br> Ministerio de Desarrollo Social. Prov. de Santa Fe. <br>Enero 2018-Diciembre 2019.";
      }
    </script>
    <script>
      function Educacion() {
        document.getElementById("SegundaParte").innerHTML = "<b>Bachillerato Universitario en Relaciones <br>Internacionales</b> - UNR. Finalizado. <br><br> <b>Licenciatura en Relaciones Internacionales</b> <br> UNR. En curso. <br><br><b>Certificado de Educación Polimodal, <br> Producción de Bienes y Servicios.</b> <br>Tecnicatura en Industrias de Proceso.<br>Finalizado.";
      }
    </script>

    <script>
      function Habilidades() {
        document.getElementById("SegundaParte").innerHTML = "<b>Inglés.</b> Nivel Avanzado.<br><br><b>Python.</b> Nivel Básico.<br><br> <b>HTML/CSS.</b> Nivel Básico.<br><br><b>MySQL.</b> Nivel Básico.";
      }
    </script>

</head>
<body>

    <header class="BarraDeNavegacion">
        <nav >  
            <div class="DivBarra">
                <ul class="RedesSociales">
                  <li class="Twitter">
                    <a class="Twitter"  target="_blank"  href="https://twitter.com/SofiBottoLDS"> <img src="LogoTwitter.png" alt="Logo de Twitter" height="50px"></a>
                  </li>
                  <li class="Facebook">
                    <a class="Facebook" target="_blank" href="https://www.facebook.com/SofiBottoLDS"> <img src="LogoFacebook.png" alt="Logo de Facebook" height="50px" >  </a>
                  </li>
                  <li class="Instagram">
                    <a class="Instagram" target="_blank" href="https://www.instagram.com/sofibottolds"> <img src="LogoInstagram.png" alt="Logo de Instagram" height="50px"> </a>
                  </li>
                  <li class="Linkedin">
                    <a class="Linkedin" target="_blank" href="https://www.linkedin.com/in/sofia-botto-b92a47253/"> <img src="LogoLinkedin.png" alt="Logo de Linkedin" height="50px"> </a>
                  </li>
                </ul>
                
                <span id="texto"><b>@sofibottolds</b></span>
              </div>
            </div>
          </nav>

    </header>

    <div id="whatsapp">
      <a href="https://api.whatsapp.com/send/?phone=5493413122052" target="_blank">
        <img src="LogoWhatsapp.png" alt="Logo de Whatsapp" height="80px" style="position: fixed; right: 20px; bottom: 50px; z-index: 100;"> 
      </a>
   </div>

    <main>
        <div class="InformacionPersonal">
            <div id="FotoSofi">
                <img id="ImagenSofi" src="FotoByN.png" alt="Sofi Botto" height="400px">
            </div>


            <div id="Parrafo">
              <p><b>Mi nombre es Sofía Botto. <br>
                 Soy de la ciudad de Rosario, Argentina. <br>
                 Nací el 14 de febrero de 1991. <br>
                 Te invito a conocer más sobre mi.</b>
              </p>
            


            <div id="ElementosCV">
                <button type="button" id="BotonExperiencia" onclick="Experiencia()"><b>Experiencia</b></button>
                <button type="button" id="BotonEducacion" onclick="Educacion()"> <b>Educación </b></button>
                <button type="button" id="BotonHabilidades" onclick="Habilidades()"><b> Habilidades</b></button>  
            </div>


            <div id="SegundaParte">
                <p></p>
            </div>
            </div>
        </div>    

          
            
      
        

    </main>


    <footer class="Footer">
        <p class="float-end"><a href="#">Volver al inicio</a></p>
        <p><b>&middot;Febrero 2023 &middot;</b> </p>
    </footer>
    
</body>
</html>
