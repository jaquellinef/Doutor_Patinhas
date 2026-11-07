# Projeto: Doutor Patinhas — estação para exames rápidos e coleta de sangue

**Versão:** 3.0 — fluxo completo em 12 telas e acessibilidade física e digital  
**Tipo de documento:** proposta de experiência e interface  
**Formato do visor:** horizontal e integrado à cabeça, conforme a maquete; mockups do equipamento em 4:3  
**Etapas:** 12 telas padronizadas; seleção de 1, 2 ou 3 exames na mesma visita, pagamento, coleta, análise e entrega dos resultados  
**Público:** pessoas de diferentes idades e necessidades de acesso  
**Identidade visual:** tecnologia de saúde acolhedora, inspirada em um gato siamês

> **Importante:** este documento descreve uma ideia de produto e de telas. Não é um protocolo médico, não comprova que a coleta automatizada seja segura ou viável e não deve ser usado para construir ou operar um equipamento. Antes de qualquer uso real, o projeto precisa ser avaliado e aprovado por profissionais de saúde, especialistas em engenharia, segurança, privacidade e acessibilidade, além de cumprir as regras aplicáveis.

## 1. A ideia em poucas palavras

A estação orienta a pessoa durante as etapas de uma coleta de sangue. A tela explica o que vai acontecer, informa o que a pessoa precisa fazer e mostra como pedir ajuda. O equipamento pode realizar algumas tarefas programadas, mas a equipe de saúde continua responsável por acompanhar o procedimento e intervir quando necessário.

A pessoa deve conseguir entender rapidamente três coisas: **em que etapa está, o que precisa fazer e como interromper ou pedir ajuda**. Cada tela deve ter uma mensagem principal, uma instrução simples e um botão de ação fácil de encontrar.

A estação não deve iniciar a coleta sem que a pessoa tenha entendido a proposta e autorizado o início. A pessoa deve poder pedir ajuda ou interromper o procedimento. Se houver dúvida, falha, desconforto ou qualquer situação fora do esperado, o processo deve parar com segurança e chamar a equipe de saúde.

## 2. O que a proposta não promete

- Não promete uma coleta sem dor, sem risco ou adequada para todas as pessoas.
- Não substitui a avaliação, a decisão ou a presença da equipe de saúde.
- Não decide sozinha se a pessoa deve fazer um exame.
- Não interpreta resultados nem dá diagnósticos.
- Não presume que todas as pessoas devam estar em jejum ou seguir o mesmo preparo.
- Não deve continuar se a pessoa pedir ajuda, se algo estiver incerto ou se o equipamento indicar uma falha.

## 3. Termos usados neste documento

- **Pessoa:** quem está realizando o exame.
- **Equipe de saúde:** profissional responsável por acompanhar e orientar o procedimento.
- **Estação:** o equipamento automatizado proposto neste projeto.
- **Amostra:** pequena quantidade de sangue coletada para análise.
- **Preparo:** instruções que podem ser necessárias antes do exame, como jejum. O preparo depende do exame e das orientações recebidas.
- **Rastrear a amostra:** acompanhar a identificação e o encaminhamento da amostra para reduzir o risco de troca ou perda.
- **Interromper:** parar o processo de forma controlada. A forma de interrupção precisa ser definida e validada por profissionais e especialistas.
- **Braille:** sistema de leitura por pontos em relevo, percebido pelo toque.
- **Tecla tátil:** botão físico que pode ser encontrado e identificado pelo formato e pelo relevo, sem depender só da tela.
- **Sensor de movimento/posição:** componente que percebe se há uma mão na área de apoio; não serve para identificar a pessoa.
- **Guia da mão:** apoio acolchoado na abertura inferior que ajuda a posicionar a mão sem prendê-la.

## 4. Jornada de atendimento e serviços

### Conceito da estação “Doutor Patinhas”

**Doutor Patinhas** é o nome provisório de uma estação de atendimento instalada em uma farmácia. A ideia é orientar a pessoa, apresentar exames rápidos disponíveis, ajudar no pagamento, explicar a coleta e informar como receber o resultado. O nome e o mascote de gato devem tornar a experiência acolhedora, sem infantilizar adultos ou fazer parecer que o equipamento é um médico.

A pessoa apoia a mão em um suporte indicado na **parte inferior frontal** do equipamento. A tela sensível ao toque fica na **cabeça do gato**, acima da abertura da mão. Uma possibilidade é a coleta de uma pequena amostra de sangue da ponta do dedo; outra é a coleta feita por um profissional, com a estação cuidando da leitura da amostra. Um método sem agulha só deve ser apresentado como opção se existir um exame validado para esse método. O projeto não deve afirmar que uma tecnologia sem agulha funciona para exames de sangue sem evidência e aprovação apropriadas.

A tela inicial pode mostrar **três exames rápidos disponíveis**, mas não existe uma lista universal dos “três exames mais necessários” para todas as pessoas. A seleção deve ser definida pelo serviço e por profissionais habilitados, com base nos exames realmente oferecidos, na demanda local e nas regras aplicáveis. A interface deve dizer para que cada exame serve e quais são seus limites, sem afirmar que a pessoa precisa fazer um exame nem substituir uma avaliação profissional.

**Sobre a verba ampla:** um orçamento alto pode permitir uma equipe multidisciplinar, testes com usuários, protótipos, validação clínica e de engenharia, acessibilidade e manutenção. Não elimina riscos, não substitui evidências e não permite ignorar aprovações ou regras de saúde.

> **Metas iniciais, ainda não comprovadas:** o exemplo de 1 gota/1 minuto, 2 gotas/2 minutos e 3 gotas/3 minutos deve ser tratado apenas como hipótese de projeto. A quantidade necessária e o tempo dependem do exame, do tipo de amostra e do dispositivo de análise. “Gota” também não é uma medida suficientemente precisa para especificar um produto. Cada exame precisa ter seus requisitos confirmados por profissionais, pelo fabricante do teste e pelo processo de validação aplicável. A tela deve mostrar tempos reais e aprovados, não promessas de velocidade.

### 4.1. Seleção do(s) exame(s)

**Objetivo:** permitir que a pessoa veja quais exames estão disponíveis e escolha o que deseja solicitar, sem confundir popularidade com necessidade médica.

**Tela sugerida:** “Quantos exames você quer fazer nesta visita?” A tela apresenta três opções de quantidade — **1 exame**, **2 exames** ou **3 exames** — e depois permite selecionar os exames correspondentes entre até três cartões disponíveis. Os nomes dos exames só devem ser preenchidos depois de decisão clínica e operacional; até lá, usar “Exame 1”, “Exame 2” e “Exame 3” como marcadores de projeto. A proposta é permitir que os exames selecionados sejam processados na mesma visita e, quando validado, em paralelo.

Cada cartão deve informar, em linguagem simples:

- o que o exame verifica e para que costuma ser usado;
- se a amostra é de sangue e como ela é obtida, em termos gerais;
- se há algum preparo ou condição para realizar o exame;
- o tempo estimado de coleta e de análise, separados quando forem diferentes;
- o preço total, incluindo cobranças conhecidas;
- limitações importantes e quando é necessário conversar com a equipe;
- que um teste rápido não substitui automaticamente consulta ou avaliação clínica.

**Escolha combinada:** permitir que a pessoa escolha **1, 2 ou 3 exames para a mesma visita**. A tela mostra claramente quantos foram selecionados e o total a pagar. A análise simultânea dos exames e o uso de uma única coleta só podem ser prometidos para combinações validadas; a quantidade de amostra e o tempo total precisam ser confirmados para cada combinação. Se uma combinação não for compatível, não oferecer essa seleção como simultânea: explicar o limite e chamar a equipe. Não sugerir que a pessoa precisa comprar todos os exames. Se houver dúvida, oferecer **Quero conversar com a equipe**.

**Ação principal:** **Continuar com 1 exame**, **Continuar com 2 exames** ou **Continuar com 3 exames**, conforme a seleção.  
**Ação de apoio:** **Quero conversar com a equipe**.

**Regra para análise em conjunto:** a interface deve indicar que os exames escolhidos serão processados na mesma visita; só usar as expressões “ao mesmo tempo” ou “em paralelo” quando a combinação e o processo tiverem sido validados. O resultado dos exames selecionados deve ser apresentado junto, com o estado de cada um.

**Regra para a interface:** apresentar até três opções na primeira tela para facilitar a escolha; não chamar esses exames de “necessários” sem uma avaliação individual feita por profissional habilitado.

### 4.2. Procedimento de pagamento

**Objetivo:** deixar o preço e as condições claros antes de a pessoa pagar e antes de iniciar a coleta.

**Resumo antes do pagamento:** mostrar os exames escolhidos, o valor de cada um, o valor total, o que está incluído, formas de pagamento disponíveis e as condições aplicáveis se o exame não puder ser realizado ou se a amostra não puder ser analisada. As regras de cancelamento, reembolso ou repetição precisam ser definidas pelo serviço e exibidas antes da confirmação.

**Fluxo sugerido:**

1. A pessoa confere o resumo dos exames e o valor total.
2. A tela explica qualquer preparo ou motivo pelo qual a equipe possa precisar avaliar a solicitação antes da coleta.
3. A pessoa escolhe uma forma de pagamento disponibilizada pela farmácia.
4. A estação confirma o pagamento ou informa, com clareza, que ele não foi concluído.
5. A pessoa recebe um comprovante e segue para as instruções da coleta.

**Cuidados:** não iniciar a coleta sem confirmar pagamento quando o serviço exigir pagamento antecipado. Não mostrar dados financeiros completos na tela pública. Se houver falha no pagamento, explicar como tentar novamente ou pedir ajuda, sem criar uma cobrança duplicada. Se o exame não puder prosseguir, seguir a política de cancelamento ou reembolso que foi informada antes.

**Ação principal:** **Confirmar e pagar**.  
**Ação de apoio:** **Voltar à seleção**, **Preciso de ajuda** ou **Cancelar**, conforme as regras do serviço.

### 4.3. Instruções sobre a coleta do material

**Objetivo:** explicar o que a pessoa vai fazer, como a amostra será obtida e o que acontecerá depois, antes de pedir autorização.

**Mensagem sugerida:** “Veja como a amostra será coletada.” A instrução deve usar palavras comuns, imagens simples e áudio opcional. Informar a parte do corpo envolvida, se a coleta é feita pela própria pessoa ou por um profissional, o tipo geral de material necessário e o que fazer se a pessoa não quiser continuar.

**Alternativas conceituais para a coleta:**

- **Coleta capilar assistida:** um profissional habilitado faz a coleta na ponta do dedo com um dispositivo de uso único e coloca a amostra em um cartucho apropriado. A estação pode ajudar na leitura e no registro.
- **Coleta capilar em módulo fechado:** a pessoa posiciona a mão em um suporte e a estação usa um conjunto estéril descartável, fechado e de uso único. É uma ideia de produto, não uma especificação de engenharia; o mecanismo só poderia ser considerado após comprovação clínica, de segurança e aprovação aplicável.
- **Coleta sem agulha:** só pode ser oferecida se houver uma tecnologia e um exame específicos validados para obter o resultado pretendido. Não apresentar sensores ópticos ou outras ideias como equivalentes a uma amostra de sangue sem evidência.

A pessoa deve ver a explicação antes de posicionar a mão. A instrução visual deve mostrar que a mão entra pela abertura da parte de baixo, na frente do equipamento; não deve sugerir que a mão seja inserida pela lateral ou por cima. A tela de controle fica na cabeça do gato, ao alcance da pessoa. Nenhum mecanismo de perfuração deve ser acionado sem autorização explícita, verificação do sistema e critérios clínicos aprovados. Deve haver equipe disponível para dúvidas, desconforto, falha ou interrupção. O projeto visual não deve mostrar instruções técnicas sobre força, profundidade ou operação de uma agulha.

**Sobre a quantidade e o tempo:** as metas de 1, 2 ou 3 gotas e 1, 2 ou 3 minutos não são garantias. Cada exame deve especificar, com base em validação, o tipo e a quantidade de amostra necessários, o tempo de análise e o que acontece se a amostra for insuficiente ou inválida. A soma de vários exames pode exigir mais amostra ou mais tempo; isso precisa ser confirmado, não presumido.

**Ação principal:** **Entendi e quero continuar**.  
**Ação de apoio:** **Quero falar com a equipe** e **Não quero continuar**.

### 4.4. Entrega do(s) resultado(s)

**Objetivo:** informar quando e como o resultado será disponibilizado, mantendo privacidade e evitando interpretações indevidas.

**Estados possíveis:** **Aguardando análise**, **Em análise**, **Resultado disponível** ou **Precisamos da equipe para revisar**. Mostrar apenas o estado confirmado. Se houver uma estimativa, identificá-la como estimativa e atualizá-la quando necessário.

**Quando o resultado estiver disponível:**

- confirmar que o resultado pertence à pessoa certa antes de exibi-lo ou entregá-lo;
- oferecer apenas os canais aprovados pelo serviço, como retirada segura ou acesso digital protegido;
- apresentar o resultado como informação do exame, explicar unidades e referências somente quando aprovadas pelo laboratório;
- não produzir diagnóstico automático nem dizer que a pessoa está saudável ou doente com base em um resultado isolado;
- encaminhar resultados que exijam contato ou revisão para a equipe, conforme protocolo aprovado;
- explicar com quem falar se o resultado estiver atrasado, inconclusivo ou não puder ser liberado.

**Ação principal:** **Ver resultado**, quando já estiver validado, ou **Entendi — aguardarei**, quando ainda estiver em análise.  
**Ação de apoio:** **Falar com a equipe**.

### 4.5. Informações intermediárias e complementares

**Objetivo:** manter a pessoa orientada antes, durante e depois do atendimento, sem sobrecarregar as telas.

A estação pode apresentar informações curtas no momento em que forem úteis:

- **Antes da escolha:** quais exames estão disponíveis e que a escolha não substitui uma consulta.
- **Antes do pagamento:** preço total, o que está incluído e regras aplicáveis.
- **Antes da coleta:** preparo confirmado, método geral de coleta, duração estimada, possibilidade de desconforto, privacidade e opção de parar.
- **Durante a análise:** estado da amostra, tempo estimado se conhecido e aviso caso seja necessária a equipe.
- **Depois da coleta:** cuidados aprovados para aquele procedimento, como pedir ajuda e como acompanhar o resultado.
- **Em todas as etapas:** opção de leitura em voz alta, texto ampliado, alto contraste, repetição da instrução, idioma disponível e contato com a equipe.

A informação deve ser breve na tela principal. Detalhes adicionais ficam em botões como **Saiba mais**, **Ouvir instruções** ou **Perguntas frequentes**. Evitar conselhos de saúde genéricos que não tenham sido aprovados para o exame e o serviço.

### 4.6. Higiene e atendimento de várias pessoas em sequência

A meta do conceito é permitir que a farmácia atenda uma pessoa após a outra sem reutilizar componentes que entram em contato com sangue. O desenho final do processo deve ser feito e validado por profissionais e especialistas; as orientações abaixo são princípios para o projeto, não um protocolo de limpeza.

- Usar um conjunto novo, estéril e descartável para cada pessoa em toda parte que entre em contato com a pele ou com a amostra, incluindo o dispositivo de punção, quando houver, e o cartucho de análise.
- Nunca reutilizar lancetas, agulhas ou cartuchos de coleta/análise entre pessoas.
- Evitar que sangue ou material usado toque as superfícies limpas, os controles compartilhados ou o próximo conjunto descartável.
- Separar, no projeto, a área de materiais novos da área de descarte de itens usados.
- Projetar superfícies de contato para limpeza conforme instruções validadas pelo fabricante e pelo serviço; definir como a equipe confirma que a limpeza foi feita antes do próximo atendimento.
- Prever descarte apropriado de itens perfurocortantes e materiais usados, conforme os procedimentos e regras aplicáveis ao local.
- Fazer a estação interromper o atendimento se faltar um item descartável, se a embalagem estiver danificada, se o teste do equipamento falhar ou se houver dúvida sobre a limpeza.
- Usar uma identificação exclusiva para cada atendimento e conferir pessoa, pedido, cartucho e resultado, sem expor dados pessoais a quem não tem autorização.
- Manter uma pessoa da equipe treinada disponível para supervisão, dúvidas, falhas, desconforto e situações que precisem de avaliação humana.

**Recomendação para o conceito inicial:** estudar primeiro uma estação assistida ou semiautomática, na qual a máquina orienta, identifica o cartucho e processa a amostra, enquanto a coleta é feita ou supervisionada por um profissional. Uma perfuração totalmente automática pode ser explorada apenas como hipótese de pesquisa e não deve ser tratada como pronta ou segura sem validação clínica e de engenharia.

**Fluxo geral sugerido:** boas-vindas e acessibilidade → escolha dos exames → explicação e preparo → conferência de identidade e pedido → informações de saúde que precisem ser comunicadas à equipe → resumo e pagamento → instruções e autorização da coleta → posicionamento da mão/braço → coleta e análise → conferência humana quando indicada → entrega segura do resultado → orientações finais.

> O fluxo completo está consolidado nas 12 telas padronizadas da seção 8. A seleção, o pagamento, a coleta, a análise, os resultados e as orientações finais estão incluídos nessa sequência.

---

## 5. Padrão visual e de linguagem

### Aparência

- Usar fundo claro, de preferência marfim ou branco suave, com detalhes grafite e azul.
- Seguir a maquete enviada: corpo vertical inspirado em um gato, tela sensível ao toque embutida na parte frontal da cabeça e abertura acolchoada para a mão na parte inferior frontal. A tela não deve ficar na barriga nem na lateral.
- Mostrar “14:23” como hora de exemplo na barra superior da tela da cabeça; isso é a hora do visor, não o tempo do exame.
- Manter o acesso da mão separado do visor: a pessoa lê e escolhe na cabeça do gato e só posiciona a mão na abertura inferior quando a tela orientar.
- Inspirar-se no gato siamês por meio de formas elegantes, olhos azuis e detalhes escuros. O mascote deve ser acolhedor, mas não pode substituir uma explicação médica clara.
- Mostrar uma ilustração grande e simples, sem imagens de sangue ou cenas que possam assustar.
- Manter a mesma posição para o título, a mensagem, o botão principal e o botão de ajuda em todas as telas.
- Usar letras grandes, bom contraste e frases curtas. Evitar textos longos, abreviações e palavras técnicas sem explicação.
- Usar movimentos discretos, sem flashes ou animações que possam incomodar. Deve haver uma opção sem movimento.

### Botões e mensagens

- Exibir uma ação principal por tela, como **Começar** ou **Continuar**.
- Manter **Preciso de ajuda** visível durante todo o processo.
- Mostrar **Interromper agora** nas etapas em que o procedimento estiver em andamento.
- Não usar apenas a cor para indicar se algo está certo ou errado. Combinar texto, ícone e cor.
- Não avançar automaticamente quando a pessoa precisar tomar uma decisão.
- Quando uma etapa estiver acontecendo sozinha, informar o que está ocorrendo e, se houver uma estimativa confiável, quanto tempo pode levar.
- Usar mensagens honestas: só mostrar que uma etapa foi concluída depois de haver confirmação suficiente.

### Opções de acesso

A pessoa deve poder escolher como prefere receber as instruções. **Dois botões com texto — “Áudio” e “Libras” — ficam visíveis em todas as telas**, inclusive nas telas de seleção, pagamento, coleta e resultado. Não depender apenas de desenhos de alto-falante ou mãos. Os botões mostram claramente quando estão ligados ou desligados. As duas opções podem funcionar juntas.

- **Botão Áudio:** ao tocar, lê a instrução da tela em voz alta; permite pausar, repetir, ajustar o volume e desligar. Não inicia som alto sem escolha da pessoa.
- **Botão Libras:** ao tocar, abre uma janela de vídeo com instrução em Língua Brasileira de Sinais, produzida ou revisada por pessoas fluentes e qualificadas. Permite repetir e fechar o vídeo sem cobrir os botões principais. Não representar Libras apenas com um ícone ou avatar não validado.
- Manter legendas e texto escrito mesmo quando o áudio ou Libras estiverem ativados.
- Os controles de acessibilidade não devem esconder **Preciso de ajuda**, **Interromper agora** ou a ação principal.

A pessoa deve poder escolher como prefere receber as instruções. As opções podem incluir:

- **Modo simples:** poucas palavras, ilustrações grandes e instruções passo a passo.
- **Mais detalhes:** explicações adicionais para quem quiser saber mais.
- **Texto ampliado:** letras maiores e mais tempo para ler.
- **Modo calmo:** sem animações e com menos sons.
- **Leitura em voz alta:** a estação lê as instruções, com controle de volume e opção de repetir.
- **Apoio visual:** legendas, ícones claros e instruções que não dependem apenas do som.
- **Alto contraste:** texto e botões mais fáceis de distinguir.
- **Acompanhamento:** possibilidade de pedir ajuda à equipe ou a um acompanhante, conforme as regras do serviço.

### Recursos físicos acessíveis

- Instalar teclas físicas salientes, com formatos e texturas diferentes, ao alcance da pessoa. Usar rótulo escrito e Braille para funções principais: **Áudio**, **Ajuda**, **Voltar**, **Confirmar** e **Parar**. O Braille deve ser revisado por pessoas cegas e por especialistas; não depender somente de pontos decorativos ou de uma tela lisa.
- Dar retorno perceptível quando uma tecla for acionada, como resposta tátil leve e mensagem sonora/visual escolhida pela pessoa. As teclas não podem ser confundidas entre si nem exigir pressão ou precisão excessiva.
- Usar sensores de proximidade para acender a tela quando alguém se aproximar e sensores de movimento/posição para verificar se a mão está na guia inferior. Os sensores não identificam a pessoa, não gravam imagem e não iniciam a coleta.
- Integrar uma guia acolchoada e tátil na abertura inferior frontal. Ela deve ajudar a alinhar e apoiar a mão direita ou esquerda, permanecer aberta para retirada fácil e nunca prender ou empurrar o braço.
- Se a posição ficar incerta, o movimento for inesperado ou a pessoa pedir ajuda, pausar e chamar a equipe; nunca corrigir a posição à força.

Para crianças, usar palavras adequadas à idade, permitir o acompanhamento do responsável e nunca prometer que não haverá dor. A participação de crianças deve seguir as orientações clínicas e as regras aplicáveis.

## 6. Como a navegação deve funcionar

A sequência tem três partes, sempre indicadas na tela:

1. **Preparar** — confirmar as informações necessárias e deixar a pessoa pronta.
2. **Coletar** — explicar o que está acontecendo e permitir pedir ajuda ou interromper.
3. **Finalizar** — conferir como a pessoa está, orientar sobre os próximos passos e informar o que aconteceu com a amostra.

A tela deve mostrar a etapa atual e o que vem a seguir, sem sobrecarregar a pessoa com menus. A estação deve pedir confirmação antes de ações importantes e deixar claro quando a equipe de saúde precisa participar.

### Elementos fixos da interface em todas as telas

- Faixa superior da tela na cabeça do gato: hora ilustrativa **14:23**, botão com texto **Áudio** e botão com texto **Libras**.
- Teclas físicas salientes, com formatos distintos e Braille revisado, para **Áudio**, **Ajuda**, **Voltar**, **Confirmar** e **Parar**; acessíveis sem procurar um ponto exato na tela.
- Botão principal grande; **Preciso de ajuda** sempre visível. Durante a coleta, **Interromper agora** aparece na tela e há uma tecla física de parada.
- Sensor de presença pode ativar a tela de boas-vindas. Sensores de movimento/posição acompanham apenas a mão na guia inferior; não usam câmera, não identificam a pessoa e não iniciam o procedimento.
- Guia acolchoada e tátil na abertura inferior frontal: ajuda a apoiar a mão e permite retirá-la livremente.
- Tela de seleção: três cartões, opção de 1, 2 ou 3 exames e total a pagar.
- Tela de andamento: um status por exame escolhido; só dizer “em paralelo” quando essa combinação estiver validada.
- Tela de resultado: estado individual de cada exame, sem valores médicos fictícios.

**Assunção de interpretação:** “14:23 na cabeça do gato” foi entendido como um relógio pequeno no topo da interface embutida na cabeça; se “14:23” significar outra coisa, o layout pode ser ajustado.

## 7. Regras de segurança que orientam a experiência

Estas regras são princípios do projeto e precisam ser detalhadas e validadas por especialistas antes de qualquer desenvolvimento ou uso:

1. A estação informa quando precisa de ajuda humana e não tenta esconder uma falha.
2. A coleta só pode começar depois das verificações definidas por profissionais e da autorização explícita da pessoa.
3. A pessoa pode pedir ajuda ou interrupção em qualquer momento. Também deve existir uma forma física de interromper o equipamento, definida por especialistas.
4. Se as informações estiverem incompletas, se houver uma leitura incerta ou se o equipamento detectar uma situação inesperada, a estação não deve prosseguir sozinha.
5. A identificação da pessoa, a confirmação do exame e a identificação da amostra precisam ser conferidas de acordo com um processo aprovado pelo serviço de saúde.
6. A biometria não deve ser a única forma de identificação. Deve haver uma alternativa com conferência humana, respeitando a privacidade e as regras do serviço.
7. A orientação sobre jejum e outros preparos deve vir do pedido do exame ou da equipe de saúde. A estação não deve inventar uma regra geral.
8. A amostra só pode ser marcada como identificada, protegida ou encaminhada depois que cada etapa tiver sido confirmada.
9. O curativo automático, se vier a ser desenvolvido, só pode ser usado quando as regras clínicas e a situação da pessoa permitirem.
10. Os resultados só podem ser apresentados depois da validação do laboratório e não devem vir acompanhados de diagnóstico automático.
11. Dados pessoais e de saúde devem ser protegidos e exibidos apenas para quem tiver autorização.
12. As teclas táteis e as marcações em Braille devem ser compreensíveis, seguras e testadas com pessoas cegas e com baixa visão.
13. Sensores de presença ou movimento não devem ser usados para reconhecimento, gravação ou início automático da coleta.
14. A guia física não pode prender, apertar nem forçar a mão; deve permitir retirada fácil e encaminhar qualquer dúvida à equipe.

---

## 8. As 12 telas padronizadas do projeto

As telas abaixo substituem o fluxo anterior de 16 telas. A numeração é a sequência principal da jornada. Os botões **Áudio** e **Libras** ficam disponíveis em todas as telas. As teclas táteis com Braille, a guia da mão e os sensores fazem parte do equipamento físico e complementam a interface visual. Nenhuma tela deve iniciar uma coleta por conta própria.

### Padrão repetido em todas as telas

- **Faixa superior:** marca Doutor Patinhas, hora ilustrativa **14:23**, botão **Áudio** e botão **Libras**.
- **Controles físicos acessíveis:** teclas salientes com formatos distintos e identificação em Braille para funções como **Áudio**, **Ajuda**, **Voltar**, **Confirmar** e **Parar**. A posição, o relevo, o texto e o Braille precisam ser testados com pessoas cegas e com baixa visão.
- **Ajuda:** botão visual e tecla tátil de ajuda sempre acessíveis.
- **Interrupção:** botão visual e controle físico de parada nas etapas de coleta; os dois devem permanecer livres e fáceis de alcançar.
- **Guia da mão:** abertura acolchoada e guia tátil na parte inferior frontal. A guia ajuda a pessoa a apoiar a mão, mas não a prende nem a força.
- **Sensores:** sensores de presença podem ativar a tela de boas-vindas; sensores de movimento/posição podem verificar se a mão permanece na área indicada. Não usar a câmera ou o movimento para identificar a pessoa. Sensores nunca substituem a equipe e, se houver dúvida, a estação pausa e pede ajuda.
- **Feedback:** combinar texto, voz, Libras, símbolos, relevo, vibração leve quando apropriado e sinais luminosos estáveis. Não depender apenas de cor, áudio, visão ou movimento.

### Tela 1 — Boas-vindas e acessibilidade

**Objetivo:** acolher a pessoa, apresentar as formas de acesso e iniciar a jornada somente quando ela quiser.

**Texto principal:** “Bem-vindo ao Doutor Patinhas. Vamos começar?”

**O que aparece:** botões grandes **Áudio**, **Libras**, **Começar** e **Preciso de ajuda**. A hora ilustrativa 14:23 aparece na faixa superior. A guia inferior fica visível, mas a pessoa ainda não insere a mão.

**O que a pessoa faz:** escolhe Áudio e/ou Libras se desejar; depois toca em **Começar** ou usa a tecla física equivalente.

**O que a estação faz:** um sensor de presença pode acender a tela ao perceber alguém próximo, sem identificar nem filmar a pessoa. A estação aguarda o comando para começar.

**Narração:** “Olá. Posso mostrar as instruções em texto, ler em voz alta ou apresentar Libras. Escolha como prefere e toque em começar quando estiver pronto.”

### Tela 2 — Selecionar 1, 2 ou 3 exames

**Objetivo:** deixar a pessoa escolher quantos exames quer fazer na mesma visita e quais exames estão disponíveis.

**Texto principal:** “Escolha 1, 2 ou 3 exames para esta visita.”

**O que aparece:** até três cartões provisórios **Exame 1**, **Exame 2** e **Exame 3**, com espaço para a descrição aprovada de cada opção. A tela mostra claramente a quantidade selecionada: **1 exame**, **2 exames** ou **3 exames**.

**O que a pessoa faz:** seleciona um, dois ou três exames e pode voltar ou pedir ajuda. Não é obrigada a escolher todos.

**O que a estação faz:** verifica se a combinação está disponível. Só apresenta os exames como simultâneos/em paralelo quando a combinação tiver validação; caso contrário, explica o limite e encaminha para a equipe.

**Ação principal:** **Continuar com 1 exame**, **Continuar com 2 exames** ou **Continuar com 3 exames**, conforme a seleção.

**Narração:** “Escolha quantos exames quer fazer nesta visita. Você pode escolher um, dois ou três. Se tiver dúvida, peça ajuda.”

### Tela 3 — Conferir exames, preparo, preço e tempo

**Objetivo:** apresentar um resumo compreensível antes de qualquer pagamento ou coleta.

**Texto principal:** “Confira sua seleção e as orientações.”

**O que aparece:** exames selecionados, para que servem em palavras simples, preparo aprovado para cada exame, tipo geral de amostra, tempo estimado validado e preço total. Quando algum dado ainda depender de confirmação, a tela deve dizer isso em vez de inventar um valor.

**O que a pessoa faz:** confere a seleção e lê ou ouve as instruções. Pode remover um exame, voltar ou falar com a equipe.

**O que a estação faz:** apresenta apenas informações aprovadas pelo serviço. Não recomenda exames automaticamente e não afirma que um exame é necessário para aquela pessoa.

**Ação principal:** **Confirmar seleção**.  
**Ações de apoio:** **Alterar seleção** e **Preciso de ajuda**.

**Narração:** “Confira os exames escolhidos, o preparo, o tempo estimado e o valor. Se alguma informação não estiver clara, fale com a equipe.”

### Tela 4 — Confirmar identidade e informar cuidados

**Objetivo:** confirmar que o atendimento está associado à pessoa certa e dar espaço para avisar a equipe sobre necessidades relevantes.

**Texto principal:** “Vamos confirmar seus dados e seus cuidados.”

**O que aparece:** instrução para conferir os dados no método aprovado pelo serviço e opções privadas para informar alergia, medicamento, tontura anterior, medo, necessidade de acessibilidade ou outro cuidado. Não exibir informação pessoal em local visível a outras pessoas.

**O que a pessoa faz:** confirma os dados e informa o que considerar importante. Pode solicitar ajuda de um profissional.

**O que a estação faz:** oferece alternativa com conferência humana e não depende apenas de biometria. Encaminha à equipe qualquer situação que exija avaliação.

**Ação principal:** **Confirmar dados**.  
**Ações de apoio:** **Quero falar com a equipe** e **Voltar**.

**Narração:** “Confira seus dados e avise se há algo importante para o seu cuidado, como alergia, medicamento ou histórico de tontura. Você também pode falar diretamente com a equipe.”

### Tela 5 — Pagamento

**Objetivo:** permitir que a pessoa confira e conclua o pagamento com preço e condições claros.

**Texto principal:** “Confira o valor antes de pagar.”

**O que aparece:** exames selecionados, preço de cada um, total, formas de pagamento disponíveis e regras de cancelamento, repetição ou reembolso definidas pelo serviço. Não usar preço fictício no protótipo.

**O que a pessoa faz:** escolhe a forma de pagamento, confirma ou volta para alterar a seleção.

**O que a estação faz:** confirma o pagamento sem expor os dados financeiros completos. Se a transação falhar, informa o estado e evita uma cobrança duplicada. Se o exame não puder prosseguir, aplica a política informada previamente.

**Ação principal:** **Confirmar e pagar**.  
**Ações de apoio:** **Voltar** e **Preciso de ajuda**.

**Narração:** “Confira o total e as condições. Se estiver de acordo, escolha uma forma de pagamento. Se precisar, peça ajuda.”

### Tela 6 — Entender a coleta e autorizar a continuação

**Objetivo:** explicar o método planejado, o que a pessoa poderá sentir, como pedir ajuda e quais exames serão processados.

**Texto principal:** “Veja como a coleta será feita.”

**O que aparece:** uma ilustração simples da mão entrando pela abertura inferior frontal, a informação de que a coleta pode envolver desconforto e uma explicação de que a pessoa pode parar. Informar se a coleta será assistida por profissional ou feita por módulo validado. Não mostrar imagens gráficas nem detalhes técnicos da agulha.

**O que a pessoa faz:** lê ou assiste à explicação e decide se quer continuar. A autorização para iniciar a coleta será solicitada novamente na Tela 7.

**O que a estação faz:** responde dúvidas, oferece equipe humana e não presume autorização pelo fato de a pessoa ter pagado.

**Ação principal:** **Entendi, continuar**.  
**Ações de apoio:** **Quero falar com a equipe** e **Não quero continuar**.

**Narração:** “Vou explicar como será a coleta e como pedir ajuda. A coleta pode causar desconforto. Você decide se quer continuar e pode pedir ajuda.”

### Tela 7 — Inserir e apoiar a mão

**Objetivo:** orientar a pessoa a localizar a abertura inferior e apoiar a mão sem esforço ou pressão.

**Texto principal:** “Insira a mão pela abertura de baixo.”

**O que aparece:** desenho da abertura acolchoada na parte inferior frontal, guia física tátil, marcações visuais estáveis e indicação de onde apoiar a mão. O apoio deve servir para mão direita ou esquerda e não deve prender o braço.

**O que a pessoa faz:** segue a guia e posiciona a mão quando estiver pronta. Pode retirá-la sem barreira e chamar a equipe.

**O que a estação faz:** sensores de movimento/posição verificam apenas se a mão está na zona de apoio prevista. Se houver movimento inesperado, posição incerta ou pedido de ajuda, pausa e chama a equipe; nunca empurra nem segura a mão.

**Ação principal:** **Mão apoiada**.  
**Ações de apoio:** **Preciso de ajuda** e **Retirar a mão**.

**Narração:** “A abertura fica na parte de baixo, à sua frente. Apoie a mão na guia confortável. Não force a posição. Se precisar, retire a mão e peça ajuda.”

### Tela 8 — Revisão final e autorização

**Objetivo:** conferir as condições antes do início e pedir autorização explícita para a coleta.

**Texto principal:** “Tudo pronto. Autoriza começar?”

**O que aparece:** resumo curto da identidade confirmada, exames selecionados, pagamento confirmado quando aplicável, posição da mão e disponibilidade da equipe. Só mostrar os itens realmente confirmados.

**O que a pessoa faz:** toca em **Autorizo começar** ou escolhe **Ainda não**. Pode retirar a mão e pedir ajuda.

**O que a estação faz:** não inicia a coleta sem autorização explícita e verificações aprovadas. Sensores não substituem essa confirmação.

**Ação principal:** **Autorizo começar**.  
**Ações de apoio:** **Ainda não**, **Preciso de ajuda** e **Interromper**.

**Narração:** “Confira se está tudo certo. A coleta só começará quando você autorizar. Você pode escolher ainda não ou pedir ajuda.”

### Tela 9 — Coleta em andamento

**Objetivo:** informar que a coleta está ocorrendo e manter a possibilidade de interrupção imediatamente disponível.

**Texto principal:** “Coleta em andamento.”

**O que aparece:** andamento visual simples, áudio e Libras disponíveis, botão **Interromper agora** e botão **Preciso de ajuda**. Mostrar estimativa somente se aprovada e confiável.

**O que a pessoa faz:** mantém a mão apoiada se estiver confortável. Pode interromper ou retirar a mão, conforme orientação do serviço.

**O que a estação faz:** monitora o estado definido no projeto. Se houver falha, movimento inesperado, mal-estar relatado ou incerteza, interrompe com segurança e chama a equipe.

**Narração:** “A coleta está em andamento. Mantenha a mão apoiada se estiver confortável. Você pode interromper ou pedir ajuda a qualquer momento.”

### Tela 10 — Analisar os exames selecionados

**Objetivo:** mostrar o estado de cada exame sem fazer promessas de tempo ou resultado.

**Texto principal:** “Seus exames estão em análise.”

**O que aparece:** um cartão por exame escolhido, com estados separados, como **Em análise**, **Aguardando revisão** ou **Resultado disponível**. Se a combinação tiver sido validada para análise em paralelo, a tela pode indicar isso claramente. Não exibir valores médicos inventados.

**O que a pessoa faz:** acompanha o estado ou pede ajuda.

**O que a estação faz:** mostra somente estados confirmados. Se a amostra for insuficiente, se houver falha ou se algum resultado exigir revisão, encaminha à equipe e informa a pessoa.

**Ação de apoio:** **Preciso de ajuda**.

**Narração:** “Estou mostrando o andamento de cada exame. O tempo pode variar. Se a equipe precisar revisar algo, avisarei nesta tela.”

### Tela 11 — Resultados e como a pessoa está

**Objetivo:** entregar os resultados validados de forma protegida e verificar se a pessoa precisa de apoio antes de sair.

**Texto principal:** “Confira os resultados e como você está.”

**O que aparece:** estado individual de cada exame e botão **Ver resultados** apenas quando liberados e vinculados à pessoa certa. Não incluir diagnóstico automático. A mesma tela pergunta **Como você está se sentindo?** com opções **Estou bem**, **Estou tonto(a)**, **Estou com dor ou desconforto** e **Preciso de ajuda**.

**O que a pessoa faz:** acessa os resultados validados, se disponíveis, e seleciona como está se sentindo. Pode conversar com a equipe.

**O que a estação faz:** protege a privacidade, não apresenta um resultado inconclusivo como definitivo e encaminha relatos de mal-estar ou pedido de ajuda à equipe.

**Ação de apoio:** **Falar com a equipe**.

**Narração:** “Veja apenas os resultados que já foram liberados. Para entender o que significam, converse com um profissional. Como você está se sentindo? Se precisar, peça ajuda.”

### Tela 12 — Orientações e encerramento

**Objetivo:** apresentar cuidados posteriores aprovados e encerrar a visita sem abandonar a pessoa caso ainda precise de ajuda.

**Texto principal:** “Atendimento concluído. Precisa de mais alguma coisa?”

**O que aparece:** instruções pós-coleta aprovadas para os exames selecionados, forma segura de acompanhar resultados ainda pendentes, comprovante e botões **Finalizar** e **Falar com a equipe**. Não usar prazos universais nem recomendações médicas genéricas.

**O que a pessoa faz:** revisa as orientações, confirma que entendeu e finaliza quando estiver pronta.

**O que a estação faz:** encerra somente quando não houver alerta ou solicitação de ajuda em aberto. Mantém o canal de apoio visível até a finalização.

**Narração:** “Siga as orientações indicadas para você. Se algum resultado ainda estiver pendente, acompanhe pelo canal informado. Obrigado; a equipe está disponível se precisar de ajuda.”

---

## 9. Lista de verificação antes de testar a proposta

### Clareza e facilidade de uso

- Pessoas conseguem dizer em que etapa estão e o que devem fazer?
- As instruções são compreendidas sem explicação técnica?
- Cada tela tem uma ação principal clara?
- Os botões de ajuda e interrupção são fáceis de encontrar?
- A pessoa consegue ouvir, ler novamente ou pedir ajuda?

### Segurança e acompanhamento

- A coleta não começa sem confirmação do processo e autorização explícita?
- A pessoa sabe que pode pedir ajuda ou interromper?
- Existe um procedimento validado para chamar a equipe e interromper o equipamento?
- A estação para quando as informações forem incertas ou algo sair do esperado?
- A equipe de saúde sabe quando precisa intervir?
- A tela evita dizer que está tudo bem sem confirmação suficiente?

### Acesso para diferentes pessoas

- As telas funcionam para pessoas com diferentes idades e níveis de leitura?
- O texto pode ser ampliado e lido em voz alta?
- As instruções são compreensíveis sem depender apenas de cor, som ou movimento?
- Há legendas, alto contraste e uma opção sem animações?
- Crianças são acompanhadas conforme as regras clínicas e aplicáveis?
- As pessoas conseguem usar a interface sem movimentos muito precisos?
- As teclas físicas têm formas distintas, rótulos em Braille corretos e retorno perceptível?
- Pessoas cegas ou com baixa visão conseguem encontrar áudio, ajuda, confirmação e parada sem depender apenas da tela?
- Os sensores funcionam sem câmera ou identificação e nunca iniciam a coleta?
- A guia inferior apoia mãos direitas e esquerdas sem prender ou forçar o braço?

### Privacidade e informação

- Os dados pessoais ficam protegidos e não aparecem para pessoas sem autorização?
- Há uma alternativa à identificação biométrica?
- A estação explica de forma simples como a amostra será identificada e encaminhada?
- As instruções de preparo e os cuidados posteriores foram revisados pelo serviço de saúde?
- Os resultados são apresentados apenas após validação do laboratório e sem diagnóstico automático?

### Testes e desenvolvimento

- Testar os textos e as telas com pessoas de diferentes idades e necessidades, sempre com os cuidados apropriados.
- Fazer avaliação clínica, de engenharia, segurança, privacidade, acessibilidade e facilidade de uso antes de qualquer teste real.
- Testar falhas, pedidos de ajuda, interrupção, perda de energia e situações em que a estação não consegue confirmar uma etapa.
- Projetar a carcaça e os materiais para permitir limpeza, manutenção, acesso da equipe e interrupção segura. A aparência de gato não pode atrapalhar nenhuma dessas funções.
- Não testar uma coleta em pessoas até que os responsáveis e especialistas tenham definido e aprovado todos os requisitos necessários.

---

## 10. Prompts refinados e separados para desenvolvimento do conceito

Os prompts abaixo podem ser usados separadamente. Em todos eles, manter o mesmo limite: produzir um conceito de experiência e design, não um protocolo clínico nem instruções para construir um mecanismo de punção. O orçamento amplo pode ser considerado para pesquisa e validação, mas não elimina riscos, regras ou necessidade de aprovação.

### Prompt 1 — Conceito geral do produto

> Desenvolva o conceito de uma estação chamada **Doutor Patinhas**, planejada para uma farmácia e destinada a orientar pessoas durante a seleção e a realização de exames rápidos. O visual pode ser acolhedor e inspirado em um gato siamês, mas deve ser profissional e adequado também a adultos e pessoas idosas. Explique a proposta em linguagem simples para pessoas sem conhecimento técnico. Descreva o público, o problema que a estação pretende resolver, os limites do produto, a presença e o papel da equipe de saúde e a jornada geral da pessoa. Não afirme que a estação substitui um médico ou laboratório, não prometa ausência de dor ou risco e não crie diagnósticos. Trate o projeto como uma hipótese que precisa de avaliação clínica, de engenharia, segurança, acessibilidade, privacidade e conformidade com as regras aplicáveis. Considere um orçamento amplo para montar uma equipe multidisciplinar e testar o conceito, mas não use “verba infinita” como justificativa para ignorar validação ou segurança. Entregue: resumo do conceito, benefícios possíveis, riscos e questões ainda não resolvidas.

### Prompt 2 — Seleção de exames e pagamento

> Crie o fluxo de telas do **Doutor Patinhas** para seleção de exames e pagamento. A tela deve permitir que a pessoa escolha fazer **1 exame, 2 exames ou 3 exames na mesma visita**. Apresente até três cartões selecionáveis, usando “Exame 1”, “Exame 2” e “Exame 3” como espaços provisórios até que a lista seja aprovada por profissionais e pelo serviço. Mostre o número selecionado e o valor total. Trate a análise em paralelo e o uso de uma única coleta como possibilidades, não como garantias: só as ofereça para combinações validadas. Em cada cartão, reservar espaço para: o que o exame verifica, preparo confirmado, tipo geral de amostra, tempo real validado, preço e limitações. Permitir escolher um ou mais exames apenas se a combinação estiver validada; nunca dizer que uma pessoa precisa comprar um exame nem recomendar automaticamente um exame. Depois, criar uma tela de resumo com preço total, regras de pagamento, o que está incluído e o que acontece se o exame não puder prosseguir. Usar português brasileiro simples, frases curtas, botões grandes e opções “Quero conversar com a equipe”, “Voltar” e “Preciso de ajuda”. Entregue o texto de cada tela, a ordem do fluxo, os estados de erro e os pontos que precisam de decisão do serviço.

### Prompt 3 — Explicação da coleta e higiene

> Desenhe, apenas no nível de conceito de produto e experiência, como o **Doutor Patinhas** pode explicar uma coleta de pequena amostra de sangue e atender várias pessoas em sequência em uma farmácia. Compare três caminhos: (1) coleta capilar feita por profissional com material descartável; (2) estação semiautomática que usa cartucho individual de uso único e mantém um profissional disponível; (3) tecnologia sem agulha, somente se houver um exame específico validado para ela. Para cada caminho, explique a experiência da pessoa, vantagens, limites, riscos que precisam de avaliação e dependências de validação. Priorize no conceito inicial uma solução assistida ou semiautomática, sem apresentar perfuração automática como tecnologia pronta. Inclua os princípios de separar materiais limpos e usados, não reutilizar partes que tocam a pele ou o sangue, descartar materiais de maneira apropriada, limpar superfícies conforme procedimentos validados, identificar cada atendimento e interromper o processo diante de qualquer falha. Não forneça profundidade, força, ângulo, desenho de mecanismo de agulha nem instruções para fabricar ou operar o coletor. Trate 1/2/3 gotas e 1/2/3 minutos como metas hipotéticas a confirmar para cada exame, nunca como promessa. Entregue um quadro comparativo e uma lista de perguntas para a equipe clínica e de engenharia.

### Prompt 4 — Entrega dos resultados e informações complementares

> Escreva a experiência do **Doutor Patinhas** para manter a pessoa informada entre a coleta e a entrega do resultado. Inclua estados simples (“Aguardando análise”, “Em análise”, “Resultado disponível” e “Precisamos da equipe para revisar”), formas de acesso protegidas, opção de falar com a equipe, mensagens para atraso ou amostra inválida e orientações finais aprovadas pelo serviço. Não invente prazos, faixas de referência, interpretação clínica ou recomendações de tratamento. Não dê diagnósticos automáticos nem conclua que a pessoa está saudável ou doente. Explique, em português brasileiro simples, que o resultado deve ser entendido com apoio profissional quando necessário. Entregue os textos de tela, as notificações intermediárias, os botões e as situações que devem ser encaminhadas a um profissional.

### Prompt 5 — Protótipo visual e teste com pessoas

> Produza uma série padronizada de **12 telas individuais** para o Doutor Patinhas, usando a maquete enviada como referência. Em todas, preserve o equipamento vertical em forma de gato siamês, o visor touchscreen na cabeça, a hora ilustrativa “14:23” e a abertura para a mão na parte inferior frontal. Mantenha sempre visíveis os botões digitais “Áudio” e “Libras”, e inclua no equipamento teclas físicas salientes com formas diferentes e identificação em Braille para Áudio, Ajuda, Voltar, Confirmar e Parar. Mostre sensores discretos de presença/posição e uma guia acolchoada e tátil na abertura inferior; não desenhe câmera, identificação biométrica, agulha, sangue ou mecanismo técnico de punção. As 12 telas devem seguir esta ordem: (1) boas-vindas e acessibilidade; (2) selecionar 1, 2 ou 3 exames; (3) conferir exames, preparo, preço e tempo; (4) confirmar identidade e informar cuidados; (5) pagamento; (6) entender a coleta e autorizar continuação; (7) inserir e apoiar a mão; (8) revisão final e autorização explícita; (9) coleta em andamento; (10) análise individual dos exames escolhidos; (11) resultados protegidos e como a pessoa está; (12) orientações e encerramento. Use português brasileiro, textos curtos, alto contraste, botões grandes, legenda e estados claros. Cada imagem é um mockup conceitual, não um software funcional. Não invente nomes de exames, preços, tempos garantidos, valores médicos ou diagnósticos. Teste compreensão, Braille e controles físicos com pessoas com deficiência visual e com diferentes necessidades de acesso, sem fazer teste clínico como parte do protótipo visual.

## 11. Série visual: 12 telas do projeto

A série final terá uma imagem independente para cada tela, mantendo a maquete, a interface e os recursos acessíveis padronizados. Todas as imagens são conceitos visuais, não representam um equipamento funcional ou clinicamente validado.

**Referência física de acessibilidade:** [ver imagem do equipamento com controles táteis, Braille, sensores e guia inferior](</home/ubuntu/Doutor_Patinhas_Acessivel_Master.png>).

### Arquivos individuais

1. [Tela 1 — Boas-vindas e acessibilidade](</home/ubuntu/Doutor_Patinhas_Tela_01_BoasVindas.png>)
2. [Tela 2 — Seleção de 1, 2 ou 3 exames](</home/ubuntu/Doutor_Patinhas_Tela_02_Selecao.png>)
3. [Tela 3 — Conferir seleção e preparo](</home/ubuntu/Doutor_Patinhas_Tela_03_Resumo.png>)
4. [Tela 4 — Confirmar identidade e cuidados](</home/ubuntu/Doutor_Patinhas_Tela_04_Identidade.png>)
5. [Tela 5 — Pagamento](</home/ubuntu/Doutor_Patinhas_Tela_05_Pagamento.png>)
6. [Tela 6 — Entender a coleta](</home/ubuntu/Doutor_Patinhas_Tela_06_Entenda_Coleta.png>)
7. [Tela 7 — Inserir e apoiar a mão](</home/ubuntu/Doutor_Patinhas_Tela_07_Guia_Mao.png>)
8. [Tela 8 — Revisão final e autorização](</home/ubuntu/Doutor_Patinhas_Tela_08_Autorizacao.png>)
9. [Tela 9 — Coleta em andamento](</home/ubuntu/Doutor_Patinhas_Tela_09_Coleta.png>)
10. [Tela 10 — Análise dos exames](</home/ubuntu/Doutor_Patinhas_Tela_10_Analise.png>)
11. [Tela 11 — Resultados](</home/ubuntu/Doutor_Patinhas_Tela_11_Resultados.png>)
12. [Tela 12 — Orientações e encerramento](</home/ubuntu/Doutor_Patinhas_Tela_12_Encerramento.png>)

