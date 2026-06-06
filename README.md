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


SCRIPT TAMPERMOONKEY ( Remove Blur + Remove Card )  

// ==UserScript==
// @name         Remove Blur + Remove Card
// @namespace    http://tampermonkey.net/
// @version      1.0
// @description  Remove blur e blocos específicos no JoomPulse
// @match        *://joompulse.com/*
// @grant        none
// ==/UserScript==

(function () {
    'use strict';

    function limpar() {

        // Remove a classe "blur" de TODOS os elementos
        document.querySelectorAll('.blur').forEach(el => {
            el.classList.remove('blur');
        });

        // Remove os blocos que possuem essa classe
        document
            .querySelectorAll('.jsx-59aa2464da0f164c.description')
            .forEach(el => {

                const bloco = el.parentElement;

                if (bloco) {
                    bloco.remove();
                }

            });

    }

    limpar();

    setInterval(limpar, 300);

})();



SCRIPT TAMPERMOONKEY ( Exportador XLSX Completo  )   


// ==UserScript==
// @name         JoomPulse Exportador XLSX Completo
// @namespace    https://joompulse.com/
// @version      1.1
// @description  Exporta automaticamente todas as páginas para XLSX com imagens
// @match        https://joompulse.com/*
// @grant        none
// @require      https://cdnjs.cloudflare.com/ajax/libs/xlsx/0.18.5/xlsx.full.min.js
// ==/UserScript==

(function () {
    'use strict';

    let executando = false;
    let parar = false;
    let produtos = [];
    let idsColetados = new Set();

    function sleep(ms) {
        return new Promise(resolve => setTimeout(resolve, ms));
    }

    function limpar(texto) {
        return (texto || '')
            .replace(/\n/g, ' ')
            .replace(/\s+/g, ' ')
            .trim();
    }

    function atualizarStatus(msg) {
        const el = document.getElementById('jp-status');

        if (el) {
            el.textContent = msg;
        }
    }

    function criarInterface() {

        if (document.getElementById('jp-exportar')) {
            return;
        }

        const exportar = document.createElement('button');

        exportar.id = 'jp-exportar';
        exportar.innerText = '📊 Exportar Tudo';

        exportar.style.cssText = `
            position:fixed;
            right:20px;
            bottom:80px;
            z-index:999999;
            padding:12px;
            border:none;
            border-radius:8px;
            cursor:pointer;
            font-weight:bold;
            background:#198754;
            color:white;
        `;

        const stop = document.createElement('button');

        stop.id = 'jp-stop';
        stop.innerText = '⛔ STOP';

        stop.style.cssText = `
            position:fixed;
            right:20px;
            bottom:30px;
            z-index:999999;
            padding:12px;
            border:none;
            border-radius:8px;
            cursor:pointer;
            font-weight:bold;
            background:#dc3545;
            color:white;
        `;

        const status = document.createElement('div');

        status.id = 'jp-status';

        status.style.cssText = `
            position:fixed;
            right:20px;
            bottom:140px;
            z-index:999999;
            background:#fff;
            border:1px solid #ccc;
            padding:10px;
            border-radius:8px;
            min-width:300px;
            font-size:12px;
            box-shadow:0 0 10px rgba(0,0,0,.2);
        `;

        status.textContent = 'Pronto';

        document.body.appendChild(exportar);
        document.body.appendChild(stop);
        document.body.appendChild(status);

        exportar.addEventListener(
            'click',
            iniciarExportacao
        );

        stop.addEventListener('click', () => {

            parar = true;

            atualizarStatus(
                'Parando exportação...'
            );
        });
    }

    function obterPaginaAtual() {

        const ativa = document.querySelector(
            '.ant-pagination-item-active a'
        );

        return ativa
            ? parseInt(ativa.textContent.trim())
            : 1;
    }
        function coletarProdutosDaPagina() {

        const linhas = document.querySelectorAll(
            'tr.ant-table-row'
        );

        let adicionados = 0;

        linhas.forEach(linha => {

            const colunas =
                linha.querySelectorAll('td');

            if (colunas.length < 11) {
                return;
            }

            const linkEl =
                colunas[3].querySelector('a');

            if (!linkEl) {
                return;
            }

            const nome =
                limpar(linkEl.textContent);

            const href =
                linkEl.getAttribute('href') || '';

            const link =
                'https://joompulse.com' + href;

            // CAPTURA DA IMAGEM
            const imagemUrl =
                linha.querySelector(
                    'img[alt="product"]'
                )?.src || '';

            const idMLB =
                limpar(
                    colunas[3]
                    .querySelector('.subtitle')
                    ?.textContent
                );

            if (!idMLB) {
                return;
            }

            if (idsColetados.has(idMLB)) {
                return;
            }

            idsColetados.add(idMLB);

            const receita =
                limpar(
                    colunas[4]
                    .innerText
                    .replace(
                        'Catálogo total',
                        ''
                    )
                );

            const mediaVendas =
                limpar(
                    colunas[5]
                    .innerText
                    .replace(
                        'Catálogo total',
                        ''
                    )
                );

            const totalVendas =
                limpar(
                    colunas[6]
                    .innerText
                    .replace(
                        'Catálogo total',
                        ''
                    )
                );

            const categoria =
                limpar(
                    colunas[7].innerText
                );

            const preco =
                limpar(
                    colunas[8].innerText
                );

            const vendedor =
                limpar(
                    colunas[9].innerText
                );

            const marca =
                limpar(
                    colunas[10].innerText
                );

            produtos.push({

                Nome: nome,

                Link: link,

                Imagem_URL: imagemUrl,

                ID_MLB: idMLB,

                Receita_Media: receita,

                Media_Vendas: mediaVendas,

                Total_Vendas: totalVendas,

                Categoria: categoria,

                Preco: preco,

                Vendedor: vendedor,

                Marca: marca,

                Pagina: obterPaginaAtual()
            });

            adicionados++;
        });

        return adicionados;
    }
        async function esperarTrocaPagina(nomeAnterior) {

        const inicio = Date.now();

        while (Date.now() - inicio < 30000) {

            if (parar) {
                return false;
            }

            const primeiro =
                document.querySelector(
                    'tr.ant-table-row td:nth-child(4) a'
                );

            const nomeAtual =
                primeiro
                    ? primeiro.textContent.trim()
                    : '';

            if (
                nomeAtual &&
                nomeAtual !== nomeAnterior
            ) {

                await sleep(1000);

                return true;
            }

            await sleep(500);
        }

        return false;
    }

    async function irParaProximaPagina() {

        const botao =
            document.querySelector(
                'li.ant-pagination-next'
            );

        if (!botao) {

            atualizarStatus(
                'Botão próxima página não encontrado'
            );

            return false;
        }

        if (
            botao.classList.contains(
                'ant-pagination-disabled'
            )
        ) {

            atualizarStatus(
                'Última página alcançada'
            );

            return false;
        }

        const primeiro =
            document.querySelector(
                'tr.ant-table-row td:nth-child(4) a'
            );

        const nomeAnterior =
            primeiro
                ? primeiro.textContent.trim()
                : '';

        botao.click();

        atualizarStatus(
            'Carregando próxima página...'
        );

        return await esperarTrocaPagina(
            nomeAnterior
        );
    }

    async function iniciarExportacao() {

        if (executando) {
            return;
        }

        executando = true;
        parar = false;

        produtos = [];
        idsColetados.clear();

        try {

            while (true) {

                if (parar) {

                    atualizarStatus(
                        'Exportação interrompida'
                    );

                    break;
                }

                const pagina =
                    obterPaginaAtual();

                atualizarStatus(
                    `Página ${pagina} | Coletados: ${produtos.length}`
                );

                const adicionados =
                    coletarProdutosDaPagina();

                atualizarStatus(
                    `Página ${pagina} | +${adicionados} produtos | Total: ${produtos.length}`
                );

                if (parar) {
                    break;
                }

                const sucesso =
                    await irParaProximaPagina();

                if (!sucesso) {
                    break;
                }

                await sleep(1500);
            }

        } catch (erro) {

            console.error(
                'Erro durante exportação:',
                erro
            );

            atualizarStatus(
                'Erro durante exportação'
            );

        } finally {

            gerarExcel();

            executando = false;
        }
    }    function gerarExcel() {

        atualizarStatus(
            'Gerando XLSX...'
        );

        const ws =
            XLSX.utils.json_to_sheet(produtos);

        // Ajuste largura das colunas
        ws['!cols'] = [
            { wch: 50 }, // Nome
            { wch: 60 }, // Link
            { wch: 60 }, // Imagem_URL
            { wch: 20 }, // ID_MLB
            { wch: 20 }, // Receita
            { wch: 20 }, // Média vendas
            { wch: 20 }, // Total vendas
            { wch: 35 }, // Categoria
            { wch: 15 }, // Preço
            { wch: 30 }, // Vendedor
            { wch: 25 }, // Marca
            { wch: 10 }  // Página
        ];

        const wb =
            XLSX.utils.book_new();

        XLSX.utils.book_append_sheet(
            wb,
            ws,
            'Produtos'
        );

        const range =
            XLSX.utils.decode_range(
                ws['!ref']
            );

        // Coluna B = Link
        // Coluna C = Imagem_URL

        for (
            let r = 1;
            r <= range.e.r;
            r++
        ) {

            const linkCell =
                XLSX.utils.encode_cell({
                    r,
                    c: 1
                });

            const imagemCell =
                XLSX.utils.encode_cell({
                    r,
                    c: 2
                });

            if (
                ws[linkCell] &&
                ws[linkCell].v
            ) {

                ws[linkCell].l = {
                    Target:
                        ws[linkCell].v
                };
            }

            if (
                ws[imagemCell] &&
                ws[imagemCell].v
            ) {

                ws[imagemCell].l = {
                    Target:
                        ws[imagemCell].v
                };
            }
        }

        const nomeArquivo =
            `JoomPulse_${new Date()
                .toISOString()
                .replace(/[:.]/g, '-')
            }.xlsx`;

        XLSX.writeFile(
            wb,
            nomeArquivo
        );

        atualizarStatus(
            `Concluído! ${produtos.length} produtos exportados`
        );

        console.log(
            'Exportação finalizada:',
            produtos.length
        );
    }

    const observer =
        new MutationObserver(() => {

            criarInterface();

        });

    observer.observe(
        document.body,
        {
            childList: true,
            subtree: true
        }
    );

    criarInterface();

})();
