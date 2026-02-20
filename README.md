# project-feature-bdd

## O que é BDD?

**BDD (Behavior Driven Development)** é uma abordagem de desenvolvimento ágil
que incentiva a colaboração entre desenvolvedores, QA e pessoas de negócio.
O foco está em descrever o comportamento do sistema em uma linguagem comum, facilitando o entendimento por todos.

## Conceitos Básicos

- **Feature:** Descreve uma funcionalidade do sistema.
- **Scenario:** Exemplos de comportamento esperado.
- **Given/When/Then:** Palavras-chave para estruturar os cenários:
    - **Given**: contexto inicial (pré-condições)
    - **When**: ação executada
    - **Then**: resultado esperado

## Dependências necessárias-Maven
<dependencies>
    <!-- Dependência para testes do Spring Boot -->
    <dependency>
        <groupId>org.springframework.boot</groupId>
        <artifactId>spring-boot-starter-test</artifactId>
        <scope>test</scope>
    </dependency>

    <!-- Dependências do Cucumber -->
    <dependency>
        <groupId>io.cucumber</groupId>
        <artifactId>cucumber-java</artifactId>
        <version>7.14.0</version>
        <scope>test</scope>
    </dependency>
    <dependency>
        <groupId>io.cucumber</groupId>
        <artifactId>cucumber-junit</artifactId>
        <version>7.14.0</version>
        <scope>test</scope>
    </dependency>
    <dependency>
        <groupId>io.cucumber</groupId>
        <artifactId>cucumber-spring</artifactId>
        <version>7.14.0</version>
        <scope>test</scope>
    </dependency>
</dependencies>

## C# project-feature-bdd

## O que é BDD?

**BDD (Behavior Driven Development)** é uma abordagem de desenvolvimento ágil
que incentiva a colaboração entre desenvolvedores, QA e pessoas de negócio.
O foco está em descrever o comportamento do sistema em uma linguagem comum, facilitando o entendimento por todos.

## Conceitos Básicos

- **Feature:** Descreve uma funcionalidade do sistema.
- **Scenario:** Exemplos de comportamento esperado.
- **Given/When/Then:** Palavras-chave para estruturar os cenários:
  - **Given**: contexto inicial (pré-condições)
  - **When**: ação executada
  - **Then**: resultado esperado

## Dependências necessárias-Maven
<dependencies>
    <!-- Dependência para testes do Spring Boot -->
    <dependency>
        <groupId>org.springframework.boot</groupId>
        <artifactId>spring-boot-starter-test</artifactId>
        <scope>test</scope>
    </dependency>

    <!-- Dependências do Cucumber -->
    <dependency>
        <groupId>io.cucumber</groupId>
        <artifactId>cucumber-java</artifactId>
        <version>7.14.0</version>
        <scope>test</scope>
    </dependency>
    <dependency>
        <groupId>io.cucumber</groupId>
        <artifactId>cucumber-junit</artifactId>
        <version>7.14.0</version>
        <scope>test</scope>
    </dependency>
    <dependency>
        <groupId>io.cucumber</groupId>
        <artifactId>cucumber-spring</artifactId>
        <version>7.14.0</version>
        <scope>test</scope>
    </dependency>
</dependencies>

## Configurar o Cumcuber

- 1.Estrutura de Pastas Recomendada
src └── test ├── java │ └── com │ └── seu_pacote │ ├── stepdefs │ │ └── MeuStepDefinitions.java │ └── RunCucumberTest.java └── resources └── features └── meu_teste.feature
- 2.Exemplo de arquivo .feature
  rc/test/resources/features/meu_teste.feature:

