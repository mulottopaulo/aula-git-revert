# Rollback com git revert
Revert é um comando do Git que desfaz as alterações de um commit. 

Para isso, ele cria **um novo commit** onde suas alterações desfazem as alterações do commit escolhido.

## Sintaxe
git revert <hash_do_commit>

## Exercício
Foram feitos alguns commits referente a criação de uma página para uma escola.

Você pode consultar os commits
[clicando aqui](https://github.com/mulottopaulo/aula-git-revert/commits/main).

O commit ["Ajuste errado serviço"](https://github.com/mulottopaulo/aula-git-revert/commit/69fbffe966c5b6e794531fd58de2c9e98987228d) foi realizado de forma incorreta e precisa ser desfeito. Mas atenção, os commits realizados após ele devem ser mantidos.

Utilize o comando <code>git revert</code> para desfazer essa alteração.

## Análise do resultado
Confira agora o histórico de commits. O que aconteceu?

O revert teve o resultado esperado?