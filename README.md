```
git clone -b dspace-7.6 git@github.com:DSpace/dspace-angular.git
```

```
git clone git@github.com:yorkulibraries/yorkspace-theme.git
```

Rename "dspace-angular/" with the folder name of your project.
```
rsync -a --exclude=.git yorkspace-theme/ dspace-angular/ 
```