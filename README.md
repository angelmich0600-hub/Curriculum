




<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Experiencia Laboral - Angel Michel Lopez Garcia</title>

<!-- Tipografías modernas -->
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
    animation: floatBg 15s infinite linear;
    z-index: -8;
}

@keyframes floatBg {
    from { transform: translateY(50); }
    to { transform: translateY(-100px); }
}

/* ===== HEADER ===== */
header {
    text-align: center;
    padding: 10px 20px;
}

header h1 {
    font-family: 'Orbitron', sans-serif;
    font-size: 2.8rem;
    letter-spacing: 2px;
    color: #00eaff;
    margin-bottom: 10px;
}

header p {
    font-size: 1.1rem;
    opacity: 0.7;
    max-width: 700px;
    margin: auto;
}

.foto-superior {
    margin-top: 30px;
    width: 200px;
    height: 200px;
    border-radius: 150%;
    object-fit: cover;
    border: 1px solid #00eaff;
    box-shadow: 0 0 15px #00eaff88;
}

/* ===== NAV ===== */
nav {
    text-align: center;
    margin: 40px 0;
}

nav a {
    margin: 0 20px;
    text-decoration: none;
    color: #00eaff;
    font-weight: 600;
    transition: 0.3s;
    opacity: 0.8;
}

nav a:hover {
    opacity: 15;
    text-shadow: 0 0 10px #00eaff;
}

/* ===== SECCIONES ===== */
section {
    width: 90%;
    max-width: 1100px;
    margin: auto;
    padding: 60px 0;
}

section h2 {
    font-family: 'Orbitron', sans-serif;
    font-size: 2rem;
    color: #00eaff;
    border-left: 4px solid #00eaff;
    padding-left: 15px;
    margin-bottom: 35px;
}

/* ===== TARJETAS ===== */
.projects {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(270px, 1fr));
    gap: 25px;
}

.project-card {
    background: #111;
    padding: 25px;
    border-radius: 14px;
    border: 1px solid #00eaff22;
    box-shadow: 0 0 12px #00eaff11;
    transition: 0.3s ease;
}

.project-card:hover {
    transform: translateY(-5px);
    box-shadow: 0 0 20px #00eaff33;
}

.project-card h3 {
    color: #00eaff;
    margin-bottom: 10px;
}

.project-card p {
    opacity: 0.8;
}

/* ===== DETAILS ===== */
details summary {
    cursor: pointer;
    background: transparent;
    padding: 8px 12px;
    display: inline-block;
    margin-top: 15px;
    border: 1px solid #00eaff55;
    border-radius: 6px;
    color: #00eaff;
    font-size: 0.9rem;
    transition: 0.3s;
}

details summary:hover {
    background: #00eaff;
    color: #000;
    box-shadow: 0 0 10px #00eaff;
}

/* ===== IMAGENES DETALLE ===== */
.img-detalle {
    width: 100%;
    max-height: 250px;   /* evita que sea muy grande */
    object-fit: cover;   /* recorte elegante */
    border-radius: 10px;
    margin-top: 15px;
    border: 1px solid #00eaff55;
    box-shadow: 0 0 12px #00eaff33;

    opacity: 0;
    transform: translateY(10px);
    transition: 0.4s ease-in-out;
}

/* Imagen aparece suave al abrir */
details[open] .img-detalle {
    opacity: 1;
    transform: translateY(0);
}

/* ===== FOOTER ===== */
footer {
    text-align: center;
    padding: 40px 20px;
    margin-top: 40px;
    font-size: 0.9rem;
    opacity: 0.5;
}
</style>
</head>
<body>

<header>
    <h1>ANGEL MICHEL LOPEZ GARCIA</h1>
    <p>EXPERTO EN VENTAS • ENCARGADO • MARKETING • DISEÑO DE PUBLICIDAD</p>
    <img src="https://scontent.fisj1-1.fna.fbcdn.net/v/t39.30808-6/474257451_1125606045685499_1736759892805951741_n.jpg?_nc_cat=107&ccb=1-7&_nc_sid=a5f93a&_nc_ohc=eSizpKzxQ-AQ7kNvwF-bPi6&_nc_oc=AdliDlnYj5Cmbi5nAUFbnpXcDKQ4zRLZLcy0Qq5_qS-RkwvoPHoFKxPwfMv0ay7tWrw&_nc_zt=23&_nc_ht=scontent.fisj1-1.fna&_nc_gid=GIdVYSZ6Rw0n2Hx5lD4Ukw&oh=00_Afj3TVmZRlDcGODfrWR7T7Ld_p9ipKNUJcQrgrGmW-3RNQ&oe=692D0931" class="foto-superior" alt="Foto de Angel Michel">
</header>

<nav>
    <a href="#sobre-mi">Sobre mí</a>
    <a href="#proyectos">Trabajos</a>
    <a href="#contacto">Contacto</a>
</nav>

<nav>
    <span>06</span>
    <span>ABRIL</span>
    <span>2004</span>
</nav>


<section id="sobre-mi">
    <h2>Sobre mí</h2>

    <p>
        Soy una persona creativa, astuta, ambiciosa y determinada, cualidades que aplico en cada desafío profesional. 
        Quienes me conocen destacan mi integridad, compromiso y vocación de servicio, especialmente en el trabajo en 
        equipo y la atención al cliente. Nací el 06 de Abril del 2004 . actualmente tengo 21 años. 
    </p>

    <h3>Habilidades y Competencias</h3>
    <ul>
        <li>Técnicas de venta y persuasión</li>
        <li>Cierre efectivo de ventas</li>
        <li>Servicio al cliente personalizado</li>
        <li>Conocimiento en dispositivos móviles (Android e iOS)</li>
        <li>Asesoría en planes y servicios de telecomunicaciones</li>
        <li>Manejo de software de punto de venta (POS)</li>
        <li>Uso de CRM y sistemas de seguimiento de clientes</li>
        <li>Manejo de efectivo y arqueos de caja</li>
        <li>Procesamiento de pagos con tarjeta y transferencias</li>
        <li>Manejo intermedio de Excel y Word</li>
        <li>Redacción de reportes de ventas</li>
        <li>Organización de bases de datos de clientes</li>
    </ul>
</section>


<section id="proyectos">
    <h2>Trabajos</h2>
    <div class="projects">

        <!-- AT&T -->
        <div class="project-card">
            <h3>AT&T</h3>
            <p>GERENTE DE TIENDA — 11 MESES</p>

            <details>
                <summary>Ver más</summary>
                <div>
                    <p>
                        Supervisión de operaciones diarias, administración de inventario, gestión de personal 
                        y cumplimiento de metas de ventas. <br><br>

                        <strong>Contactos donde pueden comunicarse:</strong><br>
                        Juan Carlos (Regional de la zona y supervisor de mi puesto)<br>
                        <strong>Número telefónico:</strong> 999 589 3630
                    </p>

                    <img 
                        src="https://scontent.fisj1-1.fna.fbcdn.net/v/t39.30808-6/561648145_122146969688722748_7652924657870108957_n.jpg?_nc_cat=103&ccb=1-7&_nc_sid=6ee11a&_nc_ohc=d1M55pDFv2MQ7kNvwFEBuKq&_nc_oc=AdlcqdhBgPFElUyGzpFNvteNn1XobJ7fX2h1hohA2It2vvzcjBPJ0s1PhEt6TSYJQpE&_nc_zt=23&_nc_ht=scontent.fisj1-1.fna&_nc_gid=foml9GFzYsiIQtQxfVJL4w&oh=00_AfjFLCy_HX66ZnKQwx0LcO5QOYTkvnrPVeG2aitYyAQU_A&oe=692D5B75"
                        class="img-detalle" 
                        alt="AT&T"
                    >
                </div>
            </details>
        </div> <!-- cierre correcto -->

        <!-- MACROPAY -->
        <div class="project-card">
            <h3>MACROPAY</h3>
            <p>ASESOR DE VENTAS Y ENCARGADO — 9 MESES</p>

            <details>
                <summary>Ver más</summary>
                <div>
                    <p>
                        Atención al cliente, colocación de créditos, selección de productos y control de inventario. 
                        <br><br>

                        <strong>Contacto donde pueden comunicarse:</strong><br>
                        Alan Jair (Gerente de tienda en el momento donde trabajé) <br>
                        <strong>Número telefónico:</strong> 984 319 2715
                    </p>

                    <img 
                        src="https://newspack-yucatan.s3.amazonaws.com/uploads/2021/12/foto-1.jpg"
                        class="img-detalle" 
                        alt="Macropay"
                    >
                </div>
            </details>
        </div>

        <!-- OXXO -->
        <div class="project-card">
            <h3>OXXO</h3>
            <p>AYUDANTE DE PISO — 3 MESES</p>

            <details>
                <summary>Ver más</summary>
                <div>
                    <p>Manejo de caja, inventarios, recepción de mercancía y control de caducidades.</p>
                    <img 
                        src="https://elceo.com/wp-content/uploads/2023/03/oxxo-1.jpg" 
                        class="img-detalle" 
                        alt="Oxxo"
                    >
                </div>
            </details>
        </div>

    </div>
</section>


<section id="contacto">
    <h2>Contacto</h2>
    <p>Email: <strong>angelmichellopezgarcia@gmail.com</strong></p>
    <p>Teléfono: <strong>5630-8991-73</strong></p>
    <p>Facebook: 
        <a href="https://www.facebook.com/michel.326842" target="_blank" style="color:#00eaff;">
            michel.326842
        </a>
    </p>
    <p>WhatsApp: 
        <a href="https://wa.me/525630899173" target="_blank" style="color:#25D366;">
            Enviar mensaje
        </a>
    </p>
</section>


<footer>
    © 2025 - ANGEL MICHEL LOPEZ GARCIA - EXPERIENCIA LABORAL
</footer>

</body>
</html>
