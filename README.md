# 🏢 Sistema de Portaria — Kamury Tech

Software desktop para **controle de portaria de condomínios**: cadastro de moradores, visitantes e prestadores, registro de entradas e saídas, gestão de encomendas e painel em tempo real, tudo em uma interface moderna e escura, pensada para o dia a dia do porteiro.

> 📌 Este repositório é uma **vitrine**: reúne apenas telas e a apresentação do sistema. O código-fonte não é público.
>
> 🧪 Todas as telas foram capturadas em um ambiente de demonstração, com **dados fictícios**. Nenhum nome, documento ou telefone real aparece nas imagens.

---

## 🚀 Principais funcionalidades

- 📊 **Painel em tempo real** com moradores, acessos ativos, entradas do dia e alerta de permanência prolongada
- 🕐 **Registro de entrada e saída** de prestadores, com veículo/placa e operador responsável
- 👤 **Cadastro de moradores** com apartamento, vagas, telefone e tipo (proprietário, inquilino…)
- 🚶 **Cadastro de visitantes** e 🛠️ **prestadores de serviço**, com detecção de documentos duplicados
- 📦 **Gestão de encomendas** com baixa na retirada e comprovante de entrega
- 🔎 **Busca rápida** em moradores, visitantes e prestadores ao mesmo tempo
- 📈 **Histórico de acessos** com filtros e exportação para Excel
- 🔐 **Login com senha criptografada**, perfis de administrador e operador, bloqueio após tentativas erradas e troca de turno sem fechar o sistema
- 💾 **Backup automático** ao fechar, backup manual, cópia para pendrive/HD externo e restauração
- 📥 **Importação de planilhas** Excel com cadastros já existentes

---

## 🖼️ Telas do sistema

### Acesso e painel

| Login do operador | Painel de controle |
|---|---|
| ![Tela de login](imagens/01-login.png) | ![Painel de controle da portaria](imagens/02-painel.png) |

### Controle de acessos

| Registrar entrada | Acessos ativos |
|---|---|
| ![Registro de entrada de prestador](imagens/03-registro-entrada.png) | ![Acessos ativos no momento](imagens/04-acessos-ativos.png) |

![Histórico de acessos com filtros e exportação](imagens/05-historico-acessos.png)

### Cadastros

| Moradores | Novo morador |
|---|---|
| ![Lista de moradores](imagens/06-moradores.png) | ![Cadastro de morador](imagens/07-cadastro-morador.png) |

| Visitantes | Prestadores |
|---|---|
| ![Lista de visitantes](imagens/08-visitantes.png) | ![Lista de prestadores](imagens/09-prestadores.png) |

### Encomendas

| Gestão de encomendas | Nova encomenda |
|---|---|
| ![Gestão de encomendas](imagens/10-encomendas.png) | ![Registro de nova encomenda](imagens/11-nova-encomenda.png) |

### Busca, administração e segurança dos dados

| Busca rápida | Operadores |
|---|---|
| ![Busca global](imagens/12-busca-global.png) | ![Gerenciar operadores](imagens/13-operadores.png) |

| Configurações do cliente | Backup e exportação |
|---|---|
| ![Configurações do cliente](imagens/14-configuracoes.png) | ![Backup e exportação](imagens/15-backup-exportacao.png) |

---

## 💻 Requisitos

- Windows 10 ou 11
- Instalador próprio: não precisa instalar Python nem banco de dados
- Funciona offline; os dados ficam no próprio computador da portaria

## 🛠️ Tecnologias

Python · Tkinter · SQLite

---

## 📞 Contato

Quer o sistema no seu condomínio ou uma demonstração? Fale com a **Kamury Tech**:

- ✉️ **E-mail:** [kamurytech@gmail.com](mailto:kamurytech@gmail.com)
- 📱 **Celular / WhatsApp:** [(41) 99118-6858](https://wa.me/5541991186858?text=Ol%C3%A1%2C%20vi%20o%20Sistema%20de%20Portaria%20no%20GitHub%20e%20quero%20saber%20mais.)

---

## 📄 Licença

Software proprietário da **Kamury Tech**. O sistema é distribuído com período de avaliação e ativação por chave de licença. Todos os direitos reservados.
