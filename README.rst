.. -*- coding: utf-8 -*-

=================================================
Manual del curso "Edición de contenidos en Plone"
=================================================

Repositorio de manuales y recursos del curso "Edición de
contenidos en Plone" realizado por Covantec R.L.

.. contents :: :local:

Estructura general
===================

La estructura general de contenidos esta confirmada por los principales archivos:

**00-capacitacion_edicion_contenidos_plone.pdf**
  Describe el contenido de la capacitación.

**01-brochure_plone.pdf**
  Describe los contenidos del módulo *2* de la capacitación.

**02-manual_plone4.pdf**
  Describe los contenidos de los módulos *1, 3, 4, 5, 6* de la capacitación. Además
  de otros temas complementarios de Plone.


Obtener la documentación
=========================

El almacenamiento de este material está disponible en un repositorio Git 
en Bitbucket.org "`entrenamiento.edicion_contenido_plone`_". Si usted tiene una
credenciales en este servidor y desea convertirse en un colaborador ejecute 
el siguiente comando: ::

  $ git clone https://bitbucket.org/covantec/entrenamiento.edicion_contenido_plone.git


..
  Obtener y compilar la documentación
  ===================================
  
  El almacenamiento de este material está disponible en un repositorio Git 
  en Bitbucket.org "`entrenamiento.edicion_contenido_plone`_". Si usted tiene una
  credenciales en este servidor y desea convertirse en un colaborador ejecute 
  el siguiente comando: ::

    $ git clone https://bitbucket.org/covantec/entrenamiento.edicion_contenido_plone.git

  Crear entorno virtual de Python para reconstruir este proyecto: ::
  
    # aptitude install python-setuptools git-core
    # easy_install virtualenv
    $ cd $HOME ; mkdir $HOME/virtualenv ; cd $HOME/virtualenv
    $ virtualenv --python=/usr/bin/python sphinx
    $ source virtualenv/sphinx/bin/activate
  
  Instale Sphinx: ::
  
    (sphinx)$ easy_install Sphinx
    
  Ahora puede generar la documentación en PDF de los módulos *1, 3, 4, 5, 6*; ejecute los siguientes comandos: ::

    (sphinx)$ cd entrenamiento.edicion_contenido_plone/02-manual-usuario-plone
    (sphinx)$ make latexpdf
  
  Ahora se puede abrir ``build/latex/ManualUsuarioPlone4.pdf`` 
  con sus programas de visor de PDF favorito (Evince, Acrobat Reader, ...)
  
¿Tiene alguna idea?, ¿Encontró un error? Por favor, hágalo saber registrando un `ticket de soporte`_.

.. _entrenamiento.edicion_contenido_plone: https://bitbucket.org/covantec/entrenamiento.edicion_contenido_plone
.. _ticket de soporte: https://bitbucket.org/covantec/entrenamiento.edicion_contenido_plone/issues/new
