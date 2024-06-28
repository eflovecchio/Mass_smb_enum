# Mass_smb_enum
El escaner de python lo que hace es iterar por una lista de IP's del cual te va a indicar con varios output cuales shares se pueden loguear con user Null y anonymous, tambien te da un output sobre toda la iteracion de archivos y carpetas del cual el share tiene permisos para visualizar, esto sirve para poder barrer de manera automatica una red.

La ejecución se hace de la siguiente manera:

pyrhon3 mass_smb_scan.py ./lista_ip.txt

