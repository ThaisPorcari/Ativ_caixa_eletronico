# Ativ_caixa_eletronico
# 🏦 Sistema de Caixa Eletrônico (GEN-CAIXA)

Este é um projeto simples, interativo e robusto de um **Caixa Eletrônico** desenvolvido em Python. O sistema simula operações bancárias essenciais de forma prática diretamente no ambiente do Google Colab, permitindo ao usuário gerenciar seu saldo dinamicamente com validações de segurança.

## 🚀 Funcionalidades

*   **💰 Consulta de Saldo:** Visualize o seu saldo atualizado instantaneamente.
*   **📈 Depósito Inteligente:** Adicione fundos à sua conta e veja o saldo ser atualizado na hora.
*   **📉 Saque Seguro com Validação:** Realize saques com verificação de limite. Se o saldo for insuficiente, o sistema impede a operação e oferece a opção amigável de tentar novamente com outro valor.
*   **🔁 Menu Interativo Contínuo:** Uma estrutura de repetição que mantém o sistema ativo para múltiplas operações sucessivas até que você decida encerrar.

## 🛠️ Tecnologias Utilizadas

*   **Linguagem:** Python 
*   **Conceitos Aplicados:** 
    *   Programação Estruturada e Modular (Funções reutilizáveis)
    *   Estruturas de Repetição (`while` e controle de fluxo com `break`)
    *   Estruturas Condicionais (`if`, `elif`, `else`)
    *   Manipulação e validação de entradas de dados (Cast para `float` e métodos de string)

## 🖥️ Como Executar no Google Colab

1. Abra este notebook no seu ambiente do Google Colab.
2. Execute sequencialmente a célula que contém as funções de depósito (`depositar`) e saque (`sacar`).
3. Execute a célula principal que inicializa o menu do `GEN-CAIXA`.
4. Interaja com as caixas de entrada digitando as opções e valores diretamente no console gerado pelo Colab.

## 📝 Exemplo de Uso Prático

```text
Bem vindo ao GEN-CAIXA
Informe seu saldo: 100

Escolha uma das opções:
1 - ver saldo
2 - depositar
3 - sacar
qualquer outra opção - sair

Digite sua opção: 2
seu saldo atual é R$ 100.0
Informe o valor do depósito: 400
Seu saldo atual é R$ 500.00

🤝 Contribuição
Contribuições são sempre bem-vindas! Se você tiver ideias para melhorar a interface do console, adicionar novas operações (como transferência ou extrato) ou refatorar o código, sinta-se à vontade para abrir uma issue ou enviar um pull request.
