#Variables
fib1, fib2, fib3 = 1, 1, 0
fibArray = []
HighestValue = 4000000
total = 0

#Main Code
if __name__ == "__main__":

    #0(n)
    while fib3 < HighestValue:
        if fib3%2 == 0:
            fibArray.append(fib3)
            fib1 = fib2
            fib2 = fib3
            fib3 = fib1+fib2
        else:
            fib1 = fib2
            fib2 = fib3
            fib3 = fib1+fib2

    #0(n)
    for i in range(len(fibArray)):
        total+= fibArray[i]


    print(fibArray, total)
