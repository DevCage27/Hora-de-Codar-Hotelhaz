# Exercícios de Programação em Kotlin (Hora de Codar 📲)

Este repositório contém meus exercícios de programação em Kotlin. Aqui, você encontrará uma coleção de códigos e práticas que estou desenvolvendo para aprimorar minhas habilidades na linguagem.

# 🏨 Hotel HAZ – Sistema de Gerenciamento em Kotlin

Um refúgio digital onde a burocracia hoteleira encontra poesia em loops e condicionais. Ideal para quem quer treinar **Estruturas de Controle**, **Manipulação de Coleções** e **Leitura de Dados** em Kotlin, tudo temperado com um toque noir e café quente.

---

## ✨ Funcionalidades

Neste terminal, o concierge é seu programa. Ele oferece:

- 🔐 **Login por senha**  
- 🛎️ **Boas-vindas e despedida** personalizadas  
- 🛏️ **Reserva de quartos** (20 unidades, controle de ocupação)  
- 📝 **Cadastro, pesquisa e listagem de hóspedes**  
- 🎉 **Reserva de eventos** (auditórios, buffet, garçons, relatório completo)  
- ⛽ **Comparativo de preços de combustível**  
- ❄️ **Orçamento de manutenção de ar-condicionado**  
- 🛠️ **Menu interativo** com tratamento de erros e recursão leve  
- 🚪 **Saída elegante** com confirmação

---

## 🌙 Atmosfera Noir

Este código é um traje preto sob luzes de néon:

> “No caos das entradas do usuário, organizamos ordem;  
>  no silencioso byte do Kotlin, construímos experiências.”

Use `Código Rosa Neon` mental para ativar seu charme de vilão carismático ao rodar este app.

---

## 🛠️ Tecnologias

- **Linguagem**: Kotlin  
- **Execução**: Terminal/Console  
- **Coleções**: `MutableList` para status de quartos e orçamentos  
- **Leituras**: `readlnOrNull()`, conversões seguras (`toIntOrNull()`, `toDoubleOrNull()`)

---

## 📂 Estrutura do Código

Cada bloco de função é um cômodo deste hotel digital:

1. `main()` – Autenticação inicial e chamada ao fluxo principal  
2. `boasVindas()` / `despedida()` – Saudação e fechamento com estilo  
3. `inicio()` – Loop infinito do **Menu Principal**  
4. `reservarQuarto()` – Lógica de diárias, seleção e confirmação de quarto  
5. `cadastrarHospedes()` – Taxas diferenciadas por idade (gratuidade, meia)  
6. `pesquisarHospedes()` – CRUD simplificado: cadastrar, buscar, listar  
7. `reservarEvento()` – Capacidade, data, horas, garçons, buffet e relatório final  
8. `abastecerCarro()` – Comparativo inteligente de preços de álcool vs. gasolina  
9. `manutencaoArCondicionado()` – Múltiplos orçamentos, cálculo de descontos e escolha do mais barato  
10. `erro()` – Guia o usuário de volta ao jogo quando a escolha falha

---

## 🚀 Como Rodar

1. Copie o código para `HotelHAZ.kt`.  
2. Compile:  
   ```bash
   kotlinc HotelHAZ.kt -include-runtime -d HotelHAZ.jar
3. execute:
java -jar HotelHAZ.jar
