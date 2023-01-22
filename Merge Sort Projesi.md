# Proje 2

[16,21,11,8,12,22] -> Merge Sort

Yukarýdaki dizinin sort türüne göre aþamalarýný yazýnýz.

	Her adýmda parçaya ayýrarak tek parça kalana kadar bölüyoruz.
	[16,21,11,8,12,22]
	[16,21,11]   [8,12,22]
	[16] [21,11]   [8] [12,22]
	[16] [21] [11]   [8] [12] [22]
	Sýralama yapýp listeyi birleþtiriyoruz.
	[16] [11,21]   [8] [12,22]
	[11,16,21]   [8,12,22]
	[8,11,12,16,21,22]

Big-O gösterimini yazýnýz.

	Big-O = O(nlogn)