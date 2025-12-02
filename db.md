# DB SCHEMA

Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.

## Table name: CARS ( Entity name: CAR)

*Columns Model Details*

- ID = *INT* - *NOT NULL* 
- BRAND = *VARCHAR(50)* - *NOT NULL*
- MODEL = *VARCHAR(100)* - *NOT NULL*
- REGISTRATION_YEAR = *YEAR* - *NOT NULL*
- MILEAGE(KM) = *INT* - *DEFAULT*
- FUEL_TYPE = *VARCHAR(20)* - *NOT NULL*
- TRASMISSION_TYPE = *VARCHAR(20)* - *NOT NULL*
- EURO = *VARCHAR(10)* - *NOT NULL*

*Columns Arrival Details*

- ARRIVAL = *DATE* - *NOT NULL*
- STATUS = *VARCHAR(50)* - *DEFAULT*
- PURCHASE_PRICE = *DECIMAL(10,2)* - *NOT NULL*
- DAMAGE_DESCRIPTION = *TEXT* - *NULL*

*Columns Selling Details*

- SELLING PRICE = *DECIMAL(10,2)* - *NULL*
- WORK_DESCRIPTION = *TEXT* - *NULL*
- SERVICE = *DATE* - *NULL*

