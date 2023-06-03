# InsertionSort
InsertionSortProject

Insertion Sort, basit ve yaygın olarak kullanılan bir sıralama algoritmasıdır. Adından da anlaşılacağı gibi, bu algoritma elemanları doğru konumlarına "yerleştirerek" bir diziyi sıralar.

Insertion Sort'un çalışma mantığı şu şekildedir:

1) Dizi, ikiye ayrılan bölümlerden oluşur: sıralanmış bölge ve sıralanmamış bölge. Başlangıçta sıralanmış bölge boştur ve sıralanmamış bölge tüm diziyi içerir.

2) Sıralanmamış bölgenin ilk elemanı sıralanmış bölgenin sonundaki elemanlarla karşılaştırılır.

3) Karşılaştırma yapılarak, sıralanmış bölgedeki uygun konum belirlenir ve eleman doğru konumuna yerleştirilir. Bu işlem, sıralanmış bölgenin sonundan başlayarak geriye doğru yapılır.

4) Sıralanmamış bölgenin bir sonraki elemanı sıralanmış bölgenin sonundaki elemanlarla karşılaştırılır ve uygun konuma yerleştirilir.

5) Bu işlem, sıralanmamış bölgedeki tüm elemanlar sıralanmış bölgeye yerleştirilene kadar tekrarlanır.

Sonuç olarak, sıralanmış bölge her adımda bir eleman daha büyürken sıralanmamış bölge küçülür. Tüm elemanlar sıralanmış bölgeye yerleştirildiğinde, dizi sıralanmış hale gelir.

Insertion Sort algoritması, küçük boyutlu dizilerin sıralanmasında etkili bir şekilde çalışır. Ancak büyük boyutlu dizilerde zaman karmaşıklığı O(n^2) olduğu için verimlilik açısından diğer algoritmalara göre daha yavaş olabilir.

Insertion Sort, basit ve yaygın olarak kullanılan bir sıralama algoritmasıdır. Adından da anlaşılacağı gibi, bu algoritma elemanları doğru konumlarına "yerleştirerek" bir diziyi sıralar.

[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

[22,27,16,2,18,6] -> Insertion Sort Aşamaları:

Adım 1: [22, 27, 16, 2, 18, 6]
Adım 2: [16, 22, 27, 2, 18, 6]
Adım 3: [2, 16, 22, 27, 18, 6]
Adım 4: [2, 16, 18, 22, 27, 6]
Adım 5: [2, 6, 16, 18, 22, 27]
