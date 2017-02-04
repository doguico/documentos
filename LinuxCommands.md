
# Operaciones basicas
## Crear
- touch [NombreArchivo]
- vi [NombreArchivo]

## Editar un archivo 
- vi [Nombre]

## Ver un archivo
- cat [NombreArchivo]
- less [NombreArchivo]

## Copiar 
- Remote to Local: scp  [NombreArchivo] [NuevaUbicacion]         
- Local to Local:  cp   [NombreArchivo] [NuevaUbicacion]  

> Si agrego -r: copia de forma recursiva, es decir absolutamente todo lo que se encuentre en subdirectorios

## Mover
- mv [NombreArchivo] [NuevaUbicacion]

## Eliminar
- Directorio vacio: rmdir [DireccionDirectorio]
- Archivo: rm [NombreArchivo]

> Si agrego -r: Es capaz de borrar todo lo que esta dentro y el directorio tmb > 

## Renombrar 
- mv [Archivo] [NombreNuevo]      

# Vi

## Guardar
- ZZ (Note: capitals) - Save and exit
- :q
- :q! - discard all changes, since the last save, and exit
- :w - save file but don't exit
- :wq - again, save and exit

## Pisaditas
- :set nu -> pone numeritos
- :nG -> se mueve a la linea numero n
- d -> borra
- u -> deshacer

# Comandos Generales
## Descomprimir 
- tar -xzvf [filename]

## Matar un proceso
- Program Id: ps ax  | grep [nombre]  
- kill [programId]

## Descargar e instalar un archivo
- sudo apt install [Nombre]
- sudo apt remove [Nombre]

## Paquetes .DEB
- Instalar: sudo dpkg -i DEB_PACKAGE
- Desinstalar: sudo dpkg -r PACKAGE_NAME

## Pisaditas
- limpiar consola: ctrl + l
- para cancelar: ctrl + c
- parar la ejecucion de un comando: ctrl + z
- Espacios en nombre de archivos
- Ejemplo: Fotos China -> Fotos\ China


Paginas
- https://help.ubuntu.com/community/UsingTheTerminal
