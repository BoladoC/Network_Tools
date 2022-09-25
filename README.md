# Network_Tools
Herramientas que puedes utilizar para el analisis de redes 

Modo de ejecución:
  (Por el momento solo lo he probado en ordenadores dentro de la red de mi laboratorio)
  En la máquina objetivo:
    >> python3 Netcat.py -t @IP_Target -p @Puerto_Ataque -l (Queremos ponerlo en modo listen) -c (Queremos ejecutarle comandos como revershell)
    Quedamos a la espera de ver que aparece en nuestra terminal

  En la máquia atacante:
    >> Python3 Netcat.py -t @IP_Target -p @Puerto_Aaque 
    Una vez ejecutado el programa queda a la espera de ordenes
    >> CTRL-D
    >> (Nos dará el mensaje de bienvenida que haya programado y estamos dentro, momento del ataque)
  
![imagen](https://user-images.githubusercontent.com/96150730/192136680-d46a9789-90aa-44e8-96dc-dbdec424f30a.png)
 En la imagen se muetra como me conecto desde Netcat (el original) para que se vea que da igual la manera de conectarse.
