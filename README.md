Fiz um teste com a funcionalidade de transcrição em tempo real do Azure AI para áudio e achei bem interessante. 
A ferramenta consegue converter fala em texto de forma rápida e com boa precisão, mesmo em português.
Pode ser útil para transcrever reuniões, gerar legendas automáticas ou analisar chamadas de atendimento.
Foi só um teste simples para entender o funcionamento, mas já deu pra ver que tem bastante potencial em aplicações como acessibilidade, automação e análise de voz.



<img width="960" alt="Teste-azure" src="https://github.com/user-attachments/assets/e684e03b-7941-421f-b71b-f0530a7c306f" />

No teste com o Azure AI Foundry, utilizei as funções de extração de entidades nomeadas, frases-chave e resumo de texto.
A extração de entidades identificou automaticamente nomes de pessoas, organizações, locais e datas dentro do texto, o que pode ser útil para 
estruturar informações não organizadas. A função de frases-chave destacou os termos mais relevantes do conteúdo, facilitando a compreensão
rápida do assunto principal. Já a função de resumo condensou textos longos em poucos parágrafos mantendo o contexto essencial.
Foi um teste simples, mas mostrou como essas ferramentas podem otimizar a análise de grandes volumes de texto de forma automatizada.

![image](https://github.com/user-attachments/assets/dc981580-7074-486a-a058-74beb90e5e05)

Durante o teste, iniciei criando os recursos necessários no portal do Azure, como o serviço de busca e o armazenamento. Em seguida, configurei uma fonte de dados para extrair as informações que seriam processadas. Apliquei habilidades de IA para enriquecer os dados, utilizando funcionalidades como extração de texto, identificação de entidades e frases-chave. Após isso, usei o indexador do Azure para organizar esses dados em um índice de pesquisa. Com o índice criado, foi possível realizar consultas utilizando filtros e palavras-chave. Por fim, revisei os dados enriquecidos que ficaram salvos no Armazenamento de Conhecimento, prontos para serem utilizados em análises ou integrações futuras.
