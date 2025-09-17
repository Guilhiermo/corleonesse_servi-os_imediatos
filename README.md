<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Corleonesse Serviços Imediatos</title>
    <style>
        /* Estilos generales */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Arial', sans-serif;
        }

        body {
            background: #f0f0f0;
        }

        /* Header */
        .header {
            background: linear-gradient(45deg, #000000, #008000, #0000FF);
            color: white;
            padding: 20px;
            text-align: center;
        }

        .logo {
            font-size: 2.5em;
            font-weight: bold;
        }

        .logo span:nth-child(1) { color: #000000; } /* CORLE */
        .logo span:nth-child(2) { color: #0000FF; } /* ONESSE */

        /* Hero Section */
        .hero {
            background: #40E0D0;
            padding: 60px 20px;
            text-align: center;
            color: white;
        }

        .tagline {
            font-size: 1.5em;
            margin: 20px 0;
        }

        /* Servicios */
        .services {
            padding: 40px 20px;
            background: white;
        }

        .services-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            max-width: 1200px;
            margin: 0 auto;
        }

        .service-card {
            background: #f8f8f8;
            padding: 20px;
            border-radius: 10px;
            text-align: center;
        }

        .service-icon {
            font-size: 3em;
            margin: 15px 0;
            color: #008000;
        }

        /* Contacto */
        .contact {
            background: #0000FF;
            color: white;
            padding: 40px 20px;
            text-align: center;
        }

        .contact-form {
            max-width: 500px;
            margin: 0 auto;
        }

        input, textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: none;
            border-radius: 5px;
        }

        button {
            background: #40E0D0;
            color: white;
            padding: 15px 30px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 1.1em;
        }

        /* Footer */
        footer {
            background: #000000;
            color: white;
            text-align: center;
            padding: 20px;
        }

        /* Responsive */
        @media (max-width: 768px) {
            .logo { font-size: 1.8em; }
            .tagline { font-size: 1.2em; }
        }
    </style>
</head>
<body>
    <!-- Header -->
    <header class="header">
        <div class="logo">
            <span>CORLE</span><span>ONESSE</span><br>
            <span style="font-size: 0.5em; color: white;">SERVICES_IMEDIATOS</span>
        </div>
    </header>

    <!-- Hero -->
    <section class="hero">
        <h1 class="tagline">Serviços Rápidos para Sua Casa e Jardim</h1>
        <p>📞 96127 44565 | ✉️ corleonesseservicosimediatos@gmail.com</p>
    </section>

    <!-- Servicios -->
    <section class="services">
        <div class="services-grid">
            <div class="service-card">
                <div class="service-icon">🖌️</div>
                <h3>Pintura</h3>
                <p>Residências, prédios e comércios com serviço 24h.</p>
            </div>
            <div class="service-card">
                <div class="service-icon">🌿</div>
                <h3>Jardinagem</h3>
                <p>Renovação de jardins, cercas e áreas externas.</p>
            </div>
            <div class="service-card">
                <div class="service-icon">🔧</div>
                <h3>Reparos</h3>
                <p>Objetos delicados, móveis e equipamentos.</p>
            </div>
        </div>
    </section>

    <!-- Contacto -->
    <section class="contact">
        <h2>Entre em Contato!</h2>
        <form class="contact-form" action="https://formspree.io/f/xzblwvwj" method="POST">
            <input type="text" name="name" placeholder="Seu Nome" required>
            <input type="tel" name="phone" placeholder="Seu Telefone" required>
            <textarea name="message" rows="4" placeholder="Mensagem" required></textarea>
            <button type="submit">Enviar</button>
        </form>
    </section>

    <!-- Footer -->
    <footer>
        <p>© 2025 Corleonesse Serviços Imediatos. Todos os direitos reservados.</p>
    </footer>

    <!-- WhatsApp Button -->
    <script>
        // Botón de WhatsApp flotante
        const whatsappBtn = document.createElement('a');
        whatsappBtn.href = 'https://wa.me/55119612744565?text=Olá!%20Quero%20saber%20mais%20sobre%20seus%20serviços';
        whatsappBtn.target = '_blank';
        whatsappBtn.innerHTML = `
            <div style="
                position: fixed;
                bottom: 20px;
                right: 20px;
                background: #25D366;
                color: white;
                padding: 15px;
                border-radius: 50%;
                font-size: 2em;
                box-shadow: 2px 2px 6px rgba(0,0,0,0.4);
                cursor: pointer;
            ">
                📲
            </div>
        `;
        document.body.appendChild(whatsappBtn);
    </script>
</body>
</html>
