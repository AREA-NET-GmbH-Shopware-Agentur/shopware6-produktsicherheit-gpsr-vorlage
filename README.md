# Shopware 6: Vorlage zur Umsetzung der GPSR (Produktsicherheitsverordnung der EU) auf der Produktdetailseite

Das Repository dient nur der Anschauen und sollte nicht 1:1 in eine Produktivumgebung integriert werden.

## Unterstützte Shopware Versionen
- **6.6.x**

## Beschreibung

Die Hintergründe über die Produktsicherheits-Verordnung der EU (GPSR = General Product Safety Regulation) finden Sie in unserem Blogbeitrag vom 01.10.2024:

- [www.area-net.de/agentur-news/produktsicherheit-gpsr-shopware-6/](https://www.area-net.de/agentur-news/produktsicherheit-gpsr-shopware-6/)

### Zusatzfelder zum Hersteller anlegen
Im ersten Schritt müssen Sie für die erforderlichen Informationen ein Zusatzfeld für die Hersteller anlegen. Es steht Ihnen natürlich frei die genaue Konfiguration und/oder Felder noch anzupassen. 

- Gehen Sie auf “Einstellungen->System->Zusatzfelder”
- Legen Sie dort ein neues Set an
  - Technischer Name. custom_gpsr
  - Position: 1
  - Label: GPSR
  - Verwenden für: Hersteller
- Legen Sie für dieses neue Set dann ein Zusatzfeld an:
  - Typ: Text-Editor
  - Technischer name: custom_gpsr_manufacturer_contact
  - Label: Kontaktadresse

Über dieses Zusatzfeld können Sie dann iun Zukunft die genaue Adresse, sowie eine verlinkte E-Mail-Adresse zu jedem Hersteller eingeben. Das Zusatzfeld wird über die Template-Vorlage im Repository entsprechend auf der Produktdetailseite ausgespielt.

**ACHTUNG: Unser [aloha Theme](https://store.shopware.com/en/arean62788672693m/a-better-cms-theme-optimized-checkout-b2b-functions-flexibly-customizable.html) unterstützt die GPSR ab Ende Oktober Out-Of-the-Box!**

## Hilfe und Support

Wir bieten zu unseren Open-Source-Plugins kostenpflichtigen Support and

* [Online-Formular](https://www.area-net.de/kontakt)
* [shopware@area-net.de](mailto:shopware@area-net.de)

## Shopware Theme und Plugins

Neben kostenlosen Open-Source Shopware-Plugins bietet die Shopware-Agentur auch Themes und Plugins im Shopware-Store an:

- [aloha Theme](https://store.shopware.com/en/arean62788672693m/a-better-cms-theme-optimized-checkout-b2b-functions-flexibly-customizable.html) mit optimiertem Checkout
- [aloha CMS Elements](https://store.shopware.com/arean13931131788m/a-better-cms-elements-slider-bilder-html5-video-google-maps-vorher-nachher-bilder.html) mit umfangreichen Erweiterungen der Standard-Inhaltselemente
- [Pagespeed Booster](https://store.shopware.com/arean41766445685m/pagespeed-booster-paypal-und-externe-skripte-auf-der-startseite-deaktivieren.html) deaktiviert PayPal und Co. auf der Startseite
- [Optimierte Inhaltsbearbeitung](https://store.shopware.com/arean36129443353f/optimierte-inhaltsbearbeitung-inhalte-nur-im-designer-bearbeiten-inhalte-in-layout-uebertragen.html) für CMS-Seiten und Kategorien
- [HTTP-Auth](https://store.shopware.com/arean97586892435f/http-authentifizierung-fuer-verkaufskanaele.html) für Verkaufskanäle

## AREA-NET GmbH
Die AREA-NET GmbH ist Shopware Partner Agentur und Shopware Hersteller, sowie Pickware Partner aus dem Großraum Stuttgart in Baden-Württemberg/Deutschland.

**Adresse**\
Öschstrasse 33\
73072 Donzdorf

Telefon: +49 (0)7162 - 941140\
Mail: [shopware@area-net.de](mailto:shopware@area-net.de)\
Web: [www.area-net.de](https://www.area-net)

Mehr Informationen, Projektanfragen und Support gibt es auf der Website der [Shopware-Agentur AREA-NET GmbH](https://www.area-net.de).

**Follow us**

- https://linkedin.com/companyarea-net-gmbh-shopware-agentur
- https://www.facebook.com/area.net.gmbh

