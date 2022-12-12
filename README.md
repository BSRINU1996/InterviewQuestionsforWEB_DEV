# InterviewQuestionsforWEB_DEV

20. How do you prevent an object to extend
    The Object.preventExtensions() method prevents new properties from ever being added to an object (i.e. prevents future extensions to the object). It also prevents     the object's prototype from being re-assigned.
    const object1 = {};

    Object.preventExtensions(object1);
    
19. What are various operators supported by javascript?

    In JavaScript, an operator is a special symbol used to perform operations on operands (values and variables).
    Assignment Operators
    
    =	Assignment operator	a = 7; // 7
    +=	Addition assignment	a += 5; // a = a + 5
    -=	Subtraction Assignment	a -= 2; // a = a - 2
    *=	Multiplication Assignment	a *= 3; // a = a * 3
    /=	Division Assignment	a /= 2; // a = a / 2
    %=	Remainder Assignment	a %= 2; // a = a % 2
    **=	Exponentiation Assignment	a **= 2; // a = a**2
    
    Arthamatic Operators
    +	Addition	x + y
    -	Subtraction	x - y
    *	Multiplication	x * y
    /	Division	x / y
    %	Remainder	x % y
    ++	Increment (increments by 1)	++x or x++
    --	Decrement (decrements by 1)	--x or x--
    
    Logival Operators..........
    &&	Logical AND: true if both the operands are true, else returns false	x && y
    ||	Logical OR: true if either of the operands is true; returns false if both are false	x || y
    !	Logical NOT: true if the operand is false and vice-versa.	!x
    
    Logical operators are used in decision making and loops.
    
    JavaScript Bitwise Operators 
    Bitwise operators perform operations on binary representations of numbers.Bitwise operators are rarely used in everyday programming. 
    
    ,	evaluates multiple operands and returns the value of the last operand.	let a = (1, 3 , 4); // 4
    ?:	returns value based on the condition	(5 > 3) ? 'success' : 'error'; // "success"
    delete	deletes an object's property, or an element of an array	delete x
    typeof	returns a string indicating the data type	typeof 3; // "number"
    void	discards the expression's return value	void(x)
    in	returns true if the specified property is in the object	prop in object
    instanceof	returns true if the specified object is of of the specified object type	object instanceof object_type.
