## Formação Microsoft AZ-900 Certification


  #### Repositório de estudos para a certificação AZ-900 – Microsoft Azure Fundamentals, com resumos baseados na Formação Microsoft AZ-900 Certification da DIO. 
---

<details closed>
<summary><strong> ☁️ Módulo 01 – Conceito de Nuvem</strong></summary>

## 📌 O que é Computação em Nuvem

A **computação em nuvem** é a entrega de serviços de computação — como **servidores, armazenamento, bancos de dados, redes, software, análises e inteligência** — por meio da Internet (a *nuvem*).

Em vez de comprar, instalar e manter infraestrutura física própria, o usuário **aluga recursos de um provedor de nuvem**, como o Microsoft Azure, pagando apenas pelo que utiliza.

### ✅ Principais Características e Benefícios

* **🚀 Acesso e Agilidade**
  Permite inovação rápida e provisionamento quase instantâneo de recursos por meio de um portal, semelhante a um e-commerce de serviços de TI, eliminando longos processos de compra e instalação de hardware.

* **💰 Economias de Escala**
  Provedores de nuvem operam em larga escala, reduzindo custos operacionais e repassando essa eficiência aos clientes.

* **📊 Modelo de Consumo**
  O pagamento é feito conforme o uso, ajudando a reduzir custos e permitindo que a infraestrutura acompanhe o crescimento ou a redução das necessidades do negócio.

---

## 🌐 Modelos de Implantação em Nuvem

Os **modelos de nuvem** definem como os recursos são disponibilizados, quem os controla e como são gerenciados.

---

### 🌍 Nuvem Pública

* **Propriedade e Acesso**
  Pertence ao provedor de serviços e é disponibilizada para múltiplas organizações pela Internet.

* **Infraestrutura Compartilhada (Multi-Tenant)**
  Recursos físicos são compartilhados entre clientes, mas os dados permanecem isolados e seguros.

* **Gestão Simplificada**
  O usuário não gerencia hardware físico, aproveitando alta flexibilidade, escalabilidade e ausência de investimento inicial em infraestrutura.

---

### 🏢 Nuvem Privada

* **Uso Exclusivo**
  Recursos dedicados a uma única organização.

* **Localização e Controle**
  Pode estar no datacenter local (*on-premises*) ou hospedada por terceiros, mas sempre em ambiente isolado.

* **Responsabilidade Total**
  A própria organização é responsável pela compra, manutenção e segurança, oferecendo maior controle e aderência a requisitos rigorosos de governança e compliance.

---

### 🔄 Nuvem Híbrida

* **Combinação de Ambientes**
  Integra nuvem pública e privada, permitindo compartilhamento de dados e aplicações.

* **Flexibilidade Operacional**
  Aplicações podem ser executadas no ambiente mais adequado — por exemplo, workloads escaláveis na nuvem pública e dados sensíveis no ambiente privado.

* **Cenário Comum de Uso**
  Muito utilizada em migrações graduais para a nuvem ou quando há sistemas legados que não podem ser movidos integralmente.

---

## 💼 CapEx x OpEx

A adoção da nuvem muda significativamente o **modelo financeiro de TI**, migrando de investimentos em ativos físicos para despesas baseadas em serviços.

---

### 🧱 CapEx (Despesas de Capital)

* **Investimento Inicial Elevado**
  Compra antecipada de servidores, datacenters, refrigeração e cabeamento.

* **Modelo Tradicional (On-Premises)**
  O hardware é adquirido antes do uso, com risco de ociosidade ou subutilização.

* **Tratamento Contábil**
  O custo é depreciado ao longo do tempo.

---

### 🔁 OpEx (Despesas Operacionais)

* **Pagamento Conforme o Uso**
  Não há investimento inicial em infraestrutura.

* **Modelo da Nuvem Pública**
  O pagamento é recorrente (mensal ou anual), baseado no consumo real — semelhante a contas de água ou energia.

* **Agilidade Financeira**
  Permite ajustar custos rapidamente conforme a demanda e deduzir despesas no mesmo período contábil.

---


### Benefícios da nuvem Azure

O Azure oferece uma mudança fundamental na gestão de TI, permitindo que as empresas foquem em objetivos comerciais em vez de manutenção de hardware.
*   **Modelo de Consumo e Custos (CapEx vs. OpEx):** O Azure opera sob um modelo de Despesas Operacionais (OpEx), onde não há custos iniciais de infraestrutura (CapEx). Os usuários pagam apenas pelos recursos que utilizam, permitindo melhor gerenciamento do fluxo de caixa e evitando o pagamento por infraestrutura ociosa,,.
*   **Alta Disponibilidade:** O Azure garante que os serviços permaneçam operacionais por longos períodos com tempo de inatividade mínimo, suportado por Acordos de Nível de Serviço (SLAs) que definem as metas de tempo de atividade,.
*   **Alcance Global e Latência:** Com datacenters em todo o mundo (mais do que qualquer outro provedor), o Azure permite implantar recursos próximos aos usuários finais, reduzindo a latência e melhorando a experiência do cliente,.
*   **Agilidade:** A nuvem permite provisionar e desprovisionar recursos computacionais em minutos, em vez de semanas ou meses, facilitando a inovação rápida e a resposta às mudanças do mercado,.
*   **Recuperação de Desastres:** O Azure oferece recursos nativos para backup e replicação de dados entre regiões, garantindo a continuidade dos negócios em caso de falhas catastróficas em uma região específica,.

### Escalabilidade e Elasticidade

Embora relacionados, estes conceitos referem-se a capacidades distintas de gerenciamento de capacidade no Azure.
*   **Escalabilidade:** É a capacidade de aumentar ou diminuir recursos para atender a uma carga de trabalho. Pode ser **vertical** (adicionar mais potência, como RAM ou CPU, a uma máquina existente) ou **horizontal** (adicionar mais máquinas/instâncias para dividir a carga),. Na nuvem, isso é feito sem a necessidade de comprar hardware físico novo.
*   **Elasticidade:** Refere-se à capacidade de escalar esses recursos de forma **automática ou dinâmica**. O sistema monitora a demanda (por exemplo, um pico de acesso durante a Black Friday) e adiciona ou remove recursos automaticamente. Isso garante que o cliente pague apenas pelo necessário naquele momento exato, otimizando custos e desempenho sem intervenção manual constante,,.

### Confiabilidade, Previsibilidade e Segurança

*   **Confiabilidade:** O Azure é projetado com **Tolerância a Falhas**. Se um componente falhar (como um rack de servidores), um backup assume o lugar, garantindo que o usuário muitas vezes nem perceba a falha,. O uso de **Zonas de Disponibilidade** (datacenters fisicamente separados dentro de uma região) e **Pares de Regiões** aumenta essa resiliência contra desastres maiores,.
*   **Previsibilidade:** O Azure fornece ferramentas para estimar e controlar gastos e desempenho.
    *   *Custos:* A **Calculadora de Preços** e a **Calculadora de TCO** (Custo Total de Propriedade) permitem prever gastos antes da implantação,,.
    *   *Desempenho:* Recursos como Autoescala e Balanceadores de Carga garantem que a performance permaneça consistente mesmo com variações de tráfego.
*   **Segurança:**
    *   **Responsabilidade Compartilhada:** A segurança é dividida entre a Microsoft (segurança física, host, rede física) e o cliente (dados, endpoints, contas, gestão de acesso). Quanto mais gerenciado o serviço (como SaaS), mais responsabilidade a Microsoft assume,,.
    *   **Defesa em Profundidade:** O Azure utiliza uma abordagem em camadas (física, identidade, perímetro, rede, computação, aplicação, dados) para proteger a infraestrutura. Se uma camada for violada, a próxima atua como barreira,.
    *   **Ferramentas:** O **Microsoft Defender para Nuvem** (anteriormente Central de Segurança) monitora a postura de segurança e recomenda melhorias,. O **Azure Key Vault** gerencia segredos e chaves criptográficas,.

### Governança e Gerenciabilidade

Esses tópicos cobrem como controlar, organizar e administrar o ambiente Azure.
*   **Gerenciabilidade:** O Azure oferece diversas interfaces para gerenciar recursos, atendendo a diferentes perfis de usuários:
    *   **Portal do Azure:** Interface gráfica baseada na web para gestão visual,.
    *   **Cloud Shell, PowerShell e CLI do Azure:** Ferramentas de linha de comando para automação e scripts,,.
    *   **Aplicativo Móvel:** Para monitoramento e ações rápidas via smartphone,.
    *   **ARM (Azure Resource Manager):** A camada de gerenciamento que permite implantar e organizar recursos usando modelos declarativos (templates JSON), garantindo consistência,.
*   **Governança:** Ferramentas para garantir conformidade e organização:
    *   **Azure Policy:** Cria regras para impor padrões (ex: impedir a criação de recursos em regiões caras ou sem tags obrigatórias) e avalia a conformidade dos recursos existentes,.
    *   **RBAC (Controle de Acesso Baseado em Função):** Gerencia quem tem acesso a quê, permitindo conceder apenas as permissões necessárias (ex: Leitor, Contribuidor, Proprietário),.
    *   **Bloqueios de Recursos (Locks):** Previne a exclusão ou alteração acidental de recursos críticos, com opções como *CanNotDelete* (não excluir) ou *ReadOnly* (somente leitura),.
    *   **Tags (Marcas):** Metadados aplicados aos recursos para organizar logicamente por departamento ou centro de custo, essenciais para o gerenciamento de faturamento e relatórios,.
    *   **Azure Blueprints:** Permite definir um pacote repetível de recursos e políticas para configurar rapidamente novos ambientes em conformidade com os padrões da organização,.
    *   **Azure Advisor:** Analisa a configuração e uso para recomendar melhorias em alta disponibilidade, segurança, desempenho e custo,.
</details>
