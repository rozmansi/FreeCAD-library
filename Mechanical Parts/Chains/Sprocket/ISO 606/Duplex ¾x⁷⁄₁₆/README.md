# Chain Sprockets ISO606 duplex 3/4" x 7/16" from z 8 to z 95

This folder contains the 3D models of the sprockets for ISO 606 chains duplex 3/4" x 7/16" with number of teeth ranging from z=8 to z=95.

![Image](../images/duplex_screenshot.png "Sprocket Duplex")

The model is parametric and the values are contained in the spreadsheet `Data`.
The parameters refer to the sprocket dimensions as in the drawing below:

![Drawing](../images/duplex_drawing.png "Drawing")

### Table of dimensions in millimeters:

P (Pitch)|Wc (Chain width)|Dr (Roller diameter)|Tr (Tooth radius)|Rw (Radius width)|Wt1 (Tooth width 1)|Wt2 (Tooth width 2)|z (Number of teeth)|De (External Diameter)|Dp (pitch diameter)|d (Hub diameter)|D (Hole diameter)|H (Total height)
---|---|---|---|---|---|---|---|---|---|---|---|---
19,05|11,68|12,07|19|2|10,8|30,3|8|57,3|49,78|31|12|45
19,05|11,68|12,07|19|2|10,8|30,3|9|62|55,7|37|12|45
19,05|11,68|12,07|19|2|10,8|30,3|10|69|61,64|42|12|45
19,05|11,68|12,07|19|2|10,8|30,3|11|75|67,61|47|16|50
19,05|11,68|12,07|19|2|10,8|30,3|12|81,5|73,6|53|16|50
19,05|11,68|12,07|19|2|10,8|30,3|13|87,5|79,59|59|16|50
19,05|11,68|12,07|19|2|10,8|30,3|14|93,6|85,61|65|16|50
19,05|11,68|12,07|19|2|10,8|30,3|15|99,8|91,63|71|16|50
19,05|11,68|12,07|19|2|10,8|30,3|16|105,5|97,65|77|20|50
19,05|11,68|12,07|19|2|10,8|30,3|17|111,5|103,67|83|20|50
19,05|11,68|12,07|19|2|10,8|30,3|18|118|109,71|89|20|50
19,05|11,68|12,07|19|2|10,8|30,3|19|124,2|115,75|95|20|50
19,05|11,68|12,07|19|2|10,8|30,3|20|129,7|121,78|100|20|50
19,05|11,68|12,07|19|2|10,8|30,3|21|136|127,82|100|20|50
19,05|11,68|12,07|19|2|10,8|30,3|22|141|133,86|100|20|50
19,05|11,68|12,07|19|2|10,8|30,3|23|149|139,9|110|20|50
19,05|11,68|12,07|19|2|10,8|30,3|24|153,9|145,94|110|20|50
19,05|11,68|12,07|19|2|10,8|30,3|25|160|152|120|20|50
19,05|11,68|12,07|19|2|10,8|30,3|26|165,9|158,04|120|20|50
19,05|11,68|12,07|19|2|10,8|30,3|27|172,3|164,09|120|20|50
19,05|11,68|12,07|19|2|10,8|30,3|28|178|170,13|120|20|50
19,05|11,68|12,07|19|2|10,8|30,3|29|184,1|176,19|120|20|50
19,05|11,68|12,07|19|2|10,8|30,3|30|190,5|182,25|120|20|50
19,05|11,68|12,07|19|2|10,8|30,3|31|196,3|188,31|130|20|50
19,05|11,68|12,07|19|2|10,8|30,3|32|203,3|194,35|130|20|50
19,05|11,68|12,07|19|2|10,8|30,3|33|209,3|200,4|130|20|50
19,05|11,68|12,07|19|2|10,8|30,3|34|214,6|206,46|130|20|50
19,05|11,68|12,07|19|2|10,8|30,3|35|221|212,52|130|20|50
19,05|11,68|12,07|19|2|10,8|30,3|36|226,8|218,58|130|25|50
19,05|11,68|12,07|19|2|10,8|30,3|37|232,9|224,64|130|25|50
19,05|11,68|12,07|19|2|10,8|30,3|38|239|230,69|130|25|50
19,05|11,68|12,07|19|2|10,8|30,3|39|245,1|236,75|130|25|50
19,05|11,68|12,07|19|2|10,8|30,3|40|251,3|242,81|130|25|50
19,05|11,68|12,07|19|2|10,8|30,3|45|282,5|273,09|140|25|63
19,05|11,68|12,07|19|2|10,8|30,3|50|312,3|303,39|140|25|63
19,05|11,68|12,07|19|2|10,8|30,3|57|355,4|345,81|140|25|63
19,05|11,68|12,07|19|2|10,8|30,3|76|469,9|460,98|140|25|63
19,05|11,68|12,07|19|2|10,8|30,3|95|585,1|576,17|140|25|63

The 3D model configuration of each sprocket can be dynamically retrieved using a preset `Configuration table`.
The file name of the 3D model containing the `Configuration table` is **`Sprocket ANSI duplex ¾x⁷⁄₁₆.FCStd`**.

To obtain the 3D model of the desidered sprocket, click the spreadsheet `Data` in the Tree View and then select the `Teeth Number` in the property editor. If nothing changes try to `Refresh` the model.

See the following image for details

![Drawing](../images/configuration.png)

### Notes for developers
If you add a row in the `Configuration table` of the `Data` spreadsheet, then add that row in the above table of this `README.md` file, without the first cell.
