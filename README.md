# Práctica Comandos de Linux  

## 1. Título  
Comandos de Linux

## 2. Tiempo de duración  
20 minutos.  

## 3. Fundamentos  

Linux es un sistema operativo ampliamente utilizado en servidores, supercomputadoras y entornos de desarrollo debido a su estabilidad, seguridad y flexibilidad. Una de sus características principales es el manejo mediante **línea de comandos**, lo cual permite al usuario interactuar directamente con el sistema operativo para administrar archivos, procesos y configuraciones.  

El uso de comandos en Linux ofrece ventajas como:  
- **Automatización:** se pueden crear scripts para ejecutar múltiples instrucciones de manera repetitiva.  
- **Precisión:** cada comando cumple una función específica.  
- **Versatilidad:** se pueden combinar comandos mediante tuberías (`|`) o redirecciones (`>` y `>>`).  

En esta práctica se utilizaron los siguientes conceptos:  

- Creación de directorios con `mkdir`.  
- Creación y edición de archivos de texto con `echo`, `nano` o `vim`.  
- Copia y movimiento de archivos con `cp` y `mv`.  
- Redirección de contenido con `>` (sobrescribe) y `>>` (añade).  
- Eliminación de archivos y carpetas con `rm` y `rmdir`.  
- Visualización de historial de comandos con `history` y redirección de salida a un archivo.  

## 4. Conocimientos previos  

Para realizar esta práctica el estudiante debe conocer:  
- Comandos básicos de Linux (mkdir, ls, cp, mv, rm, history).  
- Concepto de directorio de trabajo.  
- Manejo básico de un editor de texto en la terminal.  
- Conocer de Git y GitHub para subir archivos.  

## 5. Objetivos a alcanzar  

- Crear y organizar carpetas y archivos en Linux.
- Mover, copiar y eliminar archivos usando comandos básicos.
- Usar redirecciones para manejar contenido en archivos de texto.
- Guardar el historial de comandos como evidencia.
- Subir todo al repositorio de GitHub y familiarizarse con la terminal.
  
## 6. Equipo necesario  

- Computador con Windows/Linux/Mac.  
- Git Bash o WSL Ubuntu instalado.  
- Acceso a internet.  
- Cuenta de GitHub Personal.  

## 7. Material de apoyo  

- Documentación de Linux.
- Videos de youtube. 
- Tutoriales de Git y GitHub.  

## 8. Procedimiento  

Paso 1. Crear carpeta principal y subcarpetas.  

mkdir proyecto_comandos
cd proyecto_comandos
mkdir documentos imagenes scripts

<img width="886" height="187" alt="image" src="https://github.com/user-attachments/assets/5a9df9e8-ac0e-46e3-aba5-788931192e6e" />


Paso 2. Crear archivo notas.txt en documentos y añadir contenido.

cd documentos
echo "Primera línea" > notas.txt
echo "Segunda línea" >> notas.txt
echo "Tercera línea" >> notas.txt

Paso 3. Copiar y mover archivos.

cp notas.txt ../scripts/backup_notas.txt
mv ../scripts/backup_notas.txt ../imagenes/

Paso 4. Crear resumen.txt y redirigir contenido.

cat notas.txt > resumen.txt
echo "Nueva línea en resumen" >> resumen.txt

Paso 5. Eliminar archivo y carpeta.

rm ../imagenes/backup_notas.txt
rmdir ../imagenes

Paso 6. Guardar historial en archivo.

history | tee tarea-s1-Fernando_Castro.txt

## 9. Resultados esperados:
Se armó la estructura de carpetas (documentos, imagenes, scripts).

Se crearon y movieron archivos como notas.txt y resumen.txt.

Se practicó redirección y tuberías en la terminal.

Se eliminó la carpeta imagenes sin problemas.

Se guardó el historial de comandos en tarea-s1-Fernando_Castro.txt.

Todo se subió a GitHub como evidencia de la práctica.

## 10. Bibliografías
Atlassian. (s. f.). Git bash: definición, comandos y primeros pasos. Atlassian. https://www.atlassian.com/es/git/tutorials/git-bash
Facultad de Ingeniería, Universidad de la República. (s. f.). Tutorial de Linux. Recuperado de https://www.fing.edu.uy/inco/cursos/sistoper/recursosLaboratorio/tutorial0.pdf



