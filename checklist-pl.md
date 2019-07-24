## 1. Dozwolona składnia markdown na Devchecklists:
  * [ ] Github usuwa białe znaki podczas kompilacji plików markdown. Aby utworzyć poprawny plik skorzystaj z [nieprzetworzonej wersji](https://raw.githubusercontent.com/vintasoftware/devchecklists-template/master/checklist-pl.md) tego pliku.
  * [ ] `##` dla tytułów.
  * [ ] `* [ ]` składnia do stworzenia węzła głównego listy kontrolnej.
  * [ ] `    * [ ]` składnia do stworzenia węzła drugiego poziomu listy kontrolnej.
  * [ ] `    * np.` Składnia do stworzenia przykładu drugiego poziomu.
  * [ ] `      * np.` Składnia do stworzenia przykładu trzeciego poziomu.
  * [ ] Składnia dla prostego fragmentu kodu `Tutaj zamieść kod`.
  * [ ] Składnia dla bloków kodu:
    ```
    # Blok kodu:
	To jest
	kawałek kodu
	w bloku
    ```

## 2. Składnie, których nie należy używać:
  * [ ] `      * [ ]` lista kontrolna trzeciego poziomu.
  * [ ] `![Alt](/image.png "Obraz")` grafiki.
  * [ ] Nagłówki inne niż `## Nagłówek 2`:
      ```
      # Nagłówek 1
      ### Nagłówek 3
      #### Nagłówek 4
      ##### Nagłówek 5
      ###### Nagłówek 6 
      ```
