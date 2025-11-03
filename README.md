# Explicação e Visão Geral

Este notebook fornece uma interface web (WebUI) para o *Whisper*, um modelo de reconhecimento automático de fala desenvolvido pela OpenAI. A WebUI facilita a transcrição de arquivos de áudio e vídeo através de uma aplicação web amigável. O notebook foi projetado para ser executado no Google Colab, utilizando Python.

Link do google colab: https://colab.research.google.com/drive/1j5nM8cF2RKJ5kIE14wgyHFTJnTqN4Zek?usp=sharing

## Tecnologias utilizadas

- **Python**: Linguagem de programação utilizada para executar os scripts.
- **Jupyter Notebook / Google Colab**: Ambiente interativo para notebooks.
- **Git**: Utilizado para clonar o repositório `Whisper-WebUI`.
- **Pip**: Gerenciador de pacotes para instalar dependências.
- **[Whisper](https://github.com/openai/whisper)**: Modelo de transcrição de áudio.
- **Faster-Whisper**: Implementação otimizada do Whisper.
- **Gradio** e **Gradio-i18n**: Framework para criar a interface web.
- **Pyannote.audio**: Biblioteca para separação de locutores.
- **Ultimate Vocal Remover**: Ferramenta opcional para remover vocais de arquivos de áudio.
- **Google Drive** (opcional): Usado para ler e gravar arquivos diretamente no Drive.

## Propósito do notebook

O objetivo deste notebook é instalar e configurar o Whisper e a interface WebUI com as configurações padrão, de forma simples e sem etapas avançadas.

## Como Usar

Clique no botão **“Executar Tudo”** no painel do Google Colab. O notebook executará automaticamente as etapas necessárias:

1. **Verificar GPU**: Verifica se a sua sessão do Colab possui uma GPU disponível. Se não houver GPU, os modelos podem funcionar mais lentamente.

2. **Instalação**: Clona o repositório `Whisper-WebUI` e instala todas as bibliotecas necessárias. Esta etapa é obrigatória e pode levar alguns minutos.

3. **Executar**: Inicia o servidor Gradio do Whisper-WebUI e fornece um link (URL pública) no console. Clique ou copie esse link para abrir a interface em outra aba do navegador.

4. **Utilizar a interface web**: Na página da WebUI, você pode carregar arquivos de áudio ou vídeo, selecionar as opções de transcrição e iniciar o processo. A saída será apresentada na interface para download.

## Saída com Link para WebUI (Interface de Transcrição)

Quando executa será gerado o link da interface WebUI que irá executar o whisper com o áudio.

Acesse um link similar a: https://esteehumcodigoaleatorio.gradio.live
