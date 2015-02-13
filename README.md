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

Skal man ha flere lenker etter hverandre, lønner det seg ikke å bruke paragrafder, da det blir veldig mye luft. Bruker heller `div` for linjeskift her.
I tillegg blir det ofte en bred kolonne, derfor er det lagt ´<div class="narrow">´ rundt alle lenkene.

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
