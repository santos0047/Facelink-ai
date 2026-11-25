# FaceLink AI v0.2

Protótipo web estático em HTML, CSS e JavaScript, sem bibliotecas externas; busca de cópias opcional por link externo.

## Funções
- Pré-visualização e dimensões de duas fotos locais (JPG, PNG e WEBP, até 20 MB cada).
- Comparação de arquivos byte a byte e índice experimental de similaridade da imagem inteira (dHash e diferença de pixels).
- Contagem de rostos quando a API experimental FaceDetector estiver disponível no navegador. Não há identificação facial.
- Autorização declarada, limpeza de imagens e exportação de relatório JSON sem imagens.

- Busca reversa assistida: abertura do TinEye após autorização, com seleção manual da fotografia no provedor.
- Informações locais da foto de referência; a segunda foto é opcional para a busca externa.

## Publicação
Em Settings > Pages, selecione Deploy from a branch, main e / (root).

## Limitações
Sem backend, API automática de busca, autenticação ou integração com redes sociais. Os resultados da busca reversa aparecem no TinEye; nenhum arquivo é enviado automaticamente pelo FaceLink. O índice não é uma probabilidade e não deve ser usado para identificar pessoas. A detecção facial depende do navegador. O processamento local não comprova consentimento; o usuário deve ter autorização real.
