# Will-Kali
Will-kali es una distribución personalizada de Kali Linux en VMware 17, basada en Debian, enfocada en mejorar las habilidades OSINT para la investigación de personas, ofreciendo herramientas especializadas en recopilar y analizar información de fuentes abiertas.
![imagen](https://github.com/ciberlabpruebamaster/Will-Kali/assets/165423933/09f031a3-92a7-4e28-a3bd-dd3be476e8bc)
# 1. Navegadores Web
![2](https://github.com/ciberlabpruebamaster/Will-Kali/assets/165423933/1fb44977-02e7-4c63-aa60-b1cd80390ecd)

Will Kali cuenta con 4 navegadores imprescindindibles para cualquier analista. Para mí, por orden de importancia:

#### 1º. Brave.
#### 2º. Chromium.
#### 3º. Firefox.
#### 4º. Tor (imprescindible en DeepWeb).

### 1.1. FIREFOX 

![image](https://github.com/ciberlabpruebamaster/Will-Kali/assets/165423933/5806a5e4-65c7-4363-8f96-68a0793e2814)

Importante destacar las extensiones que se usan en este NAVEGADOR: 

![image](https://github.com/ciberlabpruebamaster/Will-Kali/assets/165423933/ee1548fc-503e-4118-a0d0-12a01768e6f2)

-	Canvas Defender
-	IG Downloader - Instagram Downloader
-	CyberGhost VPN Free Proxy
-	Wayback Machine 
-	Resurrect Pages
-	Surf Security 
-	Shodan 
-	Web Scraper - Free Web Scraping 
-	User-Agent Switcher and Manager 
-	Search by Image
-	Hunter - Email Finder Extension

### 1.2. BRAVE y CHROMIUM

![image](https://github.com/ciberlabpruebamaster/Will-Kali/assets/165423933/1d78842a-190b-4a77-8885-16b78c6a19f3)
![image](https://github.com/ciberlabpruebamaster/Will-Kali/assets/165423933/14dc0b83-d4f2-4e2d-8060-0c069f92c49a)

Estos 2 NAVEGADORES, al estar ambos basados en tecnología muy similar, comparten idénticas extensiones: 


![image](https://github.com/ciberlabpruebamaster/Will-Kali/assets/165423933/e3a81866-28e2-4e47-961e-ff8f357d7499)

-	BlackboxAI
-	Copyfish Free OCR Software
-	DeepL Translate
-	Instant Data Scraper
-	JSON Formatter
-	Link Gopher
-	Netcraft Extension 
-	Proxy SwitchySharp
-	Reader Mode
-	SquareX : Be Secure, Anonymous, Private Online
-	Temp Mail - Disposable Temporary Email 
-	UltraSurf Security, Privacy & Unblock VPN
-	Unstoppable Extension
-	User-Agent Switcher for Chrome
-	What font - font Finder
-	Alicent for ChatGPT 
-	Url Shortener

### 1.3. TorBrowser

![image](https://github.com/ciberlabpruebamaster/Will-Kali/assets/165423933/cbaeca5f-bd72-4975-8037-9db29da0d6da)

En TorBrowser, no se admiten extensiones para preservar el anonimato y la privacidad, ya que su uso podría comprometer estas características fundamentales. No son necesarias de hecho.

# 2. MARCADORES PARA NAVEGADORES
En esta sección, se destaca la importancia de contar con un sistema de marcadores organizados para la navegación efectiva en el ámbito de la ciberinteligencia. Se recomienda el uso de la plataforma https://start.me/ para crear un repositorio de marcadores accesible desde cualquier navegador compatible, como Brave y Chromium. Los marcadores se organizan por familias para facilitar su acceso y utilización.

### 2.1. OSINT METADATOS ONLINE
Se proporciona una lista de herramientas y recursos en línea para analizar metadatos de imágenes, lo que incluye la identificación y eliminación de metadatos, así como la realización de búsquedas avanzadas utilizando operadores booleanos. Entre las herramientas destacadas se encuentran:
- https://www.dcode.fr/exif-data
  
  ![image](https://github.com/ciberlabpruebamaster/Will-Kali/assets/165423933/65e189f0-9deb-469a-84c0-7c8f2e36de15)

- https://exifdata.com/
  
  ![image](https://github.com/ciberlabpruebamaster/Will-Kali/assets/165423933/03efae84-fdc2-40c8-a458-45f3b0c082f0)

- https://www.metadata2go.com/view-metadata
  
  ![image](https://github.com/ciberlabpruebamaster/Will-Kali/assets/165423933/b9a00663-3d48-41d9-b0ac-eaf75e4a3dbd)

- https://exifinfo.org
  
  ![image](https://github.com/ciberlabpruebamaster/Will-Kali/assets/165423933/ec076ef5-1fe1-4906-93f0-f0124db7f856)

- https://www.stolencamerafinder.com/
  
  ![image](https://github.com/ciberlabpruebamaster/Will-Kali/assets/165423933/85f2abf2-1386-46d4-84c7-cf089f4b1abd)

  
Estas herramientas permiten analizar metadatos de imágenes y encontrar cámaras fotográficas robadas mediante el análisis de los metadatos EXIF.

### 2.2. INFORMACION IP + DNS ONLINE
Se presenta una lista de herramientas y servicios en línea relacionados con la seguridad informática y las pruebas de penetración. Destacan:
- https://hackertarget.com/
  
  ![image](https://github.com/ciberlabpruebamaster/Will-Kali/assets/165423933/016e44ba-1287-42f1-b258-6cf8b8c60fc4)

- https://www.shodan.io/
  
![image](https://github.com/ciberlabpruebamaster/Will-Kali/assets/165423933/aeff718d-c6a0-4e84-a0c1-ce2419d36f52)

Estas plataformas ofrecen diversas herramientas para escanear puertos, detectar vulnerabilidades, enumerar subdominios, explorar dispositivos conectados a Internet y monitorizar la infraestructura de red.

### 2.3. API Y HERRAMIENTAS DE ANÁLISIS
Esta sección se centra en las herramientas y servicios disponibles para el análisis de información en línea, así como en la integración de la funcionalidad de Shodan a través de su API. Se describen los siguientes aspectos:

### 2.3.1. API DE SHODAN
Se destaca la API ofrecida por Shodan, que permite a los desarrolladores integrar la funcionalidad de Shodan en sus propias aplicaciones y herramientas. Esto les permite realizar búsquedas y obtener información sobre dispositivos conectados a Internet de manera programática.
### 2.3.2. HERRAMIENTAS DE ANÁLISIS DNS
Se mencionan varias herramientas en línea, como DNSDumpster, Netcraft y Robtex, que proporcionan funcionalidades para recopilar información relacionada con nombres de dominio y sistemas de nombres de dominio (DNS). Estas herramientas son útiles para investigadores de seguridad y profesionales de ciberseguridad para obtener información sobre la infraestructura de dominios y ayudar en la identificación de posibles problemas de seguridad.
### 2.3.3. HERRAMIENTAS DE ANÁLISIS DE REDES
Se describen herramientas como Greynoise y FOFA, que ofrecen funcionalidades para el análisis de redes y la recopilación de datos sobre actividad maliciosa en Internet. Estas herramientas proporcionan visualizaciones de datos en tiempo real sobre amenazas en línea y ayudan a las organizaciones a protegerse contra amenazas cibernéticas.

# 3. HERRAMIENTAS DE ANÁLISIS ONLINE
Esta parte destaca una serie de herramientas en línea que son útiles para analizar y escanear URLs en busca de posibles amenazas de seguridad, así como para obtener información detallada sobre direcciones IP y dominios en línea. Aquí están las herramientas mencionadas:
### 3.1. urlscan.io
- Herramienta en línea para analizar y escanear URLs en busca de contenido malicioso, scripts sospechosos y otras amenazas de seguridad.
- Características incluyen análisis de contenido, verificación de la reputación del dominio e IP, captura de pantalla y detalles detallados del análisis realizado.
### 3.2. crt.sh
- Plataforma que proporciona acceso a registros de certificados SSL/TLS utilizados para establecer conexiones seguras en línea.
- Funciones incluyen búsqueda de certificados, historial de certificados y análisis de seguridad de sitios web.
### 3.3. ping.pe
- Servicio que permite a los usuarios realizar pruebas de ping a direcciones IP o nombres de dominio desde múltiples ubicaciones en todo el mundo.
- Útil para evaluar la latencia y la estabilidad de la conexión a una dirección IP o dominio desde diferentes ubicaciones geográficas.
### 3.4. web-check.xyz
- Herramienta OSINT todo en uno para verificar rápidamente los datos de un sitio web, incluyendo información de IP, cadena SSL, registros DNS, cookies, encabezados, métricas de calidad y más.
### 3.5. app.netlas.io
- Plataforma que proporciona herramientas para la investigación de seguridad y la recopilación de datos relacionados con la infraestructura de Internet.
- Permite a los usuarios obtener información detallada sobre un nombre de dominio o una dirección IP, incluidos registros DNS, información de geolocalización y detalles del propietario.
### 3.6. ipinfo.io y myip.ms
- Ofrecen información detallada sobre direcciones IP, incluyendo ubicación geográfica aproximada, ISP, país, ciudad, código postal, latitud, longitud y más.
- Además, ipinfo.io proporciona una API para integrar la funcionalidad de consulta de IP en aplicaciones y sistemas.
### 3.7. grabify.link e iplogger.org
- Servicios de acortamiento de URL con análisis avanzados para el tráfico a través de sus enlaces.
- Aunque útiles para compartir enlaces cortos, han sido utilizados con fines de phishing y rastreo de ubicación sin consentimiento, lo que ha generado preocupaciones sobre la privacidad de los usuarios en línea.

# 4. WHOIS Y DOMINIOS
En esta sección, se presentan diversas herramientas y servicios en línea relacionados con la consulta de datos WHOIS para nombres de dominio y direcciones IP, así como otras funcionalidades relacionadas con la infraestructura de Internet y el análisis de amenazas. A continuación, se detallan las herramientas mencionadas:
### 4.1. whois.whoisxmlapi.com
- Proporciona acceso a datos de WHOIS para nombres de dominio y direcciones IP.
- Permite buscar información sobre la titularidad de un nombre de dominio, incluyendo detalles sobre el registrante, la fecha de registro y vencimiento, servidores de nombres, información de contacto, entre otros.
### 4.2. whois.domaintools.com
- Ofrece acceso a información de WHOIS para nombres de dominio, permitiendo a los usuarios buscar detalles como el registrante, la fecha de registro, vencimiento, registrador, servidores de nombres y más.
- También proporciona herramientas adicionales para investigar la historia de un dominio y realizar análisis avanzados sobre su propiedad y uso.
### 4.3. whoxy.com
- Servicio en línea que brinda acceso a datos de WHOIS para nombres de dominio, incluyendo detalles sobre el registrante, fecha de registro, vencimiento, registrador, servidores de nombres, y más.
- Ofrece características adicionales como historial de WHOIS, búsqueda inversa de WHOIS y búsqueda masiva de WHOIS.
### 4.4. nslookup.io
- Ofrece una variedad de herramientas de redes y DNS.
- Permite obtener información sobre la configuración de DNS y la infraestructura de red asociada con una dirección IP, nombre de dominio o registro DNS específico.
### 4.5. onyphe.io
- Plataforma de inteligencia de amenazas en línea que recopila y analiza datos de seguridad cibernética de diversas fuentes.
- Ofrece funciones como recopilación de datos, análisis de amenazas, investigación de seguridad y una API para integrar datos de inteligencia de amenazas en herramientas y sistemas de seguridad cibernética.
# 5. BÚSQUEDA PERSONAS Y PERFILES
En esta sección se presentan herramientas y plataformas en línea que permiten buscar información sobre personas y perfiles en internet. A continuación, se detallan las herramientas mencionadas:
### 5.1. search4faces.com
- Es un formulario de búsqueda de fotos de perfil de VKontakte.
- Utiliza reconocimiento facial, inteligencia artificial y aprendizaje automático para realizar una búsqueda inversa de imágenes.
- Proporciona enlaces al perfil de la persona encontrada en redes sociales como vk.com, ok.ru, entre otras.
### 5.2. webmii.com
- Proporciona información sobre la presencia en internet de una persona o entidad.
- Recopila datos de diversas fuentes en línea, como redes sociales, blogs, sitios web personales y profesionales, para organizarlos en un perfil de usuario.
- Permite buscar un resumen de la presencia en línea de una persona, incluyendo enlaces a perfiles en redes sociales, menciones en blogs y más.
### 5.3. spokeo.com
- Ofrece acceso a información pública y datos de búsqueda de personas.
- Recopila datos de fuentes públicas como registros gubernamentales, redes sociales y directorios telefónicos para crear perfiles de personas.
- Proporciona detalles de contacto, historial de direcciones, perfiles en redes sociales, historial laboral y educativo, historial criminal (si está disponible públicamente), fotos y videos asociados con la persona.
Estas herramientas pueden ser útiles para buscar información sobre individuos, monitorear la reputación en línea y obtener detalles de contacto, entre otros usos. 
# 6. CACHE E HISTÓRICOS
En esta sección, se presentan herramientas y servicios en línea relacionados con el acceso a versiones en caché de páginas web y la preservación de la historia de internet. A continuación, se detallan las herramientas mencionadas:
### 6.1. cachedview.nl
- Ofrece acceso a versiones en caché de páginas web.
- Permite a los usuarios ingresar una URL de página web y buscar versiones en caché disponibles.
- Proporciona acceso a versiones anteriores de páginas web, útil cuando una página ha sido eliminada o actualizada.
- Puede servir como una herramienta de recuperación de contenido para acceder a páginas web que de otro modo no estarían disponibles.
### 6.2. archive.org (The Wayback Machine)
- Proyecto sin ánimo de lucro dedicado a preservar una copia de páginas web pasadas y presentes de internet.
- Permite a los usuarios buscar y ver versiones archivadas de sitios web en diferentes momentos a lo largo del tiempo a través de la Wayback Machine.
- Alberga una amplia colección de archivos multimedia, como música, películas, libros, imágenes y programas de televisión, disponibles de forma gratuita.
- Hospeda varios proyectos adicionales, como el Proyecto Gutenberg, el Archivo de Audio y el Archivo de Películas.
- Financiado por donaciones y apoyado por voluntarios que contribuyen con fondos y ayudan con la digitalización y catalogación de materiales.
Estas herramientas son útiles para acceder a versiones anteriores de páginas web, recuperar contenido eliminado o actualizado, y preservar la historia de internet para futuras consultas

# 7. LEAKS Y FUGAS
En esta sección, se presentan herramientas y servicios en línea relacionados con la detección y verificación de fugas de datos. A continuación, se describen las herramientas mencionadas:
### 7.1. pastebin.com
- Es un sitio web que permite a los usuarios compartir texto de forma anónima.
- Los usuarios pueden pegar cualquier tipo de texto en el sitio y generar un enlace único para compartirlo con otros.
- Ofrece configuraciones de privacidad para los paste, que pueden ser públicos, no listados o privados.
- Permite establecer una duración para los paste, después de la cual el contenido se eliminará automáticamente.
- Admite resaltado de sintaxis para varios lenguajes de programación y marcado.
- Proporciona funciones de búsqueda para encontrar paste existentes en el sitio web.
### 7.2. leak-lookup.com
- Es un servicio en línea especializado en buscar y verificar si una dirección de correo electrónico o una contraseña ha sido comprometida en una filtración de datos.
- Utiliza una base de datos actualizada de información filtrada y comprometida para ayudar a los usuarios a determinar si sus credenciales están en riesgo.
- Permite buscar direcciones de correo electrónico y contraseñas para verificar si han sido comprometidas.
- Proporciona información detallada sobre la filtración en la que se encontró la dirección de correo electrónico o la contraseña, incluyendo el sitio web afectado y la fecha de la filtración.
- Ofrece la opción de suscribirse para recibir notificaciones por correo electrónico si se encuentra una dirección de correo electrónico asociada con una filtración de datos en el futuro.
Estas herramientas son útiles para detectar y verificar la presencia de datos filtrados, lo que ayuda a los usuarios a tomar medidas para proteger su información personal y su seguridad en línea. 

# 8. LEAKS Y FUGAS
Aquí hay más herramientas y servicios relacionados con la detección y verificación de fugas de datos:
### 8.1. haveibeenpwned.com
- Creado por el experto en seguridad Troy Hunt, permite a los usuarios verificar si sus direcciones de correo electrónico o contraseñas han sido comprometidas en alguna filtración de datos.
- Recopila datos de múltiples brechas de seguridad y permite búsquedas para determinar si los datos personales han sido comprometidos.
- Ofrece verificación de direcciones de correo electrónico y contraseñas.
- Permite a los usuarios registrarse para recibir notificaciones si su dirección de correo electrónico aparece en futuras filtraciones.
- Proporciona una API para que los desarrolladores integren la funcionalidad en sus aplicaciones y servicios.
- Ofrece recursos educativos sobre seguridad cibernética.
### 8.2. leakcheck.io
- Proporciona una función de verificación de direcciones de correo electrónico y contraseñas para determinar si han sido comprometidas en una filtración de datos.
- Utiliza una base de datos actualizada de información comprometida para ayudar a los usuarios a identificar si sus datos personales están en riesgo.
- Permite la verificación de direcciones de correo electrónico y contraseñas.
- Ofrece la opción de suscribirse para recibir notificaciones por correo electrónico sobre futuras filtraciones.
- Proporciona detalles sobre la filtración en la que se encontró la dirección de correo electrónico o la contraseña.
### 8.3. breachdirectory.org
- Proporciona información sobre violaciones de datos y filtraciones de información que afectan a empresas y organizaciones en todo el mundo.
- Recopila datos de diversas fuentes para proporcionar una base de datos actualizada de violaciones de datos.
- Permite buscar información sobre violaciones de datos específicas.
- Proporciona detalles sobre cada violación de datos, incluyendo la fecha, el tipo de datos comprometidos y las medidas tomadas para mitigar el impacto.
- Ofrece la opción de suscribirse para recibir notificaciones sobre nuevas violaciones de datos.
- Proporciona recursos adicionales sobre seguridad cibernética y cómo responder a una violación de datos.
Estas herramientas son útiles para ayudar a los usuarios a proteger su información personal y su seguridad en línea al verificar si han sido afectados por filtraciones de datos
# 9. EMAILS 
Aquí tienes más información sobre plataformas relacionadas con la gestión de correos electrónicos y la seguridad cibernética:
### 9.1. hunter.io
- Es una plataforma en línea que proporciona herramientas y servicios para buscar y verificar direcciones de correo electrónico.
- Principalmente dirigida a profesionales de marketing, desarrolladores y equipos de ventas.
- Permite buscar direcciones de correo electrónico utilizando el nombre de dominio de una empresa específica.
- Ofrece una función de verificación de correo electrónico para verificar si una dirección de correo electrónico es válida y activa.
- Puede mostrar una lista de todas las direcciones de correo electrónico asociadas con un dominio específico.
- Ofrece integraciones con otras herramientas y servicios populares, como Google Sheets, Zapier y Salesforce.
- Proporciona una API para que los desarrolladores integren la funcionalidad en sus propias aplicaciones y servicios.
### 9.2. epieos.com
- Es una plataforma de gestión de contraseñas y seguridad cibernética diseñada para empresas y organizaciones.
- Ofrece un sistema centralizado para almacenar, gestionar y compartir contraseñas de forma segura dentro de una organización.
- Realiza auditorías de contraseñas para evaluar la fortaleza de las contraseñas utilizadas en una organización.
- Ayuda a implementar políticas de control de acceso para proteger sistemas y datos sensibles.
- Ayuda a cumplir con los requisitos regulatorios y las mejores prácticas de seguridad cibernética.
- Genera informes detallados sobre el estado de la seguridad de las contraseñas y análisis de tendencias.
Estas plataformas son útiles para gestionar y proteger las comunicaciones por correo electrónico, así como para garantizar la seguridad de las contraseñas y datos sensibles dentro de una organización.
### 9.3. osint.industries
- Una poderosa herramienta online de investigaciones OSINT que enriquece investigaciones con información de diversas fuentes abiertas.
- Permite recopilar y analizar extensas cantidades de información de bases de datos públicas, redes sociales, blogs, foros y otros sitios web relevantes.
- Ofrece algoritmos avanzados para realizar búsquedas sofisticadas y filtrar resultados de manera rápida y precisa.
- Presenta los datos de forma clara y concisa mediante gráficos interactivos, mapas geográficos y diagramas.
- Ayuda a comprender mejor la información obtenida y detectar patrones o relaciones ocultas, facilitando el análisis.
- Es especialmente útil para profesionales de la inteligencia abierta y para llevar a cabo investigaciones exhaustivas.
### 9.4. synapsint.com
- Una herramienta que recopila datos de un objetivo específico, como un dominio, una dirección IP o un correo electrónico, desde múltiples fuentes abiertas en Internet.
- Extrae información veraz de fuentes como Shodan, VirusTotal y los Registros Regionales de Internet.
- Ofrece una interfaz amigable que permite seleccionar el tipo de objetivo, como dominios, direcciones IP, teléfonos, cuentas de redes sociales, entre otros.
- Proporciona información detallada sobre el objetivo seleccionado, lo que incluye datos relevantes para la investigación.
### 9.5. Otras plataformas de búsqueda de emails:
- gmail-osint.activetk.jp: Proporciona herramientas para buscar información en fuentes abiertas relacionadas con direcciones de correo electrónico de Gmail.
- mailtester.com: Ofrece herramientas para verificar la validez y la existencia de direcciones de correo electrónico.
- defastra.com: Plataforma para buscar información y convertirla en inteligencia a través de herramientas online en fuentes abiertas.
- seon.io: Proporciona herramientas para buscar información en fuentes abiertas relacionadas con direcciones de correo electrónico.
# 10. Análisis de Cabeceras de Correo
- Varias herramientas que analizan los encabezados de los mensajes SMTP para identificar problemas de entrega y detectar configuraciones incorrectas de servidores.
- Permiten detectar la IP del emisor, la autenticidad del correo electrónico y otros detalles.
Algunas de estas herramientas incluyen:
- toolbox.googleapps.com: Herramienta de Google para analizar encabezados de mensajes de correo electrónico.
- mxtoolbox.com: Ofrece herramientas para el análisis de encabezados de correo electrónico y otras funciones de administración de correo.
- email-analyze.activetk.jp: Plataforma para analizar encabezados de correo electrónico y obtener información útil sobre la entrega de mensajes.
# 11. Búsqueda Inversa - Geolocalización
- Herramientas para determinar la ubicación geográfica de una imagen, incluso considerando la vegetación o la arquitectura presentes en la imagen.
Algunas de estas herramientas son:
- osm-search.bellingcat.com: Desarrollada por Bellingcat para buscar información geográfica utilizando OpenStreetMap como base, útil para investigaciones periodísticas y análisis de conflictos.
- geospy.web.app: Determina la ubicación de una fotografía considerando la vegetación o la arquitectura presentes en la imagen.
- geocreepy.com: Recopila información de ubicaciones geográficas a partir de redes sociales y servicios en línea, como Twitter, Instagram y Flickr, entre otros.
# 12. SOCK PUPPET Y HUELLA DIGITAL
Para proteger la identidad del investigador al realizar investigaciones en fuentes abiertas, se utilizan diversas plataformas y herramientas online para anonimizar las actividades. Aquí se presentan algunas de estas herramientas:
#### 12.1. Creación de Perfiles "Fake"
- Namelix: Genera nombres de forma aleatoria para crear identidades falsas.
- Fake Name Generator: Proporciona nombres, direcciones, números de teléfono y otros detalles para perfiles falsos.
- This Person Does Not Exist: Genera imágenes realistas de personas que no existen.
- Photopea: Herramienta de edición de fotos para manipular imágenes.
#### 12.2. Teléfonos Temporales
- HS3X: Proporciona números de teléfono temporales para verificación y comunicación temporal.
- SMSGet: Ofrece números de teléfono virtuales para recibir mensajes temporales.
•	Receive SMS Online: Permite recibir mensajes en números temporales en línea.
#### 12.3. Huella Digital
- AmIUnique: Herramienta para comprobar la unicidad de la huella digital de un navegador.
- Cover Your Tracks (EFF): Ofrece herramientas para aumentar la privacidad y reducir la huella digital en línea.
- Social Media Leak: Verifica qué información personal se puede filtrar desde las redes sociales.
- BrowserLeaks: Detecta información técnica que puede ser filtrada por el navegador web.
#### 12.4. Correos Electrónicos Temporales
•	Email On Deck: Ofrece direcciones de correo electrónico temporales para verificación en línea.
•	Temp Mail: Proporciona correos electrónicos temporales para uso temporal.
•	TempEmail: Genera direcciones de correo electrónico temporales para recibir mensajes.
#### 12.5. Motores de Búsqueda
- Yahoo: Un motor de búsqueda generalista que proporciona resultados de una amplia gama de fuentes.
- Ask: Ofrece resultados de búsqueda y respuestas a preguntas específicas.
- DuckDuckGo: Un motor de búsqueda centrado en la privacidad que no rastrea las actividades del usuario.
- Yandex: Un motor de búsqueda popular en Rusia que ofrece resultados precisos en varios idiomas.
- Carrot2: Un motor de búsqueda que organiza los resultados en grupos temáticos.
- Qwant: Un motor de búsqueda que respeta la privacidad del usuario y no rastrea las búsquedas.
- Gibiru: Un motor de búsqueda que prioriza la privacidad y la no censura en línea.
- Ecosia: Un motor de búsqueda que utiliza sus ganancias para plantar árboles en todo el mundo.
- MillionShort: Un motor de búsqueda que permite a los usuarios eliminar los sitios web populares de los resultados de búsqueda.
- Ahmia: Un motor de búsqueda que indexa contenido en la web oscura y anónima.

# 13. THREAT INTELLIGENCE
La inteligencia de amenazas, o "threat intelligence", es esencial en la ciberseguridad moderna, ya que implica recopilar, analizar y aplicar información sobre posibles amenazas y riesgos de seguridad. Este proceso ayuda a las organizaciones a anticipar, detectar y responder proactivamente a los ataques cibernéticos. Aquí hay algunas plataformas y herramientas en línea que facilitan este proceso:
#### •	13.1. VirusTotal: 
Una herramienta en línea gratuita que permite cargar archivos y URLs sospechosas para su análisis y escaneo con múltiples motores antivirus y otros servicios de seguridad. Proporciona informes detallados sobre los resultados del escaneo y qué motores antivirus detectaron posibles amenazas.
#### •	13.2. AlienVault OTX (Open Threat Exchange): 
Una plataforma gratuita que ofrece inteligencia de amenazas compartida por la comunidad. Proporciona información sobre indicadores de compromiso (IoC) y herramientas para analizar y colaborar en la respuesta a amenazas de seguridad cibernética.
#### •	13.3. IntelX: 
Un motor de búsqueda y plataforma de inteligencia de amenazas que recopila, indexa y proporciona acceso a una amplia variedad de datos en línea, incluyendo la web oscura. Ofrece funciones de búsqueda avanzada, inteligencia de amenazas y herramientas de integración.
#### •	13.4. Malware Bazaar: 
Una colección de muestras de malware y datos relacionados compartidos por la comunidad de ciberseguridad. Los usuarios pueden explorar una variedad de muestras de malware y utilizar herramientas de búsqueda y filtrado para encontrar muestras específicas basadas en diferentes criterios.
#### •	13.5. Hybrid Analysis: 
Una plataforma en línea que ofrece análisis automatizado y detallado de archivos y URLs sospechosos en busca de malware y amenazas cibernéticas. Proporciona análisis dinámico y estático de malware, informes detallados y visualizaciones de datos para comprender el comportamiento del malware. Además, fomenta la colaboración y el intercambio de información entre la comunidad de seguridad cibernética.
#### •	13.6. MITRE ATT&CK: 
Es un marco de trabajo ampliamente utilizado en ciberseguridad que describe las tácticas, técnicas y procedimientos utilizados por los atacantes. Proporciona una estructura organizada para categorizar y analizar el comportamiento de los atacantes en diferentes etapas de un ciclo de ataque. Este marco es esencial para entender las amenazas y mejorar las defensas.
#### •	13.7. UNIT 42: 
Desarrollada por PAN-Unit42, es una herramienta que permite explorar y aprender sobre tácticas, técnicas y procedimientos utilizados por actores de amenazas específicos. Ofrece una interfaz gráfica interactiva, matrices de tácticas y técnicas, información detallada y referencias cruzadas, siendo útil para investigadores y profesionales de ciberseguridad.
#### •	13.8. CRIMINALIP: 
Es una plataforma que ofrece servicios de investigación y análisis de direcciones IP y actividad en línea asociada. Permite buscar información sobre direcciones IP, analizar actividad en línea, acceder a inteligencia de amenazas y utilizarla en investigaciones forenses digitales.
#### •	13.9. DARKFEED: 
Proporciona inteligencia de amenazas en tiempo real y feeds de datos relacionados con la ciberseguridad. Ofrece información sobre amenazas emergentes, actividad en la web oscura, análisis de tendencias, integraciones con herramientas de seguridad y alertas y notificaciones para mejorar la detección y respuesta a amenazas.
#### •	13.10. SOCRADAR: 
Es una plataforma de gestión de incidentes de seguridad cibernética y respuesta a incidentes. Ofrece detección de amenazas en tiempo real, análisis de seguridad automatizado, gestión de incidentes, integraciones con herramientas de seguridad y paneles de control y visualizaciones para supervisar el estado de seguridad de la organización.
#### •	13.11. OTRAS PLATAFORMAS DE THREAT INTELLIGENCE:
##         •	IPQualityScore: 
Herramienta de detección de fraude y amenazas cibernéticas con alta precisión. Ofrece servicios como evaluación de reputación de IP, detección de fraude en línea, protección contra ataques DDoS, validación de direcciones IP e integraciones con sistemas de seguridad.
##         •	PolySwarm: 
Plataforma de ciberseguridad basada en blockchain que utiliza un mercado de seguridad descentralizado para colaborar en la detección y análisis de malware y amenazas cibernéticas. Ofrece un mercado descentralizado de seguridad, colaboración de la comunidad e integraciones con herramientas de seguridad.
##         •	ETDA APT Encyclopedia: 
Ofrece información sobre actores de amenazas recopilada por la ETDA, una agencia gubernamental de Tailandia encargada de regular la tecnología de la información y la comunicación (TIC).
##         •	Intezer: 
Ofrece automatización de investigaciones profundas impulsadas por IA, SOC de nivel 1 y clasificación autónoma para cada endpoint, phishing y alertas SIEM.

# 14. OTRAS HERRAMIENTAS DE INTERÉS:
En esta sección se presentan diversas herramientas online que pueden ser útiles en la vida diaria de un analista:
####       •	Thumbnail Save: 
Permite ver y descargar imágenes de vista previa de miniaturas de YouTube.
####         •	Dedigger:
Motor de búsqueda que permite encontrar archivos públicos en Google Drive.
####         •	ExpandURL: 
Servicio para averiguar a dónde llevará una URL acortada antes de hacer clic en ella.
####         •	IMEI.info: 
Permite obtener información sobre un dispositivo a partir de su número IMEI.
####         •	JustDeleteMe: 
Directorio de enlaces directos para eliminar cuentas en la web, con indicadores de dificultad.
####         •	SpyCloud: 
Recopila y monitorea datos filtrados y robados en la web oscura y otros canales clandestinos en línea para proteger a las organizaciones y usuarios.
####         •	RIPE Database: 
Herramienta de búsqueda de texto completo para buscar información sobre recursos de direcciones IP y sistemas autónomos.
####         •	Aaron CTI's OSINT Resource Collection: 
Excel con una amplia selección de herramientas, sitios, cursos, entrenamientos y miles de aspectos relacionados con OSINT e investigación en fuentes abiertas.
####         •	JSON.Crack: 
Editor JSON para visualizar, analizar y manipular datos.
####         •	DarkWeb Archive: 
Buscador de sitios ONION archivados de la Dark Web.
####         •		Blackbird: 
Ofrece funcionalidades para la recopilación y análisis de información de fuentes abiertas en línea.
####         •	WhoPostedWhat: 
Herramienta de búsqueda de palabras clave no públicas en Facebook y Twitter.
####         •	AnonStories: 
Permite visualizar y descargar historias de Instagram de forma anónima.
####         •	Búsqueda Avanzada de Twitter: 
Herramienta para realizar búsquedas específicas y detalladas en Twitter.
####         •	Exploit Database: 
Base de datos de vulnerabilidades de seguridad informática.
####         •	OSINT Framework: 
Ofrece una recopilación organizada de herramientas y recursos para realizar inteligencia de fuentes abiertas.
####         •	Base64Decode: 
Herramienta en línea para decodificar texto codificado en Base64.
####         •	Malfrat's OSINT Map: 
Árbol online de herramientas útiles seleccionadas para propósitos OSINT.
####         •	Deepfake Detector: 
Herramienta contra la desinformación de la IA para detectar deepfakes en audio y video.
####         •	Any.Run: 
Sandbox para el análisis dinámico y la ejecución segura de archivos maliciosos y enlaces sospechosos.

# 15 ALGUNAS HERRAMIENTAS LÍNEA DE COMANDOS:

En esta sección se presentan herramientas y programas que se utilizan mediante línea de comandos y que son fundamentales en el mundo de OSINT y la investigación:

![image](https://github.com/ciberlabpruebamaster/Will-Kali/assets/165423933/107c0cc3-4a5c-4e46-9a57-322780f97a25)



####     • TheHarvester: 
Permite obtener datos y contactos relacionados con un dominio específico a partir de fuentes públicas en línea.
####     • Recon-ng: 
Herramienta para el reconocimiento y recopilación de información que automatiza la búsqueda y obtención de datos en línea para realizar investigaciones de seguridad y pruebas de penetración.
####     • IP Tracer: 
Rastrea y proporciona información detallada sobre la ubicación geográfica y otros detalles relacionados con una dirección IP específica.
####     • Shodan: 
Motor de búsqueda para encontrar dispositivos escaneados conectados a Internet.
####     • Nmap: 
Herramienta de escaneo de red que permite descubrir hosts, servicios y puertos abiertos en una red.
####     • Maltego: 
Servicio que encuentra información sobre personas y empresas en Internet, permitiendo cruzar datos para obtener perfiles en redes sociales, servidores de correo, etc.
####     • Exiftool: 
Permite visualizar, modificar y extraer metadatos incrustados en archivos multimedia, como imágenes y videos.
####     • H8mail: 
Herramienta de código abierto para buscar y recopilar información filtrada o comprometida, como correos electrónicos y contraseñas.
####     • GhostTrack: 
Herramienta para rastrear la ubicación o el número de teléfono móvil.
####     • The_Spy_Job: 
Herramienta de OSINT para recolectar información sobre algo o alguien.
####     • Phonefy: 
Recupera información sobre teléfonos móviles vinculados a prácticas conocidas de spam.
####     • Sherlock: 
Busca cuentas de redes sociales por nombre de usuario en diversas plataformas.
####     • IP Info: 
Proporciona información detallada sobre direcciones IP y dominios.
####     • URL Scan: 
Herramienta para analizar y obtener información detallada sobre una URL específica.
####     • OSRFramework: 
Plataforma que organiza herramientas y recursos de fuentes abiertas en línea para facilitar la investigación y recopilación de información.
####     • Spiderfoot: 
Automatiza la recopilación de información e realiza análisis de inteligencia de fuentes abiertas para obtener datos relevantes sobre un objetivo.
####     • Holehe: 
Verifica si un correo electrónico está asociado a una cuenta en varios sitios web y redes sociales.
####     • Domainfy: 
Encuentra dominios que actualmente se resuelven usando una palabra o apodo dado.
####     • Usufy: 
Identifica perfiles de redes sociales usando un apodo dado.
####     • Mailfy: 
Encuentra más información sobre los correos electrónicos tomando como referencia un apodo o una lista de correo electrónico.
####     • Searchfy: 
Encuentra perfiles vinculados a un nombre completo.


