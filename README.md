Resumen principos SOLID

Yeison Camilo Aparicio Aponte 

¿Qué son los principios SOLID?

Es un acronimo que acuñó Michael Feathers, basadose en los princinpios de la programacion orientada a objetos
es uno de los fundamentos de la arquitectura de software.

Los 5 principios SOLID de diseño de aplicaciones de software son:

S – Single Responsibility Principle (SRP)
O – Open/Closed Principle (OCP)
L – Liskov Substitution Principle (LSP)
I – Interface Segregation Principle (ISP)
D – Dependency Inversion Principle (DIP)

Entre los objetivos de tener en cuenta estos 5 principios a la hora de escribir código encontramos:

Crear un software eficaz: que cumpla con su cometido y que sea robusto y estable.
Escribir un código limpio y flexible ante los cambios: que se pueda modificar fácilmente según necesidad, que sea reutilizable y mantenible.
Permitir escalabilidad: que acepte ser ampliado con nuevas funcionalidades de manera ágil.
En definitiva, desarrollar un software de calidad.

“A class should have one, and only one, reason to change.”

La S del acrónimo del que hablamos hoy se refiere a Single Responsibility Principle (SRP). Según este principio “una clase debería tener una, y solo una, razón para cambiar”. Es esto, precisamente, “razón para cambiar”, lo que Robert C. Martin identifica como “responsabilidad”.

“You should be able to extend a classes behavior, without modifying it.”
“Deberías ser capaz de extender el comportamiento de una clase, sin modificarla”. En otras palabras: las clases que usas deberían estar abiertas para poder extenderse y cerradas para modificarse.

“Derived classes must be substitutable for their base classes.”
“las clases derivadas deben poder sustituirse por sus clases base”.

Esto significa que los objetos deben poder ser reemplazados por instancias de sus subtipos sin alterar el correcto funcionamiento del sistema o lo que es lo mismo: si en un programa utilizamos cierta clase, deberíamos poder usar cualquiera de sus subclases sin interferir en la funcionalidad del programa. 

“Make fine grained interfaces that are client specific.”

En el cuarto principio de SOLID, “Haz interfaces que sean específicas para un tipo de cliente”, es decir, para una finalidad concreta.

En este sentido, según el Interface Segregation Principle (ISP), es preferible contar con muchas interfaces que definan pocos métodos que tener una interface forzada a implementar muchos métodos a los que no dará uso.

“Depend on abstractions, not on concretions.”

Llegamos al último principio: “Depende de abstracciones, no de clases concretas”.
