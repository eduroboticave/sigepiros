# sigepiros <img src="https://github.com/eduroboticave/sigepiros/blob/main/images/CC.png" style="float: right;" height="25" width="209">
<p><span style="background-color: rgb(255, 255, 255); font-size: 22px; font-family: Arial,sans-serif;">Sistema
Generador de Pistas para Robot Seguidor de L&iacute;neas (SIGEPIROS)</span></p>
<span style="font-size: 14px; font-family: Arial,sans-serif;"><strong>M&oacute;dulo
1: Dise&ntilde;o de piezas para la Pista</strong><strong>&nbsp;</strong></span>
<p></p>
<p style="font-weight: bold;"><span
 style="font-size: 24px; font-family: Arial,sans-serif;"><b>I.-
ANTECEDENDES</b></span></p>
<span style="font-size: 14px; font-family: Arial,sans-serif;"><span
 style="font-weight: bold;">I.1.- Algunas</span>
referencias de <b>competencias</b>&nbsp;robots sigue
l&iacute;neas <b>en
Venezuela.</b> &nbsp;<br>
- En esta competencia desarrollan un circuito siguel&iacute;neas
elaborado con material mdf de dimensiones aproximadas a 2,40 x 2,40
mts; pintado todo de blanco y sobre el mismo una l&iacute;nea de 20
mm de grosor de color negro.</span>
<ol>
  <ol>
  </ol>
  <li><span
 style="font-size: 14px; font-family: Arial,sans-serif;"><span
 style="font-weight: bold;">ULABOTS, Universidad de Los
Andes,Facultad de Ingenier&iacute;a. [Noviembre 2011]</span><br>
    </span><span
 style="font-size: 14px; font-family: Arial,sans-serif;">| <a
 href="https://www.prensa.ula.ve/2011/10/26/estudiantes-y-aficionados-de-la-robotica-competiran-en-ulabots-2011"
 target="_blank">
Noticia institucional<span style="font-style: italic;"></span></a>
| </span><span
 style="font-size: 14px; font-family: Arial,sans-serif;">Portal
de la competencia |</span></li>
  <li><span
 style="font-size: 14px; font-family: Arial,sans-serif;"><span
 style="font-weight: bold;">Competencia Nacional de
Rob&oacute;tica, Universidad Sim&oacute;n Bol&iacute;var,
Grupo de Inteligencia Artificial. [Septiembre 2013]</span><br>
    </span><span
 style="font-size: 14px; font-family: Arial,sans-serif;">|
    <a
 href="https://www.pts.org.ve/index.php/2015-09-28-00-45-05/item/148-competencia-nacional-de-robotica-usb"
 target="_blank">Noticia institucional</a><span
 style="font-style: italic;"> | </span></span><span
 style="font-size: 14px; font-family: Arial,sans-serif;"><a
 href="https://web.archive.org/web/20140409030711/http://ccsbots2013.gia.usb.ve/cat_vel/"
 target="_blank">Portal de la competencia</a> |</span></li>
  <li><span
 style="font-size: 14px; font-family: Arial,sans-serif;"><span
 style="font-weight: bold;">ULABOTS, Universidad de Los
Andes,&nbsp; . [ Noviembre 2014]</span><br>
    </span><span
 style="font-size: 14px; font-family: Arial,sans-serif;">|
    <a
 href="https://comunicacioncontinua.com/ulabots-2014-supera-cifra-de-participantes-en-la-competencia-nacional-de-robotica/"
 target="_blank">Noticia institucional</a><span
 style="font-style: italic;"> | </span></span><span
 style="font-size: 14px; font-family: Arial,sans-serif;"><span
 style="font-style: italic;"></span></span><span
 style="font-size: 14px; font-family: Arial,sans-serif;"><a
 href="https://www.ing.ula.ve/ulabots/competencias/categoria-velocistas-con-pista-fantasma-reglamento/"
 target="_blank">Reglas de la competencia</a> |</span><span
 style="font-size: 14px; font-family: Arial,sans-serif;"></span></li>
  <li><span
 style="font-size: 14px; font-family: Arial,sans-serif;"><span
 style="font-weight: bold;">UNETBOTS, Universidad Nacional
Experimental del T&aacute;chira. [Octubre 2015]</span><br>
Categor&iacute;as Desaf&iacute;o, Sumo, Velocistas.<br>
Equipo universitarios.<br>
    </span><span
 style="font-size: 14px; font-family: Arial,sans-serif;">|
    <a
 href="http://www.unet.edu.ve/noticia-unet/3342-se-dio-inicio-formal-a-unetbots-2015.html"
 target="_blank">Noticia institucional</a><span
 style="font-style: italic;"> | </span></span><span
 style="font-size: 14px; font-family: Arial,sans-serif;"><span
 style="font-style: italic;"></span></span><span
 style="font-size: 14px; font-family: Arial,sans-serif;"><a
 href="http://www.unet.edu.ve/noticia-unet/3313-v-competencia-nacional-de-robotica-tiene-como-sede-a-la-unet.html"
 target="_blank">Reglas de la competencia</a> |</span><span
 style="font-size: 14px; font-family: Arial,sans-serif;"></span></li>
  <li><span
 style="font-size: 14px; font-family: Arial,sans-serif;"><span
 style="font-weight: bold;">Conferencia Nacional de
Computaci&oacute;n, Inform&aacute;tica y Sistemas (CONSISA),
Universidad de Los Andes. [Noviembre 2018]</span><br>
    </span><span
 style="font-size: 14px; font-family: Arial,sans-serif;">|
    <a href="https://concisa.net.ve/2018/" target="_blank">Noticia
institucional</a><span style="font-style: italic;">
| </span></span><span
 style="font-size: 14px; font-family: Arial,sans-serif;"><span
 style="font-style: italic;"></span></span><span
 style="font-size: 14px; font-family: Arial,sans-serif;"><a
 href="https://www.concisa.net.ve/2018/wp-content/uploads/sites/7/2018/06/velocista.pdf"
 target="_blank">Reglas de la competencia</a> |</span><span
 style="font-size: 14px; font-family: Arial,sans-serif;"></span></li>
  <li><span
 style="font-size: 14px; font-family: Arial,sans-serif;"><span
 style="font-weight: bold;">I Competencia Tachirense de
Rob&oacute;tica, Universidad
Nacional Experimental del T&aacute;chira, Laboratorio de
prototipos. [Noviembre 2024]</span><br>
    </span><span
 style="font-size: 14px; font-family: Arial,sans-serif;">|
    <a
 href="http://www.unet.edu.ve/eventos-y-noticias-externas/5545-en-noviembre-se-realizara-la-i-competencia-tachirense-de-robotica-en-la-unet.html"
 target="_blank">Noticia institucional</a><span
 style="font-style: italic;"> | </span></span><span
 style="font-size: 14px; font-family: Arial,sans-serif;"><a
 href="https://protolab.my.canva.site/tachibots" target="_blank">Portal
de la competencia</a> |</span></li>
  <li><span
 style="font-size: 14px; font-family: Arial,sans-serif;"><span
 style="font-weight: bold;">ExpoRobotik - Competencia Grand
Prix - Colegio de Ingenieros del Estado Carabobo (CIEDEC). [Noviembre
2024]</span><br>
|
    <a
 href="https://www.instagram.com/ceidec_civ/p/DAGdvpEOtgs/?hl=es"
 target="_blank">Noticia institucional</a><span
 style="font-style: italic;"> |&nbsp;</span></span><span
 style="font-size: 14px; font-family: Arial,sans-serif;"></span></li>
</ol>
<span style="font-size: 14px; font-family: Arial,sans-serif;"><span
 style="font-weight: bold;">I.2.- Algunas</span>
referencias
a <span style="font-weight: bold;">experiencias
did&aacute;cticas</span> el &aacute;mbito
pedag&oacute;gico asociadas a "<span style="font-weight: bold;">laberintos</span>"
o "<span style="font-weight: bold;">pistas
siguel&iacute;neas</span>" para la ense&ntilde;anza de la
rob&oacute;tica en la escuela. <br>
- Utilizan una metodolog&iacute;a donde&nbsp;arman el circuito
"siguel&iacute;neas" utilizando piezas de un tama&ntilde;o
cuadrado (Por ejemplo 21x21 cm)&nbsp; color blanco y con una
l&iacute;nea negra de 20mm.</span>
<ol>
  <li><span
 style="font-size: 14px; font-family: Arial,sans-serif;"><span
 style="font-weight: bold;">Exposici&oacute;n Itinerante
- Escuela
de Educaci&oacute;n, Coodinaci&oacute;n de
Tecnolog&iacute;a Educativa, Proyecto La Rob&oacute;tica va a
la Escuela [Junio 2008]</span><br>
Laberinto de 9 cuadr&iacute;culas (3x3); cada regilla tiene una
dimensi&oacute;n de 21x21cm y una&nbsp;l&iacute;nea, curva,
semicurva de color negro con un ancho de 2 cm. Los ni&ntilde;os
arman el rompecabezas y luego programan el robot para que salga del
punto de inicio, recorra a l&iacute;nea y estacione en el punto de
llegada.<br>
https://edurobotica.blogspot.com/search/label/Exposiciones%20Itinerantes
    </span></li>
  <li><span
 style="font-size: 14px; font-family: Arial,sans-serif; font-weight: bold;">Tablero
de pr&aacute;cticas Encuentro de Rob&oacute;tica Educativa - </span><span
 style="font-size: 14px; font-family: Arial,sans-serif;"><span
 style="font-weight: bold;">Escuela
de Educaci&oacute;n, Coodinaci&oacute;n de
Tecnolog&iacute;a Educatiiva [ Noviembre 2012]&nbsp;</span><br>
Dise&ntilde;o de pistas siguelineas de 4 cuadr&iacute;culas
(2x2) cada cuadr&iacute;cula es&nbsp;</span><span
 style="font-size: 14px; font-family: Arial,sans-serif;">una
cartulina en kilo 80x100cm;</span><span
 style="font-size: 14px; font-family: Arial,sans-serif;">
tiene fondo blanco y curv&iacute;neas color negro.&nbsp; Al
unir las piezas, se obtiene
un circuito cerrado de la pista. <br>
https://edurobotica.blogspot.com/search/label/InterEscolar%20Rob%C3%B3tica%20Educativa
    </span><span
 style="font-size: 14px; font-family: Arial,sans-serif;"></span></li>
  <li><span
 style="font-size: 14px; font-family: Arial,sans-serif;"><span
 style="font-weight: bold;">2018 Plantilla para la
creaci&oacute;n de circuitos para robots siguel&iacute;neas -
Dani Sanz / Juegosrobotica</span><br>
https://juegosrobotica.es/plantillas-siguelineas&nbsp;</span></li>
</ol>
<ol>
  <ol>
  </ol>
</ol>
<span style="font-size: 24px; font-family: Arial,sans-serif;"><b>II.-
PROPUESTA DE ARMADO PISTA CIRCUITO SIGUE L&Iacute;NEAS<br>
</b></span><span
 style="font-size: 14px; font-family: Arial,sans-serif;"><span
 style="font-weight: bold;">II.1.- </span>Se plantea
una metodolog&iacute;a que permita: <br>
</span>
<ul>
  <li><span
 style="font-size: 14px; font-family: Arial,sans-serif;">Crear,
armar un circuito al momento, utilizando piezas que se ensamblan entre
s&iacute; y forman la pista.</span></li>
  <li><span
 style="font-size: 14px; font-family: Arial,sans-serif;">Reutilzar
las piezas para otras formas de armar un circu&iacute;to.</span></li>
  <li><span
 style="font-size: 14px; font-family: Arial,sans-serif;">De
f&aacute;cil creaci&oacute;n y producci&oacute;n.</span></li>
  <li><span
 style="font-size: 14px; font-family: Arial,sans-serif;">Que
se pueda ir ampliando cada tipo de pieza (l&iacute;neas, curvas,
curvil&iacute;neas) para ir incorporando a la lista de piezas
existentes.<br>
    </span></li>
</ul>
<span style="font-size: 14px; font-family: Arial,sans-serif;"></span>
<p style="font-weight: bold;"><span
 style="font-size: 24px; font-family: Arial,sans-serif;"><b>III.-
PIEZAS DE LA PISTA</b></span></p>
<p style="font-weight: bold;"><span
 style="font-size: 14px; font-family: Arial,sans-serif;"><span
 style="font-weight: bold;">III.1.-</span><span
 style="font-weight: normal;"><span
 style="font-weight: bold;"> </span>Detalles&nbsp;</span></span></p>
<p style="font-weight: bold;"><span
 style="font-size: 14px; font-family: Arial,sans-serif;"><span
 style="font-weight: normal;">Se debe destacar un valor
&uacute;nico asociado a este proyecto, la forma de uni&oacute;n
de las piezas es la siguiente:&nbsp;</span></span></p>
<ul>
  <li><span
 style="font-size: 14px; font-family: Arial,sans-serif;"><span
 style="font-weight: normal;">Cada pieza tiene ocho encajes
para unirse con otras piezas en cada uno de sus cuatro lados.</span></span></li>
  <li><span
 style="font-size: 14px; font-family: Arial,sans-serif;"><span
 style="font-weight: normal;">La uni&oacute;n se realiza
a trav&eacute;s de&nbsp;un eslab&oacute;n especial
dise&ntilde;ado para este proyecto.</span></span></li>
  <li><span
 style="font-size: 14px; font-family: Arial,sans-serif;"><span
 style="font-weight: normal;">Confesamos que esto es un
innovaci&oacute;n donde no hemos encontrado referencia alguna.<br>
    </span></span></li>
</ul>
<img alt="-.-"
 src="https://github.com/eduroboticave/sigepiros/blob/main/images/Piezas_unidas.jpg">
<ul>
  <li><span
 style="font-size: 14px; font-family: Arial,sans-serif;">Materiales
posibles: carton en kilo, mdf crudo, laminado mdf color blanco mate.</span></li>
  <li><span
 style="font-size: 14px; font-family: Arial,sans-serif;">Dimensiones
iniciales: 35cm x 35cm x 0,5cm.</span></li>
  <li><span
 style="font-size: 14px; font-family: Arial,sans-serif;">Opciones
de elaboraci&oacute;n:&nbsp;</span></li>
  <ul>
    <li><span
 style="font-size: 14px; font-family: Arial,sans-serif;">Imprimir
la pieza en papel, cartulina blanca y se adhiere al material resistente
(cart&oacute;n, madera, otro).</span></li>
    <li><span
 style="font-size: 14px; font-family: Arial,sans-serif;">Grabado
y cortado l&aacute;ser de la pieza en mdf crudo o laminado mdf
color mate de 5mm de espesor.</span></li>
    <li><span
 style="font-size: 14px; font-family: Arial,sans-serif;">Grabado
y cortado l&aacute;ser de la pieza en cart&oacute;n en kilo (3
mm de espesor).</span></li>
    <li><span
 style="font-size: 14px; font-family: Arial,sans-serif;">Cada
opci&oacute;n requerir&aacute; una metodolog&iacute;a,
acciones, configuraciones especificas para su
producci&oacute;n.&nbsp;</span></li>
  </ul>
  <li><span
 style="font-size: 14px; font-family: Arial,sans-serif;">En
la versi&oacute;n 1.0 del sistema, presentamos 18 piezas con el
siguiente dise&ntilde;o de l&iacute;neas, curvas,
curvil&iacute;neas</span></li>
</ul>
<img alt="piezas1"
 src="https://github.com/eduroboticave/sigepiros/blob/main/images/DisenoPiezas.PNG">
<ul>
  <li><span
 style="font-size: 14px; font-family: Arial,sans-serif;">Posteriormente,
agrupamos las&nbsp;piezas por niveles de dificultad, de la
siguiente manera:</span></li>
  <ul>
    <li><span
 style="font-size: 14px; font-family: Arial,sans-serif;">Nivel
dificultad I: seis piezas<br>
      <img alt="n1"
 src="https://github.com/eduroboticave/sigepiros/blob/main/images/Nivel1.png"></span></li>
    <li><span
 style="font-size: 14px; font-family: Arial,sans-serif;">Nivel
dificultad II: siete piezas<br>
      <img alt="n2"
 src="https://github.com/eduroboticave/sigepiros/blob/main/images/Nivel2.png"></span></li>
    <li><span
 style="font-size: 14px; font-family: Arial,sans-serif;">Nivel
dificultad III: cinco piezas<br>
      <img alt="n3"
 src="https://github.com/eduroboticave/sigepiros/blob/main/images/Nivel3.png"><br>
      </span></li>
  </ul>
  <li><span
 style="font-size: 14px; font-family: Arial,sans-serif;">Para
la elaboraci&oacute;n de las piezas, se ofrecen los archivos
fuentes en dos formatos: svg (corte y grabado l&aacute;ser) y jpg
(impresi&oacute;n)</span></li>
</ul>


