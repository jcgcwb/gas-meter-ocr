Banco de Imagens
===============

>**Nota:**
Este repositório contém imagens de medidores de consumo de gás natural. Estas imagens foram utilizadas na dissertação de mestrado de Julio Cesar Gonçalves, cujo título é **Reconhecimento de dígitos em imagens de medidores de consumo de gás natural utilizando técnicas de visão computacional**.

>Dissertação produzida como requisito parcial à obtenção do título de Mestre em Computação, do Programa de Pós-Graduação em Computação Aplicada, da Universidade Tecnológica Federal do Paraná Computação.

>Dissertação publicada no repositório institucional da Universidade Tecnológica Federal do Paraná (UTFPR).
>Acesso em: https://repositorio.utfpr.edu.br/jspui/handle/1/2210

>Artikgo originado da dissertação e publicado na revista Abakós, periódico científico da Universidade Católica de Minas Gerais (PUC Minas).
>Acesso em: https://doi.org/10.5752/P.2316-9451.2017v5n2p59

#### <i class="icon-file"></i> Resumo do Trabalho
Este trabalho propõe uma abordagem que emprega técnicas de processamento de imagens e classificação de padrões para o reconhecimento de dígitos apresentados no contador de consumo de medidores de gás natural. Tais imagens são obtidas em campo a partir de condições reais de operação, diferentemente da maioria das abordagens encontradas na literatura que se baseiam em imagens adquiridas em ambientes controlados. Inicialmente o contador de consumo é segmentado por técnicas de processamento de imagens. A segmentação é realizada com base no espaço de cor HSL da imagem, diferentemente da maioria dos trabalhos apresentados na literatura que utilizam imagens em tons de cinza. Em seguida os dígitos são individualmente segmentados e suas características extraídas de forma a compor uma base de conhecimento. Esta base serve de apoio para realizar a classificação e reconhecimento dos dígitos. Por fim, é feita uma comparação entre o desempenho dos classificadores KNN, SVM e ELM no reconhecimento de dígitos segmentados. Os resultados demonstram que as redes neurais ELM possuem um desempenho superior aos outros classificadores testados. Além disso, a metodologia mostrou-se promissora neste cenário, chegando a alcançar 95% de taxa de acerto no reconhecimento dos dígitos. Apresentando menos de 5% de falha no processo de segmentação do contador de consumo, considerando-se uma base com 903 imagens de medidores de gás. Diante da escassez de bases de imagens compatíveis com a finalidade desta pesquisa, tem-se como outro objetivo deste trabalho a disponibilização de uma base de dados contendo imagens de medidores de consumo de gás natural. Esta base é composta por imagens de medidores com tamanhos variados, obtidas em campo a partir de condições reais de operação. Fazem parte também desta base, imagens resultantes do processo de segmentação individual dos dígitos, com o objetivo de atender pesquisadores que pretendam apenas aplicar novos métodos de classificação.

#### <i class="icon-file"></i> Exemplo de Imagens Presentes neste Banco de Imagens
![alt tag](https://raw.githubusercontent.com/jcgcwb/gas-meter-ocr/master/exemplo1.jpg)

![alt tag](https://raw.githubusercontent.com/jcgcwb/gas-meter-ocr/master/exemplo2.jpg)

![alt tag](https://raw.githubusercontent.com/jcgcwb/gas-meter-ocr/master/exemplo3.jpg)


(*) Imagens do data_set G2 foram retiradas da base de imagens disponibilizada pelo laboratório de pesquisas Arte-Lab (http://artelab.dicom.uninsubria.it/downloads.html)
