# TAG 1 - INTRO

### Habilidades técnicas

- Diseñar casos de pruebas
- Aplicar técnicas de testing
- Manehar un gestor de incidencias (**Jira**)
- Manejar un consultor de DB (**MySQL**)
- Manejar un consultor de APIs
- Aplicar un framework de automatización (**Selenium**)
- Manejar Git para CI/CD

Extras:

- Certificado ISTQB

### IT

- Desarrollo de SW
- Desarrollo Mobile/Web
- Videojuegos
- Analistas/ Consultores
- Sopote del usuario
- Infraestructura
- Calidad de SW (**QA**)
  - Tester
  - Analista
  - Ing. en automatización de pruebas
  - Especialista en seg. de la inf.

### Equipo de desarrollo

- Business analyst (BA)/ Product owner (PO)
- Product manager (PM)
- User Experience (UX)/ User Interface (UI)
- Developer (Dev)
- Test Automation Engineer (TAE)
- Quality Assurance (QA)

### Ciclo de vida del desarrollo de SW

Software Development Life Cicle (SDLC)

1. Planning (ROM)
2. Requeriment analysis
3. SW Design (Flow charts)
4. SQ Development (Coding)
5. **SW Testing (QA)**
6. Product release (or Deployment)
7. Maintenance

Los mov. entre fases se conocen como: *Deploy*

<img src="images/im_09.png" width="200" style="float: left;">



### Ciclo de vida de pruebas de SW

Software Testing Life Cicle (STLC)

1. Requeriment analysis
   - Test types
   - Priorities and focus
   - Requirements Traceability Matrix (RTM)
   - Test env details
   - Automation viability
2. Test planning
   - Test strategy
   - Efforts and costs
   - Limitations
3. Test design (test cases, scripts)
4. Env setup (programs)
5. Test execution
6. Closure (pass and fail reports)



*RTM: document that maps and traces user requirement with test cases.*



# TAG 2 - NIVELES DE TESTING

### Macro-types

- Functional (requirements)
- Non-functional (stress, performance)
- Maintenance

### Macro-levels

- Blackbox -> Vemos el código (Backend, Unit & Service levels)
- Graybox (Service level)
- Whitebox -> No vemos el código (Frontend, Service & UI levels)

### Levels (functional)

More isolation & Faster ($)	<----------------------->	More integration & Slower ($$$)



​	**Unit Test		Service/Integration		UI			UAT**

​						      (Backend)		    (Frontend)

​						or DB/API testing



*UI: User Interface (se le presenta al usuario)* 

*UAT: User Acceptance Testing*

*API: Application Programming Interface*

*Un bus o una API puede verse como un medio para traernos información desde el backend hasta el frontend. Es decir, mueven información desde  'bases de datos' de nuestro SW.*



Nosotros **NO** hacemos **unit test**, lo hacen los developers.

El UAT lo hacen los clientes y el BA.

En todos los macro-niveles se puede decidir entre hacer testing manual y automatizado, pero se recomienda:

- Service -> Automatizado
- UI -> Manual y automatizado





# TAG 3 - TIPOS DE TESTING

### Non Functional

- Security
- Performance
- Load/ Stress
- Reliability
- Usability
- Availability

### Functional

- Exploratory                                                         -> UI, UAT

- UI (✔)                                                                  -> UI, UAT

- API (✔)                                                                -> Service

- DB (✔)                                                                 -> Service

- Strategic:

  - End-To-End **E2E** (✔)                                     -> It is DB, API & UI
  - Regression (✔)
    - Smoke (✖)
      - Sanity (✖)
  - Re-Testing (it is done after Devs debug something) 

  

*✔ Indicates that either manual or automated approach can be used.*

*✖ Indicates Unit testing, made only by Devs*

*UI Testing is also known as System testing, and represents roughly 80% of all QA's tests*



# TAG 4 - SCRUM

### Process

1. Initiation
2. Requirements definition
3. Design
4. Development
5. Test
6. Release
7. Maintenance



​												  Daily Stand Up

USER STORIES	BACKLOG	PLANNING MEETING	SPRINT	DEPLOYMENT



![image-20240213190439061](C:\Users\Diego\AppData\Roaming\Typora\typora-user-images\image-20240213190439061.png)