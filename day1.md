<!-- Practice Questions With PseudoCode -->

<!-- Ques1 : Leap Year -->
START
    INPUT year
    if ((year % 4 == 0) && (year % 100 != 0 || year % 400 == 0)) 
        PRINT Leap Year
    else
        PRINT Not a Leap Year
END

<!-- Ques2 : Sum of two numbers -->
START
    INPUT num1
    INPUT num2
    sum = num1 + num2
    PRINT sum
END

<!-- Ques3 : Multiplication Table -->
START
    INPUT num
    FOR i = 1 to 10
     result = num*i
     PRINT num 'x' i '=' result
    END FOR
END

<!-- Ques4: HCF and LCM -->
START
    INPUT num1, num2
    hcf = 0
    FOR i = 1 to num1
        if(num1 % i == 0 && num2 % i == 0)
            hcf = i
    PRINT hcf
    lcm = num1 * num2 / hcf
    PRINT lcm
END

<!-- Ques 5 :  SUM until x -->
START
    INT total
    WHILE true
        INPUT num
        IF num equals x
            break
        total += num
    PRINT total
        