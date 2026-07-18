<table>
<thead>
<tr>
<th>Class</th>
<th>Variable name</th>
<th>Description</th>
<th>Values</th>
<th>Coding rules</th>
<th>Source</th>
</tr>
</thead>

<tbody>

<tr>
<td rowspan="2">IDENTITY</td>
<td>festival_id</td>
<td>Identificativo alfanumerico del festival</td>
<td>Schema: IT-PHO-000001</td>
<td>ID univoco assegnato al record del festival</td>
<td>-</td>
</tr>

<tr>
<td>festival_name</td>
<td>Nome del festival</td>
<td>Testo</td>
<td>Utilizzare il nome più ricorrente e ufficiale; evitare sottotitoli se inconsistenti tra le fonti</td>
<td>-</td>
</tr>


<tr>
<td rowspan="5">LOCATION</td>
<td>city</td>
<td>Città in cui si svolge il festival</td>
<td>Denominazioni ufficiali ISTAT</td>
<td>Inserire esclusivamente la città principale. Nei rari casi di festival multi-sede, scegliere la sede legale o l'hub principale. Indicare nelle note eventuali altre sedi o carattere itinerante.</td>
<td>-</td>
</tr>

<tr>
<td>city_geonames_id</td>
<td>Codice identificativo della città secondo GeoNames</td>
<td>Codice numerico</td>
<td>-</td>
<td>GeoNames</td>
</tr>

<tr>
<td>region</td>
<td>Regione italiana in cui si svolge il festival</td>
<td>Denominazioni ufficiali ISTAT</td>
<td>-</td>
<td>-</td>
</tr>

<tr>
<td>region_nuts</td>
<td>Regione italiana rappresentata come codice NUTS</td>
<td>Codice NUTS2 (Eurostat)</td>
<td>-</td>
<td>Eurostat NUTS classification</td>
</tr>

<tr>
<td>country_iso</td>
<td>Paese in cui si svolge il festival</td>
<td>ISO 3166-1 alpha-2</td>
<td>Codice paese per garantire scalabilità futura</td>
<td>ISO</td>
</tr>


<tr>
<td rowspan="4">TIME</td>
<td>festival_edition_start_year</td>
<td>Anno della prima edizione del festival</td>
<td>Anno / unknown</td>
<td>Estrarre da sito ufficiale o fonti affidabili</td>
<td>YOUROPE – The European Festival Association &amp; ILMC (2026). European Festival Report 2025.</td>
</tr>

<tr>
<td>festival_status</td>
<td>Stato di attività del festival al momento della raccolta dati</td>
<td>active / inactive / defunct / unknown</td>
<td>
<b>active:</b> edizione negli ultimi 18-24 mesi oppure date/open call future annunciate.<br>
<b>inactive:</b> nessuna edizione negli ultimi 2 anni, ma canali online ancora presenti.<br>
<b>defunct:</b> chiusura dichiarata ufficialmente.<br>
<b>unknown:</b> dati insufficienti o contrastanti.
</td>
<td>-</td>
</tr>

<tr>
<td>duration_days</td>
<td>Durata del festival in giorni</td>
<td>Numero / unknown</td>
<td>
Conteggio inclusivo del giorno iniziale e finale.<br>
Se le mostre rimangono aperte oltre l'evento inaugurale viene considerato l'intero periodo.<br>
Viene utilizzata l'edizione più recente.
</td>
<td>YOUROPE – The European Festival Association &amp; ILMC (2026). European Festival Report 2025.</td>
</tr>

<tr>
<td>recurrence</td>
<td>Ciclicità del festival</td>
<td>annual / biennial / mixed / unknown</td>
<td>
annual: ogni anno.<br>
biennial: ogni due anni.<br>
mixed: variazione della frequenza nel tempo.<br>
unknown: informazioni insufficienti.
</td>
<td>-</td>
</tr>


<tr>
<td rowspan="6">DIGITAL PRESENCE</td>
<td>website_official</td>
<td>Sito web ufficiale del festival</td>
<td>URL / null</td>
<td>Inserire esclusivamente il sito ufficiale</td>
<td>European Commission (2023). Creative Europe 2021-2022: Monitoring report.</td>
</tr>

<tr>
<td>website_secondary</td>
<td>Sito secondario o istituzionale contenente informazioni sul festival</td>
<td>URL / null</td>
<td>Inserire solo quando non esiste un sito ufficiale</td>
<td>European Commission (2023). Creative Europe 2021-2022: Monitoring report.</td>
</tr>

<tr>
<td>website_active</td>
<td>Presenza di un sito ufficiale aggiornato</td>
<td>0 / 1</td>
<td>
1: sito aggiornato con edizioni recenti.<br>
0: sito non aggiornato o assente.
</td>
<td>European Commission (2023). Creative Europe 2021-2022: Monitoring report.</td>
</tr>

<tr>
<td>website_languages</td>
<td>Lingue disponibili sul sito ufficiale o secondario</td>
<td>IT_EN / IT_ONLY / MULTI</td>
<td>
IT_EN: italiano + inglese.<br>
IT_ONLY: solo italiano.<br>
MULTI: italiano, inglese e altre lingue.
</td>
<td>European Commission (2023). Creative Europe 2021-2022: Monitoring report.</td>
</tr>

<tr>
<td>instagram</td>
<td>Profilo Instagram ufficiale del festival</td>
<td>URL / null</td>
<td>Inserire esclusivamente profilo ufficiale</td>
<td>European Commission (2023). Creative Europe 2021-2022: Monitoring report.</td>
</tr>

<tr>
<td>facebook</td>
<td>Pagina Facebook ufficiale del festival</td>
<td>URL / null</td>
<td>Inserire esclusivamente pagina ufficiale</td>
<td>European Commission (2023). Creative Europe 2021-2022: Monitoring report.</td>
</tr>

</tbody>
</table>
