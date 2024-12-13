PROJETO FEITO NO AZURE AI VISION STUDIO

SOBRE VISÃO COMPUTACIONAL
* Reconhecimento facial
* Leitura de caracteres
* Analise de imagem

READ-ME FACIAL

JSON

[
  {
    "faceRectangle": {
      "top": 108,
      "left": 445,
      "width": 225,
      "height": 331
    },
    "faceLandmarks": {
      "pupilLeft": {
        "x": 488.4,
        "y": 243
      },
      "pupilRight": {
        "x": 592.2,
        "y": 237.9
      },
      "noseTip": {
        "x": 520.2,
        "y": 303.7
      },
      "mouthLeft": {
        "x": 492.5,
        "y": 349.4
      },
      "mouthRight": {
        "x": 577.3,
        "y": 352
      },
      "eyebrowLeftOuter": {
        "x": 458.5,
        "y": 217.2
      },
      "eyebrowLeftInner": {
        "x": 503.4,
        "y": 219.2
      },
      "eyeLeftOuter": {
        "x": 470.9,
        "y": 243.3
      },
      "eyeLeftTop": {
        "x": 490,
        "y": 234.1
      },
      "eyeLeftBottom": {
        "x": 485,
        "y": 249.9
      },
      "eyeLeftInner": {
        "x": 507.7,
        "y": 244.7
      },
      "eyebrowRightInner": {
        "x": 555.7,
        "y": 217.1
      },
      "eyebrowRightOuter": {
        "x": 624.8,
        "y": 214.4
      },
      "eyeRightInner": {
        "x": 571.8,
        "y": 242
      },
      "eyeRightTop": {
        "x": 588,
        "y": 228
      },
      "eyeRightBottom": {
        "x": 593.7,
        "y": 245.4
      },
      "eyeRightOuter": {
        "x": 615.2,
        "y": 236.1
      },
      "noseRootLeft": {
        "x": 516.4,
        "y": 251.1
      },
      "noseRootRight": {
        "x": 545.4,
        "y": 248.7
      },
      "noseLeftAlarTop": {
        "x": 506,
        "y": 288.4
      },
      "noseRightAlarTop": {
        "x": 552,
        "y": 286.9
      },
      "noseLeftAlarOutTip": {
        "x": 500.2,
        "y": 308.7
      },
      "noseRightAlarOutTip": {
        "x": 561.5,
        "y": 309.9
      },
      "upperLipTop": {
        "x": 527.7,
        "y": 347.1
      },
      "upperLipBottom": {
        "x": 526,
        "y": 354.1
      },
      "underLipTop": {
        "x": 525.3,
        "y": 360.1
      },
      "underLipBottom": {
        "x": 525.6,
        "y": 373.2
      }
    },
    "faceAttributes": {
      "mask": {
        "type": "faceMask",
        "noseAndMouthCovered": true
      }
    }
  }
] 




RECONHECIMENTO DE CARACTER

[
  {
    "lines": [
      {
        "text": "CreditCard",
        "boundingPolygon": [
          {
            "x": 774,
            "y": 1334
          },
          {
            "x": 2042,
            "y": 1330
          },
          {
            "x": 2042,
            "y": 1556
          },
          {
            "x": 774,
            "y": 1558
          }
        ],
        "words": [
          {
            "text": "CreditCard",
            "boundingPolygon": [
              {
                "x": 774,
                "y": 1339
              },
              {
                "x": 2008,
                "y": 1332
              },
              {
                "x": 2004,
                "y": 1558
              },
              {
                "x": 774,
                "y": 1558
              }
            ],
            "confidence": 0.993
          }
        ]
      },
      {
        "text": "BANK",
        "boundingPolygon": [
          {
            "x": 3158,
            "y": 1380
          },
          {
            "x": 3662,
            "y": 1390
          },
          {
            "x": 3656,
            "y": 1572
          },
          {
            "x": 3158,
            "y": 1574
          }
        ],
        "words": [
          {
            "text": "BANK",
            "boundingPolygon": [
              {
                "x": 3158,
                "y": 1380
              },
              {
                "x": 3633,
                "y": 1384
              },
              {
                "x": 3632,
                "y": 1576
              },
              {
                "x": 3158,
                "y": 1574
              }
            ],
            "confidence": 0.989
          }
        ]
      },
      {
        "text": "1234 5678 9012 3456",
        "boundingPolygon": [
          {
            "x": 794,
            "y": 2452
          },
          {
            "x": 3654,
            "y": 2458
          },
          {
            "x": 3654,
            "y": 2660
          },
          {
            "x": 792,
            "y": 2652
          }
        ],
        "words": [
          {
            "text": "1234",
            "boundingPolygon": [
              {
                "x": 798,
                "y": 2456
              },
              {
                "x": 1338,
                "y": 2453
              },
              {
                "x": 1336,
                "y": 2655
              },
              {
                "x": 794,
                "y": 2650
              }
            ],
            "confidence": 0.99
          },
          {
            "text": "5678",
            "boundingPolygon": [
              {
                "x": 1554,
                "y": 2453
              },
              {
                "x": 2108,
                "y": 2453
              },
              {
                "x": 2107,
                "y": 2660
              },
              {
                "x": 1552,
                "y": 2657
              }
            ],
            "confidence": 0.988
          },
          {
            "text": "9012",
            "boundingPolygon": [
              {
                "x": 2310,
                "y": 2454
              },
              {
                "x": 2864,
                "y": 2457
              },
              {
                "x": 2866,
                "y": 2660
              },
              {
                "x": 2310,
                "y": 2660
              }
            ],
            "confidence": 0.986
          },
          {
            "text": "3456",
            "boundingPolygon": [
              {
                "x": 3079,
                "y": 2459
              },
              {
                "x": 3620,
                "y": 2466
              },
              {
                "x": 3624,
                "y": 2660
              },
              {
                "x": 3082,
                "y": 2660
              }
            ],
            "confidence": 0.99
          }
        ]
      },
      {
        "text": "0123",
        "boundingPolygon": [
          {
            "x": 784,
            "y": 2754
          },
          {
            "x": 1020,
            "y": 2758
          },
          {
            "x": 1012,
            "y": 2858
          },
          {
            "x": 786,
            "y": 2858
          }
        ],
        "words": [
          {
            "text": "0123",
            "boundingPolygon": [
              {
                "x": 791,
                "y": 2754
              },
              {
                "x": 1018,
                "y": 2756
              },
              {
                "x": 1017,
                "y": 2860
              },
              {
                "x": 790,
                "y": 2858
              }
            ],
            "confidence": 0.989
          }
        ]
      },
      {
        "text": "VALID",
        "boundingPolygon": [
          {
            "x": 2368,
            "y": 2732
          },
          {
            "x": 2564,
            "y": 2732
          },
          {
            "x": 2568,
            "y": 2804
          },
          {
            "x": 2368,
            "y": 2804
          }
        ],
        "words": [
          {
            "text": "VALID",
            "boundingPolygon": [
              {
                "x": 2373,
                "y": 2732
              },
              {
                "x": 2554,
                "y": 2732
              },
              {
                "x": 2554,
                "y": 2804
              },
              {
                "x": 2373,
                "y": 2804
              }
            ],
            "confidence": 0.994
          }
        ]
      },
      {
        "text": "THRU",
        "boundingPolygon": [
          {
            "x": 2382,
            "y": 2804
          },
          {
            "x": 2568,
            "y": 2804
          },
          {
            "x": 2570,
            "y": 2882
          },
          {
            "x": 2382,
            "y": 2882
          }
        ],
        "words": [
          {
            "text": "THRU",
            "boundingPolygon": [
              {
                "x": 2392,
                "y": 2804
              },
              {
                "x": 2552,
                "y": 2804
              },
              {
                "x": 2552,
                "y": 2882
              },
              {
                "x": 2392,
                "y": 2882
              }
            ],
            "confidence": 0.984
          }
        ]
      },
      {
        "text": "Name Surname",
        "boundingPolygon": [
          {
            "x": 866,
            "y": 2948
          },
          {
            "x": 2576,
            "y": 2948
          },
          {
            "x": 2574,
            "y": 3150
          },
          {
            "x": 866,
            "y": 3148
          }
        ],
        "words": [
          {
            "text": "Name",
            "boundingPolygon": [
              {
                "x": 868,
                "y": 2952
              },
              {
                "x": 1395,
                "y": 2954
              },
              {
                "x": 1397,
                "y": 3141
              },
              {
                "x": 872,
                "y": 3146
              }
            ],
            "confidence": 0.992
          },
          {
            "text": "Surname",
            "boundingPolygon": [
              {
                "x": 1587,
                "y": 2955
              },
              {
                "x": 2543,
                "y": 2949
              },
              {
                "x": 2543,
                "y": 3152
              },
              {
                "x": 1589,
                "y": 3141
              }
            ],
            "confidence": 0.994
          }
        ]
      },
      {
        "text": "06/15",
        "boundingPolygon": [
          {
            "x": 3090,
            "y": 2968
          },
          {
            "x": 3664,
            "y": 2968
          },
          {
            "x": 3664,
            "y": 3140
          },
          {
            "x": 3090,
            "y": 3140
          }
        ],
        "words": [
          {
            "text": "06/15",
            "boundingPolygon": [
              {
                "x": 3094,
                "y": 2969
              },
              {
                "x": 3650,
                "y": 2975
              },
              {
                "x": 3646,
                "y": 3141
              },
              {
                "x": 3090,
                "y": 3142
              }
            ],
            "confidence": 0.994
          }
        ]
      }
    ]
  }
]


Analise de imagem

{
  "modelVersion": "2023-10-01",
  "captionResult": {
    "text": "a statue of a woman holding a scale on top of a building",
    "confidence": 0.7009587287902832
  },
  "metadata": {
    "width": 375,
    "height": 250
  }
}
