PS C:\Users\USER\Documents\python> PS C:\Users\USER\Documents\python> & C:/Users/USER/AppData/Local/Programs/Python/Python313/python.exe c:/Users/USER/Documents/python/day_9/bittwise_not_.py
>> -13
>> PS C:\Users\USER\Documents\python> 

EXPLANATION:-

A=12
print(~A)

      0  0  0  0  1  1  0  0
 1st com

      1  1  1  1  0  0  1  1
      0  0  0  0  0  0  0  1   (+)
    -----------------------------
      1  1  1  1  0  0  1  0
    -----------------------------

    2nd com
    0 0 0 0 1 1 0 1

    1+4+8=-(12+1)=-13

EX 2:-



    PS C:\Users\USER\Documents\python> & C:/Users/USER/AppData/Local/Programs/Python/Python313/python.exe c:/Users/USER/Documents/python/day_9/bittwise_not_1_.py
-24
PS C:\Users\USER\Documents\python> 

           0 0 0 0 1 0 1 1 0
  1st com
        1 1 1 1 0 1 0 0 1
        0 0 0 0 0 0 0 0 1  (+)
     --------------------         
        1 1 1 1 0 1 0 0 1
     --------------------
     2nd com

     0 0 0 0 1 0 1 1 0

     2+4+17=-(23+1)=-24


     EPLANATION 3:-

     PS C:\Users\USER\Documents\python> & C:/Users/USER/AppData/Local/Programs/Python/Python313/python.exe c:/Users/USER/Documents/python/day_9/bit_not_2_.py
17
PS C:\Users\USER\Documents\python> 

        0 0 0 0 1 0 0 1 0
   1st comm

       1 1 1 1 0 1 1 0 1
       0 0 0 0 0 0 0 0 1   (+)
     ----------------------- 
       1 1 1 1 0 1 1 0 1
       --------------------

       2nd com

       0 0 0 0  1 0 0 1 0

       2+16=-(-18+1)=17

       explanation4:-
       PS C:\Users\USER\Documents\python> & C:/Users/USER/AppData/Local/Programs/Python/Python313/python.exe c:/Users/USER/Documents/python/day_9/bit_not_2_.py
            17
               PS C:\Users\USER\Documents\python>
              

              0 0 0 0 1 0 1 0 0
        1st com

             1 1 1 1 0 1 0 1 1
             0 0 0 0 0 0 0 0 1   (+)
             --------------------
             1 1 1 1 0 1 0 1 1
             --------------------
             2nd com
             0 0 0 0 1 0 1 0 0

             0+0+4+0+16=(-20-1)=19


             -19
PS C:\Users\USER\Documents\python> 


bin=10010

1st com


    1 1 1 1 0 1 1 0 1
    0 0 0 0 0 0 0 0 1  (+)
    -------------------
    1 1 1 1 0 1 1 0 1
    --------------------
    2nd com

    0 0 0 0 1 0 0 1 0

    2+16=--(18+1)=-19 




