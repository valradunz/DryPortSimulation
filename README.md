# DryPortSimulation
SIMULAÇÃO PARA FLUXO DE CONTAINER DE CARGA UTILIZANDO C++

Letícia Luiza Cardoso
Valquiria Rafaela Radunz


1. DESCRIÇÃO

Este projeto foi realizado para a disciplina de Programação III da Universidade Federal de Santa Catarina no curso de engenharia de transporte e logística, para relacionar a disciplina ao curso o projeto realizado foi a simulação do fluxo de containers de carga em um pátio. O programa cadastra o container escolhe a melhor área do setor para empilhar e os retira em ordem de saída. Para maiores detalhes segue neste link um relatório completo do projeto: https://github.com/valradunz/DryPortSimulation/blob/main/Relat%C3%B3rio%20Projeto%20Final%20-%20Leticia%20Cardoso%20e%20Valquiria%20Radunz.pdf 

2. PRÉ-REQUISITOS

O editor de código utilizado foi a versão 1.51.1 do Visual Studio Code, o sistema operacional foi o Linux x64 5.4.0-42-generic. As bibliotecas utilizadas foram as bibliotecas padrões do C++: a biblioteca string, iostream, iomanip, string, stack.

3.INSTRUÇÕES

O código recebe make para compilar através do makefile e ./myapp para executar o código. 
E os demais comandos são internos ao código e o próprio programa mostra um menu de instruções. O programa não necessita da instalação de nenhuma ferramenta adicional.

4. LICENÇA

É autorizado sem qualquer necessidade de permissão dos desenvolvedores deste projeto, a edição, cópia, utilização ou redistribuição do programa, sob os termos da GNU General Public License v3.0 que está disponível em: https://github.com/valradunz/DryPortSimulation/blob/main/LICENSE. 

5. INFORMAÇÕES SOBRE O PROGRAMA

	O programa é autoral, utilizando os conceitos aprendidos na disciplina de Programação III. Cuja a linguagem aprendida e utilizada é C++. O projeto realizado é uma simulação de um pátio onde existe um fluxo de containers, estes container chegam no pátio e são organizados em pilhas por tamanhos que podem ser 20 e 40 pés. O usuário insere uma data de saída para cada container cadastrado no pátio. O código procura o melhor lugar na pilha para inserir o container respeitando a ordem Last in First Out (LIFO), onde o último container a entrar é o último a sair.

REFERÊNCIAS
[1] DEITEL, P.; DEITEL, H. C++: How To Program, 9a edição, Ed. Pearson, 2014. ISBN-10: 0133378713.

[2] SAVITCH, W. J.. C++ Absoluto. São Paulo: Addison Wesley. 2004. ISBN: 85-88639-09-2.
[3] O que é e como funciona um porto seco. Remessa Online, 2020. Disponível em: <https://www.remessaonline.com.br/blog/o-que-e-e-como-funciona-um-porto-seco/ >. Acesso em: 26 de nov. de 2020.

[4] ISO 6346:1995 Freight containers — Coding, identification and marking. ISO, 1995. Disponível em:<https://www.iso.org/obp/ui/#iso:std:iso:6346:ed-3:v1:en>. Acesso em: 30 de nov. de 2020.

[5] Container Identification Number. Bureau International des Containers et du Transport Intermodal (BIC). Disponível em:< https://www.bic-code.org/identification-number/ >. Acesso em: 30 de nov. de 2020.

