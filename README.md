# Algoritma-Insertion-Sort

1)
	a)  [22,27,16,2,18,6] →  Insertion Sort					
					
		1.	[22,27]	→	indis[1] 27 ile 22 karşılaştırılır, 22 küçük olduğu için yer değiştirmez.   → [22,27,16,2,18,6]
		2.	[27,16]	→	27 ile 16 karşılaştırılır, 16 küçük olduğu için yer değiştirir.	            → [22,16,27,2,18,6]
		3.	[16,22]	→	16 ile 22 karşılaştırılır, 16 küçük olduğu için yer değiştirir.	            → [16,22,27,2,18,6]
		4.	[27,2]	→	27 ile 2 karşılaştırılır, 2 küçük olduğu için yer değiştirir.	            → [16,22,2,27,18,6]
		5.	[2,22]	→	2 ile 22 karşılaştırılır, 2 küçük olduğu için yer değiştirir.	            → [16,2,22,27,18,6]
		6.	[2,16]	→	2 ile 16 karşılaştırılır, 2 küçük olduğu için yer değiştirir.	            → [2,16,22,27,18,6]
		7.	[27,18]	→	27 ile 18 karşılaştırılır, 18 küçük olduğu için yer değiştirir.	            → [2,16,22,18,27,6]
		8.	[18,22]	→	18 ile 22 karşılaştırılır, 18 küçük olduğu için yer değiştirir.	            → [2,16,18,22,27,6]
		9.	[27,6]	→	27 ile 6 karşılaştırılır, 6 küçük olduğu için yer değiştirir.	            → [2,16,18,22,6,27]
		10.	[6,22]	→	6 ile 22 karşılaştırılır, 6 küçük olduğu için yer değiştirir.	            → [2,16,18,6,22,27]
		11.	[6,18]	→	6 ile 18 karşılaştırılır, 6 küçük olduğu için yer değiştirir.	            → [2,16,6,18,22,27]
		12.	[6,16]	→	6 ile 16 karşılaştırılır, 6 küçük olduğu için yer değiştirir.	            → [2,6,16,18,22,27] 
					
			Dizi sıralanmıştır.	→	 [2,6,16,18,22,27]

	![image](https://github.com/ertecino/Algoritma-Insertion-Sort/assets/147555058/085e95a7-cf5a-41e6-be8b-d0627e6c0768)


	b) Insertion Sort zaman karmaşıklığı O(n^2)'dir.

	c) Dizi sıralandıktan sonra 18 sayısı Average case durumu kapsamındadır.


2)     [7,3,5,8,2,9,4,15,6] → Selection Sort

   			SIRALI BÖLÜM	SIRALANMAMIŞ BÖLÜM				
		1.	[2]		[3,5,8,7,9,4,15,6]				
		2.	[2,3]		  [5,8,7,9,4,15,6]				
		3.	[2,3,4]		    [5,8,7,9,15,6]				
		4.	[2,3,4,5]	      [8,7,9,15,6]	→	4. Adımda dizinin durumu	→	[2,3,4,5,8,7,9,15,6]
		5.	[2,3,4,5,6]		[8,7,9,15]				
		6.	[2,3,4,5,6,7]		  [8,9,15]				
		7.	[2,3,4,5,6,7,8]	            [9,15]				
		8.	[2,3,4,5,6,7,8,9]	      [15]				
		9.	[2,3,4,5,6,7,8,9,15]
   		
	![image](https://github.com/ertecino/Algoritma-Insertion-Sort/assets/147555058/37a0fb4e-8da2-4f52-8f8e-9772147212d9)
