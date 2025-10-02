(Previo a esto se tenía instaladas las dependencias de git en el sistema)
Primero se forkeo el repositorio inicial con las instrucciones dadas
Se clonó el repositorio en la computadora
Se instaló wsl y luego ubuntu en la terminal dentro de la carpeta con el clon del repositorio de xv6
Actualizar ubuntu, upgradear ubuntu con sudo apt uptdate/upgrade
Luego instalar qemu esentials con sudo apt install git build-essential qemu-system
|Problema| no corre qemu, no tenia las dependencias de riscv64
Luego instalar riscv4 con sudo apt install gcc-riscv64-linux-gnu
Correr en wsl make qemu exitosamente
Abre xv6 y corro los codigos pedidos en el pdf
ls, echo y el readme funcionan.
ctrl+a y luego x para cerrar qemu
Se crea el informe y se sube

Para las soluciones a los problemas que enfrentamos, uno fue que las instrucciones no las entendíamos bien y buscamos videos que ayudaran al respecto.
videos en cuestion:
https://www.youtube.com/watch?v=zphXW4q6NMw
https://www.youtube.com/watch?v=yHD_FNIXiJo
