# patikadev-insertion-sort-project
Patika.dev Veri Yapıları ve Algoritmalar Dersi Selection Sort Projesi

[22,27,16,2,18,6]

Küçükten büyüğe sıralanırken ifadeler sırayla solundaki elemanla kıyaslanarak liste n-1 adımda sort edilir.

1. adım: 22 ve 27 kıyaslanır ve sıralama aynı kalır.
1=[22,27,16,2,18,6]

2. adım: 16, sırasıyla 27 ve 22 ile kıyaslanır ve her ikisinin de soluna yazılır.
2.1=[22,16,27,2,18,6]
2.2=[16,22,27,2,18,6]

3. adım: 2, sırasıyla 27,22 ve 16 ile kıyaslanır ve her üçünün de soluna yazılır.
3.1=[16,22,2,27,18,6]
3.2=[16,2,22,27,18,6]
3.3=[2,16,22,27,18,6]

4. adım: 18, sırasıyla 27,22 ve 16 ile kıyaslanır 27 ve 22'nin soluna, 16'nın sağına yazılır.
4.1=[2,16,22,18,27,6]
4.2=[2,16,18,22,27,6]

5. adım: 6, sırasıyla 27,22,18,16 ve 2 ile kıyaslanır 27,22 ve 18'in soluna, 2'nin sağına yazılır.
5.1=[2,16,18,22,6,27]
5.2=[2,16,18,6,22,27]
5.3=[2,16,6,18,22,27]
5.4=[2,6,16,18,22,27]

Sonuç olarak adımlar aşağıdaki şekildedir.

[22,27,16,2,18,6] > [22,27,16,2,18,6] > [22,16,27,2,18,6] > [16,22,27,2,18,6] > [16,22,2,27,18,6] > [16,2,22,27,18,6] > [2,16,22,27,18,6] > [2,16,22,18,27,6] > [2,16,18,22,27,6] > [2,16,18,22,6,27] > [2,16,18,6,22,27] > [2,16,6,18,22,27] > [2,6,16,18,22,27]

**Big O Notation = O(n2)**
