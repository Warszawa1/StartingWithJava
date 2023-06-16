## StartingWithJava

Java was created in 1995, huge reach (enterprise development/backend).

Why Java?
- Java is a platform independent language.
- It is versatile, (WORA).
- It is stable, scalable, robust and fast.
- It is an object-oriented programming language and this makes it scalable and flexible.
- It is "easy" to learn. My previous languages have been Python and Javascript. I will be 
  able to confirm or not this statement in a few months.

****************************************************************************

04.06.2023
// Intro, How Java Made Portable (WORA), Main method, Statically vs Dynamically typed.

10.06.2023
// Data types, Type casting, Identifiers, Naming convention, Operators
   
   Primitive data types:
   # byte  ->   1 byte
   # char  ->   2 bytes
   # short ->   2 bytes
   # int   ->   4 bytes
   # float ->   4 bytes
   # double ->  8 bytes
   # long  ->   8 bytes
   # boolean -> true or false 
   -------------------------------------------------------------------------
   
   Implicit and explicit type casting:
   * implicit ->
     byte a = 45;
     double b;
     b = a;
     // We are trying to fit 1byte into a space for 8bytes, so it is possible.
        In case of doing the opposite double -> byte, the output will be an error, 8bytes will never fit in 1byte.
        For that we use the explicit type casting.
    * explicit ->
      double a = 45.5;
      byte b;
      b = (byte)a; // Change the behaviour of a to be stored into b, turning it into byte.
   -------------------------------------------------------------------------  
     
   Tricky pre, post operators:
   int a = 5;
   int c;
		c = a++;
		System.out.println(c);
		c = c + a--;
		System.out.println(c);
		c = c + --a;
		System.out.println(c);
		c = c + ++a;
		System.out.println(c);
		c = c + a++;
		System.out.println(c);
		c = c + ++a;
		System.out.println(c);
		c = c + --a;
		System.out.println(c);
  	c = a++ + a-- + --a + ++a + a++ + ++a + --a;
		    5   + 6   +   4 +   5 + 6   +   7 +   6
		System.out.println(c);
    // 38
    
    

11.06.2023
