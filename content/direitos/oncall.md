---
title: "Oncall ou o famoso plantão"
date: 2020-07-25T12:26:50+01:00
draft: false
description: "O que é o plantão? Quais direitos? Como funciona?"
author:
  name: Era
  site: https://www.anarchist.work
tags:
---

Quando se trabalha no desenvolvimento de algum produto com clientes externos é comum a prática do "oncall" (plantão). O formato varia de time para time mesmo dentro da mesma empresa. Importante notar que indiferente da empresa, ela ainda precisa seguir o [Organisation of Working Time Act, 1997](http://www.irishstatutebook.ie/eli/1997/act/20/enacted/en/html).

Nas duas empresas que trabalhei na Irlanda, elas me forneceram celular (para eu instalar o aplicativo que notifica de problemas em produção). Na Amazon, o formato do meu oncall era de 8 horas por dia, pois o plantão era divido entre o time nos EUA, Austrália e Europa. Todo final de semana que ficavamos oncall era recompensado com dois dias de folga. Independente do tempo que gastamos ativamente trabalhando. Esses dias podiam ser retirados a qualquer momento.

Outros amigos que ficavam oncall por 24 horas na Amazon recebiam um extra financeiro.

Na Stripe o formato do oncall é de 24 horas também, mas sem nenhum incentivo financeiro. Porém as horas trabalhadas podem ser recuperadas. Por exemplo: recebi uma notificação que tenho que trabalhar e demorou uma hora para consertar o problema, então tenho direito de pegar uma hora em algum outro dia.

Um ponto importante da lei irlandesa é que todo empregado tem o direito de 11 horas consecutivas de descanso em um período de 24 horas ("11.—An employee shall be entitled to a rest period of not less than 11 consecutive hours in each period of 24 hours during which he or she works for his or her employer"). Então se eu for acordado meia-noite, eu deveria começar a trabalhar no outro dia pelo menos as 11 horas da manhã.

Nas duas empresas, estar de plantão nunca significou resolver o problema sozinho, mas avaliar o que está acontecendo. Se você consegue resolver, ótimo, mas caso não saiba ou precise de ajuda dado o volume de problemas, sempre há um caminho claro de quem você deve notificar. No geral, o conselho era: se em dúvida, notifica outra pessoa.

Normalmente as soluções ou dicas de como debugar o problema estão em documentações internas, "runbooks", essas documentações normalmente explicam como confirmar qual o problema e possíveis soluções.

A melhor dica para o plantão é: mantenha a calma, procure o runbook ou uma ocorrência do problema no passado, em caso de dúvida, "escale" o problema.