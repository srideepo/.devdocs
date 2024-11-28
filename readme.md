
## Git
`git init`  
`git remote add origin {remote url}`  

Push repo with auth
```  
git push https://srideepo@github.com/srideepo/.devdocs.git main
```

Push shortcut  
```
git push --set-upstream https://srideepo@github.com/srideepo/.devdocs.git main
```
thereafter you can  
```
git push
```

## Docker
Ref: https://dockerlabs.collabnix.com/docker/cheatsheet/
![image](media/dockercheatsheet8.png)

## Data Lineage
OpenLineage - https://www.youtube.com/watch?v=SZBVgREqets 

## wsl
shrink docker vhdx file  
ps >
```   
    wsl --terminate Ubuntu
    diskpart
    select vdisk file="%APPDATA%/local/docker/wsl/data/ext4.vhdx"
    compact vdisk
```