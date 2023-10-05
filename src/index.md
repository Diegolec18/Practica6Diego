---
layout: base.njk
title: Mis videojuegos favoritos
---
<link href="https://fonts.googleapis.com/css2?family=Bungee&display=swap" rel="stylesheet">


# {{ title }}

En este blog abarcaremos mis videojuegos favoritos su division por genero en este caso son:




**RPG (Role Playing Game)**

El género RPG se centra en la narrativa y la construcción del personaje. Los jugadores asumen el papel de un personaje (o varios) y toman decisiones que afectan el desenlace de la historia y el desarrollo de sus personajes. Estos juegos a menudo incluyen sistemas complejos de habilidades, progresión de niveles y un énfasis en la exploración y la interacción. 

---

**Mundo Abierto(Open World)**

Los videojuegos de mundo abierto ofrecen una sensación de libertad sin precedentes. En lugar de limitar al jugador a un camino lineal, estos juegos ofrecen un vasto mundo para explorar, lleno de secretos, misiones y aventuras. Desde las bulliciosas ciudades hasta los paisajes naturales desolados, los juegos de mundo abierto permiten a los jugadores sumergirse en entornos ricos y detallados, interactuar con personajes no jugables y decidir cómo quieren abordar los desafíos que se les presentan. 

---

**Shooters**

Los "shooters" o juegos de disparos son un género de videojuegos donde la acción principal implica el uso de armas para combatir a enemigos. Estos juegos pueden ser en primera o tercera persona, dependiendo de la perspectiva del jugador. 

---

[**Un poco de mi**]({{ '/acerca' | url }})

## Artículos de mi Blog

### Open World

{% for openworld in collections.openworlds %}

- [{{openworld.data.title}}]({{ openworld.url | url }})

{% endfor %}

### RPG

{% for rpg in collections.rpgs %}

- [{{rpg.data.title}}]({{ rpg.url | url }})

{% endfor %}

### Shooters

{% for shooter in collections.shooters %}

- [{{shooter.data.title}}]({{ shooter.url | url }})

{% endfor %}
