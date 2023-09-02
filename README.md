# Binary-test-Gda103
just a small test for school, learning python lol
this is the source code. 
from time import sleep
print('Hello, welcome to my binary converter test')
sleep(0.1)
print('--------')
print('--------')
sleep(0.4)
print('This is my second ever project as ive been studying python for 2 days and in between hours of work, so excuse me if the program breaks')
print('--------')
sleep(1)
print('This is based on the binary system which is the language in which computers read')
sleep(1)
print('From what I understand, so far, binary is read in columns from right to left, each column represents a function that works with the base of 2 multiplying by itself by the bases of 1-9')
print('-----')
print('-----')
sleep(2)
print('0,0,0,0,0,0,0,0,0')
sleep(2)
print('128,64,32,16,8,4,2,1')
sleep(1)
print('For example, the number 1 would be 01, if we were to write it in the 9 zeroed form it would be 000000001')
print('--------')
sleep(2)
print('2 would be 000000010 or 10 because its the second to last and we read from the right')
print('128 would be 100000000 as it is the first on the table mentioned above')
print('Getting a number like 131 would be done like this')
print('---------')
print('100000011')
sleep(1)
print('128 + 2 + 1')
print('128 is the first, then we have 0000000 which are the (64,32,16,8,4)which we are not using, then we have the last 2 ones, which would be translated as 2,1')
sleep(1)
print('I know this must be super confusing but you can test it out by yourself with this little thing i made')
print('If u still dont get it u can message me on discord @nikitas')
print('Here you go, have fun:)')
def binary_return(a):
    a=int(a)
    return bin(a).replace("0b","")
while True:
      a=input ('enter a decimal number between 1 and 255' )
      print(binary_return(a))
      answer =input('would you like to continue?')
      if answer == 'yes':
       continue 
      else: 
          break
