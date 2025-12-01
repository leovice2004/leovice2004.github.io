---
layout: default
title: "Hall of fame"
permalink: /hall_of_fame/
---

# Los G.O.A.T.S 🐐

<style>
.goat-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(260px, 1fr));
    gap: 30px;
}

.card-pack {
    width: 260px;
    height: 380px;
    background: linear-gradient(135deg, #0b2340, #1a3d68, #0b2340);
    border: 4px solid #d62828;
    border-radius: 18px;
    padding: 20px;
    box-shadow: 0 8px 22px rgba(0,0,0,0.25);
    position: relative;
    overflow: hidden;
    cursor: pointer;
    transition: transform 0.25s ease, box-shadow 0.25s ease;
}

.card-pack:hover {
    transform: translateY(-10px) scale(1.03);
    box-shadow: 0 14px 28px rgba(0,0,0,0.35);
}

.card-pack::before {
    content: "";
    position: absolute;
    top: -40%;
    left: -40%;
    width: 200%;
    height: 200%;
    background: linear-gradient(60deg,
        rgba(255,255,255,0) 0%,
        rgba(255,255,255,0.15) 30%,
        rgba(255,255,255,0) 60%
    );
    transform: rotate(20deg);
}

.card-pack h2 {
    color: white;
    text-align: center;
    margin-top: 80px;
    font-size: 1.8rem;
    font-weight: 700;
    letter-spacing: 1px;
}

.card-pack p {
    text-align: center;
    color: #ffcccb;
    margin-top: 10px;
    font-size: 0.9rem;
    font-weight: 600;
}

.card-link {
    text-decoration: none;
}
</style>

<div class="goat-grid">

<a class="card-link" href="{{ '/goats/futbol/' | relative_url }}">
    <div class="card-pack">
        <h2>FUTBOL GOATS</h2>
        <p>Haz click para abrir</p>
    </div>
</a>

<a class="card-link" href="{{ '/goats/baseball/' | relative_url }}">
    <div class="card-pack">
        <h2>BASEBALL GOATS</h2>
        <p>Haz click para abrir</p>
    </div>
</a>

<a class="card-link" href="{{ '/goats/basket/' | relative_url }}">
    <div class="card-pack">
        <h2>BASKETBALL GOATS</h2>
        <p>Haz click para abrir</p>
    </div>
</a>

</div>

