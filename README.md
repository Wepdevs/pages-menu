# pages-menu
a polymer element that creates a menu from the iron-pages of the page

every direct child of the iron-pages element should have these attributes:
- role="page": required
- name="name": will appear in the label
- icon="iron-icon-name": from iron icon collection
- order="number" : order of appearance in the menu

element must be registered via element.registration() method

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
