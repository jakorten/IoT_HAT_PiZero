# IoT HAT for Pi Zero

Leuk zo'n Raspberry Pi Zero van i&i, maar hoe doe je er nu IoT mee?!
- optie A: USB hub of zo, dan een Ethernet of WiFi dongle
- optie B: Weggooien en vervangen door een Raspberry Pi Zero W, maar ja zonde, gemiste kans!
- optie C: Gewoon een IoT HAT er op plaatsen!

LoRa, ZigBee, WiFi, Bluetooth Low Energy?
Eigenlijk wilde ik het zo universeel mogelijk maken, door er een XBee header op te plaatsen kun je gewoon kiezen welke module je wilt gebruiken.

N.b. Deze HAT werd geïnspireerd door: https://sixfab.com/product/xbee-shield/ die is al meer uit ontwikkeld en gewoon te koop.

### Over die HAT
Die originele HAT is in feite een https://www.sparkfun.com/products/11812 maar dan in HAT vorm.
Dat is mooi, maar ik heb gewoon een voorraad van die XBee Explorers liggen en wil er toch geen échte XBee's mee programmeren.

### Mijn versie:
- Het idee van direct met USB verbinden met de XBee module leek me echter wel een goed idee dus ik heb de selectie Pi/USB wel aangehouden.
- Er zit ook een NeoPixel LED op de HAT die je vanaf je Pi aan kunt sturen.
- Daarnaast een Vochtigheids/Temperatuur sensor via i2c én een i2c header voor evt andere sensor.

N.b. Dit is natuurlijk eerste versie dus ws. moet ik er nog aan sleutelen en het zal even duren voor ik de printjes van deze versie uit China binnen heb en gesoldeerd heb. Laat gerust weten als je interesse hebt. Dit is niet mijn eerste HAT die ik maak, ik heb o.a. weerstation HAT's, aansturingen voor tuinberegening, etc. daarnaast 'uiteraard' voor mijn reanimatie simulator.

