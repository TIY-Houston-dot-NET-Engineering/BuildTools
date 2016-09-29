```sh
# 1. create project in VisStudio
cd <project dir>
git init
curl https://raw.githubusercontent.com/TIY-Houston-dot-NET-Engineering/BuildTools/master/package.json > package.json
npm install
echo "node_modules" > .gitignore
hub create <PROJECTNAME>
npm run watch
# now edit and build as usual :-)
```


Example mixin in PostCSS:

```sass

@define-mixin grid_r $col, $width {
    	@media (min-width: $(width)px) {
            	.grid-$(col)-$(width) {
	                & > * {
		               width: calc(100 / $col)%;
		        }
	        }
	}
}
@mixin grid_r 2, 400;
@mixin grid_r 3, 600;
@mixin grid_r 4, 800;
@mixin grid_r 6, 1000;
```
