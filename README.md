
## Keyrsla á verkefni ##

Til að keyra verkefnið þarf að gera eftirfarandi skipanir:

```bash
npm install
npm run dev
```

Til að keyra stylelint þarf:

```bash
npm run lint-scss
```

## Skipulag verkefnis ##

### HTML ###

Vefsíðunni er skipt upp í eftirfarandi html skjöl:

* _index.html_
    * Sér um uppsetningu á forsíðu
* _cart.html_
    * Sér um uppsetningu á körfusíðu
* _products.html_
    * Sér um uppsetningu á yfirlitssíðu um vörur
* _staff.html_
    * Sér um uppsetningu á upplýsingasíðu um starfsfólk

index.html er í aðalmöppu verkefnisins, en hinar síðurnar eru í möppunni pages.

Footer og header eru alveg eins inni í öllum skjölum, voru skrifaðir upphaflega í index, en afritaðir í hin skjölin.

### CSS/SCSS ###

Styles.css í aðalmöppu inniheldur allar útlitsstillingar fyrir öll html skjölin. 
Þessar upplýsingar fær styles.css úr styles.scss inni í scss möppunni, sem inniheldur nokkrar grunnstillingar
en importar síðan nokkrum aðskildum scss skrám með útlitsstillingar fyrir mismunandi síður og atriði.
Þessar síður eru allar í scss möppunni og eru eftirtaldar:

* _index.scss_
    * Sér um útlit á index.html, fyrir forsíðu
* _karfa.scss_
    * Sér um útlit á cart.html, fyrir körfusíðu
* _products.scss_
    * Sér um útlit á products.html, fyrir vörusíðu
* _staff.scss_
    * Sér um útlit á staff.html, fyrir starfsmannasíðu
* _header.scss_
    * Sér um útlit á header, á öllum síðum
* _footer.scss_
    * Sér um útlit á footer, á öllum síðum
* _config.scss_
    * Inniheldur nokkrar breytur og föll sem nýtast í öllum scss skjölunum

### Annað ###

* Allar myndir sem notaðar eru í verkefninu eru í möppunni img
* node_modules inniheldur uppsett npm tæki og tól
* package.json inniheldur scripts til að keyra tól eins og sass-watch og stylelint

## Upplýsingar um hönnuði ##

* _Sunna Björnsdóttir_
    * Tölvupóstfang: sub4@hi.is
    * Hafði yfirumsjón með körfu og starfsfólki
* _Auður Margrét Pálsdóttir_
    * Tölvupóstfang: amp16@hi.is
    * Hafði yfirumsjón með forsíðu, header og footer
* _Katla Rún Ísfeld_
    * Tölvupóstfang: kri9@hi.is
    * Hafði yfirumsjón með vörusíðu



