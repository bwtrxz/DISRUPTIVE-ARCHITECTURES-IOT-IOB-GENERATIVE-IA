# DISRUPTIVE-ARCHITECTURES-IOT-IOB-GENERATIVE-IA
  O objetivo principal do projeto é desenvolver um sistema de recomendações personalizadas voltado para a educação e o desenvolvimento profissional. Com a crescente demanda por aprendizado contínuo e a vasta oferta de recursos educacionais online, torna-se desafiador para os profissionais identificar quais cursos, materiais e atividades são mais adequados às suas necessidades específicas de crescimento.
  
  Inicialmente, a proposta era utilizar a IA generativa LLAMA, selecionada por sua capacidade de suportar múltiplos idiomas, o que possibilitaria o acesso da aplicação a usuários de diversos países, além do Brasil. Essa tecnologia também se destacou por ser gratuita para pesquisas e uso comercial, incorporando aprendizagem por reforço com feedback humano. Além da escolha dessa IA, foi escolhido também utilizar as bibliotecas Pandas e NumPy, devido às suas funcionalidades que facilitam a manipulação e análise de dados, assim como operações matemáticas e numéricas.
No entanto, nos primeiros testes e durante o desenvolvimento diversos imports, incluindo Pandas, NumPy e TfidfVectorizer foram utilizados para garantir o bom funcionamento do sistema. Os resultados iniciais mostraram um código que não utilizava uma IA generativa para as recomendações, contrariando a proposta inicial e principal do grupo, além disso o sistema baseou-se em um banco de dados (Excel) contendo informações sobre usuários, a partir do qual gerava recomendações baseadas em padrões.

O sistema oferecia três opções ao usuário:
  •	Opção 1: Recomendação de cursos;
  •	Opção 2: Adicionar informações de usuários;
  •	Opção 3: Sair;

  Na Opção 1, os usuários forneciam informações sobre seus interesses e recebiam recomendações baseadas nas respostas de outros usuários cadastrados. A Opção 2 permitia a inserção de novas informações sobre usuários, enquanto a Opção 3 encerrava a execução do código.
  
  Após a apresentação e entrega do projeto, os feedbacks foram recebidos e implementamos mudanças significativas. A primeira mudança foi a integração da IA Gemini do Google possibilitando que as recomendações fossem feitas de maneira mais assertiva, alinhando-se melhor aos interesses do usuário. O sistema coleta e processa dados do usuário, como perfil, histórico de aprendizado, interesses e metas profissionais e esses dados são armazenados em um arquivo Excel, permitindo um pré-processamento eficaz. A geração de recomendações é realizada por meio de uma API externa (Google Gemini), que utiliza uma função para criar recomendações personalizadas com base nos interesses do usuário. O código envia um prompt para o modelo Gemini, que já está treinado, gerando respostas alinhadas aos interesses individuais. Além disso, o código foi atualizado para retornar de três a cinco recomendações diferentes, cada uma acompanhada de uma breve descrição, e as três funcionalidades propostas foram mantidas, enquanto as bibliotecas NumPy e TfidfVectorizer foram descontinuadas.
  
  Essas alterações não apenas melhoraram a funcionalidade do sistema, mas também destacaram a importância da adaptabilidade e do aprendizado contínuo em projetos de tecnologia. As propostas iniciais foram testadas, mas os resultados não foram satisfatórios, o que nos levou a repensar o projeto, realizar novas pesquisas e implementar mudanças significativas.
Como grupo de desenvolvedores, percebemos que um planejamento mais cuidadoso e aprofundado desde o início poderia ter contribuído para um sistema mais robusto e complexo. As novas mudanças foram implementadas na "reta final", resultando em uma solução mais simples e funcional, o que é com certeza um resultado satisfatório, mas poderíamos mais. 

  A jornada de desenvolvimento nos ensinou não apenas sobre programação e implementação de IA, mas também sobre a importância de ouvir feedbacks, ajustar o produto às necessidades dos usuários e investir em um planejamento e organização adequados.


