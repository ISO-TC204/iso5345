[Home](readme.md)

# RITSI Registered items: ITS-SRSA

Note 1: "Exp" stands for exponent.

Note 2: Units and exponent information is recommended, not required.


|ID |Description                                |Assignee  |Updated   |State   |Direction| Units    |Exp|Imprecision| Test Activation|
|---|-------------------------------------------|----------|----------|--------|---------|----------|---|-----------|-----|
|FAC|Field device: air conditioner on           |ISO TC 204|2024-03-25|assigned|any      |Boolean   |0  |          0| Yes |
|FAH|Field device: ambient air relative humidity|ISO TC 204|2023-07-06|assigned|input    |Percent   |-1 |       <100|  No |
|FAL|Field device: ambient light                |ISO TC 204|2023-07-06|assigned|input    |Unitless  |0  |         NA|  No |
|FAT|Field device: ambient air temperature      |ISO TC 204|2023-07-06|assigned|input    |Celsius   |-2 |       <100|  No |
|FBA|Field device: battery electric current     |ISO TC 204|2023-07-06|assigned|input    |Amperes   |-2 |       <100|  No |
|FBC|Field device: battery charge               |ISO TC 204|2023-07-06|assigned|input    |Percent   |-1 |       <100|  No |
|FBV|Field device: battery voltage              |ISO TC 204|2023-07-06|assigned|input    |Volts     |-2 |       <100|  No |
|FDC|Field device: dehumidifier control         |ISO TC 204|2023-07-06|assigned|output   |Boolean   |0  |          0| Yes |
|FDO|Field device: enclosure door open          |ISO TC 204|2024-03-25|assigned|input    |Boolean   |0  |          0|  No |
|FEH|Field device: enclosure relative humidity  |ISO TC 204|2024-03-25|assigned|input    |Percent   |-1 |       <100|  No |
|FET|Field device: enclosure air temperature    |ISO TC 204|2024-03-25|assigned|input    |Celsius   |-2 |       <100|  No |
|FFO|Field device: enclosure fan on             |ISO TC 204|2024-03-25|assigned|any      |Boolean   |0  |          0| Yes |
|FGA|Field device: generator electrical current |ISO TC 204|2023-07-06|assigned|input    |Amperes   |-2 |       <100|  No |
|FGF|Field device: generator fuel level         |ISO TC 204|2023-07-06|assigned|input    |Percent   |-1 |       <100|  No |
|FGS|Field device: generator engine speed       |ISO TC 204|2023-07-06|assigned|input    |RPM       |0  |       <100|  No |
|FGV|Field device: generator voltage            |ISO TC 204|2023-07-06|assigned|input    |Volts     |-2 |       <100|  No |
|FHO|Field device: enclosure heater on          |ISO TC 204|2024-03-25|assigned|any      |Boolean   |0  |          0| Yes |
|FLA|Field device: mains power line current*    |ISO TC 204|2023-07-06|assigned|input    |Amperes   |-2 |       <100|  No |
|FLV|Field device: mains power line voltage     |ISO TC 204|2023-07-06|assigned|input    |Volts     |-2 |       <100|  No |
|FPA|Field device: power supply output current  |ISO TC 204|2024-03-25|assigned|input    |Amperes   |-2 |       <100|  No |
|FPS|Field device: power supply*                |ISO TC 204|2024-03-25|assigned|input    |Enumerated|0  |         NA|  No |
|FPT|Field device: processor card temperature   |ISO TC 204|2023-07-06|assigned|input    |Celsius   |-2 |       <100|  No |
|FPV|Field device: power supply output voltage  |ISO TC 204|2024-03-25|assigned|input    |Volts     |-2 |       <100|  No |
|FSA|Field device: solar power current          |ISO TC 204|2023-07-06|assigned|input    |Amperes   |-2 |       <100|  No |
|FSV|Field device: solar power voltage          |ISO TC 204|2023-07-06|assigned|input    |Volts     |-2 |       <100|  No |
|FTT|Field device: thermostat temperature       |ISO TC 204|2024-03-25|assigned|bi-directional|Celsius|-2 |     <100|  No |
|FWA|Field device: wind power electrical current|ISO TC 204|2023-07-06|assigned|input    |Amperes   |-2 |       <100|  No |
|FWV|Field device: wind power voltage           |ISO TC 204|2023-07-06|assigned|input    |Volts     |-2 |       <100|  No |
|FXB|Field device: auxiliary bi-directional     |ISO TC 204|2024-03-25|assigned|bi-directional|any  |any|        any|  No |
|FXI|Field device: auxiliary input              |ISO TC 204|2024-03-25|assigned|input    |any       |any|        any|  No |
|FXO|Field device: auxiliary output             |ISO TC 204|2024-03-25|assigned|output   |any       |any|        any|  No |
|MDS|Message sign: drum status*                 |ISO TC 204|2024-03-25|assigned|input    |Enumerated|0  |         NA|  No |
|MLS|Message sign: lamp status*                 |ISO TC 204|2024-03-25|assigned|input    |Enumerated|0  |         NA| Yes |
|VSS|Vehicle: speed sensor                      |ISO TC 204|2024-03-25|assigned|input    |m/s       |-1 |       <100|  No |

Mains Power Line Current
negative values mean energy is being sent to the grid

Drum Status Enumerations
- other(1): an error not defined by the other enumerated values.
- noError(2): the drum is working properly.
- interlockError(3): the drum has failed to lock into a correct display position. It is hung up between two adjacent drum faces.
- stuckError(4): the drum cannot be moved from its present position, due to a problem with the drum mechanism.
- positionError(5): the drum has moved to a position other than the position requested by the DMS controller.
- positionUnknownError(6): the DMS controller cannot determine the position of the drum.

Lamp Status Enumerations
- other(1): an error not defined by the other enumerated values.
- noError(2): the lamp is working properly.
- stuckOff(3): the lamp is not able to turn on.
- stuckOn(4): the lamp is not able to turn off.

Power Supply Enumerations
- other(1): an error not defined by the other enumerated values.
- noError(2): the power supply is working properly.
- inputPowerError(3): the power supply is not receiving an acceptable power input.
- powerSupplyFailure(4): the power supply is indicating a failure (e.g., not responding as it should, receiving acceptable input but unable to provide acceptable output)

[Home](readme.md)
