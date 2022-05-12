# 💻Square root calculator

Square root calculator to any degree of accuracy.

```
Enter number : 48954351

Enter precision : 1000

Square root is : 
6996.7385973752085002225515172666342473918920191250670476585401733211290939405961906588891641037857735306

```

<details>
  <summary>Extreme example</summary>
  
```
Enter number : 2784297492593459234659296594287695769024067094769437659037690537960791000000004285257862485

Enter precision : 999

Square root is : 
1668621434775862884564065050432411033958259093.623019343246406307303615964018638699243566762952297348840182976738661801056677936763372320823517302288703250387471369354659143660021995315567526018524770456841438679149495049772379076123845778904526682277987707662602658487897243975982649770921080251669802661066685005410061487546437932161697766838372988246613473444310619869641152547602828925099047653442980469551303933375843772690469088245443934132415949102993488853826610487700894621614939411620812332454053253132913248470762707404274799125630156656329526421948726602675809575170776229610612352973299031605367872627226342613523407952044543822898437865108204111113546820574595383328232754752327781789510293481136282488383684398385255523234835661624012398067342274821466030934873366777156917090532046732061228163545766035715798275016140916194370952592949679626790679279643479777659555171748331762332332901203823854132440606769254675476962631538334793561088985557223699815470580693103843904215514218383795596683786252543715964198982383495658908347751
  
 ```
</details>

# ⭐Features #
- Calculator takes a string as argument so the square root of numbers larger than 2^32 can be calculated.
- Precision of answer can be varied.

# 📰Explanation #
Long division is used to calculate square root. 

Explanations of the method can be found here :

https://xlinux.nist.gov/dads/HTML/squareRoot.html

https://www.geeksforgeeks.org/long-division-method-to-find-square-root-with-examples/

# ⏰ Time and space complexity #
Time complexity : O(n^2)

Space complexity : O(n)

