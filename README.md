```sh
# 1. create project in VisStudio
cd <project dir>
git init
curl https://raw.githubusercontent.com/TIY-Houston-dot-NET-Engineering/BuildTools/master/package.json > package.json
npm install
echo "node_modules" > .gitignore
hub create <PROJECTNAME>

# now edit and build as usual :-)
````
