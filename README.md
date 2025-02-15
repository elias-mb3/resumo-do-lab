# Az-900

## Microsoft Azure: Provedor de Cloud da Microsoft  

Microsoft Azure é uma plataforma de computação em nuvem que oferece serviços de infraestrutura (IaaS), plataforma (PaaS) e software (SaaS). Permite a criação, implantação e gerenciamento de aplicativos e serviços através de data centers globais. Suporta diversas linguagens de programação e ferramentas, integrando-se ao ecossistema Microsoft e de terceiros. Possui soluções para inteligência artificial, machine learning, IoT, segurança, banco de dados, redes e muito mais. Com escalabilidade flexível, atende desde startups até grandes empresas. A cobrança segue um modelo de pagamento conforme o uso, otimizando custos. A segurança é reforçada com compliance e certificações internacionais.  

## Benefícios da Alta Disponibilidade e Escalabilidade na Nuvem

A computação em nuvem oferece vantagens significativas em termos de alta disponibilidade e escalabilidade. A alta disponibilidade garante que os recursos estejam acessíveis sempre que necessário, mesmo diante de falhas ou interrupções. No Azure, isso é assegurado por meio de SLAs (Contratos de Nível de Serviço) que definem garantias de tempo de atividade para diferentes serviços.

A escalabilidade permite ajustar os recursos conforme a demanda. Isso pode ser feito de duas maneiras:

- **Escala Vertical**: Aumenta ou diminui a capacidade de um recurso específico, como adicionar mais CPU ou memória a uma máquina virtual.

- **Escala Horizontal**: Adiciona ou remove instâncias de um recurso, como múltiplas máquinas virtuais, para distribuir a carga de trabalho.

Essas capacidades garantem que os aplicativos possam lidar eficientemente com variações no tráfego, mantendo o desempenho e otimizando custos. 

## Benefícios da Computação em Nuvem

A computação em nuvem oferece diversas vantagens que aprimoram a eficiência e a segurança das operações de TI:

### Confiabilidade e Previsibilidade

Devido ao design descentralizado, a nuvem suporta uma infraestrutura resiliente, permitindo a implantação de recursos em múltiplas regiões globais. Isso assegura continuidade operacional mesmo diante de falhas regionais. A previsibilidade abrange tanto o desempenho, com recursos como dimensionamento automático e balanceamento de carga, quanto os custos, possibilitando monitoramento em tempo real e estimativas precisas de gastos. 

### Segurança e Governança

Os provedores de nuvem implementam robustas medidas de segurança, incluindo proteção contra ataques DDoS. Ferramentas de governança garantem que os recursos implantados atendam aos padrões corporativos e regulatórios, com auditorias e atualizações automáticas para manter a conformidade e a segurança. 

### Capacidade de Gerenciamento

A nuvem oferece opções avançadas de gerenciamento, como escalonamento automático de recursos conforme a demanda, implantação baseada em modelos pré-configurados, monitoramento contínuo da integridade dos recursos e alertas automáticos baseados em métricas definidas. Além disso, os ambientes de nuvem podem ser gerenciados via portais web, interfaces de linha de comando, APIs ou PowerShell, proporcionando flexibilidade operacional. 

## Acordos de Nível de Serviço (SLA) do Microsoft Azure

O Microsoft Azure estabelece Acordos de Nível de Serviço (SLAs) que definem os compromissos de disponibilidade e conectividade para seus serviços online. Esses SLAs especificam garantias de tempo de atividade para diferentes serviços, como Máquinas Virtuais, Banco de Dados SQL e Armazenamento, com percentuais que podem variar conforme o serviço. Por exemplo, alguns serviços oferecem garantias de até 99,95% de disponibilidade. :contentReference[oaicite:0]{index=0}

## Diferenças entre IaaS, PaaS e SaaS

Na computação em nuvem, existem três modelos principais de serviço, cada um oferecendo diferentes níveis de controle, flexibilidade e gerenciamento:

- **Infraestrutura como Serviço (IaaS)**: Fornece acesso sob demanda a recursos de computação fundamentais, como servidores físicos e virtuais, armazenamento e redes. É ideal para empresas que desejam gerenciar diretamente sua infraestrutura de TI, mantendo controle sobre sistemas operacionais e aplicativos. :contentReference[oaicite:1]{index=1}

- **Plataforma como Serviço (PaaS)**: Oferece uma plataforma completa na nuvem para desenvolvimento, execução e gerenciamento de aplicativos, sem a complexidade de gerenciar a infraestrutura subjacente. É adequada para desenvolvedores que buscam um ambiente simplificado para criar e implantar aplicativos rapidamente. :contentReference[oaicite:2]{index=2}

- **Software como Serviço (SaaS)**: Disponibiliza aplicativos prontos para uso, hospedados na nuvem, acessíveis via internet. Os usuários não precisam se preocupar com a manutenção ou gerenciamento da aplicação ou da infraestrutura. É ideal para empresas que necessitam de soluções completas sem a necessidade de desenvolvimento ou gerenciamento de aplicativos. :contentReference[oaicite:3]{index=3}

A escolha entre esses modelos depende das necessidades específicas de cada organização, considerando fatores como controle desejado, recursos disponíveis e objetivos de negócios.

## Zonas de Disponibilidade do Azure

As **Zonas de Disponibilidade** são grupos de datacenters fisicamente separados dentro de uma região do Azure. Cada zona possui infraestrutura independente de energia, resfriamento e rede, garantindo que, se uma zona enfrentar interrupções, as outras possam manter a disponibilidade dos serviços regionais. Essas zonas são interconectadas por redes de alta performance com latência inferior a 2 ms, proporcionando baixa latência e alta resiliência. :contentReference[oaicite:0]{index=0}

## Regiões Emparelhadas do Azure

O Azure organiza algumas de suas regiões em **pares de regiões**, onde duas regiões dentro da mesma geografia são associadas para fornecer replicação e redundância geográfica. Essa configuração oferece benefícios como recuperação sequencial em casos de interrupções e atualizações planejadas de forma escalonada para minimizar o impacto. Além disso, o isolamento físico entre regiões emparelhadas reduz a probabilidade de desastres afetarem ambas simultaneamente. :contentReference[oaicite:1]{index=1}

## Grupos de Gerenciamento do Azure

Para organizações com múltiplas assinaturas, os **Grupos de Gerenciamento** oferecem um nível superior de governança no Azure. Eles permitem a aplicação de políticas e controle de acesso de forma unificada, propagando configurações para todas as assinaturas e recursos subordinados. É possível estruturar uma hierarquia flexível de grupos de gerenciamento e assinaturas, facilitando o gerenciamento eficiente e a conformidade com as diretrizes corporativas. :contentReference[oaicite:2]{index=2}

