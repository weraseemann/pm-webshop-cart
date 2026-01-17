## Epic:

Als Betreiber eines Webshops möchte ich eine Warenkorbfunktion anbieten, damit Kund:innen ausgewählte Produkte sammeln, prüfen und für den Kauf vorbereiten können.

## User Story 1: Produkt in den Warenkorb legen

User Story:
Als Kund:in möchte ich ein Produkt in den Warenkorb legen können, damit ich es später kaufen kann.
Akzeptanzkriterien:
- Ein „In den Warenkorb“-Button ist auf der Produktdetailseite sichtbar
- Nach dem Klick auf "In den Einkaufswagen"-Button wird das Produkt dem Warenkorb hinzugefügt
- Die Anzahl der Artikel im Warenkorb wird aktualisiert
- Der Warenkorb bleibt erhalten, wenn die Seite neu geladen wird
- Eine visuelle Bestätigung (z. B. Hinweis oder Badge) wird angezeigt

## User Story 2: Warenkorb anzeigen

User Story: 
Als Kund:in möchte ich meinen Warenkorb anzeigen können, damit ich sehe, welche Produkte ich ausgewählt habe.

Akzeptanzkriterien:
- Der Warenkorb ist über ein Icon oder Menü erreichbar
- Alle hinzugefügten Produkte werden aufgelistet
- Für jedes Produkt werden Name, Preis, Menge und Zwischensumme angezeigt
- Der Gesamtpreis aller Produkte wird korrekt berechnet

## User Story 3: Menge eines Produkts ändern

User Story:

Als Kund:in möchte ich die Menge eines Produkts im Warenkorb ändern können, damit ich mehrere Einheiten kaufen kann.

Akzeptanzkriterien:
- Die Produktmenge kann erhöht oder reduziert werden
- Die Zwischensumme des Produkts aktualisiert sich automatisch
- Der Gesamtpreis des Warenkorbs wird entsprechend angepasst
- Die Menge darf nicht kleiner als 1 sein

## User Story 4: Produkt aus dem Warenkorb entfernen

User Story:
Als Kund:in möchte ich ein Produkt aus dem Warenkorb entfernen können, damit ich meine Auswahl anpassen kann.

Akzeptanzkriterien:
- Jedes Produkt hat eine „Entfernen“-Option
- Nach dem Entfernen wird das Produkt nicht mehr im Warenkorb angezeigt
- Der Gesamtpreis wird neu berechnet
- Ist der Warenkorb leer, wird eine entsprechende Meldung angezeigt

## User Story 5: Warenkorb bleibt gespeichert

User Story:
Als Kund:in möchte ich, dass mein Warenkorb gespeichert bleibt, damit ich meinen Einkauf später fortsetzen kann.

Akzeptanzkriterien:
- Der Warenkorb bleibt bei einem Seitenreload erhalten
- Der Warenkorb bleibt beim erneuten Besuch der Seite bestehen
- Wird die Ware nicht vorhanden sein, muss ein Hinweis dafür stehen und der Kauf für diese Ware nicht möglich sein
- Gespeicherte Produkte werden korrekt geladen

## User Story: Zum Checkout wechseln

User Story:
Als Kund:in möchte ich vom Warenkorb aus zur Kasse gehen können, um meine Bestellung abzuschließen.

Akzeptanzkriterien
- Im Warenkorb ist ein Button „Zur Kasse“ vorhanden
- Der Button wird aktiv, wenn sich mindestens ein Produkt im Warenkorb befindet
- Beim Klick auf „Zur Kasse“ wird die Kund:in zur Checkout-Seite weitergeleitet
- Alle im Warenkorb enthaltenen Produkte werden korrekt in den Checkout übernommen:
Preise, Mengen und Gesamtsumme im Checkout entsprechen exakt dem Warenkorb
- Änderungen im Warenkorb vor dem Checkout werden berücksichtigt
- Bei technischen Fehlern erhält die Kund:in eine verständliche Fehlermeldung