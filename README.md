# Freelance Hours

Este projeto é uma aplicação de controle de horas trabalhadas por freelancers. Ele foi desenvolvido como parte de um curso de PHP oferecido pela Rocketseat, e tem como objetivo permitir o gerenciamento de tempo e produtividade, rastreando e calculando o número de horas trabalhadas em projetos.

## 🚀 Funcionalidades

- **Registro de Projetos:** Os usuários podem criar novos projetos e associá-los a clientes.
- **Rastreamento de Horas:** Permite a entrada e controle de horas trabalhadas em cada projeto, facilitando o acompanhamento das tarefas.
- **Cálculo de Faturamento:** Baseado nas horas registradas e no valor por hora configurado, a aplicação calcula o total a ser faturado.
- **Relatórios:** Gera relatórios detalhados para monitorar o tempo gasto em cada projeto.
- **Interface Simples e Intuitiva:** Uma interface amigável para fácil utilização, tanto para freelancers quanto para gestores.

## 🛠️ Tecnologias

- **PHP:** Linguagem principal do projeto.
- **Laravel:** Framework PHP usado para criar a estrutura backend.
- **SQLITE:**
- **Blade:** Motor de templates do Laravel para renderização de páginas.
- **HTML/CSS:** Estruturação e estilização do front-end.

## 📦 Instalação

Siga os passos abaixo para rodar o projeto localmente:

1. **Clone o repositório:**

   ```bash  git clone https://github.com/iuriramos93/freelancer-hours.git

```bash
composer install

cp .env.example .env
php artisan migrate
php artisan serve
