{
    "packageId": "MAFIA_PACKAGE",
    "information": {
        "name": "Mafia",
        "description": "A deck containing roles for playing the Mafia party game"
    },
    "appearance": {
        "iconName": "",
        "skinName": "leather_texture_skin"
    },
    "cards": [
        {
            "name": "Mafia",
            "description": "Mafia kills one player at night. Tries to kill all red players"
        },
        {
            "name": "Sheriff",
            "description": "A role who investigates the identity of other players to find the Mafia members."
        },
        {
            "name": "Doctor",
            "description": "A role who can heal other players to protect them from being eliminated by the Mafia."
        },
        {
            "name": "Civilian",
            "description": "Tries to remove all black players from game"
        },
        {
            "name": "Don",
            "description": "Can check one player at night if he is a Sheriff"
        }
    ],
    "decks": [
        {
            "name": "Classical Mafia",
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
                    "roleName": "Civillian",
                    "count": 0
                },
                {
                    "roleName": "Sheriff",
                    "count": 6
                },
                {
                    "roleName": "Doctor",
                    "count": 1
                }
            ]
        }
    ]
}
