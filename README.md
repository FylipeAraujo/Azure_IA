# 🧠 Desafio - Análise de Fala e Linguagem com Azure Speech Studio e Language Studio

## 📌 Descrição

Este projeto faz parte de um laboratório prático com o objetivo de aplicar e aprofundar conhecimentos em **inteligência artificial aplicada à voz e linguagem natural**, utilizando as ferramentas **Azure Speech Studio** e **Azure Language Studio**.

Durante o desafio, realizamos experimentos com funcionalidades como:
- Reconhecimento de fala (speech-to-text);
- Síntese de fala (text-to-speech);
- Análise de sentimento;
- Extração de entidades e palavras-chave;
- Classificação de texto;
- Tradução automática, entre outras.

---

## 🎯 Objetivos do Desafio

- Aplicar os conceitos de IA de fala e linguagem em um ambiente prático;
- Documentar os testes, processos e aprendizados de forma clara;
- Utilizar o GitHub como ferramenta de organização e compartilhamento de conhecimento técnico.

---

## 🛠️ Ferramentas Utilizadas

- [Microsoft Azure Speech Studio](https://speech.microsoft.com/)
- [Microsoft Azure Language Studio](https://language.azure.com/)
- [Visual Studio Code](https://code.visualstudio.com/)
- [GitHub](https://github.com/) para versionamento e publicação
- Markdown para documentação

---

## 🧪 Atividades Realizadas

### 1. Reconhecimento de Fala
> **Descrição**: Conversão de áudio para texto.  
> **Resultado**: Transcrição precisa com suporte a múltiplos idiomas.  
> **Insight**: A ferramenta oferece modelos customizados que aumentam a precisão em contextos específicos.

### 2. Análise de Texto
> **Descrição**: Análise de sentimentos e extração de entidades.  
> **Resultado**: Captação de sentimentos positivos, negativos ou neutros e identificação de termos importantes no texto.  
> **Insight**: Excelente para análise de feedbacks e classificações automáticas.

### 3. Tradução e Classificação
> **Descrição**: Tradução de frases e categorização de textos por tópicos.  
> **Resultado**: Traduções precisas e classificação coerente com o conteúdo.  
> **Insight**: Útil para atendimento ao cliente multilíngue e organização automática de conteúdos.

*(Adicione aqui outros testes que realizou)*

---

## 📂 Estrutura do Repositório

📁 /docs speech-studio_transcricao.pdf
Título: Teste de Transcrição de Áudio no Azure Speech Studio
Descrição: O áudio enviado continha a seguinte fala:
"Olá, este é um teste de reconhecimento de fala com o Azure Speech Studio. Estamos testando a precisão da transcrição automática."
Resultado da transcrição:
"Olá, este é um teste de reconhecimento de fala com o Azure Speech Studio. Estamos testando a precisão da transcrição automática."
Análise: A transcrição foi perfeita, sem erros. Ferramenta adequada para aplicações como legendas automáticas.

📁 /tests 
Áudio de entrada:
"Boa tarde! Hoje vamos aprender como transformar fala em texto usando inteligência artificial."

Transcrição gerada:
"Boa tarde! Hoje vamos aprender como transformar fala em texto usando inteligência artificial."

Avaliação:
✔️ Muito precisa, sem ruído ou perda de informação.

Texto 2 analisado:
"Estou muito decepcionado com o serviço. O produto chegou quebrado."

Resultado:
- Sentimento: Negativo
- Entidades: serviço, produto
- Score de negatividade: 94.5%


📁 /speech-samples 

exemplo_01_boa_tarde.wav
Conteúdo do áudio: "Boa tarde! Hoje vamos aprender como transformar fala em texto usando inteligência artificial."

(Arquivo de áudio simulado – pode ser gravado por você no celular e nomeado assim para prática.)

exemplo_02_feedback_cliente.wav
Conteúdo do áudio: "O produto chegou muito rápido. Estou satisfeito com o atendimento da loja."

📁 /language-samples
Comprei pela primeira vez e fiquei impressionado. O produto é excelente e chegou antes do prazo.
Infelizmente, minha experiência foi ruim. Demorou muito e o suporte não respondeu meus e-mails.


---

## 📖 Aprendizados e Reflexões

- A integração entre fala e linguagem no Azure é altamente acessível e poderosa.
- Personalizações de modelos melhoram a precisão em contextos técnicos ou regionais.
- A documentação da Microsoft auxilia bastante nos testes, mas exige conhecimento básico em inglês.

---

## 🚀 Próximos Passos

- Integrar essas soluções a uma aplicação real (ex: chatbot ou transcrição de reuniões).
- Realizar treinamentos de modelos personalizados com dados próprios.
- Explorar os recursos de automação via Azure Functions.

---

## 👨‍💻 Autor

**Fylipe Araújo**  
[LinkedIn](https://www.linkedin.com/in/fylipe0610) | [GitHub](https://github.com/FylipeAraujo)

---

## 📃 Licença

Este projeto está licenciado sob a [MIT License](LICENSE).


