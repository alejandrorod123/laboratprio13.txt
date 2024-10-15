laboratprio13
Alejandro Rod

 Clonar de Máquinas Virtuales


Pasos

Crear una máquina virtual:
1. Crear una nueva máquina virtual con una instalación de un sistema operativo (ej: Ubuntu).
2. Realizar configuraciones iniciales básicas (ej: instalación de actualizaciones, herramientas de desarrollo).

Clonación de la VM:
1. Apagar la máquina base.
2. En el menú de VirtualBox, hacer clic derecho sobre la VM -> Opción "Clonar".
3. Seleccionar "Clonación Completa" para una copia completa o "Clonación Enlazada" si se desea ahorrar espacio en disco (pero compartiendo discos virtuales).

![image](![imagen1](https://github.com/user-attachments/assets/fee2d2d4-a745-4fe9-a9cb-7dbd5e13a14b)

Verificación:
1. Iniciar ambas máquinas (la original y la clonada) para verificar que ambas funcionan correctamente de manera independiente.

Informe esperado:
- Captura de pantalla de ambas máquinas corriendo de forma simultánea.
- Comandos que verifiquen que tienen configuraciones de red y hostname diferentes.

![image](![imagen2](https://github.com/user-attachments/assets/70239f1c-c4b1-442e-bc10-719b0e20ca3a)

 Uso de Guest Additions

 Objetivo:
Instalar y utilizar Guest Additions para mejorar la integración entre el sistema host y las máquinas virtuales.

Pasos:

#Instalar Guest Additions:
1. Iniciar la máquina virtual.
2. Desde el menú de VirtualBox, ir a "Dispositivos" -> "Insertar imagen de CD de las Guest Additions".
3. Dentro de la VM, abrir un terminal y ejecutar el siguiente comando:
    ```bash
    sudo sh /media/cdrom/VBoxLinuxAdditions.run
    ```
4. Reiniciar la VM.

 Verificación:
1. Probar la redimensión automática de la pantalla.
2. Habilitar y probar la opción de compartir portapapeles y arrastrar y soltar archivos.

Informe esperado:
- Capturas de pantalla del cambio de tamaño dinámico de la ventana.
- Una demostración de arrastrar un archivo entre el host y la VM.

![image](![imagen3](https://github.com/user-attachments/assets/f806ee17-1bfe-48ff-80d5-edfa3e87b5fc)
![image](![imagen4](https://github.com/user-attachments/assets/79c32bd4-3199-41e2-968b-112cf4bab316)


