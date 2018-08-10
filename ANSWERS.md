## Lab 9 Question Answers

Try using a `TreeMap` and a `HashMap` instead of `MyHashMap`.


        1. Are the resulting word frequencies any different?
       
                - There are no differences in word frequency.
                
        2. Is the time performance any different? If so, how would you rank the three implementations (in increasing order of time complexity)?
                - There is a diffeence in performance. I would rank the implementations in increasing ordr of time as follows: HashMap, MyHashMap, and finally TreeMap.
                
                - My Hash Map:

Run: time in ms: 694,

the=33278,
of=18013,
and=12845,
to=12450,
a=12449,
in=9386,
was=7788,
that=6601,
he=6202,
his=5529,

                - HashMap:


Run: time in ms: 661,

the=33278,
of=18013,
and=12845,
to=12450,
a=12449,
in=9386,
was=7788,
that=6601,
he=6202,
his=5529,




                - TreeMap:
Run: time in ms: 864,

the=33278,
of=18013,
and=12845,
to=12450,
a=12449,
in=9386,
was=7788,
that=6601,
he=6202,
his=5529,



       
    - How are `%` and `Math.floorMod` different? Which works more reliably for computing a hash table index?
    
    
  For the floorMod if the signs of the numbers you are trying to mod are the same then the result is the same a as the floor mod but if the signs are different then the result is different. The difference in values between floorMod and the % operator is due to the difference between floorDiv that returns the integer less than or equal to the quotient and the / operator that returns the integer closest to zero. The floorMod works more reliably when computing a hash table index.
        
        
    - What is the time complexity of `MyHashMap.size()`, and how could you make it much more efficient?
    
   O(n), n is the size of the table
    
    - How does this implementation compare to one where you would directly use your linked `Node` class from the earlier assignment? Answer briefly in terms of ease of implementation, correctness, reliability, and performance.
    
   The implementation on lab 9 was more difficult due to more written methods. Due to the map interface being implemented this lab is more reliable because the map interface is a java standard library and better tested making it more reliable and allowing the correctness to be better verified. The linked node lab had fewer methods and less complexity making it not as reliable or potentially correct as the MyHashMap. The linked node lab had better performance as it was O(1).

   
