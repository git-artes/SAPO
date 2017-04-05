**Para instalar el JDK de JAI**
 - me tira el siguiente error: 
  tail: cannot open '+122' for reading: No such file or directory.  

 - Hubo que cambiar el .bin usando el siguiente comando: 
  sed s/+122/-n+122/ jai-1_1_2_01-lib-linux-i586-jdk.bin > jai-1_1_2_01-lib-linux-i586-jdk-fixed.bin   

 - Ahora tira el siguiente error: 
  This is not a proper JDK directory.  Exiting install.

 - Había que correrlo desde el directorio /usr/lib/jvm/java-8-openjdk-amd64, pero sigue tirando el mismo error. 

 - Por ahora generé el directorio i386 en /usr/lib/jvm/java-8-openjdk-amd64/jre/lib. Veremos, pero puso algo en ese directorio que no sé si lo verá el java. 

**Para instalar el JRE de JAI**
 - Lo mismo que para el JDK. 
 - NO HACE FALTA INSTALARLO. 

