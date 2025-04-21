# Resumo dos Laboratórios: Fundamentos de IA da Microsoft

## 🔤 Laboratório 6: Análise de Texto com o Azure AI Language

### 📌 Objetivo

Explorar as capacidades de **análise de texto** usando os serviços de **Azure AI Language**. O laboratório foca em como extrair informações úteis de textos não estruturados.

### 🧪 Atividades Realizadas

1. **Configuração do Recurso Azure Language**

   - Criar um recurso _Language_ no portal Azure.
   - Obter a chave e o endpoint para uso via API ou SDK.

2. **Análise de Sentimento**

   - Envio de textos via API.
   - Retorno com pontuação de sentimento: positiva, negativa ou neutra.
   - Aplicações: monitoramento de opinião pública, feedbacks de clientes etc.

3. **Extração de Frases-Chave**

   - Identificação de termos e conceitos importantes em um texto.
   - Aplicações: resumo automático, classificação temática.

4. **Reconhecimento de Entidades Nomeadas (NER)**

   - Identificação de nomes próprios, locais, datas, organizações e outros.
   - Útil para categorização e enriquecimento semântico.

5. **Detecção de Idioma**
   - Reconhece o idioma do texto automaticamente.

### 🧠 Conceitos-Chave

- **IA Cognitiva**: Permite que aplicações interpretem texto de forma "inteligente".
- **Text Analytics API**: Serviço RESTful que realiza as análises.
- **Tokenização** e **Análise Estatística**: Técnicas usadas por trás das APIs.

---

## 🗣️ Laboratório 9: Reconhecimento e Síntese de Fala com Azure AI Speech

### 📌 Objetivo

Utilizar os serviços do Azure para **converter fala em texto (STT)**, **texto em fala (TTS)** e **reconhecer comandos por voz** com o Azure AI Speech.

### 🧪 Atividades Realizadas

1. **Criação do Recurso Speech**

   - Criar no portal Azure o serviço de _Speech_.
   - Obter chave de API e endpoint.

2. **Conversão de Fala em Texto (Speech-to-Text)**

   - Gravar ou enviar arquivos de áudio para transcrição.
   - Resultados incluem texto reconhecido e grau de confiança.

3. **Conversão de Texto em Fala (Text-to-Speech)**

   - Geração de fala sintética com vozes humanas (neural TTS).
   - Suporte para múltiplos idiomas e ajustes de prosódia.

4. **Reconhecimento de Comandos por Voz**

   - Criação de comandos personalizados para interação com dispositivos.
   - Exemplo: comandos como “ligar luz” ou “tocar música”.

5. **Uso do Speech Studio**
   - Ferramenta online para testar e treinar modelos de fala sem escrever código.

### 🧠 Conceitos-Chave

- **Reconhecimento de Fala**: Conversão de áudio em texto via modelos de machine learning.
- **Síntese Neural**: Modelos avançados que simulam fala humana realista.
- **Conversational AI**: Base para chatbots com entrada por voz.

---

## 🚀 Conclusão

Esses dois laboratórios demonstram o poder dos serviços cognitivos do Azure aplicados a **texto e fala**, com APIs acessíveis e integração rápida em aplicações reais. Eles fornecem os blocos de construção para:

- Aplicações de atendimento inteligente.
- Análise de sentimento em redes sociais.
- Assistentes virtuais com voz natural.

---

> **Fontes:**
>
> - [Laboratório 6 - Análise de Texto](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/06-text-analysis.html)
> - [Laboratório 9 - Serviços de Fala](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/09-speech.html)
