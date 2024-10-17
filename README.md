# Otimizando-Custos-no-Azure
Resposta ao desafio DIO - Otimizando Custos no Azure
A Calculadora TCO (Total Cost of Ownership) da Azure é uma ferramenta desenvolvida pela Microsoft para ajudar empresas a estimar e comparar os custos entre manter uma infraestrutura local (on-premises) e migrar para a nuvem Azure. O TCO reflete os gastos totais de uma infraestrutura ao longo do tempo, incluindo despesas iniciais e custos operacionais contínuos, o que é essencial para que organizações avaliem o retorno do investimento (ROI) e determinem se a migração para a nuvem é financeiramente viável.

### Como Funciona a Calculadora TCO

1. **Informações de Configuração Local**:
   - O usuário insere dados específicos sobre a infraestrutura atual (on-premises), como a quantidade de servidores, configurações de armazenamento e de rede, custos de licenciamento, e uso de virtualização.
   - A calculadora permite ajustes detalhados, como especificar o uso de diferentes tipos de servidores (Windows, Linux, etc.) e quantidade de memória e CPU.

2. **Custos Operacionais**:
   - A ferramenta coleta informações sobre gastos operacionais, incluindo despesas de energia, refrigeração, aluguel de data centers, pessoal para manutenção e segurança. 
   - Esses dados são usados para simular o custo de manter a infraestrutura atual por um período de tempo específico.

3. **Simulação de Custos na Azure**:
   - Com base nos dados fornecidos, a Calculadora TCO projeta os custos estimados para a migração da infraestrutura para a Azure, considerando o uso de máquinas virtuais, armazenamento e rede equivalentes aos recursos on-premises.
   - A ferramenta permite explorar diferentes opções de preços e pacotes na Azure, incluindo instâncias reservadas e vantagens do Azure Hybrid Benefit para clientes com licenciamento Windows Server e SQL Server.

4. **Comparação de Custo Total**:
   - Após processar as informações, a calculadora gera um relatório comparativo, que inclui o custo atual da infraestrutura on-premises versus o custo estimado da infraestrutura equivalente na Azure ao longo do mesmo período.
   - Além disso, o relatório destaca as possíveis economias e benefícios adicionais da nuvem, como a flexibilidade de escalar recursos sob demanda e a redução de custos com manutenção e suporte técnico.

5. **Relatório e Compartilhamento**:
   - A calculadora permite a exportação de um relatório em PDF ou Excel, facilitando o compartilhamento dos resultados com stakeholders e ajudando na tomada de decisão.

### Vantagens da Calculadora TCO da Azure

- **Visão Geral dos Custos**: Auxilia na compreensão dos custos operacionais ocultos de uma infraestrutura on-premises que muitas vezes são difíceis de medir.
- **Planejamento e Justificação de Migração**: Suporte para justificar o investimento em nuvem com base em dados sólidos.
- **Flexibilidade e Personalização**: A ferramenta permite ajustar uma grande variedade de parâmetros, adaptando-se a diferentes tipos de infraestrutura e necessidades de negócios.

Para empresas que planejam migrar para a nuvem, a Calculadora TCO da Azure é uma ferramenta estratégica, pois oferece uma base financeira clara para tomada de decisão e planejamento de longo prazo.

### Calculadora de custos

Essa calculadora de preços é diferente da TCO e permite a configuração detalhada dos recursos, ajudando a prever os custos mensais de uso da VM.

1. Acessar a Calculadora de Preços da Azure
Acesse a Calculadora de Preços do Azure.
Você verá a interface da calculadora com várias categorias de serviços que podem ser adicionados para simulação de custo.
2. Selecionar o Serviço de Máquina Virtual
Na tela inicial, clique em "Virtual Machines" (ou "Máquinas Virtuais", se estiver em português).
Isso adicionará uma seção "Virtual Machines" no painel de cálculo abaixo, onde você poderá configurar os detalhes da VM.
3. Configurar a Máquina Virtual
Após adicionar "Virtual Machines", você verá opções de configuração. Aqui estão os principais pontos:

Região:

Selecione a região em que deseja hospedar a VM (por exemplo, "East US", "West Europe"). Os preços variam conforme a localização geográfica.
Tipo de Instância:

Escolha a série de máquinas virtuais (por exemplo, B, D, E). Cada série é otimizada para diferentes cargas de trabalho (como armazenamento, computação, e memória).
Em seguida, escolha o tamanho da VM, que determina a quantidade de CPUs, memória e desempenho.
Licenciamento do Sistema Operacional:

Escolha o sistema operacional, como Windows ou Linux. O custo pode variar dependendo do sistema escolhido.
Opções de Licenciamento:

Se você tiver licenças qualificadas, pode escolher o "Azure Hybrid Benefit" para reduzir custos ao reutilizar licenças do Windows Server ou SQL Server.
Duração do Tempo de Uso (Pricing Options):

Escolha o plano de pagamento: "Pay-as-you-go" para pagamento conforme o uso, ou planos reservados de 1 ou 3 anos para economizar em custos com um compromisso de longo prazo.
4. Configurar o Armazenamento
Discos OS e de Dados:

Escolha o tipo de disco (padrão HDD, padrão SSD, ou Premium SSD). Discos de maior desempenho, como Premium SSD, têm custo mais elevado.
Capacidade de Armazenamento:

Especifique a quantidade de armazenamento necessária para cada disco (OS disk e data disks).
5. Configurar Rede e Outras Opções
Rede:

Inclua estimativas para custos de rede se precisar de largura de banda adicional ou recursos de rede como IPs públicos.
Outras Opções (opcional):

Adicione serviços adicionais como Backup, Security Center, ou Load Balancers se planeja usá-los com a VM.
6. Revisar os Custos e Simular o Uso
Abaixo das configurações, você verá um resumo de custos mensais estimados com base nas escolhas feitas.
A Calculadora permite ajustar o tempo de uso mensal, caso a VM não funcione 24/7. Para ajustar, basta especificar o número de horas de uso mensal (opcional).
7. Exportar ou Compartilhar o Cálculo
Se desejar compartilhar a estimativa de custo, clique em "Export" para baixar em formato Excel, ou em "Save" para salvar a configuração e continuar posteriormente.
É possível também compartilhar o link da calculadora, que mantém todas as configurações.
Usando esses passos, a Calculadora de Preços da Azure ajuda você a estimar o custo da máquina virtual, considerando detalhes específicos para configurar e otimizar o orçamento de recursos em seus projetos de dados e computação.
