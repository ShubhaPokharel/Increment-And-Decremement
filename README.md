# Java Increment and Decrement Operator


“The operator (++) and the operator (--) are Java's increment and decrement operators.”  They are used to increase and decrease the value. Increment and decrement are both part of the Unary Operators. Increment means increase and decrement means decrease.


The increment operator adds one to its value, but the decrement operator subtracts one from its value( decrements its value by 1). Then it will return the value.

Ex:

The current value is 12.

We can do  ‘++12’  and it will increase by one. So, the value will be 13.


There are two types of Increment: 


 ## Pre Increment

The syntax of  Pre Increment is: ++variable;

Pre Increment means we increase now, we increment it now. It increases before the value gets generated.




## Post Increment

The syntax of  Pre Increment is: variable ++;

It takes only the current value but we increment will go for the next time. The initial value is used, then after the compiler generates the initial value it increases one value.


There are two types of Decrements:


## Pre Decrement

The syntax of  Pre Decrement is: -- variable ;

Pre Decrement means we decrease it now, it decreases now. It decreases before the value gets generated.


## Post Decrement


The syntax of  Pre Decrement is:  -- var;


It takes only the current value but the next statement it decreases. The initial value is used, then after the compiler generates the initial value it decreases one value.


Example of Increment and Decrement: 

class Test{ 

	public static void main(String[] args)
 
	{	int num = 4; 
 

		System.out.println(++num); // 5
  
    System.out.println(num++);	 // it is 5 but since it is post increment it will be 6
    
		System.out.println(--num); // 5
  
		System.out.println(num--);  //5 but since it is post decrement  it will be 4
  
     
	}
 
}

______________

Increment and Decrement can not be applied on final variables, because we can’t change the value. It can not be applied for booleans. It does not work for Strings or doubles.





