# Here is a github clone of the Flight Course Boeing 737-400

## Manual:

https://docs.google.com/document/d/1b9Db9eNuceENqdhMknKhC-VAVBTbJKlV8co9bgBrowI/edit?usp=sharing

### Creating a release:

1. Stage changes with `git stage .` and check that you have only changed the intended files with `git diff --cached --name-only`
2. If you have changed any of the files, contact @SuitablyMysterious as they run the DVC remote
3. Commit your changes with something along the lines of `git commit -m "<Insert commit title here>"`
4. Tag the commit for release with `git tag -a v<release number> -m "<commit message>" <hash of the commit>`
5. Push to origin with `git push origin`
6. Workflows will update skunkcrafts and release pages automatically

### Git clone:

***DO NOT INSTALL BY CLONING UNLESS YOU ARE VERY SURE ABOUT WHAT YOU ARE DOING***

1. Clone the repo using ssh or https
2. Install dvc (see [documentation](https://doc.dvc.org/install))
3. Pull files from @SuitablyMysterious 's machine with `dvc pull`
