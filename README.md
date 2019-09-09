# Klasifikacija enzima na osnovu njihovog EC broja (engl. Enzyme Commission number)
## Autor: Nevena Ćirić

EC broj je numerička klasifikaciona šema za enzime koja je bazirana na hemijskim reakcijama koje oni katalizuju. 

Na prvom nivou klasifikacije enzimi su podeljeni u 7 klasa:
* EC 1 - Oksidoreduktaze
* EC 2 - Transferaze
* EC 3 - Hidrolaze
* EC 4 - Liaze
* EC 5 - Izomeraze
* EC 6 - Ligaze
* EC 7 - Translokaze

Ove osnovne klase enzima se dalje dele na podklase.

Enzime predstavljamo njihovim *sekvencama aminokiselina* i *listom funkcionalnih domena* (deo proteinske sekvence koji ima određenu 
funkciju). Sekvence enzima zajedno sa njihovim EC brojevima uzeti su iz UniProtKB baze podataka 
([link](https://www.uniprot.org/uniprot/#enzymesViewBy)),
a funkcionalni domeni su za svaki od enzima dobijeni pomoću programa Hmmer ([link](http://hmmer.org/))
kome se kao ulaz zadaje sekvenca enzima.

Model koji se koristi za klasifikaciju enzima konstruisan je na osnovu rada 
[DEEPre: sequence-based enzyme EC number prediction by deep learning ](https://academic.oup.com/bioinformatics/article/34/5/760/4562505).
