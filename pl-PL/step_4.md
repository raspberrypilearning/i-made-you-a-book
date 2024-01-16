## Buduj 🧱 i testuj 🔄

Nadszedł czas, aby zrobić Twoją książkę. Zacznij od czegoś małego i dodaj więcej do swojego projektu, jeśli masz czas.

![Wiele stron projektu książki.](images/pages-rama.png)

**Wskazówka:** Pamiętaj, aby testować swój projekt za każdym razem, gdy coś dodasz. Znacznie łatwiej jest znaleźć i naprawić błędy, zanim wprowadzisz więcej zmian.

### Do każdej strony 📃

--- task ---

Dodaj tło i nowe duszki potrzebne dla tej strony.

![Wybierz duszka i wybierz ikony tła.](images/sprite-and-backdrop.png)

Będziesz musiał dodać kod, aby ustawić pozycje i widoczność duszków na pierwszej stronie tytułowej i na każdej kolejnej stronie.

```blocks3
when flag clicked

when backdrop switches to [strona v]
```

[[[scratch3-show-hide-sprites-backdrops]]]

[[[scratch3-positioning-with-layers]]]

--- /task ---

### Do każdego duszka 🐈 🐢 🎈

--- task ---

Będziesz musiał dodać kod do każdej postaci i duszka obiektu w swojej książce. Zastanów się, czy zrobią coś, gdy projekt się rozpocznie, kiedy tło przełączy się na określoną stronę lub po kliknięciu duszka.

```blocks3
when flag clicked

when this sprite clicked

when backdrop switches to [strona v]
```

[[[scratch3-change-costumes-to-show-mood]]]

[[[scratch3-animate-movement-costumes]]]

[[[scratch3-graphic-effects]]]

[[[scratch3-jiggle-a-sprite]]]

--- /task ---

### Przewracanie strony 📖

--- task ---

Będziesz potrzebować sposobu, aby czytelnik mógł przejść do następnej strony w Twojej książce.

```blocks3
when this sprite clicked
```

[[[scratch3-changing-backdrops-pages-levels]]]

--- /task ---

### Edytuj kostiumy 🦁 i tła 🖼️

--- task ---

Możesz edytować lub dodawać kostiumy lub tła w edytorze Paint.

![Zakładki Kostiumy i Tła.](images/costumes-backdrops-tabs.png){:width="250px"}

![Kostium farby i ikony tła.](images/sprite-and-backdrop.png)

[[[scratch3-paint-a-new-backdrop-extended]]]

[[[scratch3-backdrops-and-sprites-using-shapes]]]

[[[scratch3-use-text-tool]]]

[[[scratch3-copy-parts-between-sprite-costumes]]]

[[[scratch3-add-costumes-to-a-sprite]]]

--- /task ---

### Dodaj dźwięk 🎵

--- task ---

![Karta Dźwięki.](images/sound-editor-tab.png)

```blocks3
when flag clicked

when this sprite clicked

when backdrop switches to [strona v]
```

![Dodaj ikonę dźwięku.](images/sound-icon.png)

[[[scratch3-add-sound]]]

![Ikona nagrywania z menu dodawania dźwięku.](images/record-sound.png)

[[[scratch3-record-sound]]]

![Tekst na mowę blokuje ikonę menu.](images/text-to-speech.png)

[[[scratch3-text-to-speech]]]

--- /task ---

### Przypomnienia edytora Scratcha

[[[scratch3-copy-code]]]

[[[scratch3-full-screen]]]

[[[scratch3-duplicate-sprite]]]

--- task ---

**Test:** 🔄 Pokaż komuś swój projekt i poproś o 🗣️ jego opinię. Czy chcesz wprowadzić jakieś zmiany w swojej książce?

⏱️ Jeśli masz czas, możesz ulepszyć swój projekt.

💡 Możesz:
- Dodać więcej kodu do swojego duszka
- Dodać kolejnego duszka
- Dodać kolejną stronę
- Nagrać dźwięk
- Stworzyć nowy kostium w edytorze Paint

--- /task ---

--- task ---

**Debugowanie:** Być może znajdziesz błędy w swoim projekcie, które musisz naprawić. Oto kilka typowych błędów:

--- collapse ---
---
title: Duszek pojawia się lub znika na niewłaściwych stronach
---

Sprawdź, czy duszek ma skrypty `kiedy tło zmieni się na`{:class="block3events"} z blokami `pokaż`{:class="block3looks"} lub `ukryj`{:class="block3looks"}, według potrzeb. Sprawdź, czy wybrałeś poprawną nazwę tła w bloku `kiedy tło zmieni się na`{:class="block3events"}. Pomaga to nadawać tłom nazwy, które są łatwe do zrozumienia, a to pomaga wykryć problemy tego typu.

--- /collapse ---

--- collapse ---
---
title: Duszek porusza się do góry nogami
---

Dodaj blok `ustaw styl obrotu na lewo-prawo`{:class="block3motion"} lub `ustaw stylu obrotu na nie obracaj`{:class="block3motion"}.

--- /collapse ---

--- collapse ---
---
title: Duszek „przeskakuje”, gdy zmienia kostium lub się odbija
---

Upewnij się, że kostium jest wyśrodkowany w edytorze Paint (wyrównaj niebieski krzyż w kostiumie z celownikiem na środku edytora Paint).

--- /collapse ---

--- collapse ---
---
title: Dźwięk nie jest odtwarzany
---

Czy dodałeś blok `zagraj dźwięk`{:class="block3sound"} tam gdzie potrzeba? Jeśli skopiowałeś kod z innego duszka, będziesz musiał dodać dźwięk do tego duszka w zakładce **Dźwięki**. Sprawdź głośność na komputerze lub tablecie i upewnij się, że nie obniżyłeś głośności kodem — spróbuj bloku `ustaw głośność na`{:class="block3sound"} `100`.

--- /collapse ---

--- collapse ---
---
title: Inne duszki nachodzą na duszka
---

Dodaj blok `przesuń na wierzch`{:class="block3looks"}.

--- /collapse ---

--- collapse ---
---
title: Duszek porusza się lub zmienia tylko raz
---

Umieść swój kod wewnątrz bloku `zawsze`{:class="block3control"}, aby nie przestawał działać.

--- /collapse ---

--- collapse ---
---
title: Strony są w złej kolejności
---

Sprawdź, w jakiej kolejności są Twoje tła: kliknij panel Scena, a następnie **Tła**, aby wyświetlić tła dla swojego projektu.

--- /collapse ---

Możesz też znaleźć błąd, który nie jest tutaj wymieniony. Może wymyślisz, jak to naprawić?

🗣️ Uwielbiamy słuchać o błędach, jakie znalazłeś i o tym, jak je naprawiłeś. Użyj przycisku **Prześlij opinię** na dole tej strony i poinformuj nas, czy znalazłeś inny błąd w swoim projekcie.

--- /task ---

