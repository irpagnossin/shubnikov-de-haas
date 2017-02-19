=SdH=

Este arquivo de script do Microcal Origin foi desenvolvido para auxiliar nas análises do efeito
Shubnikov-de Haas. Com seu auxílio, e NUNCA dispensando a análise do pesquisador, pode-se determinar,
a partir de um conjunto de pares ordenados ($B$,$V_{xx}$), a concentração de portadores em cada uma das
sub-bandas observáveis e suas respectivas mobilidades quânticas (o método é tão preciso quanto melhor
for o espectro obtido, que por sua vez depende não só da qualidade da amostra como também das capaci-
dades dos aparelhos envolvidos).

Para detalhes do método e de como utilizar apropriadamente esse script, consulte a página do autor.

==Dependências==
- FIT.OGS e FFT.OTW (ambos são acompanham o Origin)
- Este script foi testado na versão 6.0 do Microcal Origin. Sabe-se que não funciona na versão 5.0.

==Bugs==
Frequentemente ocorre de a rotina GAUSS determinar erroneamente o pico e sua posição para o caso da janela Hanning mais curta. Uma segunda (ou terceira) tentativa deve resolver. Ainda não sei a origem deste problema.
