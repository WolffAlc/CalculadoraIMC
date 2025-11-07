## 🧮 Calculadora de IMC (Delphi)

### 📋 Descrição

Este projeto é uma **calculadora de IMC (Índice de Massa Corporal)** desenvolvida em **Delphi (VCL)**.
O objetivo é oferecer uma interface simples e intuitiva para o usuário calcular seu IMC com base em **idade, altura e peso**, exibindo mensagens personalizadas conforme a faixa de resultado obtida.

Além do cálculo em si, o sistema inclui validações de entrada e limites máximos, garantindo uma experiência interativa e divertida.

---

### ⚙️ Funcionalidades

* 🧠 Cálculo automático do IMC a partir da **altura** e **peso** informados.
* 🧍‍♂️ Campo de **sexo** para seleção (masculino/feminino).
* 🎂 Campo de **idade**, com limite máximo validado (até 122 anos).
* 📏 Validação de **altura** (máximo 2,34 metros).
* ⚖️ Validação de **peso** (máximo 300 kg).
* 💬 Mensagens personalizadas conforme a classificação do IMC:

  * Abaixo do peso
  * Peso ideal
  * Sobrepeso
  * Obesidade grau I
  * Obesidade grau II
  * Obesidade grau III (mórbida)

---

### 💻 Tecnologias utilizadas

* **Delphi (VCL Forms Application)**
* **Linguagem Object Pascal**
* Componentes visuais:

  * `TEdit`, `TMaskEdit`, `TRadioGroup`, `TSpeedButton`, `TPanel`, `TLabel`
* Tratamento de eventos e validação com `TryStrToFloat` e `TryStrToInt`

---

### 🧩 Estrutura principal

O código está centralizado na **unit `CalcImc.pas`**, que contém:

* A lógica de cálculo e exibição do IMC (`btCalcularClick`)
* Rotinas de validação dos campos de entrada
* Controle de teclas (`KeyPress`) para permitir apenas números e vírgulas
* Mensagens interativas com `ShowMessage` e `MessageDlg`

---

### 🧠 Lógica do cálculo

O IMC é calculado com a fórmula:

[
IMC = \frac{peso}{(altura \times altura)}
]

Com base no resultado, o programa exibe a categoria correspondente, junto com a idade do usuário.

---

### 📦 Como executar

1. Abra o projeto no **Delphi** (qualquer versão compatível com VCL, ex: Delphi 10.x).
2. Compile e execute (`F9`).
3. Informe:

   * Idade
   * Altura (em metros, ex: `1,75`)
   * Peso (em kg, ex: `80`)
4. Clique em **Calcular** e veja o resultado!

---

### 📸 Exemplo de uso

> “Você tem 28 anos, seu IMC é 30,80 e você está com obesidade grau I!”

---

### 🧰 Possíveis melhorias futuras

* Adicionar um gráfico de classificação do IMC.
* Permitir salvar o histórico de cálculos.
* Implementar interface responsiva com `TTabControl`.
* Criar versão em **FireMonkey** (compatível com mobile).

---

### 👨‍💻 Autor

**Wolfgang**
Projeto desenvolvido para fins de estudo e prática em Delphi.
📅 Ano: 2025

---

