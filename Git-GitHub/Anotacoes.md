# Anotações sobre o curso de Git/GitHub
## Comandos importantes



### Configuração Inicial

Configura seu nome e email para os commits.
```bash
git config --global user.name "Seu Nome"
git config --global user.email "seuemail@example.com"
```

### Criar e Clonar Repositório

Inicializa um repositório Git na pasta atual.
```bash
git init
```

Clona um repositório remoto para sua máquina.
```bash
git clone URL_DO_REPOSITORIO
```

### Adicionar e Confirmar Alterações

Mostra o status das alterações no repositório.
```bash
git status
```

Adiciona todas as alterações ao staging.
```bash
git add .
```

Confirma as alterações com uma mensagem descritiva.
```bash
git commit -m "Mensagem do commit"
```
### Trabalhando com Branches
Lista todas as branches.
```bash
git branch
```
