---
title: Smernice za izvoz podataka o životnom ciklusu
description: Izvoz informacija o životnom ciklusu proizvoda
ms.date: 12/16/2020
layout: ContentPage
ms.openlocfilehash: 5e9dddbff5fac32e6d3cf8ef0943151d2dfe5e35
ms.sourcegitcommit: 6ea3221fd5475440480515f04f33988656d71748
ms.translationtype: HT
ms.contentlocale: sr-Latn-RS
ms.lasthandoff: 11/02/2021
ms.locfileid: "3546870"
---
# <a name="lifecycle-data-export-guidance"></a>Smernice za izvoz podataka o životnom ciklusu
Ovaj dokument opisuje kako da koristite datoteku za izvoz proizvoda.

## <a name="query-information"></a>Informacije o upitu
U Excel dokumentu postoje polja koja pomažu u identifikaciji podataka popunjenih u tabeli proizvoda.

### <a name="end-of-support"></a>Kraj podrške
Vrednost kraj podrške filtriraće proizvode po datumu završetaka podrške za proizvod ili datumima objavljivanja.

Moguće vrednosti: Sve (nije primenjen nijedan filter), Godina i Opseg.

### <a name="family"></a>Porodica
Vrednost porodice filtrira proizvode po nadređenom nivou unutar hijerarhije poznate kao porodica.

Moguće vrednosti: Sve (nije primenjen nijedan filter), Ime porodice

### <a name="group"></a>Grupa
Vrednost grupa filtrira proizvode u okviru nadređenog nivoa (porodice) prema određenoj grupi.

Moguće vrednosti: Sve (nije primenjen nijedan filter), Ime grupe

## <a name="table-columns"></a>Kolone tabele
Tabela proizvoda se sastoji od kolona koje definišu proizvod, uređenja, izdanja i odgovarajuće datume podrške.

> [!NOTE]
> Postoji red za svaki proizvod, izdanje i kombinaciju izdanja.

### <a name="product"></a>Proizvod
Ime proizvoda.

### <a name="edition"></a>Izdanje
Kolona izdanja će biti uneta kada proizvod sadrži izdanja. Kada ne postoji izdanje proizvoda, ovo polje će biti prazno.

### <a name="release"></a>Izdanje
Kolona izdanja će se otpustiti kada proizvod sadrži više izdanja.
Kada proizvod ima samo jedno izdanje, ovo polje će biti prazno.

### <a name="support-policy"></a>Politika podrške
Ovo polje definiše politiku podrške koju proizvod sledi.

Moguće vrednosti: [Fiksno](/lifecycle/policies/fixed), [moderno](/lifecycle/policies/modern), Komponenta

### <a name="start-date"></a>Datum početka
Datum početka podrške za proizvod.

### <a name="mainstream-date"></a>Datum glavne podrške
Kada su smernice za podršku **fiksne** ili **Komponente**, ovo je datum završetka glavne podrške za proizvod.
  
Kada su smernice podrške **moderne**, ovo polje će biti prazno.

### <a name="extended-end-date"></a>Datum isteka proširene podrške
Kada su smerniceza podršku **Fiksne** ili **Komponente**, ovo je datum završetka produžene podrške proizvoda.

Kada su smernice podrške **moderne**, ovo polje će biti prazno.

### <a name="retirement-date"></a>Datum penzionisanja
Kada smernice za podršku budu **fiksne** ili **komponente**, ovo polje će biti prazno.

Kada su smernice podrške **moderne**, ovo će biti datum penzionisanja proizvoda.

### <a name="release-start-date"></a>Datum početka objavljivanja
Datum početka podrške za izdanje. Kada proizvod ima samo jedno izdanje, ovo polje će biti prazno.
 
### <a name="release-end-date"></a>Datum završetka izdanja
Datum završetka podrške za izdanje.
Kada proizvod ima samo jedno izdanje, ovo polje će biti prazno.

### <a name="docs-url"></a>Url dokumenata
URL za proširenu dokumentaciju.
