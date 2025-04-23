<h1 id="portugues" align="center">Uso do Azure Speech Studio e do Azure Language Studio</h1>

[English Version](#ingles)

Instruções sobre como explorar o uso do Azure Speech Studio e a análise linguística proporcionada pelo Language Studio.


### 🎯 Desafio de Projeto
Durante a prática, teremos a oportunidade de aprofundar nosso entendimento sobre como aproveitar essas ferramentas avançadas da Microsoft Azure. Estaremos focados em aprimorar nossas habilidades na implementação de soluções de análise de fala e linguagem, abrindo portas para uma compreensão mais ampla e prática das capacidades oferecidas por essas tecnologias inovadoras.

### ▶️ Intruções de Uso

**1. Introdução:**  
Este guia descreve como utilizar o `Azure Speech Studio` para tarefas relacionadas à fala e o `Azure Language Studio` para análise linguística, incluindo mineração de sentimentos e opiniões.

**2. Pré-requisitos:**  
Antes de começar, verifique se você possui:
- Uma conta ativa no Azure.
- Acesso aos recursos do Azure Speech Studio e Language Studio.
- Conhecimentos básicos de serviços do Azure.

**3. Passo a Passo:**  
- **Acessando o Azure Speech Studio**
1. Vá até o portal do Azure [portal.azure.com](https://portal.azure.com) e faça login.
2. Pesquise por `Speech Studio` e selecione o serviço nos resultados.
3. Explore recursos como `Conversão de Fala em Texto`, `Texto em Fala` e `Tradução de Fala`.  

- **Criando um Recurso de Fala**
1. No Speech Studio, clique em **"Criar um recurso"**.
2. Preencha os detalhes necessários, como assinatura, grupo de recursos e região.
3. Escolha o plano de preços apropriado.
4. Clique em **"Revisar + criar"** e depois em **"Criar"**.  

- **Acessando o Azure Language Studio**
1. No portal do Azure, pesquise por `Language Studio`.
2. Selecione o serviço `Language Studio`.
3. Explore funcionalidades como análise de sentimentos, extração de frases-chave e detecção de idioma.  


Mineração de Sentimentos e Opiniões no Language Studio  
- **Configurando a Análise**
1. Acesse o recurso **"Sentiment and opinion mining tryout"**.
2. Escolha o idioma do texto no menu suspenso (ex.: inglês ou português).
3. Conecte-se a um recurso Azure (plano gratuito F0 recomendado).
4. Insira o texto a ser analisado na caixa de texto. Você também pode usar arquivos ou textos de exemplo.  


- **Habilitando a Mineração de Opiniões**
1. Ative a opção **"Opinion mining"** para obter análises detalhadas sobre palavras ou atributos específicos.
2. Clique em **"Analyze"** para processar o texto.  


- **Interpretando os Resultados**
- Sentimentos são classificados como **negativo**, **neutro** ou **positivo**.
- As pontuações de confiança aparecem em níveis de sentença e documento.
- Caso a mineração de opinião esteja ativada, veja insights detalhados sobre palavras e atributos analisados.  

### Exemplo de Saída de Análise

Aqui está um exemplo de saída JSON gerada pela análise de sentimentos:

```json
{
    "documents": [
        {
            "id": "id__1177",
            "sentiment": "negative",
            "confidenceScores": {
                "positive": 0,
                "neutral": 0,
                "negative": 1
            },
            "sentences": [
                {
                    "sentiment": "negative",
                    "confidenceScores": {
                        "positive": 0,
                        "neutral": 0,
                        "negative": 1
                    },
                    "offset": 0,
                    "length": 220,
                    "text": "Tired hotel with poor service ...",
                    "targets": [
                        {
                            "sentiment": "negative",
                            "confidenceScores": {
                                "positive": 0.02,
                                "negative": 0.98
                            },
                            "offset": 7,
                            "length": 5,
                            "text": "hotel"
                        }
                    ]
                }
            ]
        }
    ],
    "errors": [],
    "modelVersion": "2025-01-01"
}
```
**4. Guia de Uso do Speech Studio:**
Este guia fornece instruções detalhadas sobre como acessar e utilizar o Speech Studio da Microsoft para conversão de fala em texto. Siga os passos abaixo para configurar e usar o serviço.

**1. Acessar a Página Inicial do Speech Studio**  
   Acesse a página inicial do Speech Studio e clique no ícone de configurações na lateral da barra de navegação.  

**2. Criar um Novo Recurso**  
   Se você não tiver nenhum recurso criado anteriormente, crie um novo clicando no botão **"+ Criar novo recurso"**.  

**3. Definir Configurações do Recurso**  
   - Defina um nome para o recurso.
   - Mantenha sua opção de assinatura.
   - Utilize a região "East US" para evitar instabilidades.
   - Mantenha "Padrão SO" em "Tipo de preço".
   - Selecione um grupo de recursos.
   - Clique em **"Criar um recurso"**.  

**4. Selecionar e Usar o Recurso**  
   Selecione o recurso criado e clique em **"Usar o recurso"**.  

**5. Conversão de Fala em Texto**  
   Navegue até a seção **"Conversão de fala em texto em tempo real"** e selecione essa opção.  

**6. Configurar Reconhecimento de Recursos**  
   Selecione o idioma do áudio e ative o reconhecimento de recursos.  

**7. Visualizar Arquivos de Áudio e Resultados de Teste**  
   - Na seção **"Arquivos de áudio"**, você encontrará os áudios já transcritos.
   - Na seção **"Resultados de teste"**, em "Texto", você verá a transcrição em tempo real.

**8. Visualizar Código JSON**  
   A transcrição gerada também pode ser visualizada na aba `JSON`.  
   

Com este guia, você aprendeu a utilizar o **Azure Speech Studio** para conversão de fala em texto e o **Azure Language Studio** para análises avançadas de texto, como mineração de sentimentos e opiniões. Essas ferramentas fornecem um poder computacional incrível para enriquecer suas aplicações com inteligência artificial e automação linguística. Para mais informações, consulte a [documentação oficial do Azure Speech Studio](https://learn.microsoft.com/en-us/azure/cognitive-services/speech-service/) e do [Azure Language Studio](https://learn.microsoft.com/en-us/azure/ai-services/language-service/).

### ✅ Conclusão
Este guia serve como repositório de estudos, desafios e projetos da [Bootcamp Decola Tech 2025](https://www.dio.me/bootcamp/decola-tech-2025). Explore os recursos compartilhados necessários para atender às suas necessidades da bootcamp.


</br></br></br></br></br></br></br></br></br></br></br>


<h1 id="ingles" align="center">Using Azure Speech Studio and Azure Language Studio</h1>

[Versão em Português](#portugues)

Instructions on how to explore the use of Azure Speech Studio and the linguistic analysis provided by Language Studio.

### 🎯 Project Challenge
During the hands-on practice, we will have the opportunity to deepen our understanding of how to leverage these advanced Microsoft Azure tools. We will focus on enhancing our skills in implementing speech and language analysis solutions, opening doors to a broader and more practical understanding of the capabilities offered by these innovative technologies.

### ▶️ Usage Instructions

**1. Introduction:**  
This guide describes how to use `Azure Speech Studio` for speech-related tasks and `Azure Language Studio` for linguistic analysis, including sentiment and opinion mining.

**2. Prerequisites:**  
Before getting started, make sure you have:
- An active Azure account.
- Access to Azure Speech Studio and Language Studio resources.
- Basic knowledge of Azure services.

**3. Step-by-Step Guide:**  

- **Accessing Azure Speech Studio**  
1. Go to the Azure portal [portal.azure.com](https://portal.azure.com) and log in.  
2. Search for `Speech Studio` and select the service from the results.  
3. Explore features such as `Speech to Text`, `Text to Speech`, and `Speech Translation`.  

- **Creating a Speech Resource**  
1. In Speech Studio, click on **"Create a resource"**.  
2. Fill in the required details such as subscription, resource group, and region.  
3. Choose the appropriate pricing plan.  
4. Click **"Review + create"** and then **"Create"**.  

- **Accessing Azure Language Studio**  
1. In the Azure portal, search for `Language Studio`.  
2. Select the `Language Studio` service.  
3. Explore features such as sentiment analysis, key phrase extraction, and language detection.  


Sentiment and Opinion Mining in Language Studio  
- **Setting Up the Analysis**  
1. Access the **"Sentiment and opinion mining tryout"** resource.  
2. Select the text language from the dropdown menu (e.g., English or Portuguese).  
3. Connect to an Azure resource (free plan F0 is recommended).  
4. Enter the text to be analyzed in the text box. You can also use files or example texts.  

- **Enabling Opinion Mining**  
1. Enable the **"Opinion mining"** option to get detailed analysis on specific words or attributes.  
2. Click **"Analyze"** to process the text.  

- **Interpreting the Results**  
- Sentiments are classified as **negative**, **neutral**, or **positive**.  
- Confidence scores appear at both sentence and document levels.  
- If opinion mining is enabled, you'll see detailed insights about analyzed words and attributes.  

### Sample Analysis Output

Here’s an example of a JSON output generated by sentiment analysis:

```json
{
    "documents": [
        {
            "id": "id__1177",
            "sentiment": "negative",
            "confidenceScores": {
                "positive": 0,
                "neutral": 0,
                "negative": 1
            },
            "sentences": [
                {
                    "sentiment": "negative",
                    "confidenceScores": {
                        "positive": 0,
                        "neutral": 0,
                        "negative": 1
                    },
                    "offset": 0,
                    "length": 220,
                    "text": "Tired hotel with poor service ...",
                    "targets": [
                        {
                            "sentiment": "negative",
                            "confidenceScores": {
                                "positive": 0.02,
                                "negative": 0.98
                            },
                            "offset": 7,
                            "length": 5,
                            "text": "hotel"
                        }
                    ]
                }
            ]
        }
    ],
    "errors": [],
    "modelVersion": "2025-01-01"
}
```

**4. Speech Studio Usage Guide:**  
This guide provides detailed instructions on how to access and use Microsoft’s Speech Studio for speech-to-text conversion. Follow the steps below to configure and use the service.

**1. Access the Speech Studio Home Page**  
   Go to the Speech Studio homepage and click the settings icon on the navigation bar.

**2. Create a New Resource**  
   If you haven't created a resource before, click the **"+ Create new resource"** button.

**3. Define Resource Settings**  
   - Set a name for the resource.  
   - Keep your subscription option.  
   - Use the "East US" region to avoid instability.  
   - Keep "Standard SO" under "Pricing tier".  
   - Select a resource group.  
   - Click **"Create a resource"**.  

**4. Select and Use the Resource**  
   Select the resource you created and click **"Use the resource"**.

**5. Speech-to-Text Conversion**  
   Navigate to the **"Real-time speech-to-text conversion"** section and select this option.

**6. Configure Resource Recognition**  
   Select the audio language and enable resource recognition.

**7. View Audio Files and Test Results**  
   - In the **"Audio files"** section, you will find already transcribed audio files.  
   - In the **"Test results"** section, under "Text", you'll see the real-time transcription.

**8. View JSON Code**  
   The generated transcription can also be viewed under the `JSON` tab.

With this guide, you have learned how to use **Azure Speech Studio** for speech-to-text conversion and **Azure Language Studio** for advanced text analysis, such as sentiment and opinion mining. These tools provide incredible computational power to enrich your applications with artificial intelligence and linguistic automation. For more information, visit the [official Azure Speech Studio documentation](https://learn.microsoft.com/en-us/azure/cognitive-services/speech-service/) and the [Azure Language Studio documentation](https://learn.microsoft.com/en-us/azure/ai-services/language-service/).

### ✅ Conclusion
This guide serves as a study repository, challenge resource, and project reference for the [Bootcamp Decola Tech 2025](https://www.dio.me/bootcamp/decola-tech-2025). Explore the shared resources needed to meet your bootcamp goals.