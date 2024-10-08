![image](https://github.com/user-attachments/assets/34e3bd64-122e-4a50-b09c-0ea8a91dc743)# Data Representation 

# Number system

## Decimal System
A Base 10 system, using digits ranging from 0-9.

## Binary System
Base-2 number system                      
The basic unit of the number system
A number system that uses only two digits: 0 and 1 (on and off)
8 bits = 1 Byte
The computer CPU can simultaneously process a fixed number of bits.

<img width="825" alt="image" src="https://github.com/user-attachments/assets/ede040fe-92fb-4577-a0f7-0686f10f1808">

## Two's Complement For Negative Numbers
Two’s complement: A way to represent positive or negative integers in binary.
Steps:
- Write the integer in binary
- Flip all the digits (0 to 1; 1 to 0)
- Add 1
**MSB** (most significant bit) : left, bit position in binary numbers, If MSB is 1, it’s a negative integer, treat it as -128. Compute the rest as normal positive binary.
**LSB** (least significant bit) : right, gives the unit value

<img width="826" alt="image" src="https://github.com/user-attachments/assets/dd2135c7-4fb7-4388-a38e-8592c7b0e990">
(Example: how to represent -20 in two’s complement)

## Hexadecimal System
A base 16 number system
Use numbers 0-9 and A to F (0123456789ABCDEF)
Each hexadecimal: 4 binary digits

<img width="641" alt="image" src="https://github.com/user-attachments/assets/c14b7a11-c3a3-4a4d-9cc9-4542f133585c">

# Text Encoding

## String
Any set of words/letters
Use double quotes like: "Hello" 

## ASCII
(American Standard Code for Information Interchange)
-	Originally, seven bits, 128 unique characters
-	Extended (now), eight bits, 256 characters
Character map/character encoding:
![image](https://github.com/user-attachments/assets/091dd821-4604-4635-9a3a-f9817a2d45d9)

## Unicode
 (ASCII is within the Unicode)
 
-	16 bits per character, 65536 characters.
-	UTF-8 UTF-16 UTF-32

# Color Representation
Pixel is the basic unit of programmable color on a computer display
**Additive primary colors** (electronic display color): Red, green, blue (each have max 255)
- If you add 255 red, 255 green, 255 blue, you get white on the screen.
- If you add 0 red, 0 green, 0 blue, you get black on the screen.
- (coloring each pixels)
- example: In a 4 x 4 square, there is 16 pixels times 3 bytes (three color, each 1 bytes) = 48 bytes (file size)

**Lossless compression**
ran less coding
- Example: Add 7 before a color, the color repeats 7 times. If you add 7, you need to add 1 even it only repeat one times.
-	Fewer bytes (file size) needed to represent the same image.

**24-bit color depth** (True color)
-	Red: 8 bits (256 intensity level)
-	Green: 8 bits (256 intensity level)
-	Blue: 8 bits (256 intensity level)
Total 256 x 256 x 256 = unique colors


The color gradient is not smooth because the reduces of color
Adv: reduce the size, fast speed in transition. 


------------------------------------

***hello***

*Welcome* to my **first** ***CS e-Portfolio***

- [Bing](https://bing.com)
- item 2

<img width="200" alt="Mob" scr="https://github.com/user-attachments/assets/2ab70102-45b0-4fbe-b131-b0b4898947cd">




### hi

Hello!
