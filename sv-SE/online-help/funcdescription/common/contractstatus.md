
<style> 
h1 { font-size:24px; } 
h2 { font-size:22px; } 
h3 { font-size:20px; } 
h4 { font-size:18px; } 
h5 { font-size:16px; }  
table th { font-size:14px !important; text-align:left !important; }
table td { font-size:14px !important; text-align:left !important; }
</style>

# Avtalets status

I den övre sektionen på avtalet visas avtalets status. Avtalets status kan ha följande värden:

#### Värden för avtalets status
* Utkast: När avtalet har påbörjats, men är ännu inte klart. Ingen statusbricka visas.

* Aktivt - Gäller inte än: När avtalets startdatum är senare än idag. Statusbrickan är orange.

* Aktivt: När idag är senare än avtalets startdatum och avtalets slutdatum är senare än idag minus 14 dagar (alltså mer än 14 dagar före slutdatum infaller). Statusen Aktivt visas också när idag är senare än avtalets startdatum och avtalets slutdatum saknas helt. Statusbrickan är grön.

* Aktivt - Slutar snart gälla: När avtalets slutdatum är senare än idag och idag är senare än avtalets slutdatum minus 14 dagar (alltså 1-14 dagar före avtalets slutdatum infaller). Statusbrickan är orange.

* Aktivt - Just slutat gälla: När idag är senare än avtalets slutdatum och avtalets slutdatum plus 14 dagar är senare än idag (alltså 1-14 dagar efter att avtalets slutdatum har infallit). Statusbrickan är röd.

* Aktivt - Inte längre giltigt: När idag är senare än avtalets slutdatum plus 14 dagar (alltså mer än 14 dagar efter att avtalets slutdatum infallit). Statusbrickan är röd.

* Avslutat: När avtalets slutdatum har passerats och avtalet aktivt har avslutats. Statusen Avslutat visas också när avtalets slutdatum saknas helt och avtalet aktivt har avslutats. Statusbrickan är röd.

* Ej ännu implementerat! Avbrutet: När avtalets slutdatum inte har passerats än men avtalet aktivt har avbrutits. Statusen Avbrutet visas också när avtalets slutdatum saknas helt och avtalet aktivt har avbrutitis. Statusbrickan är röd.















