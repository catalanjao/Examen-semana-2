## Pattern
Patron de diseño elegido para solucionar la problemantica presentada en el examen

![alt text](https://raw.githubusercontent.com/catalanjao/Examen-semana-2/master/DesignPatterns/Solucion.jpeg)

![alt text](https://github.com/catalanjao/Examen-semana-2/blob/master/DesignPatterns/Solucion1-1.jpeg)
# Solucion
Patron Mediador
# Consideraciones

![alt text](https://refactoring.guru/images/patterns/diagrams/mediator/structure.png)

-El objeto mediador concreto puede redirigir  las llamadas (en  éste caso de los componentes de Sistemas de Streaming) al tipo de función que necesite el mismo (Dar de alta una licencia, obtener actulizacion)

-Podemos tener compomentes de sistemas streaming que tengan sus propias funciones y que soliciten información al mediador

-Podemos tener componentes del sistema de canciones que se conecten con diferentes componentes de streaming

-Las funciones requeridas se comunican dinamicamente reduciendo el acoplamiento haciendo mas facil añadir sistemas de streaming en el futuro.

-se mantiene la cohecion pues dejamos ciertas validaciones en elementos distintos aunque dependan de componentes específicos
puede existir mas de un mediador el los cuales podemos implementar para que un sistema de streaming se conecte a una funcion específica.
