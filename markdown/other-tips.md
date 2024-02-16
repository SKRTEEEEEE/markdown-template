# Other Tips

## Markdown

-       asi se hace una caja en markdown


elemnto 1 | elemento 2 | elemento 3
|---|---|---|

## Git

### Repositorio temporal

- 1 Clona el repositorio en una carpeta temporal.
- 2 Mueve los archivos del repositorio clonado a la ubicación deseada.
- 3 Elimina la carpeta temporal.

```bash
git clone URL_del_repositorio tmp_repo
mv tmp_repo/* .
rm -rf tmp_repo
```

### Git pull especial
*Después de ejecutar este comando, Git intentará fusionar las historias de las dos ramas. Sin embargo, ten en cuenta que es posible que tengas que resolver conflictos si existen diferencias significativas entre las ramas.*

```bash
git pull origin main --allow-unrelated-histories
```
