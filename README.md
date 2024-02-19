# Trabalhando com Visão Computacional

## 🛠 1. Criar um Recurso dos Serviços de IA do Azure
- Acesse o **portal do Azure** e faça login.
- Clique em `+Criar um recurso` e procure por **serviços de IA do Azure**.
- Configure o recurso com as configurações especificadas:
  - Assinatura
  - Grupo de recursos
  - Região
  - Nome
  - Nível de preços

## 🔗 2. Conectar o Recurso de Serviço de IA do Azure ao Vision Studio
- Navegue até o [**Vision Studio**](https://portal.vision.cognitive.azure.com) e faça login.
- Verifique se está usando o mesmo diretório do recurso de IA.
- Na página inicial, selecione `Exibir todos os recursos` e escolha seu recurso como padrão.
- Feche a página de configurações.

    ## 👤 Detectar rostos
    - Selecione a guia `Face` e então o bloco `Detect faces in an image`.
    - Em `Try it out`, marque a caixa que reconhece a política de uso do recurso.
    - Envie uma imagem de exemplo.
    - Analise o resultado da detecção.


   ## 📖 Ler texto
   - Selecione a guia `Optical character recognition` e então o bloco `Extract text from images`
   - Em `Try it out`, marque a caixa que reconhece a política de uso do recurso.
   - Envie uma imagem de exemplo.
   - Analise o resultado da Extração.

   ## 🎥 Legendas
   - Selecione a guia `Image Analysis` e então o bloco `Add captions to images`
   - Em `Try it out`, marque a caixa que reconhece a política de uso do recurso.
   - Envie uma imagem de exemplo.
   - Analise o resultado da legenda.

### 🧹 Limpe os recursos utilizados para evitar custos desnecessários.
