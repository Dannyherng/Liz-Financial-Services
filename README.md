<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Liz Financial</title>
    <style>
        body { font-family: Arial, sans-serif; margin: 0; padding: 0; background-color: #f4f4f4; }
        header { background-color: #0056b3; color: white; padding: 15px; text-align: center; }
        nav { text-align: center; padding: 10px; background: #0073e6; position: fixed; width: 100%; top: 0; left: 0; }
        nav a { color: white; text-decoration: none; margin: 0 15px; font-weight: bold; }
        section { padding: 80px 20px 20px; text-align: center; }
        footer { background-color: #0056b3; color: white; text-align: center; padding: 10px; position: relative; width: 100%; }
        .contact-form { max-width: 400px; margin: auto; background: white; padding: 20px; border-radius: 8px; box-shadow: 0 0 10px rgba(0,0,0,0.1); }
        .contact-form input, .contact-form textarea { width: 100%; padding: 10px; margin: 5px 0; border: 1px solid #ccc; border-radius: 5px; }
        .contact-form button { background-color: #0073e6; color: white; padding: 10px; border: none; cursor: pointer; width: 100%; }
        .contact-form button:hover { background-color: #0056b3; }
        .social-icons { margin-top: 20px; }
        .social-icons a { margin: 0 10px; text-decoration: none; font-size: 24px; color: #0073e6; }
    </style>
</head>
<body>
    <header>
        <h1>Liz Financial</h1>
        <p>Seguros de Vida y Salud | Construcción y Reparación de Crédito | Taxes</p>
    </header>
    <nav>
        <a href="#seguros">Seguros</a>
        <a href="#credito">Crédito</a>
        <a href="#taxes">Taxes</a>
        <a href="#contacto">Contacto</a>
    </nav>
    <section id="seguros">
        <h2>Seguros de Vida y Salud</h2>
        <p>Protege tu futuro y el de tu familia con nuestras opciones de seguros.</p>
    </section>
    <section id="credito">
        <h2>Construcción de Crédito</h2>
        <p>Mejora tu historial crediticio con estrategias seguras y efectivas.</p>
    </section>
    <section id="taxes">
        <h2>Preparación de Taxes</h2>
        <p>Declaraciones de impuestos precisas y seguras para tu tranquilidad.</p>
    </section>
    <section id="contacto">
        <h2>Contacto</h2>
        <p>Déjanos ayudarte. Contáctanos al (786) 622-4993 o envíanos un mensaje.</p>
        <div class="contact-form">
            <input type="text" placeholder="Tu Nombre" required>
            <input type="email" placeholder="Tu Correo Electrónico" required>
            <textarea placeholder="Tu Mensaje" rows="4" required></textarea>
            <button type="submit">Enviar</button>
        </div>
        <div class="social-icons">
            <a href="https://www.facebook.com/share/1FRHmdE3J1/?mibextid=wwXIfr" target="_blank">📘 Facebook</a>
            <a href="https://wa.me/17866224993" target="_blank">📞 WhatsApp</a>
        </div>
    </section>
    <footer>
        <p>&copy; 2025 Liz Financial. Todos los derechos reservados.</p>
    </footer>
</body>
</html>
