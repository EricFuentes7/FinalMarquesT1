# XML
```xml
<?xml version="1.0" encoding="UTF-8"?>
<cuina>
    <plat nom = "Paella">
        <preu>12.50</preu>
        <recepta>
            <ingredients>
                <ingredient>
                    <nom>Arròs</nom>
                    <quantitat>200.0</quantitat>
                    <unitats>grams</unitats>
                    <calories>180 kcal</calories>
                </ingredient>
                <ingredient>
                    <nom>Camaró</nom>
                    <quantitat>100.0</quantitat>
                    <unitats>grams</unitats>
                    <calories>90 kcal</calories>
                </ingredient>
                <ingredient>
                    <nom>Pollastre</nom>
                    <quantitat>150.0</quantitat>
                    <unitats>grams</unitats>
                    <calories>210 kcal</calories>
                </ingredient>
                <ingredient>
                    <nom>Safrà</nom>
                    <quantitat>0.5</quantitat>
                    <unitats>grams</unitats>
                    <calories>2 kcal</calories>
                </ingredient>
                <ingredient>
                    <nom>Aigua</nom>
                    <quantitat>500.0</quantitat>
                    <unitats>ml</unitats>
                    <calories>0 kcal</calories>
                </ingredient>
            </ingredients>
        </recepta>
        <alergogens>
            <alergen>Pot contenir traces de crustacis</alergen>
            <alergen>Conté Safrà</alergen>
        </alergogens>
    </plat>

    <plat nom = "Amanida de Tonyina">
        <preu>8.00</preu>
        <recepta>
            <ingredients>
                <ingredient>
                    <nom>Enciam</nom>
                    <quantitat>80.0</quantitat>
                    <unitats>grams</unitats>
                    <calories>14 kcal</calories>
                </ingredient>
                <ingredient>
                    <nom>Tomàquet</nom>
                    <quantitat>100.0</quantitat>
                    <unitats>grams</unitats>
                    <calories>18 kcal</calories>
                </ingredient>
                <ingredient>
                    <nom>Tonyina</nom>
                    <quantitat>120.0</quantitat>
                    <unitats>grams</unitats>
                    <calories>132 kcal</calories>
                </ingredient>
                <ingredient>
                    <nom>Ou dur</nom>
                    <quantitat>50.0</quantitat>
                    <unitats>grams</unitats>
                    <calories>77 kcal</calories>
                </ingredient>
                <ingredient>
                    <nom>Oliva</nom>
                    <quantitat>10.0</quantitat>
                    <unitats>unitats</unitats>
                    <calories>40 kcal</calories>
                </ingredient>
            </ingredients>
        </recepta>
        <alergogens>
            <alergen>Ou</alergen>
        </alergogens>
    </plat>
</cuina>
```

# JSON
```json
{
  "plats": [
    {
    "nom": "Paella",
    "preu": 12.50,
    "recepta": [
      {
        "ingredients": [
          {
            "nom": "Arròs",
            "quantitat": 200.0,
            "unitats": "grams",
            "calories": 180
          },
          {
            "nom": "Camaró",
            "quantitat": 100.0,
            "unitats": "grams",
            "calories": 90
          },
          {
            "nom": "Pollastre",
            "quantitat": 150.0,
            "unitats": "grams",
            "calories": 210
          },
          {
            "nom": "Safrà",
            "quantitat": 0.5,
            "unitats": "grams",
            "calories": 2
          },
          {
            "nom": "Aigua",
            "quantitat": 500.0,
            "unitats": "ml",
            "calories": 0
          }
        ]
      }
    ],
    "alergogens": [
      "Pot contenir traces de crustacis",
      "Conté Safrà"
    ]
},
{
    "nom": "Amanida de Tonyina",
    "preu": 8.00,
    "recepta": [
      {
        "ingredients": [
          {
            "nom": "Enciam",
            "quantitat": 80.0,
            "unitats": "grams",
            "calories": 14
          },
          {
            "nom": "Tomàquet",
            "quantitat": 100.0,
            "unitats": "grams",
            "calories": 18
          },
          {
            "nom": "Tonyina",
            "quantitat": 120.0,
            "unitats": "grams",
            "calories": 132
          },
          {
            "nom": "Ou dur",
            "quantitat": 50.0,
            "unitats": "grams",
            "calories": 77
          },
          {
            "nom": "Oliva",
            "quantitat": 10.0,
            "unitats": "unitats",
            "calories": 40
          }
        ]
      }
    ],
    "alergogens": [
      "Ou dur"
    ]
}
]
}
```

# CSV

Plats que tenim a la cuina:

```csv
Nom,Preu,Alergogens
Paella,12.50,Crustacis i Safrà
Amanida de Tonyina,8.00,Ou dur
```

Ingredients de **Paella**

```csv
Nom,Quantitat,Unitats,Calories-kcal
Arròs,200.0,grams,180
Camaró,100.0,grams,90
Pollastre,150.0,grams,210
Safrà,0.5,grams,2
Aigua,500.0,ml,0
```

Ingredients de **Amanida de Tonyina**

```csv
Nom,Quantitat,Unitats,Calories-kcal
Enciam,80.0,grams,132
Tomàquet,100.0,grams,18
Tonyina,120.0,grams,132
Ou dur,50.0,grams,77
Oliva,10.0,unitats,40
```

# YAML

```yaml
cuina:
  plats:
    paella:
      nom: "Paella"
      preu: 12.50
      ingredients:
        arros:
          nom: "Arròs"
          quantitat: 200
          unitats: "grams"
          kcalories: 180
        camaro:
          nom: "Camaró"
          quantitat: 100
          unitats: "grams"
          kcalories: 90
        pollastre:
          nom: "Pollastre"
          quantitat: 150
          unitats: "grams"
          kcalories: 2
        safra:
          nom: "Safrà"
          quantitat: 0.5
          unitats: "grams"
          kcalories: 2
        aigua:
          nom: "Aigua"
          quantitat: 500
          unitats: "ml"
          kcalories: 0
      alergogens:
        - "Pot contenir traces de crustacis"
        - "Conté Safrà"
    amanida-de-tonyina:
      nom: "Amanida de Tonyina"
      preu: 8
      ingredients:
        enciam:
          nom: "Enciam"
          quantitat: 80
          unitats: "grams"
          kcalories: 14
        tomaquet:
          nom: "Tomàquet"
          quantitat: 100
          unitats: "grams"
          kcalories: 18
        tonyina:
          nom: "Tonyina"
          quantitat: 120
          unitats: "grams"
          kcalories: 132
        ou-dur:
          nom: "Ou dur"
          quantitat: 50
          unitats: "grams"
          kcalories: 77
        oliva:
          nom: "Oliva"
          quantitat: 10
          unitats: "unitats"
          kcalories: 40
      alergogens:
        - "Ou dur"
```