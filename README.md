# Para Fran ♥

Página estática (un solo archivo `index.html`, sin dependencias ni build).

## Publicar en Vercel (cuenta personal)

1. Sube `index.html` y este `README.md` a un repositorio **privado** de GitHub.
2. En vercel.com, cambia a tu cuenta personal (selector de equipo, arriba a la izquierda).
3. **Add New → Project**, importa el repositorio.
4. Framework Preset: **Other**. Deja vacíos Build Command y Output Directory.
5. **Deploy**.

## Editar textos

Todo el contenido está al principio del `<script>` de `index.html`, en el bloque `CONFIG`:

| Campo | Qué es |
|---|---|
| `nombre`, `apodo`, `firma` | Nombre en el sobre, saludo y firma |
| `proximaVisita` | Fecha `"AAAA-MM-DD"` para la cuenta regresiva (vacío = se oculta) |
| `nuestraCancion` | Afortunada: id de Spotify y la frase de la tarjeta |
| `canciones` | Canciones asociadas a cada sección |
| `postits` | Post-its para la defensa |
| `razones` | "Por qué te elijo" (cada una completa la frase "Te elijo porque…") |
| `carta` | Párrafos de la carta |
| `promesas` | Lo que te prometo |
| `sobres` | "Ábrelo cuando…" |

Para quitar algo, borra su línea entera, incluida la coma final. Cada texto va entre comillas `"así"`;
si un texto lleva comillas adentro, escríbelas como `\"`.

Cada cambio que guardes (commit) en GitHub se publica solo en Vercel en un minuto.
