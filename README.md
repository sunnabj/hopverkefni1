
Markup :  ## Keyrsla á verkefni ##

Til að keyra verkefnið þarf að gera eftirfarandi skipanir:

```bash
npm install
npm run dev
```

Til að keyra stylelint þarf:

```bash
npm run lint-scss
```

Markup :  ## Skipulag verkefnis ##

Markup:  ### HTML ###

Vefsíðunni er skipt upp í eftirfarandi html skjöl:

Markup : * index.html
            * Sér um uppsetningu á forsíðu
         * cart.html
            * Sér um uppsetningu á körfusíðu
         * products.html
            * Sér um uppsetningu á yfirlitssíðu um vörur
         * staff.html
            * Sér um uppsetningu á upplýsingasíðu um starfsfólk

index.html er í aðalmöppu verkefnisins, en hinar síðurnar eru í möppunni pages.

Footer og header eru alveg eins inni í öllum skjölum, voru skrifaðir upphaflega í index, en afritaðir í hin skjölin.

Markup :  ### CSS/SCSS ###

Styles.css í aðalmöppu inniheldur allar útlitsstillingar fyrir öll html skjölin. 
Þessar upplýsingar fær styles.css úr styles.scss inni í scss möppunni, sem inniheldur nokkrar grunnstillingar
en importar síðan nokkrum aðskildum scss skrám með útlitsstillingar fyrir mismunandi síður og atriði.
Þessar síður eru allar í scss möppunni og eru eftirtaldar:

Markup : * index.scss
            * Sér um útlit á index.html, fyrir forsíðu
         * karfa.scss
            * Sér um útlit á cart.html, fyrir körfusíðu
         * products.scss
            * Sér um útlit á products.html, fyrir vörusíðu
         * staff.scss
            * Sér um útlit á staff.html, fyrir starfsmannasíðu
         * header.scss
            * Sér um útlit á header, á öllum síðum
         * footer.scss
            * Sér um útlit á footer, á öllum síðum
         * config.scss
            * Inniheldur nokkrar breytur og föll sem nýtast í öllum scss skjölunum

Markup : ### Annað ###

Markup : * Allar myndir sem notaðar eru í verkefninu eru í möppunni img
         * node_modules inniheldur uppsett npm tæki og tól
         * package.json inniheldur scripts til að keyra tól eins og sass-watch og stylelint

Markup :  ## Upplýsingar um hönnuði ##

Markup : * Sunna Björnsdóttir
            * Tölvupóstfang: sub4@hi.is
            * Hafði yfirumsjón með körfu og starfsfólki
         * Auður Margrét Pálsdóttir
            * Tölvupóstfang: amp16@hi.is
            * Hafði yfirumsjón með forsíðu, header og footer
        * Katla Rún Ísfeld
            * Tölvupóstfang: kri9@hi.is
            * Hafði yfirumsjón með vörusíðu



