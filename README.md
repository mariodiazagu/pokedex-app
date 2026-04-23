# PokéPlanner 🎮

Una aplicación web progresiva para gestionar tu colección Pokémon, construir equipos y llevar el registro de tus capturas a través de todos los juegos de la saga.

**[→ Abrir PokéPlanner](https://mariodiazagu.github.io/pokedex-app/)**

---

## ¿Qué es PokéPlanner?

PokéPlanner es una herramienta personal para entrenadores Pokémon que quieren llevar un registro detallado de su colección. Puedes marcar qué Pokémon has capturado en cada juego, cuáles tienes en forma shiny, gestionar tus equipos y mucho más — todo sincronizado en la nube con tu cuenta de Google.

---

## Características principales

### Pokédex completa
- Los 1025 Pokémon hasta la Gen IX con sprites oficiales y pixel-art
- Filtros por generación, tipo, rareza (legendario, mítico, paradoja, ultra ente) y búsqueda por nombre
- Grid personalizable de 2 a 8 columnas

### Registro de capturas
- Marca capturas independientemente por juego
- Registra shinies, Pokémon en caja, Poké Ball usada y nivel
- **Variantes independientes** — Zorua de Hisui y Zorua normal se rastrean por separado
- Notas personales por Pokémon y juego

### Favoritos
- Guarda Pokémon (y variantes específicas) en tu lista de favoritos
- Filtros por nombre, generación, tipo y rareza
- Elige qué Pokémon aparece en tu Trainer Card

### Equipos
- Crea equipos independientes para cada juego
- Vista de Pokémon capturados en cada juego para añadir al equipo fácilmente
- Aviso cuando el equipo está lleno

### Trainer Card
- Tarjeta personalizada con tus estadísticas de entrenador
- Color dinámico según tu tipo más capturado
- Sprite animado de tu Pokémon favorito
- 25 logros desbloqueables
- Reto diario (se resetea cada día)
- Contador de victorias y derrotas en combate

### Sistema de combate
- Combate por turnos contra entrenadores rivales IA
- 3 dificultades: Joven Joey, Red y Cynthia
- Equipo de batalla propio (independiente de los equipos por juego)
- Movimientos reales en español de la PokeAPI
- IA que cambia de Pokémon estratégicamente en dificultad alta
- Stats inflados del rival en dificultad difícil

### Cadena evolutiva
- Visualización de la cadena completa dentro de cada ficha
- Muestra el nivel de evolución y el estado de captura de cada eslabón
- Acceso directo a cualquier Pokémon de la cadena

### Personalización
- 19 temas de color (uno por cada tipo Pokémon + magenta)
- Pokémon caminante del día sobre la barra de navegación (desactivable)
- Sprite de arte oficial o pixel-art
- Perfil de entrenador con nombre, género y avatar

---

## Stack técnico

| Capa | Tecnología |
|------|-----------|
| Frontend | HTML + CSS + JavaScript vanilla (single file) |
| Autenticación | Firebase Auth (Google Sign-In) |
| Base de datos | Cloud Firestore |
| Hosting | GitHub Pages |
| Datos Pokémon | [PokéAPI](https://pokeapi.co/) |
| Sprites | [PokeAPI Sprites](https://github.com/PokeAPI/sprites) |

---

## Estructura del repositorio

```
pokedex-app/
├── index.html      # App principal (Pokédex, equipos, favoritos, trainer card)
└── battle.html     # Sistema de combate
```

---

## Cómo usar

1. Abre la app en [mariodiazagu.github.io/pokedex-app](https://mariodiazagu.github.io/pokedex-app/)
2. Introduce la contraseña de acceso
3. Inicia sesión con tu cuenta de Google
4. ¡Empieza a registrar tus capturas!

Los datos se sincronizan automáticamente en la nube — puedes acceder desde cualquier dispositivo con la misma cuenta.

---

## Easter egg 🥚

Hay uno. Pista: tu Pokémon favorito sabe la respuesta.

---

## Créditos

- Datos e imágenes: [PokéAPI](https://pokeapi.co/) y [PokeAPI/sprites](https://github.com/PokeAPI/sprites)
- Sprites de entrenadores: [Pokémon Showdown](https://pokemonshowdown.com/)
- Pokémon y todos sus personajes son propiedad de Nintendo / Game Freak / The Pokémon Company

---

*Desarrollado con ❤️ por Mario*
