# gshool-git

O seu objetivo é clonar o projeto gshool-git, acessar o arquivo index.html e alterar o conteúdo da tag `<td>` para o seu nome completo. Em seguida, você deve criar um commit com a mensagem "Alteração do nome completo" e enviar as alterações para o repositório remoto.

O esperado é que você siga os seguintes passos:
1. Clonar o repositório gshool-git:
```bash
git clone <URL_DO_REPOSITORIO>
```
2. Acessar o diretório do projeto:
```bash
cd gshool-git
```
3. Abrir o arquivo index.html em um editor de texto e localizar a tag `<td>`. Alterar o conteúdo dessa tag para o seu nome completo.
4. Salvar as alterações e fechar o editor de texto.
5. Criar uma branch para a alteração:
```bash
git checkout -b alteracao-nome 

            ou

git switch -c alteracao-nome
```
5. Adicionar as alterações ao índice do Git:
```bash
git add index.html
```
6. Criar um commit com a mensagem "Alteração do nome completo":
```bash
git commit -m "Alteração do nome completo"
```
7. Enviar as alterações para o repositório remoto:
```bash
git push origin alteracao-nome
```
8. Criar um Pull Request (PR) no repositório remoto para que as alterações sejam revisadas e mescladas na branch principal.

