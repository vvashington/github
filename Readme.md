Alterando o arquivo
Ao Criar ou fazer alguma alteração no arquivo
1 - Untracked
    1.1 -  git status --> irá mostrar que houve alterãção no seu git.
2 - Unmodifild
    2.1 -  git add nomeDoArquivo.md --> irá adicionar o arquivo modificado na lista
    2.2 -  git add . --> adiciona TODOs os arquivos modificados na ista
3 - Modifild
    3.1 - git commit -m "descricaoDaAlteração" --> dá um nome para a alteração e salvas as alterações.
4 - Staged
    4.1 - 

COMANDOS BASICOS DO GIT
git log --> informa as alteraçoes realizadas (autor, data e nome das alteraçoes)
git log --decorate --> informa as alterações semelhante ao git log e as ramificações de branch
 git log --authot-- --> tras as informaç~eos de um altor especifico
 git shortlog -sn --> resumo das altertações com quantidade e autor
 git log --graph --> tras as ramificações em forma de grafico
 git show "hashdesejada" --> tras as alterações de um hash especifica

 DESFAZENDO MUDANÇAS
git checkout "momeDoArquivo" --> opção para desfazer a modificação
git reset --> opação de desfazer quando "commitar" em sua maquina voltando a versão anterior
git reset HEAD Readme.md --> desfazer e retirar do stage.
git reset --soft "hashdesejada" --> volta para estagio pos 
git reset --mixed "hashdesejada" --> volta para stage (estagio de alteração)
git reset --hard "hashdesejada" --> aponta apra hash anterior e apaga o historico no arquivo sem necessidade do checkout

<h1>Alterando o arquivo novamente</h1>
<h2>Alterando feita pelo dev 02</h2>



