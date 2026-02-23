# 💸 Projeto DIO - App de Organização de Finanças Pessoais com Vibe Coding

Aprenda a **criar soluções com IA** de forma criativa, guiando ferramentas como o **Copilot** e o **Lovable** com uma comunicação simples e natural. O foco é desenvolver o conceito de um **App de Organização de Finanças Pessoais**, mas, acima de tudo, aprender o **jeito Vibe de programar com IA**.

## ✨ O que é Vibe Coding

**Vibe Coding** é uma forma leve e criativa de desenvolver com IA, baseada em **conversas naturais e bem estruturadas**. Você não precisa escrever código linha por linha. Em vez disso, aprende a **guiar a IA** descrevendo suas ideias de forma clara, com **intenção e contexto**. Em outras palavras:

> Você mostra a vibe da sua ideia e a IA transforma em solução (ou em um caminho para ela).

## 🎯 Desafio

Problema: Muitas pessoas não conseguem manter um controle financeiro porque os aplicativos exigem muita entrada de dados manual, e a criação de orçamentos é vista como algo tedioso. 

Precisamos de uma solução que permita **controlar as finanças por meio de uma conversa simples**, com **agentes de IA** capazes de criar **planos de economia personalizados e automatizados**. Você deve utilizar as ideias de **Vibe Coding** e **MVP (Produto Mínimo Viável)** para desenvolver o **conceito de um aplicativo** que resolva o problema citado.

> [!IMPORTANT]
> Você **não precisa construir o código**! O foco está em **usar a IA como sua parceira criativa**, transformando boas ideias e prompts em conceitos funcionais que simulam um produto real.

## 🪄 Etapas do Desafio

### 1. Saber o que Pedir é a Chave! Otimize seus Prompts!

Antes de pedir para a IA "criar um app", é importante definir com clareza o que você quer construir e por quê. Para isso, você vai criar um **PRD (Product Requirements Document)** simplificado, uma especificação que serve como _briefing_ para a IA entender sua ideia.

Um bom PRD deve descrever o problema, quem será beneficiado, as principais funcionalidades e o que você espera que a IA entregue. 

### 📄 PRD Refinado no Copilot Web
```txt
# Objetivo
O objetivo é criar um aplicativo de Organização de Finanças Pessoais que funcione por meio de conversas em linguagem natural.
A proposta é simplificar o controle financeiro, eliminando a necessidade de formulários complexos ou planilhas manuais.

# Problema
Atualmente, muitos usuários abandonam aplicativos de finanças porque:
• Exigem muita entrada manual.
• Oferecem pouca personalização.
A solução proposta é uma experiência baseada em conversa natural, com recomendações automáticas de economia.


# Público-Alvo
• Pessoas que desejam iniciar o controle financeiro de forma prática.
• Usuários iniciantes que buscam simplicidade e acessibilidade.


# Funcionalidades-Chave
1.	Registro de receitas e despesas via chat: Inserção de despesas e receitas em linguagem natural.
2.	Classificação automática: O sistema organiza transações em categorias.
3.	Metas financeiras: Definição e acompanhamento de objetivos.
4.	Agente Financeiro: Recomendações de economia personalizadas.
5.	Relatórios simples: Visualizações claras e adaptadas ao perfil do usuário.


# Entregável da IA
• Plano de MVP: Validar a proposta de um aplicativo de finanças pessoais baseado em conversas naturais, garantindo que usuários iniciantes consigam registrar receitas e gastos e receber recomendações de forma simples e intuitiva.
• Linguagem acessível e educativa, em português.
      1. Principais telas: 
      1.1. Chat de interação: Interface central para registrar receitas, despesas e metas financeiras e interagir com o “Agente Financeiro”.
       1.2. Tela de metas:  Definição de objetivos financeiros (exemplo: economizar R$200/mês).
       1.3. Tela de relatórios: Visualização simples de gastos por categoria e progresso das metas.
      2. Recursos necessários: Processamento de linguagem natural, categorização automática, motor de recomendações, banco de dados simples.
      3. Validação inicial: Testes com grupo piloto de usuários iniciantes.
      4. Fluxo de Uso:
      4.1. Usuário registra uma despesa, receita ou meta financeira via chat.
     4.2.	Sistema interpreta e classifica automaticamente.
     4.3.	Usuário define metas.
     4.4.	Agente Financeiro envia dicas e alertas.
     4.5.	Relatórios mostram evolução das metas e categorias de gastos.
5. Storyboard Visual
5.1. Tela 1 – Chat de Registro de despesas e receitas
•	Layout: Caixa de texto para digitar mensagens + histórico de conversa.
•	Elementos visuais: 
	- Balões de conversa (estilo WhatsApp).
	- Ícone do “Agente Financeiro” simpático e amigável.
5.2. Tela 2 – Definição de Metas
•	Layout: Campo para inserir objetivo + barra de progresso.
•	Elementos visuais: 
              - Barra de progresso colorida.
	- Ícones de metas (exemplo: cofrinho, troféu).

5.3. Tela 3 – Recomendações de Economia
•	Layout: Lista de dicas personalizadas com opção de “Adicionar como ação”.
•	Elementos visuais: 
	- Cartões com dicas curtas e ícones ilustrativos (exemplo: cozinhar em casa 2x/semana).
5.4. Tela 4 – Relatórios Simples
•	Layout: Gráfico de pizza ou barras mostrando categorias de gastos + resumo textual.
•	Elementos visuais: 
	- Gráfico colorido.
	- Destaque em verde para economia alcançada.
________________________________________
Observações de Design
•	Tom visual: leve, amigável e educativo.
•	Estilo: ícones simples, cores suaves, interface inspirada em apps de mensagens.
•	Experiência: cada tela reforça o espírito do vibe coding, tornando o controle financeiro uma conversa natural e motivadora.

```



### 2. Interações com o Lovable 


- PROMPT utilizado: Crie um App de finanças pessoais com base no PRD (Product Requirements Document) abaixo;
   - Resposta:
   -  <img width="450" height="692" alt="telas lovable 01" src="https://github.com/user-attachments/assets/653dd185-aa07-45e9-aa90-c487fa75000e" />

- notei que as conversas não ficam salvas, dificultando consultar os detalhes dos gastos e entradas; também notei que o assistente registra qualquer entrada como salário, sendo que as entradas de dinheiro podem ter outras origens, como vendas e prestações de serviço. Outra questão é que na aba metas não tem opção de deletar uma meta, adicione ao lado da meta a opção de excluir. Verifique e corrija estas questões.
  - Resposta:
  -  <img width="450" height="455" alt="telas lovable 02" src="https://github.com/user-attachments/assets/4237548f-6968-494c-9705-3681c9a2f7bc" />


Só consegui mais efetividade do Lovable na minha segunda interação, pois no primeiro dia os créditos gratuitos acabaram.



### 3. Resultado Final Lovable

> Projeto no LOVABLE: https://chatty-money-assistant.lovable.app



## 📱 Galeria de Telas

<div align="center">
  <h3>💬 Tela de Chat</h3>
  <img width="450" alt="tela chat" src="https://github.com/user-attachments/assets/3ac4bdce-af8c-4ffd-b317-0b4a1fcd9480" />
</div>

<div align="center">
  <h3>🎯 Tela de Metas</h3>
  <img width="450" alt="tela metas" src="https://github.com/user-attachments/assets/4574a818-562b-412d-9fe1-3835938137de" />
</div>

<div align="center">
  <h3>📊 Tela de Relatórios</h3>
  <img width="450" alt="tela relatorios" src="https://github.com/user-attachments/assets/db81562f-ae06-4fd4-b041-901eacaf372e" />
</div>

<div align="center">
  <h3>💡 Tela de Dicas</h3>
  <img width="450" alt="tela dicas" src="https://github.com/user-attachments/assets/c239ead0-21af-4f98-96b4-b7a752511ee1" />
</div>





---

# 📊 Chatty Money Assistant

## 🎯 Objetivo
O aplicativo tem como propósito **simplificar o controle financeiro pessoal** por meio de uma experiência baseada em **conversas em linguagem natural**, eliminando a necessidade de formulários complexos ou planilhas manuais.

---

## 🚩 Problema
Muitos usuários abandonam apps de finanças porque:
- Exigem muita entrada manual.  
- Oferecem pouca personalização.  

O Chatty Money Assistant resolve isso com uma interface de chat intuitiva e recomendações automáticas de economia.

---

## 👥 Público-Alvo
- Pessoas que desejam iniciar o controle financeiro de forma prática.  
- Usuários iniciantes que buscam simplicidade e acessibilidade.  

---

## ⚙️ Funcionalidades-Chave
1. **Registro de receitas e despesas via chat**  
   - Inserção de transações em linguagem natural (ex.: *“Gastei R$45 no almoço”*).  

2. **Classificação automática**  
   - O sistema organiza despesas e receitas em categorias como *Moradia*, *Alimentação*, *Serviços*, etc.  

3. **Metas financeiras**  
   - Definição de objetivos (ex.: *“Quero guardar R$5000 para um fundo de emergência”*).  
   - Acompanhamento com barra de progresso.  

4. **Agente Financeiro**  
   - Assistente virtual que registra transações, sugere dicas de economia e acompanha metas.  

5. **Relatórios simples**  
   - Visualizações claras (gráficos de pizza ou barras) mostrando categorias de gastos e evolução das metas.  

---

## 🖼️ Principais Telas
- **Chat de interação**  
  - Interface central para registrar receitas, despesas e metas.  
  - Estilo inspirado em apps de mensagens, com balões de conversa e ícone simpático do Agente Financeiro.  

- **Tela de Metas**  
  - Campo para inserir objetivo + barra de progresso colorida.  
  - Ícones ilustrativos (cofrinho, troféu).  

- **Tela de Recomendações**  
  - Lista de dicas personalizadas com opção de “Adicionar como ação”.  
  - Cartões com ícones ilustrativos (ex.: cozinhar em casa 2x/semana).  

- **Tela de Relatórios**  
  - Gráficos simples (pizza ou barras) mostrando categorias de gastos.  
  - Destaque em verde para economia alcançada.  

---

## 🛠️ Recursos Técnicos
- Processamento de linguagem natural (NLP).  
- Categorização automática de transações.  
- Motor de recomendações financeiras.  
- Banco de dados simples para registros.  

---

## ✅ Fluxo de Uso
1. Usuário registra uma despesa, receita ou meta via chat.  
2. Sistema interpreta e classifica automaticamente.  
3. Usuário define metas financeiras.  
4. Agente Financeiro envia dicas e alertas.  
5. Relatórios mostram evolução das metas e categorias de gastos.  

---

## 🎨 Observações de Design
- **Tom visual:** leve, amigável e educativo.  
- **Estilo:** ícones simples, cores suaves, interface inspirada em apps de mensagens.  
- **Experiência:** cada tela reforça a ideia de que controlar finanças pode ser tão natural quanto conversar.  

---




## 💬 4. Reflexão sobre o Processo

### ✅ O que funcionou bem
Com o ajuste prévio do PRD feito no Copilot pude utilizar com mais assertividade o Lovable somente com os créditos gratuitos.  

### ⚠️ O que não funcionou como o esperado
As metas não foram atualizadas. Os ajustes não foram possiveis, pois os créditos acabaram.  

### 💡 O que aprendi sobre conversar com IAs
O principal é construir um prompt detalhado e bem estruturado, com as funções que você espera.    

A conversa flui de modo natural, sem formalidades, como se você estivesse passando instruções para uma uma pessoa. Quanto mais claras as instruções, quanto mais conhecimento você possuir sobre o assunto, melhores são os resultados.  



