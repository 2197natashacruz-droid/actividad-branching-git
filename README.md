# Actividad Branching Git

## Integrantes
- Natasha Cruz
- Felipe Segovia
- Sabrina Figueroa
- Cristian Díaz
- Camila Valdebenito
- Antonela Muñoz
- Sary Chara
- Alexander Hass

## Objetivo
Practicar branching, fork, pull request y merge.

## Tema investigado  
Ramas (Branch) en Git  

## Definición  
Una rama en Git es una línea de desarrollo independiente que permite trabajar en cambios, nuevas funciones o correcciones sin afectar la versión principal del proyecto (main).

## Respuestas  
1. **¿Qué es una rama en Git?**  
Es una copia del proyecto donde se pueden hacer cambios de forma aislada sin modificar el código principal.

2. **¿Por qué las ramas ayudan a ordenar el trabajo?**  
Porque permiten separar tareas, trabajar en paralelo y organizar mejor el desarrollo sin mezclar cambios.

3. **¿Qué riesgo existe si todos trabajan en main?**  
Se pueden generar conflictos, errores en el sistema, pérdida de información y dificultad para identificar cambios.

## Ejemplo  
Un equipo está desarrollando una página web:  
- En la rama **main** está la versión estable  
- Una persona crea una rama llamada *login* para el sistema de inicio de sesión  
- Otra crea una rama *diseño* para cambiar la apariencia  

Cada uno trabaja sin afectar el proyecto principal y luego integran los cambios cuando están listos.

## Conclusión personal  
Las ramas en Git son fundamentales para trabajar de forma ordenada y segura, especialmente en equipo, ya que permiten evitar errores en la versión principal y facilitan la colaboración.


**Alumno 4 — Cristian Díaz**
¿Qué es un commit y por qué es importante?

**•	¿Qué es un commit?**
Un commit es como una “foto”, “instantanea” (snapshot) o punto de guardado que captura los cambios que se realizaron en un momento especifico dentro de un proyecto. Es importante porque funciona como un historial o punto de control, el cual sirve para revisar los cambios paso por paso o, en caso de algún error, volver a un estado anterior del código en que funcione correctamente.

**•	¿Por qué se hacen commits pequeños?**

Hacer commits pequeños es una buena práctica, y tiene varias ventajas como:
Mas claridad y orden: Cada commit representa un cambio específico.
Más fácil para encontrar errores: Si algo falla, puedes ver exactamente en qué cambio ocurrió.
Mejor control: Puedes volver atrás (rollback) sin perder todo el trabajo
Trabajo en equipo: Otros entienden fácilmente qué hiciste



**•	¿Cómo ayuda a seguir el historial del proyecto?**
Los commits crean una especie de línea de tiempo del proyecto. Gracias a eso se pueden ver qué cambios se hicieron, saber cuándo se hicieron, identificar quién los hizo y entender por qué se hicieron (gracias al mensaje) Podria decirse que es como un diario del proyecto.

**•	Ejemplos**

git commit -m "Inicio del proyecto"
git commit -m "Agrego título y párrafo"
git commit -m "Agrego estilos CSS"
git commit -m "Agrego imagen de demostración"
git commit -m "Corrijo errores"


**•	Conclusión**
Un commit es una “foto” de los cambios del proyecto.
Hacer commits pequeños nos otorga más orden, control y facilidad para detectar errores.
Los commits ayudan a contar la historia completa del desarrollo.
