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
Patrón de diseño de software, define una dependencia uno a muchos, donde cuando cada uno de los objetos cambia su estado notifica el cambio a los dependientes. EJ: Un semáforo (observador) cambia su estado y notifica a los vehículos (suscriptores).
## Patrón Iterador
Ejecutar operaciones secuenciales.
Viene de POO, es na interfaz que declara los métodos necesarios para acceder secuencialmente a un grupo de objetos de una colección
## Programación funcional
Funciones con tareas específicas que reciban argumentos y no mutan la información.
Se crea un conjunto de funciones que tengan un objetivo específico.

# Diagrama de canicas
* rxjs-dev.firebaseapp.com
* reactivex.io
Nomenclatura: nombre$
Linea de tiempo: posee las esferas que son los valores emitidos por el observable, la linea vertical significa completado.
Operacion(): operador, transformación o procedimiento, recibe las flechas y genera otra linea de tiempo.
