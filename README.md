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

# Iniciando

Lo primero sería descargar el archivo SA-MP windwos servers desde www.sa-mp.com/download.php

Continúamente luego, de descargarlo y descomprimirlo, veremos estos archivos...

Archivos y carpetas básicos:

scriptfiles, plugins, pawno, npcmodes, include, gamemodes, filterscripts, announce.exe, samp-npc.exe, samp-server.exe & server.cfg

Otros archivos:

Textos que incluyen términos de servicio y una guía de configuración (samp-license.txt & server-readme.txt respectivamente).

# Explicando cada archivo y carpeta (solo los básicos):

scriptfiles: esta carpeta contiene información llamada dentro del script o logs producidos por el script. Normalmente es usada como base de datos.

plugins: esta carpeta contiene códigos adicionales que dan más opciones en la programación, usualmente programados en otros lenguajes de programación. Esta guía no dará información detallada sobre plugins debido a que es más avanzado.

pawno: contiene el programa básico para empezar a programar en SA-MP; también tiene la carpeta include que contiene los includes básicos de SA-MP para empezar nuestro script (funciones básicas de SA-MP). También podemos crear nuestros propios includes y añadirlos al script.

npcmodes: contiene información sobre NPCs (script & rec); esta guía no dará información detallada sobre NPCs debido a que es más avanzado.

include: contiene códigos que pueden ser incluidos en el script.

gamemodes: contiene los modos de juego básicos y si creamos uno debemos colocar aquí también.

filterscripts: contiene códigos adicionales, separados del gamemode, no están incluidos dentro de él y pueden ser llamados al usar comandos rcon.

announce.exe: este archivo nos permitirá mostrar nuestro servidor en la lista de Internet.

samp-npc.exe: nos permitirá usar NPCs.

samp-server.exe: con este archivo iniciamos el servidor.

server.cfg: configuración del servidor.











