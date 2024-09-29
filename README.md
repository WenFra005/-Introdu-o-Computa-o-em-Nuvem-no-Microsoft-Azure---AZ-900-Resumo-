# Introdução à Computação em Nuvem no Microsoft Azure - AZ-900

Este repositório apresenta uma visão geral detalhada dos conceitos de **computação em nuvem** com foco no **Microsoft Azure**, abordando temas como **armazenamento**, **identidade e segurança**, **ferramentas de gerenciamento e implantação**, e os principais **benefícios da nuvem**. A documentação é baseada no curso **AZ-900: Introdução aos Conceitos Básicos do Microsoft Azure**, que oferece uma base sólida para iniciantes.

---

## O que é Computação em Nuvem?

A **computação em nuvem** permite que as empresas utilizem recursos de TI, como servidores, armazenamento e redes, acessíveis pela Internet. As empresas podem pagar apenas pelos recursos que utilizam, obtendo maior flexibilidade, escalabilidade e redução de custos.

### Modelos de Nuvem

1. **Nuvem Privada**: Usada exclusivamente por uma organização, com maior controle sobre os recursos, mas com maior responsabilidade de manutenção.
   
2. **Nuvem Pública**: Compartilhada entre várias organizações, com recursos gerenciados pelo provedor.
   
3. **Nuvem Híbrida**: Combina as características das nuvens privadas e públicas, oferecendo flexibilidade para adaptar a infraestrutura.

---

## Tipos de Serviços em Nuvem (IaaS, PaaS e SaaS)

1. **IaaS (Infraestrutura como Serviço)**: Proporciona o aluguel de recursos como servidores e redes, permitindo controle total sobre a infraestrutura.

   **Análise Visual**: Diagrama mostrando a configuração de uma **VM (máquina virtual)**, com controle total sobre armazenamento, sistema operacional e rede.
   
2. **PaaS (Plataforma como Serviço)**: Fornece um ambiente gerenciado para desenvolvimento e implantação de aplicativos.

   **Análise Visual**: Ilustração de **contêineres** no Azure, que são escaláveis e otimizados para desenvolvimento.
   
3. **SaaS (Software como Serviço)**: Permite o acesso a softwares diretamente pela Internet, com manutenção e atualizações feitas pelo provedor.

   **Análise Visual**: Imagem mostrando a interface de usuários acessando **SaaS** através de navegadores, com a infraestrutura gerenciada pelo provedor.

---

## Armazenamento no Azure

O **Azure** oferece uma ampla gama de serviços de armazenamento para atender a diferentes necessidades de dados.

1. **Serviços de Armazenamento**:
   - **Blob do Azure**: Otimizado para armazenar grandes volumes de dados não estruturados.
   - **Disco do Azure**: Fornece discos gerenciados para máquinas virtuais e serviços.
   - **Arquivos do Azure**: Compartilhamento de arquivos via protocolo SMB.

   **Análise Visual**: Diagrama comparando os tipos de serviços de armazenamento, como **Blob**, **Disco** e **Arquivos**.

2. **Opções de Redundância**:
   - O **Azure** oferece opções como **Locally Redundant Storage (LRS)** e **Geo-Redundant Storage (GRS)**, garantindo proteção e alta disponibilidade dos dados.

   **Análise Visual**: Ilustração mostrando os tipos de redundância e como os dados são replicados local e geograficamente.

3. **Ferramentas de Migração**:
   - **Azure Data Box**: Solução para transferência segura de grandes volumes de dados para o Azure.
   - **AzCopy**: Ferramenta de linha de comando para copiar dados de ou para o Azure.

   **Análise Visual**: Diagrama ilustrando o fluxo de migração de dados do local para o Azure, utilizando **Data Box** e **AzCopy**.

---

## Identidade, Acesso e Segurança

A gestão de identidades e acessos é crucial para manter a segurança no Azure. Aqui estão os principais serviços oferecidos:

1. **Microsoft Entra ID**: Serviço de gerenciamento de identidades e acessos baseado na nuvem.
   
   **Análise Visual**: Diagrama mostrando como o **Microsoft Entra ID** sincroniza usuários e dispositivos para acesso seguro.

2. **Autenticação Multifator (MFA)**: Adiciona uma camada extra de segurança ao exigir dois ou mais fatores para completar o login.
   
   **Análise Visual**: Ilustração dos três fatores usados na **MFA**: senha, dispositivo e biometria.

3. **Acesso Condicional e RBAC**:
   - **Acesso Condicional**: Define políticas com base em sinais como localização e tipo de dispositivo.
   - **RBAC (Controle de Acesso Baseado em Função)**: Garante que os usuários tenham apenas os acessos necessários para realizar suas tarefas.

   **Análise Visual**: Diagrama que ilustra como as permissões são atribuídas no **RBAC** com base nas funções dos usuários.

4. **Confiança Zero e Defesa em Profundidade**:
   - **Confiança Zero**: Nenhuma entidade é confiável por padrão; todos os acessos são verificados.
   - **Defesa em Profundidade**: Utiliza várias camadas de segurança para proteger os sistemas.

   **Análise Visual**: Imagem mostrando as camadas da **defesa em profundidade**, desde a segurança física até a proteção de dados.

---

## Ferramentas de Gerenciamento e Implantação

O **Microsoft Azure** oferece ferramentas robustas para gerenciar e implantar recursos de forma eficiente.

1. **Portal do Azure**: Interface gráfica para gerenciar todos os recursos e serviços.

   **Análise Visual**: Diagrama mostrando o **Portal do Azure**, com uma visão geral de como gerenciar assinaturas e recursos.

2. **Azure PowerShell e CLI do Azure**: Ferramentas de linha de comando para automação e gerenciamento.

   **Análise Visual**: Comparação entre **PowerShell** e **CLI do Azure**, mostrando suas funcionalidades.

3. **Azure Resource Manager (ARM)**: Ferramenta que gerencia e orquestra a criação, atualização e exclusão de recursos no Azure.

   **Análise Visual**: Ilustração de como o **ARM** organiza e gerencia os recursos em diferentes regiões e assinaturas.

4. **Modelos ARM**: Arquivos JSON usados para configurar e implantar infraestrutura de forma automatizada.

   **Análise Visual**: Exemplo de um **modelo ARM** mostrando como infraestrutura pode ser provisionada de forma repetível.

5. **Azure Arc**: Extende o gerenciamento de recursos do Azure para ambientes híbridos e multi-nuvem.

   **Análise Visual**: Diagrama mostrando o **Azure Arc** gerenciando recursos em diferentes ambientes.

6. **Infraestrutura como Código (IaC)**: A **Infraestrutura como Código (IaC)** permite que a infraestrutura seja definida por código, permitindo uma gestão mais ágil e automatizada.

   **Análise Visual**: Ilustração de como a **Infraestrutura como Código** permite a rápida criação de novos ambientes com configurações consistentes.

---

## Preços e Modelos de Custos no Azure

O **Microsoft Azure** oferece uma variedade de modelos de preços para ajudar as organizações a controlar seus custos de forma eficaz.

1. **CapEx vs. OpEx**:
   - **CapEx (Despesas de Capital)**: Refere-se ao investimento inicial em infraestrutura física, onde os recursos são adquiridos e mantidos pela empresa.
   - **OpEx (Despesas Operacionais)**: Refere-se ao modelo **pay-as-you-go**, onde os recursos são cobrados conforme o uso, permitindo melhor controle de custos e escalabilidade.

2. **Ferramentas de Estimativa de Custo**:
   - O Azure oferece ferramentas como a **Calculadora de Preços do Azure**, que ajuda as empresas a preverem os custos com base no uso dos serviços.

---

## Conformidade e Governança

Para garantir que os recursos estejam em conformidade com regulamentações e políticas de segurança, o Azure oferece:

1. **Azure Policy**: Ferramenta que ajuda a definir e impor políticas de conformidade nos recursos do Azure.
   
2. **Azure Blueprints**: Ferramenta que permite definir arquiteturas padronizadas para garantir que os recursos implantados sigam as melhores práticas e normas corporativas.

---

## Monitoramento e Diagnóstico

O **Azure** oferece várias ferramentas de monitoramento para garantir que os recursos estejam funcionando corretamente:

1. **Azure Monitor**: Coleta métricas e logs de seus recursos para monitorar a saúde e o desempenho de sua infraestrutura.
   
2. **Log Analytics**: Centraliza os logs e ajuda a realizar consultas e análises detalhadas.
   
3. **Application Insights**: Ferramenta para monitorar o desempenho de aplicativos.

---

## Rede Virtual e Conectividade

O Azure oferece soluções de conectividade e rede, incluindo:

1. **Azure Virtual Network (VNet)**: Permite a criação de redes privadas no Azure, com sub-redes e controle de tráfego.
   
2. **VPN Gateway**: Solução para criar conexões seguras entre redes locais e o Azure.
   
3. **Azure ExpressRoute**: Fornece uma conexão privada e dedicada ao Azure, garantindo maior confiabilidade e segurança.

---

## Benefícios da Computação em Nuvem

Os principais benefícios da computação em nuvem incluem:

1. **Alta Disponibilidade**: Garantia de disponibilidade contínua com SLAs rigorosos.
   
   **Análise Visual**: Diagrama de redundância que mostra como o Azure garante a continuidade dos serviços em diferentes regiões.

2. **Escalabilidade**: Permite ajustar os recursos conforme a demanda.
   
   **Análise Visual**: Ilustração mostrando a escalabilidade automática de **VMs** conforme o aumento da carga de trabalho.

3. **Elasticidade**: Recursos podem ser aumentados ou diminuídos automaticamente com base no uso.

4. **Segurança**: Ferramentas como **MFA** e **Defesa em Profundidade** garantem a proteção contra ameaças.

---

## Conclusão

O **Microsoft Azure** oferece um conjunto robusto de ferramentas para armazenamento, computação e segurança, além de soluções avançadas de gerenciamento e implantação. Este artigo fornece uma visão clara de como o Azure pode ser utilizado para transformar a infraestrutura de TI das empresas, permitindo escalabilidade, segurança e flexibilidade de forma eficiente.

---
## Nota

Este resumo foi elaborado com a assistência do modelo de linguagem **ChatGPT** da OpenAI.

## Referências
- Baptista, Valéria. *AZ-900: Introdução aos Conceitos Básicos do Microsoft Azure*. 
- Microsoft. *Documentação oficial do Microsoft Azure*. 
- Curso AZ-900: Introdução aos Conceitos Básicos do Microsoft Azure【4†source】【11†source】【16†source】【37†source】【38†source】【61†source】.
