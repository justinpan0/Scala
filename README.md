# Scala

1. C++ differentiate between expressions (3+4) and statement (if-else), but in Scala, almost all constructs have valuse.

2. () is Unit value, which is a placeholder in Scala meaning "no useful value", similiar to void in C++.

3. Use :paste to enter expressions with line break.

4. Assignments return Unit value, and therefore cannot be chained togather like a=b=c

5. Functions that return the last expression as the value; if the last expression is an assignment, it will become a void function.

6. println and printf are both available.

7. The iterator in the for loop has no val or var.

8. To break, use break method in the Breaks object: import scala.util.control.Breaks._; Think of return as a kind of break statement for functions, and only use it when you want that breakout functionality.

9. With a recursive function, you must sepcify the return type: 
  def fac(n: Int): Int = if(n <= 0) 1 else n*fac(n-1)
  
