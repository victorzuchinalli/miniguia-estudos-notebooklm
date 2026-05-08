# miniguia-estudos-notebooklm
Projeto DIO - utilizando IA com NotebookLM

## 📌 Contexto e Objetivo
O assunto escolhido por mim é "Engenharia de Prompts", escolhi esse tema, pois tem total ligação com o curso e com este desafio.
Minha meta é aprender a realizar melhores Prompts, entender como receber respostas melhores e entender de fato como as IA's funcionam.

## 📚 Curadoria de Fontes
https://repositorio.ufrn.br/bitstreams/83ed7a5d-4651-4e51-8862-6c617dbbb2bb/download
https://sol.sbc.org.br/index.php/latinoware/article/view/31562
https://blog.brasilacademico.com/2025/06/guia-completo-de-engenharia-de-prompt.html

## 🤖 Engenharia de Prompts
♦TESTE 1: ESPECIFICIDADE DA PERGUNTA

PROMPT: "Explique o que é Engenharia de Prompt"

RESPOSTA OBTIDA: "A Engenharia de Prompt é a prática de criar, estruturar e otimizar instruções textuais (os "prompts") para orientar modelos de inteligência artificial generativa, especialmente os de Processamento de Linguagem Natural (PLN), na geração de respostas precisas, relevantes e seguras. Essencialmente, ela funciona como uma forma de programação em linguagem natural, permitindo que humanos comuniquem sua intenção à máquina de maneira que ela execute tarefas específicas, como escrever códigos, criar textos criativos ou analisar dados complexos, sem a necessidade de reprogramar o modelo internamente"

PROMPT MELHORADO:"Explique engenharia de prompt para iniciantes, utilizando linguagem simples, exemplos práticos do cotidiano e demonstrando como pequenas alterações em um prompt podem modificar a qualidade das respostas geradas pela IA."

RESPOSTA OBTIDA:"A Engenharia de Prompt é a arte e a ciência de criar, estruturar e otimizar instruções textuais (chamadas de "prompts") para guiar modelos de inteligência artificial generativa, como o ChatGPT, na geração de respostas precisas, úteis e relevantes.
Basicamente, é como aprendemos a nos comunicar de forma estratégica com a máquina para que ela entenda exatamente o que queremos, funcionando como uma espécie de "programação em linguagem natural".
Como funciona na prática? (A Regra de Ouro)
Uma regra simples para iniciantes é: se você desse essa instrução para uma pessoa ao seu lado, ela conseguiria executá-la?. Se a instrução for vaga demais para um humano, a IA provavelmente também terá dificuldade ou entregará algo genérico.
Veja como pequenas alterações mudam drasticamente a qualidade da resposta:
Prompt Vago: "Conte algo interessante."
Resultado provável: Uma curiosidade aleatória que você talvez já conheça.
Prompt Melhorado (com contexto): "Conte uma curiosidade sobre o espaço em menos de 100 palavras.".
Resultado: Uma resposta focada, curta e dentro do tema desejado.O Poder da Persona
Uma das técnicas mais eficazes é atribuir um papel (persona) à IA. Isso muda o vocabulário, o tom e a profundidade da resposta.
Sem Persona: "Explique o que é fotossíntese."
Resultado: Um texto técnico, estilo enciclopédia.
Com Persona: "Você é um professor de ciências. Explique o que é fotossíntese para uma criança de 8 anos.".
Resultado: Uma explicação simples, usando metáforas e linguagem acessível.
Pequenas mudanças, Grandes Diferenças,Pequenos ajustes na estrutura podem evitar o que chamamos de "alucinação" (quando a IA inventa fatos) e garantir que a tarefa seja completada: Seja Específico com Formatos: Em vez de pedir "uma descrição de produto", peça "um parágrafo de 3 a 5 frases destacando a durabilidade. Dê Exemplos (Few-shot): Se você quer que a IA classifique e-mails, dê a ela 2 ou 3 exemplos antes de pedir a tarefa final. Isso ajuda o modelo a entender o padrão esperado.Destaque o que fazer (não o que não fazer): É mais eficaz dizer à IA "fale de forma profissional e direta" do que apenas listar coisas que ela não deve dizer.Posicionamento das Instruções: Colocar as instruções mais importantes no início do prompt ajuda a IA a focar no que é prioridade antes de processar o restante do texto."

CONCLUSÃO DO TESTE 1: Esse teste demonstrou que prompts específicos reduzem ambiguidades e direcionam melhor o comportamento da IA. A primeira resposta estava bem mais simples, sem exemplos e dicas para facilitar o entendimento e após o ajuste aumentando a especificidade da pergunta, a resposta obtida foi muito melhor, pois ele explicou mais sobre o assunto e de maneira mais didática. 






♦TESTE 2: DEFINIÇÃO DA ESTRUTURA E FORMATO

PROMPT:"Fale sobre IA"

RESPOSTA OBTIDA:"A Inteligência Artificial (IA) é uma área da ciência da computação dedicada ao desenvolvimento de máquinas capazes de "pensar" e resolver problemas de maneira similar aos seres humanos. Diferente da programação tradicional, onde cada passo é definido manualmente, a IA permite que o computador aprenda com grandes volumes de dados e tome decisões de forma autônoma"

PROMPT MELHORADO:"Explique inteligência artificial utilizando tópicos organizados, separando: 1-definição,2-aplicações práticas,3-vantagens,4-desafios,5-exemplos atuais. Utilize linguagem objetiva e fácil de compreender."

RESPOSTA OBTIDA:"A Inteligência Artificial (IA) é um campo da ciência da computação que busca desenvolver máquinas capazes de "pensar" e "resolver problemas" de forma semelhante aos seres humanos.
Abaixo, os tópicos detalham essa tecnologia conforme os documentos:
1. Definição
A IA permite que computadores aprendam com grandes volumes de dados para tomar decisões autônomas, em vez de seguirem apenas sequências de instruções programadas manualmente. Ela se divide principalmente em:
Machine Learning (Aprendizado de Máquina): Ensinar a máquina a descobrir padrões sozinha através de exemplos.
Deep Learning (Aprendizado Profundo): Uso de redes neurais complexas, inspiradas no cérebro humano, para lidar com dados brutos como imagens e áudios.
LLMs (Grandes Modelos de Linguagem): Sistemas como o ChatGPT, treinados em bilhões de textos para entender e gerar linguagem humana natural.
2. Aplicações Práticas
A tecnologia já está integrada em diversas áreas do cotidiano e do trabalho:
Atendimento ao Cliente: Uso de chatbots inteligentes para responder dúvidas de forma personalizada.
Entretenimento: Recomendações de filmes na Netflix ou organização automática de fotos.
Saúde: Diagnóstico médico através da análise de exames como raios-X e tomografias.
Desenvolvimento de Software: Automação de tarefas repetitivas, geração de códigos e segurança.
Direito e Auditoria: Análise estruturada de documentos jurídicos, sumários de leis e apoio à redação técnica.
3. Vantagens
Aumento de Produtividade: Funciona como um "braço direito" que agiliza processos e escalas de produção.
Redução de Erros: Automatizar tarefas manuais e repetitivas economiza tempo e minimiza falhas humanas.
Escalabilidade: Capacidade de gerar múltiplos conteúdos (e-mails, posts, relatórios) mantendo a qualidade técnica.
Personalização: Adaptação do aprendizado e da comunicação ao perfil e necessidade do usuário.
4. Desafios
Alucinação: O risco de a IA gerar informações falsas ou inventadas com aparência de verdade.
Ética e Privacidade: Questões sobre direitos autorais, plágio no treinamento dos modelos e proteção de dados sensíveis.
Segurança: Vulnerabilidade a ataques de "prompt injection", onde comandos maliciosos tentam corromper a instrução original do sistema.
Vieses: Os modelos podem reproduzir preconceitos ou estereótipos presentes nos dados em que foram treinados.
5. Exemplos Atuais
Plataformas de Conversação: ChatGPT (OpenAI), Gemini (Google), Claude (Anthropic) e Perplexity.
Geração de Imagens: Midjourney.
Ferramentas Especializadas: ANIA, assistente desenvolvida pelo TCE-SP para análise documental, e o modelo Whisper para reconhecimento de voz.
Frameworks: LangChain, utilizado para criar aplicações personalizadas conectando modelos de IA a bases de dados privadas"

CONCLUSÃO DO TESTE 2: Definir explicitamente o formato esperado melhora significativamente a qualidade estrutural das respostas, melhora a clareza nas respostas e deixa a leitura mais fluida.






♦TESTE 3: CONTEXTUALIZAÇÃO DO OBJETIVO

PROMPT: "Crie um resumo sobre engenharia de prompt."

RESPOSTA OBTIDA: "A engenharia de prompt é a prática estratégica de planejar, criar e testar instruções textuais para orientar modelos de inteligência artificial generativa na produção de respostas precisas e relevantes. Ela funciona como uma interface ajustável que permite moldar o comportamento do sistema por meio da formulação de comandos, sem a necessidade de alterar o código interno ou os pesos do modelo. Para que um prompt seja considerado eficaz, ele deve ser construído sobre pilares fundamentais que incluem a definição de um papel ou persona para a IA, a descrição clara da tarefa, o fornecimento de contexto relevante e a especificação detalhada do formato de saída desejado. Frameworks estruturados como o RTF, que foca em papel, tarefa e formato, ou o ROGER, que engloba diretrizes e ambiente, ajudam usuários a organizar essas ordens de maneira lógica. Entre as técnicas mais utilizadas no dia a dia estão o zero-shot prompting, onde o modelo executa tarefas baseando-se apenas em seu treinamento prévio, e o few-shot prompting, que utiliza alguns exemplos para guiar o estilo da resposta. Abordagens mais sofisticadas, como a cadeia de pensamento ou chain-of-thought, instruem o modelo a decompor problemas lógicos em etapas menores e sequenciais, o que aumenta significativamente a precisão em tarefas complexas. O uso de delimitadores visuais como tags XML e o emprego de variáveis ajudam a organizar prompts longos e evitam que a IA ignore instruções importantes localizadas no meio do texto. Além disso, a integração com bases de conhecimento externas por meio da técnica de geração aumentada por recuperação, conhecida como RAG, permite que o modelo acesse dados privados ou atualizados, reduzindo drasticamente a ocorrência de informações inventadas ou alucinações. No cenário tecnológico de 2026, a disciplina amadureceu do simples ajuste de palavras para o design de sistemas e a engenharia de contexto, focando agora no desenvolvimento de agentes autônomos capazes de tomar decisões e interagir com ferramentas externas para atingir objetivos de alto nível. Dominar essas competências é atualmente considerado uma forma essencial de literacia digital que amplia a produtividade e redefine a colaboração entre humanos e tecnologia"

PROMPT MELHORADO: "Crie um resumo acadêmico sobre engenharia de prompt voltado para estudantes iniciantes em inteligência artificial, destacando definição, importância, aplicações práticas e impacto na qualidade das respostas geradas por IA."

RESPOSTA OBTIDA: "A Engenharia de Prompt é definida como o design estratégico de instruções textuais (prompts) para maximizar a eficácia e orientar o comportamento de modelos de Inteligência Artificial (IA) generativa, como os Grandes Modelos de Linguagem (LLMs). Essencialmente, essa prática funciona como uma forma de "programação em linguagem natural", permitindo que o usuário molde a saída do sistema sem a necessidade de alterar o código interno ou os pesos dos algoritmos. Trata-se de uma ciência empírica baseada no ciclo iterativo de planejar, criar e testar comandos para extrair o máximo potencial das ferramentas de IA.
A importância dessa disciplina reside no fato de que a eficácia prática da IA depende substancialmente da qualidade das instruções recebidas. Em um cenário onde cerca de 75% das organizações utilizam IA generativa, dominar a engenharia de prompt tornou-se uma nova forma de literacia digital indispensável para o século XXI. Ela é considerada uma "meta-habilidade" que destrava outras competências, permitindo que profissionais assumam o controle total da ferramenta e evitem resultados genéricos ou robóticos.
As aplicações práticas abrangem diversos setores do conhecimento:
Desenvolvimento de Software: É utilizada para refatoração de código, geração de testes unitários, debugging e criação de documentação técnica.
Marketing e Negócios: Auxilia na criação de estratégias de conteúdo, análise de mercado com dados atualizados e otimização de SEO.
Direito e Auditoria: Facilita a análise de riscos fiscais, a elaboração de sumários executivos e a classificação estruturada de documentos jurídicos.
Educação: Permite a tutoria personalizada e a adaptação de explicações complexas para diferentes níveis de aprendizado.
O impacto na qualidade das respostas geradas é significativo, com pesquisas indicando que prompts bem estruturados podem aumentar a precisão da IA em 20% a 40%. O uso de técnicas como o Few-shot prompting (fornecer exemplos) melhora a compreensão da tarefa pelo modelo, enquanto o Chain-of-Thought (Cadeia de Pensamento) eleva drasticamente o desempenho em problemas lógicos e matemáticos ao forçar a IA a raciocinar passo a passo. Além disso, a engenharia de prompt é fundamental para reduzir as alucinações — quando a IA inventa fatos — ao estabelecer restrições claras, exigir evidências contextuais e dar permissão para que o modelo admita quando não possui a informação necessária"

CONCLUSÃO DO TESTE 3: A resposta obtida do prompt melhorado ficou mais aprofundada e com linguagem acadêmica, o foco foi maior e o conteúdo mais direcionado, isso melhorou significativamente a relevância das informações geradas.






♦TESTE 4: USO DA PERSONA NO PROMPT

PROMPT: "Explique o que são prompts."

RESPOSTA OBTIDA: "Um prompt é o comando, instrução ou estímulo fornecido como entrada para um modelo de inteligência artificial generativa para guiar a sua resposta. Ele funciona como uma interface de programação em linguagem natural, permitindo que o usuário molde o comportamento e a saída da máquina sem a necessidade de alterar o código interno do sistema. Embora sejam majoritariamente baseados em texto, os prompts também podem envolver outras mídias, como imagens, sons ou vídeos. Para ser eficaz, a instrução deve ser estruturada de forma estratégica, definindo preferencialmente elementos como o papel (persona), a tarefa clara, o contexto relevante e o formato de entrega esperado"

PROMPT MELHORADO: "Explique o que são prompts como se fosse um professor ensinando um aluno iniciante que nunca utilizou inteligência artificial anteriormente."

RESPOSTA OBTIDA: "Um prompt é, de maneira simples, o comando, a pergunta ou a instrução que você fornece a uma Inteligência Artificial para que ela execute uma tarefa e te dê uma resposta útil. Imagine que a IA é como uma ferramenta extremamente poderosa que precisa de um guia; o prompt é o estímulo ou a orientação estratégica que diz para onde ela deve ir e como deve se comportar.
A regra de ouro para você que está começando agora é pensar o seguinte: "Se eu desse essa mesma instrução para uma pessoa comum ao meu lado, ela saberia exatamente o que fazer?". Se a sua instrução for clara e trouxer contexto, a IA terá muito mais chances de entregar um resultado de alta qualidade.
Embora a maioria dos prompts que usamos no dia a dia sejam feitos por texto, eles também podem envolver imagens, sons ou outros arquivos. No fundo, o prompt funciona como uma nova forma de "programação em linguagem natural", onde você assume o controle da máquina apenas conversando com ela, sem precisar aprender códigos de computador complicados."

CONCLUSÃO DO TESTE 4: Após a mudança no prompt usando a Persona, a resposta mudou de tom, ficou mais didática e com uma linguagem simplificada.

## 📖 Miniguia de Estudo (Entrega Final)

📌 Principais Aprendizados

Durante o desenvolvimento deste projeto foi possível compreender que a Engenharia de Prompt não consiste apenas em “fazer perguntas para uma IA”, mas sim em estruturar instruções capazes de direcionar corretamente o comportamento do modelo.

Os estudos demonstraram que os principais fatores que influenciam a qualidade das respostas são:

-clareza
-especificidade
-contexto
-definição de persona
-estrutura do comando
-detalhamento do objetivo

Também foi observado que prompts vagos tendem a gerar respostas superficiais, enquanto prompts refinados produzem resultados mais precisos, organizados e úteis.


📚 Glossário:

### Engenharia de Prompt
Prática de criar e otimizar comandos para obter respostas mais precisas e úteis da Inteligência Artificial.

### Prompt
Comando ou instrução enviada para a IA gerar uma resposta.

### Inteligência Artificial (IA)
Tecnologia capaz de interpretar informações, aprender padrões e gerar respostas automaticamente.

### Contexto
Informações adicionais fornecidas no prompt para direcionar melhor a resposta da IA.

### Persona
Papel definido para influenciar a forma, o tom e o nível de explicação da resposta gerada pela IA.

📝 Resumo Estruturado

A Engenharia de Prompt é a prática de criar e melhorar comandos para conseguir respostas melhores da Inteligência Artificial.
Durante os testes feitos neste projeto, foi possível perceber que a forma como o prompt é escrito influencia diretamente a qualidade da resposta gerada pela IA.
Fatores como clareza, contexto, especificidade e definição de persona ajudam a IA a entender melhor o que está sendo pedido, gerando respostas mais completas, organizadas e úteis.
Também foi possível observar que prompts muito vagos costumam gerar respostas mais simples e genéricas, enquanto prompts mais detalhados produzem respostas mais aprofundadas e didáticas.
Além disso, técnicas como definir formato da resposta, explicar o objetivo do prompt e utilizar personas tornam a comunicação com a IA muito mais eficiente.


PROMPTS REUTILIZÁVEIS:

Explicação para iniciantes
"Explique [assunto] para iniciantes utilizando linguagem simples e exemplos práticos."

Resumo estruturado
"Crie um resumo organizado sobre [assunto], separando definição, aplicações, vantagens e desafios."

Explicação com persona
"Explique [assunto] como se fosse um professor ensinando um aluno iniciante."

Comparação de conceitos
"Compare [conceito 1] e [conceito 2], destacando diferenças, vantagens e aplicações."

Resposta em tópicos
"Explique [assunto] utilizando tópicos curtos, organizados e objetivos."
