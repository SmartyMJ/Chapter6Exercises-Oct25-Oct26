Chapter6Exercises-Oct25-Oct26
=============================

Original + Continued (Completed Oct23 + Oct24)

The original exercises and the continued exercises. I originally tried to create a repository on my computer with just a .txt file, but it did not sync correctly. So I'm putting this one up.

SIX. 

    a) 0; it truncates to zero because they are both integers.

    b) 0; it truncates to zero because there is division of two integers.
    
    c) 5.0; the 1.0, which is a double (or float), makes the output a double (or float).
    
    d) 5.0; the 1.0, which is a double (or float), makes the output a double (or float).
    
    e) 3; the modulo function returns the remainder.


SEVEN. 

       a) 105; the function has a value of 105.8, but the int cast truncates it to 105.

       b) 19.0; both of the variables are integers, so the function truncates the result (19.6) to an integer (19) before making it a double (19.0).


EIGHT.

count += (total/pages - 5) * words - 1; I used the order of operations. I could remove four parentheses (two pairs).


NINE.

The console prints out "The travel distsnce is 0" because "1/2" truncates to 0. Change either the 1, the 2, or both to       a double (1.0 / 2, 1 / 2.0, or 1.0 / 2.0) to print out the correct result.


TWELVE.

temp should be declared as a double, not an int. If it is declared as an int, one number will be truncated towards 		zero.


THIRTEEN.
	
	int n;
		
	int hundreds = n / 100;     //number of hundreds that fit
	int tens = (n % 100) / 10;  //number of tens
	int ones = (n % 10);        //remainder of n divided by 10 (i.e. ones)
		
	System.out.println( (hundreds * 100) + (ones * 10) + (tens * 1) );


FOURTEEN.   

	    int dayOfWeek1; // 0=Sunday, 1=Monday, etc.
	    int day; // from 1 to 31, represents a day in january
				
	    int test = (day - 1) % 7 ;
	    System.out.println((test + dayOfWeek1) % 7); //what day of the week "int day" falls on


FIFTEEN.    

	int remainingMinutes = depHour * 60 + depMin - curHour * 60 - curMin; //time has to be in military time for this to work (i.e. 11:30pm = 11:30 and 1:15pm = 13:15)

	System.out.println((remainingMinutes / 60) + " hours and " + (remaingMinutes % 60) + " minutes.");


SIXTEEN.  

	  double meters = inches * 0.0254;
  	  double kilograms = lbs * 0.454;
  
  	  return kilograms/(meters * meters); //the block of code that should be added
