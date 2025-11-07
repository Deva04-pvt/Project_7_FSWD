&quot;Code Breaker – The Array Heist&quot;
�� Game Concept:
You are a hacker in training, trying to break into a secure system by manipulating a digital
code array. The vault’s password is hidden in a pattern within the array.
Your mission:
 Insert digits to build potential codes
 Delete wrong digits to fix mistakes
 Search for secret patterns (e.g., [2, 1, 4]) to unlock clues
 Crack the code before time runs out!
This game teaches: ✅ Insertion
✅ Deletion
✅ Linear Search for Subarrays (Pattern Matching)
✅ Array bounds and shifting logic
✅ Your Task:
Create an interactive &quot;Code Breaker&quot; game where the user manipulates a numeric array to
find a hidden password pattern.
Use HTML, CSS, and JavaScript to build:
 A visual array of digits
 Buttons for insert, delete, and search
 Animations for all operations
 Feedback messages and success effects
�� Game Features
1. Visual Array Display
 Show an array of 8–10 cells (divs) in a horizontal row
 Each cell holds a number (0–9) or is empty
 Example: [ 3 ][ 1 ][ 7 ][ ][ 2 ][ 1 ][ 4 ][ 9 ]
2. Operations Panel
Provide buttons and inputs:

Insert at Index Add a number at a given index; shift others right
Delete at Index Remove number at index; shift left
Search for Pattern Find a subarray (e.g.,[2, 1, 4]) in the array
Reset Clear the array
Inputs:
 Index: number input (0–9)
 Value: number input (0–9)
 Pattern: text input like 2,1,4
3. Animations

 Insert: Existing elements slide right; new number fades in
 Delete: Elements slide left; deleted number shrinks and fades
 Search: Highlights each segment of the array as it checks for the pattern
4. Feedback System
 Show messages like:
 &quot;Inserted 5 at index 3!&quot;
 &quot;Deleted element at index 2.&quot;
 &quot;Index out of bounds!&quot;
 &quot;Enter a valid pattern (e.g., 1,2,3)&quot;

EXTRA
1. Auto-Generate Secret Pattern
 On load, pick a random 3-digit pattern (e.g., [3,7,1])
 Player must insert digits to match it
 &quot;Level Complete!&quot; when found
2. Time Attack Mode
 Add a 60-second timer
 &quot;You cracked the code in 23 seconds!&quot; ��
3. Sound Effects
 Beep on insert
 Error buzz on invalid input
 Victory fanfare on unlock
4. Multiple Levels
 Level 1: Find any 2-digit pattern
 Level 2: Find a 3-digit pattern
 Level 3: Find a pattern in reverse order
