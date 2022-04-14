# **Proje 1**

- [22,27,16,2,18,6] -> Insertion Sort

- Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
- Big-O gösterimini yazınız.
- Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
- Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

- [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

## **Cevaplar**
---

- Insertion Sort ile sıralama yapılması için öncelikle en küçük sayı bulunmaya çalışılır. Bu sebeple ilk sayıdan (22) başlayarak en küçük sayı tek tek sorgulanarak aranır. "2" sayısı bulunduktan sonra en sol tarafa alınır. "2" sayısından sonra gelecek küçük sayı aranır. Bu şekilde sıralama devam eder.
- Insertion Sort türünde Big-O gösterimi O(n²) dir.
- [2,6,16,18,22,27] şeklinde sıralandıktan sonra 18 sayısı Average Case kapsamına girmektedir.

- 1.adım [2,7,3,5,8,9,4,15,6] 2.adım [2,3,7,5,8,9,4,15,6] 3.adım [2,3,4,7,5,8,9,15,6] 4.adım [2,3,4,5,7,8,9,15,6] şeklinde olur.