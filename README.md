# first-repo
This is my First Repository.
I am Pooja Vankineni. I love Dogs.
My Favorite Breed is Golden Retriever and ShihTzu.

2.	(4 points) Write a simple function named calcProductAndRemainder which takes 2 parameters which are double values, 
a.	Calculate the product of two numbers.
b.	Calculate Remainder when first value is divided by second value.
c.	 Return both product and remainder which are double values. 

Answer :
func calcProductAndRemainder(num1: Double, num2: Double) -> (product: Double, remainder: Double) {
	var product = num1*num2;
	var remainder = num1%num2;
	return (product, remainder);
}

3.	(2 points) What is the error you found when you type the following source code in Playground? How you can fix it? You need to fix only in line #5. Copy and paste the correct code here
 
		let num1 : Int = 2
		let num2 : Double = 3.0
		let num3 : Float = 3.5
		var result : Double = 0.0
result = num1 + num2 + num3	

Answer :

	Error :  Cannot convert ‘Float’ and ‘Int’ type to ‘Double’
                         
           We can fix the error by changing line#5 to
           Result = Double(num1) + num2 + Double(num3);
![image](https://user-images.githubusercontent.com/89403383/155581863-6dc207d5-217b-46b2-919a-6597465075b5.png)

