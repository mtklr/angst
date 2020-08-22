# angst

[Angband](https://rephial.org/) score tab.

`angst` uses a patched `angband` with a `-c` option to list scores - see [angband-scores.diff](https://github.com/mtklr/angst/blob/master/angband-scores.diff).

```
$ angst -p | column -s$'\t' -t | head -n6

# rank  score    name        species   class    lev/max  killer                   dlev/max  uid  date        gold    turn
1       1301330  Helmut III  High-Elf  Warrior  39       Ungoliant, the Unlight   35        0    2020-07-16  413394  1223621
2       1243654  Helmut V    High-Elf  Warrior  38/39    a mature green dragon    48        0    2020-07-28  116297  691838
3       1177176  Helmut VII  Dwarf     Warrior  39       a dracolich              55        0    2020-08-10  211225  615490
4       782394   Helmut      Dwarf     Warrior  37       an ancient green dragon  47        0    2020-05-14  268165  717420
5       697668   Helmut      Dwarf     Warrior  37       a death mold             44        0    2020-04-18  232413  1092286

```
