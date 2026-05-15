# 🧬 Kalkulator Tm Sekwencji DNA – Aplikacja Biologiczna w Pythonie

**Projekt zaliczeniowy z przedmiotu Programowanie w Pythonie / Bioinformatyka**

Zaawansowana aplikacja desktopowa z graficznym interfejsem, która pozwala generować losowe sekwencje DNA, obliczać temperaturę topnienia (melting temperature) oraz wizualizować skład nukleotydów.

---

## 🎯 O projekcie

Aplikacja symuluje podstawowe operacje bioinformatyczne w przyjaznym, intuicyjnym interfejsie graficznym. Użytkownik może:
- Wygenerować losową sekwencję DNA o dowolnej długości
- Obliczyć temperaturę topnienia metodami **GC** oraz **Nearest-Neighbor**
- Obejrzeć interaktywne wizualizacje składu procentowego i liczebnego baz (A, C, G, T)

Projekt łączy **programowanie GUI**, **obliczenia naukowe** oraz **wizualizację danych** – idealny przykład praktycznego zastosowania Pythona w dziedzinie biologii i bioinformatyki.

---

## ✨ Główne funkcjonalności

- **Generator losowych sekwencji DNA** (A, C, G, T)
- **Obliczanie temperatury topnienia (Tm)**:
  - Metoda Tm_GC (procent GC)
  - Metoda Tm_NN (Nearest-Neighbor)
- **Wizualizacje**:
  - Wykres kołowy – procentowy udział każdej bazy
  - Wykres słupkowy – liczba poszczególnych nukleotydów
- **Przyjazny interfejs graficzny** (Tkinter) z ciemnym motywem
- Walidacja danych wejściowych + komunikaty błędów

---

## 🛠 Technologie

| Technologia              | Zastosowanie                          |
|--------------------------|---------------------------------------|
| **Python**               | Główny język                          |
| **Tkinter**              | Interfejs graficzny (GUI)             |
| **BioPython**            | Obliczenia biologiczne (MeltingTemp)  |
| **Matplotlib**           | Wizualizacje danych (wykresy)         |
| **Random**               | Generowanie sekwencji                 |

---

## 🚀 Jak uruchomić

```bash
# 1. Sklonuj repozytorium
git clone https://github.com/Gho2st/PYTHON-PROJECT.git
cd PYTHON-PROJECT

# 2. Zainstaluj wymagane biblioteki
pip install biopython matplotlib

# 3. Uruchom aplikację
python main.py
