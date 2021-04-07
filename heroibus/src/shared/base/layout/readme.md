# layout styles

> Defines all styles for layouting

## Grid

-  [Bootstrap 4 Grid - Documentation](https://getbootstrap.com/docs/4.0/layout/grid/)
-  [NPM - Package](https://www.npmjs.com/package/bootstrap-4-grid)

## Wrapping a component

```html
<section class="l-outer">
	<div class="container">
		<div class="l-inner">
			<div class="row">
				<div class="col">
					<!--- Your Component --->
				</div>
			</div>
		</div>
	</div>
</section>
```

-  `l-outer` class defines the spacing outside of the comoponent (e.g. spacing between to separated components).

-  `l-inner` class defines the spacing within the compoonent (e.g. inner spacing of the parent wrapper).
