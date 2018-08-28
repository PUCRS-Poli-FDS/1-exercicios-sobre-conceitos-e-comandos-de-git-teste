# Exercícios sobre os conceitos e comandos do Git


Hoje vamos fazer um estudo dirigido, praticando algumas operações do Git e respondendo algumas questões. O trabalho será realizado em duplas, trabalhando em conjunto.
Assim:

* os primeiros 14 passos devem ser feitos em conjunto (em uma única máquina). Da 14 em diante, cada um fará os passos na sua máquina (até o momento de trabalharem juntos novamente)
* para as operações, crie uma pasta na sua máquina local, e exercite no repositório. Ao final, o repositório será compartilhdo no Github;
* para as questões teóricas, crie um arquivo texto com o nome "respostas.txt" e coloque-o na raiz da pasta do repositório.
* além das respostas as perguntas, liste os comandos utilizados em cada atividade no arquivo de respostas (identifique a resposta com o número da atividade)

## Passos
1. Pergunta: qual a diferença entre sistemas de controle de versão centralizados e sistemas de controle de versão distribuídos?
1. Pergunta: explique claramente o que são as três áreas do repositório local do git.
1. Pergunta: como o git identifica cada commit, uma vez que os repositórios são distribuídos?
1. Atividade: crie uma pasta local, inicialize o repositório, crie o arquivo "respostas.txt" na pasta.
1. Atividade: configure seu nome e email, para quando os commits forem executados.
1. Atividade: crie duas pastas: "java" e "testes". Crie, na pasta Java, um arquivo "Hello.java" que imprime na tela a frase "Hello, World!" (não é preciso fazer nada no arquivo "respostas.txt").
1. Atividade: adicione esta estrutura à área de *staging*
1. Atividade: coloque as modificações da área de *staging* no repositório (faça *commit*)
1. Pergunta: descreva o que fazem os comandos *git reset HEAD --filename* e *git checkout --filename*
1. Atividade: execute os comandos *git status* e *git status -s*, e explique (no arquivo de respostas) a saída exibida
1. Atividade: execute o comando *git log* e explique (no arquivo de respostas) a saída exibida
1. Atividade: crie duas novas branches, uma para cada membro do grupo. Chame-as de "dev-NOME_DO_MEMBRO_DA_EQUIPE"
1. Atividade: compartilhe o repositório (todas as branches) no repositório remoto do seu grupo. DICA: deve haver um conflito entre o repositório local e o remoto, após todas estas alterações. Resolva o conflito trazendo o repositório remoto e mesclando-o com o local (lembre-se de continuar colocando a sequência de comandos no arquivo "respostas.txt")
1. Atividade: baixem o repositório (clonem) em uma segunda máquina. A partir de agora cada um trabalhará em sua máquina.
1. Atividade: cada um em sua máquina selecione a sua branch (e atualize o arquivo de respostas :wink: )
1. Atividade: cada um em sua máquina, acrescente uma linha no programa que imprima o seu nome. Teste, faça add/commit e atualize o repositório remoto
1. Atividade: em uma das máquinas, façam o *merge* das duas branches dos alunos na branch principal. 
1. Atividade: atualize o repositório remoto
1. Pergunta: o que é a tag HEAD?
1. Pergunta: quais são os quatro tipos de objeto no Modelo de Objetos do git? Explique brevemente cada um deles.
