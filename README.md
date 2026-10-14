# Tres en Raya (Ta Te Ti)

Juego clásico de tres en raya hecho con HTML, CSS y JavaScript puro. Sin dependencias ni instalación: se abre directo en el navegador.

## Demo

Podés probarlo online desde GitHub Pages (ver la sección [Publicar en GitHub Pages](#publicar-en-github-pages)).

## Características

- Dos jugadores en el mismo dispositivo (X y O).
- Modo contra la máquina con IA **imposible de ganar** (algoritmo minimax).
- Marcador de partidas ganadas y empates.
- Atajos de teclado: teclas `1`-`9` para jugar en cada casilla y `R` para reiniciar.
- Diseño responsivo.

## Cómo jugar

1. Descargá o cloná el repositorio.
2. Abrí el archivo `index.html` en cualquier navegador.
3. Hacé clic en una casilla para poner tu ficha.
4. Opcional: activá "Jugar contra la máquina" para jugar contra la IA.

No hace falta servidor ni instalar nada.

## Estructura del proyecto

```
.
├── index.html      # Juego completo (HTML + CSS + JS)
├── README.md       # Este archivo
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
