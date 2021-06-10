# Life
Jest to excelowa wersja (stworzona przy pomocy VBA) gry w życie autorstwa brytyjskiego matematyka Johna Conwaya - jeden z pierwszych 
(powstały w roku 1970) i najbardziej znanych przykładów automatu komórkowego.  

**Przebieg gry:**  
- Uzytkownik wybiera w których komórkach chce "zasiać" życie poprzez wpianie w nich dowolnego tekstu.  
- Po kliknięciu przycisku, stworzy się nowy arkusz, z komórkami pomalowanymi na zielono, w miejsach, gdzie zostało zasiane życie.  
- Jeśli użytkownik potwierdzi, że chce rozpocząć symulacje, to co sekundę zmienią się stany komórek.  
- Symulacja zakończy się po kliknięciu przycisku stop.

**Zasady gry:**  
- Martwa komórka, która ma dokładnie 3 żywych sąsiadów, staje się żywa w następnej jednostce czasu.
- Żywa komórka z 2 albo 3 żywymi sąsiadami pozostaje nadal żywa; przy innej liczbie sąsiadów umiera (z „samotności” albo „zatłoczenia”)
- Żywe komórki są koloru zielonego, te które się właśnie rodzą są jaśniejsze, a te które właśnie umierają - szare.


-----------------------------------------------

Life is VBA version of Conway's Game of Life.  
As wiki sais it is a cellular automaton devised by the British mathematician John Horton Conway in 1970.  
It is a zero-player game, meaning that its evolution is determined by its initial state, requiring no further input.
