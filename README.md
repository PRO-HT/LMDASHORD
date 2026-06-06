 1. Dashboard
Objetivo: visão geral rápida de tudo que você cadastrou.

O que mostra:

Produtos — quantidade total cadastrada
Custo total — soma dos custos de todos os produtos
Receita estimada — preço final calculado com a margem de cada produto
Lucro estimado — diferença entre receita e custo
Tabela de produtos: lista nome, fornecedor, origem, custo, margem, preço final, links (JoomPulse, fornecedor, ML) e botões para editar ou excluir.

Observação: o Dashboard não tem botão “Limpar tudo” — ele só reflete os dados dos outros tópicos.

2. Adicionar produto
Objetivo: cadastrar produtos que você pretende vender ou já está analisando.

Campos principais:

Nome, fornecedor, WhatsApp/contato
Origem: Nacional, China, Importado ou Outros
Links: JoomPulse, fornecedor e anúncio no Mercado Livre
Custo (R$) e Margem desejada (%) — o preço final é calculado automaticamente
Funcionalidades:

Salvar produto — adiciona à lista
Editar — clique no ✏️ no Dashboard ou na Planilha
Limpar tudo — apaga todos os produtos cadastrados (com confirmação)
3. Margem estratégica
Objetivo: calcular a margem real de lucro considerando impostos, comissão do ML e outros custos — com base na metodologia Nathan Ritter (Simples Nacional com alíquota variável por faixa de RBT12).

Campos de entrada:

Campo	Descrição
Preço de venda
Valor que o cliente paga
Custo do produto
Quanto você paga ao fornecedor
Tipo de anúncio
Clássico (12%) ou Premium (17%) — altera a comissão automaticamente
Regime tributário
CPF (sem nota), Simples Nacional ou alíquota fixa
Faturamento 12m (RBT12)
Usado para calcular a alíquota efetiva no Simples
Frete vendedor
Aplicado quando o preço ≥ R$ 79
Custos fixos/embalagem
Embalagem, etiqueta, etc.
Resultado:

Status: Margem Baixa (<15%), Margem OK (15–20%) ou Excelente (>20%)
Breakdown detalhado: preço − custo − comissão − imposto − frete = lucro líquido
Histórico das simulações salvas (até 50)
▲ Minimizar filtros — esconde o formulário para ver melhor o resultado
Limpar tudo — apaga histórico + formulário + resultado
4. Calculadora ML
Objetivo: simulações rápidas de lucro por produto, com histórico automático.

Campos:

Nome da simulação (ex.: “Caneca personalizada”)
Preço, custo, comissão ML (%), imposto (%)
Custo extra por unidade e frete vendedor
Resultado: lucro em R$ e margem em %. Simulações ficam salvas e podem ser editadas depois.

Diferença da Margem estratégica: aqui o imposto é informado manualmente (%), sem cálculo automático do Simples Nacional.

5. Validação de produto
Objetivo: analisar se um produto tem vendas consistentes (estilo JoomPulse) antes de investir nele.

Campos:

Nome do produto
GMV mensal (R$) — volume bruto de vendas
Média de vendas/mês
Histórico mensal — vendas separadas por vírgula (ex.: 80,95,110,100,120,140)
Análise automática:

Gráfico de barras — evolução mês a mês
CV (Coeficiente de Variação) — mede estabilidade das vendas
Tendência — inclinação positiva ou negativa
Status: Tendência Positiva (válido) ou Vendas Instáveis (arriscado)
Critério: tendência positiva quando a inclinação é positiva e CV < 35%.

6. JoomPulse Análise
Objetivo: importar e analisar dados exportados do JoomPulse (ferramenta de pesquisa de produtos no ML).

Como usar:

Exporte um Excel no JoomPulse
Clique em Importar Excel JoomPulse ou arraste o arquivo na zona de upload
Importações seguintes somam aos dados existentes (não substituem)
Colunas esperadas: Nome, Link, ID_MLB, Receita_Media, Media_Vendas, Total_Vendas, Categoria, Preco, Vendedor, Marca

Filtros e ferramentas:

Recurso	Função
Cards de categoria
Clique para filtrar (Casa, Ferramentas, etc.)
Dropdown Categoria
Filtro por categoria específica
Busca
Por nome, ID ou vendedor
Ordenação
Receita, vendas, preço, nome
Paginação
25, 50, 100 ou todos
Exportar tudo
Baixa todos os dados acumulados
Exportar filtrados
Baixa só o que está visível na tela
Limpar tudo
Remove todos os dados importados
Estatísticas: total de produtos, categorias, receita média e importações acumuladas.

7. Simulador Ads
Objetivo: projetar retorno de investimento em anúncios pagos (Mercado Ads).

Campos:

Orçamento Ads (R$) — quanto você vai investir
ROAS esperado — retorno sobre investimento (ex.: 4x = R$ 4 de receita para cada R$ 1 investido)
Ticket médio (R$) — valor médio por venda
Margem líquida (%) — margem real após todos os custos
Resultado calculado:

Receita projetada = Orçamento × ROAS
Vendas estimadas = Receita ÷ Ticket médio
Lucro líquido real = (Receita × Margem) − Orçamento Ads
8. Missão: conta verde
Objetivo: acompanhar as 10 primeiras vendas para destravar reputação no Mercado Livre (conta verde).

Componentes:

Grid de progresso — clique nos números 1–10 para marcar vendas concluídas
Checklist “Destraves rápidos”:
Preço de Ativação (Lucro Zero)
Anúncio Premium
Envios no mesmo dia
Fotos Reais Fundos Brancos
Limpar tudo reseta progresso e checklist.

9. Planilha Online
Objetivo: visão consolidada em formato de planilha de todos os dados gerados nos outros tópicos.

Abas disponíveis:

Aba	Conteúdo
Produtos
Cadastro completo com links e data
Cálculos de Margem
Histórico da margem estratégica
Calculadora ML
Simulações salvas
Validações
Análises de produto com status
Ações:

Exportar para Excel — gera .xlsx com 4 abas (Produtos, Margem, Calculadora, Validações)
Importar Excel — junta produtos novos aos existentes (não apaga os antigos)
Limpar tudo — apaga produtos, margens, calculadora e validações de uma vez
Abrir Google Drive — link para pasta de backup na nuvem
Recursos comuns em vários tópicos
Botão “Limpar tudo”
Presente em todos os tópicos exceto o Dashboard. Sempre pede confirmação antes de apagar.

Minimizar filtros (▲ / ▼)
Nos tópicos com formulários (Margem, Calculadora, Validação, Ads, JoomPulse), o botão ao lado do título:

Minimiza o painel de filtros/formulário
Amplia a área de resultados (modo foco)
A preferência fica salva no navegador
Persistência de dados
Tudo fica no localStorage. Ao fechar e reabrir o arquivo HTML, os dados continuam lá (no mesmo navegador).

Fluxo sugerido de uso
JoomPulse Análise
Validação de produto
Adicionar produto
Margem estratégica
Calculadora ML
Simulador Ads
Planilha Online / Exportar
Missão conta verde
Primeiras 10 vendas
Pesquisar produtos no JoomPulse → importar no painel
Validar constância de vendas
Cadastrar produtos promissores
Calcular margem real com impostos
Simular escala com Ads
Exportar tudo na Planilha Online
Acompanhar as 10 primeiras vendas na Missão conta verde
