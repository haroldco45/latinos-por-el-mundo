# Latinos por el Mundo 🌎

Portada de la serie de guías "para Latinos" de **Vibras Positivas HM**: una app por ciudad para latinos recién llegados.

🔗 https://haroldco45.github.io/latinos-por-el-mundo/

## Cómo agregar una ciudad nueva

Edita solo `ciudades.json` y agrega un bloque como este a la lista `ciudades`:

```json
{ "id": "toronto", "flag": "🇨🇦", "es": "Toronto", "en": "Toronto",
  "pais": { "es": "Canadá", "en": "Canada" },
  "url": "https://haroldco45.github.io/toronto-para-latinos/" }
```

- Aparece automáticamente en esta portada y en la sección "Otras ciudades para latinos" de todas las apps.
- Agrega `"pronto": true` para anunciarla como "Muy pronto" (sin enlace) antes de publicarla.
- En la app nueva, la sección se incluye con su `data-me` igual al `id` (así no se muestra a sí misma).

**Desarrollada por Vibras Positivas HM — Derechos de Autor Reservados**
