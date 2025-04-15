# 🐍 GitHub Contribution Snake

¡Bienvenido/a a mi repositorio de GitHub Actions para generar la animación tipo "Snake" con mis contribuciones diarias!

Este workflow genera automáticamente una animación en formato SVG y GIF con la actividad de contribuciones, y la sube a una rama separada (`output`).

## 📅 ¿Cómo funciona?

- 🚀 Se ejecuta automáticamente **todos los días a medianoche** (`cron: "0 0 * * *"`).
- 🐍 Utiliza la acción [`Platane/snk`](https://github.com/Platane/snk) para generar la animación.
- 📦 Publica los resultados en la rama `output`.

## 🖼️ Vista previa

### SVG:
![GitHub Snake Light](https://raw.githubusercontent.com/SANTONLA/SANTONLA/output/snake.svg)

### GIF:
![GitHub Snake Dark](https://raw.githubusercontent.com/SANTONLA/SANTONLA/output/snake.gif)

> ⚠️ Asegurate de que la rama `output` ya exista y tenga los archivos generados.

## 🛠️ Tecnologías usadas

- GitHub Actions
- Platane/snk
- crazy-max/ghaction-github-pages

## 🧩 Personalización

Podés editar el archivo `.github/workflows/snake.yml` para cambiar:
- El nombre de usuario
- La frecuencia de ejecución
- Los archivos de salida (SVG, GIF, colores, etc.)

---

### ✨ ¿Querés usarlo en tu propio perfil?

1. Forkeá este repositorio.
2. Editá `github_user_name` en el workflow.
3. Activá GitHub Pages desde la rama `output` (opcional).
4. ¡Listo!

---

💙 ¡Gracias por pasar! Si te gusta, dejá una ⭐ o compartilo con otros.

