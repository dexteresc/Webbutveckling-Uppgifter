# Dokumentation

Här är stegen jag har tagit för att rätta koden.

Det första felen jag såg var i den osorterade listan (rad: 41). I listan så saknade list objektet "Apelsiner" både sin öppnande och avslutade &lt;li> tagg. I samma lista saknade både "Päron" och "Citroner" sina avslutande &lt;li> taggar.

Det andra felet jag hittade var under nästlad lista 1 (rad: 43), där det saknas en avslutade &lt;ul>-tagg (&lt;/ul>) i slutet av listan. Jag la till &lt;/ul>-tagg på rad 55.

Det tredje felet jag hittade var i Nästlad lista 2 (rad: 56), där list objektet på rad 65 har en en extra avslutande &lt;li>-tagg (&lt;/li>).

Hela min process med alla mina ändringar är dokumenterade i git och publiserade på github under mappen code-correction.