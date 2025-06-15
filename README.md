# PT100 Library for TwinCAT3 (Beckhoff PLC)

This is a **PT100 temperature sensor library** designed for **TwinCAT3** and Beckhoff PLCs.  
It allows accurate temperature reading and filtering from RTD sensors (PT100) using analog resistance readings.

✅ Supports:
- Beckhoff PLCs with TwinCAT3

## 🔧 Features

- Ready-to-use `PT100_To_Celc_Converter` function
- Real-time temperature conversion
- Works with standard Resistance Measurement Terminal (e.g., EL3692)



## 🧪 Example Usage

PROGRAM MAIN
VAR
	rTemperature 		        : LREAL;
	rResistance			: LREAL;
	
END_VAR

rTemperature:=PT100_Calc(Resistance:=rResistance);

## 📥 Get the Full Library

👉 [Download the full PT100 Library on Gumroad](https://swoboda0.gumroad.com/l/bhwep?_gl=1*m6zjla*_ga*...)







