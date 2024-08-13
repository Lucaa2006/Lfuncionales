# Lenguajes funcionales
Son un paradigma de programación que se basa en el concepto de funciones matemáticas. A diferencia de los lenguajes imperativos, que se enfocan en cómo se deben realizar las tareas mediante la secuencia de instrucciones, los lenguajes funcionales se enfocan en qué debe hacerse, tratando los programas como la evaluación de expresiones matemáticas.


Algunos puntos clave sobre los lenguajes funcionales:
### 1. Funciones como Ciudadanos de Primera Clase
En los lenguajes funcionales, las funciones son tratados como ciudadanos de primera clase. Esto significa que pueden ser pasadas como argumentos a otras funciones, retornadas como resultados de otras funciones y asignadas a variables.
### 2. Inmutabilidad
La inmutabilidad es un principio fundamental en los lenguajes funcionales. Las estructuras de datos no cambian una vez creadas. En lugar de modificar una estructura de datos, se crean nuevas versiones con las modificaciones deseadas. Esto ayuda a evitar efectos secundarios y hace que el código sea más predecible.
### 3. Funciones Puras
Una función pura es aquella que, para una misma entrada, siempre produce la misma salida y no tiene efectos secundarios (como modificar variables globales o realizar operaciones de entrada/salida). Esto facilita la razón sobre el código y la ejecución de pruebas.
### 4. Evaluación Perezosa (Lazy Evaluation)
En muchos lenguajes funcionales, la evaluación perezosa permite que las expresiones se evalúen solo cuando sea necesario. Esto puede llevar a optimizaciones y a la posibilidad de trabajar con estructuras de datos infinitas.
### 5. Composición de Funciones
La composición de funciones es un concepto importante en la programación funcional. Permite construir nuevas funciones combinando otras. Esto fomenta un estilo de programación modular y reutilizable.
### 6. Lenguajes Populares

Algunos lenguajes de programación funcionales populares incluyen:

  __Haskell:__ Un lenguaje puramente funcional con un sistema de tipos avanzado y una sintaxis elegante.
    
  __Erlang:__ Diseñado para sistemas concurrentes y distribuídos, conocido por su robustez en aplicaciones de telecomunicaciones.
    
   **Clojure:** Un lenguaje funcional que se ejecuta en la Máquina Virtual de Java (JVM) y se enfoca en la simplicidad y la inmudabilidad.
    
  **F#:** Un lenguaje funcional que se ejecuta en la plataforma .NET y se integra bien con el ecosistema de .NET.

### 7. Ventajas
Menor propensión a errores: Al evitar efectos secundarios, el código es más fácil de entender y depurar.
   Facilita la paralelización: La inmutabilidad y la ausencia de efectos secundarios hacen que sea más fácil ejecutar código en paralelo.

### 8. Desventajas
  Curva de aprendizaje: La programación funcional puede ser difícil de aprender para quienes están acostumbrados a paradigmas imperativos.
  Desempeño: En algunos casos, la inmutabilidad y la evaluación perezosa pueden afectar el rendimiento, aunque muchos lenguajes funcionales están optimizados para mitigar estos problemas.
