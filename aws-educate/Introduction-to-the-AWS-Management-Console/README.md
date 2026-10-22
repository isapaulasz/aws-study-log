# Introdução ao Console de Gerenciamento da AWS

## Detalhes do curso
- **Objetivo do curso**: Adquirir conhecimento necessário para começar a usar o Console de Gerenciamento da AWS

- **Nível do curso**: indicado para iniciantes em computação em nuvem e serviços AWS, não é necessário conhecimento aprofundado

- **Meta ao final do curso**: Ser capaz de:
    - Descrever a finalidade do Console de Gerenciamento da AWS;
    - Navegar pelos recursos e funções do Console de Gerenciamento da AWS;
    - Descrever a infraestrutura global da AWS;
    - Identificar modelos de pagamento da AWS e fatores de custo dos serviços.

- **Estrutura do curso**:
    - Primeira seção: Módulo de conteúdo. Parte onde são ensinadas as informações e habilidades relacionadas ao conteúdo. Duração aproximada de 30min.
    - Segunda seção: Avaliação final. É necessário ser aprovado(a) com pontuação mínima de 70%. Duração aproximada de 10min.

## Módulo

### Navegação no Console de Gerenciamento da AWS

- O console pode ter aparências diferentes quando acessado em dispositivos diferentes
- Configurar uma conta AWS: é possível criar uma nova conta selecionando "Create an AWS Account" ou fazer login selecionando "Sign in"
- Para fazer login na AWS, é possível entrar como "Root user" ou "AWS account". Pela natureza crítica do root user, é recomendado utilizar um e-mail acessado por um grupo, e não apenas um indivíduo. 
- Widgets: ao fazer login, é acessado a página inicial do console. É possível customizar o console usando a barra "Widgets", redimensionar usando o ícone do menu, resetar para o layout padrão, salvar widgets como favoritos em "Add Widget". Essas alterações não influenciam usuários compartilhados. 
- Descobrir serviços: é possivel usar a barra de pesquisa para buscar serviços pelo nome, acessar via "View all" na aba "Recently visited" na página inicial do console, ou selecionar a aba "Services" para ver todos os serviços.
- Lista de favoritos: É possível criar a lista selecionando "Add Widget". A lista é armazenada nos cookies do site, e sua remoção gera a perda da lista.


### Faturamento

- Infraestrutura global da AWS: Ao escolher os serviços no console AWS, é importante entender o impacto das regiões. 
- Região: área geográfica em que os data centers da AWS abrigam o hardware usado na infraestrutura de nuvem. A região afeta os serviços disponibilizados, custo e latência para o usuário.
- Ao escolher o serviço, é uma boa prática escolher a região mais próxima dos clientes. 
- Por motivos legais de conformidade de dados, certos dados devem permanecer em determinada região.
- Nem todos os serviços estão disponíveis em todas as regiões. US East Virginia é a região primária da AWS, fornece acesso a todos os serviços da AWS e deve ser a região escolhida para treinamentos na AWS.
- Zona de disponibilidade: Regiões consistem em dois ou mais locais isolados, denominados Zonas de disponibilidade. são compostas por um pequeno campus de edifícios (data centers) com latência e redundância ultrabaixas. Elas estão conectadas uns aos outros e à internet para que não sejam afetados simultaneamente por um cenário compartilhado de destruição.
- Modelos de pagamento: AWS usa pagamento conforme o uso. Isso significa que você paga apenas pelos serviços que você precisa, e tempo que os utilizar.
- AWS Cost Explorer permite visualizar e analisar seus custos e uso da AWS
- Os preços variam de acordo com a Região e o Serviço, é importante levar em consideração todos os serviços e regiões para determinar o verdadeiro custo total.