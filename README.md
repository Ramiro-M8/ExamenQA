# Examen QA

## Preguntas
## 1 - Explica qué es el testing manual y por qué es importante
    El testing manual es un proceso de verificación de software realizado por personas en lugar de herramientas automatizadas. Las personas "Testers Manuales" simulan el uso real del software para identificar defectos y garantizar una experiencia de usuario óptima.
    Importancia:
        - Experiencia del Usuario: Asegura que el software sea amigable y satisfaga las expectativas del usuario.
        - Exploración Exhaustiva: Permite identificar escenarios no previstos durante el desarrollo.
        - Flexibilidad: Adaptabilidad a cambios frecuentes en requisitos y funcionalidades.
        - Costo Efectivo: Para proyectos pequeños o en desarrollo constante.
        - Detección Visual: Identifica problemas visuales y de usabilidad que pueden pasar desapercibidos en pruebas automatizadas.

## 2 - Describe los pasos que seguirías para diseñar un conjunto de pruebas manuales para una nueva función.
    Los pasos que seguiria para diseñar un conjunto de pruebas manuales para esa nueva función seria la siguiente:
    - Entender la función: Comprender el proposito y como se va a integrar la nueva función al sistema existente.
    - Identificar Requisitos y Casos de Uso: Hay que documentar los requisitos(Funcionales y no Funcionales) de la nueva función, y ademas idetificar los distintos casos de uso que la función deberia abordar.
    - Crear Escenarios de Pruebas: Se debe desarrollar cada escenario de prueba que cubra todos los aspectos de la nueva función y tambien se debe incluir todos los casos positivos y negativos para garantizar una cobertura completa.
    - Definir Datos de Prueba: Se debe determinar los datos de prueba para ejecutar cada escenario y asegurar de incluir datos limite y situaciones extremas.
    - Establecer Prioridades: Tambien hay que priorizar los escenarios segun su importancia(Prioridad) y frecuencia de uso.
    - Crear Documentacion de Pruebas: Se debe detallar en un documento cada caso de prueba de un manera prolija y entendible, incluyendo cada paso a paso con sus datos de entrada y resultados esperados.
    - Configurar el entorno de pruebas: Hay que tener un entorno de prueba con la configuracion necesaria para ejecutar las pruebas(Ya sea una base de datos propia alternativa a la de produccion).
    - Ejecutar las pruebas: Se ejecutan las pruebas siguiendo los escenarios y casos de prueba definidos anteriormente, luego se registra los resultados de cada prueba, incluyendo defectos encontrados durante el proceso de ejecucion de las pruebas.
    - Revisar y Actualizar: Se revisa y actualiza los casos de prueba segun sea necesario, en especial luego de encontrar defectos o cambios en la función.
    - Reportar Resultados: Se documenta y presenta los resultados de las pruebas, destacando cualquier inconveniente(defectos) encontrado.
    - Iterar segun sea necesario: Se repite el proceso de diseño de pruebas a medida que la función evoluciona o se modifican los requisitos.

## 3 - ¿Cuál es la diferencia entre el testing funcional y el testing no funcional?
    La diferencia entre el testing funcional y el no funcional, seria que el testing funcional se centra en verificar que las funciones esperadas del software funcionen segun lo esperado, es decir que el software haga lo que deberia hacer. Mientras que el Testing No Funcional no esta relacionado directamente a las funciones especificas del software, sino que esta centrado a las características que mejoran la experiencia del usuario(como seria el probar la velocidad, la usabilidad o la seguridad).

## 4 - ¿Qué es la caja negra y la caja blanca en el contexto de testing?
    La "Caja Negra" se enfoca en la funcionalidad externa del software sin conocimiento interno, mientras que la "Caja Blanca" implica en la revision y la evaluacion del codigo interno y la logica del programa.

## 5 - ¿Cómo abordarías la identificación y reporte de un error?
    La identificación y el reporte de error se deberia abordar de la siguiente manera:
    - Reproducción del Error: Se intenta reproducir el error usando los pasoso especificos que llevaron el problema, esto nos ayuda a comprender el error.
    - Documentación Detallada: Se documenta de manera detallada la información relevante del error, incluyendo el entorno, los pasos para reproducir el error y cualquier dato adicional.
    - Capturas de pantalla o grabaciones: Se proporciona capturas de pantalla o grabaciones de video si es posible, ayuda a la visualizacion del probleam y acelera el proceso de correción.
    - Priorización del error: Se asigna una prioridad al error segun su impacto en el sistema y la urgencia de la correción.
    - Informe Claro y Conciso: Se tiene que redactar un informe claro y conciso del error, y se debe incluir el comportamiento esperado y el observado, como cualquier mensaje de errror recibido.
    - Identificacion de Patrones: Se debe verificar si el error es un problema unico o si hay patrones similares en otras partes del software.
    - Notificacion a los Responsables: En este paso se debe notificar a los responsables del desarrollo y el equipo de QA sobre el error. Se utiliza herramientas de seguimiento de problemas(como Jira, Trello, etc).
    - Seguimiento Continuo: Se realiza un seguimiento periódico para obtener actualizaciones sobre la resolución del error, es importante para tener una comunicacion efectiva.
    - Validación de la Corrección: Una vez que el error se ha corregido, se deben realizar pruebas de validación oara asegurarse que la solucion funcione como se espera.
    - Retroalimentación Post-Corrección: Se proporciona retroalimentación sobre la correción y cualquier detalle adiciona que pueda ser util para mejorar los procesos de desarrollo y de prueba.

## 6 - ¿Qué importancia tienen de las pruebas de regresión y cómo las llevarias a cabo? ¿Cuándo hay que implementarlas?
    -Importancia:
        Las pruebas de regresión son cruciales para asegurar que nuevas modificaciones en el software no introduzcan errores en las funciones existentes.
    -Cómo llevarlas a cabo:
        Automatizar los casos de prueba críticos y repetitivos. Ejecutar pruebas después de cada cambio significativo y antes de cada despliegue para identificar posibles efectos secundarios.
    -Cuándo implementarlas:
        Implementar pruebas de regresión siempre que se realicen cambios en el código, como actualizaciones, correcciones de errores o nuevas características, para garantizar la estabilidad del sistema a lo largo del tiempo.

## 8 - ¿Qué es la caja gris en el contexto del testing?
    La caja gris, también conocida como "testing de caja gris" o "pruebas de caja gris", se encuentra en un punto intermedio entre las pruebas de caja negra y caja blanca. En el contexto del testing, la caja gris implica tener un conocimiento parcial del sistema bajo prueba. El enfoque de caja gris busca aprovechar tanto la perspectiva externa como algunos conocimientos internos para realizar pruebas más completas y efectivas. Este enfoque es especialmente útil cuando se desea un equilibrio entre la cobertura de pruebas y la flexibilidad en entornos donde el acceso completo al código no es posible o práctico.

## 9 - ¿Cómo manejarías la presión de tiempo al realizar pruebas manuales en un proyecto con plazos ajustados? ¿Cómo priorizarías las pruebas?
    Ante la presión de tiempo en pruebas manuales:
    -Priorización: Identifica y prioriza las funciones críticas y escenarios clave.
    -Enfoque en lo Esencial: Centra las pruebas en las áreas críticas del sistema para maximizar la cobertura.
    -Automatización Selectiva: Automatiza pruebas recurrentes o críticas para ahorrar tiempo a largo plazo.
    -Comunicación Efectiva: Colabora con el equipo para entender y priorizar los requisitos críticos del negocio.
    -Testing Exploratorio: Utiliza el testing exploratorio para encontrar defectos de manera ágil y eficiente.
    -Documentación Eficiente: Mantén una documentación clara para acelerar el proceso y facilitar futuras pruebas.
    -Feedback Continuo: Proporciona retroalimentación constante sobre el progreso y los hallazgos al equipo de desarrollo.

## 11 - Explica la diferencia entre pruebas de aceptación del usuario(UAT) y pruebas de sistema.
    Las "pruebas de aceptación del usuario" se centran en validar si el software cumple con las expectativas y necesidades del usuario final, mientras que las "pruebas de sistema" tienen un alcance más amplio, evaluando la funcionalidad del sistema como un conjunto integrado antes de que los usuarios finales realicen sus evaluaciones.

## 12 - ¿Qué es la metodología ágil y cuáles son sus principios fundamentales?
    La metodología ágil es un enfoque de desarrollo de software flexible y colaborativo. 
    Se centra en la entrega incremental, adaptándose a cambios en los requisitos y priorizando la colaboración con el cliente.
    Principios Fundamentales de la Metodología Ágil (según el Manifiesto Ágil):
        -Individuos e Interacciones sobre Procesos y Herramientas
        -Software Funcionando sobre Documentación Exhaustiva
        -Colaboración con el Cliente sobre Negociación de Contratos
        -Responder a Cambios sobre Seguir un Plan

## 13 - ¿Cuál es la diferencia entre desarrollo en cascada(Waterfall) y desarrollo ágil? ¿Cuáles son las ventajas y desventajas de cada uno?
    El desarrollo en cascada es un método lineal y secuencial donde cada fase del desarrollo (requisitos, diseño, implementación, prueba, mantenimiento) se completa antes de pasar a la siguiente.
    Mientras que, el Desarrollo Agil, es un método iterativo e incremental que permiten adaptarse a cambios en los requisitos durante el desarrollo.

    Desarrollo en Cascada:

    Ventajas:
        -Estructura clara y fácil de gestionar.
        -Adecuado para proyectos con requisitos estables.
        -Planificación y presupuestación más previsibles.
    Desventajas:
        -Menos flexibilidad para cambios.
        -Mayor riesgo de errores no detectados hasta fases tardías.
        -Clientes pueden no ver resultados hasta el final del proyecto.

    Desarrollo Ágil:

    Ventajas:
        -Mayor capacidad de adaptación a cambios.
        -Feedback temprano y continuo.
        -Entregas incrementales permiten validación temprana.
    Desventajas:
        -Puede requerir una gestión más intensiva.
        -Requiere una colaboración más continua.
        -Menos previsibilidad en términos de tiempo y costo.

## 14 - ¿Cómo manejarías el cambio de requisitos en mitad de un proyecto?
    Manejar cambios en los requisitos durante un proyecto implica mantener una comunicación abierta con los stakeholders, priorizar y analizar los nuevos requisitos, implementar cambios de manera incremental, ajustar la planificación según sea necesario, realizar pruebas continuas, mantener la documentación actualizada y gestionar los riesgos asociados. La flexibilidad y la adaptabilidad son esenciales, y la colaboración continua con los stakeholders garantiza que los cambios estén alineados con los objetivos del proyecto.

## 15 - ¿Qué proceso seguirías para diseñar casos de prueba para una nueva función?
    Para diseñar casos de prueba para una nueva funcion:
    -Revisión de Requisitos: Entender los requisitos de la nueva función.
    -Identificación de Escenarios Clave: Identificar los casos críticos y escenarios clave.
    -Diseño de Casos de Prueba: Crear casos específicos para cubrir diferentes condiciones y comportamientos.
    -Datos de Prueba: Definir los datos de prueba relevantes para cada caso.
    -Priorización: Priorizar los casos según su importancia y frecuencia de uso.
    -Revisión y Validación: Revisar los casos con el equipo para asegurar su exhaustividad y precisión.
    -Automatización: Evalúar la posibilidad de automatizar casos para futuras pruebas.
    -Documentación: Documenta los casos de prueba de manera clara y concisa.

## 16 - ¿Cómo determinarías qué características del software deben probarse y cuáles no?
    Se puede determinar segun los siguientes casos:
    -Priorizar las características críticas para el usuario y aquellas que tienen un impacto significativo en la funcionalidad del sistema. 
    -Considerar la complejidad y la criticidad del negocio, así como la frecuencia de uso. 
    -La experiencia del usuario y los requisitos no funcionales también son factores clave a tener en cuenta al determinar qué características probar.

## 17 - ¿Cómo equilibrarías entre casos de prueba positivos y negativos en el conjunto de pruebas?
    Para equilibrar casos de prueba positivos y negativos, hay que asegurarse de cubrir escenarios positivos para validar el correcto funcionamiento del software y, al mismo tiempo, identificar los casos negativos para probar la resistencia del sistema ante condiciones adversas. Priorizar los casos negativos basándose en riesgos potenciales y utiliza escenarios del mundo real, límites y validaciones de mensajes de error. Incorporar feedback de usuarios y equipos para identificar posibles casos negativos.

## 18 - ¿Cuál sería el enfoque para la priorización de casos de prueba, cuáles casos de prueba ejecutarías primero?
    Para priorizar los casos de prueba, se comienza con características críticas para el negocio y aquellas asociadas con riesgos identificados. 
    Se debe enfocar en la complejidad técnica y ejecutar los casos de prueba relacionados con áreas recientemente modificadas. 
    Se balancea entre escenarios positivos y negativos, priorizando los de mayor frecuencia de uso y considera el feedback del cliente. 
    Además, aborda dependencias y ejecuta pruebas en áreas que impactan versiones anteriores del software. 
    La automatización puede ser útil para casos críticos y frecuentes, optimizando la eficiencia del proceso de prueba. 

## 19 - Explica la diferencia entre casos de prueba funcionales y no funcionales. ¿Cómo diseñarías pruebas no funcionales?
    Casos de prueba funcionales:
    Se centran en la funcionalidad del software, es decir, en qué hace el sistema. Estos casos evalúan cómo el software responde a entradas específicas y verifica que produce los resultados esperados. Ejemplos incluyen pruebas de la interfaz de usuario, procesos de negocio y flujos de trabajo.

    Casos de prueba no funcionales:
    Evalúan aspectos no relacionados directamente con la funcionalidad del sistema, sino más bien con sus características de rendimiento, seguridad, usabilidad, escalabilidad, etc. Estas pruebas se centran en cómo el sistema realiza sus funciones más allá de simplemente ejecutar tareas específicas.

    Diseño de pruebas no funcionales:
    -Rendimiento:
    Diseña pruebas para evaluar la velocidad, la capacidad de respuesta y la escalabilidad del sistema bajo diferentes condiciones de carga. Utiliza herramientas de prueba de carga para simular usuarios concurrentes y evaluar el rendimiento.
    -Seguridad:
    Desarrolla casos de prueba para evaluar la resistencia del sistema contra posibles vulnerabilidades y ataques. Incluye pruebas de penetración y análisis de seguridad.
    -Usabilidad:
    Diseña pruebas centradas en la experiencia del usuario, evaluando la facilidad de uso, la accesibilidad y la eficiencia del sistema. Puedes realizar pruebas de usabilidad con usuarios reales o utilizar herramientas de análisis de experiencia de usuario.
    -Fiabilidad:
    Evalúa la estabilidad y la confiabilidad del sistema bajo diversas condiciones. Crea casos de prueba que simulen eventos inesperados, como fallos de hardware o pérdida de conexión.
    -Mantenimiento:
    Diseña pruebas para evaluar la facilidad con la que el sistema puede ser mantenido y actualizado. Esto implica verificar la compatibilidad con versiones anteriores y la capacidad de implementar cambios sin afectar la estabilidad.
    -Compatibilidad:
    Verifica la compatibilidad del sistema con diferentes navegadores, sistemas operativos y dispositivos. Asegúrate de que el software funcione correctamente en una variedad de entornos.
    -Eficiencia:
    Evalúa el uso eficiente de recursos como memoria, CPU y espacio en disco. Diseña pruebas para medir la eficiencia y optimización del sistema.
    -Cumplimiento Normativo:
    Si es necesario, crea casos de prueba para garantizar que el software cumpla con regulaciones y normativas específicas de la industria.
    -Recuperación ante Desastres:
    Diseña pruebas para evaluar la capacidad del sistema para recuperarse de fallos y desastres. Esto implica simular situaciones de pérdida de datos y verificar la efectividad de los mecanismos de copia de seguridad y recuperación.
    -Escalabilidad:
    Realiza pruebas para evaluar la capacidad del sistema para manejar un aumento en la carga o el tamaño de la base de datos. Esto es crucial para sistemas que deben adaptarse al crecimiento del usuario o del negocio.

## 20 - ¿Cómo decide qué casos de prueba automatizar y cuáles no?
    En el proceso de automatización de pruebas, se seleccionan casos que se ejecutan con frecuencia, especialmente aquellos vinculados a pruebas de regresión y funciones críticas. 
    Se priorizan interfaces de usuario estables y casos con grandes volúmenes de datos o ejecuciones repetitivas para optimizar la eficiencia. 
    La compatibilidad con diversas plataformas y una evaluación de costos frente a beneficios son criterios clave. 
    La estabilidad del entorno de pruebas y las habilidades del equipo también influyen en la elección. 
    En entornos ágiles, la automatización se centra en facilitar entregas continuas, y en pruebas no funcionales, como las de carga, la automatización destaca por su valor añadido.

## 21 - ¿Qué información consideras esencial incluir en un informe de error?
    En los reportes de defectos siempre se deben indicar los siguientes puntos:
    - El título o una descripción
    - Tipo de prioridad (Si es un defecto crítico, o de alto impacto)
    - El Ambiente
    - Los pasos que se realizaron para que suceda el defecto o error
    - El resultado que se esperaba(es decir lo que debía hacer la función original)
    - El resultado que se obtuvo (que es el resultado contrario al original, el resultado que se dio al testearlo)

## 22 - ¿Cómo priorizaría los errores que ha encontrado durante las pruebas?
    Los errores se pueden priorizar de la siguiente forma: 
    - Impacto en la Funcionalidad:
    Evalúa el impacto del error en la funcionalidad del sistema. Prioriza aquellos que afectan las funciones críticas o que impiden el uso adecuado del software.
    - Frecuencia de Ocurrencia:
    Considera la frecuencia con la que se espera que ocurra el error. Los problemas que ocurren con mayor frecuencia pueden requerir una atención inmediata para evitar impactos repetidos.
    - Facilidad de Reproducción:
    La facilidad con la que se puede reproducir el error también es crucial. Errores que son fácilmente reproducibles son generalmente más urgentes y más fáciles de corregir.
    - Usuarios Afectados:
    Analiza cuántos usuarios se verán afectados por el error. Problemas que impactan a un gran número de usuarios o a clientes clave pueden necesitar atención prioritaria.
    - Importancia del Cliente:
    Si ciertos errores afectan a clientes importantes o a partes interesadas clave, considera priorizar su corrección para mantener la satisfacción del cliente y la reputación de la empresa.
    - Relevancia en el Contexto del Proyecto:
    Evalúa la relevancia del error en el contexto del proyecto. Algunos errores pueden tener un impacto mínimo en la experiencia del usuario o en los objetivos del proyecto y pueden postergarse en comparación con problemas más críticos.
    - Impacto Financiero:
    Si es posible cuantificar el impacto financiero del error, considéralo en la priorización. Errores que pueden resultar en pérdidas económicas significativas pueden requerir una atención inmediata.
    - Cumplimiento Normativo:
    Si el software debe cumplir con regulaciones o normativas específicas, prioriza la corrección de errores que afecten el cumplimiento normativo.
    - Feedback del Usuario:
    Escucha el feedback de los usuarios. Errores reportados por los usuarios, especialmente aquellos que afectan negativamente su experiencia, pueden necesitar una corrección urgente.
    - Condiciones Críticas del Negocio:
    Si el error impacta condiciones críticas del negocio, como procesos esenciales o transacciones, priorízalo para mantener la continuidad operativa.
    - Complejidad de la Corrección:
    Evalúa la complejidad de la corrección. Algunos errores pueden corregirse de manera rápida y sencilla, mientras que otros pueden requerir más tiempo y recursos.

## 23 - ¿Cuál sería el enfoque para reproducir un error antes de informarlo?
    Para reproducir un error antes de informarlo, habria que identificar el escenario y documentar los pasos específicos y datos de entrada. Asegúrarse de usar el mismo ambiente de pruebas y variar las condiciones para comprender el alcance del problema. Registrar la fecha y la hora, revisar registros de eventos y, si es posible, capturar visualmente el error con capturas de pantalla o grabaciones. Proporcionar información detallada y consistente ayudará al equipo de desarrollo a comprender y abordar eficientemente el problema.

## 24 - ¿Qué información incluirías en un informe de error si el error solo ocurre en ciertos sistemas operativos o navegadores?
    En un informe de error para problemas específicos de sistemas operativos o navegadores, incluiría:
    -Descripción del error
    -Sistema operativo y versión
    -Navegador y versión
    -Pasos para reproducir
    -Capturas de pantalla o grabaciones
    -Frecuencia de ocurrencia
    -Fecha y hora
    -Mensajes de error

## 25 - ¿Cómo manejarías la situación si encontraras un error que ya está documentado, pero aún no se ha corregido?
    Verificaria la documentación existente, confirmaria el estado actual del error y lo reproduciria para confirmar, en el caso de tener informaciona adicional, como algun detalle especifico, lo añadiria en comentarios para ayudar a describir la descripcion del problema.

## 26 - Explica la diferencia entre el frontend y el backend en el desarrollo web.
    La diferencia entre front y back, es que el Front-end es lo que sería lo visual lo que el usuario puede ver (diseño de web, botones reactivos, responsive design, etc), mientras que el Back-end es referido a las funciones de una web o programa (ya sea para registrar los datos de un usuario a una base de datos, el realizar una transacción en una aplicacion, etc).
    En resumen el front es lo visual mientras que el back es aquello que el usuario no puede ver pero que se presenta como funcionalidad del software.

## 27 - Explica la diferencia entre una base de datos SQL y una base de datos NoSQL. ¿Cuándo elegirías una sobre la otra?
    Una base de datos SQL es relacional y utiliza un lenguaje estructurado de consultas, es ideal para datos estructurados y relaciones complejas, mientras que la base de datos NoSQL, es una base no relacional, la cual es más flexible y escalable, adecuado para datos no estructurados y entornos que requieren alta velocidad y escalabilidad.
    La elección entre una base de datos SQL y NoSQL depende de si los datos tienen o no relaciones complejas y de los requisitos específicos del proyecto, como escalabilidad y flexibilidad. 
    Si los datos son principalmente estructurados y requieren relaciones, SQL puede ser más adecuado, pero si la flexibilidad y la escalabilidad son prioritarias, especialmente para datos no estructurados, NoSQL podría ser la mejor opción.
    Las diferencias entre HTML, CSS y JavaScript, serian que HTML seria la estructura o el esqueleto de la web, el CSS seria el aspecto visual o el como se veria la web, y JavaScript nos da la interactividad con la pagina web ya que es el que ejecuta funciones y nos da una dinamica. Este conjunto nos permite crear paginas web con contenido, estilo y funcionalidad.

## 28 - ¿Cuáles son las diferencias entre HTML, CSS y JavaScript? ¿Cuál es su papel en el desarrollo frontend?
    Una API (Interfaz de Programación de Aplicaciones) es como un intermediario que permite a distintos programas comunicarse y compartir recursos o servicios sin necesidad de entender los detalles internos a traves de peticiones(HTTP).

## 29 - ¿Qué es una API?
    La Programación Orientada a Objetos (POO) es un paradigma de programación que organiza el código alrededor de "objetos" que combinan datos y funciones relacionadas. Estos objetos interactúan entre sí, facilitando la modularidad y reutilización del código.

## 30 - Explica el concepto de Programación Orientada a Objetos(POO).
    La Programación Orientada a Objetos (POO) es un paradigma de programación que organiza el código alrededor de "objetos" que combinan datos y funciones relacionadas. Estos objetos interactúan entre sí, facilitando la modularidad y reutilización del código.

## 31 - ¿Cuál es la diferencia entre una clase y un objeto?
    En programación orientada a objetos, una "clase" es una plantilla que define las propiedades y comportamientos de un objeto, mientras que un "objeto" es una instancia específica de esa clase, con valores especificos para sus propiedades. La clase es como un molde, y el objeto es la construcción basada en ese molde.

## 32 - Explica el concepto de herencia, polimorfismo y encapsulamiento.
    -Herencia: Permite a una clase heredar propiedades y comportamientos de otra clase, facilitando la reutilización de código y la creación de jerarquías de clases.
    -Polimorfismo: Permite a objetos de diferentes clases responder a un mismo mensaje o método de manera única, lo que brinda flexibilidad y extensibilidad al código.
    -Encapsulamiento: Ayuda a controlar el acceso y proteger la integridad de los datos, mejorando la modularidad y la seguridad del código. Esto se hace a traves del uso de los modificadores de acceso como "Public", "Private" o "Protected", etc, estos determinan la visibilidad y el alcance de los atributos y metodos de las clases.


## PARTE 2
## 1 - Encuentra un error en la siguiente función:

```` Java
public String calcularSueldo(){
    double sueldoContractor = tarifaContractor*getHorasTrabajadas();
    return sueldoContractor;
}
````
### Solucion:
El error se encuentra en el valor de retorno del metodo calcularSueldo. Es decir, el metodo "calcularSueldo" es un metodo que debe retornar un valor de tipo "String", pero en el desarrollo del metodo se crea una variable de tipo "double" llamada "sueldoContractor", y retorna esa misma variable.
Asi que el conflicto es que el metodo retorna un valor con otro tipo de dato("Double"), en vez del tipo de dato esperado("String")

La forma correcta para retornar un valor de tipo double:
```` Java
public double calcularSueldo(){
    double sueldoContractor = tarifaContractor*getHorasTrabajadas();
    return sueldoContractor;
}
````

## 2 - Encuentra 2 errores en el siguiente código:

```` Java
private class Guitarra extends Instrumento{
    
    @Override
    public void tocar {
        System.out.println("Tocar guitarra");
    }
}
````
### Solucion:
El error seria que el metodo "tocar" le falta "()" para que funcione, ademas falta el constructor en la clase, que el constructor debe llamar al constructor de la clase base mediante "super()"

## 3 - Crear un getter para la siguiente funcion:

```` Java
private int sumar(int a, int b){
    return a+b;
}
````

### Solucion: 

La forma de hacer un get para ese metodo es el siguiente:
```` Java
public int getSuma(int a, int b){ return sumar(a, b); }
````

## PARTE 3

### 1 - Crear un objeto de tipo perro que tenga unos métodos propios(ladrar, jugar) y unos atributos heredados de la clase Animales(cantidad de patas, edad, pelaje).

### Solucion:

#### Clase "Animales":

```` Java
public class Animales {
    private String cantidad_de_patas;
    private String edad;
    private String pelaje;
}
````

#### Clase "Perro":
```` Java
public class Perro extends Animales{
    public void ladrar(){
        System.out.println("El Perro esta ladrando");
    }

    public void jugar(){
        System.out.println("El perro esta jugando");
    }
}
````

### 2 - Crear un array de 5 números enteros y calcular el número más grande.

### Solucion:
```` Java
int[] numeros = {2, 4, 9, 0, 3};
int maximo = numeros[0];
for (int e: numeros) {
    if(e > maximo){
        maximo = e;
    }
}
System.out.println("El numero mas grande de la lista de numeros es: " + maximo);
````

### 3 - Convertir las letras de una palabra de minúsculas a mayúsculas.

### Solucion:
```` Java
String palabra = "aLgoSemEocuRRirA";
palabra = palabra.toUpperCase();
System.out.println("La palabra en mayusculas es: " + palabra);
````
