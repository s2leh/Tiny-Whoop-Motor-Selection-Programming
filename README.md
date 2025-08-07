# Tiny Whoop Build And Motor Programming

1S-powered 65mm FPV drone for indoor/outdoor flying.

## Components
- **Frame**: BetaFPV Meteor65 Air  
- **FC**: BetaFPV F4 1S 5-in-1 (ELRS)  
- **Motors**: EX0802 19,000KV  
- **Props**: Gemfan 1610 40mm (1.0mm)  
- **Battery**: BT2.0 1S 450mAh  

## Setup
1. **Solder**:  
   - Motors to ESC pads (follow motor order diagram).  
   - BT2.0 connector to FC (replace PH2.0 if needed).  

2. **Betaflight**:  
   - Flash latest firmware.  
   - Motor tab: Verify spin direction (CW/CCW per diagram).  
   - BLHeli Suite: Reverse motors if needed.  

3. **Bind**: Hold FC bind button + power on.  

## Motor Diagram
##  Selected Motor
**Motor**: Brushless motor
**Model**: Happymodel EX0802 19,000KV (1S)  
**Why**:  
- Ultra-lightweight (1.8g)  
- Perfect for 65mm frames  
- Optimal 1S performance  

##  Motor Programming
1. **Connect**:  
   - USB to Betaflight Configurator  

2. **Test Spin Direction** (Props OFF!):

[1:CW] [2:CCW]

[3:CCW] [4:CW]


3. **Reverse Motors** (if wrong direction):  
- Use BLHeli Suite → Click "Reverse"  
