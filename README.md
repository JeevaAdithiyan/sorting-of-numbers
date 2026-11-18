JEEVA ADITHIYAN SK 212225060102
# sorting-of-numbers
## Aim
To write and execute an Assembly Language Program for sorting data in Ascending and  descending order using 8051 microcontroller on Keil software.
---

## Apparatus Required
- Personal Computer  
- Keil µVision software  
---

## Algorithm(ASCENDING ORDER)
1. Initialize the register **R7** with count (number of elements).  
2. Get the first two elements into two registers.  
3. Compare the two elements:  
   - If the value in register **R0** is lower, exchange **A** and **R0** data.  
   - Otherwise, increment pointer and decrement register **R7**.  
4. Check if **R7 = 0** → if yes, move the register **R0 & A**.  
5. Increment pointer and decrement **R7**.  
6. If **R7 ≠ 0**, repeat from Step 2.  
7. Otherwise, stop the program.  
---

## Program (Ascending order)



<img width="1050" height="820" alt="image" src="https://github.com/user-attachments/assets/fe0a7632-8a00-482e-9bc8-d756b7194297" />




## OUTPUT(Ascending order)


<img width="1078" height="1490" alt="image" src="https://github.com/user-attachments/assets/694ee3cd-c5d0-4452-b4fd-15895ded95a0" />

---

## Algorithm(Descending order)
1. Initialize the register **R7** with count.  
2. Get first two elements in two registers.  
3. Compare the two elements of data:  
   - If the value of **R0** register is high, then exchange **A** and **R0** data.  
   - Else, increment pointer and decrement register **R7**.  
4. Check if **R7 = 0**, then move the contents of **R0** and **A**.  
5. Again increment pointer and decrement **R7**.  
6. Check if **R7 = 0**:  
   - If **No**, repeat the process from Step 2.  
   - If **Yes**, stop the program.  
---
## Program (Descending order)



<img width="1079" height="938" alt="image" src="https://github.com/user-attachments/assets/b2864f8b-590c-4c1f-ad81-80c56a5181a9" />




## OUTPUT(Descending order)

<img width="1078" height="1490" alt="image" src="https://github.com/user-attachments/assets/e00c69a8-802c-41d6-aa40-f8d75fa1209e" />


---
## RESULT:
Thus the sorting of given data was done using 8051 keil software.

