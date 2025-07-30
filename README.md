# 🏨 Sistema de Hospedagem - DIO .NET

Este projeto foi desenvolvido como parte do desafio da DIO na trilha .NET, 
com o objetivo de criar um sistema de hospedagem que gerencia reservas de suítes e hóspedes.

## 🚀 Funcionalidades

- Cadastro de hóspedes
- Cadastro de suíte
- Validação de capacidade da suíte
- Cálculo do valor da diária
- Desconto de 10% para reservas com 10 ou mais dias

## 📸 Demonstração

<div align="center">
  <img src="hotel_gif.png" alt="Hotel GIF" width="500"/>
</div>


## 🛠 Tecnologias

- C#
- .NET 6
- Console Application

## 📦 Estrutura

HospedagemHotel/ ├── Program.cs ├── Models/ │   ├── Pessoa.cs │   ├── Suite.cs │   └── Reserva.cs ├── README.md


## 📋 Regras de Negócio

- A suíte deve ter capacidade suficiente para os hóspedes.
- O valor da reserva é calculado multiplicando os dias reservados pelo valor da diária.
- Reservas com 10 ou mais dias recebem 10% de desconto.

## 🧪 Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/HospedagemHotel.git
   cd HospedagemHotel
   dotnet run
🧠 Autor

 Desenvolvido por Tatiana Kami com 💙 e curiosidade.Bootcamp DIO


