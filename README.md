# Hospedei
Um sistema simples de Hotelaria feito em Java

Este projeto é um sistema simples de **Check-in, Check-out e controle de hóspedes (In-House)** feito em **Java**, utilizando o terminal/console para entrada e saída de dados.

---

## Funcionalidades

- ✅ **Check-in**: Cadastro de hóspedes com nome e número de contato.
- ✅ **Check-out**: Remoção de hóspedes da lista de hospedagem.
- ✅ **In-House**: Visualização de todos os hóspedes atualmente hospedados.
- ❌ **Finalização do sistema**: Encerra o programa de forma limpa.

---

## Tecnologias utilizadas

- [Java](https://www.oracle.com/java/) – Linguagem principal do projeto
- `Scanner` – Para entrada de dados via console
- `ArrayList` – Para armazenamento dinâmico da lista de hóspedes
- `Thread.sleep()` – Para simular carregamento

---

## Como executar

1. Certifique-se de ter o **Java JDK** instalado.
2. Compile o arquivo:
   ```bash
   javac JavaApplication17.java
   ```
3. Execute o programa:
   ```bash
   java JavaApplication17
   
---

## Exemplo de uso

```text
==== BEM VINDO(A) ====
1 - Check-in
2 - Check-out
3 - In-House
4 - Sair
Informe a opção desejada aqui:
```

---

## 📦 Estrutura do código

- `main`: loop principal com menu interativo
- `esperar()`: método auxiliar para simular atraso no sistema
- `ArrayList<String> hospede`: armazenamento dos nomes dos hóspedes

---

## Contribuições

Sinta-se à vontade para clonar, melhorar ou adaptar o projeto conforme necessário.
