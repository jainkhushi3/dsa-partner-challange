<!-- Practice Questions with Solutions -->
<!-- Ques1: Even Odd -->
START
INPUT n
IF(n % 2 == 0)
    PRINT even
ELSE
    PRINT odd
END

<!-- Question 2 : Take a name as input and print a greeting message for that name -->

START
INPUT name
    PRINT "Hello" + name + ", Welcome to DSA Challange"
END

<!-- Ques 3 : Simple Interest -->
START
INPUT p, r , t
CALCULATE si = (p * r * t) / 100
PRINT si

<!-- Ques 4 : Take 2 numbers and an operator (+, -, *, /) as input and calculate the result using if conditions -->
START
INPUT INT n1, n2
CHAR op = sc.next().charAt(0)
IF(op == '+')
    res = n1+n2
    PRINT res
ELSE IF(op == '-')
    res = n1-n2
    PRINT res
ELSE IF(op == '*')
    res = n1*n2
    PRINT res
ELSE IF(op == '/')
    IF(n2 != 0)
        res = n1/n2
        PRINT res
    ELSE
        PRINT "Divide by 0 not possible"
ELSE
    PRINT "Valid Operator"
END

<!-- Ques5. Take 2 numbers as input and print the largest -->
START
INPUT int n1, n2
IF(n1 > n2)
    PRINT n1
ELSE
    PRINT n2
END

<!--Ques6: Input an amount in Indian Rupees and convert it to USD. (Use: 1 USD = 83.5 INR — update with current rate) -->
START
INPUT inr
double usd = inr * 83.5
PRINT usd
END

<!-- Ques7. Print the Fibonacci Series up to n numbers -->
START
int a = 0
int b = 1
INPUT int n
int count = 2
while(count <= n)
    int temp = b
    b = b + a
    a = temp
    count++
PRINT b
END



