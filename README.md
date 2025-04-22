# 📘 PROJETO INTEGRADOR III: DESENVOLVIMENTO DE SISTEMAS ORIENTADO À OBJETOS


## 🎓 Sistema de Cadastro de um Centro Universitário
<br>

### 🧾 Descrição

Este projeto tem como objetivo o desenvolvimento de um sistema de gestão para um centro universitário, com foco na orientação a objetos e na modelagem utilizando a Linguagem de Modelagem Unificada **(UML)**.

Na **primeira fase**, realizamos:
- Elaboração do **Diagrama de Casos de Uso**, representando as principais interações dos usuários com o sistema;
- Descrição detalhada dos **cenários de uso**, incluindo fluxos principais e alternativos;
- Criação do **Diagrama de Classes**, que evidencia a estrutura estática do sistema.

Na **segunda fase**, desenvolvemos:
- Protótipos das interfaces do sistema utilizando a ferramenta **Figma**, para uma universidade fictícia chamada **PrimeTech**;
- Telas voltadas para alunos, gestores, professores e fornecedores.

<br>


# 📌 Casos de Uso
![Diagrama de Casos de Uso](Caso-de-uso.png)

<br>

## 📋 Descrição dos Cenários
<br>

#### 1. Realizar Matrícula (Pessoa Física)

**Cenário Principal**  
- **Ator:** Pessoa física (aluno ou responsável)  
- **Pré-condição:** Estar cadastrado no sistema  
- **Fluxo:** Preenchimento dos dados e confirmação da matrícula  
- **Pós-condição:** Matrícula registrada com sucesso  

**Cenários Alternativos**  
- **Cancelamento:** Matrícula cancelada antes da finalização  
- **Dados Incompletos:** Sistema solicita preenchimento obrigatório

---

#### 2. Pagar Mensalidade (Alunos)

**Cenário Principal**  
- **Ator:** Aluno  
- **Pré-condição:** Estar matriculado  
- **Fluxo:** Escolher forma de pagamento e concluir a transação  
- **Pós-condição:** Mensalidade marcada como "paga"  

**Cenários Alternativos**  
- **Desistência:** Pagamento não concluído  
- **Falha:** Erro durante o pagamento, status mantido como "pendente"

---

#### 3. Avaliar Aluno (Professores)

**Cenário Principal**  
- **Ator:** Professor  
- **Pré-condição:** Autenticado no sistema  
- **Fluxo:** Inserção de notas e comentários  
- **Pós-condição:** Avaliação registrada e visível ao aluno  

**Cenários Alternativos**  
- **Exclusão da Avaliação:** Professor remove avaliação  
- **Aluno Inexistente:** Sistema não encontra o aluno informado

---

#### 4. Realizar Contrato (Pessoa Jurídica)

**Cenário Principal**  
- **Ator:** Pessoa Jurídica  
- **Pré-condição:** Estar cadastrada no sistema  
- **Fluxo:** Fornecimento dos dados contratuais  
- **Pós-condição:** Contrato registrado  

**Cenários Alternativos**  
- **Cancelamento:** Interrupção antes da finalização  
- **Dados Incompletos:** Sistema exige preenchimento obrigatório

---

#### 5. Fornecer Materiais (Fornecedor)

**Cenário Principal**  
- **Ator:** Fornecedor  
- **Pré-condição:** Cadastro e autorização no sistema  
- **Fluxo:** Confirmação da entrega de materiais  
- **Pós-condição:** Pedido atualizado como entregue  

**Cenários Alternativos**  
- **Atraso:** Sistema notifica o responsável pelo pedido  
- **Materiais Incorretos:** Sistema registra não conformidade



<br>

# 📐 Diagrama de Classes
![Diagrama de Classes](Diagrama-de-classe.png)

<br>

# 💻 Telas do Sistema 
## 👨‍🎓 Aluno
- **Login do Aluno:** Apresenta campos para inserção de email e senha, permitindo acesso à Área do Aluno. Também inclui um botão de 'CADASTRE-SE AGORA' para novos usuários que ainda não possuem cadastro na universidade. 
![Tela Login Aluno](Tela-Login-Aluno.png)

<br>

- **Cadastro-Aluno:** Solicita os dados importantes para o cadastro no sistema.
 ![Tela Cadastro Aluno](Tela-Cadastro-Aluno.png)
 
<br>

- **Área-Aluno:** Acesso a documentos, cursos e matrícula.
![Tela Aluno](Tela-Aluno.png)

---

## 👨‍💼 Gestor
- **Login-Gestor:** Requer email e senha para autenticação, garantindo acesso restrito exclusivamente aos gestores do sistema.
![Tela Login Gestão](Tela-Login-Gestão.png)

<br>

- **Painel-Controle-Gestão:** Permite acesso aos dados cadastrais de alunos, professores, funcionários e fornecedores. Além de fornecer informações sobre contratos, relatórios e contato direto com o suporte.
 ![Tela Login Gestão](Painel-Gestor.png)
 
---

## 👨‍🏫 Professor
- **Cadastro-Professor:** Solicita dados para o Professor ser cadastrado no sistema.
![Tela Cadastro Professor](Tela-Cadastro-Professor.png)

---

## 🚚 Fornecedor
- **Cadastro-Fornecedor:** Solicita dados para o Fornecedor ser cadastrado no sistema.
![Tela Cadastro Professor](Tela-Cadastro-Fornecedor.png)

---

<br>

### 👥 Integrantes do Grupo
- Andreza Azevedo Gomes de Freitas
- Lucas Vieira Rocha

<br>

## 📜 Licença
 Este projeto é de uso acadêmico e não possui uma licença pública definida. Caso queira utilizá-lo, consulte os autores para mais informações.





