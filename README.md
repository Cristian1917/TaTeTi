# Ta Te Ti, Buscaminas y Pac-Man

Colección de juegos clásicos hecha con HTML, CSS y JavaScript puro. Sin dependencias ni instalación: se abre directo en el navegador.

## Demo

Podés probarlo online desde GitHub Pages (ver la sección [Publicar en GitHub Pages](#publicar-en-github-pages)).

## Juegos

### Ta Te Ti (`tateti.html`)

- Dos jugadores en el mismo dispositivo (X y O).
- Dos tableros desde un menú: **Clásico 3×3** (3 en línea) y **Grande 5×5** (5 en línea).
- Modo contra la máquina en ambos tableros: minimax perfecto en 3×3 e IA heurística en 5×5.
- Marcador de partidas ganadas y empates.
- Atajos de teclado: teclas `1`-`9` para jugar en el 3×3 y `R` para reiniciar.

### Buscaminas (`buscaminas.html`)

- Tres dificultades desde un menú: **Fácil 9×9** (10 minas), **Medio 16×16** (40 minas) y **Difícil 16×30** (99 minas).
- Primer clic siempre seguro.
- Modo bandera (para marcar minas, útil en móvil) y clic derecho para poner bandera.
- Contador de minas y temporizador.

### Pac-Man (`pacman.html`)

- Laberinto clásico con puntos, power pellets y cuatro fantasmas con IA.
- Tres laberintos que rotan en cada nivel.
- Dificultad creciente: la velocidad de los fantasmas sube un 10% cada ciclo de tres niveles.
- Controles con flechas/WASD o deslizando el dedo en el celular.

## Cómo jugar

1. Descargá o cloná el repositorio.
2. Abrí el archivo `index.html` (página de inicio) y elegí el juego.
3. Jugá haciendo clic en el tablero. Usá el menú de la esquina para cambiar opciones.

No hace falta servidor ni instalar nada.

## Estructura del proyecto

```
.
├── index.html        # Página de inicio con el logo y accesos a los juegos
├── tateti.html       # Ta Te Ti (3×3 y 5×5, con IA)
├── buscaminas.html   # Buscaminas (3 dificultades)
├── pacman.html       # Pac-Man (3 laberintos y dificultad creciente)
├── README.md         # Este archivo
└── .gitignore
```

## Subir el proyecto a GitHub

Si todavía no creaste el repositorio en GitHub:

```bash
# 1. Creá el repo vacío en https://github.com/new (sin README ni .gitignore)
# 2. Conectá tu repo local con el remoto (reemplazá USUARIO y REPO)
git remote add origin https://github.com/USUARIO/REPO.git

# 3. Subí tu código
git branch -M main
git push -u origin main
```

## Publicar en GitHub Pages

1. Entrá a tu repositorio en GitHub.
2. Andá a **Settings > Pages**.
3. En **Build and deployment**, elegí **Deploy from a branch**.
4. Seleccioná la rama `main` y la carpeta `/ (root)`. Guardá.
5. Esperá un minuto y tu juego estará en `https://USUARIO.github.io/REPO/`.

## Licencia

MIT.
