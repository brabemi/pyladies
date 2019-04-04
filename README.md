# Pyladies

## 03 Cykly

### Odkazy

* https://docs.python.org/3/
* zabudované funkce - https://docs.python.org/3/library/functions.html
* matematika - https://docs.python.org/3/library/math.html
* náhoda - https://docs.python.org/3/library/random.html
* želva - https://docs.python.org/3/library/turtle.html

## 05 Řetězce

### Odkazy

* string module - https://docs.python.org/3.7/library/string.html#module-string

### Úlohy

#### Vrať prostřední písmeno

Funkce vrátí jedno prostřední písmeno pro řetězce liché délky, dvě prostřední písmena pro řetězce sudé délky 

```python
def prostredni_pismeno(text):
    ...

prostredni_pismeno("test") # vrátí "es"

prostredni_pismeno("testing") # vrátí "t"

prostredni_pismeno("middle") # vrátí "dd"

prostredni_pismeno("AB") # vrátí "AB"

prostredni_pismeno("A") # vrátí "A"

prostredni_pismeno("") # vrátí ""
```

#### Vrať počet samohlísek v řetězci

```python
def pocet_samohlasek(text):
    ...

pocet_samohlasek("test") # vrátí 1

pocet_samohlasek("WTF") # vrátí 0

pocet_samohlasek("Anna") # vrátí 2
```

#### Komplementární DNA

DNA řetězec složený z bází A, G, C, T, báze jsou kmplementární A ↔ T, C ↔ G

```python
def komplementarni_dna(dna):
    ...

komplementarni_dna("ATTGC") # vrátí "TAACG"

komplementarni_dna("GTAT") # vrátí "CATA"
```

#### Otoč řetězec

```python
def otoc_retezec(text):
    ...

otoc_retezec("kapr") # vrátí "rpak"

nahrad_znak("kajak") # vrátí "kajak"
```

#### Palindrom

Palindrom - řetězec, který má tu vlastnost, že ji lze číst v libovolném směru, například kajak, madam, radar

```python
def je_palindrom(text):
    ...

je_palindrom("kapr") # vrátí false

je_palindrom("kajak") # vrátí true

je_palindrom("a") # vrátí true

je_palindrom("aa") # vrátí true
```

#### Palindrom v2

Palindrom - řetězec, který má tu vlastnost, že ji lze číst v libovolném směru, například kajak, madam, radar
Tato verze si poradí s různou velikostí písmen, mezerami, čárkami, ...

```python
def je_palindrom2(text):
    ...

je_palindrom2("kapr") # vrátí false

je_palindrom2("kajak") # vrátí true

je_palindrom2("Anna") # vrátí true

je_palindrom2("Sakal pes.") # vrátí false

je_palindrom2("Kobyla ma maly bok.") # vrátí true
```

