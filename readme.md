# Eksamen Template - En enkel nettstedtemplate med Flask

Dette er en enkel nettstedtemplate basert på Flask. Her finner du informasjon om hvordan du kan bruke og tilpasse prosjektet.

## Filer

* `app.py`: Python filen for nettstedet
* `templates/main.html`: html for nettstedets hovedside
* `static/style.css`: css for nettstedet

## Tilpasning

* For å endre fargen på knappen, rediger `style.css` og endre `background-color` for `.button`-klassen.
* For å endre fargen på bakgrunnen, rediger `style.css` og endre `background-color` for `.hero`-klassen.
* For å endre font formatet, rediger `style.css` og endre `font-family` for `.hero h1`-klassen.
* For å endre hvor knappen sender deg, rediger `main.html` og endre `href`-attributten for `<a>`-elementet.

## Enkelt forklart

#### Knapp
* For å endre hvor knappen leder til gå til href="https://www.example.com" class="button" target="_blank">Template</a i main.html filen, etter det kan du endre link til for eksempel https://google.com og knapen leder der
 
 
* For endre farge til knappen gå til .button i style.css og endre background-color: #3C3E56; og endre endre #3C3E56, 
 

* Du kan finne # koden for farger her : https://htmlcolorcodes.com/color-picker/

### Bakgrunnsfarge
* For endre bakgrunnsfarge bak knappen, gå til .section under style.css filen, deretter endre  background-color: #3F642F;
 

* For endre bakgrunnsfarge øverst på nettsiden gå til .hero under style.css filen, deretter endre   background-color: #6AA84F;
 

* Du kan finne # koden for farger her : https://htmlcolorcodes.com/color-picker/

### Tekst

  * For endre hva tekst sier, for eksempel endre fra Templete eller Eksamen, gå til de forskjellige stedene listet under her for endre dem
    * For endre tittel gå til body sektion under main.html
      * deretter velg eksamen eller eksamen template og endre det

    * For endre tekst over knappen gå til : section id="Template" class="section" eller p>Template</p for endre dem
    * For endre tekst på knapp gå til section id="Template" class="section" og velg a href="https://www.example.com" class="button" target="_blank">Template</a, helt bakerst står det target="_blank">Template</a, endre der det står template for endre hva står øver knappen