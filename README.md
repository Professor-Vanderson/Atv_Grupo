# 📦 Projeto de Entregas com Adapter, Strategy e Observer

## 🎯 Objetivo
Este projeto foi desenvolvido como parte de uma atividade prática em grupo para aplicação dos padrões de projeto **Adapter**, **Strategy** e **Observer** utilizando Java com Spring Boot.

## 🧱 Cenário
Você faz parte da equipe de desenvolvimento de uma plataforma de e-commerce. Seu time recebeu a missão de desenvolver o novo módulo de entregas da aplicação. Esse módulo precisa ser flexível, reutilizável e de fácil manutenção.
Para isso, será necessário aplicar 3 padrões de projeto:

1. Adapter para integrar transportadoras externas com interface incompatível.
2. Strategy para calcular frete com base em diferentes estratégias de entrega.
3. Observer para enviar notificações automáticas após o processamento de pedidos.
---

## 🧱 Descrição do sistema

O sistema simula o processamento de pedidos de uma plataforma de e-commerce. Ao cadastrar um pedido, o sistema:

1. Calcula o valor do frete com base na **estratégia de entrega** escolhida (`expressa`, `economica`, `transportadora`).
2. Integra com uma **transportadora externa** caso necessário, usando um **Adapter**.
3. Dispara automaticamente **notificações** para o cliente, equipe e sistema de log, usando **Observers**.

---

## 🚀 Funcionalidades

- `POST /pedidos` → Cria e processa um pedido
- `GET /pedidos` → Lista todos os pedidos
- Integração com transportadora externa (simulada)
- Cálculo de frete via Strategy
- Notificações automáticas com Observer

---

## 📐 Padrões de Projeto Aplicados

| Padrão     | Descrição |
|------------|-----------|
| **Adapter** | Permite que o sistema utilize a API da transportadora externa, mesmo com uma interface diferente. |
| **Strategy** | Permite alterar dinamicamente o cálculo do frete sem mudar o código principal. |
| **Observer** | Permite que várias ações (e-mail, log, notificações) sejam executadas automaticamente após um pedido ser processado. |

---
