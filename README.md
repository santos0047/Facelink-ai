# FaceLink AI v0.1

Protótipo web estático em HTML, CSS e JavaScript, sem bibliotecas ou serviços externos.

## Funções
- Pré-visualização e dimensões de duas fotos locais (JPG, PNG e WEBP, até 20 MB cada).
- Comparação de arquivos byte a byte e índice experimental de similaridade da imagem inteira (dHash e diferença de pixels).
- Contagem de rostos quando a API experimental FaceDetector estiver disponível no navegador. Não há identificação facial.
- Autorização declarada, limpeza de imagens e exportação de relatório JSON sem imagens.

## Publicação
Em Settings > Pages, selecione Deploy from a branch, main e / (root).

## Limitações
Sem backend, busca externa, autenticação ou integração com redes sociais. O índice não é uma probabilidade e não deve ser usado para identificar pessoas. A detecção facial depende do navegador. O processamento local não comprova consentimento; o usuário deve ter autorização real.
