- 👋 Hi, I’m @abuzer1234   (cenk gumus - pikachu_p@aol.com).
            I am here to have social media presence to have a better chance of getting a coding job (I have no social media thing other than gitHub).

- 👀 I’m interested in all kinds of nerd stuff, because I am 'hardcore' nerd! (and I am PROUD to be a Nerd and intelligent!!!) (I can't call
          my-self a 'geek', because I am  socially-crippled.)

- 🌱 I’m currently learning Blockchain and DeFi.

- 💞️ I’m looking to collaborate on DeFi, Blockchain, Game development...   (I am betting on more than one horse, and if my efforts give 'fruit', I will change my name from Cenk Gumus to Bill Gates,jr.  - by the way, I admire Mr.Gates very much). 

- 📫 How to reach me :     you can e-mail me at pikachu_p@aol.com ,  text me or call me at +905548813305 (I would rather choose to be text on this number because the sound quality on my side is very low), and    whatsapp: +905449086486  (I would check this when it is about 10:00 am in New York).




//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////

// this is the three-line graphics programming example for beginners  (graphics programming only in 3 lines!)  
// it can be turned to an image viewer easily
// requires Turbo C++ to compile
// you have to select at least the 'Large' memory model on Turbo C++ if you want to run this code
// windows doesn't let you to assign values to the content of pointers, so it won't run on windows - only on MS-DOS
// this code is public domain (even the windows 2000 programming stuff is worthless now and this is much much older DOS stuff.)
// Notes:
// Turbo C++ doesn't accept the expression:      using namespace std;

#include <iostream.h>

void main(){

char *pc;                           // define a pointer to char
pc =  (char *) 0xb8000000;          // the pointer points to the beginning address of video buffer in RAM (this value is for color screens).
*pc = 64;                           // the character at the top left corner of the screen turns to @  ( which has the ASCII code decimal 64) 

int i;
cin >> i; 
}


// If you want to manipulate pixels instead of changing characters on the screen, you have to add these lines: 
// #include <DOS.h>             // this line is necessary to be able to call int86() function
//
//  union REGS in, out;
//  in.h.ah = 0;
//  in.h.al = 0x0d;            //this values (hexadecimal 0x0d) is for EGA mode (you may try to change this value to 0x13 to change the screen mode to VGA) 
//  int86(0x10, &in, &out);    //   calls the MS-DOS interrupt 0x10  which changes the graphics mode to EGA
// 
// 
// To change the color of top-left-most pixel, we assign the memory location 0xb800000 an arbirarily chosen value (as the value assigned to that specific memory location changes, the color of the pixel also changes). To change the color of the pixel next to the top-left-most pixel, you change the value of the of the value at the memory location 0xb80000001 (hexadecimal). And to change the color of the pixel to the right of it, you change the value of the address 0xb80000002 and so on...
//
// The lower 8-bit half of AX register (that is, AL) is assigned the value of 0x0d and when the int86() function calls the interrupt 0x10 the screen mode turns to EGA. If the 0x10th interrupt is called with the value of 0x13 (the interrupt is called after the lower half of AX register is assigned the value of 0x13) the graphics mode turns to VGA. In both cases the upper octet (i.e., 8-bit Byte) of AX register (i.e., AL) is stored the value of 0. In this VGA mode only 8 bits (one octet) of memory is used per pixel. 8-bits per pixel means that every pixel can show 2^8 different colors (256 different colors).  ++++++  
//
//
//  32bit and 24bit color depths are over-kill (as human eye can't tell the difference) but 16bit color depth is OK -  for even power-users. I even used to use my Pentium-166 with only 8bit color depth to make Windows more responsive (instead of 16bit color depth). 

// This code may contain little flaws - I don't claim that it is perfect. The Turbo C++ compiler may behave very differently from hardware to hardware, OS to OS and version to version (and I don't have time to try all these combinations).
//
// So, where from here? To go further in graphics programming you may:
//            1) study WIN32 API programming with recent tutorials (old books' codes' may not compile/run on windows 7/10/11 - some lines of the code may
//                have to be modified).
//            2) study 2D Open GL programming and pixel manipulation 
//            3) learn about the 3D geometry and programming
//
//
//
//
//
//
//
//  ***************** BONUS ******************* BONUS ************************ BONUS ******************** BONUS **********************
//   WINDOWS MACHINE-CODE PROGRAMMING EXAMPLE:     (if you don't do exactly what I say, you won't be able to get the expected results)
//   
//  1- 
//
//
//
//
//  THE ASSEMBLY equivalent:
//  
//  MOV AH,4Ch
//  INT 21H
//
//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////

If you have a lot of free time, then read on:

I first connected the Internet in 1996 from civil engineering computer lab of M.E.T.U. .  In those days decent computers were very expensive and we could only effort a monochrome CGA 8086 "computer" (the modems were very expensive, we didn't have a second line, phone calls were very costyly, ISP fees were high,etc  - so I couldn't log-on to the Internet from the comfort of my home). I never had online presence (not even a vanilla-HTML web page), mostly because of the fact that web sites were being hacked and de-faced (and I am a nerd which has hard time sociallizing , even online).   




my skills (for potential employers):

C         (30+ years)
C++       (20 years) (C++17)
Java
PHP
XML
UML
XAML
SQL
NoSQL    (1 year)
HTML
CSS
PYTHON
FLASK
WIN32 API
VB6.0
X86 ASSEMBLY
EXCEL
VBA
BASH
MATHEMATICA
Qt       (1 YEAR)
AUTOCAD
BLOCKCHAIN
OPEN GL




Q&A:

Q: 


<!---
 abuzer1234/abuzer1234 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
