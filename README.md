# 🔐 Strong Password

Um sistema para análise da força de senhas, desenvolvido como projeto acadêmico da disciplina **Modelos, Métodos e Técnicas da Engenharia de Software** – Universidade São Judas Tadeu.

## 📌 Descrição

O **Strong Password** é uma aplicação que permite ao usuário inserir uma senha e obter uma avaliação sobre sua força, com base em critérios como diversidade de caracteres, comprimento e presença de padrões fracos. O sistema fornece recomendações para melhorar senhas fracas e conscientiza os usuários sobre boas práticas de segurança digital.

## 🚀 Funcionalidades

- ✅ Análise da força da senha com base em:
  - Comprimento mínimo
  - Letras maiúsculas e minúsculas
  - Números
  - Caracteres especiais
  - Padrões fracos (ex: "123456", "senha", etc.)
- ✅ Classificação da senha (Muito fraca → Muito forte)
- ✅ Sugestões de melhoria para senhas fracas
- ✅ Interface via terminal (CLI)
- ✅ Testes automatizados com Pytest
- ✅ Conformidade com boas práticas de segurança (OWASP)

## 🛠️ Tecnologias Utilizadas

- **Linguagem:** Python 3.7+
- **IDE:** Visual Studio Code / PyCharm
- **Controle de Versão:** Git + GitHub
- **Testes:** Pytest, unittest
- **Ferramentas de qualidade:** flake8

## 📄 Requisitos

- Python 3.7 ou superior
- Bibliotecas padrão do Python: `string`, `getpass`

## 🧪 Testes

O projeto possui testes automatizados baseados em:

- Caixa branca (verificando lógica e fluxo do código)
- Caixa preta (verificando respostas e comportamento esperado)
- Testes de integração e interface
- Testes de entrada inválida e feedbacks

Executar testes com:
```bash
pytest


## 👨‍💻 Equipe
Enrico Aguiar Vrunski

Thiago Ferreira Lima Gonçalves 

Matheus Tognon Siqueira 

Felipe Soares de Oliveira 

Kayky Cerquiaro Prado 


## 📚 Bibliografia
[Python Docs - String](https://docs.python.org/3/library/string.html)

[Python Docs - getpass](https://docs.python.org/3/library/getpass.html)

[OWASP Top 10](https://owasp.org/www-project-top-ten/)

[Código Base: Password Strength Checker](https://github.com/itsallaboutpython/Top-10-Easy-Python-Project-Ideas-For-Beginners/blob/main/password_strength_checker.py)


Licença: MIT License – sinta-se livre para usar, contribuir e adaptar!
