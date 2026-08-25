# BlastZap


<!-- blastzap-latest-download:start -->
[![Baixar ultima versao](https://img.shields.io/github/v/release/wendelgomesdev/blastzap?label=LATEST&style=flat-square&color=20c000)](https://github.com/wendelgomesdev/blastzap/releases/download/2.5.0/BlastZap-2.5.0-Instalador.exe)
- **Versao atual:** 2.5.0
<!-- blastzap-latest-download:end -->
- **Plataforma:** Windows
- **Tipo:** automação desktop para WhatsApp Web

O BlastZap e um aplicativo para organizar contatos, campanhas e disparos pelo WhatsApp Web em uma interface simples e direta. Ele foi criado para ajudar empresas, prestadores de servico e equipes comerciais a gerenciar listas de contatos, preparar mensagens personalizadas e acompanhar o andamento dos envios com mais controle.

## Principais Recursos

- Interface desktop em terminal interativo.
- Cadastro e gerenciamento de contas de WhatsApp.
- Organização de listas de contatos com busca, edição, remoção e importação.
- Importação de contatos por arquivos, incluindo planilhas de Excel e CSV.
- Suporte a variaveis nas mensagens, usando o formato `$nome_da_variavel$`.
- Criação de campanhas com listas de contatos, conta de WhatsApp, mensagens, imagens e audios.
- Envio de mensagens em massa com acompanhamento em tempo real.
- Mensagens aleatorias por campanha.
- Mensagens quebradas em blocos.
- Envio de imagens com legenda.
- Envio de audio usando gravação simulada pelo WhatsApp Web.
- Programação de mensagens para datas especificas.
- Controle de limite diario de disparos por conta.
- Troca automatica de conta quando o limite configurado for atingido.
- Exportação de listas de contatos em formatos como Excel, CSV e JSON.
- Notificacoes no Windows ao finalizar tarefas.

## Novidades da Versao 2.0.0

A versao 2.0.0 marca uma evolução importante do BlastZap: o programa deixou de depender apenas de entradas pelo CMD e passou a contar com uma interface mais organizada, visual e operacional.

Esta versao tambem adiciona melhorias importantes para o uso profissional:

- Interface com navegação por menus.
- Logs de atividade em tempo real.
- Barra de progresso para tarefas.
- Campanhas com mensagens, contatos e contas vinculadas.
- Controle de contas de WhatsApp por licenca.
- Limites de disparo para reduzir riscos operacionais.
- Mensagens programadas.
- Suporte a imagens, legendas, audios e variaveis.
- Encerramento mais seguro dos processos do navegador.

## Como Funciona

O BlastZap utiliza o WhatsApp Web no navegador para executar as tarefas. O usuario cadastra suas contas, importa ou cria listas de contatos, monta campanhas e inicia os disparos pela interface do programa.

Durante a execução, o aplicativo mostra o status da tarefa, logs de atividade e progresso.

## Licenca e Ativação

O uso do BlastZap pode exigir uma licenca ativa. A ativação e feita dentro do menu de configuracoes do programa.

A licenca pode controlar:

- Ativação do dispositivo.
- Limite mensal de mensagens.
- Quantidade de contas de WhatsApp vinculadas.
- Validade do plano contratado.

## Requisitos

- Windows 10 ou superior.
- Conexao com a internet.
- Uma conta de WhatsApp ativa (de preferência WhatsApp Business).
- Acesso ao WhatsApp Web.
- Licenca valida.

## Uso Responsavel

O BlastZap e uma ferramenta de automação. O usuario e responsavel pelo uso correto da ferramenta e deve respeitar:

- As politicas do WhatsApp.
- A legislação aplicavel sobre mensagens e privacidade.
- O consentimento dos contatos.
- Boas praticas de comunicação comercial.

O uso excessivo, repetitivo ou sem autorização dos destinatarios pode gerar bloqueios, restricoes de conta ou problemas legais.

## Suporte

Em caso de duvidas, erros ou necessidade de configuração, entre em contato com o responsavel pelo fornecimento da sua licenca.

Ao relatar um problema, informe:

- Versao do BlastZap.
- Etapa onde o erro ocorreu.
- Mensagem exibida no log.
- Tipo de conta usada no WhatsApp.
- Se possivel, um print da tela.

## Aviso

O BlastZap não é afiliado, associado ou endossado pelo WhatsApp ou Meta. WhatsApp e WhatsApp Web sao marcas de seus respectivos proprietarios.

<!-- blastzap-latest-changes:start -->
## Novidades da versao 2.5.0

### Novidades

- Melhorias Gerais:
- Cada card de Disparos programados agora possui o botão Reprogramar.
- Nova tela de Desempenho da campanha, com funil de enviados, respostas, classificações e resultados positivos.
- Comparação individual das mensagens para identificar quais geram melhores resultados.
- Análise de desempenho opcional, com resultados como respostas, interesse, agendamentos, vendas, reativação ou um resultado personalizado.
- IA capaz de avaliar automaticamente se a resposta do contato representa um resultado positivo para a campanha.
- Otimização automática das mensagens.
- Modelos prontos de organização: Básico, Funil comercial completo e Atendimento.
- Opção Montar minhas categorias, permitindo definir tipos de resposta e suas respectivas listas.
- Botão Reprogramar nos cards de disparos programados, utilizando o calendário.
- Programações na fila agora podem ser retiradas, editadas, reprogramadas e reativadas antes de iniciarem.
- Novo canal nas configurações para enviar sugestões ou reclamações ao suporte, disponível para clientes licenciados.
- Tela de Contas de WhatsApp reformulada com cards, pesquisa, filtros e paginação.
- Opção para excluir contas de WhatsApp, com transferência segura das campanhas e programações vinculadas.
- Disparos avulsos (Agora chamado de Disparos Express) agora permitem mensagens com imagens, vídeos, áudios e arquivos.
- Nova opção para forçar o envio de qualquer mídia como arquivo.
- Novo menu de contexto em campos de texto, com opções para copiar, colar, recortar, desfazer, selecionar tudo e limpar campo.
- Menu de contexto também pode ser aberto pela tecla de menu do teclado ou `Shift + F10`.
- Telas com alterações não salvas agora avisam o usuário antes de sair sem salvar.
- Listas de Contatos:
- Listas de contatos agora podem ser organizadas em pastas.
- É possível criar, editar, abrir e excluir pastas de listas.
- Dentro de uma lista, agora existe uma tela para transferir contatos entre listas.
- É possível copiar, mover ou criar uma nova lista a partir de contatos selecionados.
- Importação de contatos foi simplificada: a coluna obrigatória principal é o telefone.
- Após coletar contatos de grupos ou etiquetas, o programa sugere o próximo passo, como usar em campanha ou ir para a lista criada.
- Campanhas e Públicos:
- Nova opção para criar públicos a partir dos resultados de uma campanha, como responderam, não responderam, leram, receberam, converteram ou foram classificados.
- Na criação de campanha, agora é possível usar um público gerado por outra campanha como lista de contatos.
- Em Disparos Express, também é possível usar públicos de campanhas anteriores como destino.
- Nova opção “Próxima campanha”, que permite criar automaticamente uma nova campanha ao final da janela de resposta da campanha atual.
- A próxima campanha pode ser criada para públicos como clientes que responderam ou clientes que não responderam.
- A próxima campanha já pode ficar programada automaticamente para uma data e horário definidos.
- A criação da próxima campanha respeita o fim real da campanha e a janela de resposta, evitando remarketing antes da hora.
- Botão “Ir para lista” na criação da campanha permite editar a lista selecionada e voltar mantendo os dados já preenchidos.
- Botão de reset de contatos foi levado para o contexto da campanha, evitando afetar outras campanhas que usam a mesma lista.
- Resultados da campanha agora podem ter as métricas resetadas para recomeçar a análise daquela campanha.
- Disparos Express:
- “Disparos avulsos” passou a se chamar Disparos Express.
- Disparos Express agora permitem cadastrar uma lista de mensagens e sortear variações, como nas campanhas.
- A tela de Disparos Express recebeu os mesmos atalhos de montagem de mensagem usados nas campanhas, como quebra, saudação e variações.
- Métricas e Relatórios:
- Entregas e leituras detectadas passam a ser registradas como métricas informativas da campanha.
- Dados de entregue/lido ajudam o usuário a analisar alcance, mas não alteram o ranking das mensagens.
- Relatórios de campanha podem ser exportados em HTML, CSV, JSON e texto.
- Relatórios podem ser enviados ou agendados para envio pelo próprio programa.
- Inicialização, Atualizações e Notificações:
- Nova opção para abrir o programa junto com o Windows direto na bandeja, sem abrir a tela principal.
- Programa ganhou melhorias para continuar rodando em segundo plano e processar automações pendentes.
- Buffer de respostas adicionado para juntar mensagens picadas do cliente antes de classificar ou executar ações.
<!-- blastzap-latest-changes:end -->
