My project is a Runaway Alarm Clock named "Awake and Away"!
It is made with a core double-layer PCB.
Its functionality is that when its alarm goes off, the robot starts running away from the sleeper, who then must catch up to the robot and turn it off.
It is built with everything on the PCB, excluding the motors, which rest outside of it but connect back with a screw terminal connection.


<img width="825" height="551" alt="Screenshot 2026-10-11 143517" src="https://github.com/user-attachments/assets/7e51f49f-1bfd-4f39-b5f2-c196d9539b75" />
# Runaway-Alarm-Clock


Exact Features: 
- Display - showing if the alarm is on, the time, etc
- Motors - letting it run away
- Motor Drivers - telling the motors to "run away"
- Sound Module - pick up cues from surroundings, like clapping, to make it turn if it is about to hit something
- Screw terminals - to connect the motors to the motor drivers
- Capacitors - to smooth out voltage shifts
- Resistors - to make sure the PCB doesn't blow
- Buttons - to control the settings manually

// My PCB shows an extra 16 mHz crystal oscillator as a clock module, but I decided against it because it's extra - the ATmega32P-PU has those built in.

| Parts | Cost | Link |
| -- | -- | -- |
| PCB | 8.00 | |
|2 Pcs Motor | 6.19 | https://www.aliexpress.us/item/3256809774978860.html?spm=a2g0o.cart.0.0.520c38da8xtKTE&mp=1&pdp_npi=6%40dis%21USD%21USD+6.19%21USD+1.09%21%21USD+1.09%21%21%21%4021030f8317917624342064426e0ee1%2112000050700968151%21ct%21US%218281717048%21%211%210%21&_gl=1*zoysfe*_gcl_aw*R0NMLjE3OTE2NTIyNzguQ2owS0NRand4S2ZXQmhEa0FSSXNBTUt3a05icW9RblRFbk5DZDR6X2VfYlltY1FkNFVsM2Y0dmotM1BJRkpLb00yYU92V3F1Z0dzcVZIa2FBamlpRUFMd193Y0I.*_gcl_dc*R0NMLjE3OTE1MDk0ODMuQ2p3S0NBandfcHpXQmhBa0Vpd0F3RENpMVl2cmRuVUxlLXpHMmNIM0MwQUJwM2VpNk1HUF8xcjFBbGwtbDFpcmVYVDlER3pVOXMxZGhCb0NaQVlRQXZEX0J3RQ..*_gcl_au*NDQ2OTgwMTk3LjE3OTE1MDk0ODI.*_ga*MTY0ODg3ODgzOC4xNzkxNjgwNjE0*_ga_VED1YSGNC7*czE3OTE3NjE4NDUkbzYkZzEkdDE3OTE3NjI0MzYkajU0JGwwJGgw&gatewayAdapt=glo2usa |
| LM7805 | 1.74 | https://aliexpress.com/item/3256805383431284.html?spm=a2g0o.cart.0.0.520c38da8xtKTE&mp=1&pdp_npi=6%40dis%21USD%21USD%201.74%21USD%201.74%21%21USD%201.74%21%21%21%4021030f8317917624342064426e0ee1%2112000033591246615%21ct%21US%218281717048%21%211%210%21&_gl=1*17dlx5g*_gcl_aw*R0NMLjE3OTE2NTIyNzguQ2owS0NRand4S2ZXQmhEa0FSSXNBTUt3a05icW9RblRFbk5DZDR6X2VfYlltY1FkNFVsM2Y0dmotM1BJRkpLb00yYU92V3F1Z0dzcVZIa2FBamlpRUFMd193Y0I.*_gcl_dc*R0NMLjE3OTE1MDk0ODMuQ2p3S0NBandfcHpXQmhBa0Vpd0F3RENpMVl2cmRuVUxlLXpHMmNIM0MwQUJwM2VpNk1HUF8xcjFBbGwtbDFpcmVYVDlER3pVOXMxZGhCb0NaQVlRQXZEX0J3RQ..*_gcl_au*NDQ2OTgwMTk3LjE3OTE1MDk0ODI.*_ga*MTY0ODg3ODgzOC4xNzkxNjgwNjE0*_ga_VED1YSGNC7*czE3OTE3NjE4NDUkbzYkZzEkdDE3OTE3NjI0NjgkajIyJGwwJGgw |
| Atmega328P-PU | 3.08 | https://aliexpress.us/item/2251832638696075.html?spm=a2g0o.cart.0.0.520c38da8xtKTE&mp=1&pdp_npi=6%40dis%21USD%21USD%203.08%21USD%203.08%21%21USD%203.08%21%21%21%4021030f8317917624342064426e0ee1%2112000028582018063%21ct%21US%218281717048%21%211%210%21&_gl=1*rnk5gf*_gcl_aw*R0NMLjE3OTE2NTIyNzguQ2owS0NRand4S2ZXQmhEa0FSSXNBTUt3a05icW9RblRFbk5DZDR6X2VfYlltY1FkNFVsM2Y0dmotM1BJRkpLb00yYU92V3F1Z0dzcVZIa2FBamlpRUFMd193Y0I.*_gcl_dc*R0NMLjE3OTE1MDk0ODMuQ2p3S0NBandfcHpXQmhBa0Vpd0F3RENpMVl2cmRuVUxlLXpHMmNIM0MwQUJwM2VpNk1HUF8xcjFBbGwtbDFpcmVYVDlER3pVOXMxZGhCb0NaQVlRQXZEX0J3RQ..*_gcl_au*NDQ2OTgwMTk3LjE3OTE1MDk0ODI.*_ga*MTY0ODg3ODgzOC4xNzkxNjgwNjE0*_ga_VED1YSGNC7*czE3OTE3NjE4NDUkbzYkZzEkdDE3OTE3NjI1MjIkajYwJGwwJGgw&gatewayAdapt=glo2usa&_randl_shipto=US |
| Display | 5.45 | https://www.aliexpress.us/item/3256809598678660.html?spm=a2g0o.cart.0.0.520c38da8xtKTE&mp=1&pdp_npi=6%40dis%21USD%21USD+5.45%21USD+2.51%21%21USD+2.51%21%21%21%4021030f8317917624342064426e0ee1%2112000050148622938%21ct%21US%218281717048%21%211%210%21&_gl=1*1ipf4qt*_gcl_aw*R0NMLjE3OTE2NTIyNzguQ2owS0NRand4S2ZXQmhEa0FSSXNBTUt3a05icW9RblRFbk5DZDR6X2VfYlltY1FkNFVsM2Y0dmotM1BJRkpLb00yYU92V3F1Z0dzcVZIa2FBamlpRUFMd193Y0I.*_gcl_dc*R0NMLjE3OTE1MDk0ODMuQ2p3S0NBandfcHpXQmhBa0Vpd0F3RENpMVl2cmRuVUxlLXpHMmNIM0MwQUJwM2VpNk1HUF8xcjFBbGwtbDFpcmVYVDlER3pVOXMxZGhCb0NaQVlRQXZEX0J3RQ..*_gcl_au*NDQ2OTgwMTk3LjE3OTE1MDk0ODI.*_ga*MTY0ODg3ODgzOC4xNzkxNjgwNjE0*_ga_VED1YSGNC7*czE3OTE3NjE4NDUkbzYkZzEkdDE3OTE3NjI1NjckajE1JGwwJGgw&gatewayAdapt=glo2usa |
| 1x4 Connectors | 1.74 | https://www.aliexpress.us/item/2255800801798474.html?spm=a2g0o.cart.0.0.520c38da8xtKTE&mp=1&pdp_npi=6%40dis%21USD%21USD+1.71%21USD+1.71%21%21USD+1.71%21%21%21%4021030f8317917624342064426e0ee1%2110000013202368850%21ct%21US%218281717048%21%211%210%21&_gl=1*12ctxth*_gcl_aw*R0NMLjE3OTE2NTIyNzguQ2owS0NRand4S2ZXQmhEa0FSSXNBTUt3a05icW9RblRFbk5DZDR6X2VfYlltY1FkNFVsM2Y0dmotM1BJRkpLb00yYU92V3F1Z0dzcVZIa2FBamlpRUFMd193Y0I.*_gcl_dc*R0NMLjE3OTE1MDk0ODMuQ2p3S0NBandfcHpXQmhBa0Vpd0F3RENpMVl2cmRuVUxlLXpHMmNIM0MwQUJwM2VpNk1HUF8xcjFBbGwtbDFpcmVYVDlER3pVOXMxZGhCb0NaQVlRQXZEX0J3RQ..*_gcl_au*NDQ2OTgwMTk3LjE3OTE1MDk0ODI.*_ga*MTY0ODg3ODgzOC4xNzkxNjgwNjE0*_ga_VED1YSGNC7*czE3OTE3NjE4NDUkbzYkZzEkdDE3OTE3NjI2NDckajYkbDAkaDA.&gatewayAdapt=glo2usa |
| 12 mm buzzer | 1.97 | https://aliexpress.us/item/3256808603261098.html?spm=a2g0o.cart.0.0.a1f738daUVL7nA&mp=1&pdp_npi=6%40dis%21USD%21USD%201.97%21USD%201.97%21%21USD%201.97%21%21%21%40210311c217917669246332041e10e2%2112000046671331943%21ct%21US%218281717048%21%211%210%21&_gl=1*17nszhf*_gcl_aw*R0NMLjE3OTE2NTIyNzguQ2owS0NRand4S2ZXQmhEa0FSSXNBTUt3a05icW9RblRFbk5DZDR6X2VfYlltY1FkNFVsM2Y0dmotM1BJRkpLb00yYU92V3F1Z0dzcVZIa2FBamlpRUFMd193Y0I.*_gcl_dc*R0NMLjE3OTE1MDk0ODMuQ2p3S0NBandfcHpXQmhBa0Vpd0F3RENpMVl2cmRuVUxlLXpHMmNIM0MwQUJwM2VpNk1HUF8xcjFBbGwtbDFpcmVYVDlER3pVOXMxZGhCb0NaQVlRQXZEX0J3RQ..*_gcl_au*NDQ2OTgwMTk3LjE3OTE1MDk0ODI.*_ga*MTY0ODg3ODgzOC4xNzkxNjgwNjE0*_ga_VED1YSGNC7*czE3OTE3NjU0OTAkbzckZzEkdDE3OTE3NjcxODIkajYwJGwwJGgw&gatewayAdapt=glo2usa&_randl_shipto=US |
| Screw Terminals | 1.93 | https://www.aliexpress.us/item/2251832627770643.html?spm=a2g0o.cart.0.0.a1f738daUVL7nA&mp=1&pdp_npi=6%40dis%21USD%21USD+1.93%21USD+1.93%21%21USD+1.93%21%21%21%40210311c217917669246332041e10e2%2164664166305%21ct%21US%218281717048%21%211%210%21&_gl=1*1l3tlap*_gcl_aw*R0NMLjE3OTE2NTIyNzguQ2owS0NRand4S2ZXQmhEa0FSSXNBTUt3a05icW9RblRFbk5DZDR6X2VfYlltY1FkNFVsM2Y0dmotM1BJRkpLb00yYU92V3F1Z0dzcVZIa2FBamlpRUFMd193Y0I.*_gcl_dc*R0NMLjE3OTE1MDk0ODMuQ2p3S0NBandfcHpXQmhBa0Vpd0F3RENpMVl2cmRuVUxlLXpHMmNIM0MwQUJwM2VpNk1HUF8xcjFBbGwtbDFpcmVYVDlER3pVOXMxZGhCb0NaQVlRQXZEX0J3RQ..*_gcl_au*NDQ2OTgwMTk3LjE3OTE1MDk0ODI.*_ga*MTY0ODg3ODgzOC4xNzkxNjgwNjE0*_ga_VED1YSGNC7*czE3OTE3NjU0OTAkbzckZzEkdDE3OTE3NjcxODYkajU2JGwwJGgw&gatewayAdapt=glo2usa |
| Motor Drivers | 1.11 | https://www.aliexpress.com/item/3256805925483964.html?spm=a2g0o.cart.0.0.520c38da8xtKTE&mp=1&pdp_npi=6%40dis%21USD%21USD%201.11%21USD%201.11%21%21USD%201.11%21%21%21%4021030f8317917624342064426e0ee1%2112000043376584296%21ct%21US%218281717048%21%211%210%21&_gl=1*1hvz5m7*_gcl_aw*R0NMLjE3OTE2NTIyNzguQ2owS0NRand4S2ZXQmhEa0FSSXNBTUt3a05icW9RblRFbk5DZDR6X2VfYlltY1FkNFVsM2Y0dmotM1BJRkpLb00yYU92V3F1Z0dzcVZIa2FBamlpRUFMd193Y0I.*_gcl_dc*R0NMLjE3OTE1MDk0ODMuQ2p3S0NBandfcHpXQmhBa0Vpd0F3RENpMVl2cmRuVUxlLXpHMmNIM0MwQUJwM2VpNk1HUF8xcjFBbGwtbDFpcmVYVDlER3pVOXMxZGhCb0NaQVlRQXZEX0J3RQ..*_gcl_au*NDQ2OTgwMTk3LjE3OTE1MDk0ODI.*_ga*MTY0ODg3ODgzOC4xNzkxNjgwNjE0*_ga_VED1YSGNC7*czE3OTE3NjE4NDUkbzYkZzEkdDE3OTE3NjI4MTEkajYwJGwwJGgw |
| Sound Module | 1.11 | https://www.aliexpress.com/item/3256806851031376.html?spm=a2g0o.cart.0.0.520c38da8xtKTE&mp=1&pdp_npi=6%40dis%21USD%21USD%201.11%21USD%201.11%21%21USD%201.11%21%21%21%4021030f8317917624342064426e0ee1%2112000039176750370%21ct%21US%218281717048%21%211%210%21&_gl=1*1hvz5m7*_gcl_aw*R0NMLjE3OTE2NTIyNzguQ2owS0NRand4S2ZXQmhEa0FSSXNBTUt3a05icW9RblRFbk5DZDR6X2VfYlltY1FkNFVsM2Y0dmotM1BJRkpLb00yYU92V3F1Z0dzcVZIa2FBamlpRUFMd193Y0I.*_gcl_dc*R0NMLjE3OTE1MDk0ODMuQ2p3S0NBandfcHpXQmhBa0Vpd0F3RENpMVl2cmRuVUxlLXpHMmNIM0MwQUJwM2VpNk1HUF8xcjFBbGwtbDFpcmVYVDlER3pVOXMxZGhCb0NaQVlRQXZEX0J3RQ..*_gcl_au*NDQ2OTgwMTk3LjE3OTE1MDk0ODI.*_ga*MTY0ODg3ODgzOC4xNzkxNjgwNjE0*_ga_VED1YSGNC7*czE3OTE3NjE4NDUkbzYkZzEkdDE3OTE3NjI4MTEkajYwJGwwJGgw |
| Battery Holder | 2.46 | https://www.aliexpress.us/item/3256808766014997.html?spm=a2g0o.productlist.main.23.1fa23990JzMuR9&algo_pvid=96a97c00-f124-4a0d-a210-1f25c05df24e&algo_exp_id=96a97c00-f124-4a0d-a210-1f25c05df24e-22&pdp_ext_f=%7B%22order%22%3A%2248%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21USD%212.19%211.09%21%21%2114.57%217.24%21%402103129017917657108974859e0f40%2112000047340443536%21sea%21US%218281717048%21ABX%211%210%21n_tag%3A-29910%3Bd%3A1092fe7e%3Bm03_new_user%3A-29895%3BpisId%3A5000000218165385&curPageLogUid=gYoK0rpFsout&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005008952329749%7C_p_origin_prod%3A |
| Tax + shipping | 24.49 | -- |


<img width="1323" height="740" alt="image" src="https://github.com/user-attachments/assets/9746dd79-6f18-4824-9e17-9f7238e737cc" />

Wiring:
| Pin # | Connection 1 | Connection 2 |
| -- | -- | -- |
| Pin 1 | Switch 1 | Resistor |
| Pin 4 | Sound Unit Pin 1 | |
| Pin 5 | Motor Driver Pin 6 | |
| Pin 6 | Hour Switch | |
| Pin 7 | 100 nF Capacitor | +5V Rail |
| Pin 8 | GND Rail | |
| Pin 11 | Motor Driver Pin 5 | |
| Pin 12 | Motor Driver Pin 4 | |
| Pin 13 | Mode Switch | |
| Pin 14 | Minute Switch | |
| Pin 15 | Motor Driver Pin 3 |
| Pin 17 | Piezo Buzzer | |
| Pin 20 | +5V Rail | |
| Pin 22 | GND Rail | |
| Pin 23 | Sound Module Pin 4 | |
| Pin 27 | Display Pin 4 | |
| Pin 28 | Display Pin 3 | |
| Motor Driver Pin 7 | Motor A Terminal Pin 1 | |
| Motor Driver Pin 8 | Motor A Terminal Pin 2 | |
| Motor Driver Pin 9 | Motor B Terminal Pin 1 | |
| Motor Driver Pin 10 | Motor B Terminal Pin 2 | |
| Battery Connection Pin 1 | BAT+ Rail | 10uF Capacitor |
| Battery Connection Pin 2 | GND Rail | 10 uF Capacitor |
| Voltage Regulator Pin 1 | BAT+ Rail | |
| Voltage Regulator Pin 2 | GND Rail | 100nF Capacitor |
| Voltage Regulator Pin 3 | +5V Rail | 100 nF Capacitor |

