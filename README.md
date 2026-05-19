# ⚓ Interaktywny Geoportal Latarni Morskich w Estonii

> 🌐 **Zobacz mapę na żywo:** [https://szczoopak.github.io/geoportal-estonia/](https://szczoopak.github.io/geoportal-estonia/)

Interaktywna mapa prezentująca lokalizację latarni morskich w Estonii na tle szczegółowego podkładu topograficzno-komunikacyjnego. 

## 🗺️ O projekcie
Projekt został przygotowany w programie **QGIS 3.40** i wyeksportowany do formatu kafelków XYZ. Generowanie kafelków zostało rozszerzone do poziomu **Zoom 13**, co pozwoliło na bezbłędne i płynne renderowanie wszystkich warstw tematycznych, których widoczność w programie QGIS została zaprogramowana od skali 1:99 999.

### Kluczowe cechy mapy:
* **Customowa stylizacja:** Zaawansowane reguły wyświetlania sieci dróg oraz klasyfikacji miejscowości precyzyjnie reagujące na stopień przybliżenia.
* **Autorska symbolika:** Ikony latarni morskich, przystanków promowych, lotnisk i stacji kolejowych zostały w całości zaprojektowane przeze mnie w programie **Inkscape**.
* **Bogaty podkład:** Warstwy lasów, rzek, jezior oraz zagospodarowania terenu zapewniające pełny kontekst przestrzenny.

## 💾 Dane źródłowe i licencja
* Dane przestrzenne pochodzą z serwisu **Geofabrik.de** i są oparte na zasobach projektu **OpenStreetMap**. 
* Dane są udostępniane na licencji Open Data Commons Open Database License (ODbL).
* Kod geoportalu bazuje na bibliotece **Leaflet**.

## 📂 Zawartość repozytorium
* `index.html` + `tiles/` - pliki produkcyjne działającego geoportalu (zoomy od 7 do 13).
* `src/` - kompletny projekt QGIS (`.qgz`) wraz z autorskimi ikonami SVG/PNG do wglądu i edycji.
