# Ocado---Automation
All ideas and WIP scripts I have created for Ocado

# Dawid Szczerba
Problem: Wczytywanie rodzin poprzez Import Family (po jednej na raz) trwa bardzo długo i jest niewygodne (BIM360->Search->Download->Revit->Import Family)
Rozwiązanie: Stworzenie modeli zawierających najbardziej aktualne wersje rodzin (conveyory, furniture etc.) z których niczym z sandboxa możnaby bezpośrednio kopiować je do modelu i mieć pewność że wersja jest aktualna

Problem: Zasadniczy bałagan w parametrach stosowanych w rodzinach - błędy w nazwach (powtórzenia, minimalne różnice (np. Length i length itp.)), błędy w zwracanych wartościach (np. length nie zwraca poprawnej długości elementu), błędy w typie parametru 
(parametr o tej samej nazwie i mający tą samą funkcję w danej grupie rodzin raz jest Instance, raz Type, raz Shared itd.), parametry błędnie posortowane (niespójna kolejność w Properties)
Rozwiązanie: Należałoby zrobić przegląd grup rodzin i ujednolicić parametry pod względem kolejności, nazw itd - grubszy temat zasadniczo
