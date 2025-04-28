# diagrama de caso de uso
Definición general del cliente objetivo de BL Royale:
Edad: 18 a años recomendado

Género: Principalmente masculino, pero buscando atraer también a jugadoras (incluir personajes diversos ayuda).

Intereses: Videojuegos de acción, competencia online, esports, cultura geek, estética futurista/post-apocalíptica.

Hábitos:

Juegan de forma frecuente (varias veces por semana).

Les gustan los desafíos, la progresión, desbloquear contenido nuevo.

Consumen contenido en Twitch, YouTube Gaming, TikTok (clips de jugadas épicas).

Suelen jugar en PC, consolas y móviles.

Poder adquisitivo:

Gasta en microtransacciones si el juego lo engancha: skins, pases de batalla, cosméticos.

👤 ¿Qué características debe tener nuestro juego para engancharlos?
Que sea rápido y emocionante (no les gusta esperar mucho).

Que recompense la habilidad (quieren mejorar y presumir sus logros).

Que tenga estilo visual impactante (skins locas, efectos visuales copados).

Que sea competitivo pero accesible (fácil de empezar, difícil de dominar).

Que haya contenido constante (actualizaciones, eventos, modos nuevos).

🧠 ¿Por qué definir bien el cliente objetivo importa?
Porque así todo el diseño del juego (arte, mecánicas, monetización, comunicación, marketing) se enfoca en hacer feliz a ese tipo de jugador.
Si le apuntamos a todos en general, corremos el riesgo de no atraer a nadie en particular.

¿Te gustaría que ahora armemos también un "perfil de jugador ideal" (tipo crear una ficha de personaje, pero de nuestro cliente)? 🎮✨
¡Puede ser muy útil para afinar aún más el proyecto!

Dijiste:
Ahora créame  un diagrama de caso de uso que nos pueda utilizar para nuestro juego
ChatGPT dijo:
¡Perfecto! Para BL Royale, te voy a armar un Diagrama de Casos de Uso básico, ideal para mostrar qué puede hacer el jugador (y el sistema) de forma clara.

Voy a describírtelo primero, y si querés después te paso también un dibujito si lo querés visual:

🎮 Actor principal:
Jugador (el usuario que interactúa con el juego)

🛠️ Casos de uso principales:
Crear Cuenta / Iniciar Sesión
(Registrarse o ingresar con usuario)

Personalizar Personaje
(Elegir skins, emotes, habilidades)

Seleccionar Modo de Juego
(Battle Royale, Duelo rápido, Modo aleatorio)

Buscar Partida (Matchmaking)
(Emparejarse automáticamente)

Jugar Partida
(Entrar al mapa, combatir, sobrevivir)

Comunicarte con Otros Jugadores
(Chat de texto, chat de voz)

Recibir Recompensas
(XP, monedas, cofres, skins)

Comprar Ítems en la Tienda
(Pase de batalla, skins, cosméticos)

Consultar Perfil / Estadísticas
(Nivel, winrate, ranking)

Reportar Jugador
(En caso de trampas o comportamiento tóxico)

🧩 Relaciones entre ellos:
Para jugar una partida, primero debo iniciar sesión y buscar partida.

Después de jugar, puedo recibir recompensas.

Opcionalmente, puedo comprar ítems para personalizar más a mi personaje.

📈 Visual resumido:
lua
Copiar
Editar
Jugador
  |
  |---> Crear Cuenta / Iniciar Sesión
  |---> Personalizar Personaje
  |---> Seleccionar Modo de Juego
  |---> Buscar Partida
        |
        |--> Jugar Partida
             |
             |--> Comunicarte con Jugadores
             |--> Recibir Recompensas
             |--> Reportar Jugador
  |
  |---> Comprar Ítems en la Tienda
  |
  |---> Consultar Perfil / Estadísticas
