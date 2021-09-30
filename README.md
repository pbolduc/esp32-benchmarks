# Benchmark Results


```
st:0x1 (POWERON_RESET),boot:0x13 (SPI_FAST_FLASH_BOOT)
configsip: 0, SPIWP:0xee
clk_drv:0x00,q_drv:0x00,d_drv:0x00,cs0_drv:0x00,hd_drv:0x00,wp_drv:0x00
mode:DIO, clock div:2
load:0x3fff0018,len:4
load:0x3fff001c,len:1044
load:0x40078000,len:10124
load:0x40080400,len:5828
entry 0x400806a8
�Speed Test will begin momentarily.


Speed test
----------
  digitalRead               : 0.192 us
  digitalWrite              : 0.187 us
  pinMode                   : 2.990 us
  multiply byte             : 0.041 us
  divide byte               : 0.045 us
  add byte                  : 0.041 us
  multiply integer          : 0.065 us
  divide integer            : 0.070 us
  add integer               : 0.065 us
  multiply long             : 0.040 us
  divide long               : 0.050 us
  add long                  : 0.040 us
  multiply float            : 0.045 us
  divide float              : 0.925 us
  add float                 : 0.045 us
  itoa()                    : 0.715 us
  ltoa()                    : 2.400 us
  dtostrf()                 : 12.800 us
  random()                  : 1.250 us
  y |= (1<<x)               : 0.078 us
  bitSet()                  : 0.078 us
  analogRead()              : 53.450 us
  digitalWrite() PWM        : 0.180 us
  delay(1)                  : 1000.000 us
  delay(100)                : 100000.000 us
  delayMicroseconds(2)      : 2.833 us
  delayMicroseconds(5)      : 5.963 us
  delayMicroseconds(100)    : 100.850 us
  sprintf_P                 : 4.900 us
  millis                    : 1.100 us
  micros                    : 0.750 us
  WiFi.localIP()            : 0.700 us
  WiFi.status()             : 0.100 us
  gettimeofday              : 16.250 us
  time                      : 16.600 us

```
