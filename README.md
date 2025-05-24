# Criando Infra na AWS com Terraform (IaC)

Este projeto demonstra como provisionar infraestrutura na AWS utilizando o Terraform, seguindo as práticas de Infrastructure as Code (IaC).

# 📺 Tutorial

# 🛠️ Tecnologias Utilizadas

- [Terraform](https://www.terraform.io/)
- [AWS](https://aws.amazon.com/)
- [GitHub Actions](https://docs.github.com/pt/actions)

## 📁 Estrutura do Projeto
infra-as-code/
├── .github/
│ └── workflows/
│ └── terraform.yml
├── terraform/
│ ├── main.tf
│ ├── variables.tf
│ ├── outputs.tf
│ └── provider.tf
└── README.md

## 🚀 Como Utilizar

### 1. Pré-requisitos

- Conta na AWS com as credenciais configuradas.
- [Terraform](https://www.terraform.io/downloads.html) instalado na máquina.
- [Git](https://git-scm.com/) instalado.

### 2. Clonar o repositório

-->  bash
git clone https://github.com/seu-usuario/infra-as-code.git
cd infra-as-code/terraform

### 3. Inicializar o Terraform
terraform init

### 4. Planejar a infraestrutura
terraform plan

### 5. Aplicar as mudanças
terraform apply

### 6.Configurar GitHub Actions (Opcional)
Para automatizar o processo de provisionamento utilizando GitHub Actions:

• Configure os segredos AWS_ACCESS_KEY_ID e AWS_SECRET_ACCESS_KEY no repositório.

• O workflow terraform.yml será acionado automaticamente em pushs para a branch principal.
