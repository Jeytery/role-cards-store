{
  "packageId": "MAFIA_PACKAGE",
  "available_app_version": "from_5.1",
  "information": {
    "name": "Mafia",
    "description": "Una baraja que contiene roles para jugar al juego de fiesta Mafia"
  },
  "appearance": {
    "iconName": "",
    "skinName": "leather_texture_skin"
  },
  "cards": [
    {
      "name": "Mafia",
      "description": "La mafia mata a un jugador por la noche. Intenta matar a todos los jugadores rojos"
    },
    {
      "name": "Sheriff",
      "description": "Un rol que investiga la identidad de otros jugadores para encontrar a los miembros de la Mafia."
    },
    {
      "name": "Doctor",
      "description": "Un rol que puede curar a otros jugadores para protegerlos de ser eliminados por la Mafia."
    },
    {
      "name": "Civil",
      "description": "Intenta eliminar a todos los jugadores negros del juego"
    },
    {
      "name": "Don",
      "description": "Puede verificar a un jugador por la noche para ver si es un Sheriff"
    }
  ],
  "decks": [
    {
      "name": "Mafia Clásica",
      "content": [
        {
          "roleName": "Mafia",
          "count": 2
        },
        {
          "roleName": "Don",
          "count": 1
        },
        {
          "roleName": "Civil",
          "count": 6
        },
        {
          "roleName": "Sheriff",
          "count": 1
        },
        {
          "roleName": "Doctor",
          "count": 0
        }
      ]
    }
  ]
}
