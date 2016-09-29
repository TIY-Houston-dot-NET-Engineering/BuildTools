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
````
