# Historia de Object Pascal

## Orígenes: Pascal como fundamento

Object Pascal tiene sus raíces en el lenguaje **Pascal**, diseñado entre 1968 y 1969 por el científico suizo **Niklaus Wirth** en el ETH Zúrich. Pascal fue concebido como un lenguaje educativo que fomentara buenas prácticas de programación estructurada, influenciado fuertemente por ALGOL 60. Su primera implementación apareció en 1970 y rápidamente se adoptó en universidades de todo el mundo.

Pascal se caracterizó desde sus inicios por:
- Tipado estático fuerte
- Estructuras de control claras y legibles
- Énfasis en la legibilidad del código
- Portabilidad entre plataformas

---

## La era de Apple y el nacimiento de Object Pascal (1983–1986)

El salto hacia la programación orientada a objetos llegó gracias a una colaboración entre **Apple Computer** y **Niklaus Wirth**. A principios de los años 80, Apple buscaba un lenguaje adecuado para desarrollar software en sus nuevas computadoras Macintosh, que con su interfaz gráfica requerían un modelo de programación más sofisticado.

En **1983**, Apple y Wirth comenzaron a trabajar juntos en una extensión orientada a objetos de Pascal. El resultado fue **Object Pascal**, presentado públicamente en **1986** en la conferencia OOPSLA (Object-Oriented Programming, Systems, Languages & Applications). Larry Tesler, de Apple, fue uno de los arquitectos principales de esta extensión.

Las características clave que se añadieron al Pascal original fueron:
- **Clases y objetos** basados en registros con métodos
- **Herencia** simple
- **Polimorfismo** mediante métodos virtuales
- **Encapsulamiento** de datos y comportamiento

Apple utilizó Object Pascal como el lenguaje principal para desarrollar la primera versión del sistema operativo Mac OS y las herramientas del entorno Macintosh, incluyendo el framework **MacApp**, uno de los primeros frameworks de aplicaciones orientados a objetos.

---

## Turbo Pascal y la popularización en PC (1983–1992)

Mientras Apple desarrollaba Object Pascal, la compañía **Borland International** lanzó en **1983** su propio compilador: **Turbo Pascal**. Creado por Philippe Kahn, Turbo Pascal revolucionó el mercado al ofrecer un entorno de desarrollo integrado (IDE) extremadamente rápido a un precio accesible.

Turbo Pascal dominó el mercado de Pascal en IBM PC durante los años 80 gracias a:
- Tiempos de compilación extremadamente rápidos
- Un IDE integrado en una sola herramienta
- Precio muy competitivo frente a otros compiladores

En **1989**, con **Turbo Pascal 5.5**, Borland incorporó su propia implementación de programación orientada a objetos, tomando como referencia el estándar de Apple pero adaptándolo para el entorno DOS. Esta versión fue el primer contacto de muchos programadores de PC con la orientación a objetos.

Con **Turbo Pascal 6.0 (1990)** y **Turbo Pascal 7.0 (1992)**, Borland refinó aún más las capacidades orientadas a objetos y añadió soporte para la **Turbo Vision**, un framework de interfaz de usuario en modo texto.

---

## Delphi: la gran revolución (1995)

El hito más significativo en la historia de Object Pascal llegó en **1995** con el lanzamiento de **Delphi 1.0** por parte de Borland. Delphi fue diseñado por **Anders Hejlsberg** (quien más tarde crearía C# en Microsoft) y representó una evolución radical del lenguaje y del entorno de desarrollo.

Delphi introdujo:
- Un **IDE visual** con diseño de formularios en tiempo de diseño (RAD - Rapid Application Development)
- La **Biblioteca de Componentes Visuales (VCL - Visual Component Library)**, un framework orientado a objetos para Windows
- Mejoras sustanciales al lenguaje Object Pascal:
  - Nuevas directivas de visibilidad: `public`, `private`, `protected`, `published`
  - **Interfaces** (desde Delphi 3)
  - **Propiedades** con getters y setters
  - Manejo de **excepciones** estructurado
  - **RTTI** (Run-Time Type Information)

Delphi fue un éxito comercial masivo. En la segunda mitad de los años 90 se convirtió en una herramienta predilecta para el desarrollo de aplicaciones Windows empresariales, compitiendo directamente con Visual Basic de Microsoft.

### Evolución de Delphi en los años 90:

| Versión | Año | Novedades principales |
|---|---|---|
| Delphi 1 | 1995 | Primera versión, soporte Win16 |
| Delphi 2 | 1996 | Soporte Win32, strings largos |
| Delphi 3 | 1997 | Interfaces, COM/ActiveX |
| Delphi 4 | 1998 | Sobrecarga de operadores, variantes dinámicas |
| Delphi 5 | 1999 | Mejoras al IDE, soporte para bases de datos |

---

## Kylix, .NET y la expansión multiplataforma (2001–2007)

En **2001**, Borland lanzó **Kylix**, una versión de Delphi para **Linux**, con una biblioteca multiplataforma llamada **CLX (Component Library for Cross-platform)**. Aunque fue un esfuerzo técnico notable, Kylix tuvo una vida corta y fue descontinuado en 2002.

En paralelo, Borland desarrolló **Delphi 8 (2003)** con soporte para la plataforma **.NET** de Microsoft, permitiendo compilar código Object Pascal hacia el CLR (Common Language Runtime). Esta integración nunca logró la adopción esperada, en parte debido a las diferencias filosóficas entre el modelo de Delphi y el ecosistema .NET.

A mediados de los 2000, Borland comenzó a tener dificultades financieras y en **2006** separó su división de herramientas de desarrollo en una nueva empresa llamada **CodeGear**, que más tarde fue adquirida por **Embarcadero Technologies** en 2008.

---

## Free Pascal y Lazarus: la alternativa libre (1993–presente)

Paralelamente al desarrollo comercial, surgió en **1993** el proyecto **Free Pascal (FPC)**, un compilador de código abierto compatible con Turbo Pascal y Delphi. Free Pascal fue creado inicialmente por **Florian Klämpfl** y con el tiempo se convirtió en un proyecto comunitario maduro y estable.

Free Pascal destaca por:
- Soporte para docenas de plataformas y arquitecturas (Windows, Linux, macOS, FreeBSD, ARM, MIPS, etc.)
- Alta compatibilidad con el dialecto Delphi
- Licencia libre (LGPL para la RTL, GPL para el compilador)

En **1999** surgió **Lazarus**, un IDE visual de código abierto basado en Free Pascal, que ofrece una experiencia similar a Delphi pero multiplataforma. Lazarus incluye su propia biblioteca de componentes: la **LCL (Lazarus Component Library)**, compatible conceptualmente con la VCL de Delphi.

---

## La era Embarcadero y la modernización del lenguaje (2008–presente)

Bajo la gestión de **Embarcadero Technologies**, Delphi experimentó una revitalización importante. Embarcadero apostó por la portabilidad y la modernización del lenguaje.

### Delphi 2009 y Unicode
Uno de los cambios más significativos llegó con **Delphi 2009**, que migró el tipo `string` nativo de ANSI a **Unicode (UTF-16)**, adaptando el lenguaje al mundo globalizado.

### FireMonkey y el desarrollo multiplataforma
Con **Delphi XE2 (2011)** se introdujo **FireMonkey (FMX)**, un nuevo framework visual multiplataforma que permitía compilar aplicaciones para:
- Windows
- macOS
- iOS
- Android (desde XE5, 2013)
- Linux (desde Delphi 10.2 Tokyo)

### Extensiones modernas del lenguaje
A lo largo de los años 2010, Object Pascal incorporó características modernas:
- **Genéricos** (Delphi 2009)
- **Métodos anónimos** y closures (Delphi 2009)
- **Atributos personalizados** (Delphi XE)
- **Inferencia de tipos** con `var` en bloques locales (Delphi 10.3 Rio, 2018)
- **Tipos en línea** (*inline variables*) (Delphi 10.3 Rio)
- **Nullables** y mejoras al sistema de tipos

### Delphi bajo IDERA
En **2015**, Embarcadero fue adquirida por **IDERA Inc.**, que continuó el desarrollo activo de Delphi. Las versiones recientes (Delphi 11 Alexandria, Delphi 12 Athens) han mantenido el ritmo de actualizaciones, con mejoras en el IDE, soporte para las últimas versiones de iOS y Android, y refinamientos del lenguaje.

---

## Influencia y legado

Object Pascal dejó una huella profunda en la historia de los lenguajes de programación:

- **Anders Hejlsberg**, principal arquitecto de Delphi/Object Pascal, llevó muchos conceptos a **C#**, el lenguaje estrella de Microsoft que comparte similitudes estructurales notables con Delphi.
- El modelo de **propiedades** de Object Pascal (con `read`/`write`) influyó directamente en C#, Python y otros lenguajes modernos.
- La arquitectura de **componentes visuales** de Delphi fue pionera en el desarrollo rápido de aplicaciones (RAD) y anticipó muchos patrones usados hoy en frameworks como WinForms, Qt y otros.
- La **VCL** sigue siendo uno de los frameworks nativos de Windows más completos y maduros disponibles.

---

## Dialectos principales

A lo largo de su historia, Object Pascal se ha fragmentado en varios dialectos:

| Dialecto | Plataforma | Estado actual |
|---|---|---|
| Delphi (Embarcadero) | Windows, macOS, iOS, Android, Linux | Activo (versión 12) |
| Free Pascal (FPC) | Multiplataforma | Activo, código abierto |
| Lazarus + FPC | Multiplataforma | Activo, código abierto |
| Oxygene (RemObjects) | .NET / JVM / Cocoa | Activo |
| Smart Mobile Studio | Web/JavaScript | Activo |

---

## Conclusión

Object Pascal es uno de los lenguajes más longevos y versátiles de la historia de la computación. Desde sus humildes raíces educativas en los años 70, pasando por su rol central en el primer Macintosh, su explosión comercial con Delphi en los 90, hasta su presencia actual en desarrollo móvil y multiplataforma, Object Pascal ha demostrado una notable capacidad de evolución y adaptación. Su influencia en el diseño de lenguajes modernos y en la industria del software empresarial es innegable y perdura hasta hoy.

---

*Referencias y fuentes adicionales:*
- *Wirth, N. (1971). "The Programming Language Pascal". Acta Informatica.*
- *Tesler, L. (1985). "Object Pascal Report". Apple Computer.*
- *Free Pascal documentation: https://www.freepascal.org*
- *Embarcadero Delphi history: https://www.embarcadero.com*
