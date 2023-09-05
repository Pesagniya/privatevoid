# Nome do Projeto

(placebo)

## Tecnologias

A ser definido.

## Resumo do Projeto

O projeto propõe o desenvolvimento de uma plataforma online que visa atender a um público-alvo composto por profissionais autônomos e consumidores em busca de serviços diversos. O objetivo principal é introduzir trabalhos informais a aclimatizar novos profissionais em seu nicho de atuação, dispondo serviços à preços acessíveis e em localidades próximas ao cliente.

## Público-Alvo

1. *Profissionais Autônomos*: Este grupo inclui freelancers de diversas áreas, como programadores, escritores, consultores, entre outros. Eles buscam uma plataforma que os ajude a encontrar projetos compatíveis com suas habilidades e interesses. 

2. *Clientes*: Pessoas que precisam de serviços específicos, como reparos em casa, aulas particulares, entre outros. A plataforma facilitará o processo da busca por profissionais próximos.

## Dores Resolvidas

1. *Dificuldade em Encontrar Serviços ou Profissionais Confiáveis*: Muitos consumidores e empresas enfrentam dificuldades para encontrar prestadores de serviços qualificados. A plataforma resolverá esse problema, oferecendo acesso a uma rede de profissionais verificados e avaliados pelos usuários. 

2. *Tempo Gasto em Buscas*: A plataforma economizará tempo, permitindo que os usuários encontrem rapidamente o que precisam com base em suas preferências e requisitos. 

3. *Problemas de Comunicação e Agendamento*: A plataforma facilitará a comunicação direta entre freelancers e clientes, além de oferecer ferramentas para o agendamento do serviço.

## Monetização

1. *Taxas de Transação*: A plataforma cobrará uma pequena porcentagem de cada transação concluída entre prestadores de serviços e clientes. 

2. *Assinaturas Premium*: Oferecerá planos de assinatura premium para profissionais autônomos, no qual será incluído recursos adicionais, como destaque nas buscas e acesso a análises avançadas. 

# Briefing Plataforma de Serviços
## Resumo: Sistema de Listagem de Serviços
- Nessa primeira versão será implementado um MVP (Produto Mínimo Viável), dessa forma, atender somente às necessidades do MVP.
- Novas funcionalidades poderão ser implementadas em versões futuras, à medida que o projeto seja devidamente validado.

## Requisitos da primeira versão (MVP)
 - Clientes e freelancers podem se cadastrar na plataforma com informações básicas, como nome, e-mail e senha.
 - Clientes podem pesquisar serviços com base em critérios como categoria, localização e avaliações.
 - Prestadores de serviços podem listar os serviços que oferecem, incluindo descrições, preços e disponibilidade.
 - Cada freelancer deverá ser devidamente autenticado pelo admnistrador por quesitos de segurança.
 - O freelancer lista o serviço que será prestado, adotando uma breve descrição de suas habilidades e estimativas quanto ao preço do serviço.
 - O sistema não deve permitir que o cliente agende dois ou mais serviços no mesma data.
 - O sistema não deve permitir que o mesmo profissional seja requisitado por dois clientes na mesma data.
 - O sistema oferece um chat para a comunicação eficiente entre os atores envolvidos.
 - Caso o freelancer aceite a data de agendamento do cliente, a transação será registrada no sistema.
 - Tanto o cliente quanto o freelancer têm a opção de cancelar o agendamento. Entretanto, uma multa fixa deve ser repassada caso o cancelamento seja feito no mesmo dia do agendamento.
 - Após a conclusão do serviço, o cliente tem a opção de avaliar a qualidade do produto entregue.
   
## Manutenção de Dados Adicionais:

- Manutenção de informações de clientes: Nome, telefone e data de nascimento.
- Manutenção de informações de profissionais: Nome, telefone, data de nascimento e especialização.
- Ao desativar a conta de um usuário, todos os agendamentos futuros serão cancelados.
- Os agendamentos incluem informações como cliente, profissional, área, tipo, comentários, data e horário de início.
- Mostrar disponibilidade de datas e horários dentro de um mês.
- Ao agendar uma consulta, confirmar o telefone do cliente selecionado.
- Cancelamento de Consultas:
- As consultas canceladas continuam registradas no sistema, com apenas a data e horário liberados para novos agendamentos.
- Os usuários podem acessar o histórico completo de seus serviços na plataforma.

## Três perfis

- Cliente:
  - Permite buscar e visualizar serviços oferecidos pelos freelancers.
  - Permite agendar serviços com freelancers disponíveis.
  - Permite visualizar e gerenciar seus agendamentos.
  - Permite avaliar e deixar comentários sobre os serviços prestados.
  - Permite trocar mensagens com os freelancers para esclarecimento de dúvidas.
  - Permite atualizar seu próprio perfil, incluindo informações pessoais e preferências.
    
- Freelancer:
  - Permitelistar os serviços que oferece, incluindo detalhes, preços e disponibilidade.
  - Permite visualizar solicitações de agendamento e confirmar ou rejeitar agendamentos.
  - Permite gerenciar seu calendário de disponibilidade e horários de trabalho.
  - Permite trocar mensagens com os clientes para esclarecimento de dúvidas e detalhes do serviço.
  - Permite atualizar seu próprio perfil, incluindo informações pessoais e de serviços oferecidos.

- Administrador:
  - Permite fazer a manutenção de novos usuários, incluindo clientes e freelancers.
  - Permite gerenciar as categorias de serviços.
  - Permite adicionar, editar ou remover informações de profissionais.
  - Permite acesso a ferramentas de moderação e gerenciamento de conteúdo.
  - Permite acessar dados estatísticos e análises para melhorias na plataforma.
  
## Responsividade
- Ter o layout correto para larguras de tela com 350px ou mais.
- Não considerar larguras menores que 350px. 
