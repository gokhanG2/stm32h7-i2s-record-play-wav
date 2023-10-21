# stm32h7-i2s-record-play-wav
stm32h747i-disco record wav file to sd card and play recorded wav file by using i2s

In the stm32h747i-disco board;
- insert a FATFS SD Card and power on dev-board
- press Joystick Down button to start recording a Wav File (GREEN led will TURN ON)
- press Joystick Down button again to stop recording Wav File (GREEN led will TURN OFF)
- press Joystick Up button to play recorded Wav file (ORANGE led will TURN ON)

I2S pins;
- PA4: i2s1_ws
- PA6: i2s1_sdi
- PB3: i2s1_ck
- PD7: i2s1_sdo
