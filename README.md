# Projeto Beedoo Chalenge
# versão 1.0 #
# autor: José Roberto de Azevedo #


Desafio | Analista de Qualidade de Software Júnior

Este desafio tem o objetivo de avaliar seus conhecimentos e habilidades em teste de software.

**Descrição do projeto**

O teste será composto por duas etapas. A 1ª será a análise e criação dos cenários e casos de teste da tela de cursos do Beedoo Chalenge (Testes Manuais)

A 2ª será descrever como você lida com os problemas apresentados.

Você terá acesso ao módulo de curso e nele será possível, criar, excluir e listar os cursos criados.

OBS: **Ambas etapas devem ser enviadas simultaneamente**

**ETAPA 1: 

Seu desafio deve ter:**

- Você deverá criar Users story e criação dos casos de teste do módulo de curso do Beedoo (https://creative-sherbet-a51eac.netlify.app/)
- No user story deve conter uma documentação informando:
    - Como foram as decisões tomadas para criar user story
    - Para essa documentação, deve ser utilizado o **README do seu repositório no GitHub**
- Você deverá analisar o módulo de curso e criar todos os cenários e casos de teste de sucesso e de erro
- Os casos de teste deverão ser escritos em gherkin
- Documentar todos os cenários e casos de teste em uma planilha no Google Docs e **disponibilizar o link no seu repositório no GitHub**
- Criar um passo-a-passo para execução de cada caso de teste
- Gerar evidências do teste em formato MP4
- Armazenar as evidências no drive e **adicionar o link no seu repositório do GitHub**
- No GitHub, crie um repositório chamado **DESAFIO BEEDOO** e anexe o link no campo GITHUB no formulário do Google que recebeu no email.

**ETAPA 2:** 

**Você deve resolver:**

- Durante os testes do módulo de curso do Beedoo Chalenge, você pode descobrir um erro (exemplo 404) em algum fluxo. Descreva o bug identificado, incluindo passos para reproduzi-lo, gravidade do problema e o que pode ocasionar esse tipo de erro.
- Na criação do curso existem vulnerabilidades.
Liste quais vulnerabilidades foram identificadas em seus testes e quais técnicas utilizaria para identificar outras potenciais vulnerabilidades.
- **Situação hipotética:** dado que você recebe a especificação do módulo de curso para testar a funcionalidade. Identifique ao menos 3 pontos críticos que exigem esclarecimentos do time responsável antes do início dos testes. Qual seria o próximo passo e como seria realizado para garantir que a funcionalidade seja entregue com qualidade?
- Você recebe essa feature para testar e nos seus testes você identifica alguns erros. Como você avalia e define se o erro foi causado por essa feature? Caso não seja causado por ela, o que faria?
- **As respostas deverão ser enviadas no formulário que recebeu no e-mail**


# User Story 

1. # Título: Gerenciamento de Cursos Online/Presencial do Beedoo

Como possível administrador do sistema:
Eu quero cadastrar, listar, excluir e editar cursos na página https://creative-sherbet-a51eac.netlify.app/
Para gerenciar o catálogo de cursos oferecidos.
Decisões Tomadas
    1.1	Cadastro de Cursos: Permitir que o administrador adicione novos cursos com informações básicas como nome, descrição e duração.
    1.2	Listagem de Cursos: Prover uma visualização que permita ver todos os cursos cadastrados.
    1.3	Exclusão de Cursos: Permitir que o administrador remova cursos do catálogo.
    1.4  Edição de Cursos:   Permitir que o administrador edite cursos deo catálogo.

2. **Justificativas de tomadas de decisões:**

Essas decisões foram tomadas com base na necessidade de manter um catálogo atualizado e organizado de cursos online, garantindo que informações precisas e relevantes estejam disponíveis para os usuários.

3.	# Validações e Critérios de Aceite para o formlário do Curso:

    a) O campo Nome do curso deve se alfanúmerico com no mínimo 5 caracteres e no máximo 255 caracteres
    b) O campo Descrição do curso de ser alfanúmerico com no mínimo 5 caracteres e no máximo 255 caracteres
    c) O campo Instrutor deve ser alfanúmerico com no mínimo 5 caracteres e no máximo 255 caracteres
    d) O campo Data de início deve ser com máscara de calendário
    e) O campo Data de fim deve ser com máscara de calendário
    f) O campo Números de vagas deve ser numérico e permitir números positivos
    g) O campo Tipo de curso deve ser Dropdown com as opções de Presencial ou Online

4.  # Falhas encontrados:

    a) O sistema permite cadastro mesmo com qualquer campo sem preenchimento
    b) O sistema permite o cadastro com uma data incorreta
    c) O sistema não executa a exclusão e o registro continua na tela

5. # Implementações sugeridas:

    a) O sistema não tem a função de edição do registro de cadastro 
    b) Sendo um administrador do sistema, seria interessante a criação de um perfil identificado de acesso para que apenas o mesmo possa realizar as operações de gerenciamento dos cursos

 6. # Links     

    Casos de testes
    
    Evidências
	



