
Exp 5 Experimental verification of frequency response of Digital fiber optic link
# Digital Fiber Optic Link Analysis (600nm)

## AIM
To analyze the relationship between input and received signal of a 600nm fiber optic cable using digital link.

---

## EQUIPMENTS REQUIRED
- Fiber optic trainer kit ST 2502  
- Power supply  
- Patch cords  
- CRO (Cathode Ray Oscilloscope)  
- 660 nm fiber cable  

---

## THEORY

Fiber optic links can be used for transmission of digital as well as analog signals. A fiber optic link typically consists of three main elements:
- **Transmitter**: Converts the electrical input signal into optical (light) energy.
- **Optical Fiber**: Serves as the transmission medium for the light signal.
- **Receiver**: Converts the received light back into an electrical signal, preserving the original signal pattern.

---

## PROCEDURE

1. Connect the power supply to the board.  
2. Ensure that all switched faults are set to ‘Off’.  
3. Make the following connections:  
   a. Connect the 1 KHz square wave output to emitter 1's input.  
   b. Connect the fiber optic cable between emitter output and detector input.  
   c. Connect detector 1's output to comparator 1’s input.  
   d. Connect comparator 1's output to AC amplifier 1's input.  
4. On the board, switch emitter 1's driver to digital mode.  
5. Switch on the power.  
6. Monitor both the inputs to comparator 1 (TP13 & TP14). Slowly adjust the comparator's bias preset until the DC level on TP13 lies midway between the high and low levels of the signal on TP14.  
7. Observe the input to emitter 1 (TP5) and the output from AC amplifier 1 (TP28). Verify that both signals are identical.  
8. Vary the frequency between 10 Hz to 1 MHz and observe the output voltage for a constant input voltage of 5V.  
9. Calculate the bandwidth by determining the gain in decibels (dB).  

---

## BLOCK DIAGRAM

*(Insert block diagram here)*

---


## CONNECTION DIAGRAM  
**Setting up a Digital Link**


<img width="678" height="461" alt="Screenshot 2025-11-23 214511" src="https://github.com/user-attachments/assets/7fceb3eb-3872-4922-aabf-8f1b6898731c" />

---

## TABULATION  

<img width="540" height="697" alt="Screenshot 2025-11-23 214441" src="https://github.com/user-attachments/assets/6bce8a31-c475-4f8e-a59e-449ee1112d42" />

---

## MODEL GRAPH

<img width="562" height="747" alt="Screenshot 2025-11-23 214459" src="https://github.com/user-attachments/assets/d44bc85a-09a7-457d-bbee-3ae82daf2df2" />


---

## RESULT
Thus the experimental verification of frequency response of digital fiber optic link was studied and verified successfully.
