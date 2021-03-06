# PJISP - Algoritmi za sortiranje

*KO NE VOLI FOLKLOR NEKA NE OTVARA LINKOVE* 

##01 Bubble Sort
**Prolaznost O(n^2)**
[VIDEO](https://youtu.be/lyZQPjUT5B4)

Sortira niz tako što u svakom od prolaženja na vrh izbaci najveći element. Najveći element u do tada ne sortiranom nizu "ispliva" na vrh kao balončić (Bubble)

##02 Insertion Sort
**Prolaznost O(n^2)**
[VIDEO](https://youtu.be/ROalU379l3U)

Sortira niz poređenjem svih elemenata međusobno. Slično Bublble Sortu elementi se postavljaju na svoju poziciju jedan po jedan

##03 Shell Sort
**Prolaznost O(n log^2(n))**
[VIDEO](https://youtu.be/CmPA7zE8mx0)

Opis sorta

##04 Quick Sort
**Prolaznost O(n log(n))**
[VIDEO](https://youtu.be/Fj5SuEuaPhc)

Sortira niz na intervalu levi-desni. Pivot je bilo koji element sa kojim se porede svi ostali. Pivot može biti bilo koji element, a u ovom primeru pivot je srednji element niza. Nakon završene jedne interacije sa leve strane pivota svi elementi su veći ili jednaki od njega, a sa desne veći. Na ovaj način pivot je na svom mestu. Tada je potrebno rekurzivo pozvati funkciju za deo niza levo od pivota i za deo niza desno od pivota. Sort se završava kada se pozove za prazan niz, za niz čija je leva pozicija veća od desne ili za niz 

##05 Insertion Sort
**Prolaznost O(n^2)**
[VIDEO](https://youtu.be/ROalU379l3U)

Izabranom elementom se pronalazi mesto u nizu, a ostali elementi se pomeraju za jedno mesto naniže. Ovaj postupak ponavlja se za svaki element niza. Nakon uspešno završenog programa niz je sortiran.

##06 Merge Sort
**Prolaznost O(n log(n))**
[VIDEO](https://youtu.be/XaqR3G_NVoo)

Merge sort se svodi na to da da prvo cepa niz na sve manje podnizove dok ne dodje do najmanjeg podniza od 1 clana. A zatim od dva manja niza pravi jedan veci ali tako sto redom poredi elemente  malog niza i u veci upisuje element koji je manji. Kada se pozove sort on ce prvo da rekurzivno pozove sebe samog dok god ne dobije male nizove a zatim ce da se vraca unazad i spaja male nizove u vece dok ne dobije pocetni niz koji je sortiran.
