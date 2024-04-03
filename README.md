# aic-abertura-release 


## Objetivo 

O objetivo principal de uma abertura de release automática é aumentar a eficiência e a confiabilidade do processo. Com a automação, o tempo necessário para abrir uma nova release é reduzido, garantindo uma abertura consistente e padronizada. Ao liberar os desenvolvedores dessa tarefa manual, eles podem se concentrar em atividades mais complexas e de maior valor, aumentando a eficiência geral do desenvolvimento da equipe.


## Índice

- <a href="#-tecnologias-utilizadas"> Tecnologias Utilizadas</a>

- <a href="#-funcionalidade-da-aplicacao"> Funcionalidade da Aplicação</a>

- <a href="#-possiveis-problemas"> Possíveis Problemas</a>

- <a href="#-fluxograma-de-testes">Fluxograma de Testes</a>

- <a href="#-status-do-projeto"> Status do Projeto</a>



## Tecnologias Utilizadas

- Java
- Cucumber 
- JUnit 

## Funcionalidade da Aplicação

1. Acessa o [fontes](https:fontes.intranet.bb.com.br) e entra com a chave e senha cadastrada.

2. Localiza o Projeto designado no fontes: "aic / aic-helloworld-java / prd-aic-helloworld-java".

3. Seleciona o projeto mencionado e clica na opção "README", edita o mesmo e clica no botão "Commit Changes".

4. Preenche o título com "# Release Teste 2", logo após clica em "Write" e preenche o MR com "22/08/2023 12:00", então clica no botão "Assign to me" e por fim clica no botão "Create merge request".

5. Acessa o [alfred](https://alfred.ci.intranet.bb.com.br/login). Faz o login no alfred com chave e senha cadastrada, clica no botão "público" e por fim clica no botão "Release Engine" para verificar o build. 

6. Acessa a [plataforma](https://plataforma.atendimento.bb.com.br:49286/estatico/gaw/app/spas/index/index.app.html?cd_modo_uso=19#/), no menu à esquerda, clica em "Construção", logo após em "Release de Software", depois verificar as informações da abertura da release.


## Possíveis Problemas 

Há vários possíveis problemas que podem surgir durante o fluxo descrito para a abertura de release. Seguem alguns possíveis erros:

Instabilidade das Ferramentas: As ferramentas utilizadas no processo (fontes, alfred e plataforma) podem enfrentar problemas técnicos, como lentidão, falhas de conexão ou até mesmo estar fora do ar temporariamente, o que pode impedir a conclusão do fluxo.

Mudanças na Interface ou Fluxo das Ferramentas: Caso haja mudanças na interface ou no fluxo de uso das ferramentas utilizadas, os passos automatizados descritos podem não funcionar conforme o esperado, exigindo alguns ajustes no script.

***


## Fluxograma de Testes 

![DIAGRAMA_](/uploads/3057da92cf57a6bd24210eeedb3e1eb1/DIAGRAMA_.png)


## Status do Projeto

- Status do Projeto - Pendências de Disparo Automático e Configurações de Aviso para o Plumbers.  
- Objetivo: Implementar disparo automático de notificações e configurar alertas para garantir o funcionamento adequado do sistema.
- Situação Atual: A implementação do disparo automático de notificações está parcialmente concluída, faltando apenas ajustes finais.


## Próximos Passos

Concluir a implementação do disparo automático. Finalizar as configurações de alertas e avisos conforme a necessidade.









