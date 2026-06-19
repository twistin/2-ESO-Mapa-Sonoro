# 🎙️ Mapa Sonoro del Entorno
### Colegio Estudio · Chandebrito, Nigrán · 2º ESO

Aplicación web interactiva que sitúa en un mapa los paisajes sonoros grabados por el alumnado durante un itinerario por el entorno del colegio. Ahora mismo el mapa muestra los grupos **Regato**, **Fento**, **Toxo**, **Carballo** y **Corvo**, cada uno con su color identificativo y sus paradas activas. La interfaz incluye además una ficha de **contexto y objetivos** con la explicación pedagógica de la actividad, la lista de participantes y notas sobre el lugar.

---

## 📁 Estructura de archivos

```
2º ESO/
│
├── Mapa_Sonoro_Real.html   ← Aplicación principal (ábrela en el navegador)
├── vercel.json             ← Hace que la raíz del proyecto abra el mapa en Vercel
├── README.md               ← Este archivo
│
├── logo-colegio-estudio.png ← Logo usado de forma discreta en la interfaz
│
├── sofia1.mp3              ┐
├── sofia2.mp3              ┤ Audios activos del grupo Regato
│                           ┘
├── aisha1.wav              ┐
├── aisha2.wav              ┤ Audios activos del grupo Fento
│                           ┘
├── carballo1.wav           ┐
├── carballo2.wav           ┤ Audios activos del grupo Carballo
│                           ┘
├── corvo1.wav              ┐
├── corvo2.wav              ┤ Audios activos del grupo Corvo
│                           ┘
├── aishaImg2.jpg           ┐
├── aishaImg3.jpg           ┤ Fotos de lugar de las paradas de Fento
│                           ┘
├── reyes1.jpeg             ┐
├── reyes3.jpeg             ┤ Fotos de lugar de las paradas de Toxo
│                           ┘
├── 5.jpg                   ┐
├── 6.jpg                   ┤ Fotos de lugar de las paradas de Corvo
│                           ┘
├── sofia-sitio1-2.png      ┐
├── sofia-sitio1.png        ┤ Fotos de lugar de las paradas de Carballo
│                           ┘
├── 7.jpg                   ← Foto de grupo de Corvo
├── 2.jpg                   ← Foto de grupo de Toxo
├── 4.jpg                   ← Foto de grupo de Regato
├── sofia sitio 2.jpg       ← Imagen activa de la segunda parada de Regato
├── 3.jpg                   ← Foto de grupo de Fento
│
└── Otros audios e imágenes del proyecto pueden seguir en la carpeta,
   aunque de momento no aparezcan en el mapa.
```

> **Importante:** el archivo `Mapa_Sonoro_Real.html` y todos los recursos multimedia deben estar **en la misma carpeta** para que el mapa funcione correctamente.

---

## 🗺️ Grupos y paradas

| Nº | Grupo | Coordenadas | Sonidos | Audio |
|:---:|---|---|---|:---:|
| 1 | **Regato** · Parada 1 | 42.162461 N · 8.770072 W | Pájaros · voces · viento | ✅ |
| 2 | **Regato** · Parada 2 | 42.163771 N · 8.767164 W | Pájaros · voces · viento | ✅ |
| 3 | **Fento** · Parada 1 | 42.162032 N · 8.768078 W | Paisaje sonoro · entorno · escucha | ✅ |
| 4 | **Fento** · Parada 2 | 42.165060 N · 8.767460 W | Paisaje sonoro · entorno · escucha | ✅ |
| 5 | **Toxo** · Parada 1 | 42.162010 N · 8.767130 W | Pájaros · voces · ruidos · viento | ✅ |
| 6 | **Toxo** · Parada 2 | 42.164540 N · 8.767570 W | Pájaros · voces · ruidos · viento | ✅ |
| 7 | **Carballo** · Parada 1 | 42.162887 N · 8.770847 W | Paisaje sonoro · entorno · escucha | ✅ |
| 8 | **Carballo** · Parada 2 | 42.163985 N · 8.769185 W | Paisaje sonoro · entorno · escucha | ✅ |
| 9 | **Corvo** · Parada 1 | 42.162459 N · 8.771432 W | Paisaje sonoro · entorno · escucha | ✅ |
| 10 | **Corvo** · Parada 2 | 42.165647 N · 8.768299 W | Paisaje sonoro · entorno · escucha | ✅ |

### Integrantes por grupo

**Grupo Regato**
- Inés Muradás Araujo — Notador Gráfico
- Hugo Piña Consuegra — Cronista
- Sofia Prado Sanchez — Fotógrafa y Cartógrafa
- Ana Domínguez Muradás — Técnico de Sonido

**Grupo Fento**
- Iker Cordelle Pérez — Técnico de sonido
- Sara Mozas Otero — Cartógrafo
- Aisha Figueroa Fdez. — Fotógrafo
- Pablo Hermida Miguel — Cronista

**Grupo Toxo**
- Nora Kinson Zoni — Cartógrafo
- Cayetana Fdez. Andonegui — Rol pendiente
- Reyes Fdez. Pedrosa — Fotógrafo
- Ezequiel Simóns Álvarez — Notador gráfico
- Mateo Prego Rguez. — Cronista

**Grupo Carballo**
- Sofia Prado Sanchez — Técnico de sonido
- Nicolás Vila Lomba — Fotógrafo
- Graciela Serna Márquez — Cartógrafa
- Eire Sala Cabral — Notador gráfico
- Eneko Zapiraín Costas — Cronista

**Grupo Corvo**
- Bruno Campos Borrás — Técnico de sonido
- Ian Rey Aranda — Cartógrafo
- Martín Más Durán — Fotógrafo
- Mauro Concheiro Beiras — Notador gráfico

---

## 🚀 Cómo usar el mapa

1. **Abrir**: haz doble clic en `Mapa_Sonoro_Real.html` (se abre en Safari o Firefox sin problema; Chrome puede bloquear audios locales)
2. **Navegar**: desplázate y haz zoom como en cualquier mapa
3. **Escuchar**: toca/haz clic en cualquier marcador numerado para abrir el panel de esa parada
4. **Panel**: muestra el grupo, los integrantes, las coordenadas y el reproductor de audio con forma de onda
5. **Contexto y objetivos**: botón superior en la cabecera — abre la explicación de la actividad, sus valores ecoacústicos y el listado del alumnado participante
6. **Ajustes** ⚙️: botón inferior derecho — cambia tipografía, capa del mapa, etiquetas y tamaño de marcadores

> Si los audios no suenan en Chrome, ábrelo con **Safari** o usa este servidor local:
> ```bash
> python3 -m http.server 8000
> ```
> Luego entra en `http://localhost:8000/Mapa_Sonoro_Real.html`

---

## ▲ Subir a Vercel

La carpeta ya queda preparada para Vercel con [vercel.json](/Users/sdcarr/Desktop/2º ESO/vercel.json), de modo que al entrar en la raíz del proyecto se abra directamente `Mapa_Sonoro_Real.html`.

### Opción rápida: Vercel Drop

1. Entra en [vercel.com/drop](https://vercel.com/drop)
2. Arrastra la carpeta completa `2º ESO`
3. Elige nombre de proyecto y pulsa `Deploy`

### Opción recomendada: GitHub + Vercel

1. Sube esta carpeta a un repositorio de GitHub
2. En Vercel pulsa `Add New...` → `Project`
3. Importa ese repositorio
4. Vercel detectará que es un sitio estático; no necesitas framework
5. Pulsa `Deploy`

### Opción por terminal

1. Instala la CLI:
   ```bash
   npm i -g vercel
   ```
2. En esta carpeta ejecuta:
   ```bash
   vercel --prod
   ```
3. Sigue el asistente para enlazar el proyecto la primera vez

> Importante: sube **toda la carpeta**, no solo el HTML, porque los audios, imágenes y el logo deben viajar juntos.

---

## ✏️ Cómo actualizar el mapa

Todas las modificaciones se hacen en el bloque de datos al inicio del `<script>` en `Mapa_Sonoro_Real.html` (busca `const MEDIA`, `const GROUPS` y `const STOPS`).

### Añadir un audio a una parada

1. Copia el archivo de audio (`.mp3` o `.m4a`) en esta misma carpeta
2. En `const MEDIA`, añade una nueva clave:
   ```js
   const MEDIA = {
     ...,
     audioRegato1: "regato1.mp3",   // ← nueva línea
   };
   ```
3. En `const STOPS`, localiza la parada correspondiente y cambia `audio:null` por:
   ```js
   audio: MEDIA.audioRegato1,
   ```

### Añadir una foto de grupo

1. Copia la imagen (`.jpg` o `.png`) en esta carpeta
2. En `const MEDIA`, añade:
   ```js
   photoRegato: "foto_regato.jpg",
   ```
3. En `const GROUPS`, añade la foto al grupo:
   ```js
   Regato:{
     ...,
     photo: MEDIA.photoRegato,
   }
   ```

### Añadir una nueva parada

Copia el bloque de una parada existente y pégalo al final del array `STOPS` antes del `]`:
```js
{ id:"nuevo1", n:3, name:"NombreGrupo — Parada 1", cat:"Sonidos · del · lugar",
  lat:42.XXXXX, lng:-8.XXXXX, seed:42, audio:null,
  desc:"Descripción del paisaje sonoro.",
  group:GROUPS.NombreGrupo },
```

---

## 🛠️ Tecnología

| Componente | Detalle |
|---|---|
| Mapa | [Leaflet 1.9.4](https://leafletjs.com) — embebido sin CDN |
| Capas base | OpenStreetMap · Esri Satellite · OpenTopoMap |
| Tipografía | Space Grotesk · Outfit (embebidas en base64) |
| Audio | `<audio>` HTML5 + Web Audio API para forma de onda |
| Dependencias externas | **Ninguna** — funciona offline con los archivos locales |

---

## 📋 Pendiente

- [ ] Revisar si los audios `sofia1.mp3` y `sofia2.mp3` deben seguir ligados a las paradas 1 y 2 tal como están ahora
- [ ] Confirmar el rol de Cayetana Fdez. Andonegui

---

*Proyecto de Educación Ambiental y Expresión Artística · Colegio Estudio · Curso 2025-26*
