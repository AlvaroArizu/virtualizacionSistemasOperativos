# Modulo 2
# Guest additions
Las Guest Additions de Virtual box son un paquete de software el cual es un complemento de este.
Debe instalarse en cada maquina 
* Se las conoce como aplicaciones del huesped
* Sirven para: 
   * Proveen mejoras
   * Integracion del cursar del raton
   * Mejora el soporte de video
   * Sincronia de zona horaria
   * Uso de carpetas compartidad
   * Uso de portapapeles compartido  
  
# Instalacion de Gues Additions en Windows y Linux
### Windows
Desde la ventana de la maquina virtual, procedemos a realizar la insercion del d virtual de la GA(Es un disco que esta integrado en VB), en dispositivo (Arriba), ponemos la opcion insertar GA
### Linux
Se hace a traves de mandos en la consola 
* apt-get update
* apt-get instal virtualbox-guest-x11
* reboot
Luego de esto: 
1. Se adapta la pantalla
2. Dimensiona la panatalla
3. Habilita funciones especiales
   
# Portapapeles  y arrastar/soltar en VirtualBox
Es una herramienta que poseen diversos sist operativos, esta herramienta permite copiar y pegar info entre apps

La realcion que hay entre el portapapeles y VB, esta deshabilitada por defecto

Para que fuinciones:
* Tener la GA
* Repositorio actualizado(En Linux)
* MV apagada

Paso a paso:
1. Configuracion
2. General
3. Avanzado 
4. Portapales compartido(Bidireccional)
5. Arrastar y soltar(Bidireccional)

# Carpetas compartidas en Virtual Box
Las carpetas compartidas pretenden susutituir la costumbre de compartir archivos entre computadoras
Previamnete deben estar instaladas las guest additions

Paso a paso
1. Con la maquina prendida vamos a dispositivos
2. Carpetas compartidas
3. Preferencias de carpetas compartidas 
4. En el signo con la carpta y el mas apretamos (A la derecha)
5. Apametros a definir son 2
      1. Ruta de la carpeta compartida
      2. Nombre de la carpeta compartida
6. Reiniciar el equipo de la maquina virtual
   
# Clonacion de Maquinas Virtuales
Esto es realizar una copia exacta de un maquina virtual previamente creada pero con una identidad distina. Los discos duros virtuales tendran identificadores distintos (uuid)

 **Principal funcion:** Respalde de una maquina virtul
 (Esto se realiza despues de haber cargado las GA y los programas de terceros)

## Como se realiza la clonacion?
1. La MV debe estar apagada
2. Debe tener instalados todos sus complementos


Paso a paso:
1. Click derecho
2. Clonar
3. Asignar nuevo nombre 
4. Reiniciar la direcion MAC
5. Clonar, 2 tipos:
     1.  Clonacion completa: copia exacta
     2.  Clonacion Enlazada: Nueva maquina y los archivos estaran vinculados  
   
# Copias de seguridad en Maquinas Virtuales
Son tambien llamada espejo tiene como objetivo incoprporar las maquinas virtuales creadas en otros anfitriones, siempre que dispongan dela misma version de VB instalada.
La maquina virtual no debe estar encendida

Paso a paso
1. Selecionamos la MV
2. Archivo
3. Exportar servicio virtualizado
4. Se genera un archivo .ova






