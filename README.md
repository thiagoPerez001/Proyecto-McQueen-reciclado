<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Proyecto: El McQueen Reciclado</title>
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <style>
        body {
            font-family: 'Segoe UI', Arial, sans-serif;
            background: linear-gradient(135deg, #232526 0%, #414345 100%);
            color: #e0e0e0;
            margin: 0;
            padding: 0;
        }
        .container {
            max-width: 900px;
            margin: 30px auto;
            background: #232526e6;
            border-radius: 16px;
            box-shadow: 0 4px 24px #00000099;
            padding: 32px 24px 24px 24px;
            border: 2px solid #37474f;
        }
        h1, h2, h3 {
            color: #90caf9;
        }
        h1 {
            font-size: 2.2em;
            margin-bottom: 0.2em;
            text-shadow: 1px 2px 8px #263238;
        }
        .integrantes, .docentes {
            margin-bottom: 1em;
        }
        .emoji {
            font-size: 1.2em;
        }
        ul, ol {
            margin-left: 1.2em;
        }
        .objetivos, .causas, .consecuencias, .soluciones, .materiales, .aprendizajes, .datos, .fuentes, .conclusion {
            margin-bottom: 1.5em;
        }
        .destacado {
            background: linear-gradient(90deg, #263238 0%, #37474f 100%);
            border-left: 5px solid #90caf9;
            padding: 10px 18px;
            margin: 18px 0;
            border-radius: 6px;
            font-weight: 500;
            color: #e0e0e0;
        }
        .footer {
            text-align: center;
            color: #b0bec5;
            margin-top: 30px;
            font-size: 1em;
        }
        a {
            color: #90caf9;
            font-weight: bold;
            text-decoration: none;
            transition: color 0.2s;
        }
        a:hover {
            color: #42a5f5;
            text-decoration: underline;
        }
        .btn {
            display: inline-block;
            background: linear-gradient(90deg, #263238 0%, #37474f 100%);
            color: #90caf9;
            padding: 8px 20px;
            border-radius: 20px;
            margin: 8px 0;
            font-weight: bold;
            box-shadow: 0 2px 8px #26323866;
            border: none;
            cursor: pointer;
            transition: background 0.2s, color 0.2s;
        }
        .btn:hover {
            background: linear-gradient(90deg, #90caf9 0%, #1976d2 100%);
            color: #fff;
        }
        /* Interactivo: FAQ */
        .faq {
            margin: 24px 0;
        }
        .faq-question {
            cursor: pointer;
            background: #263238;
            border: none;
            width: 100%;
            text-align: left;
            padding: 12px;
            font-size: 1.1em;
            border-radius: 8px;
            margin-bottom: 6px;
            color: #90caf9;
            transition: background 0.2s;
        }
        .faq-question:hover {
            background: #37474f;
        }
        .faq-answer {
            display: none;
            background: #37474f;
            padding: 12px;
            border-radius: 0 0 8px 8px;
            margin-bottom: 10px;
            margin-top: -6px;
            color: #e0e0e0;
        }
        /* Interactivo: Encuesta */
        .encuesta {
            background: #263238cc;
            border-radius: 10px;
            padding: 18px;
            margin: 24px 0;
            border: 1.5px solid #90caf9;
        }
        .encuesta label {
            display: block;
            margin: 10px 0 4px 0;
        }
        .encuesta input[type="text"] {
            width: 90%;
            padding: 6px;
            border-radius: 4px;
            border: 1px solid #37474f;
            background: #232526;
            color: #e0e0e0;
        }
        .encuesta .btn {
            background: linear-gradient(90deg, #1976d2 0%, #90caf9 100%);
            color: #fff;
            margin-top: 10px;
        }
        .encuesta .btn:hover {
            background: linear-gradient(90deg, #90caf9 0%, #1976d2 100%);
            color: #232526;
        }
        .encuesta-result {
            margin-top: 12px;
            color: #81c784;
            font-weight: bold;
        }
        iframe {
            background: #232526;
        }
        @media (max-width: 600px) {
            .container {
                padding: 12px 4vw;
            }
            h1 {
                font-size: 1.3em;
            }
        }
        .banner-reciclaje {
            background: linear-gradient(90deg,#232526 60%,#43a047 100%);
            color: #e0e0e0;
            padding: 24px 0 18px 0;
            text-align: center;
            border-radius: 16px;
            margin-bottom: 32px;
            box-shadow: 0 2px 12px #43a04766;
            font-weight: bold;
            letter-spacing: 1px;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            gap: 10px;
        }
        .banner-titulo {
            font-size: 2.2em;
            color: #90caf9;
            font-family: 'Segoe UI', Arial, sans-serif;
            font-weight: 700;
            margin-bottom: 8px;
            text-shadow: 1px 2px 8px #263238;
            letter-spacing: 2px;
        }
        .banner-emojis {
            display: flex;
            justify-content: center;
            gap: 10px;
        }
        @media (max-width: 600px) {
            .banner-titulo {
                font-size: 1.2em;
                margin-bottom: 4px;
            }
            .banner-reciclaje {
                padding: 12px 0 10px 0;
                border-radius: 10px;
                gap: 5px;
            }
            .banner-emojis span {
                font-size: 1.3em !important;
                margin-right: 5px !important;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- Banner como título principal mejorado con el título arriba y los emojis abajo -->
<!-- Banner sin emojis -->
<div class="banner-reciclaje">
    <span class="banner-titulo">Proyecto: El McQueen Reciclado</span>
</div>

        <h2>¿Qué hicimos?</h2>
        <p>
            Nuestro grupo decidió abordar un problema urgente y cercano: la contaminación causada por los desechos electrónicos. Investigamos a fondo y desarrollamos una parte práctica: la construcción de un auto a control remoto hecho con materiales reciclados, como motores de juguetes viejos, pilas reutilizadas, tapas de botellas y partes de plástico o cartón.
        </p>
        <div class="destacado">
            La idea era mostrar con un ejemplo tangible que es posible darle una nueva vida a componentes electrónicos que normalmente terminarían en la basura. Queríamos que este auto no fuera solo un proyecto, sino una forma de concientizar a otras personas, especialmente jóvenes, sobre el impacto que tienen sus decisiones de consumo.
        </div>

        <!-- INTERACTIVO: FAQ -->
        <div class="faq">
            <h2>Preguntas frecuentes sobre reciclaje electrónico</h2>
            <button class="faq-question">¿Por qué es importante reciclar electrónicos?</button>
            <div class="faq-answer">Porque contienen materiales peligrosos y valiosos. Reciclarlos evita contaminación y permite reutilizar recursos.</div>
            <button class="faq-question">¿Dónde puedo llevar mis electrónicos viejos?</button>
            <div class="faq-answer">En Uruguay existen puntos limpios, campañas municipales y centros de acopio de residuos electrónicos.</div>
            <button class="faq-question">¿Qué pasa si tiro una pila a la basura común?</button>
            <div class="faq-answer">Las pilas liberan metales pesados que contaminan el suelo y el agua, afectando la salud y el ambiente.</div>
        </div>

        <h2>¿Por qué lo hicimos?</h2>
        <p>
            La tecnología avanza rápido, pero eso trae consecuencias: cada vez tiramos más computadoras, celulares, electrodomésticos y aparatos electrónicos. Lo preocupante es que muchos de ellos terminan en vertederos comunes o se desechan de forma incorrecta, liberando sustancias tóxicas al ambiente.
        </p>
        <p>
            El problema es real, actual y afecta tanto al medio ambiente como a nuestra salud. Por eso decidimos investigar este tema y demostrar que, con creatividad y responsabilidad, podemos hacer algo diferente.
        </p>
        <div class="destacado">
            “No todo lo que parece basura, lo es. A veces, es una oportunidad.”
        </div>

        <!-- INTERACTIVO: ENCUESTA -->
        <div class="encuesta">
            <h2>¿Tienes alguna idea para reciclar?</h2>
            <form id="form-encuesta">
                <label for="idea">¡Cuéntanos tu idea creativa para reciclar electrónicos!</label>
                <input type="text" id="idea" name="idea" maxlength="120" required>
                <button type="submit" class="btn">Enviar</button>
            </form>
            <div id="encuesta-result" class="encuesta-result"></div>
        </div>

        <h2>Objetivos del proyecto</h2>
        <div class="objetivos">
            <b>Objetivo general:</b><br>
            Motivar el reciclaje electrónico mediante la combinación de información teórica y una propuesta práctica atractiva.
            <br><br>
            <b>Objetivos específicos:</b>
            <ul>
                <li>Investigar profundamente la problemática de los residuos electrónicos y su impacto ambiental y social.</li>
                <li>Comprender las causas, consecuencias y posibles soluciones.</li>
                <li>Diseñar y construir un prototipo funcional con materiales reciclados.</li>
                <li>Compartir lo aprendido y sensibilizar a otros estudiantes.</li>
            </ul>
        </div>

        <h2>¿Cuál es el problema?</h2>
        <div class="destacado">
            <b>Pregunta guía:</b> ¿Cómo reducir la contaminación causada por productos electrónicos?
        </div>
        <p>
            Hoy en día, miles de dispositivos electrónicos son desechados sin un tratamiento adecuado. Esto genera altos niveles de contaminación y riesgos para la salud. Las causas de esta problemática son muchas:
        </p>
        <div class="causas">
            <b>Causas:</b>
            <ul>
                <li>Obsolescencia programada: Los productos están diseñados para durar poco.</li>
                <li>Consumo impulsivo: Cambiamos de celular o computadora sin que el anterior esté roto.</li>
                <li>Falta de leyes claras: No todos los países tienen normativas estrictas.</li>
                <li>Desinformación: Muchas personas no saben que se puede reciclar o cómo hacerlo.</li>
                <li>Dificultad para reparar: Muchas veces es más caro reparar que comprar algo nuevo.</li>
            </ul>
        </div>
        <div class="consecuencias">
            <b>Consecuencias:</b>
            <ul>
                <li>Contaminación del aire: Al quemar residuos electrónicos se liberan gases tóxicos como dioxinas.</li>
                <li>Contaminación del agua: Metales como plomo y mercurio llegan a ríos y mares.</li>
                <li>Contaminación del suelo: Componentes como cromo o cadmio dañan los cultivos y se filtran en el suelo.</li>
                <li>Problemas de salud: Estos contaminantes causan cáncer, problemas renales y hormonales.</li>
                <li>Pérdida de biodiversidad: Ecosistemas enteros se ven afectados por los residuos mal gestionados.</li>
            </ul>
        </div>

        <h2>¿Qué soluciones hay?</h2>
        <div class="soluciones">
            <p>
                La contaminación por residuos electrónicos no es inevitable, pero requiere compromiso de toda la sociedad. Algunas acciones que pueden marcar la diferencia:
            </p>
            <b>Buenas prácticas:</b>
            <ul>
                <li>Reducir el consumo: Comprar solo lo necesario y evitar el “último modelo” si no lo precisamos.</li>
                <li>Reutilizar: Donar o vender dispositivos que aún funcionen.</li>
                <li>Reparar: Apostar a técnicos en lugar de desechar por pequeños fallos.</li>
                <li>Reciclar correctamente: Llevar los residuos a centros especializados.</li>
                <li>Apoyar buenas marcas: Elegir empresas con políticas de reciclaje y ecodiseño.</li>
                <li>Economía circular: Favorecer modelos donde los productos puedan reacondicionarse y reusarse.</li>
            </ul>
            <p>
                En nuestro caso, apostamos a la creatividad y el ejemplo práctico. Con nuestro auto a control remoto, buscamos demostrar que reciclar también puede ser divertido, accesible y útil.
            </p>
        </div>

        <h2>La parte práctica: el auto reciclado</h2>
        <div class="materiales">
            <p>
                Uno de los pilares del proyecto fue construir un auto a control remoto a partir de componentes electrónicos reciclados y materiales simples. Esto no solo validó nuestra hipótesis, sino que también atrajo la atención de otros compañeros.
            </p>
            <b>Materiales utilizados:</b>
            <ul>
                <li>Motores pequeños (de secadores viejos o juguetes rotos)</li>
                <li>Ruedas (CDs usados, tapas de botellas)</li>
                <li>Carcasa (cartón, plástico duro)</li>
                <li>Baterías recargables</li>
                <li>Cables y conectores recuperados</li>
            </ul>
            <b>Video guía que tomamos como inspiración:</b>
            <br>
            <iframe width="100%" height="360" style="max-width:560px;border-radius:12px;border:none;box-shadow:0 2px 12px #b2ebf2;" 
src="https://www.youtube.com/embed/VIgQR1Caxrc" 
title="Video de YouTube - Auto reciclado" 
frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
allowfullscreen></iframe>
        </div>

        <h2>¿Qué aprendimos?</h2>
        <div class="aprendizajes">
            <ul>
                <li>Se pueden reutilizar muchas partes sin tener conocimientos técnicos complejos.</li>
                <li>El reciclaje puede ser creativo y motivador.</li>
                <li>Lo “viejo” puede transformarse en algo totalmente nuevo.</li>
            </ul>
        </div>

        <h2>Datos e investigaciones que usamos</h2>
        <div class="datos">
            <b>Algunos datos que nos impactaron:</b>
            <ul>
                <li>En Uruguay se generan 12 kg de residuos electrónicos por habitante cada año.</li>
                <li>Solo un pequeño porcentaje se recicla correctamente.</li>
                <li>Las “ceibalitas” del Plan Ceibal se reacondicionan: 20.000 computadoras se reparan por mes.</li>
                <li>Países como Austria reciclan el 70% de sus RAEE (residuos de aparatos eléctricos y electrónicos).</li>
            </ul>
        </div>
        <div class="fuentes">
            <b>Investigamos fuentes como:</b>
            <ul>
                <li>CEMPRE (Centro de Promoción del Reciclaje)</li>
                <li>Plan Nacional de Gestión de Residuos</li>
                <li>Monitor de Residuos Electrónicos de la ONU</li>
                <li>Ministerio de Ambiente del Uruguay</li>
                <li>Organismos internacionales como la ONU y la OMS</li>
            </ul>
        </div>

        <h2>Fuentes</h2>
        <div class="fuentes">
            <b>Investigamos fuentes como:</b>
            <ul>
                <li>CEMPRE (Centro de Promoción del Reciclaje)</li>
                <li>Plan Nacional de Gestión de Residuos</li>
                <li>Monitor de Residuos Electrónicos de la ONU</li>
                <li>Ministerio de Ambiente del Uruguay</li>
                <li>Organismos internacionales como la ONU y la OMS</li>
            </ul>
        </div>

        <h2>Hipótesis</h2>
        <div class="destacado">
            “Si construimos un auto utilizando partes electrónicas recicladas, entonces demostraremos que es posible reutilizar materiales de aparatos electrónicos en desuso para crear nuevos objetos funcionales.”
        </div>
        <ul>
            <li>La hipótesis fue confirmada con la elaboración exitosa de nuestro prototipo.</li>
            <li>También generamos conciencia en otros grupos que se interesaron por la idea.</li>
            <li>Logramos comprobar que el reciclaje puede ser educativo y práctico.</li>
        </ul>

        <h2>Nuestro cronograma</h2>
<p>
    Nos organizamos en distintas etapas, dividiendo tareas por fechas, roles e integrantes. Planificamos nuestras actividades usando un cronograma online.
</p>
<ul>
    <li><a class="btn" href="#" target="_blank">Ver presentación final del proyecto</a></li>
</ul>

        <h2>Conclusión</h2>
        <div class="conclusion">
            Con este proyecto logramos mucho más que construir un auto: abrimos una puerta al cambio de hábitos.<br><br>
            Aprendimos sobre el problema de los residuos electrónicos, buscamos soluciones reales y pusimos manos a la obra. Demostramos que la tecnología y el cuidado del medio ambiente no están en lados opuestos: pueden ir juntos.
        </div>
        <div class="destacado" style="text-align:center;">
            “Con pequeñas acciones, podemos hacer grandes diferencias. Reciclar es responsabilidad de todos.”
        </div>

        <!-- QUIZ de verdadero o falso -->
<div class="quiz-vf" style="background:#263238cc;border-radius:12px;padding:22px;margin:32px 0 24px 0;border:2px solid #43a047;box-shadow:0 2px 12px #43a04766;">
    <h2>Mini Quiz: ¿Verdadero o Falso?</h2>
    <form id="form-quiz-vf">
        <label for="quiz-nombre" style="display:block;margin-bottom:12px;">Tu nombre:</label>
        <input type="text" id="quiz-nombre" name="quiz-nombre" maxlength="40" style="width:60%;margin-bottom:18px;" required>
        <div class="quiz-pregunta">
            <b>1. En Uruguay se generan más de 10 kg de residuos electrónicos por habitante cada año.</b><br>
            <label><input type="radio" name="q1" value="verdadero" required> Verdadero</label>
            <label style="margin-left:18px;"><input type="radio" name="q1" value="falso"> Falso</label>
        </div>
        <div class="quiz-pregunta" style="margin-top:18px;">
            <b>2. El reciclaje electrónico no tiene ningún impacto en la salud de las personas.</b><br>
            <label><input type="radio" name="q2" value="verdadero" required> Verdadero</label>
            <label style="margin-left:18px;"><input type="radio" name="q2" value="falso"> Falso</label>
        </div>
        <div class="quiz-pregunta" style="margin-top:18px;">
            <b>3. Es posible construir objetos útiles usando partes de aparatos electrónicos en desuso.</b><br>
            <label><input type="radio" name="q3" value="verdadero" required> Verdadero</label>
            <label style="margin-left:18px;"><input type="radio" name="q3" value="falso"> Falso</label>
        </div>
        <div class="quiz-pregunta" style="margin-top:18px;">
            <b>4. Las pilas pueden tirarse a la basura común sin problemas.</b><br>
            <label><input type="radio" name="q4" value="verdadero" required> Verdadero</label>
            <label style="margin-left:18px;"><input type="radio" name="q4" value="falso"> Falso</label>
        </div>
        <div class="quiz-pregunta" style="margin-top:18px;">
            <b>5. El reciclaje electrónico ayuda a reducir la contaminación del agua y del suelo.</b><br>
            <label><input type="radio" name="q5" value="verdadero" required> Verdadero</label>
            <label style="margin-left:18px;"><input type="radio" name="q5" value="falso"> Falso</label>
        </div>
        <button type="submit" class="btn" style="margin-top:18px;">Enviar respuestas</button>
    </form>
    <div id="quiz-vf-result" class="encuesta-result" style="margin-top:14px;"></div>
</div>

<!-- Apartado privado para ver ideas sugeridas y resultados del quiz -->
<!-- Solo el emoji de reciclaje para abrir el panel secreto -->
<span id="admin-icon" title="Acceso privado" style="position:fixed;bottom:24px;right:24px;font-size:2.5em;cursor:pointer;z-index:999;color:#43a047;user-select:none;">
    ♻️
</span>
<div id="admin-section" style="display:none; margin-top:32px; background:linear-gradient(120deg,#263238 60%,#43a047 100%);border-radius:12px;box-shadow:0 2px 12px #43a04766;padding:24px;">
    <div style="background:linear-gradient(90deg,#43a047 60%,#232526 100%);color:#fff;padding:14px 0 10px 0;text-align:center;border-radius:10px;font-size:1.5em;font-weight:bold;letter-spacing:1px;margin-bottom:18px;box-shadow:0 2px 8px #43a04766;">
        Panel de creador
    </div>
    <h2>Ideas sugeridas</h2>
    <div style="color:#90caf9;font-weight:bold;margin-bottom:12px;">
        Visualizaciones: <span id="contador-vistas">0</span>
    </div>
    <ul id="ideas-list" style="background:#263238cc;padding:16px;border-radius:8px;border-left:4px solid #43a047;"></ul>
    <div style="margin-top:18px;color:#43a047;font-size:1.1em;">
        <b>Reciclar tecnología es cuidar el futuro.</b>
    </div>
    <hr style="margin:24px 0;">
    <h2>Resultados del Quiz</h2>
    <div id="quiz-resultados" style="background:#232526cc;padding:12px 18px;border-radius:8px;color:#90caf9;font-size:1em;max-height:180px;overflow-y:auto;"></div>
</div>

<div class="footer">
    Proyecto realizado por 2° EMS CT2 – Liceo N°1 | 2025<br>
    <b>Integrantes:</b> Bruno Reolon, Thiago Pérez, Ezequiel Arbelo, Vicente Mújica, Shtefan Acevedo
</div>
<div class="footer" style="margin-top:8px;">
    <b>Docentes:</b> Eduardo Corbo, Karina Fernández, María Meneses
</div>
    </div>
    <script>
        // Interactividad FAQ
        document.querySelectorAll('.faq-question').forEach(function(btn) {
            btn.addEventListener('click', function() {
                const answer = this.nextElementSibling;
                answer.style.display = answer.style.display === 'block' ? 'none' : 'block';
            });
        });

        // Guardar ideas en localStorage al enviar encuesta
        document.getElementById('form-encuesta').addEventListener('submit', function(e) {
            e.preventDefault();
            const idea = document.getElementById('idea').value.trim();
            const resultDiv = document.getElementById('encuesta-result');
            if(idea.length > 0) {
                // Guardar en localStorage
                let ideas = JSON.parse(localStorage.getItem('ideas')) || [];
                ideas.push(idea);
                localStorage.setItem('ideas', JSON.stringify(ideas));
                resultDiv.textContent = "¡Gracias por tu aporte! Tu idea: " + idea;
                this.reset();
            } else {
                resultDiv.textContent = "Por favor, escribe tu idea antes de enviar.";
            }
        });

        // Quiz de verdadero o falso con registro de nombre y corrección
document.getElementById('form-quiz-vf').addEventListener('submit', function(e) {
    e.preventDefault();
    const r1 = document.querySelector('input[name="q1"]:checked')?.value;
    const r2 = document.querySelector('input[name="q2"]:checked')?.value;
    const r3 = document.querySelector('input[name="q3"]:checked')?.value;
    const r4 = document.querySelector('input[name="q4"]:checked')?.value;
    const r5 = document.querySelector('input[name="q5"]:checked')?.value;
    const nombre = document.getElementById('quiz-nombre').value.trim();
    let puntaje = 0;
    let respuestas = [r1, r2, r3, r4, r5];
    const correctas = ["verdadero", "falso", "verdadero", "falso", "verdadero"];
    const preguntas = [
        "1. En Uruguay se generan más de 10 kg de residuos electrónicos por habitante cada año.",
        "2. El reciclaje electrónico no tiene ningún impacto en la salud de las personas.",
        "3. Es posible construir objetos útiles usando partes de aparatos electrónicos en desuso.",
        "4. Las pilas pueden tirarse a la basura común sin problemas.",
        "5. El reciclaje electrónico ayuda a reducir la contaminación del agua y del suelo."
    ];
    puntaje = respuestas.filter((resp, i) => resp === correctas[i]).length;
    let mensaje = "";
    if(puntaje === 5) {
        mensaje = "¡Excelente! Todas tus respuestas son correctas. 🌱";
    } else if(puntaje >= 3) {
        mensaje = "¡Muy bien! Solo te faltaron algunas. Sigue leyendo la web. 👍";
    } else {
        mensaje = "Puedes repasar la información del proyecto y volver a intentarlo. 😉";
    }
    // Mostrar detalle de respuestas
    let detalle = respuestas.map((resp, i) => {
        let esCorrecta = resp === correctas[i];
        return `<li style="margin-bottom:2px;">
            <b>${preguntas[i]}</b><br>
            <span style="color:${esCorrecta ? '#81c784' : '#e57373'}">
                Tu respuesta: ${resp ? resp.charAt(0).toUpperCase() + resp.slice(1) : '<i>Sin responder</i>'}
                ${esCorrecta ? '✔️' : `❌ (Correcta: ${correctas[i].charAt(0).toUpperCase() + correctas[i].slice(1)})`}
            </span>
        </li>`;
    }).join("");
    let resultado = `Tu puntaje: ${puntaje}/5. ${mensaje}<br><ul style="margin-top:10px;padding-left:18px;">${detalle}</ul>`;
    document.getElementById('quiz-vf-result').innerHTML = resultado;

    // Guardar resultado en localStorage con detalle de respuestas
    let quizResultados = JSON.parse(localStorage.getItem('quizResultados')) || [];
    quizResultados.push({
        nombre: nombre || "Sin nombre",
        puntaje: puntaje,
        fecha: new Date().toLocaleString(),
        respuestas: respuestas
    });
    localStorage.setItem('quizResultados', JSON.stringify(quizResultados));
});

        // Mostrar resultados del quiz y actualizar cada 5 segundos, mostrando correctas/incorrectas
function mostrarResultadosQuiz() {
    let quizResultados = JSON.parse(localStorage.getItem('quizResultados')) || [];
    const div = document.getElementById('quiz-resultados');
    const correctas = ["verdadero", "falso", "verdadero", "falso", "verdadero"];
    const preguntas = [
        "1. En Uruguay se generan más de 10 kg de residuos electrónicos por habitante cada año.",
        "2. El reciclaje electrónico no tiene ningún impacto en la salud de las personas.",
        "3. Es posible construir objetos útiles usando partes de aparatos electrónicos en desuso.",
        "4. Las pilas pueden tirarse a la basura común sin problemas.",
        "5. El reciclaje electrónico ayuda a reducir la contaminación del agua y del suelo."
    ];
    if(quizResultados.length === 0) {
        div.innerHTML = "<i>No hay respuestas registradas aún.</i>";
    } else {
        div.innerHTML = quizResultados.map((r, idx) => {
            let detalle = (r.respuestas || []).map((resp, i) => {
                let esCorrecta = resp === correctas[i];
                return `<li style="margin-bottom:2px;">
                    <b>${preguntas[i]}</b><br>
                    <span style="color:${esCorrecta ? '#81c784' : '#e57373'}">
                        Tu respuesta: ${resp ? resp.charAt(0).toUpperCase() + resp.slice(1) : '<i>Sin responder</i>'}
                        ${esCorrecta ? '✔️' : `❌ (Correcta: ${correctas[i].charAt(0).toUpperCase() + correctas[i].slice(1)})`}
                    </span>
                </li>`;
            }).join("");
            return `<div style="margin-bottom:18px;padding-bottom:8px;border-bottom:1px solid #37474f;">
                <b>${r.nombre}</b> - Puntaje: ${r.puntaje}/5 <span style="color:#b0bec5;font-size:0.9em;">(${r.fecha})</span>
                <button onclick="borrarQuiz(${idx})" style="margin-left:12px;background:#37474f;color:#90caf9;border:none;border-radius:6px;cursor:pointer;font-size:1em;" title="Eliminar registro">🗑️</button>
                <ul style="margin-top:8px;margin-bottom:0;padding-left:18px;">${detalle}</ul>
            </div>`;
        }).join("");
    }
}

// Función global para borrar un registro de quiz
window.borrarQuiz = function(idx) {
    if(confirm('¿Seguro que quieres borrar este registro de quiz?')) {
        let quizResultados = JSON.parse(localStorage.getItem('quizResultados')) || [];
        quizResultados.splice(idx, 1);
        localStorage.setItem('quizResultados', JSON.stringify(quizResultados));
        mostrarResultadosQuiz();
    }
}

        // Mostrar/ocultar apartado privado si la contraseña es correcta al hacer clic en el ícono secreto
        document.getElementById('admin-icon').addEventListener('click', function() {
            const adminSection = document.getElementById('admin-section');
            const contadorSpan = document.getElementById('contador-vistas');
            // Inicializa el contador con 14 si no existe
            let vistas = parseInt(localStorage.getItem('contadorVistas'));
            if (isNaN(vistas)) {
                vistas = 14;
                localStorage.setItem('contadorVistas', vistas);
            }
            if (adminSection.style.display === 'block') {
                // Si ya está visible, ocultar y detener actualización de quiz
                adminSection.style.display = 'none';
                if(window.quizInterval) clearInterval(window.quizInterval);
            } else {
                // Si está oculto, pedir contraseña y mostrar si es correcta
                const pass = prompt("Introduce la contraseña para ver las ideas:");
                if(pass === "proyecto") {
                    adminSection.style.display = 'block';
                    // Contador de visualizaciones
                    vistas++;
                    localStorage.setItem('contadorVistas', vistas);
                    contadorSpan.textContent = vistas;
                    // Mostrar ideas guardadas con opción de borrar
                    let ideas = JSON.parse(localStorage.getItem('ideas')) || [];
                    const list = document.getElementById('ideas-list');
                    list.innerHTML = '';
                    if(ideas.length === 0) {
                        list.innerHTML = '<li>No hay ideas sugeridas aún.</li>';
                    } else {
                        ideas.forEach(function(idea, idx) {
                            const li = document.createElement('li');
                            li.textContent = idea;
                            // Botón borrar
                            const btn = document.createElement('button');
                            btn.textContent = '🗑️';
                            btn.title = 'Borrar esta idea';
                            btn.style.marginLeft = '12px';
                            btn.style.background = '#37474f';
                            btn.style.color = '#90caf9';
                            btn.style.border = 'none';
                            btn.style.borderRadius = '6px';
                            btn.style.cursor = 'pointer';
                            btn.style.fontSize = '1em';
                            btn.onclick = function() {
                                if(confirm('¿Seguro que quieres borrar esta idea?')) {
                                    ideas.splice(idx, 1);
                                    localStorage.setItem('ideas', JSON.stringify(ideas));
                                    li.remove();
                                    // Si no quedan ideas, muestra el mensaje
                                    if(ideas.length === 0) {
                                        list.innerHTML = '<li>No hay ideas sugeridas aún.</li>';
                                    }
                                }
                            };
                            li.appendChild(btn);
                            list.appendChild(li);
                        });
                    }
                    // Mostrar resultados del quiz y actualizar cada 5 segundos
                    function mostrarResultadosQuiz() {
                        let quizResultados = JSON.parse(localStorage.getItem('quizResultados')) || [];
                        const div = document.getElementById('quiz-resultados');
                        const correctas = ["verdadero", "falso", "verdadero", "falso", "verdadero"];
                        const preguntas = [
                            "1. En Uruguay se generan más de 10 kg de residuos electrónicos por habitante cada año.",
                            "2. El reciclaje electrónico no tiene ningún impacto en la salud de las personas.",
                            "3. Es posible construir objetos útiles usando partes de aparatos electrónicos en desuso.",
                            "4. Las pilas pueden tirarse a la basura común sin problemas.",
                            "5. El reciclaje electrónico ayuda a reducir la contaminación del agua y del suelo."
                        ];
                        if(quizResultados.length === 0) {
                            div.innerHTML = "<i>No hay respuestas registradas aún.</i>";
                        } else {
                            div.innerHTML = quizResultados.map((r, idx) => {
                                let detalle = (r.respuestas || []).map((resp, i) => {
                                    let esCorrecta = resp === correctas[i];
                                    return `<li style="margin-bottom:2px;">
                                        <b>${preguntas[i]}</b><br>
                                        <span style="color:${esCorrecta ? '#81c784' : '#e57373'}">
                                            Tu respuesta: ${resp ? resp.charAt(0).toUpperCase() + resp.slice(1) : '<i>Sin responder</i>'}
                                            ${esCorrecta ? '✔️' : `❌ (Correcta: ${correctas[i].charAt(0).toUpperCase() + correctas[i].slice(1)})`}
                                        </span>
                                    </li>`;
                                }).join("");
                                return `<div style="margin-bottom:18px;padding-bottom:8px;border-bottom:1px solid #37474f;">
                                    <b>${r.nombre}</b> - Puntaje: ${r.puntaje}/5 <span style="color:#b0bec5;font-size:0.9em;">(${r.fecha})</span>
                                    <button onclick="borrarQuiz(${idx})" style="margin-left:12px;background:#37474f;color:#90caf9;border:none;border-radius:6px;cursor:pointer;font-size:1em;" title="Eliminar registro">🗑️</button>
                                    <ul style="margin-top:8px;margin-bottom:0;padding-left:18px;">${detalle}</ul>
                                </div>`;
                            }).join("");
                        }
                    }

                    // Función global para borrar un registro de quiz
window.borrarQuiz = function(idx) {
    if(confirm('¿Seguro que quieres borrar este registro de quiz?')) {
        let quizResultados = JSON.parse(localStorage.getItem('quizResultados')) || [];
        quizResultados.splice(idx, 1);
        localStorage.setItem('quizResultados', JSON.stringify(quizResultados));
        mostrarResultadosQuiz();
    }
}

                    mostrarResultadosQuiz();
                    window.quizInterval = setInterval(mostrarResultadosQuiz, 5000);
                } else if(pass !== null) {
                    alert("Contraseña incorrecta.");
                }
            }
        });
    </script>
</body>
</html>
