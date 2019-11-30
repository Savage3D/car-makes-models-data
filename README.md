# Car makes and models database (2019)
The list contains **116** car makes and **2157** models.

Last update: **2019/11/30**.

There are two files:
- car-makes.json - data in JSON string;
- query.sql - SQL query for inserting data in a database.

SQL file contains two tables:
- CarMakes (Id, Name);
- CarModels(Id, MakeId, Name, Series)

Some models belong to one series. For example, cars BMW 520, BMW 535 and BMW 535 Gran Turismo belong to BMW 5 series.

## Samples of tables

### CarMakes

| Id |   Name   |
|:--:|:--------:|
|  1 |  Abarth  |
|  2 |    AC    |
|  3 |  Acura   |

### CarModels

|  Id  | MakeId |         Name        |   Series   |
|:----:|:------:|:-------------------:|:----------:|
|  160 |   14   |         130         |  1 Series  |
|  161 |   14   |         135         |  1 Series  |
|  163 |   14   |      1er M Coupé    |  1 Series  |
|  164 |   14   |         2002        |    NULL    |
|  165 |   14   |  214 Active Tourer  |  1 Series  |

