![OriON_v2](https://github.com/Cl4r4-5/OriON/assets/127757371/782771b5-93e9-417b-ae60-ca1dc564244f)


# **OriON**

OriON es una distribución basada en Linux Ubuntu 22.10. 
Esta '.ovf' tiene integradas distintas herramientas para investigaciones de recopilación de información en fuentes abiertas (OSINT) sobre personas.

![OriON_Escritorio](https://github.com/Cl4r4-5/OriON/assets/127757371/ff7b7583-c159-41eb-a30d-d9dc7366a942)



## Navegadores

Dispone de **3 navegadores distintos (Chrome, Firefox y Tor)** con sus respectivos marcadores y extensiones web categorizados: 
- **Correo:**
	- Castrick, DeHashed, Email Header Analyzer, Have I Been Pwned, Hunter, GhostProject, LeakCheck, OSINT Industries, Skymem, Verify Email Addresses, VoilaNorbert.
- **Criptomonedas (aunque no está disponible en su primera versión, es una categoría de especial interés):**
	- Blockchain, Chainalysis, Etherscan, Mempool, BSCscan, TRONscan.
- **Dominio / Páginas Web:**
	- CachedView, Centralops, Desenmascara, DNSlytics, DomainTools Whois, ExpandURL, HTTrack, ICANN Lookup, IntelX, Internet Archive, Netcraft, PDY my URL, Robtex, urlscan, URLVoid, ViewDNS.info, Whois Request, Who Is Hosting This?
- **Geolocalización:**
	- Balizas Digitales, Canary Tokens, Flight Aware, Flightera, Flightradar, Geolocation Estimation, IP2Location, Maps, Rastreador de Buques, SunCalc.
- **Identidad:**
	- DNI (BOE, Boletines oficiales de las CCAA), Intelius, librebor.me, Pipl, ScamDigger, Spokeo, ThatsThem.
- **IP:**
	- AbuseIPDB, Censys Search, Criminal IP, DNSdumpster, IP Address Lookup, IPVoid, RIPE, Scamalytics.
- **Multimedia:**
	- Bing Visual Search, CarNet.AI, Diff Checker, Exif Info, FaceCheck, Forensically, Imageforensic.org, Imágenes de Google, TinEye Reverse Image Search, Yandex Images.
- **Navegadores:**
  	- Google.
  	- Mozilla. 
  	- Otros: All in One, Search All, Ahmia, Baidu, Bing, DuckDuckGo, eTools.ch, Gibiru, Qwant, Startpage, Yandex.
- **Otras:**
	-  *Certificaciones:* eGarante, Save The Proof.
 	-  *Creación de Mapas:* ArcGIS, QGIS, Xmind.
  	-  *Eliminar Perfiles:* Cleanup.pictures, Just Delete Me.
  	-  *Herramientas OSINT:* Cylect.io, OSINT Framework, OSINT Tools, Repositorio Ciberpatrulla.
  	-  *UA Parser:* Parse a user Agent, User Agent Parser.
  	-  Maltego, SpiderFoot, Shodan, ZoomEye. 
- **Redes sociales / Usuario:**
	- *Usuario:* KnowEm, Lullar, Namechk, UserSearch, WhatsMyName.
 	- *Twitter / X:* Descargar Videos, Hashtagify.me, Social Bearing, Tweet Archivist, TweetDeck, TweeterID, TwitterAudit, Twitonomy. 
  	- *Instagram:* Picodash, downloadGram, StoriesIG.
  	- *Facebook:* Download Facebook videos, StalkFace.
  	- *TikTok:* Descargar TikTok.
  	- *YouTube:* y2mate.
  	- Comment Picker, Export Comments, Random Tools.
- **Teléfono:**
	- AbcTelefonos, IMEI Check, Infobel España, Numbering Plans, Páginas Blancas, Peoplecall, ¿Quién me llama?, Randommer, Sync.me, Truecaller, Teledigo, NumLookup.


## Herramientas

A su vez dispone de **herrramientas de aplicación** para el investigador: 
- Audacity
- Evince
- Google Earth
- HTTrack
- KeePassxc
- Maltego
- Notepad++
- Terminator
- VLC
- Xmind
- Entre otras.

![herramientas](https://user-images.githubusercontent.com/127757371/230437330-abdbce8c-4d81-420b-9efb-48870c82d6eb.png)

Finalmente, tiene una diversidad de herramientas instaladas, las cuáles se pueden ejecutar directamente desde la línea de comandos.
De hecho, para facilitar el uso de estas herramientas, la máquina dispone de un **script**, llamado **'OriON'** en la ruta /home/orion/Escritorio/Herramientas, para facilitar la ejecución de las mismas.

**Para ejecutar el script:**

```cd /Escritorio/Herramientas```

```sudo ./OriON```



Las **herramientas** son:
- **CloudFail**: encuentra IP ocultas detrás de la red CloudFlare.
- **Crosslinked**: recopila información de perfiles de LinkedIn.
- **DaProfiler**: recopila información de perfiles en redes sociales y en la web a través de nombres.
- **Dmitry**: recopila información de fuentes públicas de dominios y direcciones IP.
- **DNSRecon**: descubre información sobre hosts y redes a través de consultas de DNS.
- **EO-Ripper**: hace OSINT a un email o a una lista de emails.
- **Exiftool**: extrae metadatos de imágenes, archivos o documentos.
- **InstagramOSINT**: recopila información de perfiles de Instagram.
- **Instaloader**: permite descargas de cualquier dato de Instagram.
- **Maltego**: análisis de datos.
- **MediaInfo**: extrae metadatos de archivos multimedia: audio o vídeo.
- **NetSoc OSINT**: recopila datos de Instagram, TikTok, Twitter, Twitch, Telegram y GitHub.
- **Photon**: extrae URLs, subdominios y archivos de una página web y realiza búsquedas en motores de búsqueda.
- **Osintgram**: recopila información de perfiles de Instagram.
- **OSRFramework**: colección de herramientas para la recopilación de OSINT.
- **ProtOSINT**: investiga cuentas de ProtonMail y direcciones IP vinculadas a ProtonVPN.
- **Sherlock**: busca cuentas en gran multitud de redes sociales por nombre de usuario.
- **Shodan**: motor de búsqueda especializado que permite buscar dispositivos conectados a Internet.
- **SpiderFoot**: recopila y analiza datos.
- **Sublist3r**: recopila y analiza datos.
- **Th3inspector**: recopilación sobre páginas webs, dominios, IP, correos, teléfonos, etc.
- **TheHarvester**: recolecta diversa información a través de un dominio.
- **Tinfoleak**: análisis de información pública de Twitter.
- **Uscrapper**: recoge información de páginas web (correos, nombres, teléfonos, enlaces, etc.).
- **WebScrape**: recoge correos y números de teléfono de páginas web.
	   

# DESCARGA

**Importante**:

Como buen investigador OSINT, es necesario hacer uso de alguna VPN. En la distribución no se ofrece ninguna en específico porque eso suele ser elección del analista. De todos modos, a continuación se ofrecen 5 opciones distintas:

- **ExpressVPN:** es de las más populares del mercado, tiene con una aplicación oficial para Linux y dispone de una gran cantidad de opciones de configuración avanzadas para usuarios más técnicos.
- **NordVPN:** tiene una reputación sólida en cuanto a privacidad y seguridad, también tiene una aplicación oficial para Linux y cuenta con una opción de doble VPN que añade una capa adicional de seguridad.
- **ProtonVPN:** se basa en la privacidad y seguridad y cuenta con un plan gratuito limitado para aquellos que quieran probar el servicio.
- **CyberGhost:** Tiene una gran cantidad de opciones de configuración, incluyendo un modo de privacidad para proteger aún más su identidad en línea.
- **Mullvad:** se centra en mantener la privacidad del usuario al máximo, incluyendo la opción de pagar con criptomonedas.

**Ahora sí:** Para empezar a usarla, solo queda descargarla: 

**Enlace a Mega:** *https://mega.nz/folder/VmpXSaKT#GUNthBlNqK63LbUR4fvByw*

**Enlace a OneDrive:** *https://1drv.ms/f/s!Aszpl7MVvmNGkivhl5yPxR2izuZY*

Y LISTO

- **Usuario:** orion
- **Contraseña:** orion


# DEMOSTRACIÓN

En el siguiente enlace se ofrece un vídeo demostrativo de la distribución:
https://youtu.be/rTYlaGtA2tE

![youtube](https://user-images.githubusercontent.com/127757371/230694424-be998770-8cc3-4b5e-aca3-17bcd337f430.png)


### *Espero que la podáis disfrutar tanto como yo he disfrutado haciéndola.*

