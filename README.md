# 0800-fizobl-lammps

W pliku wizualizacja.png przedstawiono wizualizację otrzymaną przy pomocy programu VMD. Widać na nim jeden atom chloru i jeden atom sodu w otoczeniu cząsteczek wody. 

Symulację przeprowadono dla czasu o długości równej 1 ns. W czasie tym odległość pomiędzy Na, a Cl zmieniała sie, co zostało przedstawione na wykresie odleglosc_od_czasu.png. Widać, że oscylowała ona w czasie. Na podstawie zebranych wartości dystansów stworzono histogram częstości występowania poszczególnych odległości. Uzyskany wykres jest zawarty w pliku histogram_odleglosci.

Można z niego odczytać, że odległość Na Cl w układzie najczęściej przyjmowała wartość ok 0,75 nm.

Następnie policzono energię swobodną F tego układu. W tym celu wykorzystano równanie F=-ln(N), gdzie N jest prawdopodobieństwem dla każdej kolumny z histogramu. Wartość N policzono jako iloczyn wysokości słupka z histogramu i jego szerokości. Uzyskany rezultat znajduje się w pliku energia_odleglosci.png. Tam gdzie funkcja przyjmuje większą wartość tam energia potencjalna układu jest większa, co powoduje, że istnieje mniejsza szansa na znalezienie się w tym stanie cząstek. Widzimy, że najwieksza jej wartość, a więc bariera umieszczona jest dla odległości ok. 0.38 nm. 

