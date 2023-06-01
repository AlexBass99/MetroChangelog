### _Buenas Granjeros, aquí tenéis el changelog de todo lo desarrollado durante estas updates, está separado por bloques de desarrollo para que sea más fácil de leer y veáis como ha ido avanzando todo._

# v0.1

*Estado de los NPCs durante la Alpha del servidor*

NPCs existentes:
- Araña/Escorpión - _**Hostil**_ 

- Humanimal - _(Capaz de escalar props y escalones)_ - _**Hostil**_ 

- Lurker - _(Capaz de escalar props y escalones)_ - _**Hostil**_  

- Nosalis - _(Capaz de escalar props y escalones, puede abrir puertas)_ - _**Hostil**_ 

- Nosalis Hembra - _(Capaz de escalar props y escalones, puede abrir puertas y ataca a distancia con un grito en área)_ - _**Hostil**_ 

- Madre Nosalis - _**Hostil**_ 

- Bibliotecario - _(Puede abrir puertas, si atacas a uno toda la población de este NPC será hostil contra los jugadores hasta que todos ellos mueran, si entras en contacto físico con él también se volverá hostil. Mientras recibe daño puede tener una animación de 'stagger' que lo frena )_ - _**Neutral**_ 

- Oso - _**Neutral**_ 

- Oscuro - _(Si atacas a uno toda la población de este NPC será hostil contra los jugadores hasta que todos ellos mueran, los Vigilantes los temen, ataca a distancia y en area )_ - _**Neutral**_ 

- Vigilante - _(Capaz de escalar props y escalones, puede abrir puertas, mientras es atacado puede aullar y llamar a más Vigilantes)_ - _**Hostil**_ 

- Perro - _(Neutral solo para los Jugadores a no ser que sea atacado, si interactúas con él tiene distintas órdenes)_ - _**Neutral**_ 

# v0.2 (Febrero de 2022)

## **MEJORA** - _NPCs de tamaño variable:_ 
Los mutantes ahora al ser spawneados tienen una variabilidad en la escala de su modelo. Adicionalmente algunos de esos mutantes al aparecer pueden tener una escala más grande de lo normal y ser más fuertes, a estos mutantes los llamamos "Alphas".


## **NUEVO** - _Sistema de nidos:_ 
Ahora algunos mutantes tienen nidos, que son entidades relacionadas su respectivo mutantes. Adicionalmente los mutantes cuando se encuentren con el cadáver de algo pueden comérselo para recuperar energía o arrastrarlo hasta su nido. Cuando están en la cercanía de su nido no sienten la necesidad de arrastrar o comer los cuerpos que se encuentren ahí.

## **FIX** - _Actualizado ataque Humanimal:_   
Los humanimal tenían una animación de ataque muy larga, por lo que ha sido reemplazada por otra más corta.

## **NUEVO** - _Lurker amaestrado:_ - _**Neutral**_ 
 Al igual que el NPC del perro, este funciona de la misma manera y con sus mismas órdenes. ¿Podrás conseguir alguno?

## **FIX** - _Aleatorizados los sonidos:_ 
A partir de ahora la frecuencia con la que los mutantes crean sonidos será más errática.

## **FIX** - _Velocidad del Oso:_
 Ajustada la velocidad a la que corría para aumentar un poco su dificultad y que cuadre mejor con su animación.

## **FIX** - _Sistema de relaciones de Oscuros y Bibliotecarios:_ 
Se han hecho algunos ajustes a su sistema de neutralidad ligado a su población.

# v0.3 (Junio de 2022)

## **MEJORA** - _Añadido sonido de pasos a la mayoría de mutantes:_ 
A excepción del Oscuro por motivos de diseño, que creo que no necesita tenerlos, todos los NPCs tienen sonidos de movimiento ligados a su animación.

## **MEJORA** - _Arañas y Escorpiones temen a la luz y animación de 'stagger':_
Cuando un jugador apunta con su linterna a uno de estos mutantes, este sentirá miedo e intentará huir de los jugadores, si mantienes la linterna lo suficiente lo dañas poco a poco. Adicionalmente, a partir de ahora cuando son dañados, tienen una probabilidad de tambalearse con una nueva animación. Es probable que si estos mutantes se ven amenazados intenten excavar para evitar los ataques.

## **MEJORA** - _Los Vigilantes tienen animación al aullar:_
Para cuando usan su aullido con el objetivo de llamar a más Vigilantes se ha buscado una animación acorde entre las que contenía el modelo.

## **MEJORA** - _La Madre Nosalis puede aullar y animación de 'stagger':_ 
Al igual que los Vigilantes ahora se ha ahorrado ese sonido en concreto y buscado una animación para cuando llame a más Nosalis si es dañada lo suficiente. Al igual que con otros mutantes mientras la dañas puede tambalearse.

## **FIX** - _Los NPCs ya no atacan a granadas:_ 
Con un simple cambio se ha arreglado el bug en el que si le atacabas con una granada algunos mutantes se enemistaban con esta en vez de con los jugadores.

## **MEJORA** - _Las Nosalis hembra tienen nuevo ataque:_ 
Se ha desechado el ataque a distancia y en área que tenían originalmente. Ahora tiene un lejano ataque a distancia, es débil pero puede ser molesto, tiene su tiempo de apuntado y su sonido propio y reconocible. Si impacta directamente o cerca del jugador causa un efecto de pitido en los oídos.

# v0.4 (Octubre de 2022)

## **NUEVO** - _Arácnidos de Metro Exodus:_ - _**Hostil**_ 
Añadidas las Arañas y Escorpiones de Metro Exodus, funcionan exactamente igual que las normales solo que tienen esa variación de modelos.

## **MEJORA** - _Nuevo modelo para el Perro:_ 
Añadido el modelo de los lobos de Metro Exodus para el NPC del Perro.

## **NUEVO** - _Rata:_ - _**Neutral**_ 
Una rata, simplemente, no esperes mucho más, poca vida, te tiene miedo, si te ataca te hiere muy levemente. Pues eso, una rata.

## **MEJORA** - _Menú radial para el Perro:_ 
Las ordenes ahora se dan mediante un menú radial que aparece si mantienes la E cerca del perro, estas sacan un mensaje en pantalla en el que se menciona el nombre del perro que es aleatorizado cuando es creado. Se han añadido nuevas ordenes para cambiar su neutralidad o agresividad contra otros NPCs y para pedirle que busque. 

_Gracias a Zuko2 por la ayuda con este menú._

## **FIX** _Ordenes del Perro:_
Cuando interactuabas con este NPC los mensajes que debían salir solo en tu propio chat salían por el global.

## **MEJORA** - _Renovación completa de las animaciones del Perro:_ 
Se han añadido algunas animaciones Idle nuevas, en caso de tener baja la salud estas son diferentes, mostrando su estado de debilidad. Cuando le ordenas seguirte, si te quedas quieto, el se sentará al lado tuyo un rato antes de retomar la marcha. Si le das la orden de buscar tanto en sus animaciones idle como de movimiento está olfateando constantemente. Por último al igual que en muchos NPCs se han añadido animaciones de 'stagger'.

## **MEJORA** - _Sistema de Búsqueda del Perro:_ 
La orden del perro de búsqueda hace que olfatee y busque a su alrededor la entidad más cercana, y fuera de su campo de visión. Entidades como Mutantes, Jugadores o Cajas de Loot incluso. Durante el trayecto de llevarte hasta esa posición, estará andando mientras olfatea el suelo. Dependiendo de lo que sea que haya ha encontrado actuará de alguna manera u otra, estaos atentos a como actúa o que sonidos hace pues puede que os lleve a una gloriosa arma antigua o al nido de unos mutantes.

# v0.5 (Abril de 2023)

## **MEJORA** - _Añadido 'stun' al ataque de la Nosalis Hembra:_ 
A partir de ahora cuando eres impactado por su grito, tienes la vista emborronada durante unos segundos mientras tus oídos retumban.

## **MEJORA** - _Orden de mover al Perro:_ 
Ahora el Perro tiene la orden de moverlo, para evitar que se quede atascado en zonas para seguirte, si eliges esta opción tendrás unos cuantos segundos para moverte a la zona deseada y mirar a donde quieres que aparezca.

## **MEJORA** - _Lurker domesticado completamente actualizado:_ 
Todo el sistema de ordenes del Perro ha sido pasado al Lurker. A falta de animaciones muchas de ellas son las base del mismo y no tiene las de herido, olfatear, tumbarse, etc... Por lo demás las ordenes a nivel funcional son exactamente iguales.

## **FIX** _Comer cuerpos:_
Cuando un NPC iba a comerse un cuerpo existía la posibilidad de que fuese un jugador inconsciente, para evitar problemas hace otro ataque al alimentarse, así se asegura quitar errores.

## **MEJORA** - _Teletransporte de los Oscuros:_
Ahora los Oscuros pueden teletransportarse a la espalda de un enemigo lejano para poder atacarle.

## **FIX** _Probabilidad de Stagger:_
Ajustada la probabilidad de ser tambaleadas en todas las arañas y escorpiones.

# v0.6 (Junio de 2023)

## **NUEVO** - _Lurkers excavan:_
Ahora gracias a un conjunto de efectos y funciones los Lurker pueden excavar al recibir daño.

## **MEJORA** - _Excavar de Arácnidos:_ 
Ahora todas las variantes de Arácnidos tienen el efecto de excavar usado en los Lurkers.



***En proceso...***
