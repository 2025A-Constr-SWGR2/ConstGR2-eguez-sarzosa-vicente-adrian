## Instalar un repositorio en nuestro repositorio

Para instalar un repositorio dentro de nuestro repositorio solamente necesitamos tener los permisos necesarios de la plataforma (github, gitlab, bitbucket u otros) Y correr el siguiente comando (para esto vamos a usar un repositorio de ejemplo )

```bash
git submodule add https://github.com/2025A-Constr-SWGR1/Const-GR1-granizo-ayala-dylan-jhossue.git submodulos
```

Con este comando vamos a poder anadir un repositorio dentro de nuestro repositorio y poder hacer commits y cambios al otro repositorio. Podemos usar simplemente la interfaz de `Visual Studio Code` para esto anadiendo los archivos necesarios.

Este nuevo repositorio puede trabajar en diferentes ramas y todo lo relacionado a git exactamente como un repositorio de git normal.