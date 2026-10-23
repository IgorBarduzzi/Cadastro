# Sistema de Cadastro & Gestão de Colaboradores

Aplicação desktop desenvolvida em Python utilizando **CustomTkinter** para a interface gráfica moderna e **SQLite** para persistência local de dados. O sistema permite cadastrar, consultar, editar e excluir informações de colaboradores e empresas, com validação de campos (CPF, CNPJ, datas) e exportação automatizada para planilhas Excel.

---

## 🚀 Funcionalidades

- 📋 **CRUD Completo:** Cadastro, listagem, edição e exclusão de funcionários e empresas.
- 🔍 **Busca Dinâmica:** Pesquisa de colaboradores em tempo real integrada à visualização em tabela (Treeview).
- 🛡️ **Validações de Entrada:**
  - Validação algorítmica de **CPF** e **CNPJ**.
  - Formatação e checagem automática de datas de admissão e nascimento.
  - Conversão automática de texto para maiúsculas e máscaras de moeda/salário.
- 📊 **Exportação para Excel:** Geração e download direto de relatórios tabulares em formato `.xlsx` via OpenPyXL.
- 🌓 **Tema Visual:** Suporte a alternância entre modo claro (*Light*) e escuro (*Dark*).
- 🗄️ **Auto-inicialização de Banco:** Criação automática das tabelas SQLite (`pessoas` e `empresas`) na primeira execução.

---

## 🛠️ Tecnologias Utilizadas

- **Linguagem:** Python 3.10+
- **Interface Gráfica:** [CustomTkinter](https://customtkinter.tomschimansky.com/) (modern UI baseada em Tkinter)
- **Banco de Dados:** SQLite3 (embutido)
- **Planilhas:** [OpenPyXL](https://openpyxl.readthedocs.io/)

---

## 📦 Instalação e Execução

### 1. Clonar o repositório
```bash
git clone https://github.com/IgorBarduzzi/Cadastro.git
cd Cadastro
```

### 2. Criar e ativar o ambiente virtual (recomendado)
```bash
# Windows
python -m venv venv
venv\Scripts\activate

# Linux / macOS
python3 -m venv venv
source venv/bin/activate
```

### 3. Instalar as dependências
```bash
pip install -r requirements.txt
```

### 4. Executar a aplicação
```bash
python Main.py
```

---

## 📄 Licença

Este projeto está sob a licença [MIT](LICENSE).
