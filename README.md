RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 05 de março de 2026

Empresa: Abstergo Industries

Responsável: Maurício Lima Cordeiro de Jesus
Introdução

Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Maurício Lima Cordeiro de Jesus. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos.
Descrição do Projeto

O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

Etapa 1:

    Nome da ferramenta: Amazon S3 (com S3 Intelligent-Tiering)

    Foco da ferramenta: Redução de custos de armazenamento de longo prazo.

    Descrição de caso de uso: A indústria farmacêutica gera um volume massivo de dados, como resultados de ensaios clínicos, sequenciamentos genéticos e imagens de laboratório. O S3 Intelligent-Tiering move automaticamente os dados que não são acessados com frequência (como pesquisas antigas e backups regulatórios) para camadas de armazenamento de custo mais baixo, gerando economia imediata sem impacto na performance caso os dados precisem ser recuperados para auditorias.

Etapa 2:

    Nome da ferramenta: Amazon EC2 (utilizando Instâncias Spot e Auto Scaling)

    Foco da ferramenta: Otimização de custos computacionais flexíveis.

    Descrição de caso de uso: Para o processamento de simulações farmacológicas complexas e modelagem molecular, que exigem alto poder de processamento em horários não críticos, a implementação de Instâncias Spot do EC2 permite utilizar a capacidade ociosa da AWS com descontos de até 90%. O Auto Scaling garante que os servidores liguem apenas quando há lotes de simulações na fila e desliguem assim que o trabalho for concluído, evitando o pagamento por máquinas paradas.

Etapa 3:

    Nome da ferramenta: AWS Compute Optimizer

    Foco da ferramenta: Análise inteligente de infraestrutura e rightsizing (adequação de tamanho).

    Descrição de caso de uso: A ferramenta utilizará aprendizado de máquina para analisar o histórico de utilização dos recursos atuais da Abstergo Industries. Ela identificará servidores que estão superdimensionados (pagando-se por mais CPU/memória do que o sistema realmente usa) e recomendará instâncias menores e mais baratas, cortando desperdícios da infraestrutura legada imediatamente.

Conclusão

A implementação de ferramentas na empresa Abstergo Industries tem como esperado a redução drástica de custos operacionais com TI, a otimização de recursos ociosos e a garantia de armazenamento escalável e seguro para dados sensíveis, o que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.
Anexos

    Planilha de estimativa de redução de custos (Cost Explorer Projection).

    Diagrama de arquitetura de rede (VPC) e fluxo de dados.

    Documentação técnica das políticas de ciclo de vida do Amazon S3.

    Relatório inicial de rightsizing do AWS Compute Optimizer.

Assinatura do Responsável pelo Projeto:

Maurício Lima Cordeiro de Jesus
