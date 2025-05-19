# resumo-tipos-de-servi-o-de-nuvem
# ☁️ Modelos de Serviço em Nuvem no Microsoft Azure

Este repositório apresenta um resumo dos três principais modelos de serviço em nuvem oferecidos pela Azure: **IaaS**, **PaaS** e **SaaS**, além de uma visão geral sobre o modelo de responsabilidade compartilhada.

---

## 🛠️ IaaS - Infrastructure as a Service (Infraestrutura como Serviço)

Com o IaaS, você aluga recursos de infraestrutura, como servidores, armazenamento e redes, pagando conforme o uso.

**Recursos típicos:**
- Máquinas virtuais
- Armazenamento em nuvem
- Firewalls e segurança de rede
- Datacenters físicos

**Características:**
- Alto nível de personalização
- Maior responsabilidade do usuário na configuração e manutenção
- Ideal para quem precisa de controle total sobre o ambiente de TI
- Exige mais gestão técnica, o que pode aumentar os custos

---

## ⚙️ PaaS - Platform as a Service (Plataforma como Serviço)

O PaaS fornece um ambiente completo para desenvolvimento e implantação de aplicações, sem se preocupar com a infraestrutura.

**Recursos típicos:**
- Sistemas operacionais
- Ferramentas de desenvolvimento
- Serviços de banco de dados
- Análise de dados e gerenciamento de aplicações

**Características:**
- Permite foco total no desenvolvimento do software
- O gerenciamento da infraestrutura é feito pelo provedor
- Exemplo: uso de banco de dados sem precisar configurar a máquina virtual

---

## 📦 SaaS - Software as a Service (Software como Serviço)

Com o SaaS, os usuários acessam aplicativos prontos via internet. Toda a infraestrutura e manutenção são responsabilidade do provedor.

**Recursos típicos:**
- Aplicações hospedadas e acessadas online
- Licenciamento por usuário ou por assinatura

**Exemplos:**
- Microsoft Teams
- Microsoft Office 365
- Serviços de e-mail e calendário

**Características:**
- Não há necessidade de instalação ou manutenção por parte do usuário
- Aplicações prontas para uso imediato

---

## 🔐 Modelo de Responsabilidade Compartilhada

A segurança e operação em ambientes de nuvem são responsabilidades compartilhadas entre o cliente e o provedor (Microsoft Azure). A divisão depende do modelo utilizado.

### 🧾 Responsabilidades sempre do cliente:
- Informações e dados pessoais
- Dispositivos (computadores, celulares, etc.)
- Contas e identidades de acesso

### 🧩 Por modelo de serviço:

**IaaS**
- Microsoft: hosts físicos, rede física, datacenter
- Cliente: sistema operacional, aplicativos, controle de rede, identidade

**PaaS**
- Microsoft: hosts físicos, rede física, datacenter, sistema operacional
- Compartilhado: infraestrutura de identidade, aplicativos, controle de rede

**SaaS**
- Microsoft: aplicativos, sistema operacional, rede, datacenter, etc.
- Compartilhado: infraestrutura de identidade e diretório

---

📌 Este material serve como apoio para entender os modelos de serviço em nuvem e as responsabilidades associadas. Sinta-se à vontade para contribuir ou sugerir melhorias!
