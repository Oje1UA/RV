# RV

Entrega de la asignatura de Realidad Virtual |
Oscar Jaramillo Espinosa |
14/06/2024


Trabajo Realizado
------------------------------------------------------
Se ha desarrollado un pequeno entorno donde deberas sobrevivir a la amenaza de unos invasores del futuro disparandoles tus hechizos. 

Cuanto mas pase el tiempo, mas invasores vendran. Matando invasores, por otro lado, consigues experiencia, aunque su uso es meramente de puntuacion para hacerlo mas divertido y rejugable. Los invasores seran capaces de quitarte vida, si esta llega a 0 la partida se reinicia.

El proyecto es compatible tanto para dispositivos Meta como para Windows. Al iniciar la aplicacion detecta si tienes unos cascos conectados, si los tienes al jugar crea el Pawn de VR y si no, el de Windows.

Se ha hecho, ademas, un par de videos demo del proyecto. Estan divididos en dos, la version de Windows y la version de Meta. Link a los videos:
https://drive.google.com/drive/folders/13jpoacFs6SKiuwifcy2qDgj1xVhYDNTr?usp=sharing

El Package del proyecto se puede encontrar en el siguiente enlace:
https://drive.google.com/drive/folders/1MQAvdq5DriPzOeDSug5fGci9fX_GqZ-G?usp=sharing


Controles
------------------------------------------------------
En Windows:
  - WASD para moverte en horizontal y vertical
  - Q/E para girar la camara
  - F para disparar un hechizo

En VR:
  - Stick izquierdo para moverte por el escenario
  - Stick derecho para girar la camara
  - Gatillo derecho para disparar un hechizo


Interaccion
------------------------------------------------------
Al disparar a un invasor, este morira y te dara algo de experiencia que te podria subir de nivel. Por otro lado, si el invasor llega hasta ti, te bajara la vida. Si te descuidas y la vida baja a 0 tu partida se reiniciara.


Licencias
------------------------------------------------------
Para la realicacion de este trabajo, se ha usado varios assets externos recogidos desde la marketplace y sonidos descargados de FreeSound, todos con licencia libre de uso validas para proyectos de Unreal:

Marketplace:
  - Sci_Fi_Character_08: Modelo riggeado de los invasores del futuro.
          Link: https://marketplace-website-node-launcher-prod.ol.epicgames.com/ue/marketplace/en-US/product/sci-fi-character-08-renegade
  - M5VFXVOL2: Libreria con effectos de fuego gratuitos.
          Link: https://marketplace-website-node-launcher-prod.ol.epicgames.com/ue/marketplace/en-US/product/m5-vfx-vol2-fire-and-flames
  - InfinityBladeGrassLands: El mapa donde ocurre nuestro juego, aunque ha sido ligeramente modificado.
          Link: https://marketplace-website-node-launcher-prod.ol.epicgames.com/ue/marketplace/en-US/product/infinity-blade-plain-lands

Sonidos:
  - Fireball
          Link: https://freesound.org/people/stevenmaertens/sounds/683179/
  - Die Sound
          Link: https://freesound.org/people/ebcrosby/sounds/333496/
  - 05551 Scifi short circuit.wav
          Link: https://freesound.org/people/Robinhood76/sounds/260667/
  - LushLife_LevelUp.wav
          Link: https://freesound.org/people/SimonBay/sounds/439889/
  - Heroic Charge
          Link: https://freesound.org/people/code_box/sounds/521417/
    
