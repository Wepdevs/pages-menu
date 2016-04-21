# pages-menu
a polymer element that creates a menu from the iron-pages of the page

la lista dev'essere di questo tipo, ogni elemento 'pagina' deve avere un attributo role ="page", name="qualcosa" (per il label del menu)
e un icon="nome-iron-icon" se si vuole aggiungere un'icona e un order (per l'ordine di apparizione sul menu).


```HTML
<iron-pages id="ironpages" selected="0">
				<div role="page" name="Login" order="1" icon="info">
				</div>
				<div role="page" name="Languages" order="2" icon="language">
				</div>
				<div role="page" name="Categories" order="3" icon="maps:local-offer">
				</div> 
				<div role="page" name="Import" order="4" icon="input">
				</div>
</iron-pages> 
```
