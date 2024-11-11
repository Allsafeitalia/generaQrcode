# QR Code Generator

## Caratteristiche #
- Generazione di QR code base
- Personalizzazione dei colori (QR code e sfondo)
- Controllo della dimensione del QR code
- Correzione degli errori di alto livello
- Supporto per vari formati di output

## Prerequisiti #
Prima di iniziare, assicurati di avere Python installato sul tuo sistema. Il progetto richiede Python 3.6 o versioni successive.

## Installazione #
1. Clona il repository:
```bash
git clone https://github.com/your-username/qr-code-generator.git
cd qr-code-generator
```

2. Installa le dipendenze necessarie:
```bash
pip install -r requirements.txt
```

## Utilizzo #

## Esempio Base #
```python
from qr_generator import genera_qr_code

# Genera un QR code semplice
genera_qr_code("https://www.example.com")
```

## Esempio Avanzato #
```python
# Genera un QR code personalizzato
genera_qr_code(
    dati="https://www.python.org",
    nome_file="python_qr.png",
    colore_qr="#0000FF",  # Blu
    colore_sfondo="#FFFF00",  # Giallo
    dimensione=15
)
```

## Parametri di Configurazione #
| Parametro | Tipo | Default | Descrizione |
|-----------|------|---------|-------------|
| dati | str | - | Il contenuto da codificare nel QR code |
| nome_file | str | "qr_code.png" | Nome del file di output |
| colore_qr | str | "#000000" | Colore del QR code (formato HEX) |
| colore_sfondo | str | "#FFFFFF" | Colore dello sfondo (formato HEX) |
| dimensione | int | 10 | Dimensione del QR code |

## Note Tecniche #
- Il QR code viene generato con il massimo livello di correzione degli errori
- L'immagine viene salvata nel formato PNG
- Supporta testi UTF-8
- Dimensioni consigliate: tra 5 e 20 per risultati ottimali

## Come Contribuire #
I contributi sono sempre benvenuti! Ecco come puoi aiutare:

1. Fai un Fork del progetto
2. Crea un Branch per la tua feature (`git checkout -b feature/AmazingFeature`)
3. Commit delle tue modifiche (`git commit -m 'Add some AmazingFeature'`)
4. Push al Branch (`git push origin feature/AmazingFeature`)
5. Apri una Pull Request

## Licenza #
Questo progetto è sotto licenza MIT - vedi il file [LICENSE.md](LICENSE.md) per i dettagli.

## Autore #
- **Il tuo nome** - *Lavoro iniziale* - [TuoUsername](https://github.com/TuoUsername)

## Supporto #
Se questo progetto ti è stato utile, metti una ⭐️!
