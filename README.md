# Projeto_Bootloader
Um bootloader feito utilizando a linguagem Assembly x86 para o projeto da cadeira Infraestrutura de Software (IF677-EC)
# Integrantes
Victória Xavier Queiroz

Nathália Rezende Coelho
# Professor
Eduardo Antônio Guimarães Tavares (eagt)
# Descrição do Projeto
O projeto consiste em modificar o código do boot1.asm, para que este carregue na memória o segundo estágio do bootloader (que deve ser outro arquivo criado para o projeto), e este por sua vez, deve carregar o kernel escrito por vocês em assembly. O kernel é um programa normal em assembly, que deverá imprimir na tela uma string com o nome do SO de vocês.

Existem várias formas de fazer isso, porém para facilitar a vida, vocês farão um bootloader de 2 estágio, que sabe exatamente onde está o kernel no disco (setor), e carregará esse kernel num endereço fixo da memória, pulando para lá em seguida.

Para usar o Makefile com o segundo estágio do bootloader e com o kernel, é necessário informar alguns detalhes, como aonde eles irão ser escritos no disco, o nome dos arquivos, etc.
