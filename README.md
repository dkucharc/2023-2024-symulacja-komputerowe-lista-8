# Symulacje Komputerowe

Wydział Matematyki, Semestr Letni 2023/2024

**Laboratorium 8:** Proces Ryzyka

**Termin oddania:** TBA

---

**Zadanie 1.** Proces Ryzyka

Kapitał firmy ubezpieczeniowej jest zadany wzorem:
$$R(t)=r_0 +p(t)− \sum\limits_{i=0}^{N_t}X_i$$
gdzie $N_t$ jest procesem liczącym (tutaj jednorodnym procesem Poissona o intensywności $\lambda$, ale może być też inny proces odnowy), $X_i$ to wielkości szkód (np. z rozkładu gamma, Pareto, Weibulla), $r_0$ to kapitał początkowy, a $p(t)$ to funkcja zysków.
> - Stwórz symulację takiego procesu, która zatrzymuje się przy uderzeniu w $0$; funkcja $p(t)$ oraz rozkład zmiennych $X_i$ powinny być wprowadzane przez użytkownika.

**Uwaga**: Rozwiązania poszczególnych zadań należy umieścić w dedykowanych plikach `*.py` lub `*.ipynb` o nazwach `zadanie_1.[py|ipynb]`, `zadanie_2.[py|ipynb]` i `zadanie_3.[py|ipynb]`, itd.
