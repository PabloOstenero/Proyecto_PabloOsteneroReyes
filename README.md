# Inicialización de la app Android

## Crear el proyecto Android y configurar Jetpack Compose

- Iniciar el proyecto.
- Configurar las dependencias de Compose.
- Definir el tema (colores, tipografías).
- Preparar la navegación con Navigation Compose.

## Definir la estructura de pantallas y navegación

- Decidir qué pantallas tendrá la app:
  - Login
  - Registro
  - Lista de equipos
  - Detalle de equipo
  - Lista de partidos
  - Detalle de partido
  - Estadísticas jugador
- Definir cómo se navega entre ellas.

---

# Pantallas y lógica de presentación

## Implementar las pantallas de login y registro en Compose

- Crear las UIs con formularios de usuario/contraseña/roles.
- Aplicar validaciones básicas.
- Conectarlas a los endpoints de autenticación de la API.

## Desarrollar la pantalla de listado de equipos

- Mostrar los equipos en una lista (`LazyColumn`).
- Usar tarjetas o filas para cada equipo.
- Añadir posibilidad de refresco.
- Incluir, si procede, filtros/búsqueda.

## Crear la pantalla de detalle de equipo

- Mostrar información del equipo seleccionado:
  - Nombre
  - Categoría
  - Otros datos relevantes
- Mostrar sus jugadores.
- Proporcionar acceso al detalle de jugador.

## Implementar la pantalla de partidos y calendario en móvil

- Listar partidos próximos y pasados.
- Mostrar detalles de cada partido:
  - Fecha
  - Hora
  - Equipos
  - Resultado
- Si el rol lo permite, añadir acciones para actualizar resultados.

## Implementar la pantalla de estadísticas del jugador

- Mostrar estadísticas clave de un jugador:
  - Goles
  - Asistencias
  - Minutos
  - Otros datos relevantes
- Usar un diseño claro.
- Incluir, si es posible, elementos visuales:
  - Barras
  - Chips
  - Indicadores

---

# Arquitectura, estado y datos

## Configurar ViewModel y gestión de estado en Compose

- Crear `ViewModel`s para las pantallas principales.
- Usar `State`/`StateFlow`/`LiveData` para gestionar el estado.
- Actualizar la UI de forma reactiva.

## Integrar un cliente HTTP (Retrofit/Ktor) para la API

- Configurar el cliente de red.
- Definir servicios para los distintos recursos:
  - Usuarios
  - Equipos
  - Jugadores
  - Partidos
- Manejar respuestas y errores.

## Gestionar estados de carga, éxito y error en la UI

- Añadir indicadores de carga (spinners).
- Mostrar mensajes de error.
- Manejar reintentos cuando haya fallos de red o de servidor.

## Implementar almacenamiento local (Room o DataStore)

- Guardar en caché datos básicos:
  - Por ejemplo, últimos equipos/jugadores consultados.
- Mejorar rendimiento.
- Permitir consultar cierta información aunque no haya conexión.

---

# Pruebas y optimización (PMDM)

## Realizar pruebas de usabilidad en dispositivos/emuladores

- Comprobar que la navegación es intuitiva.
- Verificar que textos y botones son legibles en distintas pantallas.
- Asegurar que los flujos habituales son fáciles de seguir.

## Optimizar rendimiento y consumo de recursos

- Revisar el uso de recomposition.
- Evitar recargas innecesarias desde la API.
- Optimizar listas grandes.
- Cuidar el uso de memoria y batería en dispositivos móviles.
