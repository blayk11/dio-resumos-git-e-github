Repositório para armazenar descrição sobre comandos Git e GitHub do curso Versionamento de Código com Git e GitHub da [Digital Innovation One](https://www.dio.me/).

## 📚 Documentação

- [Documentação Git](https://git-scm.com/doc)
- [Documentação GitHub](https://docs.github.com/)

## 💻 Resumos

| Comando | Descrição |
| --- | --- |
| git init | Inicializa o diretório como repositório git local |
| git add/rm <file> | Adiciona/remove arquivos criados para commit |
| git commit  -m “mensagem” | Faz o commit do repositório localmente |
| git remote add origin URL | Vincula o repositório local ao remoto |
| git push origin main | Publica as alterações, origin é o repositório remoto e main o branch principal |
| git pull origin main | Baixa as alterações, origin é o repositório remoto e main o branch principal |
| git clone URL <nome da pasta> | Clona o repositório remoto, o nome alterado da pasta é opcional |
| git clone URL  —branch BranchName —single-branch | Clona apenas uma branch específica |
| git status | Status da arvore de trabalho e index |
| .gitignore | Ignora um diretório/arquivo ao fazer commit |
| .gitkeep | Reconhece um diretório vazio ao fazer commit |
| git log | Histórico dos commits |
| git restore’ | Restaura a última versão salva do arquivo |
| git commit —amend -m | Altera a mensagem do último commit feito |
| git reset —soft / —mixed / —hard HASH | Restaura o repositório para uma versão de um commit anterior (buscar docs para os diferentes parâmetros) |
| git reflog | Histórico detalhado dos commits |
| git reset <file> | Desfazer alterações em um repositório |
| git restore —staged <file> | Remove o arquivo da área de preparação |
|  |  |