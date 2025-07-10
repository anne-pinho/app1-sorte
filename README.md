# 🍀 Número da Sorte – App Flutter

Aplicativo simples, interativo e divertido, desenvolvido durante o **curso de capacitação em Flutter do Instituto Venturus**.

Este projeto tem como objetivo exercitar os fundamentos do Flutter, incluindo widgets, gerenciamento de estado, layout responsivo e boas práticas de desenvolvimento mobile.

---

## 🎯 Funcionalidades

- Interface amigável com título, descrição e botão central de ação.
- Gera e exibe um **número aleatório entre 0 e 10**.
- Indica quando um número **já foi sorteado anteriormente**.
- Lista todos os números já sorteados na sessão atual.
- Botão flutuante de **reset**, que limpa a lista e reinicia o sorteio.

---

## 🛠️ Tecnologias e conceitos utilizados

- **Flutter** + **Dart**
- `StatefulWidget` e `setState()` para gerenciamento de estado
- Principais widgets:
  - `MaterialApp`, `Scaffold`, `AppBar`, `Column`, `Container`, `Text`, `ElevatedButton`, `FloatingActionButton`
- Estilização com:
  - `TextStyle`, `EdgeInsets`, `MainAxisAlignment`, `padding`, `margin`
- Lógica de sorteio:
  - `Random().nextInt(11)` para gerar números de 0 a 10
  - Verificação de duplicidade com `List<int>`

---

## 🚀 Como executar o projeto

1. Certifique-se de ter o **Flutter SDK** instalado:  
   👉 [flutter.dev/get-started/install](https://flutter.dev/get-started/install)

