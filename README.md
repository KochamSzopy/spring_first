Aplikacja składa się z 3 elementów:
SpringFirstApplication - odpowiada za uruchomienie aplikacji, dzięki funkcji main
HelloController - Kontroler, zarządza żądaniami użytkownika. Jeżeli wpiszemy samo localhost:8080, zostanie nam pokazana strona z napisem w funkcji hello, 
natomiast po dopisaniu /greeting, możemy dodać parametr z imieniem. Nie jest on wymagany i jeżeli nie zostanie podany, to zamiast niego pojawi się 
zdefniowana przez nas wartość domyślna. Name zostaje dodane do modelu, gdzie jest przechowywana jego wartość. 
greeting.html - Widok, używa thymeleaf, dzięki któremu możemy wyświetlić treści w HTML-u. Możemy wstawić zmienną "name" przekazaną przez kontroler. 
W folderze static przechowywany jest obrazek, który wyświetla na stronie. W tym przypadku jest to sympatyczny jeż.
