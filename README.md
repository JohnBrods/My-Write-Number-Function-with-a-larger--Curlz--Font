# My-Write-Number-Function-with-a-larger--Curlz--Font
C file as shown on YouTube.
This C file contains ALL functions to drive an ILI9341 8 bit display, no library required.
It contains a custom 'Write Number' function developed by me, John B and has been demonstrated on YouTube.
https://www.youtube.com/watch?v=Gmw92P38ffk
It is specifically for numbers since they constantly need updating. (unlike text).
I have just completed an up-date which automatically blanks number positions only if 'those positions' have been used.
It uses a 'Long to String' function, you do need a library for that in your own IDE.
Since a long can count to approximately 4.5 Billion, there are many 'switch cases'
The update now automatically excludes the 'switch case' if they are not required.
I demonstrated the 'write number' function in the above link and showed how one can easily change to any font of their choice.
I used a Pic32, the connections are in the C file, adjust to suit.
I hope this helps you.
Write a number once, no silly blanking after it has been written.
John B 3/06/2021
Feel free to donate a coffee in the link via YouTube.
