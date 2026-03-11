# Transcritor de Áudios Longos

Este projeto utiliza o modelo **Whisper da OpenAI** rodando no Google Colab para transcrever e traduzir áudios extensos sem custo.

##  Como Usar
1. Clique no botão abaixo para abrir o script:
[![Open In Colab] (https://github.com/marisout0/transcritor-de-udio/blob/main/transcritor_whisper.ipynb)

2. No menu do Colab, vá em **Ambiente de execução** > **Alterar tipo de ambiente de execução** e selecione **T4 GPU**.
3. Rode a primeira célula para instalar as ferramentas.
4. Faça upload do seu áudio na pasta lateral esquerda.
5. Ajuste o nome do arquivo na última célula e execute.

## Diferenciais
- **Tradução Automática:** Traduz de Português para Inglês diretamente.
- **Sem Limite de Tempo:** Ideal para podcasts, reuniões e aulas de várias horas.
- **Vários Formatos:** Gera `.srt` (legenda), `.txt` e `.vtt`.
