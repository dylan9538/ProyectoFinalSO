# Proyecto final Sistemas Operativos

### Integrantes

Estudiante | Código
--- | --- | ---
Bryan Estiben Pérez Parra | 12203030
Dylan Torres | 12103021

**URL REPOSITORIO**

https://github.com/dylan9538/ProyectoFinalSO

**NOTA: LA INSTALACIÓN DE DEPENDENCIAS ESTA DISTRIBUIDAD DE ACUERDO AL PASO QUE SE ESTE REALIZANDO, YA SEA CONNFIGURACIÓN DE PUERTOS, CREACIÓN DE AMBIENTE VIRTUAL, ETC...**

# Modulo 0 -  Prerrequisitos
Se requiere el software de virtualización para arquitecturas x86/amd64 'Oracle VM VirtualBox'. En este tutorial se asume que ya el lector lo ha instalado con anterioridad, dentro de su equipo.

![alt tag](https://github.com/dylan9538/ProyectoFinalSO/blob/master/VirtualBox.png  "Icono Virtual Box")

**Se descarga el iso necesario para el proyecto**

1. Dirigirse a la página oficial de centOS. Hacer clic en el link, a continuación:

https://www.centos.org/download/

2. Hacer clic en el botón que dice "Minimal ISO", no es necesario, para el alcance de este proyecto descargar la versión completa.

3. Una vez ubicado dentro de la página web, hacer clic en alguno de los URL's disponibles para la descarga de archivo .iso de Centos. Para nuestro caso de ejemplo, se descargó la imagen desde el sgte link:
http://centos.uniminuto.edu/7/isos/x86_64/CentOS-7-x86_64-Minimal-1511.iso

**Nota: Se recomienda el uso de software como "MD5" para verificar que los datos fueron correctamente descargados y la información no está dañada**

# Módulo 1 - Configuración de la Virtual Machine

Iniciar el software 'virtualBox' y crear una nueva maquina virtual y configurarla. A continuación se describen los pasos de la configuración por imagenes brevemente:

**Se crea una máquina virtual:**

![alt tag](https://github.com/dylan9538/ProyectoFinalSO/blob/master/ConfigurationVirtualMachine/1.png)

**Luego se añade la siguiente configuración durante la creación:**

![alt tag](https://github.com/dylan9538/ProyectoFinalSO/blob/master/ConfigurationVirtualMachine/2.PNG)

**Configuraciones en en memoria y disco duro**

![alt tag](https://github.com/dylan9538/ProyectoFinalSO/blob/master/ConfigurationVirtualMachine/3.PNG)

![alt tag](https://github.com/dylan9538/ProyectoFinalSO/blob/master/ConfigurationVirtualMachine/4.PNG)

![alt tag](https://github.com/dylan9538/ProyectoFinalSO/blob/master/ConfigurationVirtualMachine/5.PNG)

![alt tag](https://github.com/dylan9538/ProyectoFinalSO/blob/master/ConfigurationVirtualMachine/6.PNG)

![alt tag](https://github.com/dylan9538/ProyectoFinalSO/blob/master/ConfigurationVirtualMachine/7.PNG)

**Se crea:**

![alt tag](https://github.com/dylan9538/ProyectoFinalSO/blob/master/ConfigurationVirtualMachine/8.PNG)

**SE PROCEDE A CONFIGURARLA**

**Orden, arranque y características extendidas:**

![alt tag](https://github.com/dylan9538/ProyectoFinalSO/blob/master/ConfigurationVirtualMachine/9.PNG)

Almacenamiento:

![alt tag](https://github.com/dylan9538/ProyectoFinalSO/blob/master/ConfigurationVirtualMachine/10.PNG)

**SE CONFIGURAN LAS INTERFACES DE RED**

**RED NAT** 

![alt tag](https://github.com/dylan9538/ProyectoFinalSO/blob/master/ConfigurationVirtualMachine/11.PNG)

**RED puente**

![alt tag](https://github.com/dylan9538/ProyectoFinalSO/blob/master/ConfigurationVirtualMachine/12.PNG)

PARA FINALIZAR INICIAMOS LA MÁQUINA VIRTUAL Y CONTINUAMOS CON EL MÓDULO 2

![alt tag](https://github.com/dylan9538/ProyectoFinalSO/blob/master/ConfigurationVirtualMachine/13.PNG)


# Módulo 2 - Configuración de Centos 7

Luego de configurar la máquina virtual, se realiza la configuración de centos 7. Acontinuación se muestran los pasos de la configuración por medio de imágenes: 

**Selección del idioma**

![alt tag](https://github.com/dylan9538/ProyectoFinalSO/blob/master/ConfigurationCentos7/1.PNG)

**Selección de la hora**

![alt tag](https://github.com/dylan9538/ProyectoFinalSO/blob/master/ConfigurationCentos7/2.PNG)


**Teclado**

![alt tag](https://github.com/dylan9538/ProyectoFinalSO/blob/master/ConfigurationCentos7/3.PNG)


**Seguridad**

![alt tag](https://github.com/dylan9538/ProyectoFinalSO/blob/master/ConfigurationCentos7/4.PNG)


**Software**

![alt tag](https://github.com/dylan9538/ProyectoFinalSO/blob/master/ConfigurationCentos7/5.PNG)


**Fuente de instalación**

![alt tag](https://github.com/dylan9538/ProyectoFinalSO/blob/master/ConfigurationCentos7/6.PNG)

**Destino instalación**

![alt tag](https://github.com/dylan9538/ProyectoFinalSO/blob/master/ConfigurationCentos7/7.PNG)

**Comenzar instalación**

![alt tag](https://github.com/dylan9538/ProyectoFinalSO/blob/master/ConfigurationCentos7/8.PNG)

**SE CONFIGURA (CREAR) LA CONTRASEÑA Y USUARIOS**

![alt tag](https://github.com/dylan9538/ProyectoFinalSO/blob/master/ConfigurationCentos7/9.PNG)

**Password para root**

![alt tag](https://github.com/dylan9538/ProyectoFinalSO/blob/master/ConfigurationCentos7/10.PNG)

**User**

![alt tag](https://github.com/dylan9538/ProyectoFinalSO/blob/master/ConfigurationCentos7/11.PNG)

![alt tag](https://github.com/dylan9538/ProyectoFinalSO/blob/master/ConfigurationCentos7/12.PNG)

**Luego de la configuración se reinicia, selecciona centos y se inicia sesión**

![alt tag](https://github.com/dylan9538/ProyectoFinalSO/blob/master/ConfigurationCentos7/13.PNG)

![alt tag](https://github.com/dylan9538/ProyectoFinalSO/blob/master/ConfigurationCentos7/14.PNG)

![alt tag](https://github.com/dylan9538/ProyectoFinalSO/blob/master/ConfigurationCentos7/15.PNG)


# Módulo 3 - Configuracion de interfaces

**Cabe recalcar que en la configuración de la maquina virtual de configuraron la RED NAT Y RED PUENTE!.**

**Consulta nombre de interfaces**

![alt tag](https://github.com/dylan9538/ProyectoFinalSO/blob/master/InterfacesDeRed/1i.PNG)

**Subir interfaces**

![alt tag](https://github.com/dylan9538/ProyectoFinalSO/blob/master/InterfacesDeRed/2i.PNG)

**Verificar que quedaron arriba**

![alt tag](https://github.com/dylan9538/ProyectoFinalSO/blob/master/InterfacesDeRed/3i.PNG)

# Módulo 4 - Configuración de puertos

Para la configuración de puertos es posible instalar dos dependencias (El paquete firewalld que remplaza a iptables) y el paquete services.

En RHEL / CentOS 7 y Fedora 21 la interfaz de iptables está siendo reemplazada por firewalld.

Se recomienda comenzar a usar Firewalld en lugar de iptables ya que esto puede interrumpir en el futuro. Sin embargo, iptables todavía es compatible y se puede instalar con el comando YUM. No podemos mantener Firewalld e iptables en el mismo sistema, ya que puede provocar conflictos.

**Acontinuación tenemos los pasos de INSTALACIÓN DE DEPENDENCIA FIREWALLD**

**Descarga**

![alt tag](https://github.com/dylan9538/ProyectoFinalSO/blob/master/ConfiguracionPuertos/1.png)

**Instalación**

![alt tag](https://github.com/dylan9538/ProyectoFinalSO/blob/master/ConfiguracionPuertos/2.PNG)

**Prueba instalación**

![alt tag](https://github.com/dylan9538/ProyectoFinalSO/blob/master/ConfiguracionPuertos/3.PNG)

**Como en el proyecto se usará iptables, desactivamos y enmascaramos firewalld.**

![alt tag](https://github.com/dylan9538/ProyectoFinalSO/blob/master/ConfiguracionPuertos/4.PNG)

**Luego continuamos con la INSTALACIÓN DE DEPENDENCIA IPTABLES**

Se requiqere ejecutar el siguiente comando, para habilitar el archivo iptables.
Si no, no aparece dentro del etc/sysconfig:
```
yum install iptables-services
```

**Descarga**

![alt tag](https://github.com/dylan9538/ProyectoFinalSO/blob/master/ConfiguracionPuertos/5.PNG)

**CONFIGURACIÓN DE PUERTOS**

![alt tag](https://github.com/dylan9538/ProyectoFinalSO/blob/master/ConfiguracionPuertos/6.PNG)

**Reinicio**

![alt tag](https://github.com/dylan9538/ProyectoFinalSO/blob/master/ConfiguracionPuertos/7.PNG)

# Módulo 5 - Configuraciones para despliegue de la aplicación

**Clono el repositorio que necesito**
En este repositorio añadiremos los archivos que se manejen.
```
mkdir repositories
cd repositories
git clone https://github.com/dylan9538/ProyectoFinalSO
cd ProyectoFinalSO

git config remote.origin.url "https://token@github.com/dylan9538/ProyectoFinalSO.git"
```
En el campo token añado el token generado en github.

**Creo un directorio y el ambiente**
```
cd ~/
$ mkdir ambientes
$ cd ambientes
$ virtualenv ambienteFinal
```
Lo activo:
```
cd ~/ambiente
. ambienteFinal/bin/activate
```
**SE INSTALA FLASK EN EL AMBIENTE**
```
Pip install Flask
```

**Creo un directorio para el ejercicio dentro del repositorio clonado**
```
$ cd ~/
$ mkdir -p ejercicios/ejercicioPy
$ cd ejercicios/ejercicioPy
```

**Creo el archivo comandos.py que contiene el siguiente código**
```
from subprocess import Popen, PIPE
import glob
import os

def darTodosArchivos():
  listaArchivos = Popen(["ls"], stdout=PIPE, stderr=PIPE)
  miLista = Popen(["awk",'-F',':','{print $1}'], stdin=listaArchivos.stdout, stdout=PIPE, stderr=PIPE).communicate()[0].split('\n')
  return filter(None,miLista)


def agregarArchivo(nombre,contenido):
  arc = open(nombre+'.txt','a')
  arc.write(contenido+'\n')
  arc.close()
  return "Archivo generado!",201


def borrarArchivo(nombre):
  intocables = ["comandos.py","URI.py","miAmbiente","README.md"]
  if nombre in intocables:
    return True
  else:
    rp = Popen(["rm",nombre], stdout=PIPE, stderr=PIPE)
    rp.wait()
    return False if nombre in darTodosArchivos() else True

def darRecientes():
  files = darTodosArchivos()
  files.sort(key=lambda x: os.path.getmtime(x), reverse=True)
  files = [str(x) for x in files]
  return "Archivos del Mas Reciente al Mas Antiguo- ", filter(None,files)

 ```
**Creo el archivo URI.py que maneje los procesos de comandos.py y que contenga las URIS. El siguiente es el código:**
```
from flask import Flask, abort, request
import json
from comandos import darTodosArchivos, borrarArchivo, agregarArchivo, darRecientes

app = Flask(__name__)

@app.route('/files',methods=['POST'])
def crearArchivo():
  datos = request.get_json(silent=True)
  nombre = datos['filename']
  contenido = datos['content']
  agregarArchivo(nombre,contenido)
  return "el archivo ha sido creado",201

@app.route('/files',methods=['GET'])
def darArchivos():
  list = {}
  list["Documentos:"] = darTodosArchivos()
  return json.dumps(list), 202

@app.route('/files',methods=['PUT'])
def errorSolicitud():
  abort(404)

@app.route('/files',methods=['DELETE'])
def eliminarArchivos():
  error = False
  for docActual in darTodosArchivos():
    if not borrarArchivo(docActual):
        error = True

  if error:
    return 'Algunos documentos no fueron eliminados!', 400
  else:
    return 'Carpeta Reseteada!', 200 


@app.route('/files/recently_created',methods=['POST'])
def errorPost():
  abort(404)

@app.route('/files/recently_created',methods=['GET'])
def darRecientesL():
  return darRecientes()

@app.route('/files/recently_created',methods=['PUT'])
def errorPut():
  abort(404)

@app.route('/files/recently_created',methods=['DELETE'])
def errorDelete():
  abort(404)


if __name__ == "__main__":
  app.run(host='0.0.0.0',port=8081,debug='True')
```


**A CONTINUACIÓN DE PRESENTAN PRUEBAS DE LA CREACIÓN DEL AMBIENTE Y DE LA INSTALACIÓN (DEPENDENCIAS) DE FLASK, WGET, VIRTUALENV Y PIP**

**Instalación del wget**

![alt tag](https://github.com/dylan9538/ProyectoFinalSO/blob/master/Ambiente-virtual/0.PNG)

**Importación desde el repositorio booststrap**

![alt tag](https://github.com/dylan9538/ProyectoFinalSO/blob/master/Ambiente-virtual/1.PNG)

**Instalación de pip**

![alt tag](https://github.com/dylan9538/ProyectoFinalSO/blob/master/Ambiente-virtual/2.PNG)

**Creación y activación del ambiente**

![alt tag](https://github.com/dylan9538/ProyectoFinalSO/blob/master/Ambiente-virtual/3.PNG)

**Instalación de Flask dentro del ambiente**

![alt tag](https://github.com/dylan9538/ProyectoFinalSO/blob/master/Ambiente-virtual/4.PNG)

![alt tag](https://github.com/dylan9538/ProyectoFinalSO/blob/master/Ambiente-virtual/5.PNG)

**LUEGO SE VERIFICA QUE PYTHON ESTE INSTALADO**

**CORREMOS LA APLICACIÓN CON EL SIGUIENTE COMANDO**
```
Python URI.py
```

**Verificación**

![alt tag](https://github.com/dylan9538/ProyectoFinalSO/blob/master/Ambiente-virtual/6.PNG)

**Despliegue**

![alt tag](https://github.com/dylan9538/ProyectoFinalSO/blob/master/Ambiente-virtual/7.PNG)

# Módulo 6 - Netstat

Netstat (network statistics) es una herramienta de línea de comandos que muestra un listado de las conexiones activas de una computadora, tanto entrantes como salientes. Existen versiones de este comando en varios sistemas como Unix, GNU/Linux, Mac OS X, Windows y BeOS.

**Con netstat primero se realiza una prueba preliminar**

**Instalación**

![alt tag](https://github.com/dylan9538/ProyectoFinalSO/blob/master/netstat/1.PNG)

**Prueba preliminar**

![alt tag](https://github.com/dylan9538/ProyectoFinalSO/blob/master/netstat/2.PNG)


**Resultado prueba preliminar**

![alt tag](https://github.com/dylan9538/ProyectoFinalSO/blob/master/netstat/3.PNG)

**LUEGO DE ESTO, SE PROCEDE A PROBAR LA EJECUCIÓN DE LA APLICACIÓN DE PYTHON CON NETSTAT**

**Verificacion con netstat que la aplicación esta ejecutandose en el 8081**

![alt tag](https://github.com/dylan9538/ProyectoFinalSO/blob/master/netstat/4.png)

**Si no se despliega el programa, no aparece su puerto en netstat**

![alt tag](https://github.com/dylan9538/ProyectoFinalSO/blob/master/netstat/5.png)

**FIN**

##CUANDO QUIERA SUBIR ARCHIVOS AL GITHUB REPOSITORIO

**1)Creo el archivo si no existe.**

**2)Sigo los siguientes comandos:**

Estos comandos los ejecuto donde se encuentra ubicado el archivo a cargar.

```
git add nombreArchivo
git commit -m "upload README file"
git push origin master
```


