# DESAFIO-QA-BEEDOO-2026

A aplicação tem como objetivo realizar o cadastro e a listagem de cursos. Considerando o contexto de atuação da empresa, acredito que o teste foi desenvolvido para simular um cenário comum de sistemas corporativos, permitindo avaliar a capacidade do candidato em identificar falhas, validar campos, regras de negócio e analisar o comportamento da aplicação sob a perspectiva de garantia de qualidade (QA).

Temos dois fluxos principais, separados por guias. Ao abrirmos o link https://creative-sherbet-a51eac.netlify.app/ , seremos direcionados inicialmente para a guia "Listar cursos".
Ela exibe uma lista com todos os cursos previamente cadastrados. Para cada curso são apresentadas informações principais como imagem, tipo de curso (presencial ou online), nome, descrição, data de início, data fim e quantidade de vagas. Nessa mesma lista também é possível excluir cursos cadastrados, permitindo o gerenciamento dos registros existentes.
Obs: Caso ainda não tenham sido cadastrados cursos, a página permanecerá em branco.
Clicando na guia "Cadastrar cursos" é permitido inserir um novo curso no sistema por meio do preenchimento de um formulário. Nessa guia, o usuário informa os dados do curso, como nome do curso, descrição, instrutor, data de início, data fim, URL para uso de imagens, número de vagas, tipo de curso (presencial ou online) e local do curso, que varia conforme o tipo selecionado (endereço para cursos presenciais ou link para cursos online).

Durante a realização dos testes na aplicação, foram identificados alguns pontos críticos que podem impactar a integridade dos dados e o funcionamento adequado do sistema. Entre os principais problemas observados está a ausência de validações adequadas nos campos do formulário de cadastro, permitindo que informações inconsistentes ou inválidas sejam inseridas no sistema.
Também foram identificadas falhas na estrutura do HTML da página, o que pode afetar a padronização do código, a manutenção da aplicação e, em alguns casos, a experiência do usuário. Além disso, foram encontrados problemas relacionados à validação das datas de cadastro, possibilitando a inserção de valores fora de um intervalo lógico ou em formatos que não seguem um padrão esperado.
Outro ponto crítico observado foi uma falha na funcionalidade de exclusão de cursos, indicando que o sistema não executa corretamente a remoção dos registros ou não apresenta o comportamento esperado durante essa ação.
De forma geral, os problemas identificados indicam a necessidade de melhorias nas validações de entrada de dados, na consistência das regras de negócio e na estrutura da aplicação, a fim de garantir maior confiabilidade das informações, estabilidade do sistema e uma melhor experiência para o usuário final.

https://docs.google.com/spreadsheets/d/1CBrTtpe5Cs4rEvnKmtiIl8MmTeuwbebkboOBQlmn4kQ/edit?usp=sharing
