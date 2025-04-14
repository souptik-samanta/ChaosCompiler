# Chaos Compiler 

A homebrew **CoreXY-Cartesian hybrid 3D printer** powered by passion, caffeine, and questionable life choices.

---

## 🚧 Design

- **Custom CoreXY** motion for lightning-fast prints  
- Z-axis? Let’s call it *Cartesian-ish* 💀  
- So technically… it’s a **Cortesian XYZ** 👀

---

## ⚙️ Features

- Blazing fast movement (thanks CoreXY!)
- Raspberry Pi 4 runs **Klipper** for precision and performance
- **Automatic multicolor printing** with a homebrew MMU
- **Auto print ejector** (yup, kicks prints off the bed)
- Big build volume: **310 × 310 × 380 mm**
- **Auto bed leveling** for a perfect first layer every time

---

## 🛠️ Mechanism

- CoreXY with **Alpha and Beta motors** working together to drive the X & Y axes fast and accurately  
  ![CoreXY Setup](https://github.com/user-attachments/assets/a7243b92-6a62-429e-857b-2abc0ea881ad)

- **Raspberry Pi 4** + Mainboard runs Klipper  
  ![Pi + Mainboard](https://github.com/user-attachments/assets/63fb2703-6142-405c-addb-55b013b764ea)

- **Multicolor Unit (MMU)**:
  - Stepper moves the filament selector rod
  - Servo presses the filament gear to feed the correct color
  - No buffer — relies on **filament sensors**  
  ![MMU](https://github.com/user-attachments/assets/e194372e-0d3c-43a0-b6ca-9d0f9ecf97a1)

- **Auto print eject**: A servo physically *yeets* the finished print off the bed

- **Cooling system**:
  - Front fan for hotend
  - Side fan for inside components  
  ![Hotend Cooling](https://github.com/user-attachments/assets/0bfb879b-00e8-42b1-a770-25ff2abe0873)

- **Build platform**:  
  - Large glass bed for smooth finish
  - **Auto bed leveling** calculated in firmware for no-stringing, perfect first layer

- **Structure**:
  - 2020 aluminum profiles for rigidity and wobble resistance  
  ![Frame](https://github.com/user-attachments/assets/db1553ec-8795-4c5c-9c11-a6e7c9b342ce)

- Easy filament access thanks to compact extruder + hotend proximity  
  ![Filament access](https://github.com/user-attachments/assets/fbbb5669-e08e-4016-a92b-0ec9aa149486)

---

##  Thought Process

- Went *as cheap as humanly possible* — sourced **everything within India**
- Realized: **India is expensive af** for hobby electronics
- Learned both **Cartesian and CoreXY** systems (aka double pain mode)
- 75+ hours of:
  - Mood swings
  - Debugging
  - Questioning existence
  - …and rebuilding anyway  
- Somehow didn’t rage quit  
- 10/10 would emotionally spiral again :dance_catgirl:

---

##  BOM & Docs

- 📄 **[BOM Sheet](https://docs.google.com/spreadsheets/d/1VOcx1vCP93SXvwvrw4UESpFi0AxCleXlYnAZV9N3jMY/edit?usp=sharing)**  
- 🛠️ **[Build Log](https://github.com/souptik-samanta/ChaosCompiler/blob/main/notes.md)**  
- ![BOM Screenshot](https://github.com/user-attachments/assets/dc984c80-3bb9-4fc6-a29b-69e23738e542)

---

##  CAD Files

- 🔩 [Single Hotend Assembly](https://a360.co/3FXtdJx)  
- 🖨️ [Complete Printer Model](https://a360.co/3G4sTc2)  
- ✖️ [XY Gantry Only](https://a360.co/426t92P)

---

##  Belts in Action

![Belts](https://github.com/user-attachments/assets/c2e7f595-6bf5-4305-a476-45951381735e)  
![with belts Belts](https://github.com/user-attachments/assets/3677386c-c424-4aaf-881b-214cb3d7efc7)

---

## 📸 PICS (MOAR)

![1](https://github.com/user-attachments/assets/6d9971ef-22b5-4dcb-ac71-665df1e11be7)  
![2](https://github.com/user-attachments/assets/3bd4bddb-f431-4881-84cd-83be45c938c4)  
![3](https://github.com/user-attachments/assets/8673f5e1-9688-495d-b3ad-59fc20479ba1)  
![4](https://github.com/user-attachments/assets/e642f240-1160-4d96-9e84-dd841f1435c5)  
![5](https://github.com/user-attachments/assets/8d863b76-50c6-4194-970c-554a28fc71a8)

---

##  Special Thanks

Huge shoutout to **Hack Club** and **Alex Ren** for the **Infill Grant** that funded this madness 💥  
Without y’all, *this printer would still be a scribble on a napkin*.

---

## ⚡ TL;DR

I solo-built a **CoreXY-Cartesian hybrid 3D printer**, dubbed **Chaos Compiler**, in India  
— with **automatic multicolor**, **auto print removal**, and **Klipper on a Pi 4** —  
on a *very cursed budget*.  

Specs?  
- **310×310×380mm**  
- **Fast AF** (CoreXY)  
- **Auto bed leveling**, **custom MMU**, and a servo that yeets your print off the bed.  

100% self-taught.  
Powered by **mood swings, caffeine, and pure spite**.

---
