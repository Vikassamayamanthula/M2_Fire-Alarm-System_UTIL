
#
Test cases
#
| Test ID | Description | Input | Expected output | Actual Output | Passed Or Not |
| --- | --- | --- | --- | --- | --- |
| 01 | Potentiometer(0 to 1024) | value < 200 | fire not detected | fire not detected | ✅ |
| 02 | Potentiometer(0 to 1024) | value >200 | fire is detected | fire detected | ✅ |
| 03 | servo motor | fire is detects | Door Opens | Door Opens | ✅ |
| 04 | servo motor | fire is not detects | Door Closes | Door Closes | ✅ |
| 05 | LED | fire detects | Light On  | Light On  | ✅ |
| 06 | LED | fire is not detects | Ligh  Off | Light off) | ✅ |
| 07 | lcd display | fire detects | fire detecteed !!! | fire detected !!! | ✅ |
| 08 | lcd display | fire not detects | you are safe | you are safe | ✅ |
| 09 | buzzer | fire detects| sound on | sound on | ✅ |
| 10 | buzzer | fire not detects | sound off | sound off | ✅ |
#

### Circuit implementation
![outsim](https://user-images.githubusercontent.com/98829237/156992756-abed7fb7-a94b-4875-b96d-bdd1d976bda3.jpeg)
#
![outsim2](https://user-images.githubusercontent.com/98829237/156992933-87eaec44-0378-4f61-910b-d285d6f29a9d.jpeg)
