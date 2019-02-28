## Pattern
Patron de diseño elegido para solucionar la problemantica presentada en el examen

![alt text](https://raw.githubusercontent.com/catalanjao/Examen-semana-2/master/DesignPatterns/Solucion.jpeg)

#Solucion
Patron Observer
#Consideraciones
-EL proyecto es complejo
-Los objetos son independientes y nunca se van a conocer
-Los clientes, en este caso sistemas de Strimming no van a estar solicitando la información de disponibilidad siempre
-Es preferible que sea implmente el patrón Observer puesto que una vez que los cambios de estados (Suscripciones, Caducidades... etc) se efectuen, sea cuando los procesos de disparen.