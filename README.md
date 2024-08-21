# 2438-angular-memoteca
Repositório para o curso Alura - Angular 14 - aplique os conceitos e desenvolva seu primeiro CRUD


### Remover versões anteriores do Angular:
```
npm uninstall -g @angular/cli
```

### Instalar a versão 14 do Angular:
```
sudo npm install -g @angular/cli@14.0.0
```

### Nota:
Se você estiver no Linux é possível que a instalação do Angular Cli quebre o terminal, fazendo com que ele não carregue corretamente. Caso isso aconteça:

1. Edite o arquivo oculto **~/.bashrc**.
2. Remova a última linha do comando Angular: "source <(ng completion script)".
3. Salve o arquivo.


### Para criar um novo componente:
```
ng generate component nome-do-componente
```