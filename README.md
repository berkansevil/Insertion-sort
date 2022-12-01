# Selection -sort
## Proje 1
**[22,27,16,2,18,6] -> Insertion Sort**

 **1 =Yukarı verilen dizinin sort türüne göre aşamalarını yazınız**

**2=Big-O gösterimini yazınız**

**3=Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız**

- Average case: Aradığımız sayının ortada olması
* Worst case: Aradığımız sayının sonda olması 
+ Best case: Aradığımız sayının dizinin en başında olması.  <br>

 **4= [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.**<br>
## Answer:  <br>
  **1=** <br>
 -  [2,27,16,22,18,6] -> 2 dizinin küçük sayısıdır, en başa alabilmek için 22 ile yer değiştirir. <br>
 -  [2,6,16,22,18,27] -> İkinci küçük sayı 6'dır ikinci sıraya almak için 27 ile yer değiştirir. <br>
 -  [2,6,16,18,22,27] -> Üçüncü sayı 16'dır, sıralaması doğru olduğu için herhangi bir değişiklik yapılmaz. Dördüncü sayı 18'dir ve sıralamaya uygun olması için 22 ile yer değiştirir <br> Beşinci ve altıncı sayı sıralamaya uygun olduğundan sıralamada herhangi bir değişiklik yapılmaz.<br> 
 -  **2=** <br>
 22,27,16,2,18,6] dizisinde 6 tane eleman vardır, yani 6 tane işlem yapılacaktır demektir. <br>
 - ilk adımda n-> 6 tane işlem, <br>
 - ikinci adımda en küçük elemanı (yani birinci) bulmak için (n-1)-> 6-1=5 tane işlem, <br>
 - Üçüncü adımda ikinci elemanı bulmak için (n-2)-> 6-2=4 tane işlem, <br>
 - Dördüncü adımda üçüncü elemanı bulmak için (n-3)-> 6-3=3 tane işlem, <br>
 - Beşinci adımda dördüncü elemanı bulmak için (n-4)-> 6-4=2 tane işlem yapılır. <br>
 - Altı elemanlı dizi olduğu için daha fazla işlem yapılmasına gerek yoktur çünkü son eleman altıncı elemandır. <br>
Bu algoritmada n+(n-1)+(n-2)+(n-3)+(n-4)+1 kadar işlem yapılır. Bu işlemin formülü: [n(n+1)]/2'dir. Bu formül sadeleştirilerek: (n²+n)/2 elde edilir. <br>
Big-O Notation'da kat sayı önemsizdir; yani domine eden fonksiyon n² alınır. <br>
Big-O değeri = O(n²) <br>

  **3=**<br>
Aradığımız sayı 18 dizinin ortasında olduğu için bu avarage case kapsamına girer. <br>
**4=**<br>
1. [2|3,5,8,7,9,4,15,6] 
2. [2,3|5,8,7,9,4,15,6] 3  
3. [2,3,4|7,9,5,15,6] 4  
4. 2,3,4,5,7,9,8,15,6] 
