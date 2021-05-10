# curso-reactiveX-rxjs
ReactiveX - RxJs De cero hasta los detalles

# Observables
* Fuente de información
* Síncronos o asíncronos
* Emiten valores o no y errores

# Subscribers
* Están pendientes de lo que realiza el observable
* Consumen la data del observable
* Desconocen todo lo que hay detrás del observable

# Operadores
* Transformar observables
* Filtrar observables
* Crear observables
* Combinar observables

# Beneficios
* Evitar callback hell
* Trabajar de forma simple tareas síncronas y asíncronas
* Es fácil transformar los flujos
* Es fácil anexar procedimientos

# ReactiveX
## Patrón Observer
Notifica cuando suceden cambios.
Patrón de diseño de software, define una dependencia uno a muchos, donde cada uno de los objetos cambian su estado notifica el cambio a los dependientes. EJ: Un semáforo (observador) cambia su estado y notifica a los veh;iculos (suscriptores).
## Patrón Iterador
Ejecutar operaciones secuenciales.
En POO, Una interfaz que declara los métodos necesarios para acceder secuencialmente a un grupo de objetos de una colección
## Programación funcional
Funciones con tareas específicas que reciban argumentos y no muten la información.
Crear un conjunto de funciones que tengan un objetivo específico.