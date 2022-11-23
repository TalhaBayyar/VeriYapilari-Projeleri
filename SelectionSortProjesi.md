 <h1>Proje 1</h1>
 
 <h2> Insertion Sort

 [22,27,16,2,18,6] -> Insertion Sort
</h2>
  <h3>1) Yukarı verilen dizinin sort türüne göre aşamalarını yazınız. </h3>
  <br>

1. [22,27,16,2,18,6] -> 22<27 22 dizinde 27 'den küçük olduğu için 22,27 şeklinde sıralanır. <br>
2. [22,27|16,2,18,6] -> 16<27, 16<22 16 dizinde 22, 27 'den küçük olduğu için 16,22,27 şeklinde sıralanır. <br>
3. [16,22,27|2,18,6] -> 2<27, 2<22, 2<16 2dizinde 16, 22, 27 'den küçük olduğu için 2,16,22,27 şeklinde sıralanır. <br>
4. [2,16,22,27|18,6] -> 18<27, 18<22, 16<18 18dizinde 22,27 'den küçük 2,16'dan büyük olduğu için 2,16,18,22,27 şeklinde sıralanır. <br>
5. [2,16,18,22,27|6] -> 6<27, 6<22, 6<18, 6<16 2<6 6dizinde 16,18,22,27 'den küçük 2'den büyük olduğu için 2,6,16,18,22,27 şeklinde sıralanır.<br>
6. [2,6,16,18,22,27]<br><br>


<h3>2) Big-O gösterimini yazınız. </h3><br>
<h4>Dizideki eleman sayısı n olsun. Big-O yöntemine göre sıralama yapılırken işlem sayısı da n olur. Son işlem sayısı 1 olana kadar devam eder.</h4><br>

<ul>
    <li>Insertion Sort algoritması n elemanlı bir listede, ikinci eleman için en fazla 1 karşılaştırma ve 1 yer değiştirme yapar.</li>
    <li>Üçüncü eleman için 2 karşılaştırma ve 2 yer değiştirme, dördüncü eleman için 3 karşılaştırma ve 3 yer değiştirme yapar. Bu şekilde son eleman için en fazla n-1 karşılaştırma ve n-1 yer değiştirme yapar.</li>
    <li>Listedeki bütün elemanlar için yapılan karşılaştırmaların ve yer değiştirmelerin toplamı 2(1+2+3+4+...+(n-2)+(n-1))=2(n(n-1)/2)=n(n-1) yapar.</li>
    <li>Hesaplamalar sonucunda elde edilen n(n-1) değerinin asimptotik üst sınırı O(n²) değerini verir.</li>
</ul>

<h3>Big-O değeri = O(n²)</h3><br><br>

<h3>3) Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız.</h3><br>

<ul>
    <li>Average case: Aradığımız sayının ortada olması [.,.,.,18,.,.,.]</li>
    <li>Worst case: Aradığımız sayının sonda olması [.,.,.,.,.,.,18]</li>
    <li>Best case: Aradığımız sayının dizinin en başında olması [18,.,.,.,.,.,.,]</li>
    <li>[2,6,16,18,22,27] dizisine bakıldığında 18 sayısı ortada olduğu için <b>Average Case</b> kapsamına girer.</li>


</ul><br><br>

<h2>Selection Sort</h2><br>
<h3>4) [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.</h3><br>

<ol>
    <li>[2,3,5,8,7,9,4,15,6]</li>
    <li>[2,3,5,8,7,9,4,15,6]</li>
    <li>[2,3,4,8,7,9,5,15,6]</li>
    <li>[2,3,4,5,7,9,8,15,6]</li>

</ol>


[Talha Bayyar](https://github.com/TalhaBayyar/VeriYapilari-Projeleri)<br>
[Patika.dev](https://app.patika.dev/)