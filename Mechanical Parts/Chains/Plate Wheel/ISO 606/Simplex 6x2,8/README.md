# Chain Plate Wheels ISO606 simplex 6 x 2,8 from z 8 to z 50

This folder contains the 3D models of the plate wheels for ISO 606 chains simplex 6 x 2,8 with number of teeth ranging from z=8 to z=50.

![Image](../images/simplex_screenshot.png "Plate Wheel Simplex")

The model is parametric and the values are contained in the spreadsheet `Data`.

The parameters refer to the plate wheel dimensions as in the drawing below:

![Drawing](../images/simplex_drawing.png "Drawing")

### Table of dimensions in millimeters:

P (Pitch)|Wc (Chain width)|Dr (Roller diameter)|Tr (Tooth radius)|Rw (Radius width)|Wt (Tooth width)|z (Number of teeth)|De (External Diameter)|Dp (Pitch diameter)|D (Hole diameter)|H (Total height)
---|---|---|---|---|---|---|---|---|---|---
6|2,8|4|6|0,7|2,6|8|18|15,67|5|2,6
6|2,8|4|6|0,7|2,6|9|19,9|17,54|5|2,6
6|2,8|4|6|0,7|2,6|10|21,7|19,42|6|2,6
6|2,8|4|6|0,7|2,6|11|23,6|21,3|6|2,6
6|2,8|4|6|0,7|2,6|12|25,4|23,18|6|2,6
6|2,8|4|6|0,7|2,6|13|27,3|25,05|8|2,6
6|2,8|4|6|0,7|2,6|14|29,2|26,96|8|2,6
6|2,8|4|6|0,7|2,6|15|31|28,86|8|2,6
6|2,8|4|6|0,7|2,6|16|33|30,76|8|2,6
6|2,8|4|6|0,7|2,6|17|35|32,65|8|2,6
6|2,8|4|6|0,7|2,6|18|36,9|34,55|8|2,6
6|2,8|4|6|0,7|2,6|19|38,8|36,44|8|2,6
6|2,8|4|6|0,7|2,6|20|40,7|38,34|8|2,6
6|2,8|4|6|0,7|2,6|21|42,6|40,25|8|2,6
6|2,8|4|6|0,7|2,6|22|44,5|42,16|8|2,6
6|2,8|4|6|0,7|2,6|23|46,4|44,06|8|2,6
6|2,8|4|6|0,7|2,6|24|48,3|45,96|8|2,6
6|2,8|4|6|0,7|2,6|25|50,2|47,87|8|2,6
6|2,8|4|6|0,7|2,6|26|52,1|49,76|8|2,6
6|2,8|4|6|0,7|2,6|27|54|51,67|8|2,6
6|2,8|4|6|0,7|2,6|28|55,9|53,58|8|2,6
6|2,8|4|6|0,7|2,6|29|57,8|55,5|8|2,6
6|2,8|4|6|0,7|2,6|30|59,8|57,42|8|2,6
6|2,8|4|6|0,7|2,6|31|61,7|59,31|8|2,6
6|2,8|4|6|0,7|2,6|32|63,6|61,21|8|2,6
6|2,8|4|6|0,7|2,6|33|65,5|63,11|8|2,6
6|2,8|4|6|0,7|2,6|34|67,4|65,02|8|2,6
6|2,8|4|6|0,7|2,6|35|69,3|66,93|8|2,6
6|2,8|4|6|0,7|2,6|36|71,2|68,84|8|2,6
6|2,8|4|6|0,7|2,6|37|73,1|70,75|8|2,6
6|2,8|4|6|0,7|2,6|38|75|72,66|8|2,6
6|2,8|4|6|0,7|2,6|39|76,9|74,57|8|2,6
6|2,8|4|6|0,7|2,6|40|78,9|76,47|8|2,6
6|2,8|4|6|0,7|2,6|41|80,8|78,38|10|2,6
6|2,8|4|6|0,7|2,6|42|82,7|80,28|10|2,6
6|2,8|4|6|0,7|2,6|43|84,7|82,19|10|2,6
6|2,8|4|6|0,7|2,6|44|86,6|84,1|10|2,6
6|2,8|4|6|0,7|2,6|45|88,5|86,01|10|2,6
6|2,8|4|6|0,7|2,6|46|90,4|87,92|10|2,6
6|2,8|4|6|0,7|2,6|47|92,3|89,93|10|2,6
6|2,8|4|6|0,7|2,6|48|94,2|91,74|10|2,6
6|2,8|4|6|0,7|2,6|49|96,1|93,64|10|2,6
6|2,8|4|6|0,7|2,6|50|98|95,55|10|2,6

The 3D model configuration of each plate wheel can be dynamically retrieved using a preset `Configuration table`.
The file name of the 3D model containing the `Configuration table` is **`Plate Wheel simplex 6x2,8.FCStd`**.

To obtain the 3D model of the desidered plate wheel, click the spreadsheet `Data` in the Tree View and then select the `Teeth Number` in the property editor. If nothing changes try to `Refresh` the model.

See the following image for details

![Drawing](../images/configuration.png "Configuration")

### Notes for developers
If you add a row in the `Configuration table` of the `Data` spreadsheet, then add that row in the above table of this `README.md` file, without the first cell.
