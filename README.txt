=== Bibvenn infoboks ===
Contributors: sundaune
Tags: aviser, bilder, bøker, bok, ISBN, info, anmeldelse, litteratur, bibvenn, nasjonalbiblioteket, metadata, infoboks
Requires at least: 4.0
Tested up to: 4.3
Stable tag: 1.0.2
License: GPLv3
License URI: http://www.gnu.org/licenses/gpl-3.0.html

Insert metadata in posts automatically from ISBN or URL at www.nb.no. Norwegian: Oppi ISBN eller URL fra www.nb.no, få infoboks med metadata etc.

== Description ==

This plugin enables a shortcode that allows you to input either a valid ISBN number or a URL to an item in the National Library of Norway (starting with http://urn.nb.no..) into your posts and pages. Info about the item is then retrieved from various sources, and a nicely formatted info box with a book cover (where available) and various metadata about the book (titel, author, number of pages etc.) is output. The box can be styled using the included CSS file. For your convenience, a button to insert the shortcode is also added to the toolbar in the Wordpress editor screen.

NORWEGIAN:

Dette innstikket gir deg en kortkode hvor du kan putte inn enten et gyldig ISBN-nummer eller en URL til et objekt i Nasjonalbiblioteket (begynner med http://urn.nb.no..) og få tilbake en pen infoboks med info hentet fra forskjellige kilder (omslag, metadata og andre ting). Boksens utseende kan tilpasses ved hjelp av den inkluderte CSS-filen. For ekstra komfort legger innstikket også til en knapp på verktøylinjen i redigeringsskjermen i Wordpress, som du kan klikke på for å sette inn kortkoden. 

== Installation ==

= Uploading the plugin via the Wordpress control panel =

Make sure you have downloaded the .zip file containing the plugin. Then:

1. Go to 'Add' on the plugin administration panel
2. Proceed to 'Upload'
3. Choose the .zip file on your local drive containing the plugin
4. Click 'Install now'
5. Activate the plugin from the control panel

= Upload the plugin via FTP =

Make sure you have downloaded the .zip file containing the plugin. Then:

1. Unzip the folder 'finnlokalhist' to your local drive
2. Upload the folder 'finnlokalhist' to the '/wp-content/plugins/' folder (or wherever you store your plugins)
3. Activate the plugin from the control panel

= Or install it via the Wordpress repository! =

To place the search form in your post/page, simply insert this shortcode:

[bibvenn_infoboks id=XXX]

where XXX is either a valid ISBN number (eg. 978-82-8255-025-3) or the URL to an item in the National Library of Norway's collections (eg. http://urn.nb.no/URN:NBN:no-nb_digibok_2007072000051). You can also use the toolbar button to insert this shortcode, in which case you will be prompted for the ID.

NORWEGIAN:

= Laste opp innstikket i kontrollpanelet for Wordpress =

Sørg for at du har lastet ned ZIP-filen som inneholder innstikket. Deretter:

1. Gå til 'Legg til' på administrasjonssiden for innstikk
2. Gå til 'Last opp'
3. Velg ZIP-filen som inneholder innstikket på harddisken din
4. Klikk 'Installer nå'
5. Aktiver innstikket fra kontrollpanelet

= Laste opp innstikket via FTP =

Sørg for at du har lastet ned ZIP-filen som inneholder innstikket. Deretter:

1. Pakk ut mappen 'finnlokalhist' til datamaskinen din
2. Last opp mappen 'finnlokalhist' til '/wp-content/plugins/'-katalogen under din Wordpress-installasjon
3. Aktiver innstikket fra kontrollpanelet

= Eller installér det via Wordpress-katalogen! =

For å sette inn søkeboksen på siden eller i innleget ditt, bruk følgende kortkode:

[bibvenn_infoboks id=XXX]

der XXX er enten et gyldig ISBN-nummer (for eksempel 978-82-8255-025-3) eller en URL til et objekt i Nasjonalbibliotekets samlinger (f.eks. http://urn.nb.no/URN:NBN:no-nb_digibok_2007072000051). Du kan også bruke knappen på verktøylinja i redigeringsskjermen til å sette inn kortkoden - da vil du bli spurt om å oppgi ID-en.

== Frequently Asked Questions ==

= Why are there no frequently asked questions? =

Because the plugin is so new that no question has had the chance to become frequent yet!

NORWEGIAN:

= Hvorfor er det ingen Ofte Stilte Spørsmål? =

Fordi dette er første versjon - spørsmålene kommer nok etter hvert.

== Screenshots ==
1. An example of an info box inserted into the page

NORWEGIAN:

1. Slik kan infoboksen se ut

== Change log ==

= 1.0.2 = 

* Bugfix: Nasjonalbiblioteket changed their URL for cover image retrieval

= 1.0.1 = 

* Bugfix: updated code to avoid functions conflicting with other addons

= 1.0 =

* First version

NORWEGIAN:

= 1.0.2 = 

* Bugfix: Nasjonalbiblioteket hadde byttet ut URL-en for å hente bokomslag

= 1.0.1 =

* Bugfix: Oppdaterte koden for å unngå konflikter med andre utvidelser

= 1.0 =

* Første versjon

== Upgrade Notice ==

No upgrade notice at this point

NORWEGIAN:

Ingen oppgraderingsmerknader akkurat nå
