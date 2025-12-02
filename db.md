# DB SCHEMA

Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.

## Table name: CARS ( Entity name: CAR)

*Columns Model Details*

- ID = *INT*
- BRAND = *VARCHAR(50)*
- MODEL = *VARCHAR(100)*
- REGISTRATION_YEAR = *YEAR*
- MILEAGE(KM) = *INT*
- FUEL_TYPE = *VARCHAR(20)*
- TRASMISSION_TYPE = *VARCHAR(20)*
- EURO = *VARCHAR(10)*

*Columns Arrival Details*

- ARRIVAL = *DATE*
- STATUS = *VARCHAR(50)*
- PURCHASE_PRICE = *DECIMAL(10,2)*
- DAMAGE_DESCRIPTION = *TEXT*

*Columns Selling Details*

- SELLING PRICE = *DECIMAL(10,2)*
- WORK_DESCRIPTION = *TEXT*
- SERVICE = *DATE*

