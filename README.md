# KB-PRO board for KBIDE
This repository is official KB-PRO block and structure board for KBIDE. Build apon esp32-arduino and esp-idf platform with the board's static library that can access all sensor and GPIO in the board.
### Block mode
All block are compatible with arduino-esp32 platform but we provide extended block to easy to access onboard sensors and GPIO
- display -drawing display function
- gpio -add button state and read/write board IO
- sensor -access all board sensor
- music -sound control and synthesis onboard speaker

### Programming mode
All accessible functions are cited in **'include'**  folder, and all pin defination are compatibled with esp32-wrover module

### Schematic 
can be found in static folder

### License
MIT
