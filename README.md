<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1e3a8a,100:7c3aed&height=180&section=header&text=Alfonso%20Maza&fontSize=50&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Producto%20digital%20%C2%B7%20Real%20Estate%20%C2%B7%20Automatizaci%C3%B3n%20con%20IA&descSize=16&descAlignY=60" width="100%" alt="Alfonso Maza">

<h1 align="center">Hola, soy Alfonso 👋</h1>

<p align="center">
<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1200&color=7C3AED&center=true&vCenter=true&width=700&lines=Construyendo+OIKAI+desde+Sevilla;Gesti%C3%B3n+de+alquileres+vacacionales%2C+media+y+larga+estancia;Automatizo+negocios+con+n8n+e+IA;Emprendedor+desde+2020" alt="Typing SVG">
</p>

<p align="center">
<a href="https://oikai.es"><img src="https://img.shields.io/badge/OIKAI-oikai.es-7C3AED?style=for-the-badge&logo=googlechrome&logoColor=white"></a>
<a href="https://www.linkedin.com/in/alfonsomazaosuna/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"></a>
<a href="https://www.instagram.com/alfonso.maza"><img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white"></a>
<a href="mailto:fonzymazai@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white"></a>
</p>

---

## 🧭 Sobre mí

Desde 2020 he montado y dirigido **cuatro negocios propios**, con mi dinero en juego y la cuenta de resultados a mi cargo. Eso enseña a decidir con números antes que con intuiciones. Soy de **Sevilla** (con los veranos en Islantilla) y ahora llevo esa experiencia a **construir producto**: plataformas para el sector inmobiliario y automatización de procesos con IA.

<table align="center">
<tr>
<td align="center"><h3>4</h3>negocios propios<br>desde 2020</td>
<td align="center"><h3>85%</h3>ocupación media<br>en alquiler vacacional</td>
<td align="center"><h3>4,2/5</h3>nota media en reseñas<br>entre plataformas</td>
<td align="center"><h3>+1.000</h3>colaboradores en la red<br>que construí en eventos</td>
</tr>
</table>

## 💻 En qué estoy trabajando

| | Proyecto | Qué es |
|---|---|---|
| 🏠 | **OIKAI** | Participo en el desarrollo de una plataforma de gestión a medida para media estancia |
| 🏖️ | **WellHome Rentals** | Gestión de alquileres vacacionales, de media y larga estancia, con la operativa automatizada en n8n |

## 🏢 OIKAI

<p align="center">
<a href="https://oikai.es"><img src="https://pub-bb2e103a32db4e198524a2e9ed8f35b4.r2.dev/lovp_2sabnkx1qr9cwab59s7q5tgqaj/039c182ca898e8d39f9619b71941af5c_1794932021783.png" width="640" alt="OIKAI"></a>
</p>

**OIKAI** es una plataforma de gestión a medida para gestores de habitaciones y apartamentos de media estancia. *Tu alquiler por habitaciones, en piloto automático.* Participo en el desarrollo del producto junto al equipo técnico, trabajando con Claude Code y Lovable sobre un repositorio de GitHub.

| | |
|---|---|
| 🏠 **Gestión** | Propiedades, contratos, cobros, incidencias y mensajes |
| 💶 **Rentabilidad** | Margen real por inmueble y habitación, con alertas |
| 🌐 **Portal de reservas** | Web pública con marca propia para captar reservas |
| 🤖 **IA y automatización** | Asistente en lenguaje natural y tareas automatizadas |
| 🧾 **Liquidaciones** | Informes y liquidaciones a propietarios |

👉 Más información en [oikai.es](https://oikai.es)

## 🏖️ WellHome Rentals

Gestión de **alquileres vacacionales, de media y larga estancia**, de principio a fin: reservas, limpieza, comunicación con huéspedes, proveedores y contabilidad. Los precios los fijo yo, cruzando la ocupación con lo que hace la competencia y con los eventos de la ciudad.

- 📈 **85 %** de ocupación media
- ⭐ **4,2 / 5** de nota media entre todas las plataformas
- 🤖 Operativa diaria automatizada con **n8n** (ver abajo)

## ⚙️ Automatización con n8n

Tengo montado un servidor de **n8n** que lleva buena parte de la operativa en piloto automático. Webhooks, triggers de Gmail y Drive, tareas programadas e integración con la API de ERPNext:

```mermaid
flowchart LR
A["📧 Emails de reservas"] --> B["⚙️ n8n"]
B --> C["📊 Hoja de reservas"]
C --> D["📅 Calendario y limpiezas"]
C --> E["🌅 Resumen diario a las 9:00"]
C --> F["🗣️ Consulta por Siri"]
G["🧾 Facturas en Drive"] --> B
B --> H["📚 Contabilidad en ERPNext"]
```

| Workflow | Disparador | Qué hace |
|---|---|---|
| **Alta de reservas** | Gmail, email de confirmación | Guarda cada reserva nueva en Google Sheets |
| **Resumen diario** | Programado, 9:00 | Entradas, salidas y agenda de limpieza |
| **Calendario** | Programado | Bloques de limpieza con el número de huéspedes de cada día |
| **Consulta por voz** | Webhook GET desde un Atajo de Siri | Responde qué pasa hoy y mañana, días libres y próxima reserva |
| **Facturas a contabilidad** | Drive, nueva factura | Comprueba o crea el proveedor y crea la factura en ERPNext por API |
| **Reconciliación** | Manual | Cruza reservas y emails para detectar las que faltan, cambian o se cancelan |

## 🎟️ Tricket

Plataforma de gestión de ticketing para eventos que desarrollé en equipo entre 2025 y 2026. Conozco el problema desde dentro: organicé eventos universitarios con UNight en Sevilla, Huelva y Cádiz.

## 🛤️ Trayectoria

| Etapa | Qué hice |
|---|---|
| **2026 a hoy** | **OIKAI**: desarrollo de una plataforma de gestión de alquileres para media estancia |
| **2025 a hoy** | **WellHome Rentals**: gestión de alquileres vacacionales, de media y larga estancia, con automatización en n8n |
| **2025 a 2026** | **Tricket**: desarrollo de una plataforma de gestión de ticketing para eventos |
| **2023 a 2025** | **Mad Club Islantilla**: cofundador y CEO de un local de hostelería de temporada. Presupuestos, caja, proveedores, patrocinadores y equipo de hasta 15 personas |
| **2021 a 2026** | **UNight S.L.**: fundador y CEO. Eventos universitarios en Sevilla, Huelva y Cádiz, con una red de más de 1.000 colaboradores y más de 20 locales asociados |
| **2020 a 2022** | **Waikiki Club Islantilla**: cofundador y encargado de un pub de temporada. Tesorería, personal, proveedores y promoción en redes |

## 🎓 Formación

- 🎓 **Administración y Dirección de Empresas**, Universidad Europea de Madrid
- 🎯 **Programa LYDES**, San Telmo Business School

## 🛠️ Herramientas que uso

![n8n](https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white)
![Claude](https://img.shields.io/badge/Claude_Code-D97757?style=for-the-badge&logo=anthropic&logoColor=white)
![Lovable](https://img.shields.io/badge/Lovable-FF4F8B?style=for-the-badge&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![Notion](https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=notion&logoColor=white)
![Google Sheets](https://img.shields.io/badge/Google_Sheets-34A853?style=for-the-badge&logo=googlesheets&logoColor=white)
![Google Drive](https://img.shields.io/badge/Google_Drive-4285F4?style=for-the-badge&logo=googledrive&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logoColor=white)
![ERPNext](https://img.shields.io/badge/ERPNext-0089FF?style=for-the-badge&logoColor=white)

## 📫 Hablamos

¿Tienes un proyecto o una oportunidad de la que quieras hablar? Escríbeme por [LinkedIn](https://www.linkedin.com/in/alfonsomazaosuna/), [Instagram](https://www.instagram.com/alfonso.maza) o a [fonzymazai@gmail.com](mailto:fonzymazai@gmail.com).

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:7c3aed,100:1e3a8a&height=110&section=footer" width="100%" alt="">
