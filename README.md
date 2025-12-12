# Taller4-AlonsoJorquera-NicolasBugueno

Alonso Hernan Jorquera Rodriguez (hernanAJR) - 20.948.058-1 ||
Nicolás Ignacio Bugueño Rementería (nibugr) - 20.007.300-2



## Información del Proyecto
**Asignatura:** Programación Orientada a Objetos  
**Semestre:** II Semestre 2025  
**Institución:** Universidad Católica del Norte  
**Carrera:** Ingeniería Civil en Computación e Informática e  Ingeniería en Tecnologias de Informacion

##  Integrantes del Grupo
| Nombre | RUT | Carrera | 
|--------|-----|---------|
| Nicolás Bugueño | 20.007.300-2| Ingeniería Civil en Computación e Informática |
| Alonso Jorquera | 20.948.058-1 | Ingeniería en Tecnologias de Informacion | 

##  Objetivos del Taller
- Diseñar e implementar un sistema de curricular educativa, enfocandose en el seguimiento del progreso de los estudiantes en lineas de
  certificación que la institución creó para suplir la demanda de especializaciones en la industria.
- Aplicar patrones de diseño (Singleton, Factory, Strategy, Visitor)
- Crear una GUI util
- Desarrollar menús interactivos para diferentes roles de usuario
##  Arquitectura del código
- Se implementó una arquitectura de tres capas, con paquetes: Dominio, Lógica y PresentacionGUI
- Dentro del Dominio, se crearon todas las clases identificadas del análisis del problema entregado:
  Usuario -> (Administrador/Estudiante/Coordinador), Curso/Certificacion/Nota/Registros, además de la implementacion
  de UsuariosFactory.
- Dentro de la Lógica, se crearon todas las clases funcionales para la resolución del problema, principalmente:
  Sistema/App y la implementacion del patrón Strategy (EstrategiaValidacion -> ValidacionPorAsignaturascriticas/PorCreditos/PorPromedio.
- PresentacionGUI solo contiene la clase GUI, que nos permite implementar la interfaz gráfica. 
