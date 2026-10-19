# Lisboa no Tempo

Uma experiência interativa para explorar Lisboa em diferentes épocas, combinando pontos históricos, cronologia, cartografia histórica georreferenciada e percursos guiados.

## Funcionalidades

- Mapa interativo 3D com 58 locais históricos, filtros por época e pesquisa por nome/contexto.
- Linha temporal de 100 a.C. a 2026; selecionar um ano atualiza os locais e as camadas temporais.
- Cartografia histórica da Câmara Municipal de Lisboa: planta de Tinoco (1650) e planta de Carlos Mardel (1756), com controlo de visibilidade e opacidade.
- Camadas esquemáticas de muralhas, frente ribeirinha e extensão urbana; reconstrução 3D ilustrativa e limitada à área de estudo da Baixa Pombalina.
- Percursos guiados: Lisboa medieval, terramoto de 1755 e reconstrução pombalina.
- Pesquisa de locais, fotografias específicas via Wikimedia Commons e créditos/fontes quando disponíveis.
- Interface em português, inglês, espanhol e francês.

## Precisão histórica e fontes

As plantas de 1650 e 1756 são camadas raster publicadas pela Câmara Municipal de Lisboa no conjunto **Cartografia Histórica de Lisboa**, com referenciação espacial Web Mercator (EPSG:3857). A visualização acompanha o mapa atual através dos mosaicos cartográficos publicados pela CML.

As camadas desenhadas no próprio projeto — extensão urbana, algumas muralhas, frente ribeirinha, área de destruição e volumes 3D — são esquemáticas/interpretativas, não levantamentos arqueológicos nem modelos arquitetónicos rigorosamente georreferenciados. Os marcadores indicam a localização atual aproximada de um lugar; não representam necessariamente a sua posição ou forma em todas as épocas. As cronologias e descrições são introdutórias e devem ser verificadas nas fontes ligadas em cada ficha.

Ver [HISTORICAL_SOURCES.md](./HISTORICAL_SOURCES.md) para o catálogo de fontes, cartografia e limitações.

## Publicar no GitHub Pages

A publicação é automatizada por GitHub Actions em cada push para `main`.

1. Em **Settings → Pages**, selecionar **GitHub Actions** como source, se necessário.
2. Verificar a execução em [Actions](https://github.com/gui816/lisbon-history/actions).
3. Abrir https://gui816.github.io/lisbon-history/

## Tecnologias e dados externos

- MapLibre GL JS
- Carto basemap (Dark Matter)
- HTML, CSS e JavaScript
- Mosaicos raster ArcGIS Online da Câmara Municipal de Lisboa
- API da Wikimedia Commons para descoberta de imagens

A aplicação é estática e não necessita de backend. Para carregar o mapa base, as plantas históricas e as fotografias, necessita de ligação à Internet. A utilização de serviços cartográficos externos está sujeita às condições dos respetivos fornecedores.
