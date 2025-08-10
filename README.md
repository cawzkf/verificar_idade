# Verificação de Maioridade

Programa simples em **C** que solicita ao usuário sua idade e determina se a pessoa é maior ou menor de idade com base na entrada fornecida. Desenvolvido como atividade acadêmica para demonstrar conceitos básicos de programação.

---

## Funcionalidades

* **Entrada de dados** via terminal
* **Validação de idade** (18 anos como critério)
* **Exibição de resultado** com mensagem clara
* **Interface simples** em linha de comando
* **Lógica condicional** básica

---

## Tecnologias Utilizadas

![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![GCC](https://img.shields.io/badge/GCC-A42E2B?style=for-the-badge&logo=gnu&logoColor=white)
![Terminal](https://img.shields.io/badge/Terminal-000000?style=for-the-badge&logo=windows-terminal&logoColor=white)

### Stack Detalhada

* **Linguagem C** — Linguagem de programação principal
* **GCC Compiler** — Compilador GNU para C
* **stdio.h** — Biblioteca padrão para entrada e saída
* **Terminal/CMD** — Interface de linha de comando

---

## Estrutura do Programa

```
projeto/
├── verificar_maioridade.c    # Código fonte principal
├── README.md                 # Documentação
└── verificar_maioridade      # Executável (após compilação)
```

---

## Como o Programa Funciona

### Fluxo de Execução

1. **Solicita entrada** - Pede ao usuário para digitar sua idade
2. **Recebe dados** - Captura a idade inserida via `scanf()`
3. **Aplica lógica** - Verifica se idade >= 18 anos
4. **Exibe resultado** - Mostra se é maior ou menor de idade
5. **Finaliza** - Programa encerra após exibir o resultado

### Lógica Condicional

```c
if (idade >= 18) {
    printf("Você é maior de idade.\n");
} else {
    printf("Você é menor de idade.\n");
}
```

---

## Pré-requisitos

* **Compilador C** (GCC recomendado)
* **Sistema operacional** Windows, Linux ou macOS
* **Terminal/Prompt** de comando
* **Conhecimentos básicos** de linha de comando

---

## Compilação e Execução

### Compilar o Programa

```bash
gcc -o verificar_maioridade verificar_maioridade.c
```

### Executar

**Linux/macOS:**
```bash
./verificar_maioridade
```

**Windows:**
```cmd
verificar_maioridade.exe
```

### Exemplo de Uso

```
Digite sua idade: 20
Você é maior de idade.
```

```
Digite sua idade: 16
Você é menor de idade.
```

---

## Conceitos Demonstrados

### Programação Básica
* **Variáveis** e tipos de dados (`int`)
* **Entrada de dados** com `scanf()`
* **Saída de dados** com `printf()`
* **Estruturas condicionais** (`if/else`)

### Boas Práticas
* **Código limpo** e legível
* **Comentários** explicativos
* **Nomenclatura** clara de variáveis
* **Estrutura** organizada do programa

---

## Possíveis Melhorias

* **Validação de entrada** para números negativos
* **Tratamento de erros** para entradas inválidas
* **Interface mais amigável** com menus
* **Suporte a diferentes** critérios de maioridade por país
* **Logs** de execução para debugging

---

## Repositório

[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/cawzkf/verificacao-maioridade)

**Repositório:** [github.com/cawzkf/verificar_idade](https://github.com/cawzkf/verificar_idade)

---

<div align="center">

**Desenvolvido como atividade acadêmica de programação**

![C](https://img.shields.io/badge/Made_with-C-00599C?style=flat-square&logo=c&logoColor=white)
![GCC](https://img.shields.io/badge/Compiled_with-GCC-A42E2B?style=flat-square&logo=gnu&logoColor=white)

</div>
