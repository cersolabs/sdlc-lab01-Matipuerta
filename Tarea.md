[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/-s1_zvqh)
# SDLC-Lab01

- Requisitos de entrega y aprobacion:
  - Respetar el formato Markdown.
  - Solo se aceptan los trabajos por GitHub Classroom
  - Todas las respuestas deben realizarse en el archivo **README.md** del repositorio asignado..
  - El Trabajo en individual. Si bien se puede realizar de forma grupal, la entrega es siempre ***individual***
  - Defensa individual
  - Respetar las fechas de entraga. No se aceptan las actividades fuera de termino.

> Si surge algún cambio o aclaración adicional, se comunicará durante la clase.

### Actividad 1
Teniendo en cuenta el material de clase, responda las siguientes preguntas:

1. ¿Por qué el desarrollo de software no puede realizarse simplemente comenzando a programar?

   R: Debido a que si no se analiza los requisitos del propio cliente, podes terminar programando algo que no satisface la necesidad real del cliente. Antes de programar, se realiza un analisis, donde se identifica:
   -Necesidades del clientte.
   -Problemas a resolver.
   -Restricciones del sistema.

2. ¿Qué significa que un desarrollo sea dirigido por un plan?

   R: El desarrollo comienza analizando las necesidades del cliente y, en base a ellas, se elabora un plan detallado que guía todas las etapas del proyecto hasta su finalización.
   Antes de programar se define:
   -Que se va a hacer.
   -Como se va a hacer.
   -En cuanto tiempo.
   -Con que recuros.
   En su desarrollo se sigue:
   -Analisis
   -Diseño
   -Codificacion
   -Prueba
   -Despliegue


3. ¿Cuáles son las ventajas de utilizar un plan de desarrollo?

   R: Las ventajas al utilizar un plan de desarrollo son:
   -Permitir estimar costo y tiempos.
   -Hace el desarrollo mas predecible.
   -Ordena el proceso del trabajo.
   -Define claramente los requerimientos.
   -Facilita la gestion de recursos.
   -Util en entornos estables.

4. ¿Qué críticas se hacen a los modelos tradicionales de desarrollo?

   R: Las principales criticas son:
   -No reflejan la realidad: los proyectos no son completamente lineales.
   -Poca flexibilidad: no permiten cambios una vez definido el plan.
   -Escasa participación del cliente durante el proceso.
   -Los errores de etapas iniciales se arrastran a las siguientes.
   -Dificultad para definir todos los requerimientos desde el inicio.
   -Poco adecuados para proyectos grandes o complejos.
   -Ciclos largos y poca adaptación a entornos cambiantes.

5. ¿Por qué en la práctica muchas organizaciones combinan metodologías ágiles y modelos dirigidos por un plan?

   R: 
   -Porque ningún modelo es perfecto para todos los proyectos.
   -Los modelos dirigidos por un plan aportan orden, documentación y previsibilidad.
   -Las metodologías ágiles aportan flexibilidad y adaptación a cambios.
   -Permite equilibrar control (plan) con capacidad de cambio (ágil).
   -Muchos proyectos requieren planificación inicial, pero también ajustes durante el desarrollo.
   -Se adapta mejor a contextos reales, donde hay tanto partes estables como cambiantes.


### Actividad 2

| Etapa                         | Descripción |
| ----------------------------- | ----------- |
| Análisis                      |Se relevan las necesidades del cliente y se definen los requerimientos del sistema. |
| Diseño                        |Se elabora la solución técnica, definiendo arquitectura, datos y componentes.       |
| Codificación                  |Se desarrolla el software escribiendo el código según el diseño.                    |
| Prueba                        |Se detectan y corrigen errores antes de la implementación.                          |
| Puesta en marcha / Despliegue |Se instala el sistema y se capacita a los usuarios para su uso.                     |


* Luego responda:
  * ¿En qué etapa se obtienen los requerimientos del sistema? 
    R: En la etapa de Análisis. Es aquí donde se relevan las necesidades del cliente para definir qué debe hacer el sistema.

  * ¿En qué etapa se construye el programa?
    R: En la etapa de Codificación. En esta fase se traduce el diseño a un lenguaje de programación para desarrollar el software.
  
  * ¿Cuál es el objetivo principal de las pruebas?   
    R: El objetivo es detectar y corregir errores en el funcionamiento del sistema antes de que sea entregado o implementado finalmente.
    
### Actividad 3
Ordene las siguientes etapas según corresponda  Diseño
-al modelo lineal secuencial:
- Codificación
- Prueba
- Diseño
- Despliegue
- Ingeniería de requerimientos
---
R:
- Ingeniería de requerimientos
- Diseño
- Codificación
- Prueba
- Despliegue

- Luego responder:
  * ¿Qué problema puede surgir si hay un error en una etapa inicial?
    
    R: Se produce un efecto dominó. Como cada etapa se basa en la anterior, un error en los requerimientos o en el diseño se arrastra y se magnifica durante la codificación. Esto genera que, al final del proceso, el software no cumpla con lo que el cliente necesitaba, lo que implica costos altísimos y mucho tiempo perdido para volver atrás y corregirlo.
  * ¿Por qué este modelo puede ser problemático cuando los requerimientos cambian?

    R:Porque es un modelo inflexible y rígido. Al ser secuencial, no permite volver a etapas anteriores fácilmente una vez que se ha avanzado. Si el cliente solicita un cambio a mitad del desarrollo, el equipo tendría que reiniciar prácticamente todo el ciclo, lo que lo hace poco apto para proyectos modernos donde las necesidades del mercado o del usuario evolucionan rápidamente.

### Actividad 4
Complete la siguiente tabla.
| Modelo      | Característica principal     |    Cuándo conviene usarlo       |
| ----------- | ---------------------------- | ------------------------------- |
| Cascada     |      Secuencial y rigido     |Requerimientos fijos y claros    |
| Incremental |Entrega por partes funcionales|Necesidad de entregas rapidas    |
| Prototipos  |Versiones previas para validar|Requerimientos poco claros       |
| Espiral     |Enfoque en gestión de riesgos |Proyectos grandes y complejos    |
| RAD         |Desarrollo ultra rápido       |Tiempos cortos y alto presupuesto|

- Responder:
  - ¿Qué modelo es más adecuado cuando existen muchos riesgos en el proyecto?
  R: El Modelo en Espiral, ya que evalúa riesgos en cada iteración.
  - ¿Qué modelo ayuda a comprender mejor los requerimientos del usuario?
  R: El Modelo de Prototipos, porque permite al usuario ver y probar una versión inicial del sistema.
    
### Actividad 5 – Caso práctico
Una empresa quiere desarrollar un sistema de ventas para un pequeño comercio.

**Características del proyecto:**
- Sistema relativamente pequeño
- Pocos usuarios
- Requerimientos claros
- Tiempo limitado

**Preguntas**

- ¿Qué modelo de desarrollo recomendaría? 
  R: El Modelo en Cascada (o Cascada con entregas rápidas si se busca agilidad, pero técnicamente el lineal es el más directo).

- Justifique su respuesta.
  R:Es el más adecuado porque los requerimientos son claros y el sistema es pequeño. Al no haber incertidumbre ni cambios previstos, avanzar de forma lineal permite cumplir con el tiempo limitado sin la complejidad extra de gestionar múltiples iteraciones o análisis de riesgos profundos como en otros modelos.
  
- ¿Qué etapas principales tendría el desarrollo?
  R:Análisis: Definir las funciones del sistema de ventas.
  Diseño: Estructurar la base de datos y la interfaz de usuario.
  Codificación: Programar las funcionalidades del sistema.
  Pruebas: Verificar que el proceso de venta no tenga errores.
  Despliegue: Instalar el programa en el comercio y capacitar al personal.


### Actividad 7 – Verdadero o Falso
Indique si las siguientes afirmaciones son Verdaderas (V) o Falsas (F). ***marcar con x la verdaderas, dejar en blanco las falsas***

1. [ ] El modelo en cascada permite cambios constantes en los requerimientos.
2. [X] El modelo incremental entrega el sistema en varias versiones.
3. [X] Un prototipo se utiliza para comprender mejor los requerimientos.
4. [X] El modelo RAD busca reducir los tiempos de desarrollo.
5. [X] El modelo en espiral incorpora el análisis de riesgos.
