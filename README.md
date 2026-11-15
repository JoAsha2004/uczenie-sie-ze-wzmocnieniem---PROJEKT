# uczenie-sie-ze-wzmocnieniem---PROJEKT

OPIS PROJEKTU:

Projekt ma na celu symulację trasy kuriera rozwożącego pizzę na dwuwymiarowej planszy
podzielonej na pola reprezentujące uproszczoną sieć miejskich ulic. Punktem startowym
dla agenta poruszającego się pomiędzy sąsiednimi polami planszy (każdy ruch wiąże się z
upływem czasu i zużyciem określonej ilości energii) jest pizzeria, z której odbiera określoną
liczbę zamówień, a punktami docelowymi są znajdujący się w różnych, oddalonych od
siebie lokalizacjach mapy klienci, do których musi dotrzeć przed powrotem do pizzerii
po kolejne przesyłki (nowy epizod). Agent omija trwale nieprzejezdne pola (budynki) oraz
bramy, które są początkowo otwarte, ale mogą zostać zamknięte do końca obecnego epizodu,
jeśli kurier przeszedł przez dane wyznaczone pole określoną wcześniej liczbę razy w czasie
obecnego epizodu. Im lokalizacja dostawy znajduje się dalej od pizzerii, tym oferuje wyższy
początkowy napiwek doliczany do stałej zapłaty, ale jego wartość zmniejsza się krokowo
wraz z wydłużającym się czasem dostawy, co wymusza decyzję o kolejności obsługi klientów.
Jeśli napiwek spadnie poniżej 0, klient anuluje zamówienie i kurier już go nie dostarcza (co
skutkuje mniejszym zarobkiem na koniec epizodu). W przypadku gdy energia spadła do
zera agent przenosi się do punktu startowego i rozpoczyna się kolejny epizod.

AKTUALNY STAN PRAC:

Zostały zrealizowane pierwsze 3 rozdziały raportu ("Informacje podstawowe", "Temat i cel projektu" oraz  "Formalizacja problemu RL/MDP")
