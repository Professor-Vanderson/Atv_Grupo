# 📘 Projeto Prático: Sistema de Entrega e Notificação com Design Patterns

## 🌟 Objetivo
Este projeto tem como objetivo praticar a implementação dos padrões de projeto **Adapter**, **Strategy** e **Observer** utilizando **Java com Spring Boot**, simulando um sistema de logística de uma plataforma de e-commerce.

---

## 📖 Contexto
Você foi contratado para desenvolver um módulo de **logística**. Esse módulo deve calcular valores de frete com diferentes transportadoras, integrar-se com uma transportadora externa e notificar o cliente e equipe interna após o processamento de uma entrega.

---

## 📊 Requisitos do Sistema

### 1. Cálculo de Frete (**Strategy Pattern**)
- O sistema deve oferecer três modalidades de entrega:
  - Entrega Expressa
  - Entrega Econômica
  - Transportadora Terceirizada
- Cada modalidade deve ter uma **regra de cálculo de frete diferente**.
- A escolha da modalidade deve ser feita de forma **dinâmica**, via parâmetro na requisição.

### 2. Integração com Transportadora Externa (**Adapter Pattern**)
- Uma transportadora externa fornece uma API que não segue os padrões do seu sistema.
- Deve-se criar um **adaptador** que permita integrar a API externa sem alterar o funcionamento interno do sistema.

### 3. Notificações de Entrega (**Observer Pattern**)
- Após concluir a entrega, o sistema deve:
  - Enviar um e-mail de confirmação ao cliente
  - Registrar um log da operação
  - Enviar uma mensagem para a equipe de atendimento
- Cada uma dessas tarefas deve ser tratada por um **observador independente**, notificado automaticamente.

---

## 🚀 Funcionalidades Esperadas
- Um endpoint HTTP que receba o **peso** e a **modalidade** da entrega.
- Cálculo automático do frete com base na estratégia escolhida.
- Uso do **adapter** para integrar com a transportadora externa (quando necessário).
- Notificação automática de todos os observadores ao concluir a entrega.

---

## 🧠 Desafios Propostos
- Implementar os três padrões de forma clara e funcional.
- Permitir que novas estratégias, integrações ou notificadores possam ser adicionados **sem alterar o código existente**.

---

## 📦 Entregáveis
1. Código-fonte Java/Spring Boot com a implementação dos padrões.
2. `README.md` com explicações sobre o uso dos padrões.
3. Evidências de funcionamento (ex: logs ou prints).
4. (Opcional) Diagrama UML mostrando os padrões usados.

---

> Boa sorte e bom código! 🚀 Se precisar de ajuda com exemplos ou testes, fale com seu instrutor ou consulte a documentação do Spring.


