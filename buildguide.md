# Helix Build Guide

This guide walks through assembling one half of the Helix keyboard.  
Repeat the same steps for the other half.

> **Important:**  
> Helix uses a **reversible PCB**. The same PCB is used for both left and right sides.

---

## Assembly Order (Recommended)

### 1. Solder the MCU (nice!nano)

- Solder the **MCU face-down** onto the PCB.
- Make sure orientation is correct before soldering.
- **Do NOT solder the top row of MCU pins. Leave them unconnected.**
- Double-check pin alignment — fixing this later is painful.

---

### 2. Solder Small Components (Opposite Side)

On the **opposite side of where the MCU is soldered**, solder the following:

- Reset button
- Power slide switch
- Jumpers

⚠️ All of these **must be on the opposite side of the MCU**.

---

### 3. Solder the Battery

- The battery **+ and − pads are clearly labeled on the PCB**.
- You can use **any LiPo battery**, but:
  - Check the **battery slot size in the case STL** to ensure it fits.
- **Before soldering the battery**, set the power switch to **OFF**.

---

### 4. Solder Hot-Swap Sockets

- Solder all hot-swap sockets on the **opposite side of the MCU**.
- Make sure they sit flat — uneven sockets will cause switch fit issues.

---

## Case Assembly

### 5. Insert Hex Nuts

- Insert **4 × M2 hex nuts per side** into the bottom case.
- The fit is tight; adding **a small amount of adhesive** is recommended.
  - Epoxy works well.
  - Avoid blocking the screw holes.

---

### 6. Final Assembly

1. Place the PCB into the bottom case  
   - MCU should be on the **top side**
2. Place the top case
3. Insert **4 × M2 countersunk (CSK) screws**
4. Tighten evenly

---

### 7. Switches & Keycaps

- Insert switches
- Add keycaps

Repeat the entire process for the other half.

---

## Done

Flash firmware, pair the halves, and you’re good to go.
