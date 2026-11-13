# IA Básica Grafos - Manuel Dono Araújo

Este documento describe os cambios realizados ao proxecto.

A partir da escea de TankWaypoints: 

- Fixen un novo nodo detrás das rocas, na parte superior do mapa.
- Para isto, engadin un novo nodo no array de Waypoints, modifiquei o WPManager para engadir novos enlaces bidireccionais cos puntos 04, 07 e 03.
- Logo, modifiquei o script de TanksWaypointsFollow para unha nova función chamada "GoToBack", cambiando o id do waypoint a 8.
- Finalmente, engadin un novo botón chamado Go To Back, que chama ao metodo anteriormente mencionado.