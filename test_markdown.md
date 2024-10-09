# Creiamo un file markdown che contiene tutte le sintassi spiegate
markdown_content = """
# Elenco delle principali sintassi base di Markdown

## 1. Titoli
I titoli si creano utilizzando il simbolo `#`. Il numero di `#` indica il livello del titolo (da 1 a 6).

### Esempi:
# Titolo 1
## Titolo 2
### Titolo 3
#### Titolo 4
##### Titolo 5
###### Titolo 6

## 2. Testo formattato
Puoi formattare il testo in **grassetto**, *corsivo* o ~~barrato~~.

### Esempi:
- **Grassetto**: `**testo**`
- *Corsivo*: `*testo*`
- ~~Barrato~~: `~~testo~~`
- +++evidenziato+++: `+++testo+++`

## 3. Liste
### Liste non ordinate:
Le liste non ordinate si creano con `-`, `+` o `*`.

### Esempio:
- Elemento 1
- Elemento 2
- Elemento 3

### Liste ordinate:
Le liste ordinate si creano con numeri seguiti da un punto.

### Esempio:
1. Primo elemento
2. Secondo elemento
3. Terzo elemento

## 4. Citazioni
Per creare una citazione, usa il simbolo `>`.

### Esempio:
> Questa è una citazione.

## 5. Link
Per inserire un link, utilizza la sintassi `[testo del link](url)`.

### Esempio:
[Visita OpenAI](https://www.openai.com)

## 6. Immagini
Per inserire un'immagine, utilizza la sintassi `![alt text](url dell'immagine)`.

### Esempio:
![Logo OpenAI](https://openai.com/logo.png)

## 7. Codice
### Inline Code:
Per mostrare del codice inline, utilizza un singolo apice inverso `` ` ``.

### Esempio:
`codice inline`

### Blocchi di codice:
Per blocchi di codice usa tripli apici inversi o, in questo caso, tripli `+++` come in questo documento.

### Esempio:
+++ 
def esempio():
    print("Ciao, mondo!")
+++

## 8. Tabelle
Le tabelle si creano con `|` e `-`.

### Esempio:
| Colonna 1 | Colonna 2 |
|-----------|-----------|
| Valore 1  | Valore 2  |
| Valore 3  | Valore 4  |

## 9. Liste di controllo
Per creare delle liste di controllo, utilizza `- [ ]` per un elemento non selezionato e `- [x]` per uno selezionato.

### Esempio:
- [x] Attività completata
- [ ] Attività da fare

## 10. Separatore
Per aggiungere un separatore, utilizza `---` o `***`.

### Esempio:
---
"""
