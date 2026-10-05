# Data - Datasets locales al repositorio

Los Datasets necesarios para las prácticas de este repositorio son los siguientes:

* 01 - winemag-data-130k-v2.csv (Vinos)
* 02-  CAVideos.csv (Videos de Canadá)
* 02 - GBVideos.csv (Videos de Gran Bretaña)

En caso de requerir [Git Large File Storage](https://git-lfs.com/) usar los comandos:

```
git lfs track "*.csv"
git add .gitattributes
git add file.csv
git commit -m "Add Dataset"
git push origin main
```
