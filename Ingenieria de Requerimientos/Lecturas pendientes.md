![[Pasted image 20260328084251.png]]
![[Pasted image 20260328084337.png]]
![[Pasted image 20260328084411.png]]
![[Pasted image 20260329175345.png]]
Resumen (por ahora):
1. Fundamentos y Definiciones de la Ingeniería de Software (IS)

**Fuentes: Sommerville (Cap. 1) y Pressman (Cap. 1)**

- **Definición de IS:** Es una **disciplina de la ingeniería** que abarca todos los aspectos de la producción de software, desde la especificación inicial hasta el mantenimiento tras la puesta en marcha. Pressman la define como la aplicación de un enfoque **sistemático, disciplinado y cuantificable** al desarrollo.
- **Software Profesional:** No son solo programas; incluye **documentación** asociada y datos de **configuración** necesarios para su correcta operación.
- **Actividades Fundamentales del Proceso:** Todo desarrollo implica cuatro etapas clave:
    1. **Especificación:** Definición de qué debe hacer el sistema y sus restricciones.
    2. **Desarrollo:** El diseño y la programación del software.
    3. **Validación:** Asegurar que el software cumple con lo que el cliente desea.
    4. **Evolución:** Modificación del software para adaptarse a cambios en el mercado o necesidades del cliente.
- **Capas de la IS (Pressman):** La ingeniería de software se apoya en una estructura de capas: **Calidad** (fundamento), **Proceso** (marco de trabajo), **Métodos** (el "cómo" técnico) y **Herramientas** (apoyo automatizado como CASE).
- **Atributos de Calidad:** Un software de calidad debe ser mantenible, confiable, seguro, eficiente y aceptable para el usuario. Pressman añade el acrónimo **FURPS** (funcionalidad, usabilidad, confiabilidad, rendimiento y mantenibilidad).
- **Ética:** Los ingenieros de software deben guiarse por principios éticos, como actuar en el interés del público y mantener integridad en su juicio profesional (Código ACM/IEEE).

2. Modelos y Procesos de Software

**Fuentes: Sommerville (Cap. 2) y Pressman (Cap. 2)**

- **Modelos de Proceso Generales (Paradigmas):**
    - **Modelo en Cascada (Waterfall):** Enfoque **lineal y secuencial** donde cada fase se completa antes de iniciar la siguiente. Ideal para requerimientos estables y bien comprendidos.
    - **Desarrollo Incremental:** El sistema se construye como una serie de **versiones (incrementos)**. Reduce costos de cambio y permite entregas rápidas de funcionalidad básica.
    - **Ingeniería Orientada a la Reutilización:** Se basa en integrar componentes existentes o software comercial (**COTS**) en lugar de desarrollar desde cero.
- **Modelos Evolutivos:** Reconocen que el software cambia continuamente. Incluyen el uso de **prototipos** (para aclarar requerimientos inciertos) y el **modelo en espiral** de Boehm, el cual es **impulsado por el riesgo** y repite fases en cada ciclo.
- **Proceso Unificado (RUP/PU):** Un modelo híbrido moderno centrado en la **arquitectura** e impulsado por **casos de uso**. Se divide en fases: Concepción, Elaboración, Construcción y Transición.
- **Flujo del Proceso (Pressman):** Define cómo se organizan las actividades en el tiempo, pudiendo ser lineal, iterativo, evolutivo o paralelo.

3. Paradigmas y Programación Orientada a Objetos (POO)

**Fuentes: Pantaleo (Cap. 3) y Augusto/Sznajdleder (Cap. 14)**

- **Definición de Paradigma:** Es el enfoque o **modelo** con que se piensa y diseña la solución a un problema.
- **Tipos de Paradigmas:**
    - **Imperativo (Procedimental):** Secuencia de sentencias que cambian el estado del programa (ej. C, Pascal).
    - **Funcional:** Basado en funciones matemáticas y lógica declarativa (ej. Haskell, Lisp).
    - **Lógico:** Basado en axiomas, reglas e inferencia (ej. Prolog).
    - **Orientado a Objetos (POO):** Se basa en la descomposición de problemas mediante conceptos del dominio representados como objetos.
    - **Orientado a Aspectos (POA):** Separa conceptos transversales (como seguridad o errores) de la lógica principal para evitar código disperso.
- **Conceptos Clave de la POO:**
    - **Clase:** Estructura que agrupa datos (atributos) y el comportamiento para manipularlos (métodos/operaciones).
    - **Objeto:** Una instancia específica de una clase que posee un estado propio.
    - **Encapsulamiento:** Ocultar los datos internos de un objeto tras una "pared" de métodos públicos (interfaz), reduciendo efectos colaterales.
    - **Herencia:** Permite que una subclase adquiera los atributos y métodos de una clase base, facilitando la reutilización.
    - **Polimorfismo:** Capacidad de objetos de diferentes clases de responder al mismo mensaje de formas distintas (redefinición de métodos).
- **UML (Unified Modeling Language):** Estándar industrial gráfico para modelar sistemas OO mediante diagramas como los de clases, secuencia y estados.

4. Recopilación de Información y Desarrollo Ágil

**Fuente: Kendall & Kendall (Cap. 4, 5 y 6)**

- **Métodos Interactivos (Recopilación directa):**
    - **Entrevistas:** Útiles para obtener opiniones, sentimientos y metas. Requieren preparación y tipos de preguntas (abiertas o cerradas).
    - **JAD (Diseño Conjunto de Aplicaciones):** Sesiones de trabajo grupales intensas para reducir el tiempo de análisis de requerimientos.
    - **Cuestionarios:** Permiten medir actitudes y creencias en una gran muestra de usuarios.
- **Métodos Discretos (Sin interrupción):**
    - **Muestreo:** Selección sistemática de elementos representativos de la población.
    - **Investigación:** Análisis de documentos cualitativos y cuantitativos de la organización.
    - **Observación (STROBE):** Observación del entorno físico y comportamiento de los tomadores de decisiones para confirmar datos de entrevistas.
- **Modelado Ágil y Prototipos:**
    - **Prototipos:** Versiones preliminares para capturar requerimientos de forma rápida (parches, no operacionales, primero de serie, características selectas).
    - **Valores Ágiles:** Comunicación, Simpleza, Retroalimentación y Valentía.
    - **Programación Extrema (XP):** Metodología ágil que lleva las buenas prácticas al límite. Incluye la **programación en pareja** (dos personas en una estación de trabajo), propiedad colectiva del código e **integración continua**.