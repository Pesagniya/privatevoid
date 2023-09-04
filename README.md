# Nome do Projeto

LinkHub (placebo)

## Tecnologias usadas

A definir

## Resumo do Projeto

O projeto propõe o desenvolvimento de uma plataforma online que visa atender a um público-alvo composto por profissionais autônomos, pequenas empresas e consumidores em busca de serviços diversos. 

## Público-Alvo

1. *Profissionais Autônomos*: Este grupo inclui freelancers de diversas áreas, como programadores, escritores, consultores, entre outros. Eles buscam uma plataforma que os ajude a encontrar projetos compatíveis com suas habilidades e interesses. 

Empresas ? Linkedin 

3. *Clientes*: Pessoas que precisam de serviços específicos, como reparos em casa, aulas particulares, entre outros. A plataforma facilitará a busca por profissionais qualificados e confiáveis. 

## Dores Resolvidas

1. *Dificuldade em Encontrar Serviços ou Profissionais Confiáveis*: Muitos consumidores e empresas enfrentam dificuldades para encontrar prestadores de serviços qualificados. A plataforma resolverá esse problema, oferecendo acesso a uma rede de profissionais verificados e avaliados pelos usuários. 

2. *Tempo Gasto em Buscas*: A busca manual por profissionais e serviços pode ser demorada. A plataforma economizará tempo, permitindo que os usuários encontrem rapidamente o que precisam com base em suas preferências e requisitos. 

3. *Problemas de Comunicação e Agendamento*: Muitos enfrentam desafios na comunicação e no agendamento de serviços. A plataforma facilitará a comunicação direta entre prestadores de serviços e clientes, além de oferecer ferramentas de agendamento. 

## Monetização

1. *Taxas de Transação*: A plataforma cobrará uma pequena porcentagem de cada transação concluída entre prestadores de serviços e clientes. 

2. *Assinaturas Premium*: Oferecerá planos de assinatura premium para profissionais autônomos, que incluirão recursos adicionais, como destaque nas buscas e acesso a análises avançadas. 

# Briefing Plataforma de Serviços
## Resumo: Sistema de Listagem de Serviços
- Nessa primeira versão será implementado um MVP (Produto Mínimo Viável), dessa forma, atender somente às necessidades do MVP.
- Novas funcionalidades poderão ser implementadas em versões futuras, à medida que o projeto seja validado.

## Requisitos da primeira versão (MVP)
 - A plataforma deve estar on-line em tempo integral, com exceção de serviços de manutenção.
  - Cada freelancer deverá ser devidamente verificado pelo admnistrador por quesitos de segurança.
  - O freelancer lista o serviço que será prestado, adotando uma breve descrição de suas habilidades e estimativas quanto ao preço do serviço.
  - Cada atendimento deve durar o tempo de 30 minutos e os horários de agendamento são intercalados a cada 30 minutos (das 08:00 às 12:00 e das 13:00 às 18:00 horas de segunda à sexta) (Isso poderá mudar no futuro).
  - O sistema não deve permitir agendar fora do horário e dias da semana de cada profissional.
  - O sistema não deve permitir agendar duas ou mais clientes no mesmo dia e horário de um profissional.
  - O sistema não deve permitir agendar o mesmo cliente no mesmo dia e horário.
  - O atendente pode cancelar um atendimento quando solicitado pelo cliente. Nas remover a consulta, apenas mudar o status para CANCELADO.
  - O sistema deve controlar a frequência dos clientes (PRESENTE ou AUSENTE).
    - O status PRESENTE só deve ser alterado no dia do Agendamento. 
    - O status AUSENTE só pode ser alterado depois da data e hora do Agendamento
  - Ao agendar uma consulta, selecionar primeiro a área e depois o profissional.
  - Agendar somente com profissionais ativos.
  - Não agendar no passado.
  - Não remover clientes com consultas ou sessões realizadas.
  - Não remover profissionais com consultas ou sessões realizadas.
  - Não remover Area e Tipo de Consulta com relacionamentos.
 
## Observações
1. **Cadastro de Usuário:** Permitir que prestadores de serviços e clientes criem contas com informações básicas, como nome, e-mail e senha. 

2. **Listagem de Serviços:** Oferecer uma interface para prestadores de serviços descreverem seus serviços, incluindo detalhes, preços e disponibilidade. 

3. **Busca Avançada:** Permitir que os clientes pesquisem serviços com base em critérios como localização, categoria, avaliações e preço. 

4. **Avaliações e Comentários:** Possibilitar que os clientes avaliem e comentem sobre os serviços prestados pelos profissionais. 

5. **Agendamento de Serviços:** Implementar um sistema de agendamento que permita que os clientes reservem serviços diretamente pela plataforma. 

6. **Sistema de Mensagens:** Facilitar a comunicação entre prestadores de serviços e clientes através de mensagens instantâneas.

7. **Autenticação de Usuário:** Garantir a segurança com autenticação de dois fatores e recuperação de senha.

## Um perfil
- Admnistrador

## Responsividade
- Ter o layout correto para larguras de tela com 350px ou mais.
- Não considerar larguras menores que 350px. 

banco de dados
