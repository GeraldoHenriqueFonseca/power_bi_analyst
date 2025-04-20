# Guia de Prática: Azure Speech Studio e Language Studio

Este guia foi criado para auxiliar profissionais e entusiastas a praticarem e se aprofundarem nas ferramentas **Azure Speech Studio** e **Language Studio**, com foco na análise de **fala** e **linguagem natural (NLU)**.

---

##  Objetivo

Desenvolver competências práticas no uso das ferramentas Speech Studio e Language Studio da Microsoft Azure, voltadas para:

- Transcrição e análise de fala em tempo real ou arquivos de áudio
- Compreensão de linguagem natural e extração de insights de texto
- Criação de modelos customizados para reconhecimento de intenções e entidades

---

##  Pré-requisitos

- Conta Microsoft com acesso ao Azure
- Subscrição ativa do Azure (com créditos suficientes para testes)
- Conhecimentos básicos de linguagem natural e machine learning

---

## 1. Azure Speech Studio

###  O que é?

O Speech Studio é uma plataforma baseada em nuvem para criar, testar e gerenciar soluções de conversão fala-texto, texto-fala e análise de fala.

###  Como começar

1. Acesse: [https://speech.microsoft.com/](https://speech.microsoft.com/)
2. Faça login com sua conta Azure
3. Navegue até "Speech to Text" ou "Speech Translation" para iniciar um projeto

###  Atividades práticas

- **Transcrição de Áudio**: Faça upload de arquivos de áudio (.wav, .mp3) e observe como o modelo lida com sotaques, ruídos e interrupções.
- **Personalização de Modelos**: Crie um modelo customizado com seu vocabulário (ex: termos técnicos específicos do seu domínio).
- **Análise de Fala**: Utilize a funcionalidade “Conversation Transcription” para obter transcrições diarizadas e segmentadas por locutor.

###  Recursos

- Documentação: [Speech service docs](https://learn.microsoft.com/azure/cognitive-services/speech-service/)
- Exemplos com SDK: [GitHub Samples](https://github.com/Azure-Samples/cognitive-services-speech-sdk)

---

## 2. Azure Language Studio

###  O que é?

O Language Studio é uma interface visual para usar os serviços de IA de linguagem da Azure, incluindo análise de sentimentos, extração de entidade, tradução e modelos de linguagem customizados.

###  Como começar

1. Acesse: [https://language.azure.com/](https://language.azure.com/)
2. Escolha uma tarefa (por exemplo: Análise de Texto)
3. Importe ou digite seu conteúdo textual para testes

### Atividades práticas

- **Análise de Sentimento e Emoção**: Teste textos com polaridades variadas e analise como o modelo responde.
- **Extração de Entidades Nomeadas**: Identifique nomes de pessoas, locais, organizações, etc.
- **Classificação de Texto**: Crie modelos de classificação para categorizar conteúdos (ex: reclamações, elogios, dúvidas).
- **Treinamento de Intenções**: Modele intenções e entidades para uso em bots ou assistentes conversacionais.

###  Recursos

- Documentação: [Language service docs](https://learn.microsoft.com/azure/cognitive-services/language-service/)
- Exemplos: [Azure AI Studio Examples](https://learn.microsoft.com/en-us/azure/cognitive-services/language-service/samples)

---

##  Projetos sugeridos para prática

1. **Transcritor Inteligente de Reuniões**
   - Combine Speech Studio (fala-texto) + Language Studio (entendimento do conteúdo)
   - Objetivo: gerar ata com sumário automático

2. **Análise de Sentimentos em Reviews**
   - Coletar avaliações (por exemplo de app ou produto)
   - Usar Language Studio para classificar emoções e identificar temas recorrentes

3. **Assistente Virtual com Intenções Customizadas**
   - Criar intenções no Language Studio (ex: marcar reunião, cancelar compromisso)
   - Integrar com bot usando o Azure Bot Framework

---

##  Dicas de aprofundamento

- Estude os SDKs para integração via Python, C#, JavaScript
- Explore a **Personalização com Linguagem Neural** (Custom Neural Voice e Classificadores Preditivos)
- Acompanhe atualizações no [Azure AI Blog](https://techcommunity.microsoft.com/t5/azure-ai/ct-p/AzureAI)

---

##  Conclusão

Speech Studio e Language Studio são poderosas ferramentas da Azure para construir aplicações inteligentes de voz e texto. Com prática contínua e projetos próprios, é possível desenvolver soluções robustas e adaptadas a múltiplos contextos.
