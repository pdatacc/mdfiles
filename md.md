# Markdown cheatsheet

## Nagłówki

# Nagłówek stopnia pierwszego H1
## Nagłówek stopnia drugiego H2
### Nagłówek stopnia trzeciego H3
#### Nagłówek stopnia trzeciego H4
##### Nagłówek stopnia trzeciego H5
###### Nagłówek stopnia szóstego H6

***

## Listy

* element 1
* element 2
* element 3

1. element 1
2. element 2
3. element 3

***

## Formatowanie tekstu

**Pogrubienie**
*Pochylenie*
~~przekreślenie~~
[link](http:/clearcode.pl/)
`const kod = function(makeMeLookLikeACode)`
> cytat

***
## Zdjęcie

![zdjęcie](https://clearcode.pl/wp-content/uploads/2021/04/ill_chrome_mobile-phone-adtech-graphic-01.png?ver=1619600342)

***
## Kod

```
<nav class="pagination">
	<div class="wrapper">
	  {{#if prev}}
		  <a href="{{page_url prev}}" class="button rounded light next"><span class="sub"><i class="icon icon-angle-left"></i></span><span class="main">Nowsze wpisy</span></a>
	{{/if}}
	   {{#if next}}
		  <a href="{{page_url next}}" class="button rounded light previous"><span class="main">Starsze wpisy</span><span class="sub"><i class="icon icon-angle-right"></i></span></a>
	   {{/if}}
	</div>
</nav>
 ```
 