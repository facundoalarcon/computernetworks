# Pasos
```
git init
git remote add origin <REMOTE_URL>
git branch -M main
git add .
git commit -m "First commit"
git push -u origin main
```
Para crear un PR deberás crear un nuevo branch
```
git branch -M new-branch-name
git add .
git commit -m "new commit"
git push -u origin new-branch-name
```

Podes crear un archivo ```.gitignore``` para excluir archivos o carpetas y en vez de usar ```git add .``` podrías incluit sólo los archivos que necesites.

Una vez hecho esto y finalizado correctamente el workflow esperar al review de los instructores.

## Links de referencia
- [instalar git](https://github.com/git-guides/install-git)
- [crear un repositorio en github](https://docs.github.com/en/get-started/quickstart/create-a-repo)
