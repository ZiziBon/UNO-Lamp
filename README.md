# UNO-Lamp
UNO&amp;Lamp one of my first project where i was forced to think outside the guiding tutorials or limits of Arduino sets. It is one first project when non Arduino component was used.

#Reasons
I understood that most of my project were not a full project, only build using Arduino and Basic tool kit, which forced me to narrow my project construction and planning, however after deciding to add a used camera tripod as a carcass to my lamp which can be turned by simple button push, it might look simple but for me it's totally different starting from planning to adding external components.

##Info UNO-Lamp

turned an old camera tripod into an adjustable desk lamp using an arduino and some leds. 

got tired of just building random circuits on a breadboard that don't actually do anything useful, so I wanted to try integrating electronics with actual hardware.

## pics
- `v1`: initial setup testing the tripod mount with an hc-sr04[cite: 1]
- `v2`: final build with the leds, button at the bottom, and zip-tied wires[cite: 2]

## how it works
- **hardware:** photo tripod, arduino nano, vertical led strip, push button, zip ties.
- **button placement:** put the button near the bottom of the board on purpose. if you press it near the top, the tripod head tilts. putting it lower keeps the whole thing steady when turning it on/off[cite: 2].
- **code:** simple c++ sketch using `millis()` for button debounce and pwm for dimming.

## what I learned
making this in a day was a good reality check. it works, but taping a breadboard to a tripod shows the limits of prototyping on the fly[cite: 1, 2]. 

it made me realize I can't just eyeball physical builds if I want to make cleaner systems, which forced me to start learning autodesk inventor for cad modeling. this was basically the main bridge before I started working on my robotic arm.

## how to run
just upload dropped files (Two options available, C++ and INO). make sure to power the leds from an external 5v supply, not directly off the nano.

<img width="960" height="1280" alt="photo_2026-09-26_22-36-53" src="https://github.com/user-attachments/assets/a23e6f41-34a6-4128-8873-cf974016f848" />
<img width="960" height="1280" alt="photo_2026-09-26_22-37-04" src="https://github.com/user-attachments/assets/7b436262-0071-4cd4-892f-0225da153ee2" />

##Construction Video


https://github.com/user-attachments/assets/1a0ecd32-8aaa-4b49-b281-3cf935e99249
https://github.com/user-attachments/assets/97bcbdd4-cf89-4346-85b9-28f3bb671d4b


