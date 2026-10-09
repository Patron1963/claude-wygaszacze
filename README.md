# Claude — wygaszacze ekranu

Cztery wygaszacze ekranu dla Windows: pikselowy Claude i totem BlastPDF.

| Wygaszacz | Paczka | Co się dzieje |
|---|---|---|
| **Claude** | `claude_wygaszacz.zip` | Claude wędruje po całym ekranie. Sam wybiera drogę, która się nie powtarza. Czasem przystanie, rozejrzy się, zatańczy albo podskoczy. |
| **Claude i Totem** | `claude_i_totem.zip` | Na środku siedzi totem BlastPDF, a Claude krąży wokół niego i się z nim drażni. Tańczy mu przed nosem, pokazuje język, wskakuje mu na głowę, chowa się za nim. Czasem go kopnie i ucieka w kąt. Totem się wtedy kołysze. |
| **Totem karbon** | `totem_karbon_XL.zip` | Totem BlastPDF na karbonowym talerzu powoli wędruje po ekranie. Sam zmienia kierunek, to zwalnia, to przyspiesza. |
| **Totem mix** | `totem_mix.zip` | Totem BlastPDF powoli wędruje po ekranie i lekko drży. Co jakiś czas, bez stałego rytmu, płynnie przechodzi z czarnego w złoty i z powrotem. |

## Jak zainstalować

1. Pobierz paczkę `.zip` z zakładki **Releases** (po prawej stronie).
2. Rozpakuj ją.
3. Kliknij plik `.scr` prawym przyciskiem myszy i wybierz **Zainstaluj**.

Dwuklik na pliku `.scr` uruchamia wygaszacz od razu. Ruch myszy albo dowolny klawisz go zamyka.

**Ostrzeżenie Windows:** plik nie ma płatnego podpisu cyfrowego, więc Windows może pokazać okno „System Windows ochronił ten komputer”. Żeby uruchomić wygaszacz, kliknij **Więcej informacji**, a potem **Uruchom mimo to**.

## Z czego to jest zrobione

Animacja to strona HTML, a do pliku `.scr` pakuje ją pywebview z PyInstallerem. W paczkach z Claude'em jest też plik `.html`, który działa w każdej przeglądarce i nic nie trzeba instalować.

Autorzy: Piotrek (pomysł) i Claude (kod), 2026.
