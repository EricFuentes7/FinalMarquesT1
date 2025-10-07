# XML
```xml
<cuina>
    <plat nom = "Paella" preu= "12.50">
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

    <plat nom = "Amanida de Tonyina" preu= "8.00">
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
            "calories": "180 kcal"
          },
          {
            "nom": "Camaró",
            "quantitat": 100.0,
            "unitats": "grams",
            "calories": "90 kcal"
          },
          {
            "nom": "Pollastre",
            "quantitat": 150.0,
            "unitats": "grams",
            "calories": "210 kcal"
          },
          {
            "nom": "Safrà",
            "quantitat": 0.5,
            "unitats": "grams",
            "calories": "2 kcal"
          },
          {
            "nom": "Aigua",
            "quantitat": 500.0,
            "unitats": "ml",
            "calories": "0 kcal"
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
            "calories": "14 kcal"
          },
          {
            "nom": "Tomàquet",
            "quantitat": 100.0,
            "unitats": "grams",
            "calories": "18 kcal"
          },
          {
            "nom": "Tonyina",
            "quantitat": 120.0,
            "unitats": "grams",
            "calories": "132 kcal"
          },
          {
            "nom": "Ou dur",
            "quantitat": 50.0,
            "unitats": "grams",
            "calories": "77 kcal"
          },
          {
            "nom": "Oliva",
            "quantitat": 10.0,
            "unitats": "unitats",
            "calories": "40 kcal"
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