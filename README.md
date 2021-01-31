# PROJEKT_MASKA
Projekt Maska został stworzony w ramach konkursu "Sztuczna inteligencja w moim życiu". Przedstawiona jest w nim koncepcja wykrywania czy osoba ma założona maseczkę czy nie. Koncepcja może mieć zastosowanie np. w kamerach IP i CCTV w marketach, na lotniskach czy też przy wejściach do galerii, aby zaalarmować o założenie owej. Projekt został stworzony w oparciu o pakiet Tensorflow, pakiet Keras, a rozpoznawanie w czasie rzeczywistym jest dostępne dzięki pakietowi OpenCV.<br/><br/>
Aplikacja pozwala na rozpoznawanie w czasie rzeczywistym, z wideo jak i obrazu.<br/>
Link do pobrania:<br/>
aa<br/><br/>
Aby uruchomić aplikację należy rozpakować pobraną paczkę, a nastepnie włączyć program aplikacja.exe znajdujący się w głównym folderze "aplikacja". Uruchamianie może zająć dłuższą chwilę(ok. 1 min), następnie wyświetli się okno jak przedstawiono niżej.<br/>
![Alt text](https://github.com/wonderooo/PROJEKT_MASKA/blob/main/ss.png)<br/>
Aby uruchmić model rozpoznawania maseczki w wideo lub obrazie należy do okna pod "WIDEO i OBRAZ" wpisać nazwę pliku wrzuconego przez Ciebie do głównego folderu "aplikacja" (można przenieść plik po włączeniu aplikacji). Wpisana nazwa musi być wpisana z rozszerzeniem np. mp4, mov, jpg, png, następnie kliknąć przycisk "Zatwierdź" i to wszystko.<br/><br/>
Aby uruchmić model w trybie rzeczywistym należy po prostu wpisać w okno pod "RZECZYWISTOŚĆ" numer urządzenia wideo. Standardowo jest to 0, ale jeśli nie zadziała możesz spróbować od 1 w górę. Po kliknięciu przycisku zatwierdź powinieneś zobaczyć obraz z kamery z detekcjami. Aby wyłączyć ten tryb należy wcisnąć "w"<br/><br/>
Przykłady:<br/>
![Alt text](https://github.com/wonderooo/PROJEKT_MASKA/blob/main/3.gif)
<br/>
![Alt text](https://github.com/wonderooo/PROJEKT_MASKA/blob/main/1.gif)
<br/>
![Alt text](https://github.com/wonderooo/PROJEKT_MASKA/blob/main/4.gif)
<br/>
![Alt text](https://github.com/wonderooo/PROJEKT_MASKA/blob/main/2.gif)
<br/><br/>
Tensorflow: https://www.tensorflow.org/<br/>
Keras: https://keras.io/<br/>
OpenCV: https://opencv.org/
