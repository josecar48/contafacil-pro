PASOS PARA EL INSTALADOR
-Paso 1: Crear el ejecutable de tu aplicación (Con Web2Exe)
En este paso transformas tu diseño web en un programa ejecutable tradicional para Windows.
Abres Web2Exe.Seleccionas la carpeta donde tienes tus archivos HTML, CSS y JavaScript.
La herramienta procesará todo y te devolverá un archivo llamado 
(por ejemplo) MiSoftwareContable.exe junto con algunos archivos de soporte.
Resultado de este paso: Ya tienes tu programa funcional, pero está "suelto" 
(si se lo mandas así al contador, no se instalará correctamente en su sistema).
-Paso 2: Crear el instalador oficial y configurar tu autoría (Con NSIS)
Aquí es donde empaquetas el ejecutable del Paso 1 para que tenga un asistente de instalación y lleve tus datos de autor legal. 
El código NSIS es un archivo de texto independiente (con extensión .nsi) que lee el compilador de 
