##  Design

- **custom CoreXY**
- ~+ an *unknown flavor* of Z-axis (let’s just call it *Cartesian-ish* 💀)~
- ~So yeah… it’s a **Cortesian XYZ**~

---

##  Features


- will be really fast(core xy)
- will use a pi 4 for its calcs and all
- automatic multicolor printing
- auto print remover
- Big 310 X 310 X 380
- Auto bed leveling
---
## Mechanism
- the core xy mech gives me a faster speed ..
- core xy with alpha and beta motors to move the print head with good accuracy and lightninh spped </br>
![image](https://github.com/user-attachments/assets/a7243b92-6a62-429e-857b-2abc0ea881ad)

- the pi 4 will be used to run klipper
- The pi 4 and the main board 
</br>![image](https://github.com/user-attachments/assets/63fb2703-6142-405c-addb-55b013b764ea)

- the mmu unit has one servo and a rod that will move all the extruder gears and the servo will move a rod that will press a filament gear againt the filament gear of the desired color when it presses over it the filament comes out there is no buffer so i am totally on filament sensors </br>

**</br>**
- the servo moves the upper rod and stepper moves the rod in with all the extruder gears.
- the bed is very big and a glass build plate 
- the bed leveling sensor will work and do the calculations in the firmware so the first layer is printed correctly and no stringing issue 
- the servo for auto print remove will turn on and push the print out and print removed .
- the hot end cooled with the fan on frond and the inside part with the fan on side </br>![image](https://github.com/user-attachments/assets/0bfb879b-00e8-42b1-a770-25ff2abe0873)
- the bed and ganrty connecte with the 2020 profile so the wobble is minimized </br>![image](https://github.com/user-attachments/assets/db1553ec-8795-4c5c-9c11-a6e7c9b342ce)
- accessing the filament wont be and issue as the extruder and the hot end it pretty close </br>![image](https://github.com/user-attachments/assets/fbbb5669-e08e-4016-a92b-0ec9aa149486)


##  Thought Process

I went *as cheap as humanly possible*, sourcing *everything* within India.  
Spoiler alert: **India is expensive af** when it comes to hobby electronics.  


---

##  The Crazy Part

I don’t even know how I stayed this dedicated.

We're talking:
- **75+ hours**
- **Multiple mood swings** (per day ig?)
- Learning **both Cartesian and CoreXY** systems  
(because why suffer once when you can suffer *twice*, right?)  
- Debugging, rebuilding, doubting my life choices, and then doing it again  
Maybe mood swings are underrated 😭  
They made me **learn two motion systems at once**.  
10/10 would emotionally spiral again :dance_catgirl:

---

##  BOM & Docs

- **BOM**: [New BOM Sheet](https://docs.google.com/spreadsheets/d/1VOcx1vCP93SXvwvrw4UESpFi0AxCleXlYnAZV9N3jMY/edit?usp=sharing)  
- **Build Log**: [GitHub Log](https://github.com/souptik-samanta/ChaosCompiler/blob/main/notes.md)  

BOM 
![image](https://github.com/user-attachments/assets/dc984c80-3bb9-4fc6-a29b-69e23738e542)

---
Thanks yo HACKCLUB and Alex Ren
Without them this would have nott been posible.
---
##  CAD Files

- [Single Hotend Assembly](https://a360.co/3FXtdJx)  
- [Complete Printer Model](https://a360.co/3G4sTc2)  
- [XY Gantry Only](https://a360.co/426t92P)

---

##  With the Belts:

![image](https://github.com/user-attachments/assets/c2e7f595-6bf5-4305-a476-45951381735e)

## With the Belts:

![image](https://github.com/user-attachments/assets/3677386c-c424-4aaf-881d-214cb3d7efc7)


---
# PICS (MORE PICSS)
![image](https://github.com/user-attachments/assets/6d9971ef-22b5-4dcb-ac71-665df1e11be7)
![image](https://github.com/user-attachments/assets/3bd4bddb-f431-4881-84cd-83be45c938c4)
![image](https://github.com/user-attachments/assets/8673f5e1-9688-495d-b3ad-59fc20479ba1)
![image](https://github.com/user-attachments/assets/e642f240-1160-4d96-9e84-dd841f1435c5)
![image](https://github.com/user-attachments/assets/8d863b76-50c6-4194-970c-554a28fc71a8)

---
## TL;DR

I built a **CoreXY-Cartesian hybrid 3D printer**  
with **manual tool changing**, **automatic multicolor**, and **auto eject**,  
all on a budget, in India,  
by myself,  
with caffeine, breakdowns, and vibes 

