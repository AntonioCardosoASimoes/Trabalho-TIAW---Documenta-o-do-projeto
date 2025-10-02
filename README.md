# Trabalho-TIAW---Documenta-o-do-projeto
# Introdução

Informações básicas do projeto.

- **Projeto:** ConectaSaúde
- **Repositório GitHub:** [text](https://github.com/AntonioCardosoASimoes/Trabalho-TIAW---Documenta-o-do-projeto.git)

- **Membros da equipe:**
  - Antônio Cardoso
  - Caio Fernandes
  - Davi Fideles
  - Maria Eduarda
  - Taccio Gabriel

## Contexto do Projeto  

A rede pública de saúde enfrenta dificuldades recorrentes relacionadas ao longo tempo de espera, grandes filas e à falta de materiais básicos necessários para o atendimento. Esse cenário compromete a qualidade do serviço prestado aos pacientes e gera insatisfação tanto para os usuários quanto para os profissionais de saúde. Nesse contexto, o projeto propõe o desenvolvimento de uma aplicação, disponível tanto em site quanto em aplicativo móvel, que será utilizada em centros de saúde, postos e unidades básicas de saúde (UBS).  

O objetivo geral do trabalho é criar uma solução tecnológica que permita aos pacientes interagir diretamente com as unidades de saúde, fornecendo feedback sobre o atendimento recebido, relatando a ausência de materiais, consultando o tempo médio de espera, localizando o posto de saúde mais próximo e acompanhando seu histórico de atendimentos. Entre os objetivos específicos estão a criação de um sistema acessível e intuitivo, que facilite a comunicação entre pacientes e unidades de saúde, além de proporcionar maior transparência em relação ao tempo de espera e à disponibilidade de atendimento.  

A justificativa para o desenvolvimento desta solução está na urgência de melhorar a qualidade do atendimento prestado pela rede pública, visto que problemas como longas filas e a falta de recursos básicos impactam diretamente no bem-estar e na saúde da população. A aplicação pretende dar voz aos pacientes, permitindo que suas necessidades sejam registradas e acompanhadas de forma organizada, ao mesmo tempo em que oferece aos profissionais e gestores de saúde uma visão mais clara das demandas e dificuldades enfrentadas no cotidiano. Assim, será possível colaborar para a tomada de decisões mais rápidas e eficientes, contribuindo para a redução das desigualdades no acesso à saúde e promovendo um atendimento mais digno e humanizado.  

O público-alvo principal são os pacientes do Sistema Único de Saúde (SUS), que necessitam de atendimentos em centros, postos e UBS, abrangendo diferentes faixas etárias e perfis de conhecimento tecnológico. Além deles, a aplicação também atenderá enfermeiros, atendentes e coordenadores das unidades de saúde, que poderão utilizar os dados coletados para melhorar a gestão do atendimento e otimizar o uso dos recursos disponíveis.  

# Processo de Product Discovery e Product Design

## Processo de Product Discovery

### Matriz CSD
A Matriz CSD (Certezas, Suposições e Dúvidas) foi utilizada para organizar informações relevantes e apoiar a compreensão do problema:

- **Certezas**:  
  - O subfinanciamento do SUS gera falhas na estrutura e infraestrutura.  
  - Há falta de produtos e itens de higiene básica.  
  - A má administração reflete nos serviços prestados.  
  - Existe desigualdade social que afeta o acesso à saúde.  
  - Há sobrecarga de profissionais devido ao aumento da demanda da população.  

- **Suposições**:  
  - Há demora no tempo de espera de ambulâncias.  
  - Existe falta de gestão de pacientes.  
  - Podem ocorrer desafios na implementação de novas tecnologias.  

- **Dúvidas**:  
  - O quanto a falta de investimento em infraestrutura tecnológica impacta os atendimentos.  
  - Se existe descaso com pacientes mais jovens em detrimento da preferência a idosos.  

---

### Mapa de Stakeholders
O mapa de stakeholders permitiu identificar os diferentes grupos relacionados à solução:

- **Pessoas Fundamentais**:  
  Pacientes, população dependente do SUS e profissionais de saúde.  

- **Pessoas Importantes**:  
  Gestores públicos, mídia e opinião pública, empresas privadas de saúde, farmácias do SUS.  

- **Pessoas Influenciadoras**:  
  Ministério da Saúde, Conselhos de Classe (CRM, COFEN etc.), organizações civis e ONGs, Tribunais de Contas e órgãos de controle.  

---

### Entrevistas Qualitativas
As entrevistas qualitativas foram realizadas com pacientes e profissionais da saúde, trazendo percepções relevantes sobre o uso do SUS:

- **Perguntas e respostas:**
  - *Quais são os maiores problemas enfrentados no dia a dia na UBS/UPA?*  
    → "As filas são muito longas, chego de madrugada e ainda espero horas."  
  - *Como foi sua última experiência utilizando o SUS?*  
    → "O atendimento foi bom, mas demorou demais para conseguir ser chamado."  
  - *Há carência de recursos para atender pacientes?*  
    → "Sim, faltam materiais básicos como luvas e seringas."  
  - *Quais produtos básicos deveriam ser implementados como gratuitos?*  
    → "Medicamentos contínuos e itens de higiene."  
  - *Quais programas de saúde pública você considera mais eficazes?*  
    → "As campanhas de vacinação funcionam bem, mas faltam ações de prevenção contínua."  

---

### Highlights de Pesquisa
Resumo dos principais pontos observados nas entrevistas:

- **Falas significativas**: demora no atendimento e falta de materiais básicos.  
- **Aspectos mais importantes para participantes**: rapidez no atendimento e maior organização.  
- **Principais aprendizados**: pacientes valorizam ações preventivas, mas sofrem mais com demora no atendimento.  
- **Novos tópicos a explorar**: gestão tecnológica para reduzir filas e organizar recursos.  

---

### Personas
Foram definidas personas que representam os principais usuários:

- **Rita Soares Lina**  
  - Idade: 62 anos  
  - Hobby: Yoga  
  - Trabalho: Aposentada  
  - Personalidade: Tranquila, mas firme quando necessário; detesta filas.  
  - Objetivos chave: garantir acesso a medicamentos contínuos, reduzir tempo de espera, ter atendimento simples e eficiente.  

- **Fernanda Lopes**  
  - Idade: 42 anos  
  - Hobby: Praticar corrida  
  - Trabalho: Secretária de centro de saúde  
  - Personalidade: Determinada, empática, organizada.  
  - Objetivos chave: oferecer agilidade no atendimento, organizar consultas, melhorar a comunicação com pacientes.  

---

## Processo de Product Design

### Histórias de Usuários
Algumas histórias de usuário levantadas a partir das personas:

- **Como paciente (Rita)**, quero visualizar o tempo de espera em cada posto de saúde, para escolher onde serei atendida mais rápido.  
- **Como paciente (Rita)**, quero registrar minha experiência de atendimento, para que os gestores saibam das falhas.  
- **Como secretária de saúde (Fernanda)**, quero organizar os agendamentos de pacientes em uma única plataforma, para reduzir confusões e filas.  
- **Como profissional de saúde**, quero receber feedback dos pacientes, para melhorar a qualidade do atendimento.  

---

### Proposta de Valor
O mapa de proposta de valor sintetiza como a solução atende às dores e necessidades identificadas:

- **Produtos e Serviços**:  
  Plataforma digital (site e aplicativo) para consulta de tempo de espera, histórico de atendimento, localização de unidades, envio de feedback e registro de falta de materiais.  

- **Analgésicos (redução das dores)**:  
  - Diminuição de filas e tempo de espera.  
  - Melhoria na comunicação entre paciente e unidade de saúde.  
  - Registro de problemas estruturais para gestores.  

- **Criadores de ganhos (geração de valor)**:  
  - Atendimento mais ágil e eficiente.  
  - Maior transparência sobre recursos disponíveis.  
  - Melhor experiência para pacientes e profissionais.  


5. Metodologia
6. Solução
7. Referências Bibliográficas
