pwd    : muestra la ruta en donde estamos trabajando
cd ..  : cambiar al directorio padre (anterior)
cd /   : root / es el directorio rais
ls     : muestra los elemento que existen en el directorio
cd mnt : acceder a windows
cd c   : acceder a disco local c
cd     : sin parametros vamos a la carpeta home
cd Users/coreg/Desktop  --> navegar al escritorio de mi usuarion en windows

cd ~   : acceder directamente el directorio /home/aron en linux

#Se debe crear el directorio de trabajo dentro de linux, es la mejor practica profesional al trabajar con linux WSL.

mv "archivo o carpeta a mover" "destino" : es para mover archivos o carpetas a otra direccion

rm nombrearchivo.extencion : borrar archivo
rm -d nombredirectorioVacio:borrar directorio vasio
rm -rf nombredirectorio : borrar directorio con contenido


#instalar un programa: anaconda

wget -O "identificadorName" linkInstalador 
bash identificadorName   //extrae los archivos del instalador
#aceptar aceptar siguiente
source ~/.bashrc //reload the shell
conda init //run anaconada
conda info // info
jupyter-notebook --> copiar link (host)
code . // inicia VSCode en esta carpeta (el punto)

https://evancalz.medium.com/setting-up-neovim-on-wsl2-bf634cac435f


touch nombre_archivo.extencion //crear archivos en linux
    ejemplo: touch comandos.txt


https://catlinux.es/descargar-archivos-de-repositorio-github/   


ls -l //lectura completa de archivos
ls -lh //lectura humana