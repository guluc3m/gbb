# Zoe Agent Index

El gestor de agentes de Zoe (o
*[zam](https://github.com/rmed/zoe_agent_manager)*) permite instalar agentes en
tiempo de ejecución de forma automática. Actualmente, utiliza direcciones de
**repositorios de git** tales como
`https://github.com/rmed/zoe_agent_manager.git`.

Usar repositorios git directamente permite a los desarrolladores publicar
actualizaciones de sus agentes de manera rápida. Sin embargo, esto ocasiona que
el resto de usuarios tengan que conocer de antemano dónde se aloja el código
del agente.

## Información del proyecto

La idea principal sería tener un portal online donde los desarrolladores
pudieran indicar la dirección de sus repositorios git y tener así un índice
centralizado de los agentes. Únicamente sería necesario indicar:

- Nombre del agente
- Correo del desarrollador
- Dirección del repositorio

De esta manera, los desarrolladores seguirían pudiendo actualizar sus agentes
de manera independiente.

Dicha idea está inspirada en sitios como [PyPI](https://pypi.python.org/pypi).

Si se incluyera **una API**, el gestor de agentes podría acceder al listado de
la plataforma para buscar un agente específico, de manera que el usuario final
no tuviera que conocer la dirección del repositorio.
