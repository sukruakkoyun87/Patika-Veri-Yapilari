# Proje 1

## [22,27,16,2,18,6] -> Insertion Sort

1. **Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.**|   |   |

	1.[22,27|16,2,18,6] -> n [ Bu Adımda 22 27 'den büyük oldugu için işlem yapılmaz]
	2.[16,22,27|2,18,6] -> n-1
	3.[2,16,22,27|18,6] -> n-2
	4.[2,16,18,22,27|6] -> n-3
	5.[2,6,16,18,22,27] -> n-4


  2.**Big-O gösterimini  : 0(n^2)**


  3.**Time Complexity**

  - Time Complexity: n^2
  - Average case: 18
  - Worst case: 27
  - Best case: 2

4.**Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer?**

- Average case: 18



5.**[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.**

-[7,3,5,8,2,9,4,15,6]

-[3,7,5,8,2,9,4,15,6]
-[3,5,7,8,2,9,4,15,6]
-[2,3,5,7,8,9,4,15,6]
-[2,3,4,5,7,8,9,15,6]