# 📚 Trabalho Final - Testes de Sistemas

## Sistema BiblioTech - Gerenciamento de Biblioteca

**Disciplina:** Testes de Sistemas  
**Período:** 2025.2  
**Tipo:** Em grupo (mesmo grupo do TCC)  
**Data de Entrega:** 07/11/2025  
**Valor:** 100 pontos

---

## 📋 Sumário

1. [Apresentação](#1-apresentação)
2. [Descrição do Sistema](#2-descrição-do-sistema)
3. [Objetivos do Trabalho](#3-objetivos-do-trabalho)
4. [O que Vocês Devem Fazer](#4-o-que-vocês-devem-fazer)
5. [Estrutura Obrigatória do Relatório](#5-estrutura-obrigatória-do-relatório)
6. [Entregáveis](#6-entregáveis)
7. [Critérios de Avaliação](#7-critérios-de-avaliação)
8. [Perguntas Frequentes (FAQ)](#8-perguntas-frequentes-faq)

---

## 1. Apresentação

Bem-vindos ao **Trabalho Final da disciplina de Testes de Sistemas**!

Neste trabalho, vocês atuarão como **Analistas de Teste** responsáveis por validar a qualidade de um sistema real antes de sua implantação em produção. O sistema escolhido é o **BiblioTech**, uma aplicação web completa para gerenciamento de bibliotecas.

### 1.1 Contexto do Trabalho

Vocês foram contratados por uma empresa de software que desenvolveu o sistema BiblioTech. O sistema já está implementado e aparentemente funcionando, porém, como sabemos, todo software precisa ser **rigorosamente testado** antes de ser liberado para uso.

**⚠️ ATENÇÃO IMPORTANTE:**  
O sistema contém **bugs propositais** que simulam defeitos reais que podem ocorrer no desenvolvimento. Parte da avaliação de vocês será **identificar e documentar esses bugs** através dos testes automatizados.

### 1.2 O que Este Trabalho Representa

Este trabalho simula um cenário real de QA (Quality Assurance) onde vocês precisarão:

✅ Analisar documentação técnica completa  
✅ Planejar estratégias de teste  
✅ Implementar testes automatizados (unitários e de interface)  
✅ Executar e documentar resultados  
✅ Identificar e reportar bugs  
✅ Produzir relatório profissional de testes  

### 1.3 Modalidade e Prazo

- **Modalidade:** Em grupo (mesmo grupo do TCC)
- **Data de Entrega:** 07/11/2025
- **Forma de Entrega:** Via repositório GitHub + Relatório em PDF ou Projeto completo com Relatório em PDF em uma pasta .zip

**Penalidades por atraso:**
- 1 dia: -10 pontos
- 2 dias: -20 pontos
- 3+ dias: Trabalho não será aceito

---

## 2. Descrição do Sistema

### 2.1 O que é o BiblioTech?

O **BiblioTech** é um sistema web desenvolvido em **Spring Boot + Thymeleaf** para gerenciar operações de uma biblioteca escolar/universitária. O sistema permite cadastrar livros, gerenciar usuários (alunos, professores e funcionários), controlar empréstimos e devoluções, além de calcular multas por atraso automaticamente.

**Funcionalidades principais:**
- 📖 **Gestão de Livros:** Cadastro, edição, busca e exclusão
- 👥 **Gestão de Usuários:** Cadastro de alunos, professores e funcionários
- 🔄 **Controle de Empréstimos:** Registro de empréstimos e devoluções
- 💰 **Cálculo de Multas:** R$ 2,00 por dia de atraso (calculado automaticamente)
- 📊 **Dashboard:** Estatísticas e relatórios visuais


### 2.2 Documentação Completa

📖 **Para conhecer TODOS os detalhes do sistema, acessem a documentação completa na Wiki:**

👉 **[BiblioTech - Documentação de Modelagem do Sistema](https://github.com/NirtonAfonso/Trabalho-Final-Testes-de-Sistemas/wiki/BiblioTech-%E2%80%90-Documenta%C3%A7%C3%A3o-de-Modelagem-do-Sistema)**

A documentação contém:
- ✅ Requisitos Funcionais (RF) detalhados
- ✅ Requisitos Não-Funcionais (RNF)
- ✅ Regras de Negócio (RN)
- ✅ Casos de Uso completos
- ✅ Diagramas UML (Arquitetura, DER, Fluxos)
- ✅ Modelo de dados
- ✅ Descrição das tecnologias

**Vocês DEVEM estudar essa documentação antes de começar os testes!**

### 2.3 Código-Fonte do Sistema

📁 **O código-fonte completo está disponível em:**

👉 **[Repositório do Projeto BiblioTech](https://github.com/NirtonAfonso/Trabalho-Final-Testes-de-Sistemas/tree/main/bibliotech)**

O código está organizado, documentado e pronto para ser clonado e testado.

### 2.4 JavaDoc do Sistema

📁 **O arquivo do JavaDoc completo está disponível em:**

👉 **[JavaDoc]([https://github.com/NirtonAfonso/Trabalho-Final-Testes-de-Sistemas/tree/main/bibliotech](https://github.com/NirtonAfonso/Trabalho-Final-Testes-de-Sistemas/tree/main/bibliotech/doc))**

Para abrir a documentação, execute o arquivo `index.html` que está dentro da pasta `doc`.

---

## 3. Objetivos do Trabalho

### 3.1 Objetivo Geral

Desenvolver competências práticas em **planejamento, implementação e documentação de testes automatizados de software** utilizando **JUnit 5** e **Selenium WebDriver**.

### 3.2 Objetivos Específicos

Ao final deste trabalho, vocês deverão ser capazes de:

1. ✅ **Planejar** uma estratégia de testes baseada em requisitos e regras de negócio
2. ✅ **Implementar** testes unitários com JUnit 5 para validar lógica de negócio
3. ✅ **Implementar** testes de interface com Selenium para validar fluxos completos
4. ✅ **Identificar** bugs e defeitos através da execução dos testes
5. ✅ **Documentar** resultados de forma clara e profissional
6. ✅ **Produzir** relatório técnico de testes seguindo padrões da indústria

---

## 4. O que Vocês Devem Fazer

### 📅 **Fase 1: Análise e Planejamento**

#### 4.1.1 Estudar o Sistema

**O que fazer:**
1. Acessem a [documentação completa do sistema na Wiki](https://github.com/NirtonAfonso/Trabalho-Final-Testes-de-Sistemas/wiki/BiblioTech-%E2%80%90-Documenta%C3%A7%C3%A3o-de-Modelagem-do-Sistema)
2. Leiam TODOS os requisitos funcionais (RF-01 a RF-15)
3. Estudem as regras de negócio (RN-01 a RN-12)
4. Analisem os casos de uso (UC-01 a UC-10)
5. Entendam o diagrama de entidade-relacionamento (DER)

**Dica:** Façam anotações dos requisitos mais importantes. Criem um checklist do que precisa ser testado.

#### 4.1.2 Executar e Explorar o Sistema

**O que fazer:**
1. Clonem o [repositório do projeto](https://github.com/NirtonAfonso/Trabalho-Final-Testes-de-Sistemas/tree/main/bibliotech)
2. Importem o projeto no Eclipse
3. Executem a aplicação (`mvn spring-boot:run`)
4. Acessem http://localhost:8080
5. Façam login com: `admin@bibliotech.com` / `admin123`
6. **Explorem TODAS as funcionalidades manualmente:**
   - Cadastrem livros
   - Cadastrem usuários
   - Realizem empréstimos
   - Registrem devoluções
   - Testem as buscas
   - Visualizem o dashboard

**Dica:** Anotem tudo que observarem. Identifiquem quais funcionalidades são mais críticas.

#### 4.1.3 Elaborar o Plano de Testes

**O que fazer:**

Criem um documento (pode ser em Excel, Google Sheets ou Markdown) contendo:

**A) Lista de Casos de Teste Unitários (mínimo 15)**

Exemplo de estrutura:

| ID | Descrição do Teste | Classe Testada | Método Testado | Requisito/RN |
|----|-------------------|----------------|----------------|--------------|
| TU-001 | Deve calcular multa de R$ 10,00 para 5 dias de atraso | EmprestimoService | calcularMulta() | RN-03 |
| TU-002 | Deve impedir cadastro de livro com ISBN duplicado | LivroService | salvar() | RN-02 |
| TU-003 | Deve validar formato de CPF corretamente | UsuarioService | validarCPF() | RN-07 |

**B) Lista de Casos de Teste Selenium (mínimo 10)**

Exemplo de estrutura:

| ID | Descrição do Teste | Fluxo a Testar | Requisito |
|----|-------------------|----------------|-----------|
| TS-001 | Deve realizar login com credenciais válidas | Login → Dashboard | RF-15 |
| TS-002 | Deve exibir erro ao tentar login com senha incorreta | Login com senha errada | RF-15 |
| TS-003 | Deve cadastrar novo livro com sucesso | Livros → Novo → Preencher → Salvar | RF-01 |

**C) Matriz de Rastreabilidade**

Relacionem cada requisito funcional com pelo menos um caso de teste:

| Requisito | Casos de Teste |
|-----------|----------------|
| RF-01 | TU-002, TS-003, TS-004 |
| RF-02 | TU-005, TS-006 |
| ... | ... |

**Dica:** Quanto melhor o planejamento, mais fácil será a implementação!

---

### ⚙️ **Fase 2: Implementação dos Testes**

#### 4.2.1 Testes Unitários com JUnit 5

**O que fazer:**

Criem testes unitários para validar a **lógica de negócio** das classes de serviço.

**Estrutura de pastas:**
```
src/test/java/com/bibliotech/unit/
├── LivroServiceTest.java
├── UsuarioServiceTest.java
├── EmprestimoServiceTest.java
└── DashboardServiceTest.java
```

**Requisitos mínimos:**
- ✅ **Mínimo 15 testes unitários**
- ✅ Testar métodos das classes `Service`
- ✅ Incluir testes de **sucesso** (casos válidos)
- ✅ Incluir testes de **falha** (casos inválidos)
- ✅ Usar **assertions** corretas (assertEquals, assertNotNull, assertTrue, etc.)
- ✅ Nomear testes de forma descritiva

**Exemplos do que testar:**

**Exemplo 1 - EmprestimoService:**
```java
@Test
@DisplayName("Deve calcular multa de R$ 10,00 para 5 dias de atraso")
void deveCalcularMultaCorretamente() {
    // Arrange: Preparar dados
    Emprestimo emprestimo = new Emprestimo();
    emprestimo.setDataDevolucaoPrevista(LocalDate.now().minusDays(5));
    emprestimo.setDataDevolucaoReal(LocalDate.now());
    
    // Act: Executar método
    double multa = emprestimoService.calcularMulta(emprestimo);
    
    // Assert: Verificar resultado
    assertEquals(10.0, multa, 0.01, 
        "Multa deveria ser R$ 2,00 x 5 dias = R$ 10,00");
}
```

**Exemplo 2 - UsuarioService:**
```java
@Test
@DisplayName("Deve validar CPF no formato correto")
void deveValidarCPFCorreto() {
    // Act
    boolean resultado = usuarioService.validarCPF("123.456.789-00");
    
    // Assert
    assertTrue(resultado, "CPF no formato válido deveria ser aceito");
}
```

**Exemplo 3 - LivroService:**
```java
@Test
@DisplayName("Deve lançar exceção ao cadastrar ISBN duplicado")
void deveLancarExcecaoISBNDuplicado() {
    // Arrange
    Livro livro1 = new Livro("Clean Code", "Robert Martin", 
        "978-0132350884", "Prentice Hall", 2008, 3);
    livroService.salvar(livro1);
    
    Livro livro2 = new Livro("Outro Livro", "Outro Autor", 
        "978-0132350884", "Editora", 2020, 2); // mesmo ISBN
    
    // Act & Assert
    assertThrows(RuntimeException.class, 
        () -> livroService.salvar(livro2),
        "Deveria lançar exceção ao tentar salvar ISBN duplicado");
}
```

**O que NÃO fazer:**
- ❌ Não testem apenas o "caminho feliz" (quando tudo dá certo)
- ❌ Não criem testes sem assertions
- ❌ Não copiem e colem código sem entender

---

#### 4.2.2 Testes de Interface com Selenium

**O que fazer:**

Criem testes end-to-end que simulam a interação de um usuário real com o sistema.

**Estrutura de pastas:**
```
src/test/java/com/bibliotech/selenium/
├── LoginSeleniumTest.java
├── LivroSeleniumTest.java
├── UsuarioSeleniumTest.java
└── EmprestimoSeleniumTest.java
```

**Requisitos mínimos:**
- ✅ **Mínimo 10 testes Selenium**
- ✅ Testar **fluxos completos** (do início ao fim)
- ✅ Validar elementos da interface (botões, mensagens, redirecionamentos)
- ✅ Capturar **screenshots** automaticamente em caso de falha
- ✅ Testar navegação entre páginas

**Exemplos do que testar:**

**Exemplo 1 - Teste de Login:**
```java
@Test
@DisplayName("Deve fazer login com credenciais válidas e redirecionar para dashboard")
void deveFazerLoginComSucesso() {
    // Navegar para página de login
    driver.get("http://localhost:8080/login");
    
    // Preencher campos
    driver.findElement(By.id("email")).sendKeys("admin@bibliotech.com");
    driver.findElement(By.id("senha")).sendKeys("admin123");
    
    // Clicar no botão
    driver.findElement(By.id("btn-login")).click();
    
    // Validar redirecionamento
    String urlAtual = driver.getCurrentUrl();
    assertTrue(urlAtual.contains("/dashboard"), 
        "Após login válido, deveria redirecionar para /dashboard");
    
    // Validar mensagem de boas-vindas
    WebElement mensagem = driver.findElement(By.id("mensagem-bemvindo"));
    assertTrue(mensagem.isDisplayed(), 
        "Mensagem de boas-vindas deveria estar visível");
}
```

**Exemplo 2 - Teste de Cadastro de Livro:**
```java
@Test
@DisplayName("Deve cadastrar novo livro com sucesso")
void deveCadastrarNovoLivro() {
    // Login primeiro
    fazerLogin();
    
    // Navegar para cadastro
    driver.get("http://localhost:8080/livros/novo");
    
    // Preencher formulário
    driver.findElement(By.id("titulo")).sendKeys("Test Driven Development");
    driver.findElement(By.id("autor")).sendKeys("Kent Beck");
    driver.findElement(By.id("isbn")).sendKeys("978-0321146533");
    driver.findElement(By.id("editora")).sendKeys("Addison-Wesley");
    driver.findElement(By.id("ano")).sendKeys("2003");
    driver.findElement(By.id("quantidadeExemplares")).sendKeys("5");
    
    // Salvar
    driver.findElement(By.cssSelector("button[type='submit']")).click();
    
    // Validar mensagem de sucesso
    WebElement mensagemSucesso = driver.findElement(By.className("alert-success"));
    assertTrue(mensagemSucesso.isDisplayed(), 
        "Mensagem de sucesso deveria aparecer");
    assertTrue(mensagemSucesso.getText().contains("sucesso"), 
        "Mensagem deveria conter a palavra 'sucesso'");
}
```

**Exemplo 3 - Teste de Erro:**
```java
@Test
@DisplayName("Deve exibir erro ao tentar cadastrar livro com ISBN duplicado")
void deveExibirErroISBNDuplicado() {
    fazerLogin();
    
    // Cadastrar primeiro livro
    cadastrarLivro("Clean Code", "Robert Martin", "978-0132350884");
    
    // Tentar cadastrar outro com mesmo ISBN
    driver.get("http://localhost:8080/livros/novo");
    driver.findElement(By.id("titulo")).sendKeys("Outro Livro");
    driver.findElement(By.id("autor")).sendKeys("Outro Autor");
    driver.findElement(By.id("isbn")).sendKeys("978-0132350884"); // ISBN duplicado!
    driver.findElement(By.id("ano")).sendKeys("2020");
    driver.findElement(By.id("quantidadeExemplares")).sendKeys("2");
    driver.findElement(By.cssSelector("button[type='submit']")).click();
    
    // Validar mensagem de erro
    WebElement mensagemErro = driver.findElement(By.className("alert-danger"));
    assertTrue(mensagemErro.isDisplayed(), 
        "Mensagem de erro deveria aparecer");
    assertTrue(mensagemErro.getText().contains("ISBN já cadastrado"), 
        "Mensagem deveria informar que ISBN já existe");
}
```

**Dicas importantes:**
- ✅ Sempre inicializem e fechem o WebDriver corretamente (`@BeforeEach` e `@AfterEach`)
- ✅ Usem esperas explícitas quando necessário (evitem Thread.sleep())
- ✅ Capturem screenshots em falhas para evidências
- ✅ Criem métodos auxiliares para ações comuns (fazerLogin, cadastrarLivro, etc.)

---

### 📸 **Fase 3: Execução e Coleta de Evidências**

#### 4.3.1 Executar Todos os Testes

**O que fazer:**

1. Executem a suíte completa de testes:
   ```bash
   mvn clean test
   ```

2. Anotem os resultados:
   - Quantos testes **passaram** (✅)
   - Quantos testes **falharam** (❌)
   - **Por que** falharam (analisem a mensagem de erro)

3. Para cada teste que falhou, investiguem:
   - É um bug no código do sistema? (**provável**)
   - É um erro no meu teste? (revisar código do teste)
   - É uma falha intermitente? (executar novamente)

#### 4.3.2 Capturar Evidências

**O que capturar:**

**Para testes unitários:**
- ✅ Screenshot do console com resultado dos testes
- ✅ Relatório HTML gerado pelo Maven (em `target/site/surefire-report.html`)

**Para testes Selenium:**
- ✅ Screenshot automático de cada falha (configurar no código)
- ✅ Descrição do que deveria acontecer vs. o que aconteceu
- ✅ Mensagem de erro do navegador (se houver)

**Dica:** Organizem as evidências em uma pasta:
```
evidencias/
├── screenshots/
│   ├── bug-001-isbn-duplicado.png
│   ├── bug-002-multa-incorreta.png
│   └── bug-003-login-falha.png
└── relatorios/
    └── surefire-report.html
```

#### 4.3.3 Documentar Bugs Encontrados

Para cada bug identificado, criem um registro:

**Modelo de registro de bug:**

```
BUG-001: Sistema permite cadastro de livros com ISBN duplicado

Severidade: ALTA
Módulo: Gerenciamento de Livros
Requisito violado: RN-02 (ISBN Único)
Caso de teste que falhou: TS-005

Descrição:
Ao tentar cadastrar um livro com um ISBN já existente no sistema, 
esperava-se que uma mensagem de erro fosse exibida e o cadastro 
impedido. No entanto, o sistema permite o cadastro, resultando 
em dois livros com o mesmo ISBN.

Passos para reproduzir:
1. Acessar /livros/novo
2. Cadastrar livro com ISBN "978-0132350884"
3. Acessar /livros/novo novamente
4. Cadastrar outro livro com o mesmo ISBN "978-0132350884"
5. Sistema permite cadastro (ERRO!)

Resultado esperado: 
Mensagem "ISBN já cadastrado!" e impedimento do cadastro

Resultado obtido:
Mensagem "Livro cadastrado com sucesso!" e livro duplicado salvo

Evidência: Ver screenshot bug-001-isbn-duplicado.png

```

**Quantos bugs devem encontrar?**
- Mínimo esperado: **5 bugs**
- Quanto mais bugs documentados, maior a nota!

---

### 📝 **Fase 4: Elaboração do Relatório**

Agora vocês criarão o **Relatório de Testes**, que é o documento oficial que será entregue ao cliente (professor).

**Formato:** PDF  
**Estrutura:** Ver seção 5 deste README

---

## 5. Estrutura Obrigatória do Relatório

O relatório deve seguir **exatamente** esta estrutura:

### 📄 **5.1 Capa**

Deve conter:
- Nome da Instituição
- Nome da Disciplina: **Testes de Sistemas**
- Título: **Trabalho Final - Relatório de Testes do Sistema BiblioTech**
- Nome completo de todos os integrantes do grupo
- Data de entrega

---

### 📄 **5.2 Sumário**

Lista de todas as seções com numeração de páginas.

---

### 📄 **5.3 Introdução**

**O que escrever:**

- Contexto do trabalho
- Objetivo do relatório
- Descrição breve do sistema testado (2-3 parágrafos)
- Ambiente de teste utilizado (SO, Java, navegador, ferramentas)

**Exemplo de conteúdo:**

> "Este relatório apresenta os resultados da execução de testes automatizados 
> realizados no sistema BiblioTech, uma aplicação web para gerenciamento de 
> bibliotecas desenvolvida em Spring Boot. O objetivo foi validar os requisitos 
> funcionais e não-funcionais através de testes unitários (JUnit 5) e testes de 
> interface (Selenium WebDriver).
>
> O ambiente de teste consistiu em: Windows 11, Java 17, Google Chrome 120, 
> Eclipse IDE 2024, Maven 3.9. Os testes foram executados em 15/11/2025."

---

### 📄 **5.4 Escopo dos Testes**

**O que escrever:**

- Quais módulos/funcionalidades foram testados
- Quais NÃO foram testados (se houver)
- Justificativa do escopo escolhido

**Exemplo:**

> **Módulos Testados:**
> - Gerenciamento de Livros (cadastro, edição, busca, exclusão)
> - Gerenciamento de Usuários (cadastro, autenticação)
> - Gerenciamento de Empréstimos (registro, devolução, cálculo de multa)
> - Dashboard (visualização de estatísticas)
>
> **Módulos NÃO Testados:**
> - Console H2 (ferramenta de debug, não é funcionalidade do usuário)
>
> **Justificativa:**
> O escopo cobriu todas as funcionalidades principais do sistema voltadas 
> ao usuário final, priorizando fluxos críticos de negócio.

---

### 📄 **5.5 Metodologia de Teste**

**O que escrever:**

- Abordagem utilizada (caixa-branca para unitários, caixa-preta para Selenium)
- Estratégia de testes unitários (o que foi testado e por quê)
- Estratégia de testes de interface (quais fluxos foram testados)
- Ferramentas utilizadas e suas versões

**Exemplo:**

> **Testes Unitários (Caixa-Branca):**
> Foram implementados 18 testes unitários focados nas classes de serviço 
> (LivroService, UsuarioService, EmprestimoService e DashboardService). 
> A estratégia consistiu em testar todos os métodos públicos dessas classes, 
> incluindo casos de sucesso e falha, com ênfase em regras de negócio críticas 
> como cálculo de multa (RN-03) e validações (RN-02, RN-07).
>
> **Testes de Interface (Caixa-Preta):**
> Foram implementados 12 testes Selenium cobrindo fluxos completos do sistema. 
> A estratégia priorizou fluxos críticos (login, cadastros, empréstimos) e 
> validação de mensagens de erro. Todos os testes foram executados no navegador 
> Chrome em modo headless.

---

### 📄 **5.6 Casos de Teste Planejados e Resultados**

**⚠️ Esta é a SEÇÃO MAIS IMPORTANTE do relatório!**

#### 5.6.1 Matriz de Rastreabilidade

Criem uma tabela relacionando requisitos e casos de teste:

| Requisito | Descrição | Casos de Teste | Status |
|-----------|-----------|----------------|--------|
| RF-01 | Cadastro de livros | TU-002, TS-003, TS-005 | 2/3 passaram |
| RF-02 | Cadastro de usuários | TU-005, TS-006 | 2/2 passaram |
| RF-10 | Realizar empréstimo | TU-008, TS-009 | 1/2 passou |
| RN-02 | ISBN único | TU-002, TS-005 | 0/2 passaram (BUG!) |
| RN-03 | Multa R$ 2,00/dia | TU-009 | 0/1 passou (BUG!) |

#### 5.6.2 Tabela Completa de Casos de Teste

Para CADA teste implementado, criem uma linha nesta tabela:

| ID | Tipo | Descrição | Requisito | Resultado Esperado | Resultado Obtido | Status | Evidência |
|----|------|-----------|-----------|-------------------|------------------|--------|-----------|
| TU-001 | Unitário | Validar formato de CPF correto | RN-07 | retorna true | retorna true | ✅ PASSOU | - |
| TU-002 | Unitário | Impedir ISBN duplicado | RN-02 | lança exceção | não lança exceção | ❌ FALHOU | BUG-001 |
| TS-001 | Selenium | Login com credenciais válidas | RF-15 | redireciona /dashboard | redireciona corretamente | ✅ PASSOU | - |
| TS-005 | Selenium | Cadastrar livro ISBN duplicado | RF-01, RN-02 | exibe erro | permite cadastro | ❌ FALHOU | Fig. 1 |
| ... | ... | ... | ... | ... | ... | ... | ... |

**Totalize os resultados:**
- Total de testes: XX
- Testes que passaram: XX (XX%)
- Testes que falharam: XX (XX%)

**Exemplo de totalização:**

> Dos 30 testes implementados (18 unitários + 12 Selenium), 23 passaram (76,7%) 
> e 7 falharam (23,3%). As falhas indicam 7 bugs distintos no sistema.

---

### 📄 **5.7 Evidências de Falhas**

Para CADA teste que falhou, incluam:

**Estrutura por bug:**

```
Figura X - [Título descritivo do bug]

[SCREENSHOT AQUI]

Legenda: Descrição do que deveria acontecer vs. o que aconteceu

Caso de teste: TS-XXX
Severidade: [Crítica/Alta/Média/Baixa]
Requisito violado: [RF-XX ou RN-XX]
```

**Exemplo real:**

```
Figura 1 - Sistema permite cadastro de ISBN duplicado (Bug-001)

[Screenshot mostrando mensagem "Livro cadastrado com sucesso!" 
 quando deveria mostrar erro]

Legenda: Ao tentar cadastrar um livro com ISBN já existente no sistema 
(978-0132350884), esperava-se que uma mensagem de erro "ISBN já cadastrado!" 
fosse exibida e o cadastro impedido. No entanto, o sistema permitiu o cadastro, 
resultando em dois livros com o mesmo ISBN no banco de dados.

Caso de teste: TS-005
Severidade: ALTA
Requisito violado: RN-02 (ISBN único)
```

**IMPORTANTE:** Um screenshot por bug! Não incluam screenshots de testes que passaram.

---

### 📄 **5.8 Resumo de Resultados**

#### 5.8.1 Gráficos

Incluam gráficos visuais:

**Gráfico 1: Taxa de Sucesso vs. Falha**
```
[ Gráfico de pizza ou barras mostrando % de aprovação ]
Exemplo: 76,7% aprovados / 23,3% reprovados
```

**Gráfico 2: Bugs por Severidade**
```
Crítica: 2 bugs
Alta: 3 bugs
Média: 2 bugs
Baixa: 0 bugs
```

#### 5.8.2 Tabelas Resumo

**Tabela 1: Resumo Geral**

| Métrica | Valor |
|---------|-------|
| Total de Testes Implementados | 30 |
| Testes Unitários | 18 |
| Testes Selenium | 12 |
| Testes Aprovados | 23 (76,7%) |
| Testes Reprovados | 7 (23,3%) |
| Bugs Identificados | 7 |
| Requisitos Testados | 15 de 15 (100%) |
| Regras de Negócio Testadas | 10 de 12 (83%) |

**Tabela 2: Bugs por Módulo**

| Módulo | Bugs Encontrados |
|--------|------------------|
| Gerenciamento de Livros | 3 |
| Gerenciamento de Usuários | 1 |
| Gerenciamento de Empréstimos | 3 |
| Dashboard | 0 |

---

### 📄 **5.9 Análise de Bugs Encontrados**

Para CADA BUG identificado, criem um registro completo:

**Modelo obrigatório:**

```
═══════════════════════════════════════════════════════════════
BUG-XXX: [Título descritivo do bug]
═══════════════════════════════════════════════════════════════

Severidade: [Crítica/Alta/Média/Baixa]
Módulo: [Nome do módulo]
Requisito violado: [RF-XX ou RN-XX]
Caso de teste que falhou: [TU-XX ou TS-XX]

DESCRIÇÃO:
[Explicação clara e detalhada do problema encontrado]

PASSOS PARA REPRODUZIR:
1. [Passo 1]
2. [Passo 2]
3. [Passo 3]
...

RESULTADO ESPERADO:
[O que deveria acontecer conforme a documentação]

RESULTADO OBTIDO:
[O que realmente aconteceu]

IMPACTO:
[Qual o impacto deste bug no sistema e nos usuários]

EVIDÊNCIA:
Ver Figura X - [nome do screenshot]

═══════════════════════════════════════════════════════════════
```

**Exemplo completo:**

```
═══════════════════════════════════════════════════════════════
BUG-001: Sistema permite cadastro de livros com ISBN duplicado
═══════════════════════════════════════════════════════════════

Severidade: ALTA
Módulo: Gerenciamento de Livros
Requisito violado: RN-02 (ISBN Único)
Caso de teste que falhou: TS-005

DESCRIÇÃO:
O sistema não valida se o ISBN informado já existe no banco de dados 
antes de salvar um novo livro. Isso permite que dois ou mais livros 
sejam cadastrados com o mesmo ISBN, violando a regra de negócio RN-02 
que estabelece que o ISBN deve ser único no sistema.

PASSOS PARA REPRODUZIR:
1. Fazer login no sistema (admin@bibliotech.com / admin123)
2. Acessar menu "Livros" → "Novo Livro"
3. Cadastrar um livro com ISBN "978-0132350884"
4. Sistema exibe "Livro cadastrado com sucesso!"
5. Acessar novamente "Livros" → "Novo Livro"
6. Cadastrar outro livro diferente, mas com o mesmo ISBN "978-0132350884"
7. Sistema exibe "Livro cadastrado com sucesso!" (ERRO!)
8. Ao listar os livros, aparecem dois livros diferentes com o mesmo ISBN

RESULTADO ESPERADO:
No passo 7, o sistema deveria exibir uma mensagem de erro 
"ISBN já cadastrado!" e impedir o cadastro do segundo livro.

RESULTADO OBTIDO:
O sistema permite o cadastro e exibe mensagem de sucesso, 
resultando em dois livros com ISBN duplicado no banco de dados.

IMPACTO:
Este bug compromete a integridade do catálogo da biblioteca, pois 
o ISBN é um identificador único internacional de livros. Isso pode 
causar problemas em buscas, relatórios e integração com sistemas externos.

EVIDÊNCIA:
Ver Figura 1 - Screenshots mostrando dois livros com ISBN duplicado

═══════════════════════════════════════════════════════════════
```

**Repitam esse formato para TODOS os bugs encontrados!**

---

### 📄 **5.10 Conclusão**

**O que escrever:**

1. **Síntese dos Resultados**
   - Resumo do que foi feito
   - Principais descobertas

2. **Análise Crítica**
   - O sistema está pronto para produção?
   - Quais são os riscos se os bugs não forem corrigidos?
   - Qual módulo está mais instável?

3. **Aprendizados**
   - O que o grupo aprendeu com este trabalho?
   - Qual foi a maior dificuldade?
   - Como os testes automatizados ajudam na qualidade?

4. **Recomendações**
   - Próximos passos sugeridos
   - Prioridade de correção dos bugs

**Exemplo:**

> **Síntese:**
> Após 15 dias de testes rigorosos, identificamos 7 bugs no sistema BiblioTech, 
> dos quais 2 são críticos e 3 são de alta severidade. A taxa de aprovação de 
> 76,7% indica que o sistema possui boa qualidade geral, mas os bugs encontrados 
> impedem sua liberação para produção.
>
> **Análise Crítica:**
> O sistema NÃO está pronto para produção. Os bugs BUG-001 (ISBN duplicado) e 
> BUG-003 (multa incorreta) afetam diretamente regras de negócio críticas e 
> devem ser corrigidos com MÁXIMA PRIORIDADE antes do lançamento.
>
> **Aprendizados:**
> Este trabalho demonstrou a importância vital dos testes automatizados. Sem eles, 
> esses bugs passariam despercebidos e causariam problemas sérios em produção...

---

### 📄 **5.11 Referências**

Liste todas as fontes consultadas:

```
JUNIT 5. JUnit 5 User Guide. Disponível em: https://junit.org/junit5/docs/current/user-guide/
Acesso em: [data].

SELENIUM. Selenium WebDriver Documentation. Disponível em: https://www.selenium.dev/documentation/
Acesso em: [data].

GITHUB. Trabalho Final - Testes de Sistemas. Disponível em: 
https://github.com/NirtonAfonso/Trabalho-Final-Testes-de-Sistemas
Acesso em: [data].

[Outras referências utilizadas...]
```

---

### 📄 **5.12 Anexos**

Incluam como anexos (após as referências):

- **Anexo A:** Relatório HTML do JUnit (prints ou PDF)
- **Anexo B:** Código-fonte completo dos testes (pode ser link do GitHub)
- **Anexo C:** Screenshots de todos os bugs (se não incluídos na seção 5.7)

---

## 6. Entregáveis

Vocês devem entregar **3 itens**:

### 📦 **6.1 Relatório de Testes (PDF)**

- ✅ Seguindo a estrutura da seção 5
- ✅ Nome do arquivo: `Relatorio_Testes_BiblioTech_GrupoX.pdf`

### 📦 **6.2 Código-Fonte dos Testes (Repositório Git) ou arquivo zipado**

Criem um **fork ou branch** do [repositório original](https://github.com/NirtonAfonso/Trabalho-Final-Testes-de-Sistemas) e adicionem seus testes:

**Estrutura esperada:**
```
bibliotech/
├── src/
│   ├── main/java/com/bibliotech/          [NÃO MODIFICAR]
│   └── test/java/com/bibliotech/          [ADICIONAR AQUI]
│       ├── unit/
│       │   ├── LivroServiceTest.java
│       │   ├── UsuarioServiceTest.java
│       │   ├── EmprestimoServiceTest.java
│       │   └── DashboardServiceTest.java
│       └── selenium/
│           ├── LoginSeleniumTest.java
│           ├── LivroSeleniumTest.java
│           ├── UsuarioSeleniumTest.java
│           └── EmprestimoSeleniumTest.java
├── evidencias/                             [ADICIONAR PASTA]
│   └── screenshots/
└── README_GRUPO.md                         [ADICIONAR]
```

**README_GRUPO.md deve conter:**
- Nome dos integrantes
- Como executar os testes
- Resultados obtidos (resumo)
- Link para o relatório PDF que deve estar no repositório

### 📦 **6.3 Pasta de Evidências**

Organizem uma pasta compactada (.zip) contendo:
```
Evidencias_GrupoX/
├── screenshots/
│   ├── bug-001-isbn-duplicado.png
│   ├── bug-002-multa-incorreta.png
│   └── ...
├── relatorios/
│   └── surefire-report.html
└── logs/
    └── execucao-testes.log  (opcional)
```

---

## 7. Critérios de Avaliação

### 📊 Distribuição de Pontos (Total: 100 pontos)

| Critério | Pontos | Detalhamento |
|----------|--------|--------------|
| **1. Planejamento** | 15 | Matriz de rastreabilidade (5) + Lista de casos de teste (5) + Estratégia clara (5) |
| **2. Testes Unitários** | 25 | Qualidade do código (10) + Cobertura de RNs (8) + Uso correto de assertions (7) |
| **3. Testes Selenium** | 25 | Cobertura de fluxos (10) + Qualidade dos testes (8) + Screenshots de falhas (7) |
| **4. Identificação de Bugs** | 15 | Quantidade encontrada (7) + Qualidade da documentação (5) + Classificação correta (3) |
| **5. Relatório** | 15 | Estrutura completa (5) + Clareza e evidências (5) + Análise crítica (5) |
| **6. Organização** | 5 | Código organizado (2) + Commits no Git (2) + Facilidade de execução (1) |

### 📋 Detalhamento dos Critérios

#### 1. Planejamento (15 pontos)
- [ ] Matriz de rastreabilidade completa relacionando RF/RN × Testes (5 pts)
- [ ] Lista de casos de teste bem documentada antes da implementação (5 pts)
- [ ] Estratégia de testes clara e justificada (5 pts)

#### 2. Testes Unitários (25 pontos)
- [ ] Mínimo 15 testes unitários implementados (5 pts)
- [ ] Código bem estruturado seguindo padrão AAA (Arrange-Act-Assert) (5 pts)
- [ ] Cobertura de regras de negócio críticas (8 pts)
- [ ] Uso correto de assertions do JUnit 5 (4 pts)
- [ ] Nomes descritivos nos testes (@DisplayName) (3 pts)

#### 3. Testes Selenium (25 pontos)
- [ ] Mínimo 10 testes Selenium implementados (5 pts)
- [ ] Testes cobrem fluxos completos do sistema (10 pts)
- [ ] Validações corretas de elementos e redirecionamentos (5 pts)
- [ ] Screenshots capturados automaticamente em falhas (3 pts)
- [ ] Código organizado com métodos auxiliares (2 pts)

#### 4. Identificação de Bugs (15 pontos)
- [ ] Mínimo 5 bugs identificados e documentados (7 pts)
- [ ] Documentação completa de cada bug (descrição, passos, evidência) (5 pts)
- [ ] Severidade classificada corretamente (3 pts)

#### 5. Relatório (15 pontos)
- [ ] Estrutura completa seguindo seção 5 deste README (5 pts)
- [ ] Clareza na escrita e evidências (screenshots) incluídas (5 pts)
- [ ] Análise crítica dos resultados e conclusão bem elaborada (5 pts)

#### 6. Organização (5 pontos)
- [ ] Código organizado em pacotes corretos (2 pts)
- [ ] Commits claros e frequentes no Git (2 pts)
- [ ] Testes podem ser executados facilmente com `mvn test` (1 pt)

---

## 8. Perguntas Frequentes (FAQ)

### 📌 **Sobre o Grupo**

**Q1: Qual é a composição dos grupos?**  
**R:** O trabalho deve ser feito **no mesmo grupo do TCC**. Se seu grupo do TCC tem 3 pessoas, façam em trio. Se tem 4, façam em quarteto.

**Q2: Posso fazer individual?**  
**R:** Não. O trabalho é obrigatoriamente em grupo (mesmo grupo do TCC).

**Q3: Posso trocar de grupo?**  
**R:** Não. Os grupos já foram definidos no início do semestre para o TCC.

---

### 📌 **Sobre o Sistema**

**Q4: Onde encontro o código-fonte do sistema?**  
**R:** No repositório oficial: [https://github.com/NirtonAfonso/Trabalho-Final-Testes-de-Sistemas/tree/main/bibliotech](https://github.com/NirtonAfonso/Trabalho-Final-Testes-de-Sistemas/tree/main/bibliotech)

**Q5: Onde está a documentação completa do sistema?**  
**R:** Na Wiki do projeto: [https://github.com/NirtonAfonso/Trabalho-Final-Testes-de-Sistemas/wiki/BiblioTech-%E2%80%90-Documenta%C3%A7%C3%A3o-de-Modelagem-do-Sistema](https://github.com/NirtonAfonso/Trabalho-Final-Testes-de-Sistemas/wiki/BiblioTech-%E2%80%90-Documenta%C3%A7%C3%A3o-de-Modelagem-do-Sistema)

**Q6: Posso modificar o código do sistema (src/main)?**  
**R:** **NÃO!** Vocês devem apenas criar os testes em `src/test/`. O código em `src/main` não pode ser alterado.

**Q7: E se eu achar que o código do sistema está errado?**  
**R:** Provavelmente está (é proposital)! Documente como um bug no relatório.

---

### 📌 **Sobre os Testes**

**Q8: Quantos testes no mínimo preciso fazer?**  
**R:** Mínimo 15 unitários + 10 Selenium = **25 testes totais**.

**Q9: E se eu fizer mais de 25 testes?**  
**R:** Melhor ainda! Quanto mais testes (com qualidade), maior a nota.

**Q10: O que acontece se todos os meus testes passarem?**  
**R:** Improvável, pois o sistema tem bugs. Se acontecer, provavelmente seus testes não estão cobrindo todos os requisitos. Revise a documentação e amplie a cobertura.

**Q11: Todos os testes devem falhar?**  
**R:** Não! A maioria deve passar. Apenas os testes que encontrarem bugs devem falhar.

**Q12: Posso usar Mockito nos testes unitários?**  
**R:** Sim! Mockito é recomendado para isolar dependências nos testes unitários, mas pode fazer sem se quiser.

**Q13: Preciso testar os Controllers?**  
**R:** Foco principal nos Services. Se quiserem testar Controllers (testes de integração), é um bônus, mas não obrigatório.

---

### 📌 **Sobre os Bugs**

**Q14: Quantos bugs vou encontrar?**  
**R:** O sistema contém múltiplos bugs propositais. Vocês devem encontrar e documentar **pelo menos 5 bugs**.

**Q15: Como sei se é realmente um bug ou se meu teste está errado?**  
**R:** Consulte a documentação (requisitos e regras de negócio). Se o comportamento do sistema viola a documentação, é um bug.

**Q16: E se eu não encontrar nenhum bug?**  
**R:** Muito improvável. Revise a documentação, especialmente as Regras de Negócio (RN). Implemente testes específicos para cada RN.

**Q17: Preciso corrigir os bugs?**  
**R:** **NÃO!** Seu papel é identificar e documentar. A correção é responsabilidade dos desenvolvedores (não de vocês neste trabalho).

---

### 📌 **Sobre o Relatório**


**Q18: Posso usar Canva/PowerPoint para fazer o relatório?**  
**R:** Não recomendado. Use Word ou Google Docs, que são mais adequados para documentos técnicos.

**Q19: Preciso incluir o código dos testes no relatório?**  
**R:** Não precisa incluir código no relatório. O código completo vai no repositório Git.

**Q20: Quantos screenshots preciso incluir?**  
**R:** Pelo menos um screenshot por bug identificado. Não incluam screenshots de testes que passaram.

---

### 📌 **Sobre Execução**

**Q21: Como executo o sistema?**  
**R:** Clone o repositório, importe no Eclipse e execute `mvn spring-boot:run`. Acesse http://localhost:8080

**Q22: Como executo os testes?**  
**R:** `mvn test` para executar todos. `mvn test -Dtest=NomeDoTeste` para executar um específico.

**Q23: Preciso do Chrome instalado para Selenium?**  
**R:** Sim. Os testes Selenium foram configurados para Chrome. Se quiser usar outro navegador, ajuste o código.

**Q24: Como gero o relatório HTML dos testes?**  
**R:** Execute `mvn surefire-report:report`. O relatório estará em `target/site/surefire-report.html`

**Q25: Não estou conseguindo executar o sistema nem os testes pelo terminal da IDE, o que eu posso fazer?**
**R:** Para executar o sistema, abra a Classe `BiblioTechApplication.java` e execute o `Run As`. Faça o mesmo para os testes com suas respsctivas Classes.

---

### 📌 **Sobre Ferramentas**

**Q26: Posso usar IntelliJ em vez de Eclipse?**  
**R:** Sim, qualquer IDE Java serve. Eclipse foi recomendado mas não é obrigatório.

**Q27: Posso usar TestNG em vez de JUnit?**  
**R:** Não. O trabalho exige especificamente **JUnit 5**.

**Q28: Posso usar Cypress em vez de Selenium?**  
**R:** Não. O trabalho exige especificamente **Selenium WebDriver**.

**Q29: Posso usar ChatGPT ou outras IAs para ajudar?**  
**R:** Sim, mas citem no relatório e **entendam o código** que estão usando.

---

### 📌 **Sobre Entrega**

**Q30: Onde e como entregar?**  
**R:** A entrega seeá feita pelo Classroom + link do repositório Git ou Arquivo zipado.

**Q31: Posso entregar após o prazo?**  
**R:** Sim, mas com penalidades (-10 pontos por dia). Após 3 dias não será aceito.

**Q32: O que acontece se o repositório Git estiver privado?**  
**R:** O professor não conseguirá acessar. Deixem **público** ou adicionem o professor como colaborador.

**Q33: Devo entregar o projeto Maven completo?**  
**R:** Sim. Façam fork ou branch do repositório original e adicionem seus testes. Entreguem o link.

---

### 📌 **Sobre Dúvidas Durante o Trabalho**

**Q34: Onde tiro dúvidas?**  
**R:** Podem retirar as dúvidas durante as aulas ou no grupo da turma que o professor está, pois a sua dúvida pode ser uma dúvida do coleguinha também.

**Q35: Posso pedir ajuda aos colegas de outros grupos?**  
**R:** Podem discutir conceitos, mas os testes e relatório devem ser originais do grupo.

---

## 🎯 Mensagem Final

Este trabalho é uma oportunidade de aplicar tudo que aprenderam na disciplina em um cenário realista. **Testem com rigor, documentem com clareza e analisem criticamente!**

Lembrem-se:
- ✅ Bugs são oportunidades de aprendizado, não falhas suas
- ✅ Um bom relatório vale tanto quanto bons testes
- ✅ Organização e clareza contam muito
- ✅ Comecem cedo e dividam bem as tarefas no grupo

**Boa sorte a todos! 🚀**
