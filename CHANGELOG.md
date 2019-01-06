# SIG Change Log

## 0.01.06
- Criado arquivo Changelog no github
- Corrigido erro ao baixar várias contas com status parcialmente pago
- Adicionado opção de deletar, cancelar e ativar conta a pagar/receber recorrente
## 0.01.05
- Retirada url das imagens referenciadas do site lorempixel
- Preenchendo os campos created_at e updated_at no seeder das empresas
- Corrigido bug no cadastro contas bancárias, não deixava cadastrar uma conta como padrão para receitas e despesas.
## 0.01.04
- Opção de dar baixa em várias contas ao mesmo tempo
- Retirado botões de imprimir e excluir (não utilizados) nos cadastros de usuários, groupos e permissões
## 0.01.03
- Organizado as contas a pagar e receber pela data de vencimento e data de emissão
- Validando dados antes de gravar as contas recorrentes
## 0.01.02
- Corrigido erro na data de vencimento ao gerar contas a partir de contas recorrentes
- Criado controller das contas recorrentes herdado por contas a pagar e receber recorrentes
- Alterado o campo dia de vencimento conta recorrente de date para number(visualmente)
## 0.01.01
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
