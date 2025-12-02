---
layout: default
title: "Playlists deportivas"
permalink: /playlist/
---

# Vuélvete un G.O.A.T 🎵🏆
### Vuélvete un G.O.A.T con estas canciones pre-acción, como Lionel Messi en la Copa del Mundo de Qatar 2022, Ohtani en la Serie Mundial 2025, Jordan con los Bulls, Ali en el ring, Senna en Mónaco y Brady en el Superbowl...

<style>
.playlist-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(260px, 1fr));
    gap: 30px;
    margin-top: 20px;
}

.playlist-card {
    position: relative;
    border-radius: 18px;
    overflow: hidden; /* asegura que el gradiente y la imagen respeten los bordes */
    border: 3px solid #d62828;
    box-shadow: 0 8px 22px rgba(0,0,0,0.25);
    text-align: center;
    transition: transform 0.25s ease, box-shadow 0.25s ease;
    cursor: pointer;
}

/* Imagen de fondo */
.playlist-card::before {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: url('https://assets.goal.com/images/v3/blt77343c47650bbfc1/2342f72fb9136c85780213e2ad65de2843a40911.jpg?auto=webp&format=pjpg&width=3840&quality=60') center/cover no-repeat;
    z-index: 1;
    transition: transform 0.3s ease;
}

/* Gradiente oscuro encima de la imagen */
.playlist-card::after {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: linear-gradient(135deg, rgba(11,35,64,0.7), rgba(26,61,104,0.7));
    z-index: 2;
    transition: background 0.3s ease;
}

/* Contenido dentro del card */
.playlist-card > * {
    position: relative;
    z-index: 3; /* para que esté sobre la imagen y el gradiente */
    padding: 20px;
    color: #fff; /* texto visible sobre el gradiente */
}

/* Hover efecto */
.playlist-card:hover {
    transform: translateY(-6px) scale(1.02);
    box-shadow: 0 12px 28px rgba(0,0,0,0.35);
}

.playlist-card:hover::before {
    transform: scale(1.05); /* imagen se hace un poco más grande al pasar el mouse */
}

.playlist-card h2 {
    font-size: 1.5rem;
    margin-bottom: 10px;
}

.playlist-card p {
    color: #ffcccb;
    font-weight: 600;
}

.playlist-link {
    text-decoration: none;
}
</style>

<div class="playlist-grid">

<!-- Fútbol -->
<a class="playlist-link" href="https://open.spotify.com/playlist/38GGgiwpJO8JVi7dPE4FKO?si=NE8ikwTeRYem8NUncCQosA" target="_blank">
    <div class="playlist-card">
        <h2>Fútbol</h2>
        <p>Escúchala antes de regatear y definir ⚽</p>
    </div>
</a>

<!-- Baseball -->
<a class="playlist-link" href="https://open.spotify.com/playlist/7LjQHK27LQ8aJ1lDnS4oNx?si=b3Ss6jdMRneDG7hITVcEwg" target="_blank">
    <div class="playlist-card">
        <h2>Baseball</h2>
        <p>Playlist de tus ídolos del baseball ⚾</p>
    </div>
</a>

<!-- Basketball -->
<a class="playlist-link" href="https://open.spotify.com/playlist/4f6Nqw2CnrqcuIHR5k1W5P?si=9d9VZDoPStCoEeYYbWjbpQ" target="_blank">
    <div class="playlist-card">
        <h2>Basketball</h2>
        <p>Playlist para los mejores triples 🏀</p>
    </div>
</a>

<!-- Fútbol Americano -->
<a class="playlist-link" href="https://open.spotify.com/playlist/6KNruzKpF3ZZUUfjRJHcMV?si=vjXFI8S5S2iQWN3YQQEgsA" target="_blank">
    <div class="playlist-card">
        <h2>Fútbol Americano</h2>
        <p>Playlist de touchdowns y adrenalina 🏈</p>
    </div>
</a>

<!-- Box -->
<a class="playlist-link" href="https://open.spotify.com/playlist/7BjPPggSVPDl0gUtlTvqH0?si=brSmQD8KSIWa_vwJFbLCQg" target="_blank">
    <div class="playlist-card">
        <h2>Box</h2>
        <p>Playlist para pelear con ritmo 🥊</p>
    </div>
</a>

<!-- F1 -->
<a class="playlist-link" href="https://open.spotify.com/playlist/286L0KkE3PwMWvJzxwe70l?si=4uYwv5pbTTSiiHqZYIQTjg" target="_blank">
    <div class="playlist-card">
        <h2>F1</h2>
        <p>Playlist para acelerar 🏎️</p>
    </div>
</a>

</div>
