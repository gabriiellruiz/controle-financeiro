<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Controle Financeiro Ruiz PRO MAX</title>
<link rel="manifest" href="./manifest.json">
<meta name="theme-color" content="#0b0f14">
<script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
<style>
:root{
  --bg:#0b0f14; --card:#121821; --muted:#1a2230; --text:#e9eef6; --sub:#b8c2d9;
  --brand:#6a6aff; --ok:#29c989; --warn:#ffb020; --bad:#ff6b6b; --ring:#2c3750;
  --chip:#1d2635;
}
*{box-sizing:border-box}
html,body{height:100%}
body{margin:0;background:linear-gradient(180deg,#0b0f14,#0e141c);color:var(--text);font-family:system-ui,-apple-system,Segoe UI,Roboto,Ubuntu}
a{color:var(--brand);text-decoration:none}
.container{max-width:1200px;margin:0 auto;padding:16px}
.header{display:flex;align-items:center;gap:12px;justify-content:space-between;margin:6px 0 16px}
.brand{display:flex;align-items:center;gap:10px}
.brand .logo{width:36px;height:36px;border-radius:10px;background:#0b0f14;border:2px solid var(--brand);display:grid;place-content:center;font-weight:700;color:var(--text)}
.brand h1{font-size:18px;margin:0}
.nav{display:flex;gap:8px;flex-wrap:wrap}
button,.btn{background:var(--muted);color:var(--text);border:1px solid #253047;padding:10px 12px;border-radius:10px;cursor:pointer}
button:hover,.btn:hover{border-color:var(--brand)}
input,select,textarea{background:#0f1520;border:1px solid #253047;color:var(--text);padding:10px;border-radius:10px;width:100%}
label{font-size:13px;color:var(--sub)}
.grid{display:grid;gap:12px}
.cards{grid-template-columns:repeat(auto-fit,minmax(220px,1fr))}
.card{background:var(--card);border:1px solid #192339;border-radius:14px;padding:14px}
.card h3{margin:0 0 8px;font-size:14px;color:var(--sub)}
.big{font-size:28px;font-weight:700}
.tag{display:inline-flex;gap:6px;align-items:center;background:var(--chip);border:1px solid #253047;color:var(--sub);padding:6px 8px;border-radius:999px;font-size:12px}
.row{display:flex;gap:10px;flex-wrap:wrap}
table{width:100%;border-collapse:collapse}
th,td{padding:10px;border-bottom:1px solid #1c2637}
th{font-size:12px;text-transform:uppercase;color:var(--sub);text-align:left}
td{font-size:14px}
.t-right{text-align:right}
.kpi-positive{color:var(--ok)} .kpi-warn{color:var(--warn)} .kpi-bad{color:var(--bad)}
.section h2{margin:18px 0 10px}
hr{border:0;border-top:1px solid #1c2637;margin:12px 0}
.modal{position:fixed;inset:0;display:none;place-items:center;background:rgba(0,0,0,.5);z-index:50}
.modal.open{display:grid}
.modal>div{background:var(--card);border:1px solid #1b2640;border-radius:16px;max-width:560px;width:92%;padding:16px}
.modal-header{display:flex;align-items:center;justify-content:space-between;margin-bottom:8px}
.close{background:transparent;border:none;color:var(--sub);font-size:20px}
.small{font-size:12px;color:var(--sub)}
.badge{padding:4px 8px;border-radius:8px;font-size:12px;border:1px solid #253047;background:var(--chip);color:var(--sub)}
.badge.open{color:#cdd7ff;background:#12203d;border-color:#233a74}
.badge.overdue{color:#fff;background:#41210c;border-color:#7a3f17}
.badge.paid{color:#05241a;background:#153d2f;border-color:#285b4a}
.actions{display:flex;gap:8px;flex-wrap:wrap}
input[type="file"]{padding:8px}
.img-thumb{max-width:120px;max-height:120px;border:1px solid #233;display:block;border-radius:10px}
.footer-note{color:var(--sub);font-size:12px;margin-top:16px}
.searchbar{display:flex;gap:8px;flex-wrap:wrap}

/* Dropdown Menu Styles */
.dropdown {
  position: relative;
  display: inline-block;
}

.dropdown-content {
  display: none;
  position: absolute;
  background-color: var(--card);
  min-width: 160px;
  box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
  z-index: 1;
  border-radius: 10px;
  border: 1px solid #253047;
  top: 100%;
  left: 0;
}

.dropdown-content a {
  color: var(--text);
  padding: 12px 16px;
  text-decoration: none;
  display: block;
  border-radius: 8px;
  margin: 4px;
}

.dropdown-content a:hover {
  background-color: var(--muted);
}

.dropdown:hover .dropdown-content {
  display: block;
}

.dropdown:hover .dropbtn {
  border-color: var(--brand);
}

/* Chart Container */
.chart-container {
  position: relative;
  height: 300px;
  margin: 20px 0;
}

/* Score Widget */
.score-widget {
  text-align: center;
  padding: 20px;
}

.score-circle {
  width: 120px;
  height: 120px;
  border-radius: 50%;
  margin: 0 auto 10px;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 24px;
  font-weight: bold;
  position: relative;
}

.score-excellent { background: linear-gradient(135deg, #29c989, #20a574); }
.score-good { background: linear-gradient(135deg, #ffb020, #e09900); }
.score-poor { background: linear-gradient(135deg, #ff6b6b, #e55555); }

/* Responsive */
@media (max-width: 768px) {
  .nav {
    flex-direction: column;
    width: 100%;
  }
  
  .dropdown-content {
    position: static;
    display: none;
    box-shadow: none;
    background-color: var(--muted);
    margin-top: 5px;
  }
  
  .dropdown.mobile-open .dropdown-content {
    display: block;
  }
}
</style>
</head>
<body>
<div class="container">
  <div class="header">
    <div class="brand">
      <div class="logo">RF</div>
      <h1>Controle Financeiro Ruiz <span class="small">PRO MAX</span></h1>
    </div>
    <div class="nav">
      <button onclick="nav('dashboard')">📊 Dashboard</button>
      <div class="dropdown">
        <button class="dropbtn">📝 Lançamentos</button>
        <div class="dropdown-content">
          <a href="#" onclick="nav('recebiveis')">💸 Recebíveis</a>
          <a href="#" onclick="nav('despesas')">🧾 Despesas</a>
          <a href="#" onclick="nav('faturas')">💳 Faturas</a>
          <a href="#" onclick="nav('cofres')">🎯 Cofres</a>
          <a href="#" onclick="nav('dividas')">💰 Dívidas</a>
          <a href="#" onclick="nav('pessoas')">👥 Pessoas me Devem</a>
          <a href="#" onclick="nav('viagens')">🧳 Viagens</a>
        </div>
      </div>
      <button onclick="nav('relatorios')">📈 Relatórios</button>
      <button onclick="nav('config')">⚙️ Configurações</button>
    </div>
  </div>

  <div id="dashboard" class="section">
    <h2>📊 Dashboard</h2>
    <div class="grid cards">
      <div class="card">
        <h3>Score Financeiro</h3>
        <div class="score-widget">
          <div id="scoreCircle" class="score-circle score-good">
            <span id="scoreValue">750</span>
          </div>
          <div class="small">Bom</div>
        </div>
      </div>
      <div class="card"><h3>Total de Recebíveis</h3><div id="kpiRecebiveis" class="big">R$ 0,00</div></div>
      <div class="card"><h3>A Receber x A Pagar (mês)</h3><div id="kpiRxP" class="big">R$ 0 x R$ 0</div></div>
      <div class="card"><h3>Maiores Devedores</h3><div id="kpiTopDevedores"></div></div>
      <div class="card">
        <h3>Atalhos Rápidos</h3>
        <div class="actions">
          <button onclick="openModal('modalRecebivel')">+ Recebível</button>
          <button onclick="openModal('modalDespesa')">+ Despesa</button>
          <button onclick="openModal('modalViagem')">+ Viagem</button>
          <button onclick="duplicarRecorrentes()">↻ Lanç. Recorrentes</button>
        </div>
      </div>
      <div class="card">
        <h3>Resumo Mensal</h3>
        <div id="resumoMensal"></div>
      </div>
    </div>
    
    <!-- Gráficos Interativos -->
    <div class="grid cards" style="margin-top: 20px;">
      <div class="card">
        <h3>Evolução Financeira (6 meses)</h3>
        <div class="chart-container">
          <canvas id="chartEvolucao"></canvas>
        </div>
      </div>
      <div class="card">
        <h3>Distribuição de Gastos</h3>
        <div class="chart-container">
          <canvas id="chartDistribuicao"></canvas>
        </div>
      </div>
    </div>
    
    <hr>
    <div class="row">
      <div class="tag">💡 Dica: Use os gráficos interativos para analisar seus padrões financeiros.</div>
    </div>
  </div>

  <div id="recebiveis" class="section" style="display:none">
    <h2>💸 Recebíveis</h2>
    <div class="searchbar">
      <input id="recSearch" placeholder="Buscar por pessoa, tag..." oninput="renderRecebiveis()">
      <select id="recStatus" onchange="renderRecebiveis()">
        <option value="">Status (todos)</option>
        <option value="open">Em aberto</option>
        <option value="overdue">Atrasado</option>
        <option value="paid">Pago</option>
      </select>
      <button onclick="openModal('modalRecebivel')">+ Adicionar</button>
      <button onclick="exportCSV('recebiveis')">Exportar CSV</button>
      <button onclick="exportJSON('recebiveis')">Exportar JSON</button>
    </div>
    <div class="grid cards" style="margin-top:10px">
      <div class="card">
        <h3>Total Geral</h3>
        <div id="recTotal" class="big">R$ 0,00</div>
      </div>
      <div class="card">
        <h3>Gráfico de Recebíveis</h3>
        <div class="chart-container">
          <canvas id="chartRecebiveis"></canvas>
        </div>
      </div>
    </div>
    <table>
      <thead><tr>
        <th>Pessoa</th><th>Descrição</th><th>Vencimento</th><th>Valor</th><th>Status</th><th>Tags</th><th>Ações</th>
      </tr></thead>
      <tbody id="tblRecebiveis"></tbody>
    </table>
  </div>

  <div id="despesas" class="section" style="display:none">
    <h2>🧾 Despesas</h2>
    <div class="searchbar">
      <input id="depSearch" placeholder="Buscar por descrição ou tag..." oninput="renderDespesas()">
      <select id="depFP" onchange="renderDespesas()">
        <option value="">Forma de pagamento</option>
        <option>Cartão</option><option>PIX</option><option>Dinheiro</option><option>Boleto</option>
      </select>
      <button onclick="openModal('modalDespesa')">+ Adicionar</button>
      <button onclick="exportCSV('despesas')">Exportar CSV</button>
      <button onclick="exportJSON('despesas')">Exportar JSON</button>
    </div>
    <div class="grid cards" style="margin-top:10px">
      <div class="card">
        <h3>Gráfico de Despesas por Categoria</h3>
        <div class="chart-container">
          <canvas id="chartDespesas"></canvas>
        </div>
      </div>
    </div>
    <table>
      <thead><tr>
        <th>Data</th><th>Descrição</th><th>Valor</th><th>Forma</th><th>Tags</th><th>Comprovante</th><th>Ações</th>
      </tr></thead>
      <tbody id="tblDespesas"></tbody>
    </table>
  </div>

  <!-- Nova seção: Faturas -->
  <div id="faturas" class="section" style="display:none">
    <h2>💳 Faturas de Cartão</h2>
    <div class="searchbar">
      <button onclick="openModal('modalFatura')">+ Nova Fatura</button>
      <button onclick="exportJSON('faturas')">Exportar JSON</button>
    </div>
    <div class="grid cards" style="margin-top:10px">
      <div class="card">
        <h3>Total em Faturas Abertas</h3>
        <div id="faturaTotal" class="big">R$ 0,00</div>
      </div>
    </div>
    <table>
      <thead><tr>
        <th>Cartão</th><th>Vencimento</th><th>Valor</th><th>Status</th><th>Ações</th>
      </tr></thead>
      <tbody id="tblFaturas"></tbody>
    </table>
  </div>

  <!-- Nova seção: Cofres -->
  <div id="cofres" class="section" style="display:none">
    <h2>🎯 Cofres (Metas de Economia)</h2>
    <div class="searchbar">
      <button onclick="openModal('modalCofre')">+ Novo Cofre</button>
      <button onclick="exportJSON('cofres')">Exportar JSON</button>
    </div>
    <div class="grid cards" id="cofresGrid">
      <!-- Cofres serão renderizados aqui -->
    </div>
  </div>

  <!-- Nova seção: Dívidas -->
  <div id="dividas" class="section" style="display:none">
    <h2>💰 Minhas Dívidas</h2>
    <div class="searchbar">
      <button onclick="openModal('modalDivida')">+ Nova Dívida</button>
      <button onclick="exportJSON('dividas')">Exportar JSON</button>
    </div>
    <div class="grid cards" style="margin-top:10px">
      <div class="card">
        <h3>Total em Dívidas</h3>
        <div id="dividaTotal" class="big">R$ 0,00</div>
      </div>
    </div>
    <table>
      <thead><tr>
        <th>Credor</th><th>Descrição</th><th>Valor Total</th><th>Valor Pago</th><th>Restante</th><th>Vencimento</th><th>Ações</th>
      </tr></thead>
      <tbody id="tblDividas"></tbody>
    </table>
  </div>

  <!-- Nova seção: Pessoas me Devem -->
  <div id="pessoas" class="section" style="display:none">
    <h2>👥 Pessoas que me Devem</h2>
    <div class="searchbar">
      <button onclick="openModal('modalPessoa')">+ Nova Pessoa</button>
      <button onclick="exportJSON('pessoas')">Exportar JSON</button>
    </div>
    <div class="grid cards" style="margin-top:10px">
      <div class="card">
        <h3>Total a Receber de Pessoas</h3>
        <div id="pessoaTotal" class="big">R$ 0,00</div>
      </div>
    </div>
    <div id="pessoasList">
      <!-- Lista de pessoas será renderizada aqui -->
    </div>
  </div>

  <div id="viagens" class="section" style="display:none">
    <h2>🧳 Viagens</h2>
    <div class="searchbar">
      <input id="viagemSearch" placeholder="Buscar por destino..." oninput="renderViagens()">
      <button onclick="openModal('modalViagem')">+ Nova Viagem</button>
      <button onclick="exportJSON('viagens')">Exportar JSON</button>
    </div>
    <div class="grid cards" style="margin-top:10px">
      <div class="card">
        <h3>Gráfico de Gastos por Viagem</h3>
        <div class="chart-container">
          <canvas id="chartViagens"></canvas>
        </div>
      </div>
    </div>
    <table>
      <thead><tr>
        <th>Destino</th><th>Período</th><th>Pessoas</th><th>Gastos</th><th>Total</th><th>Ações</th>
      </tr></thead>
      <tbody id="tblViagens"></tbody>
    </table>
  </div>

  <!-- Nova seção: Relatórios -->
  <div id="relatorios" class="section" style="display:none">
    <h2>📈 Relatórios e Análises</h2>
    <div class="grid cards">
      <div class="card">
        <h3>Fluxo de Caixa Mensal</h3>
        <div class="chart-container">
          <canvas id="chartFluxoCaixa"></canvas>
        </div>
      </div>
      <div class="card">
        <h3>Comparativo Anual</h3>
        <div class="chart-container">
          <canvas id="chartComparativo"></canvas>
        </div>
      </div>
      <div class="card">
        <h3>Análise de Tendências</h3>
        <div class="chart-container">
          <canvas id="chartTendencias"></canvas>
        </div>
      </div>
      <div class="card">
        <h3>Resumo Executivo</h3>
        <div id="resumoExecutivo">
          <!-- Resumo será gerado aqui -->
        </div>
      </div>
    </div>
  </div>

  <div id="config" class="section" style="display:none">
    <h2>⚙️ Configurações & Backup</h2>
    <div class="grid cards">
      <div class="card">
        <h3>Backup Completo</h3>
        <div class="actions">
          <button onclick="backupCompleto()">📥 Exportar Backup JSON</button>
          <input type="file" id="restoreFile" accept="application/json" />
          <button onclick="restaurarBackup()">📤 Restaurar Backup</button>
        </div>
      </div>
      <div class="card">
        <h3>Configurações do Sistema</h3>
        <div class="actions">
          <button onclick="configurarCategorias()">🏷️ Gerenciar Categorias</button>
          <button onclick="configurarRecorrentes()">🔄 Configurar Recorrentes</button>
          <button onclick="configurarNotificacoes()">🔔 Notificações</button>
        </div>
      </div>
      <div class="card">
        <h3>Limpeza de Dados</h3>
        <button onclick="if(confirm('⚠️ Apagar todos os dados? Esta ação não pode ser desfeita!')){localStorage.clear();init();alert('✅ Dados limpos com sucesso.');}">🗑️ Apagar Tudo</button>
      </div>
      <div class="card">
        <h3>Estatísticas do Sistema</h3>
        <div id="estatisticasSistema">
          <!-- Estatísticas serão geradas aqui -->
        </div>
      </div>
    </div>
    <p class="footer-note">💾 Dados salvos localmente no seu dispositivo (localStorage). Faça backups regulares!</p>
  </div>
</div>

<!-- Modais Existentes -->
<div class="modal" id="modalRecebivel" aria-hidden="true">
  <div>
    <div class="modal-header">
      <h3>💸 Adicionar/Editar Recebível</h3>
      <button class="close" onclick="closeModal('modalRecebivel')">✖</button>
    </div>
    <div class="grid">
      <input id="r_id" type="hidden">
      <div><label>👤 Pessoa</label><input id="r_pessoa"></div>
      <div><label>📝 Descrição</label><input id="r_desc"></div>
      <div class="row">
        <div style="flex:1"><label>💰 Valor (R$)</label><input id="r_valor" type="number" step="0.01"></div>
        <div style="flex:1"><label>📅 Vencimento</label><input id="r_venc" type="date"></div>
      </div>
      <div class="row">
        <div style="flex:1"><label>📊 Status</label>
          <select id="r_status"><option value="open">Em aberto</option><option value="paid">Pago</option><option value="overdue">Atrasado</option></select>
        </div>
        <div style="flex:1"><label>🏷️ Tags (separe por vírgula)</label><input id="r_tags"></div>
      </div>
      <div class="actions">
        <button onclick="salvarRecebivel()">💾 Salvar</button>
        <button class="btn" onclick="closeModal('modalRecebivel')">❌ Fechar</button>
      </div>
    </div>
  </div>
</div>

<div class="modal" id="modalDespesa" aria-hidden="true">
  <div>
    <div class="modal-header">
      <h3>🧾 Adicionar/Editar Despesa</h3>
      <button class="close" onclick="closeModal('modalDespesa')">✖</button>
    </div>
    <div class="grid">
      <input id="d_id" type="hidden">
      <div class="row">
        <div style="flex:1"><label>📅 Data</label><input id="d_data" type="date"></div>
        <div style="flex:1"><label>💰 Valor (R$)</label><input id="d_valor" type="number" step="0.01"></div>
      </div>
      <div><label>📝 Descrição</label><input id="d_desc"></div>
      <div class="row">
        <div style="flex:1"><label>💳 Forma de Pagamento</label>
          <select id="d_fp"><option>Cartão</option><option>PIX</option><option>Dinheiro</option><option>Boleto</option></select>
        </div>
        <div style="flex:1"><label>🏷️ Tags (vírgulas)</label><input id="d_tags"></div>
      </div>
      <div><label>📎 Comprovante (imagem)</label><input id="d_comp" type="file" accept="image/*" onchange="previewComp(event,'d_prev')"><img id="d_prev" class="img-thumb" alt=""></div>
      <div class="actions">
        <button onclick="salvarDespesa()">💾 Salvar</button>
        <button class="btn" onclick="closeModal('modalDespesa')">❌ Fechar</button>
      </div>
    </div>
  </div>
</div>

<!-- Novos Modais -->
<div class="modal" id="modalFatura" aria-hidden="true">
  <div>
    <div class="modal-header">
      <h3>💳 Nova/Editar Fatura</h3>
      <button class="close" onclick="closeModal('modalFatura')">✖</button>
    </div>
    <div class="grid">
      <input id="f_id" type="hidden">
      <div><label>💳 Nome do Cartão</label><input id="f_cartao"></div>
      <div class="row">
        <div style="flex:1"><label>💰 Valor (R$)</label><input id="f_valor" type="number" step="0.01"></div>
        <div style="flex:1"><label>📅 Vencimento</label><input id="f_venc" type="date"></div>
      </div>
      <div><label>📊 Status</label>
        <select id="f_status"><option value="open">Em aberto</option><option value="paid">Paga</option></select>
      </div>
      <div class="actions">
        <button onclick="salvarFatura()">💾 Salvar</button>
        <button class="btn" onclick="closeModal('modalFatura')">❌ Fechar</button>
      </div>
    </div>
  </div>
</div>

<div class="modal" id="modalCofre" aria-hidden="true">
  <div>
    <div class="modal-header">
      <h3>🎯 Novo/Editar Cofre</h3>
      <button class="close" onclick="closeModal('modalCofre')">✖</button>
    </div>
    <div class="grid">
      <input id="c_id" type="hidden">
      <div><label>🎯 Nome da Meta</label><input id="c_nome"></div>
      <div class="row">
        <div style="flex:1"><label>💰 Valor Meta (R$)</label><input id="c_meta" type="number" step="0.01"></div>
        <div style="flex:1"><label>💵 Valor Atual (R$)</label><input id="c_atual" type="number" step="0.01"></div>
      </div>
      <div><label>📅 Data Limite</label><input id="c_limite" type="date"></div>
      <div class="actions">
        <button onclick="salvarCofre()">💾 Salvar</button>
        <button class="btn" onclick="closeModal('modalCofre')">❌ Fechar</button>
      </div>
    </div>
  </div>
</div>

<div class="modal" id="modalDivida" aria-hidden="true">
  <div>
    <div class="modal-header">
      <h3>💰 Nova/Editar Dívida</h3>
      <button class="close" onclick="closeModal('modalDivida')">✖</button>
    </div>
    <div class="grid">
      <input id="dv_id" type="hidden">
      <div><label>🏦 Credor</label><input id="dv_credor"></div>
      <div><label>📝 Descrição</label><input id="dv_desc"></div>
      <div class="row">
        <div style="flex:1"><label>💰 Valor Total (R$)</label><input id="dv_total" type="number" step="0.01"></div>
        <div style="flex:1"><label>💵 Valor Pago (R$)</label><input id="dv_pago" type="number" step="0.01"></div>
      </div>
      <div><label>📅 Vencimento</label><input id="dv_venc" type="date"></div>
      <div class="actions">
        <button onclick="salvarDivida()">💾 Salvar</button>
        <button class="btn" onclick="closeModal('modalDivida')">❌ Fechar</button>
      </div>
    </div>
  </div>
</div>

<div class="modal" id="modalPessoa" aria-hidden="true">
  <div>
    <div class="modal-header">
      <h3>👥 Nova/Editar Pessoa</h3>
      <button class="close" onclick="closeModal('modalPessoa')">✖</button>
    </div>
    <div class="grid">
      <input id="p_id" type="hidden">
      <div><label>👤 Nome da Pessoa</label><input id="p_nome"></div>
      <div><label>📝 Descrição da Dívida</label><input id="p_desc"></div>
      <div><label>💰 Valor (R$)</label><input id="p_valor" type="number" step="0.01"></div>
      <div><label>📅 Data do Empréstimo</label><input id="p_data" type="date"></div>
      <div class="actions">
        <button onclick="salvarPessoa()">💾 Salvar</button>
        <button class="btn" onclick="closeModal('modalPessoa')">❌ Fechar</button>
      </div>
    </div>
  </div>
</div>

<div class="modal" id="modalViagem" aria-hidden="true">
  <div>
    <div class="modal-header">
      <h3>🧳 Nova/Editar Viagem</h3>
      <button class="close" onclick="closeModal('modalViagem')">✖</button>
    </div>
    <div class="grid">
      <input id="v_id" type="hidden">
      <div class="row">
        <div style="flex:1"><label>🌍 Destino</label><input id="v_dest"></div>
        <div style="flex:1"><label>📅 Data Início</label><input id="v_ini" type="date"></div>
        <div style="flex:1"><label>📅 Data Fim</label><input id="v_fim" type="date"></div>
      </div>
      <div><label>👥 Participantes (separe por vírgula)</label><input id="v_part"></div>
      <div class="actions">
        <button onclick="salvarViagem()">💾 Salvar</button>
        <button class="btn" onclick="closeModal('modalViagem')">❌ Fechar</button>
      </div>
    </div>
  </div>
</div>

<div class="modal" id="modalGastoViagem" aria-hidden="true">
  <div>
    <div class="modal-header">
      <h3>💸 Adicionar gasto à viagem</h3>
      <button class="close" onclick="closeModal('modalGastoViagem')">✖</button>
    </div>
    <div class="grid">
      <input id="gv_vid" type="hidden">
      <div class="row">
        <div style="flex:1"><label>📅 Data</label><input id="gv_data" type="date"></div>
        <div style="flex:1"><label>💰 Valor (R$)</label><input id="gv_valor" type="number" step="0.01"></div>
      </div>
      <div><label>📝 Descrição</label><input id="gv_desc"></div>
      <div><label>📎 Comprovante</label><input id="gv_comp" type="file" accept="image/*" onchange="previewComp(event,'gv_prev')"><img id="gv_prev" class="img-thumb" alt=""></div>
      <div class="actions">
        <button onclick="salvarGastoViagem()">💾 Salvar</button>
        <button class="btn" onclick="closeModal('modalGastoViagem')">❌ Fechar</button>
      </div>
    </div>
  </div>
</div>

<!-- Modal para adicionar lançamento a pessoa -->
<div class="modal" id="modalLancamentoPessoa" aria-hidden="true">
  <div>
    <div class="modal-header">
      <h3>💰 Novo Lançamento</h3>
      <button class="close" onclick="closeModal('modalLancamentoPessoa')">✖</button>
    </div>
    <div class="grid">
      <input id="lp_pid" type="hidden">
      <div><label>📝 Descrição</label><input id="lp_desc"></div>
      <div class="row">
        <div style="flex:1"><label>💰 Valor (R$)</label><input id="lp_valor" type="number" step="0.01"></div>
        <div style="flex:1"><label>📅 Data</label><input id="lp_data" type="date"></div>
      </div>
      <div class="actions">
        <button onclick="salvarLancamentoPessoa()">💾 Salvar</button>
        <button class="btn" onclick="closeModal('modalLancamentoPessoa')">❌ Fechar</button>
      </div>
    </div>
  </div>
</div>

<script>
// ====== Storage helpers ======
const S = {
  get(k,def){try{const v=localStorage.getItem(k);return v?JSON.parse(v):def}catch(e){return def}},
  set(k,v){localStorage.setItem(k,JSON.stringify(v))},
};

const KEYS = {
  rec: 'ruizCF_recebiveis',
  dep: 'ruizCF_despesas',
  via: 'ruizCF_viagens',
  fat: 'ruizCF_faturas',
  cof: 'ruizCF_cofres',
  div: 'ruizCF_dividas',
  pes: 'ruizCF_pessoas',
  recTemplates: 'ruizCF_recorrentes'
};

// ====== Utility functions ======
function money(v){return (v||0).toLocaleString('pt-BR',{style:'currency',currency:'BRL'})}
function today(){return new Date().toISOString().slice(0,10)}
function byId(id){return document.getElementById(id)}
function openModal(id){byId(id).classList.add('open')}
function closeModal(id){byId(id).classList.remove('open')}

// ====== Navigation ======
function nav(id){
  ['dashboard','recebiveis','despesas','faturas','cofres','dividas','pessoas','viagens','relatorios','config'].forEach(x=>{
    const el = byId(x);
    if(el) el.style.display = (x===id)?'block':'none';
  });
  
  // Render specific sections
  if(id==='dashboard') renderDashboard();
  if(id==='recebiveis') renderRecebiveis();
  if(id==='despesas') renderDespesas();
  if(id==='faturas') renderFaturas();
  if(id==='cofres') renderCofres();
  if(id==='dividas') renderDividas();
  if(id==='pessoas') renderPessoas();
  if(id==='viagens') renderViagens();
  if(id==='relatorios') renderRelatorios();
  if(id==='config') renderConfig();
}

// ====== Init ======
function init(){
  // Initialize storage
  Object.values(KEYS).forEach(key => {
    if(!S.get(key)) S.set(key, []);
  });
  
  renderDashboard();
}

document.addEventListener('DOMContentLoaded', ()=>{
  init();
  // Register service worker
  if('serviceWorker' in navigator){
    navigator.serviceWorker.register('./sw.js').catch(()=>{});
  }
});

// ====== Dashboard ======
function renderDashboard(){
  renderKpis();
  renderCharts();
}

function renderKpis(){
  const rec = S.get(KEYS.rec, []);
  const deps = S.get(KEYS.dep, []);
  const fat = S.get(KEYS.fat, []);
  const div = S.get(KEYS.div, []);
  const pes = S.get(KEYS.pes, []);
  
  // Total de recebíveis
  const totalRec = rec.filter(x=>x.status!=='paid').reduce((a,b)=>a+Number(b.valor||0),0);
  byId('kpiRecebiveis').textContent = money(totalRec);

  // A receber x A pagar no mês
  const month = new Date().toISOString().slice(0,7);
  const recMes = rec.filter(x=> (x.venc||'').startsWith(month) && x.status!=='paid').reduce((a,b)=>a+Number(b.valor||0),0);
  const depMes = deps.filter(x=> (x.data||'').startsWith(month)).reduce((a,b)=>a+Number(b.valor||0),0);
  byId('kpiRxP').textContent = `${money(recMes)} x ${money(depMes)}`;

  // Top devedores
  const map = {};
  rec.forEach(r=>{ if(r.status!=='paid'){ map[r.pessoa] = (map[r.pessoa]||0)+Number(r.valor||0) } });
  pes.forEach(p=>{ 
    const totalPessoa = (p.lancamentos||[]).filter(l=>!l.pago).reduce((a,b)=>a+Number(b.valor||0),0);
    if(totalPessoa > 0) map[p.nome] = (map[p.nome]||0)+totalPessoa;
  });
  const tops = Object.entries(map).sort((a,b)=>b[1]-a[1]).slice(0,5);
  byId('kpiTopDevedores').innerHTML = tops.length? tops.map(([p,v])=>`<div class="row"><div class="tag">${p}</div><div class="t-right" style="margin-left:auto">${money(v)}</div></div>`).join('') : '<span class="small">Sem devedores em aberto.</span>';

  // Score financeiro
  const score = calcularScore();
  updateScoreWidget(score);
  
  // Resumo mensal
  const fatMes = fat.filter(x=> (x.venc||'').startsWith(month) && x.status!=='paid').reduce((a,b)=>a+Number(b.valor||0),0);
  const divMes = div.filter(x=> (x.venc||'').startsWith(month)).reduce((a,b)=>a+Number(b.total||0)-Number(b.pago||0),0);
  
  byId('resumoMensal').innerHTML = `
    <div class="small">Receitas: ${money(recMes)}</div>
    <div class="small">Despesas: ${money(depMes)}</div>
    <div class="small">Faturas: ${money(fatMes)}</div>
    <div class="small">Dívidas: ${money(divMes)}</div>
    <hr style="margin: 8px 0;">
    <div class="small ${recMes-depMes-fatMes-divMes >= 0 ? 'kpi-positive' : 'kpi-bad'}">
      Saldo: ${money(recMes-depMes-fatMes-divMes)}
    </div>
  `;
}

function calcularScore(){
  const rec = S.get(KEYS.rec, []);
  const deps = S.get(KEYS.dep, []);
  const fat = S.get(KEYS.fat, []);
  const div = S.get(KEYS.div, []);
  
  let score = 500; // Base score
  
  // Positive factors
  const totalRecebiveis = rec.filter(x=>x.status!=='paid').reduce((a,b)=>a+Number(b.valor||0),0);
  score += Math.min(totalRecebiveis * 0.1, 200);
  
  // Negative factors
  const totalDespesas = deps.reduce((a,b)=>a+Number(b.valor||0),0);
  const totalFaturas = fat.filter(x=>x.status!=='paid').reduce((a,b)=>a+Number(b.valor||0),0);
  const totalDividas = div.reduce((a,b)=>a+(Number(b.total||0)-Number(b.pago||0)),0);
  
  score -= Math.min((totalDespesas + totalFaturas + totalDividas) * 0.05, 300);
  
  // Overdue penalties
  const overdueRec = rec.filter(x=>x.status==='overdue').length;
  const overdueFat = fat.filter(x=>x.status==='open' && x.venc < today()).length;
  score -= (overdueRec + overdueFat) * 50;
  
  return Math.max(0, Math.min(1000, Math.round(score)));
}

function updateScoreWidget(score){
  const scoreEl = byId('scoreValue');
  const circleEl = byId('scoreCircle');
  
  scoreEl.textContent = score;
  
  // Remove existing classes
  circleEl.classList.remove('score-excellent', 'score-good', 'score-poor');
  
  // Add appropriate class
  if(score >= 750) {
    circleEl.classList.add('score-excellent');
    circleEl.nextElementSibling.textContent = 'Excelente';
  } else if(score >= 500) {
    circleEl.classList.add('score-good');
    circleEl.nextElementSibling.textContent = 'Bom';
  } else {
    circleEl.classList.add('score-poor');
    circleEl.nextElementSibling.textContent = 'Precisa Melhorar';
  }
}

// ====== Charts ======
function renderCharts(){
  renderEvolucaoChart();
  renderDistribuicaoChart();
}

function renderEvolucaoChart(){
  const ctx = byId('chartEvolucao');
  if(!ctx) return;
  
  const deps = S.get(KEYS.dep, []);
  const rec = S.get(KEYS.rec, []);
  
  // Get last 6 months
  const months = [];
  for(let i = 5; i >= 0; i--){
    const date = new Date();
    date.setMonth(date.getMonth() - i);
    months.push(date.toISOString().slice(0,7));
  }
  
  const despesasData = months.map(month => {
    return deps.filter(d => (d.data||'').startsWith(month))
              .reduce((sum, d) => sum + Number(d.valor||0), 0);
  });
  
  const recebiveisData = months.map(month => {
    return rec.filter(r => (r.venc||'').startsWith(month) && r.status === 'paid')
              .reduce((sum, r) => sum + Number(r.valor||0), 0);
  });
  
  new Chart(ctx, {
    type: 'line',
    data: {
      labels: months.map(m => new Date(m + '-01').toLocaleDateString('pt-BR', {month: 'short', year: '2-digit'})),
      datasets: [{
        label: 'Despesas',
        data: despesasData,
        borderColor: '#ff6b6b',
        backgroundColor: 'rgba(255, 107, 107, 0.1)',
        tension: 0.4
      }, {
        label: 'Recebidos',
        data: recebiveisData,
        borderColor: '#29c989',
        backgroundColor: 'rgba(41, 201, 137, 0.1)',
        tension: 0.4
      }]
    },
    options: {
      responsive: true,
      maintainAspectRatio: false,
      plugins: {
        legend: {
          labels: { color: '#e9eef6' }
        }
      },
      scales: {
        x: { ticks: { color: '#b8c2d9' } },
        y: { ticks: { color: '#b8c2d9' } }
      }
    }
  });
}

function renderDistribuicaoChart(){
  const ctx = byId('chartDistribuicao');
  if(!ctx) return;
  
  const deps = S.get(KEYS.dep, []);
  const categorias = {};
  
  deps.forEach(d => {
    const tags = (d.tags||'').split(',').map(t => t.trim()).filter(Boolean);
    if(tags.length === 0) tags.push('Sem categoria');
    
    tags.forEach(tag => {
      categorias[tag] = (categorias[tag] || 0) + Number(d.valor||0);
    });
  });
  
  const labels = Object.keys(categorias);
  const data = Object.values(categorias);
  const colors = [
    '#6a6aff', '#29c989', '#ffb020', '#ff6b6b', '#9c88ff', 
    '#ff9f43', '#26de81', '#fc5c65', '#45aaf2', '#a55eea'
  ];
  
  new Chart(ctx, {
    type: 'doughnut',
    data: {
      labels: labels,
      datasets: [{
        data: data,
        backgroundColor: colors.slice(0, labels.length),
        borderWidth: 0
      }]
    },
    options: {
      responsive: true,
      maintainAspectRatio: false,
      plugins: {
        legend: {
          position: 'bottom',
          labels: { color: '#e9eef6', padding: 20 }
        }
      }
    }
  });
}

// ====== Receipts preview helper ======
function previewComp(evt, imgId){
  const file = evt.target.files && evt.target.files[0];
  if(!file) return;
  const reader = new FileReader();
  reader.onload = e => byId(imgId).src = e.target.result;
  reader.readAsDataURL(file);
}

// ====== Recebíveis CRUD ======
function renderRecebiveis(){
  const q = (byId('recSearch').value||'').toLowerCase();
  const status = byId('recStatus').value;
  let rec = S.get(KEYS.rec, []);
  
  // Auto mark overdue
  rec.forEach(r=>{
    if(r.status==='open' && r.venc && r.venc < today()) r.status='overdue';
  });
  S.set(KEYS.rec, rec);
  
  const filtered = rec.filter(r=> (r.pessoa||'').toLowerCase().includes(q) || (r.tags||'').toLowerCase().includes(q))
                      .filter(r=> !status || r.status===status);
  
  // Update total
  const total = filtered.reduce((a,b)=>a+Number(b.valor||0),0);
  byId('recTotal').textContent = money(total);
  
  // Render table
  const tbody = byId('tblRecebiveis');
  tbody.innerHTML = filtered.map(r=>{
    const badge = `<span class="badge ${r.status}">${r.status==='open'?'Em aberto': r.status==='paid'?'Pago':'Atrasado'}</span>`;
    const tags = (r.tags||'').split(',').filter(x=>x.trim()).map(t=>`<span class="tag">#${t.trim()}</span>`).join(' ');
    return `<tr>
      <td>${r.pessoa||''}</td>
      <td>${r.desc||''}</td>
      <td>${r.venc||''}</td>
      <td class="t-right">${money(r.valor||0)}</td>
      <td>${badge}</td>
      <td>${tags}</td>
      <td class="actions">
        <button onclick='editRecebivel(${JSON.stringify(r.id)})'>✏️</button>
        <button onclick='delRecebivel(${JSON.stringify(r.id)})'>🗑️</button>
        ${r.status!=='paid'?`<button onclick='marcarPago(${JSON.stringify(r.id)})'>✅</button>`:''}
      </td>
    </tr>`
  }).join('');
  
  // Render chart
  renderRecebiveisChart(filtered);
}

function renderRecebiveisChart(data){
  const ctx = byId('chartRecebiveis');
  if(!ctx) return;
  
  const statusCount = {
    'Em aberto': data.filter(r => r.status === 'open').length,
    'Atrasado': data.filter(r => r.status === 'overdue').length,
    'Pago': data.filter(r => r.status === 'paid').length
  };
  
  new Chart(ctx, {
    type: 'pie',
    data: {
      labels: Object.keys(statusCount),
      datasets: [{
        data: Object.values(statusCount),
        backgroundColor: ['#6a6aff', '#ff6b6b', '#29c989'],
        borderWidth: 0
      }]
    },
    options: {
      responsive: true,
      maintainAspectRatio: false,
      plugins: {
        legend: {
          position: 'bottom',
          labels: { color: '#e9eef6' }
        }
      }
    }
  });
}

function salvarRecebivel(){
  const obj = {
    id: byId('r_id').value || cryptoRandomId(),
    pessoa: byId('r_pessoa').value.trim(),
    desc: byId('r_desc').value.trim(),
    valor: Number(byId('r_valor').value||0),
    venc: byId('r_venc').value,
    status: byId('r_status').value,
    tags: byId('r_tags').value.trim()
  };
  
  if(!obj.pessoa || !obj.desc || !obj.valor){ 
    alert('❌ Pessoa, descrição e valor são obrigatórios.'); 
    return; 
  }
  
  const data = S.get(KEYS.rec, []);
  const idx = data.findIndex(x=>x.id===obj.id);
  if(idx>=0) data[idx]=obj; else data.push(obj);
  S.set(KEYS.rec, data);
  
  closeModal('modalRecebivel'); 
  clearRecebivelForm(); 
  renderRecebiveis();
  renderKpis();
}

function clearRecebivelForm(){
  ['r_id','r_pessoa','r_desc','r_valor','r_venc','r_tags'].forEach(i=>byId(i).value='');
  byId('r_status').value='open';
}

function editRecebivel(id){
  const r = S.get(KEYS.rec, []).find(x=>x.id===id); 
  if(!r) return;
  
  byId('r_id').value = r.id;
  byId('r_pessoa').value = r.pessoa||'';
  byId('r_desc').value = r.desc||'';
  byId('r_valor').value = r.valor||'';
  byId('r_venc').value = r.venc||'';
  byId('r_status').value = r.status||'open';
  byId('r_tags').value = r.tags||'';
  
  openModal('modalRecebivel');
}

function delRecebivel(id){
  if(!confirm('🗑️ Excluir este recebível?')) return;
  let data = S.get(KEYS.rec, []);
  data = data.filter(x=>x.id!==id);
  S.set(KEYS.rec, data);
  renderRecebiveis();
  renderKpis();
}

function marcarPago(id){
  const data = S.get(KEYS.rec, []);
  const r = data.find(x=>x.id===id);
  if(r) r.status = 'paid';
  S.set(KEYS.rec, data);
  renderRecebiveis();
  renderKpis();
}

// ====== Despesas CRUD ======
function renderDespesas(){
  const q = (byId('depSearch').value||'').toLowerCase();
  const fp = byId('depFP').value;
  const deps = S.get(KEYS.dep, []).filter(d=> (d.desc||'').toLowerCase().includes(q) || (d.tags||'').toLowerCase().includes(q))
                                           .filter(d=> !fp || d.fp===fp);
  
  const tbody = byId('tblDespesas');
  tbody.innerHTML = deps.map(d=>{
    const tags = (d.tags||'').split(',').filter(x=>x.trim()).map(t=>`<span class="tag">#${t.trim()}</span>`).join(' ');
    const comp = d.comp ? `<a href="${d.comp}" target="_blank">📎</a>` : '—';
    return `<tr>
      <td>${d.data||''}</td>
      <td>${d.desc||''}</td>
      <td class="t-right">${money(d.valor||0)}</td>
      <td>${d.fp||''}</td>
      <td>${tags}</td>
      <td>${comp}</td>
      <td class="actions">
        <button onclick='editDespesa(${JSON.stringify(d.id)})'>✏️</button>
        <button onclick='delDespesa(${JSON.stringify(d.id)})'>🗑️</button>
      </td>
    </tr>`
  }).join('');
  
  // Render chart
  renderDespesasChart(deps);
}

function renderDespesasChart(data){
  const ctx = byId('chartDespesas');
  if(!ctx) return;
  
  const categorias = {};
  data.forEach(d => {
    const tags = (d.tags||'').split(',').map(t => t.trim()).filter(Boolean);
    if(tags.length === 0) tags.push('Sem categoria');
    
    tags.forEach(tag => {
      categorias[tag] = (categorias[tag] || 0) + Number(d.valor||0);
    });
  });
  
  const labels = Object.keys(categorias).slice(0, 10); // Top 10
  const values = labels.map(label => categorias[label]);
  const colors = ['#6a6aff', '#29c989', '#ffb020', '#ff6b6b', '#9c88ff', '#ff9f43', '#26de81', '#fc5c65', '#45aaf2', '#a55eea'];
  
  new Chart(ctx, {
    type: 'bar',
    data: {
      labels: labels,
      datasets: [{
        label: 'Valor (R$)',
        data: values,
        backgroundColor: colors.slice(0, labels.length),
        borderWidth: 0
      }]
    },
    options: {
      responsive: true,
      maintainAspectRatio: false,
      plugins: {
        legend: { display: false }
      },
      scales: {
        x: { ticks: { color: '#b8c2d9' } },
        y: { ticks: { color: '#b8c2d9' } }
      }
    }
  });
}

function salvarDespesa(){
  const file = byId('d_comp').files[0];
  const proceed=(comp)=>{
    const obj = {
      id: byId('d_id').value || cryptoRandomId(),
      data: byId('d_data').value || today(),
      valor: Number(byId('d_valor').value||0),
      desc: byId('d_desc').value.trim(),
      fp: byId('d_fp').value,
      tags: byId('d_tags').value.trim(),
      comp: comp||null
    };
    
    if(!obj.valor || !obj.desc){ 
      alert('❌ Descrição e valor são obrigatórios.'); 
      return; 
    }
    
    const data = S.get(KEYS.dep, []);
    const idx = data.findIndex(x=>x.id===obj.id);
    if(idx>=0) data[idx]=obj; else data.push(obj);
    S.set(KEYS.dep, data);
    
    closeModal('modalDespesa'); 
    clearDespesaForm(); 
    renderDespesas();
    renderKpis();
  };
  
  if(file){
    const reader = new FileReader();
    reader.onload = e => proceed(e.target.result);
    reader.readAsDataURL(file);
  } else {
    proceed(byId('d_prev').src || null);
  }
}

function clearDespesaForm(){
  ['d_id','d_desc','d_valor','d_tags'].forEach(i=>byId(i).value='');
  byId('d_data').value = today();
  byId('d_fp').value='Cartão';
  byId('d_prev').src='';
  byId('d_comp').value='';
}

function editDespesa(id){
  const d = S.get(KEYS.dep, []).find(x=>x.id===id); 
  if(!d) return;
  
  byId('d_id').value = d.id;
  byId('d_data').value = d.data||today();
  byId('d_valor').value = d.valor||'';
  byId('d_desc').value = d.desc||'';
  byId('d_fp').value = d.fp||'Cartão';
  byId('d_tags').value = d.tags||'';
  byId('d_prev').src = d.comp||'';
  
  openModal('modalDespesa');
}

function delDespesa(id){
  if(!confirm('🗑️ Excluir esta despesa?')) return;
  let data = S.get(KEYS.dep, []);
  data = data.filter(x=>x.id!==id);
  S.set(KEYS.dep, data);
  renderDespesas();
  renderKpis();
}

// ====== Faturas CRUD ======
function renderFaturas(){
  const faturas = S.get(KEYS.fat, []);
  
  // Update total
  const total = faturas.filter(f=>f.status!=='paid').reduce((a,b)=>a+Number(b.valor||0),0);
  byId('faturaTotal').textContent = money(total);
  
  // Render table
  const tbody = byId('tblFaturas');
  tbody.innerHTML = faturas.map(f=>{
    const badge = `<span class="badge ${f.status==='paid'?'paid':'open'}">${f.status==='paid'?'Paga':'Em aberto'}</span>`;
    return `<tr>
      <td>${f.cartao||''}</td>
      <td>${f.venc||''}</td>
      <td class="t-right">${money(f.valor||0)}</td>
      <td>${badge}</td>
      <td class="actions">
        <button onclick='editFatura(${JSON.stringify(f.id)})'>✏️</button>
        <button onclick='delFatura(${JSON.stringify(f.id)})'>🗑️</button>
        ${f.status!=='paid'?`<button onclick='marcarFaturaPaga(${JSON.stringify(f.id)})'>✅</button>`:''}
      </td>
    </tr>`
  }).join('');
}

function salvarFatura(){
  const obj = {
    id: byId('f_id').value || cryptoRandomId(),
    cartao: byId('f_cartao').value.trim(),
    valor: Number(byId('f_valor').value||0),
    venc: byId('f_venc').value,
    status: byId('f_status').value
  };
  
  if(!obj.cartao || !obj.valor){ 
    alert('❌ Nome do cartão e valor são obrigatórios.'); 
    return; 
  }
  
  const data = S.get(KEYS.fat, []);
  const idx = data.findIndex(x=>x.id===obj.id);
  if(idx>=0) data[idx]=obj; else data.push(obj);
  S.set(KEYS.fat, data);
  
  closeModal('modalFatura'); 
  clearFaturaForm(); 
  renderFaturas();
  renderKpis();
}

function clearFaturaForm(){
  ['f_id','f_cartao','f_valor','f_venc'].forEach(i=>byId(i).value='');
  byId('f_status').value='open';
}

function editFatura(id){
  const f = S.get(KEYS.fat, []).find(x=>x.id===id); 
  if(!f) return;
  
  byId('f_id').value = f.id;
  byId('f_cartao').value = f.cartao||'';
  byId('f_valor').value = f.valor||'';
  byId('f_venc').value = f.venc||'';
  byId('f_status').value = f.status||'open';
  
  openModal('modalFatura');
}

function delFatura(id){
  if(!confirm('🗑️ Excluir esta fatura?')) return;
  let data = S.get(KEYS.fat, []);
  data = data.filter(x=>x.id!==id);
  S.set(KEYS.fat, data);
  renderFaturas();
  renderKpis();
}

function marcarFaturaPaga(id){
  const data = S.get(KEYS.fat, []);
  const f = data.find(x=>x.id===id);
  if(f) f.status = 'paid';
  S.set(KEYS.fat, data);
  renderFaturas();
  renderKpis();
}

// ====== Cofres CRUD ======
function renderCofres(){
  const cofres = S.get(KEYS.cof, []);
  const grid = byId('cofresGrid');
  
  grid.innerHTML = cofres.map(c=>{
    const progresso = c.meta > 0 ? (c.atual / c.meta * 100) : 0;
    const progressoClass = progresso >= 100 ? 'kpi-positive' : progresso >= 50 ? 'kpi-warn' : 'kpi-bad';
    
    return `<div class="card">
      <h3>🎯 ${c.nome}</h3>
      <div class="big ${progressoClass}">${money(c.atual||0)}</div>
      <div class="small">Meta: ${money(c.meta||0)}</div>
      <div class="small">Progresso: ${progresso.toFixed(1)}%</div>
      ${c.limite ? `<div class="small">Prazo: ${c.limite}</div>` : ''}
      <div class="actions" style="margin-top: 10px;">
        <button onclick='editCofre(${JSON.stringify(c.id)})'>✏️</button>
        <button onclick='delCofre(${JSON.stringify(c.id)})'>🗑️</button>
        <button onclick='adicionarAoCofre(${JSON.stringify(c.id)})'>💰</button>
      </div>
    </div>`
  }).join('') || '<div class="card"><h3>Nenhum cofre criado</h3><p class="small">Crie seu primeiro cofre para começar a economizar!</p></div>';
}

function salvarCofre(){
  const obj = {
    id: byId('c_id').value || cryptoRandomId(),
    nome: byId('c_nome').value.trim(),
    meta: Number(byId('c_meta').value||0),
    atual: Number(byId('c_atual').value||0),
    limite: byId('c_limite').value
  };
  
  if(!obj.nome || !obj.meta){ 
    alert('❌ Nome e valor da meta são obrigatórios.'); 
    return; 
  }
  
  const data = S.get(KEYS.cof, []);
  const idx = data.findIndex(x=>x.id===obj.id);
  if(idx>=0) data[idx]=obj; else data.push(obj);
  S.set(KEYS.cof, data);
  
  closeModal('modalCofre'); 
  clearCofreForm(); 
  renderCofres();
}

function clearCofreForm(){
  ['c_id','c_nome','c_meta','c_atual','c_limite'].forEach(i=>byId(i).value='');
}

function editCofre(id){
  const c = S.get(KEYS.cof, []).find(x=>x.id===id); 
  if(!c) return;
  
  byId('c_id').value = c.id;
  byId('c_nome').value = c.nome||'';
  byId('c_meta').value = c.meta||'';
  byId('c_atual').value = c.atual||'';
  byId('c_limite').value = c.limite||'';
  
  openModal('modalCofre');
}

function delCofre(id){
  if(!confirm('🗑️ Excluir este cofre?')) return;
  let data = S.get(KEYS.cof, []);
  data = data.filter(x=>x.id!==id);
  S.set(KEYS.cof, data);
  renderCofres();
}

function adicionarAoCofre(id){
  const valor = prompt('💰 Quanto deseja adicionar ao cofre?');
  if(!valor || isNaN(valor)) return;
  
  const data = S.get(KEYS.cof, []);
  const c = data.find(x=>x.id===id);
  if(c) {
    c.atual = (c.atual || 0) + Number(valor);
    S.set(KEYS.cof, data);
    renderCofres();
    alert(`✅ ${money(valor)} adicionado ao cofre "${c.nome}"!`);
  }
}

// ====== Dívidas CRUD ======
function renderDividas(){
  const dividas = S.get(KEYS.div, []);
  
  // Update total
  const total = dividas.reduce((a,b)=>a+(Number(b.total||0)-Number(b.pago||0)),0);
  byId('dividaTotal').textContent = money(total);
  
  // Render table
  const tbody = byId('tblDividas');
  tbody.innerHTML = dividas.map(d=>{
    const restante = Number(d.total||0) - Number(d.pago||0);
    const progressoClass = restante <= 0 ? 'kpi-positive' : restante < Number(d.total||0) * 0.5 ? 'kpi-warn' : 'kpi-bad';
    
    return `<tr>
      <td>${d.credor||''}</td>
      <td>${d.desc||''}</td>
      <td class="t-right">${money(d.total||0)}</td>
      <td class="t-right">${money(d.pago||0)}</td>
      <td class="t-right ${progressoClass}">${money(restante)}</td>
      <td>${d.venc||''}</td>
      <td class="actions">
        <button onclick='editDivida(${JSON.stringify(d.id)})'>✏️</button>
        <button onclick='delDivida(${JSON.stringify(d.id)})'>🗑️</button>
        <button onclick='pagarDivida(${JSON.stringify(d.id)})'>💰</button>
      </td>
    </tr>`
  }).join('');
}

function salvarDivida(){
  const obj = {
    id: byId('dv_id').value || cryptoRandomId(),
    credor: byId('dv_credor').value.trim(),
    desc: byId('dv_desc').value.trim(),
    total: Number(byId('dv_total').value||0),
    pago: Number(byId('dv_pago').value||0),
    venc: byId('dv_venc').value
  };
  
  if(!obj.credor || !obj.desc || !obj.total){ 
    alert('❌ Credor, descrição e valor total são obrigatórios.'); 
    return; 
  }
  
  const data = S.get(KEYS.div, []);
  const idx = data.findIndex(x=>x.id===obj.id);
  if(idx>=0) data[idx]=obj; else data.push(obj);
  S.set(KEYS.div, data);
  
  closeModal('modalDivida'); 
  clearDividaForm(); 
  renderDividas();
  renderKpis();
}

function clearDividaForm(){
  ['dv_id','dv_credor','dv_desc','dv_total','dv_pago','dv_venc'].forEach(i=>byId(i).value='');
}

function editDivida(id){
  const d = S.get(KEYS.div, []).find(x=>x.id===id); 
  if(!d) return;
  
  byId('dv_id').value = d.id;
  byId('dv_credor').value = d.credor||'';
  byId('dv_desc').value = d.desc||'';
  byId('dv_total').value = d.total||'';
  byId('dv_pago').value = d.pago||'';
  byId('dv_venc').value = d.venc||'';
  
  openModal('modalDivida');
}

function delDivida(id){
  if(!confirm('🗑️ Excluir esta dívida?')) return;
  let data = S.get(KEYS.div, []);
  data = data.filter(x=>x.id!==id);
  S.set(KEYS.div, data);
  renderDividas();
  renderKpis();
}

function pagarDivida(id){
  const valor = prompt('💰 Quanto deseja pagar desta dívida?');
  if(!valor || isNaN(valor)) return;
  
  const data = S.get(KEYS.div, []);
  const d = data.find(x=>x.id===id);
  if(d) {
    d.pago = (d.pago || 0) + Number(valor);
    if(d.pago > d.total) d.pago = d.total;
    S.set(KEYS.div, data);
    renderDividas();
    renderKpis();
    alert(`✅ ${money(valor)} pago da dívida "${d.desc}"!`);
  }
}

// ====== Pessoas CRUD ======
function renderPessoas(){
  const pessoas = S.get(KEYS.pes, []);
  
  // Update total
  const total = pessoas.reduce((sum, p) => {
    const totalPessoa = (p.lancamentos||[]).filter(l=>!l.pago).reduce((a,b)=>a+Number(b.valor||0),0);
    return sum + totalPessoa;
  }, 0);
  byId('pessoaTotal').textContent = money(total);
  
  // Render list
  const list = byId('pessoasList');
  list.innerHTML = pessoas.map(p=>{
    const lancamentos = p.lancamentos || [];
    const totalPessoa = lancamentos.reduce((a,b)=>a+Number(b.valor||0),0);
    const totalPago = lancamentos.filter(l=>l.pago).reduce((a,b)=>a+Number(b.valor||0),0);
    const totalDevendo = totalPessoa - totalPago;
    
    const lancamentosHtml = lancamentos.map(l => `
      <div class="row" style="justify-content: space-between; align-items: center; padding: 8px; background: var(--muted); border-radius: 8px; margin: 4px 0;">
        <div>
          <div style="font-weight: 500;">${l.desc}</div>
          <div class="small">${l.data} - ${money(l.valor)}</div>
        </div>
        <div class="actions">
          ${!l.pago ? `<button onclick='marcarLancamentoPago(${JSON.stringify(p.id)}, ${JSON.stringify(l.id)})' style="padding: 4px 8px;">✅ Pago</button>` : '<span class="badge paid">Pago</span>'}
          <button onclick='delLancamentoPessoa(${JSON.stringify(p.id)}, ${JSON.stringify(l.id)})' style="padding: 4px 8px;">🗑️</button>
        </div>
      </div>
    `).join('');
    
    return `<div class="card">
      <div class="row" style="justify-content: space-between; align-items: center;">
        <h3>👤 ${p.nome}</h3>
        <div class="actions">
          <button onclick='editPessoa(${JSON.stringify(p.id)})'>✏️</button>
          <button onclick='delPessoa(${JSON.stringify(p.id)})'>🗑️</button>
          <button onclick='adicionarLancamentoPessoa(${JSON.stringify(p.id)})'>+ Lançamento</button>
        </div>
      </div>
      <div class="row" style="margin: 10px 0;">
        <div class="tag">Total: ${money(totalPessoa)}</div>
        <div class="tag">Pago: ${money(totalPago)}</div>
        <div class="tag ${totalDevendo > 0 ? 'kpi-bad' : 'kpi-positive'}">Devendo: ${money(totalDevendo)}</div>
      </div>
      <div style="margin-top: 15px;">
        <h4 style="margin-bottom: 10px;">Lançamentos:</h4>
        ${lancamentosHtml || '<div class="small">Nenhum lançamento</div>'}
      </div>
    </div>`
  }).join('') || '<div class="card"><h3>Nenhuma pessoa cadastrada</h3><p class="small">Adicione pessoas que te devem dinheiro!</p></div>';
}

function salvarPessoa(){
  const obj = {
    id: byId('p_id').value || cryptoRandomId(),
    nome: byId('p_nome').value.trim(),
    lancamentos: []
  };
  
  // Se estamos editando, preservar lançamentos existentes
  if(byId('p_id').value) {
    const existing = S.get(KEYS.pes, []).find(x=>x.id===obj.id);
    if(existing) obj.lancamentos = existing.lancamentos || [];
  }
  
  // Se há dados de lançamento inicial, adicionar
  const desc = byId('p_desc').value.trim();
  const valor = Number(byId('p_valor').value||0);
  const data = byId('p_data').value;
  
  if(desc && valor && !byId('p_id').value) { // Só adiciona se for nova pessoa
    obj.lancamentos.push({
      id: cryptoRandomId(),
      desc: desc,
      valor: valor,
      data: data || today(),
      pago: false
    });
  }
  
  if(!obj.nome){ 
    alert('❌ Nome da pessoa é obrigatório.'); 
    return; 
  }
  
  const data_storage = S.get(KEYS.pes, []);
  const idx = data_storage.findIndex(x=>x.id===obj.id);
  if(idx>=0) data_storage[idx]=obj; else data_storage.push(obj);
  S.set(KEYS.pes, data_storage);
  
  closeModal('modalPessoa'); 
  clearPessoaForm(); 
  renderPessoas();
  renderKpis();
}

function clearPessoaForm(){
  ['p_id','p_nome','p_desc','p_valor','p_data'].forEach(i=>byId(i).value='');
}

function editPessoa(id){
  const p = S.get(KEYS.pes, []).find(x=>x.id===id); 
  if(!p) return;
  
  byId('p_id').value = p.id;
  byId('p_nome').value = p.nome||'';
  // Não preencher dados de lançamento ao editar pessoa
  
  openModal('modalPessoa');
}

function delPessoa(id){
  if(!confirm('🗑️ Excluir esta pessoa e todos os seus lançamentos?')) return;
  let data = S.get(KEYS.pes, []);
  data = data.filter(x=>x.id!==id);
  S.set(KEYS.pes, data);
  renderPessoas();
  renderKpis();
}

function adicionarLancamentoPessoa(pessoaId){
  byId('lp_pid').value = pessoaId;
  ['lp_desc','lp_valor'].forEach(i=>byId(i).value='');
  byId('lp_data').value = today();
  openModal('modalLancamentoPessoa');
}

function salvarLancamentoPessoa(){
  const pessoaId = byId('lp_pid').value;
  const lancamento = {
    id: cryptoRandomId(),
    desc: byId('lp_desc').value.trim(),
    valor: Number(byId('lp_valor').value||0),
    data: byId('lp_data').value || today(),
    pago: false
  };
  
  if(!lancamento.desc || !lancamento.valor){ 
    alert('❌ Descrição e valor são obrigatórios.'); 
    return; 
  }
  
  const data = S.get(KEYS.pes, []);
  const pessoa = data.find(x=>x.id===pessoaId);
  if(pessoa) {
    pessoa.lancamentos = pessoa.lancamentos || [];
    pessoa.lancamentos.push(lancamento);
    S.set(KEYS.pes, data);
    closeModal('modalLancamentoPessoa');
    renderPessoas();
    renderKpis();
  }
}

function marcarLancamentoPago(pessoaId, lancamentoId){
  const data = S.get(KEYS.pes, []);
  const pessoa = data.find(x=>x.id===pessoaId);
  if(pessoa) {
    const lancamento = (pessoa.lancamentos||[]).find(l=>l.id===lancamentoId);
    if(lancamento) {
      lancamento.pago = true;
      S.set(KEYS.pes, data);
      renderPessoas();
      renderKpis();
    }
  }
}

function delLancamentoPessoa(pessoaId, lancamentoId){
  if(!confirm('🗑️ Excluir este lançamento?')) return;
  
  const data = S.get(KEYS.pes, []);
  const pessoa = data.find(x=>x.id===pessoaId);
  if(pessoa) {
    pessoa.lancamentos = (pessoa.lancamentos||[]).filter(l=>l.id!==lancamentoId);
    S.set(KEYS.pes, data);
    renderPessoas();
    renderKpis();
  }
}

// ====== Viagens CRUD ======
function renderViagens(){
  const q = (byId('viagemSearch').value||'').toLowerCase();
  const viagens = S.get(KEYS.via, []).filter(v=> (v.dest||'').toLowerCase().includes(q));
  
  const tbody = byId('tblViagens');
  tbody.innerHTML = viagens.map(v=>{
    const pessoas = (v.part||[]).join(', ');
    const tot = (v.gastos||[]).reduce((a,b)=>a+Number(b.valor||0),0);
    return `<tr>
      <td>${v.dest||''}</td>
      <td>${v.ini||''} → ${v.fim||''}</td>
      <td>${pessoas||'—'}</td>
      <td>${(v.gastos||[]).length}</td>
      <td class="t-right">${money(tot)}</td>
      <td class="actions">
        <button onclick='editViagem(${JSON.stringify(v.id)})'>✏️</button>
        <button onclick='openAddGastoViagem(${JSON.stringify(v.id)})'>+ Gasto</button>
        <button onclick='verGastos(${JSON.stringify(v.id)})'>👁️ Ver</button>
        <button onclick='delViagem(${JSON.stringify(v.id)})'>🗑️</button>
      </td>
    </tr>`
  }).join('');
  
  // Render chart
  renderViagensChart(viagens);
}

function renderViagensChart(data){
  const ctx = byId('chartViagens');
  if(!ctx) return;
  
  const labels = data.map(v => v.dest || 'Sem nome').slice(0, 10);
  const values = data.map(v => (v.gastos||[]).reduce((a,b)=>a+Number(b.valor||0),0)).slice(0, 10);
  const colors = ['#6a6aff', '#29c989', '#ffb020', '#ff6b6b', '#9c88ff', '#ff9f43', '#26de81', '#fc5c65', '#45aaf2', '#a55eea'];
  
  new Chart(ctx, {
    type: 'horizontalBar',
    data: {
      labels: labels,
      datasets: [{
        label: 'Gastos (R$)',
        data: values,
        backgroundColor: colors.slice(0, labels.length),
        borderWidth: 0
      }]
    },
    options: {
      responsive: true,
      maintainAspectRatio: false,
      plugins: {
        legend: { display: false }
      },
      scales: {
        x: { ticks: { color: '#b8c2d9' } },
        y: { ticks: { color: '#b8c2d9' } }
      }
    }
  });
}

function salvarViagem(){
  const obj = {
    id: byId('v_id').value || cryptoRandomId(),
    dest: byId('v_dest').value.trim(),
    ini: byId('v_ini').value,
    fim: byId('v_fim').value,
    part: (byId('v_part').value||'').split(',').map(s=>s.trim()).filter(Boolean),
    gastos: (S.get(KEYS.via, []).find(x=>x.id===byId('v_id').value)||{}).gastos || []
  };
  
  if(!obj.dest || !obj.ini){ 
    alert('❌ Destino e data inicial são obrigatórios.'); 
    return; 
  }
  
  const data = S.get(KEYS.via, []);
  const idx = data.findIndex(x=>x.id===obj.id);
  if(idx>=0) data[idx]=obj; else data.push(obj);
  S.set(KEYS.via, data);
  
  closeModal('modalViagem'); 
  clearViagemForm(); 
  renderViagens();
}

function clearViagemForm(){
  ['v_id','v_dest','v_ini','v_fim','v_part'].forEach(i=>byId(i).value='');
}

function editViagem(id){
  const v = S.get(KEYS.via, []).find(x=>x.id===id); 
  if(!v) return;
  
  byId('v_id').value = v.id;
  byId('v_dest').value = v.dest||'';
  byId('v_ini').value = v.ini||'';
  byId('v_fim').value = v.fim||'';
  byId('v_part').value = (v.part||[]).join(', ');
  
  openModal('modalViagem');
}

function delViagem(id){
  if(!confirm('🗑️ Excluir esta viagem e seus gastos?')) return;
  let data = S.get(KEYS.via, []);
  data = data.filter(x=>x.id!==id);
  S.set(KEYS.via, data);
  renderViagens();
}

function openAddGastoViagem(id){
  byId('gv_vid').value = id;
  ['gv_data','gv_valor','gv_desc'].forEach(i=>byId(i).value='');
  byId('gv_data').value = today();
  byId('gv_prev').src=''; 
  byId('gv_comp').value='';
  openModal('modalGastoViagem');
}

function salvarGastoViagem(){
  const vid = byId('gv_vid').value;
  const file = byId('gv_comp').files[0];
  
  const proceed=(comp)=>{
    const g = {
      id: cryptoRandomId(),
      data: byId('gv_data').value || today(),
      valor: Number(byId('gv_valor').value||0),
      desc: byId('gv_desc').value.trim(),
      comp: comp||null
    };
    
    if(!g.valor || !g.desc){ 
      alert('❌ Descrição e valor são obrigatórios.'); 
      return; 
    }
    
    const data = S.get(KEYS.via, []);
    const v = data.find(x=>x.id===vid); 
    if(!v) return;
    
    v.gastos = v.gastos||[]; 
    v.gastos.push(g);
    S.set(KEYS.via, data);
    
    closeModal('modalGastoViagem'); 
    renderViagens();
  };
  
  if(file){
    const reader = new FileReader();
    reader.onload = e => proceed(e.target.result);
    reader.readAsDataURL(file);
  } else {
    proceed(byId('gv_prev').src || null);
  }
}

function verGastos(id){
  const v = S.get(KEYS.via, []).find(x=>x.id===id); 
  if(!v){ 
    alert('❌ Viagem não encontrada.'); 
    return; 
  }
  
  const linhas = (v.gastos||[]).map(g=>{
    const link = g.comp? `<a href="${g.comp}" target="_blank">📎 comprovante</a>`:'—';
    return `• ${g.data} — ${g.desc} — ${money(g.valor)} ${link}`
  }).join('\n');
  
  const tot = (v.gastos||[]).reduce((a,b)=>a+Number(b.valor||0),0);
  alert(`🧳 Gastos da viagem para ${v.dest}\n\n${linhas||'Sem gastos.'}\n\n💰 Total: ${money(tot)}`);
}

// ====== Relatórios ======
function renderRelatorios(){
  renderFluxoCaixaChart();
  renderComparativoChart();
  renderTendenciasChart();
  renderResumoExecutivo();
}

function renderFluxoCaixaChart(){
  const ctx = byId('chartFluxoCaixa');
  if(!ctx) return;
  
  const deps = S.get(KEYS.dep, []);
  const rec = S.get(KEYS.rec, []);
  
  // Get last 12 months
  const months = [];
  for(let i = 11; i >= 0; i--){
    const date = new Date();
    date.setMonth(date.getMonth() - i);
    months.push(date.toISOString().slice(0,7));
  }
  
  const entradas = months.map(month => {
    return rec.filter(r => (r.venc||'').startsWith(month) && r.status === 'paid')
              .reduce((sum, r) => sum + Number(r.valor||0), 0);
  });
  
  const saidas = months.map(month => {
    return deps.filter(d => (d.data||'').startsWith(month))
              .reduce((sum, d) => sum + Number(d.valor||0), 0);
  });
  
  new Chart(ctx, {
    type: 'line',
    data: {
      labels: months.map(m => new Date(m + '-01').toLocaleDateString('pt-BR', {month: 'short', year: '2-digit'})),
      datasets: [{
        label: 'Entradas',
        data: entradas,
        borderColor: '#29c989',
        backgroundColor: 'rgba(41, 201, 137, 0.1)',
        tension: 0.4,
        fill: true
      }, {
        label: 'Saídas',
        data: saidas,
        borderColor: '#ff6b6b',
        backgroundColor: 'rgba(255, 107, 107, 0.1)',
        tension: 0.4,
        fill: true
      }]
    },
    options: {
      responsive: true,
      maintainAspectRatio: false,
      plugins: {
        legend: {
          labels: { color: '#e9eef6' }
        }
      },
      scales: {
        x: { ticks: { color: '#b8c2d9' } },
        y: { ticks: { color: '#b8c2d9' } }
      }
    }
  });
}

function renderComparativoChart(){
  const ctx = byId('chartComparativo');
  if(!ctx) return;
  
  const currentYear = new Date().getFullYear();
  const lastYear = currentYear - 1;
  
  const deps = S.get(KEYS.dep, []);
  
  const currentYearData = [];
  const lastYearData = [];
  
  for(let month = 0; month < 12; month++){
    const currentMonth = `${currentYear}-${String(month + 1).padStart(2, '0')}`;
    const lastMonth = `${lastYear}-${String(month + 1).padStart(2, '0')}`;
    
    const currentTotal = deps.filter(d => (d.data||'').startsWith(currentMonth))
                            .reduce((sum, d) => sum + Number(d.valor||0), 0);
    const lastTotal = deps.filter(d => (d.data||'').startsWith(lastMonth))
                         .reduce((sum, d) => sum + Number(d.valor||0), 0);
    
    currentYearData.push(currentTotal);
    lastYearData.push(lastTotal);
  }
  
  new Chart(ctx, {
    type: 'bar',
    data: {
      labels: ['Jan', 'Fev', 'Mar', 'Abr', 'Mai', 'Jun', 'Jul', 'Ago', 'Set', 'Out', 'Nov', 'Dez'],
      datasets: [{
        label: currentYear.toString(),
        data: currentYearData,
        backgroundColor: '#6a6aff',
        borderWidth: 0
      }, {
        label: lastYear.toString(),
        data: lastYearData,
        backgroundColor: '#9c88ff',
        borderWidth: 0
      }]
    },
    options: {
      responsive: true,
      maintainAspectRatio: false,
      plugins: {
        legend: {
          labels: { color: '#e9eef6' }
        }
      },
      scales: {
        x: { ticks: { color: '#b8c2d9' } },
        y: { ticks: { color: '#b8c2d9' } }
      }
    }
  });
}

function renderTendenciasChart(){
  const ctx = byId('chartTendencias');
  if(!ctx) return;
  
  const deps = S.get(KEYS.dep, []);
  
  // Análise por categoria nos últimos 6 meses
  const months = [];
  for(let i = 5; i >= 0; i--){
    const date = new Date();
    date.setMonth(date.getMonth() - i);
    months.push(date.toISOString().slice(0,7));
  }
  
  // Pegar top 5 categorias
  const allCategories = {};
  deps.forEach(d => {
    const tags = (d.tags||'').split(',').map(t => t.trim()).filter(Boolean);
    if(tags.length === 0) tags.push('Sem categoria');
    
    tags.forEach(tag => {
      allCategories[tag] = (allCategories[tag] || 0) + Number(d.valor||0);
    });
  });
  
  const topCategories = Object.entries(allCategories)
    .sort((a, b) => b[1] - a[1])
    .slice(0, 5)
    .map(([cat]) => cat);
  
  const datasets = topCategories.map((category, index) => {
    const colors = ['#6a6aff', '#29c989', '#ffb020', '#ff6b6b', '#9c88ff'];
    const data = months.map(month => {
      return deps.filter(d => (d.data||'').startsWith(month) && 
                             (d.tags||'').split(',').map(t => t.trim()).includes(category))
                .reduce((sum, d) => sum + Number(d.valor||0), 0);
    });
    
    return {
      label: category,
      data: data,
      borderColor: colors[index],
      backgroundColor: colors[index] + '20',
      tension: 0.4
    };
  });
  
  new Chart(ctx, {
    type: 'line',
    data: {
      labels: months.map(m => new Date(m + '-01').toLocaleDateString('pt-BR', {month: 'short'})),
      datasets: datasets
    },
    options: {
      responsive: true,
      maintainAspectRatio: false,
      plugins: {
        legend: {
          labels: { color: '#e9eef6' }
        }
      },
      scales: {
        x: { ticks: { color: '#b8c2d9' } },
        y: { ticks: { color: '#b8c2d9' } }
      }
    }
  });
}

function renderResumoExecutivo(){
  const rec = S.get(KEYS.rec, []);
  const deps = S.get(KEYS.dep, []);
  const fat = S.get(KEYS.fat, []);
  const div = S.get(KEYS.div, []);
  const pes = S.get(KEYS.pes, []);
  const cof = S.get(KEYS.cof, []);
  
  const totalRecebiveis = rec.filter(r=>r.status!=='paid').reduce((a,b)=>a+Number(b.valor||0),0);
  const totalDespesas = deps.reduce((a,b)=>a+Number(b.valor||0),0);
  const totalFaturas = fat.filter(f=>f.status!=='paid').reduce((a,b)=>a+Number(b.valor||0),0);
  const totalDividas = div.reduce((a,b)=>a+(Number(b.total||0)-Number(b.pago||0)),0);
  const totalPessoas = pes.reduce((sum, p) => {
    return sum + (p.lancamentos||[]).filter(l=>!l.pago).reduce((a,b)=>a+Number(b.valor||0),0);
  }, 0);
  const totalCofres = cof.reduce((a,b)=>a+Number(b.atual||0),0);
  
  const saldoLiquido = totalRecebiveis + totalPessoas + totalCofres - totalDespesas - totalFaturas - totalDividas;
  
  const resumo = byId('resumoExecutivo');
  resumo.innerHTML = `
    <div class="grid" style="grid-template-columns: repeat(auto-fit, minmax(150px, 1fr)); gap: 10px;">
      <div class="small">
        <strong>💸 Recebíveis:</strong><br>
        ${money(totalRecebiveis)}
      </div>
      <div class="small">
        <strong>👥 Pessoas:</strong><br>
        ${money(totalPessoas)}
      </div>
      <div class="small">
        <strong>🎯 Cofres:</strong><br>
        ${money(totalCofres)}
      </div>
      <div class="small">
        <strong>🧾 Despesas:</strong><br>
        ${money(totalDespesas)}
      </div>
      <div class="small">
        <strong>💳 Faturas:</strong><br>
        ${money(totalFaturas)}
      </div>
      <div class="small">
        <strong>💰 Dívidas:</strong><br>
        ${money(totalDividas)}
      </div>
    </div>
    <hr style="margin: 15px 0;">
    <div class="big ${saldoLiquido >= 0 ? 'kpi-positive' : 'kpi-bad'}" style="text-align: center;">
      Saldo Líquido: ${money(saldoLiquido)}
    </div>
    <div class="small" style="text-align: center; margin-top: 10px;">
      Score Financeiro: ${calcularScore()}/1000
    </div>
  `;
}

// ====== Configurações ======
function renderConfig(){
  const stats = byId('estatisticasSistema');
  const totalTransacoes = S.get(KEYS.rec, []).length + S.get(KEYS.dep, []).length + 
                         S.get(KEYS.fat, []).length + S.get(KEYS.div, []).length + 
                         S.get(KEYS.pes, []).length + S.get(KEYS.via, []).length + 
                         S.get(KEYS.cof, []).length;
  
  const dataSize = JSON.stringify({
    recebiveis: S.get(KEYS.rec, []),
    despesas: S.get(KEYS.dep, []),
    faturas: S.get(KEYS.fat, []),
    dividas: S.get(KEYS.div, []),
    pessoas: S.get(KEYS.pes, []),
    viagens: S.get(KEYS.via, []),
    cofres: S.get(KEYS.cof, [])
  }).length;
  
  stats.innerHTML = `
    <div class="small">📊 Total de registros: ${totalTransacoes}</div>
    <div class="small">💾 Tamanho dos dados: ${(dataSize/1024).toFixed(2)} KB</div>
    <div class="small">📅 Último acesso: ${new Date().toLocaleString('pt-BR')}</div>
    <div class="small">🔧 Versão: PRO MAX 2.0</div>
  `;
}

function configurarCategorias(){
  alert('🏷️ Funcionalidade em desenvolvimento!\n\nEm breve você poderá gerenciar suas categorias personalizadas.');
}

function configurarRecorrentes(){
  alert('🔄 Funcionalidade em desenvolvimento!\n\nEm breve você poderá configurar lançamentos recorrentes automáticos.');
}

function configurarNotificacoes(){
  alert('🔔 Funcionalidade em desenvolvimento!\n\nEm breve você poderá configurar notificações de vencimentos e lembretes.');
}

// ====== Recorrentes ======
function duplicarRecorrentes(){
  const templates = S.get(KEYS.recTemplates, [
    {desc:'💪 Mensalidade Academia', valor:189.99, fp:'Cartão', tags:'recorrente,saúde'},
    {desc:'🏠 Aluguel', valor:1200.00, fp:'PIX', tags:'recorrente,moradia'},
    {desc:'📱 Plano Celular', valor:89.90, fp:'Cartão', tags:'recorrente,telefone'}
  ]);
  
  // Duplicate templates for current month
  const month = today().slice(0,7);
  let deps = S.get(KEYS.dep, []);
  let added = 0;
  
  templates.forEach(t=>{
    const exists = deps.some(d=>d.desc===t.desc && (d.data||'').startsWith(month));
    if(!exists){
      deps.push({
        id:cryptoRandomId(), 
        data:today(), 
        valor:t.valor, 
        desc:t.desc, 
        fp:t.fp, 
        tags:t.tags, 
        comp:null
      });
      added++;
    }
  });
  
  S.set(KEYS.dep, deps);
  alert(`✅ ${added} lançamento(s) recorrente(s) adicionado(s) para o mês atual.`);
  renderDespesas(); 
  renderKpis();
}

// ====== Export/Backup ======
function exportCSV(section){
  let data = [];
  let filename = 'dados.csv';
  
  if(section === 'recebiveis') {
    data = S.get(KEYS.rec, []);
    filename = 'recebiveis.csv';
  } else if(section === 'despesas') {
    data = S.get(KEYS.dep, []);
    filename = 'despesas.csv';
  }
  
  if(data.length === 0) {
    alert('❌ Nenhum dado para exportar.');
    return;
  }
  
  // Convert to CSV
  const headers = Object.keys(data[0]);
  const csvContent = [
    headers.join(','),
    ...data.map(row => headers.map(header => `"${row[header] || ''}"`).join(','))
  ].join('\n');
  
  const blob = new Blob([csvContent], {type:'text/csv;charset=utf-8;'});
  const a = document.createElement('a');
  a.href = URL.createObjectURL(blob);
  a.download = filename;
  a.click();
}

function exportJSON(section){
  let data = null, fname = 'dados.json';
  
  if(section==='recebiveis'){ data = S.get(KEYS.rec, []); fname='recebiveis.json';}
  else if(section==='despesas'){ data = S.get(KEYS.dep, []); fname='despesas.json';}
  else if(section==='faturas'){ data = S.get(KEYS.fat, []); fname='faturas.json';}
  else if(section==='cofres'){ data = S.get(KEYS.cof, []); fname='cofres.json';}
  else if(section==='dividas'){ data = S.get(KEYS.div, []); fname='dividas.json';}
  else if(section==='pessoas'){ data = S.get(KEYS.pes, []); fname='pessoas.json';}
  else if(section==='viagens'){ data = S.get(KEYS.via, []); fname='viagens.json';}
  
  if(!data) return;
  
  const blob = new Blob([JSON.stringify(data,null,2)], {type:'application/json'});
  const a = document.createElement('a');
  a.href = URL.createObjectURL(blob);
  a.download = fname;
  a.click();
}

function backupCompleto(){
  const data = {
    recebiveis: S.get(KEYS.rec, []),
    despesas: S.get(KEYS.dep, []),
    faturas: S.get(KEYS.fat, []),
    cofres: S.get(KEYS.cof, []),
    dividas: S.get(KEYS.div, []),
    pessoas: S.get(KEYS.pes, []),
    viagens: S.get(KEYS.via, []),
    recorrentes: S.get(KEYS.recTemplates, []),
    backup_date: new Date().toISOString(),
    version: 'PRO MAX 2.0'
  };
  
  const blob = new Blob([JSON.stringify(data,null,2)], {type:'application/json'});
  const a = document.createElement('a');
  a.href = URL.createObjectURL(blob);
  a.download = `backup_ruiz_finance_${today()}.json`;
  a.click();
}

function restaurarBackup(){
  const inp = byId('restoreFile');
  const file = inp.files && inp.files[0];
  if(!file){ 
    alert('❌ Selecione um arquivo de backup JSON.'); 
    return; 
  }
  
  const reader = new FileReader();
  reader.onload = e => {
    try{
      const data = JSON.parse(e.target.result);
      
      if(data.recebiveis) S.set(KEYS.rec, data.recebiveis);
      if(data.despesas) S.set(KEYS.dep, data.despesas);
      if(data.faturas) S.set(KEYS.fat, data.faturas);
      if(data.cofres) S.set(KEYS.cof, data.cofres);
      if(data.dividas) S.set(KEYS.div, data.dividas);
      if(data.pessoas) S.set(KEYS.pes, data.pessoas);
      if(data.viagens) S.set(KEYS.via, data.viagens);
      if(data.recorrentes) S.set(KEYS.recTemplates, data.recorrentes);
      
      alert('✅ Backup restaurado com sucesso!');
      
      // Refresh all views
      renderDashboard();
      renderRecebiveis(); 
      renderDespesas();
      renderFaturas();
      renderCofres();
      renderDividas();
      renderPessoas();
      renderViagens();
      renderRelatorios();
      renderConfig();
      
    }catch(err){ 
      alert('❌ Arquivo de backup inválido.'); 
    }
  };
  reader.readAsText(file);
}

// ====== Utils ======
function cryptoRandomId(){
  if(window.crypto && crypto.randomUUID) return crypto.randomUUID();
  return 'id_'+Math.random().toString(36).slice(2);
}

// Mobile dropdown toggle
document.addEventListener('click', function(e) {
  if (window.innerWidth <= 768) {
    const dropdown = e.target.closest('.dropdown');
    if (dropdown) {
      e.preventDefault();
      dropdown.classList.toggle('mobile-open');
      
      // Close other dropdowns
      document.querySelectorAll('.dropdown').forEach(d => {
        if (d !== dropdown) d.classList.remove('mobile-open');
      });
    } else {
      // Close all dropdowns when clicking outside
      document.querySelectorAll('.dropdown').forEach(d => {
        d.classList.remove('mobile-open');
      });
    }
  }
});
</script>
</body>
</html>

