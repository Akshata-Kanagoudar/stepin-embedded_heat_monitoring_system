# Test Plans

|  Test ID | Description  | Input  | Output  | Status |
|---|---|---|---|---|
| TID_01  | If driver seated, the user needs to enable the heater sensor  |Heater sensor switch closed| Heater sensor on| PASS  |
| TID_02  | Enabling button and heater sensor, LED will be ON  | Both switches closed| LED ON | PASS  |
| TID_03  | Enabling any one of sensor | Any one of switch open| 	LED OFF | PASS  |
| TID_04  | Reads temperature information from temperature sensor and convert analong inputs to digital using ADC |Read ADC from temperature sensor| Successfully read and covert digital values | PASS  |
| TID_05  | Display temperature value by showing PWM | Read ADC values |Successfully displayed temperature | PASS  |
| TID_06  | Display digital temperature values in serial monitor using USART | Read ADC values| Successfully displayed temperature | PASS  |
