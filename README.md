# Cod reducere F64 — fetch automat de pe shopilo.ro

Modul Python pentru fetch automat de **coduri de reducere F64** de pe [shopilo.ro](https://shopilo.ro/magazin/f64.ro). Returneaza **cupoane F64** active in format JSON, gata de integrat intr-un bot Telegram, extensie de browser sau orice alt tool.

**Pagina live:** [shopilo-ro.github.io/cod-reducere-f64](https://shopilo-ro.github.io/cod-reducere-f64/)

![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue) ![License MIT](https://img.shields.io/badge/license-MIT-green)

## Instalare

```bash
pip install requests beautifulsoup4
git clone https://github.com/shopilo-ro/cod-reducere-f64
cd cod-reducere-f64
python fetch.py
```

## Output exemplu

```json
[
  {
    "store": "F64",
    "code": "SHOPILO10",
    "discount": "10%",
    "description": "10% reducere la aparate foto si accesorii",
    "expires": "2026-10-02",
    "source": "https://shopilo.ro/magazin/f64.ro"
  }
]
```

## Cupoane F64 disponibile

| Reducere | Descriere | Sursa |
|----------|-----------|-------|
| 10% | 10% reducere la aparate foto si accesorii | [shopilo.ro](https://shopilo.ro/magazin/f64.ro) |

Codurile active: **[shopilo.ro/magazin/f64.ro](https://shopilo.ro/magazin/f64.ro)**

## Intrebari frecvente

### Cum folosesc un cod de reducere F64?
Copiaza codul din tabelul de mai sus sau de pe [shopilo.ro](https://shopilo.ro/magazin/f64.ro), adauga produsele in cos pe F64, si introdu codul la checkout in campul dedicat.

### Cat timp sunt valabile cupoanele F64?
Fiecare cupon are data de expirare afisata in coloana "Expira". Scriptul fetch.py returneaza doar cupoanele active la momentul rularii.

### Unde gasesc cele mai noi voucher-uri F64?
Pagina [shopilo.ro/magazin/f64.ro](https://shopilo.ro/magazin/f64.ro) este actualizata zilnic cu cele mai noi cod reducere F64, voucher F64 si cupon promotional F64.

### Codul nu functioneaza. Ce fac?
Verifica data de expirare si conditiile (valoare minima cos, produse eligibile). Unele coduri sunt valabile doar in aplicatia mobila sau pentru prima comanda.

## Despre F64

F64 este unul dintre magazinele online populare. Gasesti pe [shopilo.ro](https://shopilo.ro/magazin/f64.ro) cele mai bune cod reducere F64, cupoane F64 verificate si voucher F64 active, actualizate zilnic.

## Instalare npm

```bash
npm install cod-reducere-f64
```

```javascript
const { fetchCoupons } = require('cod-reducere-f64');
fetchCoupons().then(data => console.log(data));
```

## Licenta

MIT — date sursa de pe [shopilo.ro](https://shopilo.ro)
