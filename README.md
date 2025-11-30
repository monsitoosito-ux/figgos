<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Términos y Privacidad - Figgo</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        :root {
            --primary-blue: #1a73e8;
            --dark-blue: #0d47a1;
            --light-blue: #e8f0fe;
            --white: #ffffff;
            --text-dark: #202124;
            --text-light: #5f6368;
            --border-color: #dadce0;
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background-color: #f8f9fa;
            color: var(--text-dark);
            line-height: 1.6;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }
        
        /* Header Styles */
        header {
            background: linear-gradient(135deg, var(--primary-blue), var(--dark-blue));
            color: var(--white);
            padding: 30px 0;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
        }
        
        .header-content {
            display: flex;
            align-items: center;
            justify-content: space-between;
        }
        
        .logo {
            display: flex;
            align-items: center;
            gap: 15px;
        }
        
        .logo-icon {
            font-size: 2.5rem;
            background: rgba(255, 255, 255, 0.2);
            padding: 12px;
            border-radius: 50%;
        }
        
        .logo-text {
            font-size: 2.2rem;
            font-weight: 700;
        }
        
        .tagline {
            font-size: 1.1rem;
            opacity: 0.9;
            margin-top: 5px;
        }
        
        /* Navigation */
        .nav-tabs {
            display: flex;
            background: var(--white);
            border-radius: 8px 8px 0 0;
            overflow: hidden;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }
        
        .nav-tab {
            flex: 1;
            text-align: center;
            padding: 18px 0;
            font-weight: 600;
            cursor: pointer;
            transition: all 0.3s ease;
            border-bottom: 3px solid transparent;
        }
        
        .nav-tab.active {
            color: var(--primary-blue);
            border-bottom: 3px solid var(--primary-blue);
            background-color: var(--light-blue);
        }
        
        .nav-tab:hover:not(.active) {
            background-color: #f5f5f5;
        }
        
        /* Content Sections */
        .content-section {
            display: none;
            background: var(--white);
            padding: 40px;
            border-radius: 0 0 8px 8px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.08);
            margin-bottom: 40px;
        }
        
        .content-section.active {
            display: block;
        }
        
        h1 {
            color: var(--dark-blue);
            margin-bottom: 25px;
            font-size: 2rem;
            border-bottom: 2px solid var(--light-blue);
            padding-bottom: 10px;
        }
        
        h2 {
            color: var(--primary-blue);
            margin: 30px 0 15px;
            font-size: 1.5rem;
        }
        
        h3 {
            color: var(--text-dark);
            margin: 20px 0 10px;
            font-size: 1.2rem;
        }
        
        p {
            margin-bottom: 15px;
            color: var(--text-light);
        }
        
        ul, ol {
            margin: 15px 0 15px 30px;
            color: var(--text-light);
        }
        
        li {
            margin-bottom: 8px;
        }
        
        .legal-reference {
            background: var(--light-blue);
            padding: 15px;
            border-radius: 8px;
            margin: 20px 0;
            border-left: 4px solid var(--primary-blue);
        }
        
        .legal-reference h4 {
            color: var(--dark-blue);
            margin-bottom: 8px;
        }
        
        .highlight {
            background-color: #fff8e1;
            padding: 15px;
            border-radius: 8px;
            margin: 20px 0;
            border-left: 4px solid #ffc107;
        }
        
        .contact-info {
            background: var(--light-blue);
            padding: 20px;
            border-radius: 8px;
            margin-top: 30px;
        }
        
        .contact-info h3 {
            color: var(--dark-blue);
            margin-bottom: 15px;
        }
        
        .location-badge {
            display: inline-flex;
            align-items: center;
            gap: 8px;
            background: var(--light-blue);
            color: var(--dark-blue);
            padding: 8px 15px;
            border-radius: 20px;
            font-size: 0.9rem;
            margin-top: 10px;
        }
        
        /* Footer */
        footer {
            background: var(--dark-blue);
            color: var(--white);
            padding: 30px 0;
            text-align: center;
        }
        
        .footer-content {
            display: flex;
            flex-direction: column;
            align-items: center;
            gap: 20px;
        }
        
        .footer-logo {
            font-size: 1.8rem;
            font-weight: 700;
        }
        
        .footer-links {
            display: flex;
            gap: 25px;
            margin: 15px 0;
        }
        
        .footer-links a {
            color: var(--white);
            text-decoration: none;
            transition: opacity 0.3s;
        }
        
        .footer-links a:hover {
            opacity: 0.8;
            text-decoration: underline;
        }
        
        .copyright {
            opacity: 0.8;
            font-size: 0.9rem;
        }
        
        /* Responsive */
        @media (max-width: 768px) {
            .header-content {
                flex-direction: column;
                text-align: center;
                gap: 20px;
            }
            
            .nav-tabs {
                flex-direction: column;
            }
            
            .content-section {
                padding: 25px;
            }
            
            .footer-links {
                flex-direction: column;
                gap: 15px;
            }
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <div class="header-content">
                <div class="logo">
                    <div class="logo-icon">
                        <i class="fas fa-map-marker-alt"></i>
                    </div>
                    <div>
                        <div class="logo-text">Figgo</div>
                        <div class="tagline">Conectando talento con oportunidades</div>
                        <div class="location-badge">
                            <i class="fas fa-map-pin"></i>
                            San Andrés de Tumaco, Nariño
                        </div>
                    </div>
                </div>
                <div class="header-info">
                    <p><i class="fas fa-shield-alt"></i> Protegemos tus datos según las leyes colombianas</p>
                </div>
            </div>
        </div>
    </header>
    
    <div class="container">
        <div class="nav-tabs">
            <div class="nav-tab active" data-target="terms">Términos de Servicio</div>
            <div class="nav-tab" data-target="privacy">Política de Privacidad</div>
        </div>
        
        <section id="terms" class="content-section active">
            <h1>Términos de Servicio de Figgo</h1>
            
            <p>Última actualización: Enero, 2025</p>
            
            <div class="legal-reference">
                <h4><i class="fas fa-balance-scale"></i> Marco Legal Colombiano</h4>
                <p>Estos términos se rigen por la Constitución Política de Colombia, el Código de Comercio (Decreto 410 de 1971), la Ley 1480 de 2011 (Estatuto del Consumidor) y la Ley 527 de 1999 (Comercio Electrónico).</p>
            </div>
            
            <h2>1. Aceptación de los Términos</h2>
            <p>Al registrarte, acceder o utilizar la aplicación Figgo ("la App"), usted ("el Usuario") acepta de manera expresa e inequívoca estar legalmente vinculado por estos Términos de Servicio y nuestra Política de Privacidad.</p>
            
            <h2>2. Definiciones</h2>
            <ul>
                <li><strong>"App" o "Plataforma":</strong> Figgo, propiedad de Figgo Colombia.</li>
                <li><strong>"Usuario Talent" o "Trabajador":</strong> Persona natural que crea un perfil profesional para ofrecer sus servicios.</li>
                <li><strong>"Usuario Contratante":</strong> Persona natural o jurídica que utiliza la App para buscar y contactar Talentos.</li>
                <li><strong>"Contenido del Usuario":</strong> Información, textos, fotos, portafolios y cualquier material publicado en la Plataforma.</li>
            </ul>
            
            <h2>3. Descripción del Servicio</h2>
            <p>Figgo actúa como un mercado digital que facilita la conexión entre Usuarios Talent y Usuarios Contratantes. Figgo NO es un empleador de los Usuarios Talent. La App no garantiza empleo ni contratación.</p>
            
            <div class="highlight">
                <p><strong>Nota importante:</strong> Cualquier acuerdo de trabajo o servicio que se genere entre los Usuarios es un contrato directo entre ellos, del cual Figgo no es parte.</p>
            </div>
            
            <h2>4. Registro y Cuentas</h2>
            <p>Es obligatorio ser mayor de 18 años y tener capacidad legal para contratar según el Código Civil Colombiano.</p>
            
            <h3>Para Usuarios Talent:</h3>
            <p>Al crear un perfil, declara y garantiza que la información sobre su experiencia, habilidades y formación es veraz, exacta y actualizada.</p>
            
            <h3>Para Usuarios Contratantes:</h3>
            <p>Se compromete a utilizar la información de los Usuarios Talent únicamente para fines de evaluación para posibles contrataciones.</p>
            
            <h2>5. Uso Aceptable</h2>
            <p>Queda prohibido:</p>
            <ul>
                <li>Publicar información falsa o engañosa en el perfil profesional.</li>
                <li>Contactar a otros usuarios con fines distintos a la contratación de servicios.</li>
                <li>Suplantar la identidad de otra persona o empresa.</li>
                <li>Eludir el sistema de la App para realizar pagos fuera de la plataforma.</li>
                <li>Publicar contenido que viole derechos de autor.</li>
            </ul>
            
            <h2>6. Relación entre las Partes</h2>
            <p>El Usuario reconoce y acepta expresamente que Figgo actúa únicamente como intermediario y que no es parte de ninguna relación laboral, comercial o contractual que pueda surgir entre el Usuario Talent y el Usuario Contratante.</p>
            
            <h2>7. Propiedad Intelectual</h2>
            <p>El Usuario Talent conserva todos los derechos de propiedad intelectual sobre los elementos de su portafolio. Al publicarlos en la App, otorga a Figgo una licencia no exclusiva para mostrar dicho contenido únicamente con el fin de operar y promocionar la Plataforma.</p>
            
            <h2>8. Terminación</h2>
            <p>Nos reservamos el derecho de suspender o eliminar cuentas que violen estos Términos, publiquen información fraudulenta o realicen actividades que dañen la integridad de la Plataforma.</p>
            
            <h2>9. Limitación de Responsabilidad</h2>
            <p>En la máxima medida permitida por la ley colombiana, Figgo no será responsable por daños emergentes, indirectos o consecuentes derivados del uso de la App o de cualquier acuerdo entre Usuarios.</p>
            
            <h2>10. Ley Aplicable</h2>
            <p>Estos Términos de Servicio se regirán e interpretarán de acuerdo con las leyes de la República de Colombia. Cualquier disputa se someterá a los tribunales competentes de San Andrés de Tumaco, Nariño, Colombia.</p>
            
            <div class="contact-info">
                <h3>Información Legal</h3>
                <p>Para consultas sobre estos Términos de Servicio: <strong>legal@figgo.com</strong></p>
                <p><i class="fas fa-map-marker-alt"></i> <strong>Domicilio:</strong> San Andrés de Tumaco, Nariño, Colombia</p>
            </div>
        </section>
        
        <section id="privacy" class="content-section">
            <h1>Política de Privacidad de Figgo</h1>
            
            <p>Última actualización: Enero, 2025</p>
            
            <div class="legal-reference">
                <h4><i class="fas fa-user-shield"></i> Protección de Datos en Colombia</h4>
                <p>Esta política se ajusta a la Ley 1581 de 2012 y el Decreto 1377 de 2013 (Protección de Datos Personales), garantizando los derechos de los titulares de información establecidos en la Constitución Política de Colombia.</p>
            </div>
            
            <h2>1. Responsable del Tratamiento</h2>
            <p><strong>Figgo Colombia</strong>, con domicilio principal en San Andrés de Tumaco, Nariño, Colombia, es el Responsable del Tratamiento de los datos personales.</p>
            
            <h2>2. Datos Personales Recopilados</h2>
            
            <h3>Para Usuarios Talent (Perfil Público):</h3>
            <ul>
                <li>Nombre, foto, profesión, habilidades</li>
                <li>Experiencia laboral, formación académica</li>
                <li>Portafolio (imágenes, textos)</li>
                <li>Ubicación, tarifas</li>
            </ul>
            
            <h3>Para Todos los Usuarios (Datos de Registro):</h3>
            <ul>
                <li>Correo electrónico, número de teléfono</li>
                <li>Datos de contacto</li>
            </ul>
            
            <h3>Datos Recopilados Automáticamente:</h3>
            <ul>
                <li>Dirección IP, tipo de dispositivo</li>
                <li>Historial de búsquedas e interacciones</li>
                <li>Ubicación (para conectar con talentos cercanos)</li>
            </ul>
            
            <h2>3. Finalidades del Tratamiento</h2>
            <p>Utilizamos sus datos para:</p>
            <ul>
                <li>Crear y mostrar su perfil profesional en la Plataforma</li>
                <li>Permitir la búsqueda, filtrado y contacto entre usuarios</li>
                <li>Gestionar su cuenta y prestar soporte</li>
                <li>Enviar comunicaciones transaccionales</li>
                <li>Realizar análisis para mejorar el servicio</li>
                <li>Marketing (solo con su autorización expresa)</li>
            </ul>
            
            <h2>4. Autorización del Titular</h2>
            <p>En cumplimiento de la Ley 1581 de 2012, al registrarse en la App y marcar la casilla correspondiente, el Usuario otorga su autorización expresa, previa, informada y voluntaria a Figgo para el tratamiento de sus datos personales para las finalidades descritas.</p>
            
            <div class="highlight">
                <p><strong>Derechos del Titular:</strong> Usted tiene derecho a conocer, actualizar, rectificar y suprimir su información personal, así como a revocar su autorización.</p>
            </div>
            
            <h2>5. Ejercicio de Derechos Habeas Data</h2>
            <p>Como titular de sus datos, usted puede:</p>
            <ol>
                <li>Acceder, conocer y actualizar sus datos</li>
                <li>Solicitar prueba de la autorización otorgada</li>
                <li>Ser informado sobre el uso de sus datos</li>
                <li>Presentar quejas ante la Superintendencia de Industria y Comercio (SIC)</li>
                <li>Revocar la autorización</li>
                <li>Solicitar la supresión de sus datos</li>
            </ol>
            
            <p>Para ejercer estos derechos, envíe una solicitud al correo: <strong>privacidad@figgo.com</strong></p>
            
            <h2>6. Transferencia y Transmisión de Datos</h2>
            <p>Sus datos del perfil público (Talent) serán visibles para todos los usuarios de la App. Sus datos de contacto de registro NO se compartirán abiertamente, sino a través del sistema de mensajería interno de la App.</p>
            
            <h2>7. Seguridad de los Datos</h2>
            <p>Implementamos medidas técnicas, administrativas y humanas para proteger sus datos personales contra pérdida, acceso no autorizado o uso indebido, de acuerdo con los estándares exigidos por la ley colombiana.</p>
            
            <h2>8. Conservación de la Información</h2>
            <p>Conservaremos sus datos personales durante el tiempo necesario para cumplir con las finalidades descritas en esta política, o según lo requiera la ley colombiana.</p>
            
            <div class="contact-info">
                <h3>Información Legal</h3>
                <p>Para ejercer sus derechos de protección de datos: <strong>privacidad@figgo.com</strong></p>
                <p><i class="fas fa-map-marker-alt"></i> <strong>Domicilio:</strong> San Andrés de Tumaco, Nariño, Colombia</p>
            </div>
        </section>
    </div>
    
    <footer>
        <div class="container">
            <div class="footer-content">
                <div class="footer-logo">Figgo</div>
                <p>Conectando el talento colombiano con oportunidades locales</p>
                <div class="footer-links">
                    <a href="#terms">Términos de Servicio</a>
                    <a href="#privacy">Política de Privacidad</a>
                </div>
                <div class="copyright">
                    &copy; 2025 Figgo Colombia. Todos los derechos reservados.<br>
                    San Andrés de Tumaco, Nariño
                </div>
            </div>
        </div>
    </footer>
    
    <script>
        document.addEventListener('DOMContentLoaded', function() {
            const tabs = document.querySelectorAll('.nav-tab');
            
            tabs.forEach(tab => {
                tab.addEventListener('click', function() {
                    // Remove active class from all tabs and sections
                    tabs.forEach(t => t.classList.remove('active'));
                    document.querySelectorAll('.content-section').forEach(section => {
                        section.classList.remove('active');
                    });
                    
                    // Add active class to clicked tab and corresponding section
                    this.classList.add('active');
                    const targetId = this.getAttribute('data-target');
                    document.getElementById(targetId).classList.add('active');
                });
            });
        });
    </script>
</body>
</html>
