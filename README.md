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
