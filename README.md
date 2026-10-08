Taller de Repaso General en C++

Información del proyecto

- Materia: Laboratorio de Programación (LPR)
- Curso: 5.º año
- Actividad: 6 - Taller práctico de repaso y consolidación en C++
- Año: 2026
- Estudiante: Lucas Benitez

Descripción

Este proyecto consiste en un programa desarrollado en C++ que permite repasar y poner en práctica conceptos importantes de programación, como la recursividad, la búsqueda secuencial en arreglos y el uso de punteros para intercambiar valores.

Funcionalidades

El programa contiene tres retos:

1. Suma recursiva: calcula la suma de los números desde 1 hasta un número determinado.
2. Búsqueda secuencial: busca un valor dentro de un arreglo y muestra su posición y dirección de memoria.
3. Intercambio con punteros: intercambia los valores de dos variables utilizando punteros.

Tecnologías utilizadas

- Lenguaje C++.
- Compilador g++.
- Visual Studio Code.
- Git y GitHub para el control de versiones.

Estructura del proyecto
<pre>
repasogeneral/
├── .gitignore                      <-- Reglas de exclusión (.exe, .vscode/, *.out)
├── LICENSE                         <-- Licencia MIT de uso escolar
├── README.md                       <-- Portada explicativa con integrantes y menú de retos
├── docs/                           <-- Carpeta para entregables formales
│   └── InformeEEST1_LPR2026_ACT06_G99_Informe_v1.0.0.pdf <-- ENTREGABLE EN PDF (Normas APA v7)
│   └── manuales
│   	├── manual_programador_v1.0.0.pdf 	<-- Basado en el ejemplo oficial
│   	├── manual_usuario_v1.0.0.pdf	<-- Basado en el ejemplo oficial 	
│   └── CHANGELOG.md                <-- Registro de cambios y versión SemVer/DocVer
├── src/                            <-- Código fuente modular en C++
│   └── main.cpp                    <-- Suite unificada con los retos del taller
└── capturas/                       <-- Evidencias de ejecución local (.png)
    ├── ejecucion_repasogeneral.png        <-- Captura de la terminal ejecutando los retos
    └── traza_memoria.png           <-- Diagrama de bloques de la memoria RAM hecho a mano

</pre>

Compilación y ejecución

Para compilar el programa, abrir una terminal en la carpeta principal del proyecto y ejecutar:

g++ src/main.cpp -o src/repasogeneral.exe

Después, ejecutar el programa con:

.\src\repasogeneral.exe

Documentación

La carpeta "docs/" contiene el registro de cambios del proyecto ("CHANGELOG.md") y los documentos correspondientes a la actividad. La carpeta "capturas/" almacena las imágenes de las ejecuciones y pruebas realizadas.

Licencia

Este proyecto utiliza la licencia MIT.