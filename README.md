# 0800-fizobl-lammps

W pliku wizualizacja.png przedstawiono wizualizację otrzymaną przy pomocy programu VMD. Widać na nim jeden atom chloru i jeden atom sodu w otoczeniu cząsteczek wody. 

Symulację przeprowadono dla czasu o długości równej 1 ns. W czasie tym odległość pomiędzy Na, a Cl zmieniała sie, co zostało przedstawione na wykresie odleglosc_od_czasu.png. Widać, że oscylowała ona w czasie. Na podstawie zebranych wartości dystansów stworzono histogram częstości występowania poszczególnych odległości. Uzyskany wykres jest zawarty w pliku histogram_odleglosci.

Można z niego odczytać, że odległość Na Cl w układzie najczęściej przyjmowała wartość ok 0,75 nm.

Następnie policzono energię swobodną F tego układu. W tym celu wykorzystano równanie F=-ln(N), gdzie N jest prawdopodobieństwem dla każdej kolumny z histogramu. Wartość N policzono jako iloczyn wysokości słupka z histogramu i jego szerokości. Uzyskany rezultat znajduje się w pliku energia_odleglosci.png. Tam gdzie funkcja przyjmuje większą wartość tam energia potencjalna układu jest większa, co powoduje, że istnieje mniejsza szansa na znalezienie się w tym stanie cząstek. Widzimy, że najwieksza jej wartość, a więc największa bariera umieszczona jest dla odległości ok. 0.38 nm. 

W pliku uzyskanym podczas analizy cząstek wody i atomów Na i Cl znajdowała się również wartość, która reprezentowała ruch kolektywny rozpuszczalnika, tj. wody. Zmienność tej wartości w czasie ukazano na wykresie coordination_od_czasu.png. Widzimy, że wartość ta oscyluje w czasie.

Tak jak poprzednio otrzymane wartości przedstawiono na histagramie, który jest  w pliku histogram_koordynacyjne.png. Odczytać możemy z niego, że wartością najczęściej występującą było 6,2 nm.

Następnie korzystając z tego samego wzoru na F co uprzednio, wykreślono zależność energii F od wartości coordination number i znajduje się ona w pliku energia_koordynacyjne.png. Możemy z niego odczytać, że układ był ograniczony dużym potencjałem z obu stron przy wartościach 3.8 nm i 7.2 nm. 

Ponadto przy wartości 5.7 widzimy kolejną niewielką bariere potencjału. Jej wpływ wyraźnie widać na histogramie histogram_koordynacyjne.png, gdzie dla dokładnie tej wartości widzimy mniejszą liczbę zliczeń niż w sąsiednich przedziałach.
