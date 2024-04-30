{
    "id": "F28D9CAB-4B86-4A6F-A9A5-2A3445C74FD8",
    "information": {
        "name": "Mafia",
        "description": "A deck containing roles for playing the Mafia party game"
    },
    "roles": [
        {
            "id": "8C3A275E-B2E2-402A-84ED-1765B2F4A6D1",
            "name": "Mafia",
            "description": "Mafia kills one player at night. Tries to kill all red players",
            "imageName": ""
        },
        {
            "id": "84F1A9BC-837C-4E77-AD59-4656D293D191",
            "name": "Sheriff",
            "description": "A role who investigates the identity of other players to find the Mafia members.",
            "imageName": ""
        },
        {
            "id": "3814D6B3-82A2-46DF-9D6E-6C0D6CA59471",
            "name": "Doctor",
            "description": "A role who can heal other players to protect them from being eliminated by the Mafia.",
            "imageName": ""
        },
        {
            "id": "3814D6B3-82A2-46DF-9D6E-6C0D6CA59472",
            "name": "Civilian",
            "description": "Tries to remove all black players from game",
            "imageName": ""
        },
        {
            "id": "3814D6B3-82A2-46DF-9D6E-6C0D6CA59473",
            "name": "Don",
            "description": "Can check one player at night if he is a Sheriff",
            "imageName": ""
        }
    ],
    "patterns": [
        {
            "id": "1A74E8A9-47E7-42F4-92FD-4A3F00E75012",
            "name": "Classic Mafia",
            "content": [
                {
                    "id": "0FAACB17-2C7A-4D3C-BF4D-5EAE9A5649A1",
                    "role": {
                        "id": "8C3A275E-B2E2-402A-84ED-1765B2F4A6D1",
                        "name": "Mafia",
                        "description": "Mafia kills one player at night. Tries to kill all red players",
                        "imageName": ""
                    },
                    "count": 2
                },
                {
                    "id": "0FAACB17-2C7A-4D3C-BF4D-5EAE9A5649A2",
                    "role": {
                        "id": "84F1A9BC-837C-4E77-AD59-4656D293D191",
                        "name": "Sheriff",
                        "description": "A role who investigates the identity of other players to find the Mafia members.",
                        "imageName": ""
                    },
                    "count": 1
                },
                {
                    "id": "0FAACB17-2C7A-4D3C-BF4D-5EAE9A5649A3",
                    "role": {
                        "id": "3814D6B3-82A2-46DF-9D6E-6C0D6CA59472",
                        "name": "Doctor",
                        "description": "A role who can heal other players to protect them from being eliminated by the Mafia.",
                        "imageName": ""
                    },
                    "count": 0
                },
                {
                    "id": "0FAACB17-2C7A-4D3C-BF4D-5EAE9A5649A4",
                    "role": {
                        "id": "3814D6B3-82A2-46DF-9D6E-6C0D6CA59471",
                        "name": "Civilian",
                        "description": "Tries to remove all black players from game",
                        "imageName": ""
                    },
                    "count": 6
                },
                {
                    "id": "0FAACB17-2C7A-4D3C-BF4D-5EAE9A5649A5",
                    "role": {
                        "id": "3814D6B3-82A2-46DF-9D6E-6C0D6CA59473",
                        "name": "Don",
                        "description": "Can check one player at night if he is a Sheriff",
                        "imageName": ""
                    },
                    "count": 1
                }
            ]
        }
    ],
    "appearance": {
        "iconName": "",
        "skinName": "leather_texture_skin"
    }
}
