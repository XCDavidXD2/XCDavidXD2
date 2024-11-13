<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>David Correa's README</title>
    <style>
        .content { display: none; }
        .active { display: block; }
        button { margin: 5px; padding: 5px 10px; cursor: pointer; }
    </style>
</head>
<body>

<!-- Botones de selección de idioma -->
<div align="center">
    <button onclick="setLanguage('en')">English</button>
    <button onclick="setLanguage('es')">Español</button>
</div>

<!-- Contenido en inglés -->
<div id="content-en" class="content active">
    <h1 align="center">Hi 👋, I'm David Correa</h1>
    <img alt="Night Coding" src="https://media2.giphy.com/media/v1.Y2lkPTc5MGI3NjExczVqM3F6cGNpeWg3ZGEyZWVjNnAwNTV0eTA3MGJpc3JiaXg0cHB6aiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/6rOhtOcGJapBECjMkb/giphy.gif" width=100% height="300px" align="center"/>

    <h2>/ about me /</h2>
    <ul>
        <li>⭐ currently studying <strong>DAM</strong></li>
        <li>👾 a <strong>student</strong> working his way around things</li>
    </ul>

    <h2>Languages</h2>
    <!-- Logos de tecnologías en inglés -->
    <!-- ... (mantén las imágenes y los enlaces como estaban) ... -->
</div>

<!-- Contenido en español -->
<div id="content-es" class="content">
    <h1 align="center">Hola 👋, soy David Correa</h1>
    <img alt="Night Coding" src="https://media2.giphy.com/media/v1.Y2lkPTc5MGI3NjExczVqM3F6cGNpeWg3ZGEyZWVjNnAwNTV0eTA3MGJpc3JiaXg0cHB6aiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/6rOhtOcGJapBECjMkb/giphy.gif" width=100% height="300px" align="center"/>

    <h2>/ sobre mí /</h2>
    <ul>
        <li>⭐ Actualmente estudiando <strong>DAM</strong></li>
        <li>👾 Un <strong>estudiante</strong> abriéndose camino</li>
    </ul>

    <h2>Lenguajes</h2>
    <!-- Logos de tecnologías en español -->
    <!-- ... (mantén las imágenes y los enlaces como estaban) ... -->
</div>

<script>
    function setLanguage(language) {
        // Oculta ambos idiomas
        document.getElementById("content-en").classList.remove("active");
        document.getElementById("content-es").classList.remove("active");
        
        // Muestra el idioma seleccionado
        if (language === "en") {
            document.getElementById("content-en").classList.add("active");
        } else if (language === "es") {
            document.getElementById("content-es").classList.add("active");
        }
    }
</script>

</body>
</html>
