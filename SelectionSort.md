## **PROJE 1**

**[22,27,16,2,18,6] Insertion Sort**  
**1.Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.**

>**Verilen diziye ait elemanlar sırayla kontrol edilir , küçükten büyüğe doğru sıralama işlemi devam ettirilir , sıralama bitince , işlem durur.**
>**a-) [2|27,16,22,18,6]**--> n işlem gerçekleştirildi.    
>**b-) [2,6|16,22,18,27]**--> n-1 işlem gerçekleştirildi.    
>**c-) [2,6,16|22,18,27]**--> n-2 işlem gerçekleştirildi.       
>**d-) [2,6,16,18,22,27]**--> n-3 işlem gerçekleştirildi ve sonucumuzu elde etmiş olduk.

**2.Big-O Gösterimini yazınız.**    
>n+(n-1)+(n-2)+(n-3)+…+1= n*(n+1)/2 --> O(n^2) (Not: Domine eden fonksiyon alınır, katsayılar önemsenmez.

**3.Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case’lerden hangisinin kapsamına girer? Yazınız**
>**Dizi de aranan 18 sayısı ortaya yakın bir yerde olması sebebiyle cevap Average case olmalıdır.  

**[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.**

>[2|3,5,8,7,9,4,15,6] --> n işlem gerçekleştirildi  
>[2,3|5,8,7,9,4,15,6] --> n-1 işlem gerçekleştirildi  
>[2,3,4|8,7,9,5,15,6] --> n-2 işlem gerçekleştirildi   
>[2,3,4,5|7,9,8,15,6] --> n-3 işlem gerçekleştirildi  


[Patika.dev](https://www.patika.dev/)
