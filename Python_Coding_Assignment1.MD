#Basic 
for i in range(0,151,1):
    print(i)


#Multiples of Five   
for x in range(5,1000,5):
    print(x)

#Counting, the Dojo Way 
for x in range (1,101,1):
        if x % 10 == 0:
            print ('Coding Dojo')
        elif x % 5 == 0:
            print ('Coding')
        else:
            print(x)


#Whoa. That Sucker's Huge - Add odd integers from 0 to 500,000, and print the final sum.
sum = 0
for i in range(1,500000,2):
        sum +=i
        
print(sum)


#Countdown by Fours - Print positive numbers starting at 2018, counting down by fours.
for i in range(2018,-1,-4):
       print (i)
         

