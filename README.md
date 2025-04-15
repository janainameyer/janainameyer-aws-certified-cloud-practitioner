# ☁️ AWS Certified Cloud Practitioner – Guia de Estudos

Este repositório contém anotações e resumos para ajudar na preparação para a certificação **AWS Certified Cloud Practitioner (CLF-C02)**.  

---

## 📚 Índice

- [1. Conceitos de Nuvem](#1-conceitos-de-nuvem)
- [2. Princípios da AWS](#2-princípios-da-aws)
- [3. Segurança e Conformidade](#3-segurança-e-conformidade)
- [4. Faturamento e Preço](#4-faturamento-e-preço)
- [5. Suporte e Documentação](#5-suporte-e-documentação)
- [6. Links úteis](#6-links-úteis)

---

## 1. Conceitos de Nuvem

🧠 1. Conceitos de Nuvem
A computação em nuvem (cloud computing) revolucionou a forma como consumimos recursos de tecnologia, oferecendo uma alternativa moderna, escalável e econômica ao modelo tradicional de TI. Ao invés de comprar, instalar e manter servidores físicos, empresas e pessoas agora podem acessar recursos de computação via internet, pagando apenas pelo que utilizam. Mas pra entender bem esse universo, vamos explorar os conceitos fundamentais da nuvem:

☁️ O que é computação em nuvem?
Computação em nuvem é a entrega de recursos de TI sob demanda — como servidores, armazenamento, bancos de dados, redes, software, análise e inteligência artificial — por meio da internet. Esses recursos são fornecidos por provedores como a AWS, Microsoft Azure, Google Cloud, entre outros.

Em vez de investir em infraestrutura própria, você pode "alugar" essa infraestrutura na nuvem, escalando conforme a necessidade e pagando por uso.

🎯 Principais benefícios da computação em nuvem
Elasticidade: é possível aumentar ou reduzir recursos rapidamente de acordo com a demanda.

Escalabilidade: permite atender desde pequenos projetos até grandes empresas globais.

Alta disponibilidade: a nuvem fornece redundância automática e serviços em múltiplas regiões para garantir que seus sistemas fiquem sempre no ar.

Agilidade: novos recursos podem ser ativados em minutos, acelerando a inovação.

Redução de custos: elimina gastos com compra e manutenção de hardware e reduz custos operacionais.

Modelo pay-as-you-go: você paga somente pelos recursos que utilizar.

🏗️ Modelos de implantação da nuvem
Nuvem Pública
Recursos são oferecidos por um provedor (como AWS) e compartilhados com outros clientes. É o modelo mais comum e econômico.

Nuvem Privada
Recursos dedicados exclusivamente para uma única organização. Pode estar localizada no data center da empresa ou ser hospedada por terceiros. Garante mais controle e segurança.

Nuvem Híbrida
Combinação de nuvem pública e privada. Ideal para empresas que querem manter parte de suas operações locais (on-premises) e aproveitar a escalabilidade da nuvem.

🛠️ Modelos de serviço em nuvem
A nuvem é oferecida em três modelos principais de serviço:

1. IaaS – Infrastructure as a Service (Infraestrutura como Serviço)
Você aluga a infraestrutura básica de TI — como servidores, redes e armazenamento.
➡️ Exemplos: Amazon EC2, Azure Virtual Machines, Google Compute Engine
💡 Ideal para administradores que precisam de controle total sobre o ambiente.

2. PaaS – Platform as a Service (Plataforma como Serviço)
Fornece um ambiente completo para desenvolvimento, com ferramentas de build, deploy e gerenciamento de aplicações.
➡️ Exemplos: AWS Elastic Beanstalk, Heroku, Google App Engine
💡 Ideal para desenvolvedores que querem focar no código sem se preocupar com a infraestrutura.

3. SaaS – Software as a Service (Software como Serviço)
Você utiliza softwares prontos diretamente pela internet.
➡️ Exemplos: Gmail, Microsoft 365, Zoom, Salesforce
💡 Ideal para usuários finais — não precisa instalar nem manter nada.

🌍 Infraestrutura Global da Nuvem
Provedores como a AWS operam em regiões geográficas (regions), cada uma contendo várias zonas de disponibilidade (AZs). Isso garante:

Menor latência (resposta mais rápida)

Redundância e tolerância a falhas

Continuidade do negócio mesmo em caso de desastres

🔒 Segurança na nuvem
Ao contrário do que muitos pensam, a nuvem pode ser mais segura que data centers tradicionais, pois os provedores investem pesadamente em segurança. O modelo de responsabilidade compartilhada da AWS, por exemplo, deixa claro o que é responsabilidade da AWS (infraestrutura física, rede, etc.) e o que é responsabilidade do cliente (configuração de segurança, controle de acesso, criptografia, etc.).

---

## 2. Princípios da AWS

- AWS é uma plataforma de nuvem amplamente adotada, oferecendo mais de 200 serviços.
- Principais regiões e zonas de disponibilidade (AZs).
- Conceito de infraestrutura global.
- Serviços principais:
  - **EC2** (máquinas virtuais)
  - **S3** (armazenamento de objetos)
  - **RDS** (banco de dados relacional)
  - **Lambda** (computação serverless)

---

## 3. Segurança e Conformidade

- Modelo de responsabilidade compartilhada.
- Conceitos de IAM (gerenciamento de identidade e acesso):
  - Usuários, grupos, permissões, políticas.
- Serviços de segurança:
  - **AWS Shield**, **WAF**, **KMS**, **CloudTrail**, **CloudWatch**.
- Conformidades e certificações da AWS (ex: ISO, SOC, GDPR).

---

## 4. Faturamento e Preço

- Modelo de **pay-as-you-go** (pague pelo uso).
- Ferramentas de gerenciamento de custos:
  - **AWS Pricing Calculator**
  - **Billing Dashboard**
  - **Cost Explorer**
- Tipos de planos:
  - Sob demanda, instâncias reservadas, spot.
- Dicas para otimizar custos:
  - Auto Scaling, desligar instâncias, escolher regiões estratégicas.

---

## 5. Suporte e Documentação

- Níveis de suporte AWS:
  - Basic, Developer, Business, Enterprise.
- Recursos de aprendizagem:
  - AWS Training, Skill Builder, Whitepapers.
- Documentação oficial e fóruns:
  - [https://docs.aws.amazon.com](https://docs.aws.amazon.com)
  - [https://repost.aws](https://repost.aws)

---

## 6. Links úteis

- [AWS Cloud Practitioner – Página oficial](https://aws.amazon.com/certification/certified-cloud-practitioner/)
- [AWS Skill Builder (Cursos Gratuitos)](https://skillbuilder.aws/)
- [AWS Whitepapers](https://aws.amazon.com/whitepapers/)
- [AWS Pricing Calculator](https://calculator.aws.amazon.com/)
