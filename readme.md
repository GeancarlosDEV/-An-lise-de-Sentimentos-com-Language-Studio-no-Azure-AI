# Explorando o Estúdio de Fala no Azure

No exercício de hoje, decidi explorar o serviço Azure AI Speech, que oferece a capacidade de transcrever fala em texto e vice-versa. A ideia é utilizar esse serviço para criar um aplicativo que pode transcrever notas de reuniões ou gerar texto a partir de gravações de entrevistas.

## Configurando o Recurso Azure AI Speech

Primeiro, é necessário criar um recurso Azure AI Speech. Se você ainda não tem um, pode criá-lo acessando o [Azure AI Speech Studio](https://speech.cognitive.azure.com). Lá, você configurará um novo recurso com nome exclusivo, associado à sua assinatura do Azure e selecionando uma região suportada.

Após a criação do recurso, é hora de explorar o Azure AI Speech Studio. Você pode baixar um exemplo de áudio [aqui](https://aka.ms/mslearn-speech-files), e, na página inicial do Speech Studio, selecionar "Experimente a fala em tempo real para texto." Basta escolher o arquivo de áudio baixado, e o serviço Speech transcreverá o áudio em tempo real para texto.

Certifique-se de revisar a saída para garantir que a transcrição foi bem-sucedida. Se encontrar algum problema, aguarde alguns minutos antes de tentar novamente.

Com isso, concluímos este exercício. Agora, você tem um recurso AI Speech configurado no Speech Studio e foi capaz de transcrever uma gravação de áudio em texto.

## Limpando o Ambiente

Se não pretende realizar mais exercícios, é recomendável excluir os recursos que não precisa mais para evitar custos desnecessários. Acesse o [portal do Azure](https://portal.azure.com), selecione o grupo de recursos e exclua o recurso AI Speech.

Este foi apenas um vislumbre das capacidades do serviço Speech. Para aprender mais, consulte a página oficial do [Azure Speech](https://learn.microsoft.com/en-us/azure/cognitive-services/speech-service/).

---

# Analisando Texto com o Language Studio da Azure AI

## Explorando Recursos de Linguagem e PNL

No segundo exercício, mergulhamos no Azure AI Language Studio para analisar avaliações de hotéis. O Processamento de Linguagem Natural (PNL) é um campo poderoso da IA que lida com a linguagem escrita e falada.

## Configurando o Recurso de Idioma

Antes de começar, é necessário criar um recurso de idioma na assinatura do Azure. No [portal do Azure](https://portal.azure.com), busque por "Serviço de idioma" e crie um plano de serviço de idiomas. Certifique-se de configurar corretamente, escolhendo uma região, nível de preços e confirmando a leitura dos termos.

Com o recurso de idioma criado, acesse o [Language Studio](https://language.cognitive.azure.com) e configure-o selecionando o recurso de serviço de idioma criado anteriormente.

## Análise de Avaliações

Dentro do Language Studio, exploramos a guia "Classificar texto" para analisar sentimentos e extrair opiniões de avaliações de hotéis. Utilizamos exemplos de revisões, analisando a saída para determinar sentimentos positivos e negativos.

Lembre-se de limpar seus recursos se não planeja mais usá-los, evitando custos desnecessários. Acesse o [portal do Azure](https://portal.azure.com) e exclua o recurso de idioma.

Este exercício proporcionou uma visão sobre como utilizar o Language Studio para análise de texto e sentimentos. Para aprofundar seus conhecimentos, confira a [documentação oficial](https://learn.microsoft.com/en-us/azure/cognitive-services/language-service/).

