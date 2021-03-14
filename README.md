# DZ-Wilaya-Data

## Description

DZ-Wilaya-Data, is a set of collected Data, that containins the list of the Algerian ***States (Wilaya)*** and  ***Provinces (Baladiya)***. Wialaya codes, and Baladiya codes, post codes and phones codes, are all included in this Data set.  
The Data is represented into two formats, JSON and SQL.

## Notes

### Be Aware

The Data goes to ***27 June 2019***, and it has never being modified or updated since.

### Resources

There are the following resources used to collect and combine the Data.

* Official Goverment websites:
  * <http://www.interieur.gov.dz/index.php/fr/component/annuaire>
  * <http://www.interieur.gov.dz/index.php/ar/component/annuaire>
  * <https://www.algerietelecom.dz/fr/annuaire>
  * <https://www.algerietelecom.dz/ar/annuaire>

* Non-official Goverment websites:
  * <https://abbassa.wordpress.com/wilayate/>
  * <https://dza.postcodebase.com/region1-text>
  * <http://www.algerie-poste.net/code-postal/>
  * <https://fr.wikipedia.org/wiki/Liste_des_communes_d%27Alg%C3%A9rie>

### Scraping code

This work belongs to [Herhar Fares](https://github.com/FaresHerhar), and if you are looking for the Scraping code, please visit the [WilayaApi](https://github.com/FaresHerhar/WilayaApi) repository.

## Explaing the Data

### Json Data

> Full Data Combined

* `Data.json`: All the Data below was combined into one big file, that contains a join of all the Data, as it follows.

```json
    "31": {
        "nameEn": "Oran",
        "nameAr": "وهران",
        "code": "31",
        "commune": [
            "3109",
            .
            .
            .
            "3114"
        ],
        "nameFr": "Oran",
        "codeTel": "41",
        "codePost": "31000"
    }
```

> The Data Related To The States (Wilaya)

* `wilaya.json`: The list of all the States (With all the Data, except Provinces).
* `wilayaAr.json`: The list of all the States names in Arabic.
* `wilayaFr.json`: The list of all the States names in French.
* `wilayaCode.json`: The list of all the States codes.
* `wilayaCodePost.json`: The list of all the States poste codes.
* `wilayaCodeTel.json`: The list of all the States telephone codes.

> The Data Related To The Provinces (Baladiya)

* `baladiya.json`: The list of all the Provinces (With all the Data).
* `baladiyaAr.json`: The list of all the Provinces names in Arabic.
* `baladiyaFr.json`: The list of all the Provinces names in French.
* `baladiyaCode.json`: The list of all the Provinces codes.

### Sql Data

> Tables Schemas

* `schema.sql`: The Tables Schema for the Sql, MySql like databases.
* `schema.sqlite`: The Tables Schema for the Sqlite databases.

> The Data

* `data.sql`: A Data migration file, for inserting all the Data after creating the tables, it is for Sql, MySql like databases.
* `data.sqlite`: The Sqlite Database, therefore it is portable, just copy paste it, and use it.

### Csv Data

ℹ️  The data in the CSV format is separated by a TAB.

> The Data Related To The States (Wilaya)

* `wilaya.csv`: The list of all the States (With all the Data, except Provinces).
* `wilayaAr.csv`: The list of all the States names in Arabic.
* `wilayaFr.csv`: The list of all the States names in French.
* `wilayaCode.csv`: The list of all the States codes.
* `wilayaCodePost.csv`: The list of all the States poste codes.
* `wilayaCodeTel.csv`: The list of all the States telephone codes.

> The Data Related To The Provinces (Baladiya)

* `baladiya.csv`: The list of all the Provinces (With all the Data).
* `baladiyaAr.csv`: The list of all the Provinces names in Arabic.
* `baladiyaFr.csv`: The list of all the Provinces names in French.
* `baladiyaCode.csv`: The list of all the Provinces codes.
