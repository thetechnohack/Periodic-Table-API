
API to fetch elements of the periodic table in JSON format. Uses Pandas for dumping .csv data to .json and Flask for API Integration. Deployed on "pythonanywhere.com".

## Requirements:
- Python
- Flask
- JSON


## Install Requirements:

- To install Flask
    > `pip install Flask`

- To install JSON
    > `pip install json`

## Overview
The following document will specify how to use the API to fetch the periodic elements in JSON. Also it will state different methods throught which the elements can be fetch.

|     **Data Object**    |
|------------------------|
| symbol                 |
| name                   |
| atomicMass             |
| atomicNumber           |
| atomicRadius           |
| boilingPoint           |
| bondingType            |
| cpkHexColor            |
| density                |
| electronAffinity       |
| electronegativity      |
| electronicConfiguration|
| groupBlock             |
| ionRadius              |
| ionizationEnergy       |
| meltingPoint           |
| oxidationStates        |
| standardState          |
| vanDerWaalsRadius      |
| yearDiscovered         |


## Methods
There are total of 6 methods by which you can fetch the data :

### All

[https://neelpatel05.pythonanywhere.com](https://neelpatel05.pythonanywhere.com/)

This will fetch all the 118 elements from periodic table.

--------------------------------------------------------------------------------------------------------------------------------------------
### Atomic Number

 [https://neelpatel05.pythonanywhere.com/element/atomicnumber?atomicnumber=20](https://neelpatel05.pythonanywhere.com/element/atomicnumber?atomicnumber=20)

This will fetch element from periodic table having atomic number 20. Replace 20 with any other atomic number to fetch that element from 118.

--------------------------------------------------------------------------------------------------------------------------------------------

### Atomic Name

[https://neelpatel05.pythonanywhere.com/element/atomicname?atomicname=Mercury](https://neelpatel05.pythonanywhere.com/element/atomicname?atomicname=Mercury)

This will fetch element from periodic table having atomic name "Mercury". Replace "Mercury" with any other atomic name to fetch that element.

--------------------------------------------------------------------------------------------------------------------------------------------

### Atomic Symbol

[https://neelpatel05.pythonanywhere.com/element/symbol?symbol=H](https://neelpatel05.pythonanywhere.com/element/symbol?symbol=H)

This will fetch element from periodic table having atomic symbol "H" i.e. Hydrogen. Replace "H" with any other atomic symbol to fetch that element.

--------------------------------------------------------------------------------------------------------------------------------------------

### Bonding Type

[https://neelpatel05.pythonanywhere.com/element/bondingtype?bondingtype=metallic](https://neelpatel05.pythonanywhere.com/element/bondingtype?bondingtype=metallic)

This will fetch all elements from periodic table having  Metallic bonding. Replace metallic with any other bonding type to fetch elements.

--------------------------------------------------------------------------------------------------------------------------------------------

### Group Block

[https://neelpatel05.pythonanywhere.com/element/groupblock?groupblock=metal](https://neelpatel05.pythonanywhere.com/element/groupblock?groupblock=metal)

This will fetch all elements from periodic table belongs to metal group. Replace metal with any other bonding type to fetch elements.

--------------------------------------------------------------------------------------------------------------------------------------------

### State

[https://neelpatel05.pythonanywhere.com/element/state?state=gas](https://neelpatel05.pythonanywhere.com/element/state?state=gas)

This will fetch all elements from periodic table belongs to gas state. Replace gas with any other state to fetch elements.