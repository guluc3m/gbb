# Zoe Agent Index

Portal online para tener una **lista centralizada de agentes de Zoe** y que
además disponga de una **API** sobre la cual poder crear servicios
o aplicaciones.

## Información sobre el proyecto

El gestor de agentes de Zoe permite instalar agentes en
tiempo de ejecución de forma automática. Actualmente, utiliza direcciones de
**repositorios de git** tales como
`https://github.com/rmed/zoe_agent_manager.git`.

Usar repositorios git directamente permite a los desarrolladores publicar
actualizaciones de sus agentes de manera rápida. Sin embargo, esto ocasiona que
el resto de usuarios tengan que conocer de antemano dónde se aloja el código
del agente.

La idea principal sería tener un portal donde los desarrolladores pudieran
indicar la dirección de sus repositorios git y tener así un índice centralizado
de los agentes. Únicamente sería necesario indicar:

- Nombre del agente
- Correo del desarrollador
- Dirección del repositorio

De esta manera, los desarrolladores seguirían pudiendo actualizar sus agentes
de manera independiente.

Al incluir **una API**, el gestor de agentes podría acceder al listado de la
plataforma para buscar un agente específico, de manera que el usuario final no
tuviera que conocer la dirección del repositorio.

## Referencias

- [PyPI](https://pypi.python.org/pypi): Índice de paquetes de Python
- [zam](https://github.com/rmed/zoe_agent_manager): Gestor de agentes de Zoe.
  Incluye documentación sobre el formato de los archivos que identifican un
  agente como "instalable"

## Recursos

## Equipo
