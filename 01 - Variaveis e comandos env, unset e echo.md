## Variáveis de Ambiente

**PATH**: Lista de diretórios de programas executáveis

**USERNAME**: Nome do usuário logado

**TERM** Tipo de terminal ou janela de terminal em uso 

**HOME** Diretório home do usuário atual

**UID**: UID do usuário atual

**RANDOM**: Gera um número aleatório

**LANG**: Idioma, especificado como locale

env ou printenv listam as variáveis de ambiente no terminal

## Variável do Shell

Criando a variável `teste=valor` e use o `echo $teste` para ver o valor da variável. Para remover a variável usa-se o comando `unset teste`

Mostrar quanto tempo a sessão no termial esta aberta:`echo $SECONDS`

Exercicio:

01. Criar uma variável local e atribuir um valor;
02. Mostrar o conteúdo da variável criada;
03. Mostrar os dois processos;
04. Mostrar o conteúdo da variável criada;
05. Voltar para o processo 'pai';
06. Mostrar o processo único rodando agora;
07. Mostrar o conteúdo da variável criada;
08. Exporta a variável TESTE;
09. Cria um novo processo bash filho;
10. Mostra os dois processos;
11. Mostra o conteúdo da variável criada.

Resolução:
> teste='teste'
> echo $teste
> bash
> ps
> echo $teste
> exit
> ps
> echo $teste
> export teste
> bash
> ps
> echo $teste

