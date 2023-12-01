# esphome_7_segment_display
A simple esphome yaml configuration for displaying time, date and weather on 4 MAX7219 7-Segment Displays
![PXL_20231201_024039865](https://github.com/Raining-Eye/esphome_7_segment_display/assets/89368249/bb3dc15a-a882-4f29-a501-3493c3eb9396)
# Instructions
1. Daisy chain 4 MAX7219 displays, and then wire them to your esp like the following:
- DIN to your mosi_pin (GPIO23)
- CS to your set cs_pin (GPIO5)
- CLOCK to your clock pin (GPIO18)
- VCC to +3.3 V
- GND to GND

2. Make necessary changes to the configuration for your situation

3. Upload and add device into HA
