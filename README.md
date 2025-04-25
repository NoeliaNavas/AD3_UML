# Sistema de Gestión de Torneos de eSports

## Autor
Noelia Navas Garrido  
[GitHub Profile](https:https://github.com/NoeliaNavas)

## Descripción del Proyecto
Este proyecto implementa un sistema para gestionar torneos de eSports. Se incluyen diagramas UML y una propuesta de arquitectura modular con clases de entidad, control e interfaz.

### Análisis del problema y requisitos del sistema

Identificamos los **actores** y sus **funcionalidades principales**:

#### Actores

- **Administrador**: gestiona equipos, jugadores y torneos.  
- **Jugador**: pertenece a equipos.  
- **Sistema**: interactúa automáticamente con datos (por ejemplo, generar emparejamientos).

#### Funciones principales

- Registrar equipos  
- Añadir jugadores  
- Consultar listas de equipos y jugadores  
- Crear torneos  
- Inscribir equipos  
- Generar emparejamientos  
- Registrar resultados  
- Asignar premios

### Diagrama de Casos de Uso
![Casos de uso](diagrams/casos-uso.jpg)

### Diagrama de Clases
![Diagrama de clases](diagrams/clases.png)

## Justificación del diseño
He tilizado clases de entidad para modelar objetos del dominio (Equipo, Jugador),y una interfaz (GestorEquiposI) para el funcionamiento de la aplicación. He relacionado equipo y jugado con agregacion desde equipo apuntando a jugador ya que si eliminas un equipo el jugador no desaparece.

## Conclusiones
Me ha costado un poco ver las clases desde el caso de usos, finalmente he concluido que estas tres eran las corestas para el caso de uso "Gestión de equipos y jugadores".
Por otro lado tengo bastante claro el el diagrama de uso, los incluse y los extends.
