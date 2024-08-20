Control software
====

This directory contains the code for the control software which was developed by our team and is used by our vehicle in order to participate in the competition.

~*~

The software we used for our team's self-driving car is AIcode, the programming language for Nashenbot's AISTEAM. The attached code is the official one we used in order to make our car self-driving.

![image](https://github.com/user-attachments/assets/cdf6424a-fe02-47ce-b7ac-6e121371fb3a)
![image](https://github.com/user-attachments/assets/907feb2e-6ee1-45fb-b861-d8929e20f8a0)
![image](https://github.com/user-attachments/assets/d6828eee-1667-4384-b451-8a2da6814468)



{
    "functionList": {
    },
    "notes": {
        "note_0": {
            "text": "sequence of tests\n\n1st - 4th first try (if success proceed to) \n\n1st - 8th (if success proceed to)\n\n1st - 12th\n\nexit",
            "x": "5970",
            "y": "376"
        }
    },
    "top_0": {
        "item_0000000000": {
            "disabled": "0",
            "opcode": "",
            "x": "5000",
            "y": "1955"
        }
    },
    "top_1": {
        "item_0000000001": {
            "disabled": "0",
            "opcode": "control_wait",
            "param_1": {
                "opcode": "CGraphicsTextItem",
                "position": "1",
                "type": "10",
                "value": "2"
            },
            "x": "4426",
            "y": "1058"
        },
        "item_0000000002": {
            "disabled": "0",
            "opcode": "break",
            "x": "4426",
            "y": "1108"
        }
    },
    "top_2": {
        "item_0000000003": {
            "disabled": "0",
            "opcode": "control_wait",
            "param_1": {
                "opcode": "CGraphicsTextItem",
                "position": "1",
                "type": "10",
                "value": "4"
            },
            "x": "5983",
            "y": "1225"
        },
        "item_0000000004": {
            "disabled": "0",
            "noteItem": {
                "text": "ninth turn",
                "x": "6267.5",
                "y": "1306.35"
            },
            "opcode": "MakerSteerin_Analogy",
            "param_1": {
                "opcode": "CGraphicsTextItem",
                "position": "1",
                "type": "10",
                "value": "135"
            },
            "x": "5983",
            "y": "1275"
        },
        "item_0000000005": {
            "disabled": "0",
            "opcode": "control_wait",
            "param_1": {
                "opcode": "CGraphicsTextItem",
                "position": "1",
                "type": "10",
                "value": "1.5"
            },
            "x": "5983",
            "y": "1325"
        },
        "item_0000000006": {
            "disabled": "0",
            "opcode": "MakerSteerin_Analogy",
            "param_1": {
                "opcode": "CGraphicsTextItem",
                "position": "1",
                "type": "10",
                "value": "90"
            },
            "x": "5983",
            "y": "1375"
        },
        "item_0000000007": {
            "disabled": "0",
            "opcode": "control_wait",
            "param_1": {
                "opcode": "CGraphicsTextItem",
                "position": "1",
                "type": "10",
                "value": "4"
            },
            "x": "5983",
            "y": "1425"
        },
        "item_0000000008": {
            "disabled": "0",
            "noteItem": {
                "text": "tenth turn",
                "x": "6225.5",
                "y": "1502.35"
            },
            "opcode": "MakerSteerin_Analogy",
            "param_1": {
                "opcode": "CGraphicsTextItem",
                "position": "1",
                "type": "10",
                "value": "135"
            },
            "x": "5983",
            "y": "1475"
        },
        "item_0000000009": {
            "disabled": "0",
            "opcode": "control_wait",
            "param_1": {
                "opcode": "CGraphicsTextItem",
                "position": "1",
                "type": "10",
                "value": "1.5"
            },
            "x": "5983",
            "y": "1525"
        },
        "item_0000000010": {
            "disabled": "0",
            "opcode": "MakerSteerin_Analogy",
            "param_1": {
                "opcode": "CGraphicsTextItem",
                "position": "1",
                "type": "10",
                "value": "90"
            },
            "x": "5983",
            "y": "1575"
        },
        "item_0000000011": {
            "disabled": "0",
            "opcode": "control_wait",
            "param_1": {
                "opcode": "CGraphicsTextItem",
                "position": "1",
                "type": "10",
                "value": "4"
            },
            "x": "5983",
            "y": "1625"
        },
        "item_0000000012": {
            "disabled": "0",
            "noteItem": {
                "text": "eleventh turn",
                "x": "6247.5",
                "y": "1696.35"
            },
            "opcode": "MakerSteerin_Analogy",
            "param_1": {
                "opcode": "CGraphicsTextItem",
                "position": "1",
                "type": "10",
                "value": "135"
            },
            "x": "5983",
            "y": "1675"
        },
        "item_0000000013": {
            "disabled": "0",
            "opcode": "control_wait",
            "param_1": {
                "opcode": "CGraphicsTextItem",
                "position": "1",
                "type": "10",
                "value": "1.5"
            },
            "x": "5983",
            "y": "1725"
        },
        "item_0000000014": {
            "disabled": "0",
            "opcode": "MakerSteerin_Analogy",
            "param_1": {
                "opcode": "CGraphicsTextItem",
                "position": "1",
                "type": "10",
                "value": "90"
            },
            "x": "5983",
            "y": "1775"
        },
        "item_0000000015": {
            "disabled": "0",
            "opcode": "control_wait",
            "param_1": {
                "opcode": "CGraphicsTextItem",
                "position": "1",
                "type": "10",
                "value": "4"
            },
            "x": "5983",
            "y": "1825"
        },
        "item_0000000016": {
            "disabled": "0",
            "noteItem": {
                "text": "twelveth turn",
                "x": "6245.5",
                "y": "1896.35"
            },
            "opcode": "MakerSteerin_Analogy",
            "param_1": {
                "opcode": "CGraphicsTextItem",
                "position": "1",
                "type": "10",
                "value": "135"
            },
            "x": "5983",
            "y": "1875"
        },
        "item_0000000017": {
            "disabled": "0",
            "opcode": "control_wait",
            "param_1": {
                "opcode": "CGraphicsTextItem",
                "position": "1",
                "type": "10",
                "value": "1.5"
            },
            "x": "5983",
            "y": "1925"
        },
        "item_0000000018": {
            "disabled": "0",
            "opcode": "MakerSteerin_Analogy",
            "param_1": {
                "opcode": "CGraphicsTextItem",
                "position": "1",
                "type": "10",
                "value": "90"
            },
            "x": "5983",
            "y": "1975"
        },
        "item_0000000019": {
            "disabled": "0",
            "opcode": "control_wait",
            "param_1": {
                "opcode": "CGraphicsTextItem",
                "position": "1",
                "type": "10",
                "value": "4"
            },
            "x": "5983",
            "y": "2025"
        }
    },
    "top_3": {
        "item_0000000020": {
            "disabled": "0",
            "opcode": "MakerMotion_OpenLoop",
            "param_1": {
                "position": "1",
                "type": "11",
                "value": "1"
            },
            "param_3": {
                "opcode": "CGraphicsTextItem",
                "position": "3",
                "type": "10",
                "value": "50"
            },
            "x": "3866",
            "y": "249"
        },
        "item_0000000021": {
            "disabled": "0",
            "opcode": "MakerMotion_OpenLoop",
            "param_1": {
                "position": "1",
                "type": "11",
                "value": "1"
            },
            "param_3": {
                "opcode": "CGraphicsTextItem",
                "position": "3",
                "type": "10",
                "value": "50"
            },
            "x": "3866",
            "y": "299"
        },
        "item_0000000022": {
            "disabled": "0",
            "opcode": "smallmotion_setmotor",
            "param_1": {
                "position": "1",
                "type": "11",
                "value": "1"
            },
            "param_3": {
                "position": "3",
                "type": "11",
                "value": "3"
            },
            "param_5": {
                "opcode": "CGraphicsTextItem",
                "position": "5",
                "type": "10",
                "value": "-100"
            },
            "x": "3866",
            "y": "349"
        },
        "item_0000000023": {
            "disabled": "0",
            "opcode": "smallmotion_setmotor",
            "param_1": {
                "position": "1",
                "type": "11",
                "value": "1"
            },
            "param_3": {
                "position": "3",
                "type": "11",
                "value": "4"
            },
            "param_5": {
                "opcode": "CGraphicsTextItem",
                "position": "5",
                "type": "10",
                "value": "-100"
            },
            "x": "3866",
            "y": "399"
        },
        "item_0000000024": {
            "disabled": "0",
            "opcode": "MakerSteerin_Analogy",
            "param_1": {
                "opcode": "CGraphicsTextItem",
                "position": "1",
                "type": "10",
                "value": "0"
            },
            "x": "3866",
            "y": "449"
        },
        "item_0000000025": {
            "disabled": "0",
            "opcode": "control_wait",
            "param_1": {
                "opcode": "CGraphicsTextItem",
                "position": "1",
                "type": "10",
                "value": "4"
            },
            "x": "3866",
            "y": "499"
        },
        "item_0000000026": {
            "disabled": "0",
            "opcode": "MakerSteerin_Analogy",
            "param_1": {
                "opcode": "CGraphicsTextItem",
                "position": "1",
                "type": "10",
                "value": "50"
            },
            "x": "3866",
            "y": "549"
        },
        "item_0000000027": {
            "disabled": "0",
            "noteItem": {
                "text": "start ng pagliko nya",
                "x": "4158.33",
                "y": "590.333"
            },
            "opcode": "control_wait",
            "param_1": {
                "opcode": "CGraphicsTextItem",
                "position": "1",
                "type": "10",
                "value": "2"
            },
            "x": "3866",
            "y": "599"
        },
        "item_0000000028": {
            "disabled": "0",
            "opcode": "MakerSteerin_Analogy",
            "param_1": {
                "opcode": "CGraphicsTextItem",
                "position": "1",
                "type": "10",
                "value": "0"
            },
            "x": "3866",
            "y": "649"
        },
        "item_0000000029": {
            "disabled": "0",
            "opcode": "control_wait",
            "param_1": {
                "opcode": "CGraphicsTextItem",
                "position": "1",
                "type": "10",
                "value": "4.5"
            },
            "x": "3866",
            "y": "699"
        },
        "item_0000000030": {
            "disabled": "0",
            "opcode": "MakerSteerin_Analogy",
            "param_1": {
                "opcode": "CGraphicsTextItem",
                "position": "1",
                "type": "10",
                "value": "50"
            },
            "x": "3866",
            "y": "749"
        },
        "item_0000000031": {
            "disabled": "0",
            "opcode": "control_wait",
            "param_1": {
                "opcode": "CGraphicsTextItem",
                "position": "1",
                "type": "10",
                "value": "2.2"
            },
            "x": "3866",
            "y": "799"
        },
        "item_0000000032": {
            "disabled": "0",
            "opcode": "MakerSteerin_Analogy",
            "param_1": {
                "opcode": "CGraphicsTextItem",
                "position": "1",
                "type": "10",
                "value": "0"
            },
            "x": "3866",
            "y": "849"
        },
        "item_0000000033": {
            "disabled": "0",
            "opcode": "control_wait",
            "param_1": {
                "opcode": "CGraphicsTextItem",
                "position": "1",
                "type": "10",
                "value": "4"
            },
            "x": "3866",
            "y": "899"
        },
        "item_0000000034": {
            "disabled": "0",
            "opcode": "MakerSteerin_Analogy",
            "param_1": {
                "opcode": "CGraphicsTextItem",
                "position": "1",
                "type": "10",
                "value": "50"
            },
            "x": "3866",
            "y": "949"
        },
        "item_0000000035": {
            "disabled": "0",
            "opcode": "control_wait",
            "param_1": {
                "opcode": "CGraphicsTextItem",
                "position": "1",
                "type": "10",
                "value": "2"
            },
            "x": "3866",
            "y": "999"
        },
        "item_0000000036": {
            "disabled": "0",
            "opcode": "MakerSteerin_Analogy",
            "param_1": {
                "opcode": "CGraphicsTextItem",
                "position": "1",
                "type": "10",
                "value": "0"
            },
            "x": "3866",
            "y": "1049"
        },
        "item_0000000037": {
            "disabled": "0",
            "opcode": "control_wait",
            "param_1": {
                "opcode": "CGraphicsTextItem",
                "position": "1",
                "type": "10",
                "value": "4.5"
            },
            "x": "3866",
            "y": "1099"
        },
        "item_0000000038": {
            "disabled": "0",
            "opcode": "MakerSteerin_Analogy",
            "param_1": {
                "opcode": "CGraphicsTextItem",
                "position": "1",
                "type": "10",
                "value": "50"
            },
            "x": "3866",
            "y": "1149"
        },
        "item_0000000039": {
            "disabled": "0",
            "opcode": "control_wait",
            "param_1": {
                "opcode": "CGraphicsTextItem",
                "position": "1",
                "type": "10",
                "value": "2.3"
            },
            "x": "3866",
            "y": "1199"
        },
        "item_0000000040": {
            "disabled": "0",
            "opcode": "MakerSteerin_Analogy",
            "param_1": {
                "opcode": "CGraphicsTextItem",
                "position": "1",
                "type": "10",
                "value": "0"
            },
            "x": "3866",
            "y": "1249"
        },
        "item_0000000041": {
            "disabled": "0",
            "opcode": "control_wait",
            "param_1": {
                "opcode": "CGraphicsTextItem",
                "position": "1",
                "type": "10",
                "value": "4"
            },
            "x": "3866",
            "y": "1299"
        },
        "item_0000000042": {
            "disabled": "0",
            "opcode": "MakerSteerin_Analogy",
            "param_1": {
                "opcode": "CGraphicsTextItem",
                "position": "1",
                "type": "10",
                "value": "50"
            },
            "x": "3866",
            "y": "1349"
        },
        "item_0000000043": {
            "disabled": "0",
            "opcode": "control_wait",
            "param_1": {
                "opcode": "CGraphicsTextItem",
                "position": "1",
                "type": "10",
                "value": "2.1"
            },
            "x": "3866",
            "y": "1399"
        },
        "item_0000000044": {
            "disabled": "0",
            "opcode": "MakerSteerin_Analogy",
            "param_1": {
                "opcode": "CGraphicsTextItem",
                "position": "1",
                "type": "10",
                "value": "0"
            },
            "x": "3866",
            "y": "1449"
        },
        "item_0000000045": {
            "disabled": "0",
            "opcode": "control_wait",
            "param_1": {
                "opcode": "CGraphicsTextItem",
                "position": "1",
                "type": "10",
                "value": "4.2"
            },
            "x": "3866",
            "y": "1499"
        },
        "item_0000000046": {
            "disabled": "0",
            "opcode": "MakerSteerin_Analogy",
            "param_1": {
                "opcode": "CGraphicsTextItem",
                "position": "1",
                "type": "10",
                "value": "50"
            },
            "x": "3866",
            "y": "1549"
        },
        "item_0000000047": {
            "disabled": "0",
            "opcode": "control_wait",
            "param_1": {
                "opcode": "CGraphicsTextItem",
                "position": "1",
                "type": "10",
                "value": "2.2"
            },
            "x": "3866",
            "y": "1599"
        },
        "item_0000000048": {
            "disabled": "0",
            "opcode": "MakerSteerin_Analogy",
            "param_1": {
                "opcode": "CGraphicsTextItem",
                "position": "1",
                "type": "10",
                "value": "0"
            },
            "x": "3866",
            "y": "1649"
        },
        "item_0000000049": {
            "disabled": "0",
            "opcode": "control_wait",
            "param_1": {
                "opcode": "CGraphicsTextItem",
                "position": "1",
                "type": "10",
                "value": "4"
            },
            "x": "3866",
            "y": "1699"
        },
        "item_0000000050": {
            "disabled": "0",
            "opcode": "MakerSteerin_Analogy",
            "param_1": {
                "opcode": "CGraphicsTextItem",
                "position": "1",
                "type": "10",
                "value": "50"
            },
            "x": "3866",
            "y": "1749"
        },
        "item_0000000051": {
            "disabled": "0",
            "opcode": "control_wait",
            "param_1": {
                "opcode": "CGraphicsTextItem",
                "position": "1",
                "type": "10",
                "value": "2"
            },
            "x": "3866",
            "y": "1799"
        },
        "item_0000000052": {
            "disabled": "0",
            "opcode": "MakerSteerin_Analogy",
            "param_1": {
                "opcode": "CGraphicsTextItem",
                "position": "1",
                "type": "10",
                "value": "0"
            },
            "x": "3866",
            "y": "1849"
        },
        "item_0000000053": {
            "disabled": "0",
            "opcode": "control_wait",
            "param_1": {
                "opcode": "CGraphicsTextItem",
                "position": "1",
                "type": "10",
                "value": "4.25"
            },
            "x": "3866",
            "y": "1899"
        },
        "item_0000000054": {
            "disabled": "0",
            "opcode": "MakerSteerin_Analogy",
            "param_1": {
                "opcode": "CGraphicsTextItem",
                "position": "1",
                "type": "10",
                "value": "50"
            },
            "x": "3866",
            "y": "1949"
        },
        "item_0000000055": {
            "disabled": "0",
            "opcode": "control_wait",
            "param_1": {
                "opcode": "CGraphicsTextItem",
                "position": "1",
                "type": "10",
                "value": "2.1"
            },
            "x": "3866",
            "y": "1999"
        },
        "item_0000000056": {
            "disabled": "0",
            "opcode": "MakerSteerin_Analogy",
            "param_1": {
                "opcode": "CGraphicsTextItem",
                "position": "1",
                "type": "10",
                "value": "0"
            },
            "x": "3866",
            "y": "2049"
        },
        "item_0000000057": {
            "disabled": "0",
            "opcode": "control_wait",
            "param_1": {
                "opcode": "CGraphicsTextItem",
                "position": "1",
                "type": "10",
                "value": "4"
            },
            "x": "3866",
            "y": "2099"
        },
        "item_0000000058": {
            "disabled": "0",
            "opcode": "MakerSteerin_Analogy",
            "param_1": {
                "opcode": "CGraphicsTextItem",
                "position": "1",
                "type": "10",
                "value": "50"
            },
            "x": "3866",
            "y": "2149"
        },
        "item_0000000059": {
            "disabled": "0",
            "opcode": "control_wait",
            "param_1": {
                "opcode": "CGraphicsTextItem",
                "position": "1",
                "type": "10",
                "value": "2"
            },
            "x": "3866",
            "y": "2199"
        },
        "item_0000000060": {
            "disabled": "0",
            "opcode": "MakerSteerin_Analogy",
            "param_1": {
                "opcode": "CGraphicsTextItem",
                "position": "1",
                "type": "10",
                "value": "0"
            },
            "x": "3866",
            "y": "2249"
        },
        "item_0000000061": {
            "disabled": "0",
            "opcode": "control_wait",
            "param_1": {
                "opcode": "CGraphicsTextItem",
                "position": "1",
                "type": "10",
                "value": "4.1"
            },
            "x": "3866",
            "y": "2299"
        },
        "item_0000000062": {
            "disabled": "0",
            "opcode": "MakerSteerin_Analogy",
            "param_1": {
                "opcode": "CGraphicsTextItem",
                "position": "1",
                "type": "10",
                "value": "50"
            },
            "x": "3866",
            "y": "2349"
        },
        "item_0000000063": {
            "disabled": "0",
            "opcode": "control_wait",
            "param_1": {
                "opcode": "CGraphicsTextItem",
                "position": "1",
                "type": "10",
                "value": "2.2"
            },
            "x": "3866",
            "y": "2399"
        },
        "item_0000000064": {
            "disabled": "0",
            "opcode": "MakerSteerin_Analogy",
            "param_1": {
                "opcode": "CGraphicsTextItem",
                "position": "1",
                "type": "10",
                "value": "0"
            },
            "x": "3866",
            "y": "2449"
        },
        "item_0000000065": {
            "disabled": "0",
            "opcode": "control_wait",
            "param_1": {
                "opcode": "CGraphicsTextItem",
                "position": "1",
                "type": "10",
                "value": "4"
            },
            "x": "3866",
            "y": "2499"
        },
        "item_0000000066": {
            "disabled": "0",
            "opcode": "MakerSteerin_Analogy",
            "param_1": {
                "opcode": "CGraphicsTextItem",
                "position": "1",
                "type": "10",
                "value": "50"
            },
            "x": "3866",
            "y": "2549"
        },
        "item_0000000067": {
            "disabled": "0",
            "opcode": "control_wait",
            "param_1": {
                "opcode": "CGraphicsTextItem",
                "position": "1",
                "type": "10",
                "value": "2"
            },
            "x": "3866",
            "y": "2599"
        },
        "item_0000000068": {
            "disabled": "0",
            "opcode": "MakerSteerin_Analogy",
            "param_1": {
                "opcode": "CGraphicsTextItem",
                "position": "1",
                "type": "10",
                "value": "0"
            },
            "x": "3866",
            "y": "2649"
        },
        "item_0000000069": {
            "disabled": "0",
            "opcode": "control_wait",
            "param_1": {
                "opcode": "CGraphicsTextItem",
                "position": "1",
                "type": "10",
                "value": "4.2"
            },
            "x": "3866",
            "y": "2699"
        },
        "item_0000000070": {
            "disabled": "0",
            "opcode": "MakerSteerin_Analogy",
            "param_1": {
                "opcode": "CGraphicsTextItem",
                "position": "1",
                "type": "10",
                "value": "50"
            },
            "x": "3866",
            "y": "2749"
        },
        "item_0000000071": {
            "disabled": "0",
            "opcode": "control_wait",
            "param_1": {
                "opcode": "CGraphicsTextItem",
                "position": "1",
                "type": "10",
                "value": "2.1"
            },
            "x": "3866",
            "y": "2799"
        },
        "item_0000000072": {
            "disabled": "0",
            "opcode": "MakerSteerin_Analogy",
            "param_1": {
                "opcode": "CGraphicsTextItem",
                "position": "1",
                "type": "10",
                "value": "0"
            },
            "x": "3866",
            "y": "2849"
        },
        "item_0000000073": {
            "disabled": "0",
            "opcode": "control_wait",
            "param_1": {
                "opcode": "CGraphicsTextItem",
                "position": "1",
                "type": "10",
                "value": "1.5"
            },
            "x": "3866",
            "y": "2899"
        },
        "item_0000000074": {
            "disabled": "0",
            "opcode": "MakerMotion_OpenLoop",
            "param_1": {
                "position": "1",
                "type": "11",
                "value": "1"
            },
            "param_3": {
                "opcode": "CGraphicsTextItem",
                "position": "3",
                "type": "10",
                "value": "0"
            },
            "x": "3866",
            "y": "2949"
        },
        "item_0000000075": {
            "disabled": "0",
            "opcode": "smallmotion_setmotor",
            "param_1": {
                "position": "1",
                "type": "11",
                "value": "1"
            },
            "param_3": {
                "position": "3",
                "type": "11",
                "value": "3"
            },
            "param_5": {
                "opcode": "CGraphicsTextItem",
                "position": "5",
                "type": "10",
                "value": "0"
            },
            "x": "3866",
            "y": "2999"
        },
        "item_0000000076": {
            "disabled": "0",
            "opcode": "smallmotion_setmotor",
            "param_1": {
                "position": "1",
                "type": "11",
                "value": "1"
            },
            "param_3": {
                "position": "3",
                "type": "11",
                "value": "4"
            },
            "param_5": {
                "opcode": "CGraphicsTextItem",
                "position": "5",
                "type": "10",
                "value": "0"
            },
            "x": "3866",
            "y": "3049"
        }
    },
    "top_4": {
        "item_0000000077": {
            "disabled": "0",
            "opcode": "main",
            "x": "5000",
            "y": "0"
        },
        "item_0000000078": {
            "disabled": "0",
            "opcode": "MakerMotion_OpenLoop",
            "param_1": {
                "position": "1",
                "type": "11",
                "value": "1"
            },
            "param_3": {
                "opcode": "CGraphicsTextItem",
                "position": "3",
                "type": "10",
                "value": "85"
            },
            "x": "5000",
            "y": "55"
        },
        "item_0000000079": {
            "disabled": "0",
            "opcode": "MakerSteerin_Analogy",
            "param_1": {
                "opcode": "CGraphicsTextItem",
                "position": "1",
                "type": "10",
                "value": "90"
            },
            "x": "5000",
            "y": "105"
        },
        "item_0000000080": {
            "disabled": "0",
            "opcode": "motion_ExpansionEdition",
            "param_1": {
                "position": "1",
                "type": "11",
                "value": "1"
            },
            "param_3": {
                "opcode": "CGraphicsTextItem",
                "position": "3",
                "type": "10",
                "value": "50"
            },
            "param_5": {
                "opcode": "CGraphicsTextItem",
                "position": "5",
                "type": "10",
                "value": "50"
            },
            "param_7": {
                "opcode": "CGraphicsTextItem",
                "position": "7",
                "type": "10",
                "value": "95"
            },
            "param_9": {
                "opcode": "CGraphicsTextItem",
                "position": "9",
                "type": "10",
                "value": "95"
            },
            "x": "5000",
            "y": "155"
        },
        "item_0000000081": {
            "disabled": "0",
            "opcode": "MakerSteerin_Analogy",
            "param_1": {
                "opcode": "CGraphicsTextItem",
                "position": "1",
                "type": "10",
                "value": "90"
            },
            "x": "5000",
            "y": "205"
        },
        "item_0000000082": {
            "disabled": "0",
            "opcode": "control_wait",
            "param_1": {
                "opcode": "CGraphicsTextItem",
                "position": "1",
                "type": "10",
                "value": "4.0"
            },
            "x": "5000",
            "y": "255"
        },
        "item_0000000083": {
            "disabled": "0",
            "noteItem": {
                "text": "first turn",
                "x": "5259",
                "y": "296.25"
            },
            "opcode": "MakerSteerin_Analogy",
            "param_1": {
                "opcode": "CGraphicsTextItem",
                "position": "1",
                "type": "10",
                "value": "130"
            },
            "x": "5000",
            "y": "305"
        },
        "item_0000000084": {
            "disabled": "0",
            "opcode": "control_wait",
            "param_1": {
                "opcode": "CGraphicsTextItem",
                "position": "1",
                "type": "10",
                "value": "1.75"
            },
            "x": "5000",
            "y": "355"
        },
        "item_0000000085": {
            "disabled": "0",
            "opcode": "MakerSteerin_Analogy",
            "param_1": {
                "opcode": "CGraphicsTextItem",
                "position": "1",
                "type": "10",
                "value": "90"
            },
            "x": "5000",
            "y": "405"
        },
        "item_0000000086": {
            "disabled": "0",
            "opcode": "control_wait",
            "param_1": {
                "opcode": "CGraphicsTextItem",
                "position": "1",
                "type": "10",
                "value": "5.8"
            },
            "x": "5000",
            "y": "455"
        },
        "item_0000000087": {
            "disabled": "0",
            "noteItem": {
                "text": "second turn",
                "x": "5259",
                "y": "496.25"
            },
            "opcode": "MakerSteerin_Analogy",
            "param_1": {
                "opcode": "CGraphicsTextItem",
                "position": "1",
                "type": "10",
                "value": "135"
            },
            "x": "5000",
            "y": "505"
        },
        "item_0000000088": {
            "disabled": "0",
            "opcode": "control_wait",
            "param_1": {
                "opcode": "CGraphicsTextItem",
                "position": "1",
                "type": "10",
                "value": "1.75"
            },
            "x": "5000",
            "y": "555"
        },
        "item_0000000089": {
            "disabled": "0",
            "opcode": "MakerSteerin_Analogy",
            "param_1": {
                "opcode": "CGraphicsTextItem",
                "position": "1",
                "type": "10",
                "value": "90"
            },
            "x": "5000",
            "y": "605"
        },
        "item_0000000090": {
            "disabled": "0",
            "opcode": "control_wait",
            "param_1": {
                "opcode": "CGraphicsTextItem",
                "position": "1",
                "type": "10",
                "value": "5.8"
            },
            "x": "5000",
            "y": "655"
        },
        "item_0000000091": {
            "disabled": "0",
            "noteItem": {
                "text": "third turn",
                "x": "5279",
                "y": "712.75"
            },
            "opcode": "MakerSteerin_Analogy",
            "param_1": {
                "opcode": "CGraphicsTextItem",
                "position": "1",
                "type": "10",
                "value": "135"
            },
            "x": "5000",
            "y": "705"
        },
        "item_0000000092": {
            "disabled": "0",
            "opcode": "control_wait",
            "param_1": {
                "opcode": "CGraphicsTextItem",
                "position": "1",
                "type": "10",
                "value": "1.75"
            },
            "x": "5000",
            "y": "755"
        },
        "item_0000000093": {
            "disabled": "0",
            "opcode": "MakerSteerin_Analogy",
            "param_1": {
                "opcode": "CGraphicsTextItem",
                "position": "1",
                "type": "10",
                "value": "90"
            },
            "x": "5000",
            "y": "805"
        },
        "item_0000000094": {
            "disabled": "0",
            "opcode": "control_wait",
            "param_1": {
                "opcode": "CGraphicsTextItem",
                "position": "1",
                "type": "10",
                "value": "5.8"
            },
            "x": "5000",
            "y": "855"
        },
        "item_0000000095": {
            "disabled": "0",
            "noteItem": {
                "text": "fourth turn",
                "x": "5281",
                "y": "907.25"
            },
            "opcode": "MakerSteerin_Analogy",
            "param_1": {
                "opcode": "CGraphicsTextItem",
                "position": "1",
                "type": "10",
                "value": "135"
            },
            "x": "5000",
            "y": "905"
        },
        "item_0000000096": {
            "disabled": "0",
            "opcode": "control_wait",
            "param_1": {
                "opcode": "CGraphicsTextItem",
                "position": "1",
                "type": "10",
                "value": "1.75"
            },
            "x": "5000",
            "y": "955"
        },
        "item_0000000097": {
            "disabled": "0",
            "opcode": "MakerSteerin_Analogy",
            "param_1": {
                "opcode": "CGraphicsTextItem",
                "position": "1",
                "type": "10",
                "value": "90"
            },
            "x": "5000",
            "y": "1005"
        },
        "item_0000000098": {
            "disabled": "0",
            "opcode": "control_wait",
            "param_1": {
                "opcode": "CGraphicsTextItem",
                "position": "1",
                "type": "10",
                "value": "5.8"
            },
            "x": "5000",
            "y": "1055"
        },
        "item_0000000099": {
            "disabled": "0",
            "noteItem": {
                "text": "fifth turn",
                "x": "5275",
                "y": "1131.18"
            },
            "opcode": "MakerSteerin_Analogy",
            "param_1": {
                "opcode": "CGraphicsTextItem",
                "position": "1",
                "type": "10",
                "value": "135"
            },
            "x": "5000",
            "y": "1105"
        },
        "item_0000000100": {
            "disabled": "0",
            "opcode": "control_wait",
            "param_1": {
                "opcode": "CGraphicsTextItem",
                "position": "1",
                "type": "10",
                "value": "1.75"
            },
            "x": "5000",
            "y": "1155"
        },
        "item_0000000101": {
            "disabled": "0",
            "opcode": "MakerSteerin_Analogy",
            "param_1": {
                "opcode": "CGraphicsTextItem",
                "position": "1",
                "type": "10",
                "value": "90"
            },
            "x": "5000",
            "y": "1205"
        },
        "item_0000000102": {
            "disabled": "0",
            "opcode": "control_wait",
            "param_1": {
                "opcode": "CGraphicsTextItem",
                "position": "1",
                "type": "10",
                "value": "5.8"
            },
            "x": "5000",
            "y": "1255"
        },
        "item_0000000103": {
            "disabled": "0",
            "noteItem": {
                "text": "sixth turn",
                "x": "5283",
                "y": "1301.18"
            },
            "opcode": "MakerSteerin_Analogy",
            "param_1": {
                "opcode": "CGraphicsTextItem",
                "position": "1",
                "type": "10",
                "value": "135"
            },
            "x": "5000",
            "y": "1305"
        },
        "item_0000000104": {
            "disabled": "0",
            "opcode": "control_wait",
            "param_1": {
                "opcode": "CGraphicsTextItem",
                "position": "1",
                "type": "10",
                "value": "1.75"
            },
            "x": "5000",
            "y": "1355"
        },
        "item_0000000105": {
            "disabled": "0",
            "opcode": "MakerSteerin_Analogy",
            "param_1": {
                "opcode": "CGraphicsTextItem",
                "position": "1",
                "type": "10",
                "value": "90"
            },
            "x": "5000",
            "y": "1405"
        },
        "item_0000000106": {
            "disabled": "0",
            "opcode": "control_wait",
            "param_1": {
                "opcode": "CGraphicsTextItem",
                "position": "1",
                "type": "10",
                "value": "5.8"
            },
            "x": "5000",
            "y": "1455"
        },
        "item_0000000107": {
            "disabled": "0",
            "noteItem": {
                "text": "seventh turn",
                "x": "5286.25",
                "y": "1514.18"
            },
            "opcode": "MakerSteerin_Analogy",
            "param_1": {
                "opcode": "CGraphicsTextItem",
                "position": "1",
                "type": "10",
                "value": "135"
            },
            "x": "5000",
            "y": "1505"
        },
        "item_0000000108": {
            "disabled": "0",
            "opcode": "control_wait",
            "param_1": {
                "opcode": "CGraphicsTextItem",
                "position": "1",
                "type": "10",
                "value": "1.75"
            },
            "x": "5000",
            "y": "1555"
        },
        "item_0000000109": {
            "disabled": "0",
            "opcode": "MakerSteerin_Analogy",
            "param_1": {
                "opcode": "CGraphicsTextItem",
                "position": "1",
                "type": "10",
                "value": "90"
            },
            "x": "5000",
            "y": "1605"
        },
        "item_0000000110": {
            "disabled": "0",
            "opcode": "control_wait",
            "param_1": {
                "opcode": "CGraphicsTextItem",
                "position": "1",
                "type": "10",
                "value": "5.8"
            },
            "x": "5000",
            "y": "1655"
        },
        "item_0000000111": {
            "disabled": "0",
            "noteItem": {
                "text": "eigth turn",
                "x": "5272.25",
                "y": "1708.18"
            },
            "opcode": "MakerSteerin_Analogy",
            "param_1": {
                "opcode": "CGraphicsTextItem",
                "position": "1",
                "type": "10",
                "value": "135"
            },
            "x": "5000",
            "y": "1705"
        },
        "item_0000000112": {
            "disabled": "0",
            "opcode": "control_wait",
            "param_1": {
                "opcode": "CGraphicsTextItem",
                "position": "1",
                "type": "10",
                "value": "1.75"
            },
            "x": "5000",
            "y": "1755"
        },
        "item_0000000113": {
            "disabled": "0",
            "opcode": "MakerSteerin_Analogy",
            "param_1": {
                "opcode": "CGraphicsTextItem",
                "position": "1",
                "type": "10",
                "value": "90"
            },
            "x": "5000",
            "y": "1805"
        },
        "item_0000000114": {
            "disabled": "0",
            "opcode": "control_wait",
            "param_1": {
                "opcode": "CGraphicsTextItem",
                "position": "1",
                "type": "10",
                "value": "2"
            },
            "x": "5000",
            "y": "1855"
        },
        "item_0000000115": {
            "disabled": "0",
            "opcode": "MakerMotion_stopOne",
            "param_0": {
                "position": "0",
                "type": "11",
                "value": "3"
            },
            "x": "5000",
            "y": "1905"
        },
        "item_0000000116": {
            "disabled": "0",
            "opcode": "motion_ExpansionEdition",
            "param_1": {
                "position": "1",
                "type": "11",
                "value": "1"
            },
            "param_3": {
                "opcode": "CGraphicsTextItem",
                "position": "3",
                "type": "10",
                "value": "50"
            },
            "param_5": {
                "opcode": "CGraphicsTextItem",
                "position": "5",
                "type": "10",
                "value": "50"
            },
            "param_7": {
                "opcode": "CGraphicsTextItem",
                "position": "7",
                "type": "10",
                "value": "0"
            },
            "param_9": {
                "opcode": "CGraphicsTextItem",
                "position": "9",
                "type": "10",
                "value": "0"
            },
            "x": "5000",
            "y": "1955"
        },
        "item_0000000117": {
            "disabled": "0",
            "opcode": "break",
            "x": "5000",
            "y": "2005"
        }
    },
    "varList": [
    ]
}
