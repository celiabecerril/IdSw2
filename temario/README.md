# Temario

## Introducción

> [Nivel: la base...](00-introduccion/README.md)

- [x] [Software & Complejidad](00-introduccion/software.md)  [*oldDiapos*](https://docs.google.com/presentation/d/1N0wtTid8iFAlyR8TNDbCR3FxIkJYvQ_p5kC3pqkkB1c/edit?usp=sharing) / [*oldDiapos*](https://docs.google.com/presentation/d/1K8TusDz7jbpSQkffZdF_-TLDTjfjfxWs-dr9Lf7js80/edit?usp=sharing)
- [x] [Análisis y Diseño](https://docs.google.com/presentation/d/1fPbUOZ6epnsC0RzccIc-VI7f-WO2lnzxWnnpEryBTVg/edit?usp=sharing)

## [Diseño](01-diseño/README.md)

> Nivel: línea...

- [x] [Estrategias de clasificación](https://docs.google.com/presentation/d/1GJ-J5IKzcYiXpODAjQpXQaGmkeu8ClJ3ho_OXcZOpE4/edit?usp=sharing)
- [x] Relaciones entre clases
    - [x] [xColaboración](https://docs.google.com/presentation/d/1pMD3ONO1Urug8n9ZWnnURv0lS_0F0PNi1O5rv73nROY/edit?usp=sharing)
    - [x] [xTransmisión](https://docs.google.com/presentation/d/1ghZkWWi5LOSibOTaVjteYxgyBm6G83nhW5B5BVqkV6c/edit?usp=sharing)
- [x] [Clean code: legibilidad](https://docs.google.com/presentation/d/1JKWWhu-AzPAJ0xSPxwuM0zmDvt86FjU7WPLhK1UMmoI/edit?usp=sharing)

### Caso ejemplo: [repo de **theWorld**](https://github.com/puntoReflex/pyAspiradora)

- Clases por colaboración: *rama mundo-habitacion-baldosa-gato*
- Clases por transmisión: *rama mundo-habitacion-baldosa-elemento*

## [Diseño modular](02-diseñoModular/README.md#Cómo)

> Nivel: clases y métodos...

- [x] Fundamentos: [modularidad](02-diseñoModular/modularidad.md) & [jerarquización](02-diseñoModular/jerarquizacion.md)
- [x] [Cohesión](02-diseñoModular/cohesion.md)
- [x] [Acoplamiento](02-diseñoModular/acoplamiento.md)
- [x] [Tamaño](02-diseñoModular/tamaño.md)
- [x] Smell Codes
  |Cohesión|Acoplamiento|Tamaño|
  |-|-|-|
  |[Alternative classes with different interfaces - Clases alternativas con distintas interfaces](02-diseñoModular/sc.acdi.md)|[Inappropriate Intimacy - Inapropiada intimidad](02-diseñoModular/sc.ii.md)|[Long Parameter List - Listas de parámetros larga](02-diseñoModular/sc.lpl.md)|
  |[Features envy - Envidia de características](02-diseñoModular/sc.fe.md)|[Incomplete Library Class - Clase de biblioteca incompleta](02-diseñoModular/sc.ilc.md)|[Long Method - Métodos largos](02-diseñoModular/sc.lm.md)|
  |[Data class - Clase de datos](02-diseñoModular/sc.dc.md)||[Large Class - Clase grande](02-diseñoModular/sc.lcl.md)|
  |[Divergent Change - Cambios divergentes](02-diseñoModular/sc.dch.md)||[Temporary Fields - Campos temporales](02-diseñoModular/sc.tf.md)|
  |[Shotgun Surgery - Cirugía con escopeta](02-diseñoModular/sc.ss.md)
  |[Data Clumps - Grupo de datos](02-diseñoModular/sc.dcl.md)
  |[Primitive Obssesion - Obsesión por tipos primitivos](02-diseñoModular/sc.po.md)
  |[Lazy Classes - Clases perezosas](02-diseñoModular/sc.lc.md)
  |[Acerca de... getters y setter](02-diseñoModular/gettersSetter.md)
- [ ] Técnicas
  - [ ] Abstracción de interfaz
  - [ ] Diseño por contrato
  - [ ] Patrones de indirección

## Diseño orientado a objetos

> Nivel: Jerarquías de clasificación

- [ ] ***S*** Principio de responsabilidad única
- [ ] ***O*** Principio de abierto/cerrado
- [ ] ***L*** Principio de Sustitución de Liskov
- [ ] ***I*** Principio de segregación de interfaces
- [ ] ***D*** Principio de Inversión de Dependencias
- [ ] Demeter
- [ ] Inversión de Control
- [ ] Inyección de Dependencias

## Temario++

### Patrones de diseño

### Arquitectura de software

### Arquitectura MV*

- [x] Artículos varios recopilados en la [carpeta de documentos](/documentos/README.md).

---

Con todo esto, [a día de hoy deberíamos saber](aDiaDeHoy.md)...
