# alexa-115
Test to create an alexa skill for the 115 dataset

Lets go!


{
    "interactionModel": {
        "languageModel": {
            "invocationName": "amtsuche",
            "intents": [
                {
                    "name": "AMAZON.FallbackIntent",
                    "samples": []
                },
                {
                    "name": "AMAZON.CancelIntent",
                    "samples": []
                },
                {
                    "name": "AMAZON.HelpIntent",
                    "samples": []
                },
                {
                    "name": "AMAZON.StopIntent",
                    "samples": []
                },
                {
                    "name": "AMAZON.NavigateHomeIntent",
                    "samples": []
                },
                {
                    "name": "Perso",
                    "slots": [
                        {
                            "name": "Bezirksamt",
                            "type": "Aemter"
                        }
                    ],
                    "samples": [
                        "Wo kann ich einen {Bezirksamt} beantragen",
                        "Sag mir in welchem Amt ich einen {Bezirksamt} beantragen kann."
                    ]
                }
            ],
            "types": [
                {
                    "name": "Aemter",
                    "values": [
                        {
                            "name": {
                                "value": "KFZ Zulassungsstelle"
                            }
                        },
                        {
                            "name": {
                                "value": "Bezirksamt"
                            }
                        }
                    ]
                }
            ]
        }
    }
}
