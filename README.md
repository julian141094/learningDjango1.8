Para ejecutar este ejercicio debe realizar los siguientes pasos:
===========================================================

1-) Instalar el controlador de versiones git:
------------------------------------------------------
    
    Ingresar como super usuario:

    $ su

    # aptitude install git
    
    Salir del modo super usuario


2-) Descargar el codigo fuente del proyecto CME_V2 :
-------------------------------------------------------------------------------------------------

    Para descargar el código fuente del proyecto contenido en su repositorio GIT realice un clon del proyecto CME_V2:

    $ git clone https://github.com/julian141094/learningDjango1.8.git django18

3-) Crear un Ambiente Virtual:
---------------------------------------

    El proyecto está desarrollado con el lenguaje de programación Python, debe instalar previamente. Con los siguientes comandos puede instalar Python y PIP.

    Entrar como root o super usaurio para la instalacion 

    # aptitude install python3.4 python3-pip python3.4-dev python3-setuptools

    # aptitude install python3-virtualenv virtualenvwrapper

    Salir del modo root y crear el ambiente:

    $ virtualenv .

    Posteriormente debe iniciar el ambiente virtual creado

    $ source bin/activate

4-) Instalar los requerimientos del proyecto:
---------------------------------------------------------

    Debe instalar los requerimientos con el siguiente comando

    