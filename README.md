# musickkk-keyboard
This keyboard is not just a musical instrument, its a musickkkk keyboard it gonna be sick!!, and this will be a midi keyboard, i will make my own Pcb and things for it!!
# Musickkk Keyboard

So basically, I made my own MIDI keyboard using a Waveshare ESP32-S3-Zero and designed the whole PCB from scratch in KiCad.

It has 7 copper touch keys arranged like a piano, 3 Kailh Choc switches, a rotary encoder, 2 slide potentiometers and 3 RGB LEDs. I wanted to make something that was actually mine, so I worked on my own layout and added my own silkscreen art.

# How it works

The 7 piano keys are just copper pads on the PCB. When I touch them, the ESP32-S3 detects the change in capacitance. Each key has its own GPIO pin and is meant to send MIDI notes over USB.

I also added 3 Choc switches for extra buttons, a rotary encoder and 2 sliders that can be used for things like volume and effects. The 3 RGB LEDs are on the back of the PCB and shine through holes in the board.

# Why I made it

I wanted to learn PCB design properly using KiCad, and I followed Kai Pereira's Hack Club MIDI keypad guide to get started. But I wanted to make my own version instead of just copying the original design.

I designed my own key layout, added the extra controls and worked on the silkscreen art too. This project helped me learn how the schematic, footprints, wiring and PCB layout all come together.

<img width="347" height="387" alt="image" src="https://github.com/user-attachments/assets/825b7f2f-ce8c-44bb-9ab6-33ac71f4eab2" />
<img width="404" height="281" alt="image" src="https://github.com/user-attachments/assets/bc080ec7-6247-4fa0-8241-6c099c1df189" />
<img width="632" height="232" alt="image" src="https://github.com/user-attachments/assets/31f180b0-7578-460d-83c5-996e96f4f6cf" />
<img width="375" height="256" alt="image" src="https://github.com/user-attachments/assets/8309ce9c-768f-4d19-9b2c-e21be6902c45" />
<img width="1035" height="717" alt="image" src="https://github.com/user-attachments/assets/d388f2d8-9924-46ab-9f66-64656e11e575" />
<img width="1350" height="796" alt="image" src="https://github.com/user-attachments/assets/de67e47c-8135-480f-863b-70464f4c4402" />
<img width="1118" height="791" alt="image" src="https://github.com/user-attachments/assets/b39b11d2-09f7-47c4-b803-2f36a11cdbda" />
<img width="881" height="478" alt="image" src="https://github.com/user-attachments/assets/e24e8f29-dbb6-488a-8633-121d6e2b59ff" />
<img width="1177" height="580" alt="image" src="https://github.com/user-attachments/assets/225e7a29-99cb-4e65-b5c2-84dffc88a8c6" />
<img width="1662" height="319" alt="image" src="https://github.com/user-attachments/assets/e66ea50b-5961-4d93-899d-9aecbb9e82bf" />
<img width="1101" height="985" alt="image" src="https://github.com/user-attachments/assets/2e8e9020-be82-4cd9-a63b-08718c9fcf95" />

