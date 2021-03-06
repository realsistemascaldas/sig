# SIG Change Log

[![Waffle.io - Columns and their card count](https://badge.waffle.io/realsistemascaldas/sig.svg?columns=all)](https://waffle.io/realsistemascaldas/sig)
## 2.02.09
- Correções de bugs e melhorias:
  - Cadastro de pessoas
  - Cadastro de usuários
  - Entrada de mercadorias
  - Pedidos
  - Contas recorrentes
  - Fluxo de caixa
## 2.02.07
- Correções de bugs e melhorias:
  - Listagem contas a pagar e receber
  - Cadastros contas a pagar e receber
  - Fluxo de caixa
## 2.02.05
- Correções de bugs e melhorias:
  - Entrada de mercadorias
  - Pedidos
  - Contas a pagar
  - Contas a receber
## 2.01.28
- Correcao de pequenos bugs
## 2.01.26
- Criação do relatório de contas a receber
- Melhorado o fluxo de caixa, pequenos detalhes
## 2.01.12
- Tela que mostra as comissões dos vendedores
- Vendas >> Comissões
## 2.01.01
- Gerando números corretamente para os produtos
- Gravando o total dos produtos na entrada de mercadorias e pedidos
- Mostrando preço de venda ao inves de compra nos pedidos
## 1.12.22
- Criado tela de pedidos
- Criado tabela de comissões
## 1.12.10
- Adicionado relatório de serviços das frotas
- Criado as telas de cadastro de vendedores
## 1.11.07
- Adicionado funcionalidade de impressão para PDF
## 1.10.11
- Entrada na entrada de mercadorias:
- Tratando quando adicionar um produto sem nome na entrada de notas
- Calculando total ao buscar produto no autocomplete
- Somando ipi e icms-st ao valor total da nota
- Calculando o total do icms e ipi ao adicionar um produto
- Autocomplete transportadoras
## 1.9.15
- Criado relatório de entrada de mercadorias
- Verificando se nota está cancelada antes de testar duplicidade
- Lançando o valor total da nota como uma duplicata, quando não encontrar parcelas na Nota Fiscal de entrada
- Usando storage para armazenar as imagens dos produtos, usuários e pessoas
## 1.8.26
- Opção de cancelar uma nota fiscal
- Opção de estonar os pagamentos lançados no financeiro de uma nota fiscal
- Opção de estornar os produtos lançados no estoque de uma nota fiscal
- Opção de trazer todas a movimentações de um produto no estoque na tela de entrada/saida
## 1.8.22
- Correção de pequenos bugs nos relatórios
- Gerando o relatório de saldo de estoque
- Criação do relatório de movimentações estoque
- Criaçao dos menus de relatorios
## 1.8.12
- Criaçao e listagem de serviços dos veiculos funcionando
## 1.8.11
- Confimando antes de importar uma nota fiscal de entrada por xml
- Criação da tabela de serviços das frotas
- Mudança das telas de listagem e cadastro de serviço das frotas
## 1.8.09.001
- Desabilitada a rota de registrar novo usuário
- Melhorias no design de algumas telas
- Verificando se escolheu um arquivo xml válido
## 1.8.08
- Melhorado design de algumas telas nos dispositivos mobile
## 1.8.07
- Corrigido erro na importação do xml (tratando a falta de fornecedor e de duplicatas)
- Adicionado campo margem de lucro na tela de cadastro de produtos
- Gerando código do produto automaticamente
- Botoes separados para entrada e saida produtos na tela que mostra as movimentacoes do estoque
Pedindo confirmacao antes de cadastrar uma nota manual
## 1.8.06
- Função de substituir produto na entrada de nota fiscal por xml
- Corrigido erro que não armazenava o número da duplicata das notas de entrada
- Novo layout tela da tela que mostra as entradas de mercadorias
- Controle de frotas
- Cadastro de veiculos
- Cadastro de tipos de serviços feitos nos veículos
## 1.8.04.001
- Criada tela para mostrar as notas fiscais de entrada
- Melhoria nos alertas de quantidade mínima e máxima de estoque
- Retirado painel de controle lateral
## 1.8.04
- Opção para lançar no estoque e no financeiro automaticamente ao importar o xml
## 1.8.03
- Cadastro de veículos (Gerenciamento de frotas)
- Correções na importação de notas por xml
- Corrigido erro que mostrava todas as opções do menu quando tinha uma # no endereço
- #40 #84
## 1.8.02
- Importação de notas fiscais de entrada por xml funcionando
- Corrigido bug na geração de estatisticas (calculo dos últimos 6 meses)
- Melhoria nas telas de entrada de notas e importação de xml (entrada notas)
## 1.7.22
- Criada tela que lê arquivo xml de entrada nota fiscal
## 1.7.18
- Criado as telas de entradas de mercadorias
## 1.4.30
- Correção de bug que não permitia o cadastro de contas a pagar e contas a receber

## 1.4.28
- Criado cadastro rápido de pessoas (CRP)
- Utilizando CRP no cadastro de contas a pagar
- Utilizando CRP no cadastro de contas a pagar recorrentes
- Utilizando CRP no cadastro de contas a receber
- Utilizando CRP no cadastro de contas a receber recorrentes
- Utilizando o gitlab para hospedar as features, contagem praticamente reiniciou
- Melhorada a aparência do botão de cadastro rápido
- #54 #63
## 1.02.01.001
-	Gerando fluxo de caixa de meses anteriores e posteriores
-	Retirado opção do cadastro de permissões
-	#37 #130
## 1.02 Estável (Permissões e transferência entre contas)
-	Corrigido erro que não ativava o menu lateral ao criar ou editar um registro
-	Mostrando a soma das entradas nos detalhes do fluxo de caixa
-	#22 #55
## 1.01.27
-	Retirados cadastros da liderseg
-	#103
## 1.01.23
-	Criado página de acesso não autorizado
-	Corrigido erro no cadastro grupos
-	Melhorado cadastro de grupos
-	#106 #125
## 1.01.20
- Não deletar registros predefinidos sistema
- Verificando relacionamentos antes de deletar:
  Categoria financeira, categoria pessoa, bairro,
  cidade, estado, categoria de produto e forma de pagamento
- #63 #107 #116 #117
## 1.01.17
-	Transferência entre contas
-	Possibilidade de cadastrar uma conta parcelada como paga
-	#46 #127
## 1.01.15.0001
-	Corrigido erro no cadastro de contas a receber recorrente
-	#126
## 1.01.15
- Corrigido permissões extrato financeiro
- Corrigido permissões fluxo de caixa
- Criado permissões para transferência entre contas
- Criado permissões para dar baixa, cancelar conta e imprimir recibo
- Criada permissão para cancelar uma conta recorrente
- Criadas permissões para o estoque e gerar contrato
- Corrigido seeder de geração das categorias financeiras
- Utilizando permissões na tela de fluxo de caixa, extrato, remessa e retorno
- Criadas as permissões para imprimir de todos os itens do sistema
- Criado campo para armazenar o tipo da permissão facilitando sua ordenação
- #120 #119 #123 #114 #115 #110 #112 #101
## 1.01.13
-	Utilizando permissões nas opções de editar e deletar da view Table
-	Utilizando permissões nos cadastros de grupos de usuários, permissões e usuários
-	Utilizando permissões nos cadastros de contas bancárias, categorias de pessoas e pessoas
-	Utilizando permissões nos cadastros de categorias de produtos, pessoas e formas de pagamento
-	Utilizando permissões nos cadastros de centro de custos e categoria financeira
-	Utilizando permissões nos cadastros de contas a pagar e contas a pagar recorrentes
-	Utilizando permissões nos cadastros de contas a receber e contas a receber recorrentes
-	Opção de deletar grupos de usuários, permissões, usuários e contas bancárias
-	Opção de deletar cidades, estados, bairros e categoria de pessoas e formas de pagamento
-	Opção de deletar categoria de produtos, centro de custos e categoria financeira
-	#99 #92 #97 #100 #102 #108 #109 #118
## 1.01.12
-	Corrigido bug que não alterava o tipo de documento de uma conta recorrente
-	Utilizando permissões nos cadastros de bairros, cidades e estados
-	#104 #98
## 1.01.09
- Criada todas as permissões do sistema
- Utilizando permissões nos menus
## 1.01.07
- Criado tela de extrato financeiro
## 1.01.06
- Criado arquivo Changelog no github
- Corrigido erro ao baixar várias contas com status parcialmente pago
- Adicionado opção de deletar, cancelar e ativar conta a pagar/receber recorrente
## 1.01.05
- Retirada url das imagens referenciadas do site lorempixel
- Preenchendo os campos created_at e updated_at no seeder das empresas
- Corrigido bug no cadastro contas bancárias, não deixava cadastrar uma conta como padrão para receitas e despesas.
## 1.01.04
- Opção de dar baixa em várias contas ao mesmo tempo
- Retirado botões de imprimir e excluir (não utilizados) nos cadastros de usuários, groupos e permissões
## 1.01.03
- Organizado as contas a pagar e receber pela data de vencimento e data de emissão
- Validando dados antes de gravar as contas recorrentes
## 1.01.02
- Corrigido erro na data de vencimento ao gerar contas a partir de contas recorrentes
- Criado controller das contas recorrentes herdado por contas a pagar e receber recorrentes
- Alterado o campo dia de vencimento conta recorrente de date para number(visualmente)
## 1.01.01
- Cadastro rápido de bairros
## 0.12.29
- Cadastro rápido de cidades
- Corrigido erro na filtragem de cidades ao escolher um estado cad. pessoas
## 0.12.28
- Retirado menu da vigilância
- Invertido o gráfico receita x despesas do painel controle
- Retirado o sinal de (-) do valor pago, na listagem de contas a pagar e receber
## 0.12.25
- Mostrando o valor pago acrescido dos juros, descontos e acréscimos na listagem de contas a pagar e receber
- Corrigido contagem de pagamentos de uma conta a pagar ou receber
- Mostrando o campo obs dos pagamentos das contas a receber
- Adição de totalizador dos valores de pagamentos (valor pago + juros + acréscimo - desconto) conta a pagar ou receber
## 0.12.23
- Não permite dar baixa em contas canceladas
- Buscando pessoas pelo nome ou nome fantasia no autocomplete
- Corrigido a categoria financeira 'Commissão Vendedores'
- Mostrando o valor pago abaixo do valor da conta na listagem de contas a pagar e receber
- Possibilidade de cadastrar uma conta com o status de paga
- Corrigido erro que não mostrava tela de baixa quando uma conta estava parcialmente paga
## 0.08.07
- Cadastrando centro de custo como ativo
- Ao clicar no valor da conta o mesmo é copiado para o campo valor pago na baixa de contas
- Corrigido erro na geração de estatísticas (saldo atual) do fluxo de caixa
- Corrigido erro na geração de estatísticas receitas e despesas atuais do fluxo de caixa
## 0.08.05
- Corrigido erro na geração de estatísticas do painel de controle
- Criado tela para adicionar informações sobre os serviços
- Criação da tabela de serviços municipais padrões da lc 116/13
- Adição dos campos de impostos aproximados na tabela de produtos
- Adição do campo para armazenar token do IBPT
## 0.07.16
- Mostrando contas previstas no fluxo de caixa
- Retirado campo type da migration de pessoas
- Corrigido bug ao gerar estatísticas do painel de controle
- Corrigido bug que mostrava contas recorrentes na listagem de contas a pagar
- Corrigido bug na geração de fluxo de caixa
- Corrigido bug Botão voltar das contas recorrentes que entrava em loop e não saia da página
- Na listagem de contas, dando ênfase na descrição ao invés da categoria
- Mostrando dois status quando a conta está parcialmente paga e vencida ao mesmo tempo
- Mostrando nomes de pessoas físicas de forma correta na listagem de pessoas
- Tirando algumas regras de negócios dos controllers e levando para os models
## 0.07.11
- Ordenando arquivos de remessa pela data de criação
- Corrigido bug que mostrava contas canceladas como atrasadas.
- Mostrando nome do cliente na listagem de contas atrasadas do painel de controle
- Mostrando descrição da conta no label ao editar ao invés de 'Novo'
- Colocado links para os produtos, cliente e contas listados no painel de controle
## 0.07.09
- Corrigido bug ao gerar estatisticas do painel de controle - indice de array inválido
## 0.07.07
- Deletado os controllers de cliente, funcionários e fornecedores
- Criado componente para mostrar o status das contas
- Consertado títulos no cadastro de contas a pagar (de clientes para fornecedores)
- Mostrando 20 registros nas listagens
- Só recarrega a listagem de clientes quando é gerado um contrato 
- Adicionado o campo nota fiscal para geração de contratos
- Corrigido títulos de alguns botões de cadastros. Cadastrar(Novo)/Salvar(Update)
## 0.07.06
- Alterando título campo Cpf/Cnpj de acordo com o tipo de pessoa escolhido
- Corrigido mensagem de erro no contas a pagar quando não selecionava o fornecedor
- Corrigido máscara de telefone no cadastro de pessoas
- Corrigido erro ao tentar cadastrar uma empresa como isenta
- Mostrando nome fantasia das empresa na listagem de pessoas
- Retirado campo tipo da tabela de pessoas
## 0.06.29
- Possibilidade de criar e armazenar contratos a partir de templates
- Gerado pagamentos ao processar arquivo de retorno
- Retirado obrigatoriedade de preencher ponto de referência
- Criado campo descrição na tabela de arquivos
- Criado campo valor do contrato na configuração da empresa
## 0.06.24
- Fluxo de caixa funcionando para o mês atual
- Arrumado formatação de valores no painel de controle
- Adicionado máscaras na tela de baixar conta
- Corrigido bug que não gravava quando um produto estava inativo
- Corrigido bug que não gravava quando uma pessoa era pessoa física
- Mostrando data de vencimento das contas a receber atrasadas no painel administrativo
- Trocado cor do status de pago parcialmente
- Colocado algumas estatísticas no painel de controle
## 0.06.23
- Mostrando mais dados da empresa no painel administrativo
- Buscando contas pelo nome do cliente ou descrição da conta
- Não permite imprimir boleto com status diferente de aberto
- Consertado erro de redirecionamento quando ficava muito tempo sem mexer no sistema
- Mostrando valor pago na listagem de contas a pagar e receber
- Arrumado labels do cadastro de formas de pagamento
- Arrumado máscaras cadastro contas a pagar
- Arrumado máscaras contas a receber- 
- Arrumado máscaras cadastro contas bancárias
- Arrumado máscaras cadastro produtos
- Arrumado as máscaras no cadastro de pessoas
## 0.06.21
- Criada a tabela de recebimentos para armazenenar os pagamentos das contas
- Criado BillController para as funções interentes a contas a pagar e receber
- Buscando produtos na listagem por nome ou código
- Buscando pessoas na listagem por nome, nome fantasia ou cpf_cnpj
- Unificação dos cadastros de Clientes, Fornecedores e Funcionários (Cadastro de pessoas)
- Verificando se já há pessoa cadastrada com mesmo cpf/cnpj (somento na inserção)
- Verificando se já há produto cadastrado com mesmo nome ou código (somento na inserção)
- Importação de produtos da Nobre Ferragista
## 0.06.19
- Layout Fluxo de caixa
- Verificando se já há produto cadastrado com mesmo nome ou código
- Mudando classificação para serviço quando tipo do produto for serviço
- Autocomplete no campo bairro do cadastro de pessoas
- Colocado algumas estatísticas no painel de controle
- Consertado erro no cálculo das estatisticas
## 0.06.16
- Tela de cancelar nota
- Marcando boleto para geração de remessa ao cancelar, dar baixa e/ou alterar data vencimento
- Mostrando dados de desconta no boleto, caso haja
- Retirado capitalize(primeira letra maiúscula) do nome dos produtos
- Fornecedor não é mais obrigatório
## 0.06.14
- Cadastro de produtos: table, listagem, adição e edição de produtos
- Campo site não é mais obrigatório
- Criação das tabela de estoque
- Criação da listagem de movimentações no estoque
- Criação da tela de movimentar estoque
## 0.06.03
- Mostrando dados de juros e multa no boleto
- Logradouro e ponto de referência podem ser maiúsculos
- Alterado campos para o tipo number cadastro de contas bancárias
## 0.06.02
- Mostrando valores decimais na baixa de conta
- Pedindo confirmação de baixa parcial
- Arrumado a contagem dos registros na table, sempre iniciava do 1 mesmo em outras páginas 
- Recibo contas a pagar

Real Sistemas 2018-2019
