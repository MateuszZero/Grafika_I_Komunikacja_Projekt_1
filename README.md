# Grafika i Komunikacja Projekt 1
Projekt nr 1 na przedmiot GiK                                                                                                           

OPIS:

Projekt składający się z 4 programów, które można bardzo szybko i wygodnie otworzyć poprzez pliki .JAR utworzone w głównym folderze projektu. Są to "GIK" oraz "EndlessRace" - pierwszy z nich służy do uruchomienia rysunku, krótkiej informacji o grze, rysunku inicjału za pomocą krzywej Beziera oraz wygenerowania kodu punktów Beziera czajnika Utah, filiżanki, oraz łyżeczki Utah do foldera "WspolrzedneDoModelu3D". W folderze "WspolrzedneWynik" zaś, znajdują się zrzuty ekranu z programów, które wyrysowały punkty Beziera, czerpiąc ze współrzych przetworzonych przez program "Dzbanek", ilustrując w ten sposób końcowe działanie programu. Drugi z nich - EndlessRace to gra samochodowa, którą uruchamiamy oddzielnie.
W folderze "src" znajdują się kody źródłowe każdego z programów.

Projekt składa się z:

1.Rysunek

Korzystając z biblioteki graphics2d utworzony został kolorowy rysunek domu wraz z elementami krajobrazu. Zastosowano proste punkty, a w przypadku niektórych z figur konieczna była implementacja odpowiednich pętli sprytnie przesuwających się po punktach.

2.Gra

Gra samochodowa, w której auto którym sterujemy może poruszać się w lewo, prawo, górę oraz dół - wszystko po to, aby uniknąć jak największej liczby samochodów! Gra toczy się w nieskończoność, dopóki nie zderzymy się z innymi autami, których prędkość, kolor oraz pozycja są generowane losowo, a więc nigdy nie wiemy skąd nadjedzie pojazd. Auto jedzie po prostej drodze, jednak co jakiś czas mija skrzyżowania, będące urozmaiceniem poziomów.

3.Inicjaly

Program ten korzysta z funkcji Beziera, która za pomocą podanych punktów wyrysowuje inicjały - w tym przypadku MŻ, dlatego też korzysta z 4 przejść oraz pętli - jednej dla literki M, drugiej dla Z, oraz dwóch dla drobnych elementów - kreseczki ( - ) oraz kropki na i nad Ż.

4.Dzbanek

Jest to program, który pobiera z 3 plików źródłowych współrzędne dzbanka, kubka oraz łyżeczki w taki sposób, że tworzy aż ponad 100,000 punktów dla każdego z elementów i zapisuje je do pustego folderu WspolrzedneDoModelu3D. Za pomocą programów graficznych umożliwiających wyrysowywanie takich punktów w 3D, takich jak  ParaView, Leica Cloudworx, AutoCAD czy LSS 3DVision możemy narysować wygładzony dzbanek, filiżankę oraz łyżeczkę. W folderze "WspolrzedneWynik" zamieszczony jest wynik wyrysowania tych przedmiotów w ParaView.
