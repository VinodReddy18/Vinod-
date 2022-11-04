# which are divisible by 15 and multiple of 5, between 10 and 150
for i in range(10,150):
    if i%15==0 and i%5==0:
        print(i)
        
       
#print 100 prime numbers and you should print "Hey Bro done!" 
for Number in range (1, 101):
    count = 0
    for i in range(2, (Number//2 + 1)):
        if(Number % i == 0):
            count = count + 1
    if (count == 0 and Number != 1):
        print(Number)
print("Hey Bro done!")
