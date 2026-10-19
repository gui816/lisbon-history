# Fontes históricas, cartografia e limitações

Este documento separa as fontes documentais das geometrias ilustrativas desenhadas para a experiência.

## Cartografia histórica georreferenciada

### 1650 — Planta de João Nunes Tinoco

- Catálogo de dados da Câmara Municipal de Lisboa: https://dados.cm-lisboa.pt/ar/dataset/cartografia-historica-de-lisboa
- Serviço de mosaicos raster (ArcGIS): https://tiles.arcgis.com/tiles/1dSrzEWVQn5kHHyK/arcgis/rest/services/web_tiles_t1/MapServer
- Registo do Arquivo Municipal de Lisboa: https://arquivomunicipal3.cm-lisboa.pt/x-arqweb/Result.aspx?id=1288470&type=PCD

O serviço raster publicado pela CML permite visualizar a planta de 1650 alinhada com o mapa atual. A planta corresponde a uma representação histórica da cidade e não deve ser interpretada como um cadastro moderno.

### 1756 — Planta de Carlos Mardel / Eugénio dos Santos

- Catálogo de dados da Câmara Municipal de Lisboa: https://dados.cm-lisboa.pt/ar/dataset/cartografia-historica-de-lisboa
- Serviço de mosaicos raster (ArcGIS): https://tiles.arcgis.com/tiles/1dSrzEWVQn5kHHyK/arcgis/rest/services/CartografiaHistoricaCarlosMardel1756/MapServer
- Digitalização histórica alternativa no Wikimedia Commons: https://commons.wikimedia.org/wiki/File:Pombaline_Baixa_Lisbon_map_1756.jpg

Esta camada mostra a cidade arruinada e os novos alinhamentos de reconstrução após o terramoto. O serviço da CML usa mosaicos espaciais publicados no sistema Web Mercator. A aplicação permite controlar a visibilidade e a opacidade da camada.

### Cartografia complementar

- Conjunto Cartografia Histórica de Lisboa (1650–1911): https://dados.cm-lisboa.pt/ar/dataset/cartografia-historica-de-lisboa
- Planta do centro histórico anterior ao terramoto, Arquivo Municipal: https://arquivomunicipal3.cm-lisboa.pt/x-arqweb/Result.aspx?id=1547345&type=PCD
- Modelo de Lisboa antes do terramoto, Museu de Lisboa: https://museudelisboa.pt/pt/collection/assets/4837-lisboa-antes-terramoto-1755/
- História de Lisboa, Câmara Municipal: https://geo.lisboa.pt/fileadmin/geo/difusao/Publicacoes/historiadelisboatemposfortes.pdf
- Investigação municipal sobre o terramoto de 1755: https://geo.lisboa.pt/atividades-e-difusao/investigacao/detalhe/o-terramoto-de-1-de-novembro-de-1755

## Fotografias

- As seis imagens iniciais têm referências explícitas para páginas de ficheiro do Wikimedia Commons.
- Os restantes locais usam pesquisa contextual na API do Wikimedia Commons, executada quando o local é selecionado.
- Os créditos e links para as páginas dos ficheiros são mostrados quando a API devolve resultados.
- A pesquisa automática não equivale a uma revisão editorial de cada imagem. Se não for encontrada uma imagem adequada, a aplicação mostra um marcador de ausência em vez de reutilizar uma fotografia genérica.

## Limitações que a interface deve preservar

1. **Plantas de 1650 e 1756:** são camadas raster históricas georreferenciadas disponibilizadas pela CML. A qualidade e o detalhe dependem da cartografia original e da publicação do serviço.
2. **Extensão urbana, muralhas e frente ribeirinha:** linhas e polígonos desenhados manualmente para contextualização; são aproximações interpretativas, não vetores oficiais extraídos das plantas.
3. **Reconstrução 3D pombalina:** volumes ilustrativos para comunicar a malha da Baixa. Não são edifícios individualmente levantados nem um modelo BIM/arqueológico.
4. **Pontos históricos:** as coordenadas representam a localização atual aproximada do lugar. A localização histórica pode ter mudado, e a existência do lugar numa época é controlada por datas indicativas.
5. **Textos e datas:** conteúdo introdutório, não substitui a consulta das fontes primárias. Quando há dúvida, a interface deve comunicar a incerteza em vez de afirmar precisão não comprovada.
6. **Serviços externos:** o mapa base, os mosaicos históricos e as fotografias precisam de Internet e podem ter disponibilidade ou políticas alteradas pelos respetivos fornecedores.

## Atribuição

Cartografia Histórica de Lisboa — Câmara Municipal de Lisboa / Lisboa Aberta. Serviços de mosaicos ArcGIS Online identificados junto das respetivas camadas. Fotografias e créditos individuais do Wikimedia Commons, quando disponíveis. As restantes fontes são ligadas diretamente nas fichas ou nesta lista.
