it remote -v # Estudo de Node
## Arquitetura em DDD e padrões de projeto

Configuração de alias para Git
```
git config --global core.editor code
git config --global --edit

[alias]
	s = !git status
	c = !git add --all && git commit -m
	l = !git log --pretty=format:'%C(blue)%h%C(red)%d %C(white)%s - %C(cyan)%cn, %C(green)%cr'

```


Git commit message linter -> Persiste e convenção de commits
```
git-commit-msg-linter
```

Eslint dar suporte ao typescript
```
https://www.npmjs.com/package/eslint-config-standard-with-typescript
npm install --save-dev eslint@^7.12.1 eslint-plugin-promise@^5.0.0 eslint-plugin-import@^2.22.1 eslint-plugin-node@^11.1.0 @typescript-eslint/eslint-plugin@^4.0.1 eslint-config-standard-with-typescript@latest
```

Husky, define hooks para o commit, comandos que serão executados antes de um commit ou push
Lint-staged vai atuar junto com o husky para que o eslint apenas verifique os novos arquivos que estão na stage area, não todo o projeto
```
https://www.npmjs.com/package/husky
https://www.npmjs.com/package/lint-staged
```

TDD
```
npm install -D jest @types/jest ts-jest
```
