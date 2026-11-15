# 💸 App de Organização de Finanças Pessoais(Bolso) do wesley com Vibe Coding

PRD refinado no copilot:

```
Crie um app de finanças pessoais com base no seguinte PRD(Product Requirements Document): 
PRD – Assistente de Finanças Pessoais Conversacional

Visão Geral
Criar um aplicativo de gestão financeira pessoal baseado em conversas em linguagem natural.

O usuário não precisa preencher formulários complexos. Em vez disso, ele conversa com um assistente financeiro que interpreta mensagens, registra transações, categoriza gastos, acompanha metas e fornece recomendações personalizadas.

O objetivo é transformar o controle financeiro em uma experiência simples, intuitiva e acessível para iniciantes.

Problema
Muitas pessoas abandonam aplicativos financeiros porque:

Exigem entrada manual excessiva.
Possuem interfaces complexas.
Não oferecem orientação personalizada.
Geram relatórios difíceis de interpretar.
Como consequência, usuários iniciantes têm dificuldade para manter uma rotina de controle financeiro.

Objetivo do Produto
Permitir que qualquer pessoa registre e acompanhe suas finanças usando linguagem natural, recebendo orientação prática para melhorar sua saúde financeira.

Público-Alvo
Primário
Pessoas iniciando sua organização financeira pessoal.

Perfil
18 a 45 anos.
Pouco conhecimento financeiro.
Desejam controlar gastos sem planilhas.
Procuram orientação simples para economizar.
Proposta de Valor
"Controle suas finanças conversando como se estivesse falando com um amigo."

Funcionalidades do MVP
1. Registro de Gastos por Conversa
O usuário envia mensagens como:

"Gastei R$ 35 no almoço."
"Paguei R$ 120 de internet."
"Recebi R$ 2.500 de salário."
O sistema deve identificar:

Valor.
Tipo da transação.
Categoria.
Data.
2. Classificação Automática
Categorias iniciais:

Alimentação
Transporte
Moradia
Lazer
Saúde
Educação
Assinaturas
Outros
O usuário poderá corrigir categorias quando necessário.

3. Metas Financeiras
Permitir criar metas como:

Economizar R$ 5.000.
Montar reserva de emergência.
Juntar dinheiro para viagem.
O sistema acompanhará o progresso automaticamente.

4. Agente Financeiro
Assistente virtual responsável por:

Responder dúvidas simples.
Sugerir economia.
Alertar sobre gastos acima da média.
Incentivar hábitos financeiros saudáveis.
Exemplos:

"Você gastou 25% mais com delivery este mês."

"Sua meta de viagem está 70% concluída."

5. Dashboard Simplificado
Exibir:

Gastos do mês.
Receitas do mês.
Saldo atual.
Categorias que mais consomem orçamento.
Evolução das metas.
Principais Telas
Tela 1 – Onboarding
Apresentação rápida.
Cadastro básico.
Definição da primeira meta financeira.
Tela 2 – Chat Financeiro
Conversa com o assistente.
Registro de receitas e despesas.
Perguntas financeiras.
Tela 3 – Histórico
Lista de transações.
Busca e filtros simples.
Tela 4 – Dashboard
Resumo financeiro.
Gráficos básicos.
Indicadores principais.
Tela 5 – Metas
Criação de metas.
Acompanhamento de progresso.
Requisitos Funcionais
Interface mobile-first.
Linguagem simples.
Tempo de resposta inferior a 3 segundos.
Design acessível para iniciantes.
Segurança básica para dados financeiros.
Métricas de Sucesso
O MVP será considerado validado quando:

80% dos usuários conseguirem registrar um gasto sem ajuda.
Pelo menos 60% retornarem após sete dias.
Mais de 70% considerarem o chat mais fácil que aplicativos tradicionais.
Design Universal e Acessibilidade

O produto deve seguir princípios de Design Universal, garantindo que possa ser utilizado de forma confortável, intuitiva e eficiente pelo maior número possível de pessoas, independentemente de idade, experiência tecnológica, condição cognitiva ou possíveis limitações físicas.

Diretrizes

Interface simples e intuitiva.

Linguagem clara, sem jargões financeiros complexos.

Textos legíveis e com bom contraste.

Navegação consistente em todas as telas.

Ícones acompanhados de texto explicativo.

Compatibilidade com leitores de tela.

Suporte a diferentes tamanhos de fonte.

Não depender exclusivamente de cores para transmitir informações.

Fluxos com o menor número possível de etapas.

Design responsivo para celular, tablet e desktop.

Feedback claro após cada ação realizada pelo usuário.

Objetivo

Permitir que qualquer pessoa consiga registrar despesas, entender sua situação financeira e acompanhar metas sem necessidade de treinamento prévio. ---

Entregável Esperado da IA
Gerar:

Estrutura das telas.
Fluxo de navegação.
Modelo de banco de dados inicial.
Arquitetura sugerida.
Plano de testes do MVP.
Estratégia de validação com primeiros usuários.
Tom: educativo, amigável e acessível. Idioma: Português (Brasil).
```

### Interações com Lovable:
> Crie um app de finanças pessoais com base no seguinte PRD(Product Requirements Document): 
PRD – Assistente de Finanças Pessoais ConversacionalCrie um app de finanças pessoais com base no seguinte PRD(Product Requirements Document): 
PRD – Assistente de Finanças Pessoais Conversacional

> Como você quer que o chat com o assistente funcione?

>Uma conversa contínua

>Onde os dados (transações, metas, conversas) devem ficar salvos?

>Na nuvem, com login

>Os entregáveis escritos (estrutura de telas, fluxo, banco, arquitetura, testes, validação) devem vir em qual formato?

>Documento Markdown
 
>não gostei do tamanho da fonte dos números que selecionei ,pois os números ultrapassam enquadramento dos ícones, poderia ajustar os números de forma que fiquem dentro dos seus respectivos quadrados

Resultado final no Lovable:https://chatty-penny-companion.lovable.app/painel
<img width="1763" height="1023" alt="image" src="https://github.com/user-attachments/assets/3d05ffce-24d7-4a85-9b29-02ef67a77672" />

### Funcionalidades do APP de Organização Financeira(bolso):

💬 Conversa (Assistente Financeiro)

Tela principal de interação com o usuário.

Permite registrar receitas e despesas utilizando linguagem natural, por exemplo:

"Recebi R$ 2.500 de salário."
"Gastei R$ 25 com almoço."
"Paguei R$ 100 em compras."

O assistente interpreta a mensagem, identifica valores, classifica automaticamente a transação e atualiza os indicadores financeiros.

Também pode oferecer:

orientações financeiras;
sugestões de economia;
alertas de gastos;
acompanhamento de metas.
📊 Painel Financeiro

Centraliza os principais indicadores financeiros do usuário.

No print é possível visualizar:

Receitas do mês

Mostra a soma de todas as entradas registradas.

Exemplo:

R$ 2.500,00
Gastos do mês

Mostra o total de despesas registradas.

Exemplo:

R$ 125,00
Saldo do mês

Calcula automaticamente:

Saldo = Receitas - Gastos

Exemplo:

R$ 2.375,00

Além do valor, exibe feedback positivo para reforçar hábitos saudáveis de gestão financeira.

📈 Análise de Gastos por Categoria

Mostra onde o usuário está gastando mais dinheiro.

No exemplo:

Outros → R$ 100 (80%)
Alimentação → R$ 25 (20%)

Essa funcionalidade ajuda o usuário a identificar padrões de consumo rapidamente.

📉 Histórico de Gastos

Gráfico com evolução das despesas ao longo do tempo.

Essa visualização facilita análises sem exigir conhecimento financeiro avançado.

🎯 Metas Financeiras

Permite criar objetivos de economia e acompanhar sua evolução.

Exemplo exibido:

Meta:

Comprar um carro

Progresso:

Objetivo: R$ 5.000
Acumulado: R$ 500
Conclusão: 10%

A funcionalidade incentiva planejamento financeiro de longo prazo.

📚 Histórico

Tela dedicada à consulta de movimentações financeiras registradas.

Potencialmente permite:

visualizar lançamentos anteriores;
pesquisar transações;
aplicar filtros por período;
consultar receitas e despesas.
♿ Recursos de Acessibilidade

No canto inferior esquerdo tem botões de controles para:

tamanho padrão de texto;
aumento de fonte;
aumento máximo de fonte.

##Proposta de Valor

O diferencial do Bolso não é apenas mostrar números.

O verdadeiro valor do produto é:

"Permitir que qualquer pessoa organize suas finanças conversando naturalmente com um assistente financeiro inteligente, sem precisar aprender planilhas, termos técnicos ou processos complexos."

## Reflexão 

### O que funcionou bem?
o refinamento do PRD no Copilot, e o desenvolvimento do APP no Lovable.


### O que não funcionou como o esperado?
esperava que os créditos gratuitos do Lovable ia dar pra concluir o APP, mas ,não deu, tive que pagar 26 reais para poder concluir o APP.

### O que aprendeu sobre conversar com IAs?
aprendi que conversar com as IAs, é como conversar com um amigo ,pois quanto mais detalhes você dá, sobre o o quer que ela faça, melhor e mais assertiva vai ser a resposta 

