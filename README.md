# All Eyes On You - HackNY '20

## Instructions 
* Run this command to build everything properly: `tweego -f sugarcube-2 -o aeou.html yjb-game`

## Explanation of Refactoring :)
Within the `yib-game` directory:
* each **scene** and the **intro** has its own folder 
* within the `scene` directory
    * choices - passage listing out available choices
    * long - options a & b
    * short - options a, b, c
    * scenario - passage explaining the situation

Within the `main.twee` file:
* `<<includes PASSAGE_NAME>>` - this will import the contents of the `.twee` file contain the specified passage

## Resources
* [SugarCube v2 Documentation](https://www.motoslave.net/sugarcube/2/docs/) - source of methods and tools for working with Twee, for example: `<<includes passageName>>`

## The Team
Cliff, Diane, Diana, Ian, Chiazo :)



