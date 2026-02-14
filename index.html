<!DOCTYPE html>
<html lang="es">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, viewport-fit=cover">
    <title>Carta Especial</title>

    <style>
        :root {
            --pink-main: #ff5c8a;
            --pink-dark: #ff2e63;
            --pink-light: #ffd6e0;
            --shadow-strong: 0 25px 50px rgba(0, 0, 0, .35);
            --shadow-soft: 0 12px 30px rgba(0, 0, 0, .25);
        }

        * {
            box-sizing: border-box;
            -webkit-tap-highlight-color: transparent;
        }

        html,
        body {
            margin: 0;
            padding: 0;
            height: 100%;
            background: radial-gradient(circle at top, #ffe4ec, #f7b7c9);
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", system-ui, sans-serif;
            overflow: hidden;
        }

        /* 🌸 PÉTALOS */
        .petal {
            position: fixed;
            top: -40px;
            font-size: 22px;
            pointer-events: none;
            animation: fall linear forwards;
            opacity: .9;
        }

        @keyframes fall {
            0% {
                transform: translateY(0) translateX(0) rotate(0deg);
            }

            100% {
                transform: translateY(110vh) translateX(var(--drift)) rotate(360deg);
            }
        }

        /* CENTRADO */
        .wrapper {
            height: 100%;
            display: flex;
            justify-content: center;
            align-items: flex-start;
            padding-top: 45vh;
            /* Ajusta este valor */

        }

        /* CONTENEDOR */
        .container {
            position: relative;
            width: 82vw;
            max-width: 340px;
            height: 220px;
            cursor: pointer;
            perspective: 1000px;
        }

        /* SOBRE */
        .envelope {
            position: absolute;
            inset: 0;
            background: linear-gradient(145deg, var(--pink-main), var(--pink-dark));
            border-radius: 18px;
            box-shadow: var(--shadow-strong);
            z-index: 1
        }

        /* BORDE */
        .envelope::after {
            content: "";
            position: absolute;
            inset: 6px;
            border-radius: 14px;
            border: 1px solid rgba(255, 255, 255, .35);
        }

        /* TAPA */
        .popo {
            position: absolute;
            inset: 0;
            background: linear-gradient(145deg, #d94f78, #b81f4d);

            clip-path: polygon(0 0, 50% 58%, 100% 0);
            transform-origin: top;
            transition: transform 1.2s cubic-bezier(.22, 1.3, .36, 1);
            border-radius: 18px;
            z-index: 4;
        }

        .letter-mask {
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            height: 120%;
            /* más alto */
            z-index: 6;
            clip-path: polygon(0 -2000%,
                    /* esquina superior izquierda */
                    100% 0,
                    /* esquina superior derecha */
                    100% 0,
                    /* esquina inferior derecha */
                    50% 58%,
                    /* punta del triángulo (invertido) */
                    0 0
                    /* esquina inferior izquierda */
                );
        }

        /* CARTA */
        .letter {
            position: absolute;
            width: 88%;
            height: 175%;
            background: linear-gradient(180deg, #ffffff, #fff6f8);
            left: 6%;
            top: 16%;
            border-radius: 22px;
            padding: 26px 22px;
            box-shadow: var(--shadow-soft);
            transform: translateY(110%);
            transition: transform 1.3s cubic-bezier(.22, 1.2, .36, 1) .35s;
            text-align: center;
            z-index: 5;
        }

        /* SOBRE */
        .caca {
            position: absolute;
            inset: 0;
            background: linear-gradient(145deg, var(--pink-main), var(--pink-dark));
            border-radius: 18px;
            box-shadow: var(--shadow-strong);
            z-index: 3
        }

        .letter h2 {
            margin: 0;
            font-size: 22px;
            color: var(--pink-dark);
        }

        .letter p {
            margin-top: 14px;
            font-size: 15px;
            line-height: 1.6;
            color: #444;
        }

        /* TAPA */
        .flap {
            position: absolute;
            inset: 0;
            background: linear-gradient(145deg, #ff7aa2, #ff3f6c);
            clip-path: polygon(0 0, 50% 58%, 100% 0);
            transform-origin: top;
            transition: transform 1.2s cubic-bezier(.22, 1.3, .36, 1);
            border-radius: 18px;
            z-index: 4;
        }

        /* ABIERTO */
        .open .flap {
            transform: rotateX(180deg);
        }

        .open .letter {
            transform: translateY(-50%) rotate(-2deg);
            /* Un pequeño giro la hace ver más natural */
            transition: transform 1.3s cubic-bezier(.22, 1.2, .36, 1) .35s;
        }

        /* CORAZÓN */
        .fire-heart {
            position: fixed;
            font-size: 32px;
            pointer-events: none;
            animation: launch 1.1s cubic-bezier(.25, 1.2, .4, 1) forwards;
            filter: drop-shadow(0 6px 10px rgba(0, 0, 0, .25));
        }

        @keyframes launch {
            from {
                transform: translateY(0) scale(1);
                opacity: 1;
            }

            to {
                transform: translateY(-240px) scale(1.15);
                opacity: 1;
            }
        }

        /* PARTÍCULAS */
        .particle {
            position: fixed;
            font-size: 20px;
            pointer-events: none;
            animation: explode 1.5s ease-out forwards;
        }

        @keyframes explode {
            from {
                transform: translate(0, 0) scale(1);
                opacity: 1;
            }

            to {
                transform: translate(var(--x), var(--y)) scale(.3);
                opacity: 0;
            }
        }

        /* MICRO ANIMACIÓN */
        .open .container {
            animation: pulse .5s ease;
        }

        /* Cursor máquina */
        .cursor {
            display: inline-block;
            width: 2px;
            background: var(--primary-dark);
            animation: blink 1s infinite;
            margin-left: 3px;
            height: 16px;
            vertical-align: bottom;
        }

        @keyframes blink {

            0%,
            50%,
            100% {
                opacity: 1;
            }

            25%,
            75% {
                opacity: 0;
            }
        }

        @keyframes pulse {
            0% {
                transform: scale(1);
            }

            50% {
                transform: scale(1.02);
            }

            100% {
                transform: scale(1);
            }
        }
    </style>
</head>

<body>

    <div class="wrapper">
        <div class="container" id="sobre">
            <div class="envelope"></div>
            <div class="popo"></div>
            <div class="letter-mask">
                <div class="letter">
                    <h2>💌 Feliz San Valentin</h2>
                    <p id="typedText"></p>

                </div>
            </div>
            <div class="flap"></div>
            <div class="caca"></div>
        </div>
    </div>

    <script>
        const sobre = document.getElementById("sobre");

        sobre.addEventListener("pointerdown", abrirCarta);

        function abrirCarta() {
            if (sobre.classList.contains("open")) return;
            sobre.classList.add("open");
            lanzarFuegos();
            setTimeout(() => {
                typeWriter();
            }, 1000); // 👈 2000ms = 2 segundos
        }

        function lanzarFuegos() {
            const rect = sobre.getBoundingClientRect();
            const centerX = rect.left + rect.width / 2;
            const topY = rect.top + 10;

            for (let i = 0; i < 8; i++) {
                setTimeout(() => {
                    // Alternar izquierda y derecha
                    const lado = i % 2 === 0 ? -1 : 1;

                    // Separación horizontal aleatoria
                    const offsetX = lado * (20 + Math.random() * 40);

                    crearCorazon(centerX + offsetX, topY);
                }, i * 250);
            }
        }


        function crearCorazon(x, y) {
            const heart = document.createElement("div");
            heart.className = "fire-heart";
            heart.textContent = "💖";
            heart.style.left = x - 16 + "px";
            heart.style.top = y - 16 + "px";
            document.body.appendChild(heart);

            setTimeout(() => {
                heart.remove();
                explotar(x, y - 240);
            }, 1100);
        }

        function explotar(x, y) {
            const icons = ["💖", "💗", "💘", "💞"];
            for (let i = 0; i < 26; i++) {
                const p = document.createElement("div");
                p.className = "particle";
                p.textContent = icons[Math.floor(Math.random() * icons.length)];

                const angle = Math.random() * Math.PI * 2;
                const dist = 60 + Math.random() * 140;

                p.style.setProperty("--x", Math.cos(angle) * dist + "px");
                p.style.setProperty("--y", Math.sin(angle) * dist + "px");
                p.style.left = x - 10 + "px";
                p.style.top = y - 10 + "px";

                document.body.appendChild(p);
                setTimeout(() => p.remove(), 1500);
            }
        }

        /* 🌸 Generador de pétalos */
        function createPetal() {
            const petal = document.createElement("div");
            petal.className = "petal";
            petal.textContent = ["🌸", "🌹", "🌻", "🌷"][Math.floor(Math.random() * 4)];
            petal.style.left = Math.random() * 100 + "vw";
            petal.style.animationDuration = 6 + Math.random() * 6 + "s";
            petal.style.setProperty("--drift", (Math.random() * 100 - 50) + "px");
            document.body.appendChild(petal);
            setTimeout(() => petal.remove(), 12000);
        }

        setInterval(createPetal, 500);

        const textElement = document.getElementById("typedText");

        const message = `Me gusta estar a tu lado…
        Contigo todo se siente hogar,
        se siente paz,
        se siente infinito.
        💞
        No cambiaría ni un solo detalle de ti,
        porque así como eres…
        eres perfectamente
        imperfecta.
        💗`;


        /* ✨ Máquina de escribir */
        function typeWriter() {
            let i = 0;
            textElement.innerHTML = "";
            const cursor = document.createElement("span");
            cursor.className = "cursor";
            textElement.appendChild(cursor);

            function typing() {
                if (i < message.length) {
                    cursor.remove();
                    textElement.innerHTML += message[i] === "\n" ? "<br>" : message[i];
                    textElement.appendChild(cursor);
                    i++;
                    setTimeout(typing, 40);
                } else {
                    cursor.remove();
                }
            }
            typing();
        }
    </script>

</body>

</html>
