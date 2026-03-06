<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Experiencia Laboral - Angel Michel Lopez Garcia</title>

<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600&family=Orbitron:wght@600&display=swap" rel="stylesheet">

<style>
/* ===== RESET GENERAL ===== */
* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}

body {
    font-family: 'Inter', sans-serif;
    background: #0a0a0a;
    color: #e6e6e6;
    line-height: 1.7;
    overflow-x: hidden;
}

/* ===== ANIMATED BACKGROUND ===== */
body::before {
    content: "";
    position: fixed;
    inset: 0;
    background: radial-gradient(circle at 30% 20%, #0ff2, transparent 50%),
                radial-gradient(circle at 70% 70%, #0ff1, transparent 50%),
                url('https://www.transparenttextures.com/patterns/cubes.png');
    opacity: 0.3;
    animation: floatBg 20s infinite linear;
    z-index: -8;
}

@keyframes floatBg {
    from { background-position: 0 0; }
    to { background-position: 0 -500px; }
}

/* ===== HEADER ===== */
header {
    text-align: center;
    padding: 40px 20px;
}

header h1 {
    font-family: 'Orbitron', sans-serif;
    font-size: 2.5rem;
    letter-spacing: 2px;
    color: #00eaff;
    margin-bottom: 10px;
    text-shadow: 0 0 15px #00eaff44;
}

header p {
    font-size: 1rem;
    opacity: 0.7;
    max-width: 700px;
    margin: auto;
    letter-spacing: 1px;
}

.foto-superior {
    margin-top: 30px;
    width: 180px;
    height: 180px;
    border-radius: 50%;
    object-fit: cover;
    border: 2px solid #00eaff;
    box-shadow: 0 0 20px #00eaff66;
}

/* ===== NAV ===== */
nav {
    text-align: center;
    margin: 20px 0;
}

nav a {
    margin: 0 15px;
    text-decoration: none;
    color: #00eaff;
    font-weight: 600;
    transition: 0.3s;
    opacity: 0.7;
    font-size: 0.9rem;
    text-transform: uppercase;
}

nav a:hover {
    opacity: 1;
    text-shadow: 0 0 10px #00eaff;
}

.fecha-nac {
    display: flex;
    justify-content: center;
    gap: 15px;
    font-family: 'Orbitron', sans-serif;
    font-size: 0.8rem;
    color: #555;
    margin-bottom: 20px;
}

/* ===== SECCIONES ===== */
section {
    width: 90%;
    max-width: 1000px;
    margin: auto;
    padding: 40px 0;
}

section h2 {
    font-family: 'Orbitron', sans-serif;
    font-size: 1.8rem;
    color: #00eaff;
    border-left: 4px solid #00eaff;
    padding-left: 15px;
    margin-bottom: 30px;
}

/* ===== TARJETAS ===== */
.projects {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 25px;
}

.project-card {
    background: rgba(20, 20, 20, 0.8);
    padding: 25px;
    border-radius: 15px;
    border: 1px solid #00eaff22;
    transition: 0.3s ease;
    display: flex;
    flex-direction: column;
    backdrop-filter: blur(5px);
}

.project-card:hover {
    border-color: #00eaff66;
    box-shadow: 0 10px 30px rgba(0, 234, 255, 0.1);
}

.project-card h3 {
    color: #00eaff;
    margin-bottom: 5px;
}

.project-card .p-periodo {
    font-size: 0.85rem;
    font-weight: 600;
    margin-bottom: 15px;
    color: #888;
}

/* ===== DETAILS & BOTONES ===== */
details summary {
    cursor: pointer;
    list-style: none;
    outline: none;
}

/* Quitar flecha de summary en todos los navegadores */
details summary::-webkit-details-marker { display: none; }

.btn-ver-mas {
    display: inline-block;
    padding: 8px 15px;
    border: 1px solid #00eaff55;
    border-radius: 6px;
    color: #00eaff;
    font-size: 0.85rem;
    transition: 0.3s;
}

.btn-ver-mas:hover {
    background: rgba(0, 234, 255, 0.1);
}

/* Estilo del botón de la carta */
.btn-doc {
    display: block;
    margin-top: 20px;
    padding: 10px;
    background: transparent;
    border: 1px solid #00eaff;
    border-radius: 8px;
    color: #00eaff;
    text-align: center;
    font-weight: 600;
    text-transform: uppercase;
    font-size: 0.75rem;
    transition: 0.3s;
}

.btn-doc:hover {
    background: #00eaff;
    color: #000;
    box-shadow: 0 0 15px #00eaff;
}

/* ===== CONTENEDOR DE LA CARTA (EL CUADRITO NUEVO) ===== */
.carta-desplegable {
    margin-top: 15px;
    background: #151515;
    border-radius: 10px;
    border: 1px dashed #00eaff88;
    overflow: hidden;
    animation: slideDown 0.4s ease-out;
}

@keyframes slideDown {
    from { opacity: 0; transform: translateY(-10px); }
    to { opacity: 1; transform: translateY(0); }
}

.img-carta-preview {
    width: 100%;
    height: auto;
    display: block;
    filter: grayscale(0.3);
    transition: 0.3s;
}

.img-carta-preview:hover {
    filter: grayscale(0);
}

.footer-carta {
    padding: 10px;
    text-align: center;
    background: #111;
}

.link-externo {
    color: #00eaff;
    font-size: 0.8rem;
    text-decoration: none;
}

/* ===== IMAGENES DE APOYO ===== */
.img-detalle {
    width: 100%;
    height: 150px;
    object-fit: cover;
    border-radius: 8px;
    margin: 15px 0;
    border: 1px solid #333;
}

/* ===== CONTACTO ===== */
#contacto p {
    margin-bottom: 10px;
}

#contacto strong {
    color: #00eaff;
}

footer {
    text-align: center;
    padding: 40px;
    opacity: 0.4;
    font-size: 0.8rem;
}
</style>
</head>
<body>

<header>
    <h1>ANGEL MICHEL LOPEZ GARCIA</h1>
    <p>EXPERTO EN VENTAS • ENCARGADO • MARKETING • DISEÑO DE PUBLICIDAD</p>
    <img src="https://i.postimg.cc/Gpy97LJ2/1760930478557.png" class="foto-superior" alt="Angel Michel">
</header>

<div class="fecha-nac">
    <span>06 / ABRIL / 2004</span>
</div>

<nav>
    <a href="#sobre-mi">Sobre mí</a>
    <a href="#proyectos">Trabajos</a>
    <a href="#contacto">Contacto</a>
</nav>

<section id="sobre-mi">
    <h2>Sobre mí</h2>
    <p>
        Soy una persona creativa, astuta, ambiciosa y determinada. Quienes me conocen destacan mi integridad, 
        compromiso y vocación de servicio, especialmente en el trabajo en equipo y la atención al cliente. 
        Actualmente tengo 21 años.
    </p>

    <div style="margin-top: 25px; display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 20px;">
        <div>
            <h3 style="color:#00eaff; font-size: 1rem; margin-bottom: 10px;">Ventas y Atención</h3>
            <ul style="list-style: none; font-size: 0.9rem; opacity: 0.8;">
                <li>✓ Técnicas de persuasión y cierre</li>
                <li>✓ Manejo de CRM y POS</li>
                <li>✓ Asesoría en planes móviles</li>
            </ul>
        </div>
        <div>
            <h3 style="color:#00eaff; font-size: 1rem; margin-bottom: 10px;">Administración</h3>
            <ul style="list-style: none; font-size: 0.9rem; opacity: 0.8;">
                <li>✓ Arqueos de caja y efectivo</li>
                <li>✓ Control de inventarios</li>
                <li>✓ Excel y Word intermedio</li>
            </ul>
        </div>
    </div>
</section>

<section id="proyectos">
    <h2>Trabajos</h2>
    <div class="projects">

        <div class="project-card">
            <h3>AT&T</h3>
            <p class="p-periodo">GERENTE DE TIENDA — 11 MESES (2025-2026)</p>
            <details>
                <summary class="btn-ver-mas">Ver detalles</summary>
                <div>
                    <p style="margin-top: 15px; font-size: 0.9rem;">
                        Supervisión de operaciones diarias, administración de inventario y gestión de personal.
                    </p>
                    <p style="font-size: 0.85rem; margin-top: 10px; border-top: 1px solid #333; pt: 10px;">
                        <strong>Ref:</strong> Juan Carlos (Regional) <br>
                        <strong>Tel:</strong> 999 589 3630
                    </p>
                    
                    <details>
                        <summary class="btn-doc">📄 Ver Carta de Recomendación</summary>
                        <div class="carta-desplegable">
                            <img src="https://i.postimg.cc/CKxp5mdh/IMG-20250224-WA0005.jpg" class="img-carta-preview" alt="Carta AT&T">
                            <div class="footer-carta">
                                <a href="https://drive.google.com/file/d/1FOnxmfdBR3XJJma4QhEkLSxhR8pnWfTT/view?usp=drivesdk" target="_blank" class="link-externo">Abrir documento original ↗</a>
                            </div>
                        </div>
                    </details>
                </div>
            </details>
        </div>

        <div class="project-card">
            <h3>MACROPAY</h3>
            <p class="p-periodo">ASESOR Y ENCARGADO — 9 MESES (2024-2025)</p>
            <details>
                <summary class="btn-ver-mas">Ver detalles</summary>
                <div>
                    <p style="margin-top: 15px; font-size: 0.9rem;">
                        Atención al cliente, colocación de créditos y control de inventario.
                    </p>
                    <p style="font-size: 0.85rem; margin-top: 10px; border-top: 1px solid #333; pt: 10px;">
                        <strong>Ref:</strong> Alan Jair (Gerente) <br>
                        <strong>Tel:</strong> 984 319 2715
                    </p>
                    
                    <details>
                        <summary class="btn-doc">📄 Ver Carta de Recomendación</summary>
                        <div class="carta-desplegable">
                            <img src="https://i.postimg.cc/RVYB3DdW/IMG-20260218-WA0005.jpg" class="img-carta-preview" alt="Carta Macropay">
                            <div class="footer-carta">
                                <a href="https://drive.google.com/file/d/1IN24S21kvixDRVj8gt_NQtF9XE98mktH/view?usp=drivesdk" target="_blank" class="link-externo">Abrir documento original ↗</a>
                            </div>
                        </div>
                    </details>
                </div>
            </details>
        </div>

        <div class="project-card">
            <h3>OXXO</h3>
            <p class="p-periodo">AYUDANTE DE PISO — 3 MESES</p>
            <details>
                <summary class="btn-ver-mas">Ver detalles</summary>
                <div>
                    <p style="margin-top: 15px; font-size: 0.9rem;">
                        Manejo de caja, inventarios, recepción de mercancía y control de caducidades.
                    </p>
                    <img src="https://elceo.com/wp-content/uploads/2023/03/oxxo-1.jpg" class="img-detalle" alt="Oxxo">
                    
                    <details>
                        <summary class="btn-doc">📄 Ver Carta de Recomendación</summary>
                        <div class="carta-desplegable">
                            <div style="padding: 20px; text-align: center; font-size: 0.8rem; color: #666;">
                                Imagen de carta en proceso de carga...
                            </div>
                            <div class="footer-carta">
                                <a href="#" class="link-externo">Documento no disponible</a>
                            </div>
                        </div>
                    </details>
                </div>
            </details>
        </div>

    </div>
</section>

<section id="contacto">
    <h2>Contacto</h2>
    <p>Email: <strong>angelmichellopezgarcia@gmail.com</strong></p>
    <p>Teléfono: <strong>56 1003 2002</strong></p>
    <p>WhatsApp: 
        <a href="https://wa.me/525610032002" target="_blank" style="color:#25D366; text-decoration: none; font-weight: bold;">
            Enviar mensaje directo
        </a>
    </p>
    <p>Facebook: 
        <a href="https://www.facebook.com/michel.326842" target="_blank" style="color:#00eaff; text-decoration: none;">
            michel.326842
        </a>
    </p>
</section>

<footer>
    © 2025 - ANGEL MICHEL LOPEZ GARCIA <br>
    Desarrollado con enfoque en tecnología y ventas.
</footer>

</body>
</html>
