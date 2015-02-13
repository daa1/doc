# Stiler i editor


### Dersom man ser at noe flyter lenger ut til sidene enn selve teksten så kan man gjøre følgende:

```html
<div class="narrow">
	innhold som flyter for langt ut inni her.
</div>
```



### Det er også muligheter for å legge punktlister og tallister som en trekolonners i stedet for under hverandre

Eksempel:

```html
<ul class="three-column">
	<li><Innhold.../li>
	<li><Innhold.../li>
	... osv
</ul>
```

Ønsker man talliste i stedet så bruker man `<ol>` i stedet for `<ul>`


### Sette opp generelle kolonner

Det man har å jobbe med her er inndeling i enten 2, 3 eller 4 kolonner

Eksempel:

#### 2 kolonner

```html
<div class="box-container">
	<div class="column half">
		Valgfritt innhold
	</div>
	<div class="column half">
		Valgfritt innhold
	</div>
</div>
```

#### 3 kolonner

```html
<div class="box-container">
	<div class="column third">
		Valgfritt innhold
	</div>
	<div class="column third">
		Valgfritt innhold
	</div>
	<div class="column third">
		Valgfritt innhold
	</div>
</div>
```

#### 4 kolonner

```html
<div class="box-container">
	<div class="column fourth">
		Valgfritt innhold
	</div>
	<div class="column fourth">
		Valgfritt innhold
	</div>
	<div class="column fourth">
		Valgfritt innhold
	</div>
	<div class="column fourth">
		Valgfritt innhold
	</div>
</div>
```



### Lage last ned lenker

```html
<p>
	<a href="http://www.linkorama.no" class="download">Lenketekst</a>
</p>
```

Skal man ha flere lenker etter hverandre, lønner det seg ikke å bruke paragrafder, da det blir veldig mye luft. Bruker heller `<div>` for linjeskift her.
I tillegg blir det ofte en bred kolonne, derfor er det lagt `<div class="narrow">` rundt alle lenkene.

```html
<div class="narrow">
	<div>
		<a href="http://www.linkorama.no" class="download">Lenketekst</a>
	</div>
	<div>
		<a href="http://www.linkorama.no" class="download">Lenketekst</a>
	</div>
	<div>
		<a href="http://www.linkorama.no" class="download">Lenketekst</a>
	</div>
</div>
```


### Sammensatt eksempel

```html
<div style="overflow: hidden;">
  <div class="box loose fourth left">
     <div class="figure"><img alt="formater-sma" src="bildetekst" width="102" height="88" title="formater-sma"></div>
     <p class="heading">Inntil 0,5cm tykk for små sendinger</p>
     <ul>
        <li>Typisk for vanlige brev</li>
        <li>Lengde og brev inntil: 25 x 17,6cm</li>
     </ul>
  </div>
  <div class="box loose fourth left">
     <div class="figure"><img alt="formater-store" src="bildetekst" width="104" height="133" title="formater-store"></div>
     <p class="heading">Inntil 2cm tykk for store sendinger</p>
     <ul>
        <li>Typisk for større brev</li>
        <li>Lengde og bredde inntil: 35,3 x 25cm</li>
     </ul>
  </div>
  <div class="box loose fourth left">
     <div class="figure"><img alt="formater-ekstra-store" src="bildetekst" width="111" height="143" title="formater-ekstra-store"></div>
     <p class="heading">2-7cm for ekstra store sendinger</p>
     <ul>
        <li>Typisk for mindre pakker</li>
        <li>Lengde og bredde inntil: 35,3 x 25cm</li>
     </ul>
  </div>
  <div class="box loose fourth left">
     <div class="figure"><img alt="formater-ekstra-ekstra-store" src="bildesti" width="120" height="150" title="formater-ekstra-ekstra-store"></div>
     <p class="heading">Mer enn 7cm tykk for ekstra store sendinger</p>
     <ul>
        <li>Formattilleg</li>
        <li>Legnde og bredde mer enn 35,3 x 25cm. Lengde + bredde + tykkelse kan være inntil 90cm.</li>
     </ul>
  </div>
</div>
```

