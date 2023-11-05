# Fonti96.github.io

Anàlisi del Projecte:

Target user profile:
En aquest cas, era un projecte per mi, les necessitats que tenia eren, fer el projecte del meu currículum amb el html, css i figma. Tot això assolint els objectius proposats pel professor.

Information architecture:
Un dels passos més importants que he pres és l'organització lògica i coherent de la informació. He creat una estructura de navegació que és intuïtiva i fàcil d'entendre, assegurant que els usuaris puguin accedir al currículum obtinguin la meva informació que necessitin fàcilment i ràpidament.

Visual design:
En aquest apartat, he explorat els diferents aspectes visuals del projecte que podia fer. He seleccionat una paleta de colors que reflecteixi l'esperit del projecte, ja que és personal i representa el meu color preferit i he definit les tipografies i els estils de text fàcils d'entendre i bàsics.

Conclusions:
Durant aquesta projecte, he arribat a diverses conclusions . He trobat els punts que em costen més d'entendre del HTML i css, però realment tot m'ha servit per apendre i millorar, i al finalitzar el projecte he identificat possibles millores que es podrien fer del currículum. Aquesta projecte em servirà com a guia per a seguir creant projectes del estil i millorar-los amb el desenvolupament que he après.


Link to the Figma project:
https://www.figma.com/file/BNhHhHr13otSg2kPLLLTLH/Curriculum?type=design&node-id=0%3A1&mode=design&t=C0U37DdhoIEGFU2l-1


<!DOCTYPE html>
<html>

<head>
    <meta charset="UTF-8">
    <title>Currículum de Marc Font Marqués</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>

    <div id="left-side">
        <h1 id = "Nom">Marc Font Marqués</h1>
        <img src="foto_carnet.jpg" alt="Foto de perfil" style="width: 375px; ">
        <section id="contacte">
            
            <h2>Perfil</h2>
            <ul>
                <li><b>Mail</b><br> marcfont3@gmail.com</li>
                <li><b>Població</b><br> Lloret de Mar</li>
                <li><b>Adreça</b><br> c/ Pere Serafí</li>
                <li><b>Teléfon</b><br> 640208243</li>
                <li><b>DNI</b><br> 45967369Y</li>
            </ul>
        </section>

        <section id="habilitats">
            <h2>Habilitats</h2>
            <ul>
                <li>Facilitat d'aprenentatge</li>
                <li>Adaptabilitat</li>
                <li>Resiliència</li>
                <li>Col·laboració efectiva</li>
                <li>Presa de decisions informades</li>    
            </ul>
        </section>

        <section id="hobbies">
            <h2>Hobbies</h2>
            <ul>
                <li>Jugador d'hoquei patins</li>
                <li>Aficonat al fútbol</li>
                <li>Fòrmula 1</li>
                <li>Videojocs</li>
                <li>Amant de las películas/series de misteri</li>
            </ul>
        </section>
</div>

<div id="right-side">
    
    <section id="sobre">
        <h2>Sobre mi</h2>
        <p>Sóc un estudiant apassionat de la programació amb una àmplia varietat d'experiències i coneixements.
            Estic buscant oportunitats per aprendre i créixer com a desenvolupador de programari. Em preocupa la responsabilitat social i la tecnologia. Estic interessat en oportunitats on pugui aplicar les meves habilitats per a projectes que tinguin un impacte positiu en la societat o l'entorn.</p>
    </section>

    <section id="estudis">
        <h2>Estudis</h2>
        <ul id="llista-estudis">
            <li>
                <span id="any-estudis">2008/09 - 2015/06</span>
                <span id="text-estudis">
                    <b>Graduat en Educació Primària</b><br>
                    <i>Col·legi Immaculada Concepció, Lloret de Mar</i></b><br>
                </span>
            </li>
            <li>
                <span id="any-estudis">2015/09 - 2018/06</span>
                <span id="text-estudis">
                    <b>Graduat en Educació Secundària Obligatòria</b><br>
                    <i>Col·legi Immaculada Concepció, Lloret de Mar</i></b><br>
                </span>
            </li>
            <li>
                <span id="any-estudis">2018/09 - 2021/06</span>
                <span id="text-estudis">
                    <b>Graduat en Batxillerat Tecnològic</b><br>
                    <i>Col·legi Immaculada Concepció, Lloret de Mar</i></b><br>
                </span>
            </li>
            <li>
                <span id="any-estudis">2021/09 - Actualitat</span>
                <span id="text-estudis">
                    <b>Grau en Enginyeria Informàtica</b><br>
                    <i>Universitat de Girona, Girona</i></b><br>
                </span>
            </li>
        </ul>
    </section>
    
    <section id="experiencia">
        <h2>Experiència Laboral</h2>
        <ul>
            <li>
                <b>Monitor en un Casal d'Estiu de Hoquei Patins</b><br>
                <i>Campus Tecnificació Club Hoquei Lloret, Lloret de Mar</i></br>
            </li>
            <li>
                <b>Instal·lador de Toldos, Cortines i Pérgoles</b><br>
                <i>Font Decoració, Lloret de Mar</i></br>
            </li>
        </ul>
    </section>


    <section id="llengues">
        <h2>Idiomes</h2>
        <ul>
            <li>Català   ★★★★★</li>
            <li>Castellà ★★★★★</li>
            <li>Anglès   ★★★☆☆</li>
            <li>Francès  ★☆☆☆☆</li>
        </ul>
    </section>

    <section id="software">
        <h2>Software</h2>
        <ul>
            <li>C++  ★★★★★</li>
            <li>C    ★★☆☆☆</li>
            <li>Java ★★★☆☆</li>
            <li>JavaScript ★★★☆☆</li>
            <li>HTML ★★★☆☆</li>
            <li>SQL  ★★★★☆</li>
            <li>PHP  ★★★☆☆</li>
            
        </ul>
    </section>

    <section id="projectes">
        <h2>Projectes</h2>
        <ul>
            <li>Aplicació eco amb sockets TCP/IP. <a href="https://docs.google.com/document/d/1ieZ7qgtIP1ueaywescTZfVv9MGPGeBi-/edit?usp=sharing&ouid=110529942049654006963&rtpof=true&sd=true">més informació.</a></li> 
            <li>L'Empresa i el seu entorn. <a href="https://docs.google.com/document/d/15uJzfIDGPRmJXlitvWZ_3EzZwIE30DFPxFmhLWVallg/edit?usp=sharing">més informació.</a></li> 
        </ul>
    </section>

    
</div>

</body>

</html>

