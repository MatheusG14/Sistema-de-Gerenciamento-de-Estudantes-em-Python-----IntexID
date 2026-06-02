# 📚 Sistema de Boletim Escolar

## 📖 Sobre o Projeto

Sistema desenvolvido em Python para gerenciamento de alunos, cálculo de médias e controle de frequência escolar.

### Funcionalidades

* Cadastro de alunos
* Registro de notas
* Cálculo automático da média
* Controle de frequência
* Verificação de aprovação ou reprovação
* Armazenamento dos dados em listas e dicionários
* Cadastro de múltiplos alunos

---

## 🏗️ Estrutura do Projeto

### Funções Principais

| Função                  | Descrição                |
| ----------------------- | ------------------------ |
| `calcular_nota()`       | Calcula a média do aluno |
| `calcular_frequencia()` | Soma as presenças        |
| `cadastrar_aluno()`     | Recebe os dados do aluno |
| `exibir_resultados()`   | Exibe o boletim final    |

---

## 🔄 Fluxo do Sistema

```text
Início
 ↓
Cadastrar Aluno
 ↓
Inserir Notas
 ↓
Calcular Média
 ↓
Registrar Frequência
 ↓
Exibir Resultado
 ↓
Cadastrar Novo Aluno?
 ↓
Fim
```

---

## 💻 Exemplo de Estrutura de Dados

```python
{
    "nome": "João",
    "boletim": {
        "Matemática": {
            "notas": [8, 7, 9],
            "media": 8,
            "presenca": 60
        }
    }
}
```

---

## 📋 Exemplo de Saída

```text
========================================
RESULTADO FINAL: JOÃO
========================================

--- MATEMÁTICA ---
Nota média: 8
Status (Nota): Aluno Aprovado!

----------------------------------------
Presença total (todas as matérias): 420
----------------------------------------
```

---

## 🛠️ Tecnologias Utilizadas

* Python 3
* Estruturas Condicionais
* Loops
* Funções
* Listas
* Dicionários

---

## 🎯 Conceitos Aplicados

* Modularização
* Programação Estruturada
* Manipulação de Dados
* Boas Práticas de Programação
* Organização de Código

---

## 🚀 Como Executar

```bash
python main.py
```

---

## 👨‍💻 Autor

Projeto desenvolvido para fins acadêmicos e aprendizado de programação em Python.


🌐 Demonstração Interativa

Acesse o repositório do projeto:

https://github.com/MatheusG14/Sistema-de-Gerenciamento-de-Estudantes-em-Python---Idex
