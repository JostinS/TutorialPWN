# Conocimiento basico sobre PAWNO.

Esta guía esta basada en diversas guías y en mi propia experiencia. Guía creada especialmente para nuevos scripters y usuarios a los que les gustaría aprender sobre el lenguaje Pawn en SA-MP; explicando solo lo básico y cómo empezar.

* Nota: es importante que el usuario tenga el mayor conocimiento posible del idioma inglés, dado que el lenguaje de programación Pawn está basado en este idioma.
#
Introducción

1. Explicando cada archivo y carpeta (solo los básicos)

filterscripts
gamemodes
plugins
npcmodes
pawno
include
announce.exe
samp-npc.exe
samp-server.exe
server.cfg
#
2. Configuración

Publics
public OnGameModeInit()

public OnPlayerRequestClass(playerid, classid)

public OnPlayerConnect(playerid)

public OnPlayerSpawn(playerid)

public OnPlayerDeath(playerid)

public OnPlayerDisconnect(playerid, reason)

public OnPlayerText(playerid)

public OnPlayerUpdate(playerid)

#
Funciones

SetPlayerPos(playerid, X, Y, Z);

TextDrawCreate(X, Y, text[])

#
Dialogs

ShowPlayerDialog(playerid, dialogid, style, caption[], info[], button1[], button2[]);

Dialog de cuadro (envía un mensaje al jugador)

Dialog de texto (permite a los jugadores colocar texto en el dialog)

Dialog de lista (menú, muestra a los jugadores una lista de opciones)

Dialog de contraseña (permite a los jugadores colocar texto en el dialog, sin revelar el texto)
#
# Iniciando












