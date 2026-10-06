<div style="display: flex; justify-content: flex-end; align-items: center; gap: 8px; margin: 10px 0;">
  <span style="font-size: 14px; color: #555; font-weight: bold;">Tamanho do texto:</span>
  <button onclick="diminuirFonte()" title="Diminuir texto" style="padding: 6px 12px; font-weight: bold; cursor: pointer; border: 1px solid #ccc; border-radius: 4px; background: #f8f9fa;">A-</button>
  <button onclick="resetarFonte()" title="Tamanho normal" style="padding: 6px 12px; font-weight: bold; cursor: pointer; border: 1px solid #ccc; border-radius: 4px; background: #f8f9fa;">A</button>
  <button onclick="aumentarFonte()" title="Aumentar texto" style="padding: 6px 12px; font-weight: bold; cursor: pointer; border: 1px solid #ccc; border-radius: 4px; background: #f8f9fa;">A+</button>
  
  <button onclick="window.print()" style="background-color: #0056b3; color: white; padding: 6px 16px; border: none; border-radius: 5px; font-size: 14px; cursor: pointer; box-shadow: 0 2px 4px rgba(0,0,0,0.2); margin-left: 10px;">
    🖨️ Imprimir ou baixar esta página
  </button>
</div>

# 1. ACESSO E AUTENTICAÇÃO

**Passo 01:** Acesse o Portal de compras do governo federal: [https://www.compras.gov.br](https://www.compras.gov.br).

**Passo 02:** No canto superior esquerdo, localize o ícone com três linhas.

![Tela Ícone Menu](Imagens/AA.png)

**Passo 03:** Ao clicar, será exibido um menu lateral. Nele, arraste o cursor até a opção “Sistemas”, depois “Compras.gov.br” e, em seguida, “Pesquisa de Preços”.

![Tela Menu Sistemas](Imagens/BB.png)

**Passo 04:** Na página do Pesquisa de Preços, clique no botão “Pesquisa de Preços Lite”.

**Passo 05:** Caso deseje recuperar pesquisas anteriores ou garantir que sua nova consulta fique salva, clique em "Entrar com GOV.BR" no canto superior direito e faça a autenticação com seu CPF e senha.

![Tela Entrar com Gov BR](Imagens/PPLite-1A.png)

**Passo 06 (Recuperação):** Após o login, a página inicial exibirá a lista "Minhas Pesquisas". Para recuperar uma consulta salva anteriormente e continuar a edição ou emitir relatórios, localize a pesquisa desejada e clique no ícone de "Abrir/Visualizar" (ou no título da pesquisa).

![Tela Minhas Pesquisas](Imagens/PPLite-1B.png)

!!! note "Nota"
    Caso deseje iniciar uma pesquisa do zero (com ou sem login), clique no botão "Nova Pesquisa" e siga para os passos seguintes.

<br>
# 2. NOVA PESQUISA E ADIÇÃO DE ITENS

**Passo 07:** Preencha as informações básicas da consulta como título e observações e clique em “Itens”.

![Tela Informações Básicas](Imagens/PPLite-2.png)

**Passo 08:** Na opção “Itens”, clique em “Adicionar Item” para incluir o material ou serviço que deseja pesquisar.

![Tela Adicionar Item](Imagens/Screenshot_18.jpg)

**Passo 09:** No campo de texto descreva de forma resumida o item que deseja pesquisar e selecione a opção mais adequada: Material ou Serviço.

![Tela Descrição do Item](Imagens/Screenshot_19.jpg)

!!! note "Nota"
    O sistema mostra as opções do catálogo do Compras.gov.br. Os itens que aparecem com a letra M antes do nome correspondem aos materiais e aqueles que aparecem com S são serviços. Ex: Você escreveu Computador. É um material. Na lista, vai aparecer: "M - Computador". Mas se você escreveu Manutenção de Computador, o que aparece é “S - Manutenção de Computador”, como mostra a tela abaixo.
    
    ![Tela Material vs Serviço](Imagens/Screenshot_20.jpg)

**Passo 10:** No painel de consulta, selecione o item que melhor atende ao que deseja pesquisar, assim como a quantidade, a unidade de fornecimento e características necessárias para refinamento da pesquisa. Após identificar o item e preencher os campos de quantidade e unidade de fornecimento clique na opção “+” para incluir o item na lista de pesquisa.

![Tela Inclusão de Item](Imagens/PPLite-4.png)

# 3. EDIÇÃO E GESTÃO DE COTAÇÕES

**Passo 11:** Caso deseje alterar a pesquisa, clique em “Editar item” (caneta) ou “Excluir Itens” (lixeira vermelha).

![Tela Editar Item](Imagens/PPLite-9.png)

**Passo 12:** Após clicar em “Editar item” abrirá a tela de edição. No topo da página, o sistema exibe as informações oficiais do catálogo do sistema Compras.gov.br - CATMAT para materiais ou CATSER para serviços, a respeito do item selecionado:

*   **Descrição do Item:** Mostra o código (catmat ou catser) e a descrição padronizada (Ex: 500075 - Caneta Esferográfica Material: Madeira).
*   **Quantidade e Unidade de Fornecimento:** Indica a quantidade estipulada para a contratação e como o item é fornecido (Ex: Caixa 50 Unidade).

![Tela Informações do Item](Imagens/PPLite-11.png)

**Passo 13:** Faça as alterações necessárias e clique em “Aplicar”. O sistema confirma a atualização das unidades de fornecimento ou unidades, alertando que as cotações para aquele item serão atualizadas.

![Tela Aplicar Alterações](Imagens/Screenshot_25.jpg)

**Passo 14:** Confirme a alteração do item.

![Tela Confirmar Alteração](Imagens/Screenshot_24.jpg)

!!! tip "Dica"
    Pronto, a cotação para aquele item foi atualizada. Para atualizar os demais itens, basta seguir novamente as instruções dos Passos 11 e 12.

### Indicadores e Controle Estatístico

O Pesquisa de Preços Lite exibe os seguintes indicadores em tempo real:

*   **Métodos de Cálculo:** Permite visualizar e alternar o critério de obtenção do preço estimado entre Menor Preço, Média ou Mediana. O método selecionado influenciará diretamente no valor de referência calculado pelo sistema.
*   **Painel de Controle Estatístico:** Localizado à direita, apresenta o Coeficiente de variação, o Desvio padrão e o Maior preço encontrado na amostra, servindo de parâmetro para analisar a homogeneidade e a segurança dos dados.

O Pesquisa de Preços Lite também mostra a relação de contratações públicas que foram selecionadas para compor os preços.

![Tela Painel Estatístico e Cotações](Imagens/Screenshot_22.jpg)

Além disso, é possível detalhar as informações a respeito das compras. Ao expandir o registro, o usuário tem acesso completo às informações da compra, incluindo o número do processo, a modalidade de contratação (Ex: Dispensa), os dados do fornecedor, marca do produto e o critério de julgamento.

!!! warning "Atenção"
    É possível gerenciar as contratações que compõem a pesquisa de preços.
    
    *   Na coluna **Compor** é possível ativar ou desativar aquela cotação específica. Quando a opção estiver desativada, o valor é excluído dos cálculos estatísticos.
    *   Na coluna **Ações**, o ícone de lixeira exclui o registro da lista do item.

<br>

# 4. RESUMO E RELATÓRIOS

**Passo 15:** Após preencher os campos obrigatórios de identificação e escolher as cotações que farão parte da sua pesquisa, clique na aba "Resumo".

![Tela Resumo](Imagens/PPLite-6.png)

Na página de Resumo será possível realizar as seguintes ações:

*   **Baixar e salvar o Relatório resumido:** Para gerar o relatório resumido da pesquisa realizada em PDF, clique no botão "Resumido".
*   **Baixar e salvar o Relatório Detalhado:** O relatório apresentará a média e a mediana dos últimos 12 meses, calculadas a partir das compras homologadas de todos os itens da consulta, junto com os dados de cada item. Clique no botão "Detalhado" para gerar.

![Tela Relatório Detalhado](Imagens/PPLite-7.png)

*   **Exportar os dados obtidos:** Caso prefira extrair os dados e salvá-los em formato editável no seu computador, clique em "Exportar CSV" no canto superior direito.
*   **Salvar a pesquisa na sua conta:** Para armazenar a consulta e acessá-la posteriormente, clique no botão "Salvar Pesquisa". Se você já realizou o login Gov.br no início, o sistema confirmará o salvamento imediatamente. Caso ainda não tenha feito login, abrirá a tela de autenticação do Gov.br para vincular a pesquisa ao seu perfil.

![Tela Salvar Pesquisa](Imagens/PPLite-6A.png)

!!! warning "Atenção"
    Ao clicar no botão "Home" ou em "Voltar" sem estar autenticado via Gov.br ou sem salvar a pesquisa, o sistema encerrará a consulta e os dados não ficarão salvos. 
    
    Para garantir que o seu trabalho não seja perdido e possa ser recuperado a qualquer momento, utilize o botão "Salvar Pesquisa" com o login Gov.br antes de sair.
    
    ![Tela Alerta Voltar](Imagens/PPLite-8.png)

**Suporte:** Caso tenha dúvidas ou precise de suporte, a Central de Atendimento do Ministério da Gestão e da Inovação em Serviços Públicos (MGI) está disponível pelo Portal de Serviços ou pelo telefone 0800 978 9001, de segunda a sexta-feira, das 8h às 18h.

<br>
<div style="text-align: right; margin: 10px 0;">
  <button onclick="window.print()" style="background-color: #0056b3; color: white; padding: 10px 20px; border: none; border-radius: 5px; font-size: 16px; cursor: pointer; box-shadow: 0 2px 4px rgba(0,0,0,0.2);">
  🖨️ Imprimir ou baixar esta página
  </button>
</div>

