# 05-Instalar-Ubuntu

# Introducción

El concepto de máquina virtual puede definirse como equipos virtuales o equipos definidos por software dentro de servidores físicos, donde solo existen como código. Una máquina virtual (Virtual machine en inglés abreviado VM) es una réplica, en cuanto a comportamiento, de un equipo físico, como una PC, teléfono inteligente o un servidor, etc.

[Wikipedia (2023)](https://es.wikipedia.org/wiki/M%C3%A1quina_virtual)

Ubuntu es una distribución Linux basada en Debian GNU/Linux, que incluye principalmente software libre y de código abierto.

[Wikipedia (2023)](https://es.wikipedia.org/wiki/Ubuntu)

# Material Necesario

- [VirtualBox](https://github.com/RaulToribio/01-Instalar-VirtualBox)
- [Ubuntu 22.04.1 LTS](https://github.com/RaulToribio/02-Descargar-Ubuntu)
- [Crear Máquina Virtual](https://github.com/RaulToribio/03-Crear-Maquina-Virtual)
- [Configurar Máquina Virtual](https://github.com/RaulToribio/04-Configurar-Maquina-Virtual)

# Material de Referencia

- [Instalación de Ubuntu 20.04 en VirtualBox Windows (Codigo IoT)](https://edu.codigoiot.com/course/view.php?id=812)

# Instrucciones

![https://raw.githubusercontent.com/RaulToribio/05-Instalar-Ubuntu/main/Im%C3%A1genes/Instalar%20Ubuntu%20(1).png](https://raw.githubusercontent.com/RaulToribio/05-Instalar-Ubuntu/main/Im%C3%A1genes/Instalar%20Ubuntu%20(1).png)

Clic en “Iniciar”.

![https://raw.githubusercontent.com/RaulToribio/05-Instalar-Ubuntu/main/Im%C3%A1genes/Instalar%20Ubuntu%20(2).png](https://raw.githubusercontent.com/RaulToribio/05-Instalar-Ubuntu/main/Im%C3%A1genes/Instalar%20Ubuntu%20(2).png)

Se mostrará GNU GRUB V 2.06.

Dejando la selección en “Try or Install Ubuntu” presionar la tecla “*e”* para editar los comandos antes de arrancar el sistema.

![https://raw.githubusercontent.com/RaulToribio/05-Instalar-Ubuntu/main/Im%C3%A1genes/Instalar%20Ubuntu%20(3).png](https://raw.githubusercontent.com/RaulToribio/05-Instalar-Ubuntu/main/Im%C3%A1genes/Instalar%20Ubuntu%20(3).png)

Utilizar las flechas de dirección del teclado ara desplazarse en la pantalla de comandos previos al arranque del sistema.

![https://raw.githubusercontent.com/RaulToribio/05-Instalar-Ubuntu/main/Im%C3%A1genes/Instalar%20Ubuntu%20(4).png](https://raw.githubusercontent.com/RaulToribio/05-Instalar-Ubuntu/main/Im%C3%A1genes/Instalar%20Ubuntu%20(4).png)

Agregar el argumento `vga=791`.

Esto hará que la resolución de la ventana cambie a 1024*768@16 bit.

Para más resoluciones se puede consultar [Linux Video Mode Numbers](https://en.wikipedia.org/wiki/VESA_BIOS_Extensions#Linux_video_mode_numbers).

![https://raw.githubusercontent.com/RaulToribio/05-Instalar-Ubuntu/main/Im%C3%A1genes/Instalar%20Ubuntu%20(5).png](https://raw.githubusercontent.com/RaulToribio/05-Instalar-Ubuntu/main/Im%C3%A1genes/Instalar%20Ubuntu%20(5).png)

Presionar la combinación de teclas “Ctrl + X” o “F10” para arrancar el sistema.

![https://raw.githubusercontent.com/RaulToribio/05-Instalar-Ubuntu/main/Im%C3%A1genes/Instalar%20Ubuntu%20(6).png](https://raw.githubusercontent.com/RaulToribio/05-Instalar-Ubuntu/main/Im%C3%A1genes/Instalar%20Ubuntu%20(6).png)

Seleccionar idioma “English” e “Install Ubuntu”.

![https://raw.githubusercontent.com/RaulToribio/05-Instalar-Ubuntu/main/Im%C3%A1genes/Instalar%20Ubuntu%20(7).png](https://raw.githubusercontent.com/RaulToribio/05-Instalar-Ubuntu/main/Im%C3%A1genes/Instalar%20Ubuntu%20(7).png)

Seleccionar la distribución de teclado.

Para comprobar que nuestro teclado está realmente en la distribución Español (Latino América) podemos escribir “*Ñ*”, “***”, “*¿?*”.

Clic en “Continue”.

![https://raw.githubusercontent.com/RaulToribio/05-Instalar-Ubuntu/main/Im%C3%A1genes/Instalar%20Ubuntu%20(8).png](https://raw.githubusercontent.com/RaulToribio/05-Instalar-Ubuntu/main/Im%C3%A1genes/Instalar%20Ubuntu%20(8).png)

Dejar marcadas las opciones “Minimal Installation” e “Install Third-Party Sowftware for grapichs and Wi-Fi Hardware and Additional Media Formats”.

Clic en “Continue”.

![https://raw.githubusercontent.com/RaulToribio/05-Instalar-Ubuntu/main/Im%C3%A1genes/Instalar%20Ubuntu%20(9).png](https://raw.githubusercontent.com/RaulToribio/05-Instalar-Ubuntu/main/Im%C3%A1genes/Instalar%20Ubuntu%20(9).png)

Dejar seleccionada la opción “Erase Disk and Install Ubuntu”. Nuestra información del sistema operativo anfitrión no se verá afectada ya que nos encontramos trabajando en una máquina virtual con un disco duro virtual.

Clic en “Install Now”.

![https://raw.githubusercontent.com/RaulToribio/05-Instalar-Ubuntu/main/Im%C3%A1genes/Instalar%20Ubuntu%20(10).png](https://raw.githubusercontent.com/RaulToribio/05-Instalar-Ubuntu/main/Im%C3%A1genes/Instalar%20Ubuntu%20(10).png)

Clic en “Continue”.

![https://raw.githubusercontent.com/RaulToribio/05-Instalar-Ubuntu/main/Im%C3%A1genes/Instalar%20Ubuntu%20(11).png](https://raw.githubusercontent.com/RaulToribio/05-Instalar-Ubuntu/main/Im%C3%A1genes/Instalar%20Ubuntu%20(11).png)

Seleccionar zona horaria correspondiente a la ubicación actual.

Clic en “Continue”.

![https://raw.githubusercontent.com/RaulToribio/05-Instalar-Ubuntu/main/Im%C3%A1genes/Instalar%20Ubuntu%20(12).png](https://raw.githubusercontent.com/RaulToribio/05-Instalar-Ubuntu/main/Im%C3%A1genes/Instalar%20Ubuntu%20(12).png)

Crear un usuario.

Clic en “Continue”.

![https://raw.githubusercontent.com/RaulToribio/05-Instalar-Ubuntu/main/Im%C3%A1genes/Instalar%20Ubuntu%20(13).png](https://raw.githubusercontent.com/RaulToribio/05-Instalar-Ubuntu/main/Im%C3%A1genes/Instalar%20Ubuntu%20(13).png)

Se copiarán los archivos del sistema operativo.

![https://raw.githubusercontent.com/RaulToribio/05-Instalar-Ubuntu/main/Im%C3%A1genes/Instalar%20Ubuntu%20(14).png](https://raw.githubusercontent.com/RaulToribio/05-Instalar-Ubuntu/main/Im%C3%A1genes/Instalar%20Ubuntu%20(14).png)

Iniciará el proceso de instalación del sistema operativo.

![https://raw.githubusercontent.com/RaulToribio/05-Instalar-Ubuntu/main/Im%C3%A1genes/Instalar%20Ubuntu%20(15).png](https://raw.githubusercontent.com/RaulToribio/05-Instalar-Ubuntu/main/Im%C3%A1genes/Instalar%20Ubuntu%20(15).png)

Reiniciar la máquina virtual una vez terminada la instalación del sistema operativo.

# Evidencias

![https://raw.githubusercontent.com/RaulToribio/05-Instalar-Ubuntu/main/Im%C3%A1genes/Instalar%20Ubuntu%20(15).png](https://raw.githubusercontent.com/RaulToribio/05-Instalar-Ubuntu/main/Im%C3%A1genes/Instalar%20Ubuntu%20(15).png)

# Créditos

> [José Raúl Toribio Gabriel](https://github.com/RaulToribio)
> 

> [Codigo IoT](https://github.com/codigo-iot)
>