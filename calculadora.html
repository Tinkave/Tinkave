<!DOCTYPE html>
<!--
═══════════════════════════════════════════════════════════════
  CALCULADORA TÊXTIL TINKAVE
  © 2026 Tinkave — Tinturaria & Acabamentos · tinkave.pt
  Todos os direitos reservados.
  Proibida a cópia, reprodução ou distribuição sem autorização.
═══════════════════════════════════════════════════════════════
-->
<html lang="pt">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0, viewport-fit=cover">
<title>Calculadora Têxtil — Tinkave</title>
<meta name="theme-color" content="#2c4a3e">
<meta name="mobile-web-app-capable" content="yes">
<meta name="apple-mobile-web-app-capable" content="yes">
<meta name="apple-mobile-web-app-status-bar-style" content="black-translucent">
<meta name="apple-mobile-web-app-title" content="Tinkave">
<link rel="manifest" id="manifest-link">
<link rel="apple-touch-icon" id="apple-icon">
<script src="https://cdnjs.cloudflare.com/ajax/libs/jspdf/2.5.1/jspdf.umd.min.js"></script>
<style>
*{box-sizing:border-box;margin:0;padding:0}
:root{
  --ink:#1a1a1a;--ink2:#555;--ink3:#888;
  --surface:#fff;--surface2:#f7f6f4;
  --border:#e2ddd7;--border2:#c8c0b5;
  --accent:#2c4a3e;--accent2:#3d6b5c;--accent-light:#e8f0ed;
  --gold:#8b6914;--gold-light:#fdf6e3;
  --radius:10px;--radius-sm:6px;
}
body{font-family:'Georgia',serif;color:var(--ink);background:var(--surface2);min-height:100vh}

.app-header{background:var(--accent);color:#fff;padding:1.5rem 1.25rem 1.25rem;position:relative;overflow:hidden;text-align:center}
.app-header::after{content:'';position:absolute;right:-40px;top:-40px;width:180px;height:180px;border-radius:50%;background:rgba(255,255,255,.05)}
.app-header::before{content:'';position:absolute;left:-50px;bottom:-50px;width:140px;height:140px;border-radius:50%;background:rgba(255,255,255,.04)}
.logo-badge{position:absolute;left:1.25rem;top:1.5rem;width:58px;height:58px;border-radius:50%;background:#15171e;display:flex;align-items:center;justify-content:center;box-shadow:0 2px 8px rgba(0,0,0,.35);z-index:2}
.lang-row{position:absolute;right:1rem;top:1.1rem;display:flex;gap:4px;z-index:3}
.lang-btn{padding:4px 8px;font-size:11px;font-family:system-ui,sans-serif;font-weight:600;border:1px solid rgba(255,255,255,.3);border-radius:6px;background:rgba(255,255,255,.08);color:rgba(255,255,255,.7);cursor:pointer;transition:all .2s}
.lang-btn.active{background:#fff;color:var(--accent);border-color:#fff}
.lang-btn:hover:not(.active){background:rgba(255,255,255,.2);color:#fff}
.brand-name{font-size:24px;font-weight:700;color:#fff;font-family:system-ui,sans-serif;letter-spacing:.12em;line-height:1}
.brand-sub{font-size:11px;color:rgba(255,255,255,.65);font-family:system-ui,sans-serif;margin-top:4px}
.brand-sub a{color:rgba(255,255,255,.85);text-decoration:underline;text-underline-offset:2px}
.app-header h1{font-size:14px;font-weight:400;letter-spacing:.08em;color:rgba(255,255,255,.8);font-family:system-ui,sans-serif;text-transform:uppercase;margin-top:.5rem;position:relative}
.app-header p{font-size:11px;color:rgba(255,255,255,.5);letter-spacing:.07em;text-transform:uppercase;font-family:system-ui,sans-serif;margin-top:3px;position:relative}

.tabs-wrap{background:var(--accent);padding:0 1.25rem;border-bottom:1px solid rgba(255,255,255,.12)}
.tabs{display:flex;gap:0;justify-content:center}
.tab{padding:11px 14px;font-size:11px;font-family:system-ui,sans-serif;letter-spacing:.05em;text-transform:uppercase;border:none;background:transparent;color:rgba(255,255,255,.5);cursor:pointer;border-bottom:2px solid transparent;margin-bottom:-1px;transition:all .2s}
.tab.active{color:#fff;border-bottom-color:#fff}
.tab:hover:not(.active){color:rgba(255,255,255,.8)}

.app-body{padding:1.5rem 1rem 3rem;display:flex;flex-direction:column;gap:1.25rem;max-width:720px;margin:0 auto}
.panel{display:none;flex-direction:column;gap:1.25rem}
.panel.active{display:flex}

.card{background:var(--surface);border:1px solid var(--border);border-radius:var(--radius);overflow:hidden}
.card-head{padding:.875rem 1.25rem;border-bottom:1px solid var(--border);display:flex;align-items:center;justify-content:space-between}
.card-head h3{font-size:13px;font-weight:400;letter-spacing:.07em;text-transform:uppercase;color:var(--ink2);font-family:system-ui,sans-serif}
.badge{font-size:10px;font-family:system-ui,sans-serif;padding:3px 9px;border-radius:20px;background:var(--accent-light);color:var(--accent);letter-spacing:.05em;font-weight:500;border:1px solid rgba(44,74,62,.15)}
.card-body{padding:1.25rem}

.tipo-row{display:flex;gap:6px;flex-wrap:wrap}
.tipo-btn{padding:7px 14px;font-size:12px;font-family:system-ui,sans-serif;border:1px solid var(--border2);border-radius:20px;background:transparent;color:var(--ink3);cursor:pointer;transition:all .2s}
.tipo-btn.active{background:var(--accent);color:#fff;border-color:var(--accent)}
.tipo-btn:hover:not(.active){border-color:var(--accent);color:var(--accent)}

.field{display:flex;flex-direction:column;gap:5px}
.field label{font-size:11px;font-family:system-ui,sans-serif;letter-spacing:.06em;text-transform:uppercase;color:var(--ink3)}
.field input,.field select{width:100%;padding:9px 12px;font-size:14px;font-family:'Georgia',serif;border:1px solid var(--border);border-radius:var(--radius-sm);background:var(--surface2);color:var(--ink);transition:border .2s}
.field input:focus,.field select:focus{outline:none;border-color:var(--accent2);background:#fff}
.field input[readonly]{background:var(--accent-light);border-color:rgba(44,74,62,.25);color:var(--accent)}
.field.out label{color:var(--accent)}

.grid2{display:grid;grid-template-columns:1fr 1fr;gap:12px}
.grid3{display:grid;grid-template-columns:1fr 1fr 1fr;gap:12px}
.grid4{display:grid;grid-template-columns:1.2fr 1fr 1fr 1fr;gap:12px}

.sub{padding:1rem 1.25rem}
.sub+.sub{border-top:1px solid var(--border)}
.sub-label{font-size:10px;font-family:system-ui,sans-serif;letter-spacing:.1em;text-transform:uppercase;color:var(--ink3);margin-bottom:.75rem;display:flex;align-items:center;gap:8px}
.sub-label::after{content:'';flex:1;height:1px;background:var(--border)}

.larg-group{display:flex;gap:8px;align-items:flex-end;max-width:320px}
.larg-group .field{flex:1}
.unit-sel{padding:9px 8px;font-size:13px;font-family:system-ui,sans-serif;border:1px solid var(--border);border-radius:var(--radius-sm);background:var(--surface2);color:var(--ink);cursor:pointer;height:38px}
.unit-sel:focus{outline:none;border-color:var(--accent2)}

.results-wrap{background:var(--surface2);border-top:1px solid var(--border);padding:1.25rem}
.results-title{font-size:10px;font-family:system-ui,sans-serif;letter-spacing:.1em;text-transform:uppercase;color:var(--ink3);margin-bottom:1rem;display:flex;align-items:center;gap:8px}
.results-title::after{content:'';flex:1;height:1px;background:var(--border)}
.result-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(140px,1fr));gap:10px}
.rcard{background:var(--surface);border:1px solid var(--border);border-radius:var(--radius-sm);padding:1rem 1.125rem}
.rcard.gold{background:var(--gold-light);border-color:rgba(139,105,20,.25)}
.rcard .rlabel{font-size:11px;font-family:system-ui,sans-serif;color:var(--ink3);margin-bottom:6px;line-height:1.4}
.rcard .rval{font-size:24px;font-weight:400;line-height:1;color:var(--ink)}
.rcard.gold .rval{color:var(--gold)}
.rcard .runit{font-size:12px;color:var(--ink3);margin-top:4px;font-family:system-ui,sans-serif}

.btn-row{display:flex;gap:8px;flex-wrap:wrap;padding:1rem 1.25rem}
.btn{padding:9px 22px;font-size:12px;font-family:system-ui,sans-serif;letter-spacing:.07em;text-transform:uppercase;border-radius:var(--radius-sm);cursor:pointer;transition:all .2s;border:1px solid}
.btn.primary{background:var(--accent);color:#fff;border-color:var(--accent)}
.btn.primary:hover{background:var(--accent2)}
.btn.ghost{background:transparent;color:var(--ink2);border-color:var(--border2)}
.btn.ghost:hover{border-color:var(--accent);color:var(--accent)}
.error{font-size:13px;color:#8b2a2a;padding:.5rem 1.25rem;font-family:system-ui,sans-serif}

.conv-table{width:100%;border-collapse:collapse;font-family:system-ui,sans-serif}
.conv-table thead tr{background:var(--surface2)}
.conv-table th{text-align:left;padding:9px 14px;font-size:10px;letter-spacing:.08em;text-transform:uppercase;color:var(--ink3);border-bottom:1px solid var(--border);font-weight:500}
.conv-table td{padding:11px 14px;border-bottom:1px solid var(--border);font-size:14px;color:var(--ink2)}
.conv-table td:last-child{font-size:18px;font-family:'Georgia',serif;color:var(--ink);text-align:right}
.conv-table tr.origin{background:var(--accent-light)}
.conv-table tr.origin td{color:var(--accent)}
.conv-table tr:last-child td{border-bottom:none}
.origin-tag{font-size:10px;background:var(--accent);color:#fff;padding:2px 7px;border-radius:10px;margin-left:6px;vertical-align:middle}

.qrow{display:grid;grid-template-columns:1fr 1fr 32px 1fr;gap:12px;align-items:end}
.conv-row{grid-template-columns:1fr 32px 1fr}
.arrow{display:flex;align-items:center;justify-content:center;height:38px;color:var(--border2);font-size:20px;font-family:system-ui,sans-serif}
.note{font-size:12px;color:var(--ink3);margin-top:10px;font-style:italic;font-family:system-ui,sans-serif;line-height:1.5}
.project-input{width:100%;padding:10px 14px;font-size:16px;font-family:'Georgia',serif;border:none;border-bottom:1.5px solid var(--border2);background:transparent;color:var(--ink)}
.project-input:focus{outline:none;border-bottom-color:var(--accent)}
.project-input::placeholder{color:var(--ink3)}

.app-footer{text-align:center;padding:1.5rem 1rem 2rem;font-family:system-ui,sans-serif}
.app-footer .copy{font-size:11px;color:var(--ink3);line-height:1.6}
.app-footer .copy a{color:var(--accent);text-decoration:none}

@media(max-width:560px){
  .grid2,.grid3,.grid4{grid-template-columns:1fr}
  .qrow{grid-template-columns:1fr 1fr}
  .arrow{display:none}
  .result-grid{grid-template-columns:1fr 1fr}
  .tab{padding:10px 8px;font-size:10px}
}
</style>
</head>
<body>

<div class="app-header">
  <div class="lang-row">
    <button class="lang-btn active" id="lang-pt" onclick="setLang('pt')">PT</button>
    <button class="lang-btn" id="lang-es" onclick="setLang('es')">ES</button>
    <button class="lang-btn" id="lang-fr" onclick="setLang('fr')">FR</button>
    <button class="lang-btn" id="lang-en" onclick="setLang('en')">EN</button>
  </div>
  <div class="logo-badge">
    <svg width="50" height="50" viewBox="0 0 100 100" xmlns="http://www.w3.org/2000/svg">
      <defs>
        <linearGradient id="tg" x1="92%" y1="20%" x2="8%" y2="80%">
          <stop offset="0%" stop-color="#e2542b"/><stop offset="40%" stop-color="#b04434"/>
          <stop offset="75%" stop-color="#4a4566"/><stop offset="100%" stop-color="#2f3b64"/>
        </linearGradient>
        <clipPath id="c0"><circle cx="50" cy="50" r="46"/></clipPath>
        <clipPath id="w1"><path d="M50,50 L-2.9,-22.8 L102.9,-22.8 Z"/></clipPath>
        <clipPath id="w2"><path d="M50,50 L102.9,-22.8 L135.6,77.8 Z"/></clipPath>
        <clipPath id="w3"><path d="M50,50 L135.6,77.8 L50,140 Z"/></clipPath>
        <clipPath id="w4"><path d="M50,50 L50,140 L-35.6,77.8 Z"/></clipPath>
        <clipPath id="w5"><path d="M50,50 L-35.6,77.8 L-2.9,-22.8 Z"/></clipPath>
        <g id="ln"><path d="M-45 -4H145M-45 7H145M-45 18H145M-45 29H145M-45 40H145M-45 51H145M-45 62H145M-45 73H145M-45 84H145M-45 95H145M-45 106H145" stroke="url(#tg)" stroke-width="6.5" fill="none"/></g>
      </defs>
      <g clip-path="url(#c0)">
        <g clip-path="url(#w1)"><g transform="rotate(45 50 50)"><use href="#ln"/></g></g>
        <g clip-path="url(#w2)"><g transform="rotate(-55 50 50)"><use href="#ln"/></g></g>
        <g clip-path="url(#w3)"><g transform="rotate(15 50 50)"><use href="#ln"/></g></g>
        <g clip-path="url(#w4)"><g transform="rotate(75 50 50)"><use href="#ln"/></g></g>
        <g clip-path="url(#w5)"><g transform="rotate(-45 50 50)"><use href="#ln"/></g></g>
      </g>
    </svg>
  </div>
  <div class="brand-name">TINKAVE</div>
  <div class="brand-sub">Tinturaria &amp; Acabamentos &nbsp;·&nbsp; <a href="https://tinkave.pt" target="_blank">tinkave.pt</a></div>
  <h1 data-i18n="appTitle">Calculadora Têxtil</h1>
  <p data-i18n="appSub">Gramagem · Peso por metro linear · Conversão de títulos</p>
</div>

<div class="tabs-wrap">
  <div class="tabs">
    <button class="tab active" onclick="showTab('gramagem')" data-i18n="tabGram">Gramagem</button>
    <button class="tab" onclick="showTab('conversao')" data-i18n="tabConv">Títulos</button>
    <button class="tab" onclick="showTab('rapidos')" data-i18n="tabFast">Cálculos rápidos</button>
  </div>
</div>

<div class="app-body">

<!-- ===== GRAMAGEM ===== -->
<div class="panel active" id="tab-gramagem">

  <div class="card">
    <div class="card-head"><h3 data-i18n="projeto">Projeto</h3></div>
    <div class="card-body" style="display:flex;flex-direction:column;gap:1.125rem">
      <input class="project-input" type="text" id="nome-projeto" data-i18n-ph="nomeProjeto" placeholder="Nome do projeto…">
      <div class="field">
        <label data-i18n="tipoCalc">Tipo de cálculo</label>
        <div class="tipo-row" style="margin-top:4px">
          <button class="tipo-btn active" id="tipo-algodao" onclick="setTipo('algodao')" data-i18n="matAlgodao">Algodão (Ne)</button>
          <button class="tipo-btn" id="tipo-linho" onclick="setTipo('linho')" data-i18n="matLinho">Linho (Nm)</button>
          <button class="tipo-btn" id="tipo-poliester" onclick="setTipo('poliester')" data-i18n="matPoli">Poliéster (Dtex)</button>
          <button class="tipo-btn" id="tipo-mistura" onclick="setTipo('mistura')" data-i18n="matMistura">Mistura de fibras</button>
        </div>
      </div>
    </div>
  </div>

  <!-- ALGODÃO -->
  <div class="card mat-bloco" id="bloco-algodao">
    <div class="card-head"><h3>Algodão</h3><span class="badge">Ne · Fios/pol</span></div>
    <div class="sub">
      <div class="sub-label"><span class="lbl-teia">Teia</span></div>
      <div class="grid3">
        <div class="field"><label class="lbl-fios">Fios/polegada</label><input type="text" inputmode="decimal" id="al-ft" placeholder="0" step="any" min="0"></div>
        <div class="field"><label>Ne</label><input type="text" inputmode="decimal" id="al-net" placeholder="0" step="any" min="0"></div>
        <div class="field"><label class="lbl-enc">Encolhimento %</label><input type="text" inputmode="decimal" id="al-et" placeholder="0" step="any" min="0" max="100"></div>
      </div>
    </div>
    <div class="sub">
      <div class="sub-label"><span class="lbl-trama">Trama</span></div>
      <div class="grid3">
        <div class="field"><label class="lbl-fios">Fios/polegada</label><input type="text" inputmode="decimal" id="al-ftr" placeholder="0" step="any" min="0"></div>
        <div class="field"><label>Ne</label><input type="text" inputmode="decimal" id="al-netr" placeholder="0" step="any" min="0"></div>
        <div class="field"><label class="lbl-enc">Encolhimento %</label><input type="text" inputmode="decimal" id="al-etr" placeholder="0" step="any" min="0" max="100"></div>
      </div>
    </div>
    <div class="sub">
      <div class="larg-group">
        <div class="field"><label class="lbl-larg">Largura da tela</label><input type="text" inputmode="decimal" id="al-larg" placeholder="0" step="any" min="0"></div>
        <select class="unit-sel" id="al-un"><option value="cm">cm</option><option value="pol">pol</option></select>
      </div>
    </div>
  </div>

  <!-- LINHO -->
  <div class="card mat-bloco" id="bloco-linho" style="display:none">
    <div class="card-head"><h3>Linho</h3><span class="badge">Nm · Fios/pol</span></div>
    <div class="sub">
      <div class="sub-label"><span class="lbl-teia">Teia</span></div>
      <div class="grid3">
        <div class="field"><label class="lbl-fios">Fios/polegada</label><input type="text" inputmode="decimal" id="li-ft" placeholder="0" step="any" min="0"></div>
        <div class="field"><label>Nm</label><input type="text" inputmode="decimal" id="li-nmt" placeholder="0" step="any" min="0"></div>
        <div class="field"><label class="lbl-enc">Encolhimento %</label><input type="text" inputmode="decimal" id="li-et" placeholder="0" step="any" min="0" max="100"></div>
      </div>
    </div>
    <div class="sub">
      <div class="sub-label"><span class="lbl-trama">Trama</span></div>
      <div class="grid3">
        <div class="field"><label class="lbl-fios">Fios/polegada</label><input type="text" inputmode="decimal" id="li-ftr" placeholder="0" step="any" min="0"></div>
        <div class="field"><label>Nm</label><input type="text" inputmode="decimal" id="li-nmtr" placeholder="0" step="any" min="0"></div>
        <div class="field"><label class="lbl-enc">Encolhimento %</label><input type="text" inputmode="decimal" id="li-etr" placeholder="0" step="any" min="0" max="100"></div>
      </div>
    </div>
    <div class="sub">
      <div class="larg-group">
        <div class="field"><label class="lbl-larg">Largura da tela</label><input type="text" inputmode="decimal" id="li-larg" placeholder="0" step="any" min="0"></div>
        <select class="unit-sel" id="li-un"><option value="cm">cm</option><option value="pol">pol</option></select>
      </div>
    </div>
  </div>

  <!-- POLIÉSTER -->
  <div class="card mat-bloco" id="bloco-poliester" style="display:none">
    <div class="card-head"><h3>Poliéster</h3><span class="badge">Dtex · Fios/pol</span></div>
    <div class="sub">
      <div class="sub-label"><span class="lbl-teia">Teia</span></div>
      <div class="grid3">
        <div class="field"><label class="lbl-fios">Fios/polegada</label><input type="text" inputmode="decimal" id="po-ft" placeholder="0" step="any" min="0"></div>
        <div class="field"><label>Dtex</label><input type="text" inputmode="decimal" id="po-dt" placeholder="0" step="any" min="0"></div>
        <div class="field"><label class="lbl-enc">Encolhimento %</label><input type="text" inputmode="decimal" id="po-et" placeholder="0" step="any" min="0" max="100"></div>
      </div>
    </div>
    <div class="sub">
      <div class="sub-label"><span class="lbl-trama">Trama</span></div>
      <div class="grid3">
        <div class="field"><label class="lbl-fios">Fios/polegada</label><input type="text" inputmode="decimal" id="po-ftr" placeholder="0" step="any" min="0"></div>
        <div class="field"><label>Dtex</label><input type="text" inputmode="decimal" id="po-dtr" placeholder="0" step="any" min="0"></div>
        <div class="field"><label class="lbl-enc">Encolhimento %</label><input type="text" inputmode="decimal" id="po-etr" placeholder="0" step="any" min="0" max="100"></div>
      </div>
    </div>
    <div class="sub">
      <div class="larg-group">
        <div class="field"><label class="lbl-larg">Largura da tela</label><input type="text" inputmode="decimal" id="po-larg" placeholder="0" step="any" min="0"></div>
        <select class="unit-sel" id="po-un"><option value="cm">cm</option><option value="pol">pol</option></select>
      </div>
    </div>
  </div>

  <!-- MISTURA -->
  <div class="card mat-bloco" id="bloco-mistura" style="display:none">
    <div class="card-head"><h3 data-i18n="matMistura">Mistura de fibras</h3><span class="badge" data-i18n="teiaTramaInd">Teia e trama independentes</span></div>
    <div class="sub">
      <div class="sub-label"><span class="lbl-teia">Teia</span></div>
      <div class="grid4">
        <div class="field"><label class="lbl-fibra-t">Fibra da teia</label>
          <select id="mx-fibra-t" onchange="updateMxLabels()">
            <option value="Ne">Algodão (Ne)</option><option value="Nm">Linho (Nm)</option><option value="Dtex">Poliéster (Dtex)</option>
          </select>
        </div>
        <div class="field"><label class="lbl-fios">Fios/polegada</label><input type="text" inputmode="decimal" id="mx-ft" placeholder="0" step="any" min="0"></div>
        <div class="field"><label id="mx-tit-t-label">Ne</label><input type="text" inputmode="decimal" id="mx-tit-t" placeholder="0" step="any" min="0"></div>
        <div class="field"><label class="lbl-enc">Encolhimento %</label><input type="text" inputmode="decimal" id="mx-et" placeholder="0" step="any" min="0" max="100"></div>
      </div>
    </div>
    <div class="sub">
      <div class="sub-label"><span class="lbl-trama">Trama</span></div>
      <div class="grid4">
        <div class="field"><label class="lbl-fibra-tr">Fibra da trama</label>
          <select id="mx-fibra-tr" onchange="updateMxLabels()">
            <option value="Ne">Algodão (Ne)</option><option value="Nm" selected>Linho (Nm)</option><option value="Dtex">Poliéster (Dtex)</option>
          </select>
        </div>
        <div class="field"><label class="lbl-fios">Fios/polegada</label><input type="text" inputmode="decimal" id="mx-ftr" placeholder="0" step="any" min="0"></div>
        <div class="field"><label id="mx-tit-tr-label">Nm</label><input type="text" inputmode="decimal" id="mx-tit-tr" placeholder="0" step="any" min="0"></div>
        <div class="field"><label class="lbl-enc">Encolhimento %</label><input type="text" inputmode="decimal" id="mx-etr" placeholder="0" step="any" min="0" max="100"></div>
      </div>
    </div>
    <div class="sub">
      <div class="larg-group">
        <div class="field"><label class="lbl-larg">Largura da tela</label><input type="text" inputmode="decimal" id="mx-larg" placeholder="0" step="any" min="0"></div>
        <select class="unit-sel" id="mx-un"><option value="cm">cm</option><option value="pol">pol</option></select>
      </div>
      <p class="note" data-i18n="notaMistura" style="margin-top:10px">Exemplos: teia 100% linho + trama 100% algodão, teia algodão + trama poliéster, etc.</p>
    </div>
  </div>

  <div class="card">
    <div class="btn-row">
      <button class="btn primary" onclick="calcGramagem()" data-i18n="btnCalcular">Calcular</button>
      <button class="btn ghost" onclick="limparGramagem()" data-i18n="btnLimpar">Limpar</button>
      <button class="btn ghost" onclick="exportPDF()" data-i18n="btnPDF">Exportar PDF</button>
    </div>
    <div id="gram-error" class="error"></div>
    <div id="gram-results" style="display:none">
      <div class="results-wrap">
        <div class="results-title" data-i18n="resultados">Resultados</div>
        <div class="result-grid" id="gram-result-grid"></div>
      </div>
    </div>
  </div>
</div>

<!-- ===== CONVERSÃO ===== -->
<div class="panel" id="tab-conversao">
  <div class="card">
    <div class="card-head"><h3 data-i18n="convTitulo">Conversão de títulos de fio</h3></div>
    <div class="card-body" style="display:flex;flex-direction:column;gap:1rem">
      <div class="grid2">
        <div class="field"><label data-i18n="valorTitulo">Valor do título</label><input type="text" inputmode="decimal" id="conv-val" placeholder="30" step="any" min="0" oninput="calcConversao()"></div>
        <div class="field"><label data-i18n="unidOrigem">Unidade de origem</label>
          <select id="conv-unit" onchange="calcConversao()">
            <option value="Ne">Ne</option><option value="Nm">Nm</option><option value="Denier">Denier (Den)</option><option value="Tex">Tex</option><option value="Dtex">Dtex</option>
          </select>
        </div>
      </div>
      <p class="note" data-i18n="notaConv">Apenas para fios simples/singelos (1 cabo) ou títulos resultantes.</p>
    </div>
    <div id="conv-results" style="display:none">
      <div style="border-top:1px solid var(--border)">
        <table class="conv-table">
          <thead><tr><th data-i18n="thUnidade">Unidade</th><th data-i18n="thSistema">Sistema</th><th data-i18n="thResultado">Resultado</th></tr></thead>
          <tbody id="conv-tbody"></tbody>
        </table>
      </div>
    </div>
  </div>
</div>

<!-- ===== RÁPIDOS ===== -->
<div class="panel" id="tab-rapidos">
  <div class="card">
    <div class="card-head"><h3 data-i18n="convPolCm">Polegadas ↔ Centímetros</h3></div>
    <div class="card-body">
      <div class="qrow conv-row">
        <div class="field"><label data-i18n="polegadas">Polegadas (pol)</label><input type="text" inputmode="decimal" id="pc-pol" placeholder="0" step="any" min="0" oninput="calcPolCm('pol')"></div>
        <div class="arrow">⇄</div>
        <div class="field"><label data-i18n="centimetros">Centímetros (cm)</label><input type="text" inputmode="decimal" id="pc-cm" placeholder="0" step="any" min="0" oninput="calcPolCm('cm')"></div>
      </div>
      <p class="note" data-i18n="notaPolCm">1 polegada = 2,54 cm · Conversão automática nos dois sentidos.</p>
    </div>
  </div>
  <div class="card">
    <div class="card-head"><h3 data-i18n="r1Title">Peso/metro linear → Gramagem</h3></div>
    <div class="card-body"><div class="qrow">
      <div class="field"><label data-i18n="pesoMetroLinear">Peso/metro linear (g/m)</label><input type="text" inputmode="decimal" id="r1-plm" placeholder="0" step="any" min="0" oninput="calcR1()"></div>
      <div class="field"><label data-i18n="larguraM">Largura (m)</label><input type="text" inputmode="decimal" id="r1-larg" placeholder="0" step="any" min="0" oninput="calcR1()"></div>
      <div class="arrow">→</div>
      <div class="field out"><label data-i18n="gramagemUn">Gramagem (g/m²)</label><input type="text" id="r1-result" readonly placeholder="—"></div>
    </div></div>
  </div>
  <div class="card">
    <div class="card-head"><h3 data-i18n="r2Title">Gramagem → Peso/metro linear</h3></div>
    <div class="card-body"><div class="qrow">
      <div class="field"><label data-i18n="gramagemUn">Gramagem (g/m²)</label><input type="text" inputmode="decimal" id="r2-gram" placeholder="0" step="any" min="0" oninput="calcR2()"></div>
      <div class="field"><label data-i18n="larguraM">Largura (m)</label><input type="text" inputmode="decimal" id="r2-larg" placeholder="0" step="any" min="0" oninput="calcR2()"></div>
      <div class="arrow">→</div>
      <div class="field out"><label data-i18n="pesoMetroLinear">Peso/metro linear (g/m)</label><input type="text" id="r2-result" readonly placeholder="—"></div>
    </div></div>
  </div>
  <div class="card">
    <div class="card-head"><h3 data-i18n="r3Title">Comprimento total</h3></div>
    <div class="card-body"><div class="qrow">
      <div class="field"><label data-i18n="pesoMetroLinear">Peso/metro linear (g/m)</label><input type="text" inputmode="decimal" id="r3-plm" placeholder="0" step="any" min="0" oninput="calcR3()"></div>
      <div class="field"><label data-i18n="pesoTotalKg">Peso total (kg)</label><input type="text" inputmode="decimal" id="r3-ptot" placeholder="0" step="any" min="0" oninput="calcR3()"></div>
      <div class="arrow">→</div>
      <div class="field out"><label data-i18n="comprimentoM">Comprimento (m)</label><input type="text" id="r3-result" readonly placeholder="—"></div>
    </div></div>
  </div>
  <div class="card">
    <div class="card-head"><h3 data-i18n="r4Title">Peso total</h3></div>
    <div class="card-body"><div class="qrow">
      <div class="field"><label data-i18n="pesoMetroLinear">Peso/metro linear (g/m)</label><input type="text" inputmode="decimal" id="r4-plm" placeholder="0" step="any" min="0" oninput="calcR4()"></div>
      <div class="field"><label data-i18n="comprimentoTotalM">Comprimento total (m)</label><input type="text" inputmode="decimal" id="r4-comp" placeholder="0" step="any" min="0" oninput="calcR4()"></div>
      <div class="arrow">→</div>
      <div class="field out"><label data-i18n="pesoTotalKg">Peso total (kg)</label><input type="text" id="r4-result" readonly placeholder="—"></div>
    </div></div>
  </div>
</div>

</div><!-- app-body -->

<footer class="app-footer">
  <div class="copy">
    © 2026 <strong>Tinkave</strong> — Tinturaria &amp; Acabamentos · <a href="https://tinkave.pt" target="_blank">tinkave.pt</a><br>
    <span data-i18n="copy">Todos os direitos reservados. Reprodução total ou parcial proibida sem autorização.</span>
  </div>
</footer>

<script>
// ════════ TRADUÇÕES ════════
const I18N={
  pt:{appTitle:'Calculadora Têxtil',appSub:'Gramagem · Peso por metro linear · Conversão de títulos',tabGram:'Gramagem',tabConv:'Títulos',tabFast:'Cálculos rápidos',projeto:'Projeto',nomeProjeto:'Nome do projeto…',tipoCalc:'Tipo de cálculo',matAlgodao:'Algodão (Ne)',matLinho:'Linho (Nm)',matPoli:'Poliéster (Dtex)',matMistura:'Mistura de fibras',teiaTramaInd:'Teia e trama independentes',teia:'Teia',trama:'Trama',fiosPol:'Fios/polegada',encolhimento:'Encolhimento %',larguraTela:'Largura da tela',fibraTeia:'Fibra da teia',fibraTrama:'Fibra da trama',btnCalcular:'Calcular',btnLimpar:'Limpar',btnPDF:'Exportar PDF',resultados:'Resultados',convTitulo:'Conversão de títulos de fio',valorTitulo:'Valor do título',unidOrigem:'Unidade de origem',notaConv:'Apenas para fios simples/singelos (1 cabo) ou títulos resultantes.',thUnidade:'Unidade',thSistema:'Sistema',thResultado:'Resultado',origem:'origem',convPolCm:'Polegadas ↔ Centímetros',polegadas:'Polegadas (pol)',centimetros:'Centímetros (cm)',notaPolCm:'1 polegada = 2,54 cm · Conversão automática nos dois sentidos.',r1Title:'Peso/metro linear → Gramagem',r2Title:'Gramagem → Peso/metro linear',r3Title:'Comprimento total',r4Title:'Peso total',pesoMetroLinear:'Peso/metro linear (g/m)',larguraM:'Largura (m)',gramagemUn:'Gramagem (g/m²)',pesoTotalKg:'Peso total (kg)',comprimentoM:'Comprimento (m)',comprimentoTotalM:'Comprimento total (m)',notaMistura:'Exemplos: teia 100% linho + trama 100% algodão, teia algodão + trama poliéster, etc.',errAlgodao:'Preencha todos os campos de Algodão.',errLinho:'Preencha todos os campos de Linho.',errPoli:'Preencha todos os campos de Poliéster.',errMistura:'Preencha todos os campos da mistura.',errLargura:'Informe a largura da tela.',errSemCalc:'Faça primeiro um cálculo antes de exportar.',gTeia:'Gramagem teia',gTrama:'Gramagem trama',gTotal:'Gramagem total',pLinear:'Peso por metro linear',pctTeia:'% peso teia',pctTrama:'% peso trama',larguraOrig:'Largura introduzida',copy:'Todos os direitos reservados. Reprodução total ou parcial proibida sem autorização.'},
  es:{appTitle:'Calculadora Textil',appSub:'Gramaje · Peso por metro lineal · Conversión de títulos',tabGram:'Gramaje',tabConv:'Títulos',tabFast:'Cálculos rápidos',projeto:'Proyecto',nomeProjeto:'Nombre del proyecto…',tipoCalc:'Tipo de cálculo',matAlgodao:'Algodón (Ne)',matLinho:'Lino (Nm)',matPoli:'Poliéster (Dtex)',matMistura:'Mezcla de fibras',teiaTramaInd:'Urdimbre y trama independientes',teia:'Urdimbre',trama:'Trama',fiosPol:'Hilos/pulgada',encolhimento:'Encogimiento %',larguraTela:'Ancho de la tela',fibraTeia:'Fibra de urdimbre',fibraTrama:'Fibra de trama',btnCalcular:'Calcular',btnLimpar:'Limpiar',btnPDF:'Exportar PDF',resultados:'Resultados',convTitulo:'Conversión de títulos de hilo',valorTitulo:'Valor del título',unidOrigem:'Unidad de origen',notaConv:'Solo para hilos simples (1 cabo) o títulos resultantes.',thUnidade:'Unidad',thSistema:'Sistema',thResultado:'Resultado',origem:'origen',convPolCm:'Pulgadas ↔ Centímetros',polegadas:'Pulgadas (pul)',centimetros:'Centímetros (cm)',notaPolCm:'1 pulgada = 2,54 cm · Conversión automática en ambos sentidos.',r1Title:'Peso/metro lineal → Gramaje',r2Title:'Gramaje → Peso/metro lineal',r3Title:'Longitud total',r4Title:'Peso total',pesoMetroLinear:'Peso/metro lineal (g/m)',larguraM:'Ancho (m)',gramagemUn:'Gramaje (g/m²)',pesoTotalKg:'Peso total (kg)',comprimentoM:'Longitud (m)',comprimentoTotalM:'Longitud total (m)',notaMistura:'Ejemplos: urdimbre 100% lino + trama 100% algodón, etc.',errAlgodao:'Complete todos los campos de Algodón.',errLinho:'Complete todos los campos de Lino.',errPoli:'Complete todos los campos de Poliéster.',errMistura:'Complete todos los campos de la mezcla.',errLargura:'Indique el ancho de la tela.',errSemCalc:'Haga primero un cálculo antes de exportar.',gTeia:'Gramaje urdimbre',gTrama:'Gramaje trama',gTotal:'Gramaje total',pLinear:'Peso por metro lineal',pctTeia:'% peso urdimbre',pctTrama:'% peso trama',larguraOrig:'Ancho introducido',copy:'Todos los derechos reservados. Reproducción total o parcial prohibida sin autorización.'},
  fr:{appTitle:'Calculatrice Textile',appSub:'Grammage · Poids par mètre linéaire · Conversion de titres',tabGram:'Grammage',tabConv:'Titres',tabFast:'Calculs rapides',projeto:'Projet',nomeProjeto:'Nom du projet…',tipoCalc:'Type de calcul',matAlgodao:'Coton (Ne)',matLinho:'Lin (Nm)',matPoli:'Polyester (Dtex)',matMistura:'Mélange de fibres',teiaTramaInd:'Chaîne et trame indépendantes',teia:'Chaîne',trama:'Trame',fiosPol:'Fils/pouce',encolhimento:'Retrait %',larguraTela:'Largeur du tissu',fibraTeia:'Fibre de chaîne',fibraTrama:'Fibre de trame',btnCalcular:'Calculer',btnLimpar:'Effacer',btnPDF:'Exporter PDF',resultados:'Résultats',convTitulo:'Conversion de titres de fil',valorTitulo:'Valeur du titre',unidOrigem:'Unité d\'origine',notaConv:'Uniquement pour fils simples (1 bout) ou titres résultants.',thUnidade:'Unité',thSistema:'Système',thResultado:'Résultat',origem:'origine',convPolCm:'Pouces ↔ Centimètres',polegadas:'Pouces (po)',centimetros:'Centimètres (cm)',notaPolCm:'1 pouce = 2,54 cm · Conversion automatique dans les deux sens.',r1Title:'Poids/mètre linéaire → Grammage',r2Title:'Grammage → Poids/mètre linéaire',r3Title:'Longueur totale',r4Title:'Poids total',pesoMetroLinear:'Poids/mètre linéaire (g/m)',larguraM:'Largeur (m)',gramagemUn:'Grammage (g/m²)',pesoTotalKg:'Poids total (kg)',comprimentoM:'Longueur (m)',comprimentoTotalM:'Longueur totale (m)',notaMistura:'Exemples : chaîne 100% lin + trame 100% coton, etc.',errAlgodao:'Remplissez tous les champs Coton.',errLinho:'Remplissez tous les champs Lin.',errPoli:'Remplissez tous les champs Polyester.',errMistura:'Remplissez tous les champs du mélange.',errLargura:'Indiquez la largeur du tissu.',errSemCalc:'Effectuez d\'abord un calcul avant d\'exporter.',gTeia:'Grammage chaîne',gTrama:'Grammage trame',gTotal:'Grammage total',pLinear:'Poids par mètre linéaire',pctTeia:'% poids chaîne',pctTrama:'% poids trame',larguraOrig:'Largeur saisie',copy:'Tous droits réservés. Reproduction totale ou partielle interdite sans autorisation.'},
  en:{appTitle:'Textile Calculator',appSub:'Fabric weight · Weight per linear metre · Yarn count conversion',tabGram:'Weight',tabConv:'Yarn count',tabFast:'Quick calculations',projeto:'Project',nomeProjeto:'Project name…',tipoCalc:'Calculation type',matAlgodao:'Cotton (Ne)',matLinho:'Linen (Nm)',matPoli:'Polyester (Dtex)',matMistura:'Fibre blend',teiaTramaInd:'Independent warp and weft',teia:'Warp',trama:'Weft',fiosPol:'Threads/inch',encolhimento:'Shrinkage %',larguraTela:'Fabric width',fibraTeia:'Warp fibre',fibraTrama:'Weft fibre',btnCalcular:'Calculate',btnLimpar:'Clear',btnPDF:'Export PDF',resultados:'Results',convTitulo:'Yarn count conversion',valorTitulo:'Count value',unidOrigem:'Source unit',notaConv:'Only for single yarns (1 ply) or resulting counts.',thUnidade:'Unit',thSistema:'System',thResultado:'Result',origem:'source',convPolCm:'Inches ↔ Centimetres',polegadas:'Inches (in)',centimetros:'Centimetres (cm)',notaPolCm:'1 inch = 2.54 cm · Automatic two-way conversion.',r1Title:'Linear weight → Fabric weight',r2Title:'Fabric weight → Linear weight',r3Title:'Total length',r4Title:'Total weight',pesoMetroLinear:'Linear weight (g/m)',larguraM:'Width (m)',gramagemUn:'Fabric weight (g/m²)',pesoTotalKg:'Total weight (kg)',comprimentoM:'Length (m)',comprimentoTotalM:'Total length (m)',notaMistura:'Examples: warp 100% linen + weft 100% cotton, etc.',errAlgodao:'Fill in all Cotton fields.',errLinho:'Fill in all Linen fields.',errPoli:'Fill in all Polyester fields.',errMistura:'Fill in all blend fields.',errLargura:'Enter the fabric width.',errSemCalc:'Make a calculation before exporting.',gTeia:'Warp weight',gTrama:'Weft weight',gTotal:'Total weight',pLinear:'Weight per linear metre',pctTeia:'% warp weight',pctTrama:'% weft weight',larguraOrig:'Width entered',copy:'All rights reserved. Total or partial reproduction prohibited without authorisation.'}
};
let lang='pt';
function t(k){return (I18N[lang]&&I18N[lang][k])||I18N.pt[k]||k;}
function setLang(l){
  lang=l;
  ['pt','es','fr','en'].forEach(x=>document.getElementById('lang-'+x).classList.toggle('active',x===l));
  document.querySelectorAll('[data-i18n]').forEach(el=>{const k=el.getAttribute('data-i18n');if(I18N[lang][k])el.textContent=I18N[lang][k];});
  document.querySelectorAll('[data-i18n-ph]').forEach(el=>{const k=el.getAttribute('data-i18n-ph');if(I18N[lang][k])el.placeholder=I18N[lang][k];});
  document.querySelectorAll('.lbl-teia').forEach(e=>e.textContent=t('teia'));
  document.querySelectorAll('.lbl-trama').forEach(e=>e.textContent=t('trama'));
  document.querySelectorAll('.lbl-fios').forEach(e=>e.textContent=t('fiosPol'));
  document.querySelectorAll('.lbl-enc').forEach(e=>e.textContent=t('encolhimento'));
  document.querySelectorAll('.lbl-larg').forEach(e=>e.textContent=t('larguraTela'));
  document.querySelectorAll('.lbl-fibra-t').forEach(e=>e.textContent=t('fibraTeia'));
  document.querySelectorAll('.lbl-fibra-tr').forEach(e=>e.textContent=t('fibraTrama'));
  calcConversao();
}

function showTab(tb){
  ['gramagem','conversao','rapidos'].forEach((id,i)=>{
    document.querySelectorAll('.tab')[i].classList.toggle('active',id===tb);
    document.getElementById('tab-'+id).classList.toggle('active',id===tb);
  });
}

let tipoAtual='algodao';
let ultimoCalculo=null;
function setTipo(tp){
  tipoAtual=tp;
  ['algodao','linho','poliester','mistura'].forEach(x=>document.getElementById('tipo-'+x).classList.toggle('active',x===tp));
  document.getElementById('bloco-algodao').style.display=(tp==='algodao')?'block':'none';
  document.getElementById('bloco-linho').style.display=(tp==='linho')?'block':'none';
  document.getElementById('bloco-poliester').style.display=(tp==='poliester')?'block':'none';
  document.getElementById('bloco-mistura').style.display=(tp==='mistura')?'block':'none';
  document.getElementById('gram-results').style.display='none';
}
function updateMxLabels(){
  document.getElementById('mx-tit-t-label').textContent=document.getElementById('mx-fibra-t').value;
  document.getElementById('mx-tit-tr-label').textContent=document.getElementById('mx-fibra-tr').value;
}

// lê o valor de um campo aceitando vírgula OU ponto como separador decimal
function vc(id){return (document.getElementById(id).value||'').replace(',','.');}
function v(id){return parseFloat(vc(id))||0}
function fibraNome(s){return s==='Ne'?t('matAlgodao').split(' (')[0]:s==='Nm'?t('matLinho').split(' (')[0]:t('matPoli').split(' (')[0]}

// Gramagem de um componente (g/m²) — fios/pol
function gramComp(sis,fios,tit,enc){
  if(!fios||!tit)return null;
  const fm=fios*39.37*(1+enc/100);
  if(sis==='Ne')return fm/tit*0.5905;
  if(sis==='Nm')return fm/tit;
  if(sis==='Dtex')return fm*tit/10000;
  return null;
}

// devolve {larg, fator}: largura para mostrar + fator p/ peso linear
// se pol → fator 2,54 (multiplica gramagem e peso linear na largura)
function lerLargura(idCampo,idUn){
  const valor=v(idCampo);
  const un=document.getElementById(idUn).value;
  const fator=(un==='pol')?2.54:1;
  return {valor:valor, unidade:un, larguraCm:valor*fator, fator:fator};
}

function calcGramagem(){
  const err=document.getElementById('gram-error');
  err.textContent='';
  let res=[],entradas=[],materialLabel='';

  function montaResultado(sis1,sis2,gt,gtr,L,fibT,fibTr,erroMsg){
    if(gt===null||gtr===null){err.textContent=erroMsg;return false}
    if(!L.valor){err.textContent=t('errLargura');return false}
    const g=gt+gtr;
    // peso por metro linear (g/m) usa largura em cm: g/m² × largura(cm)/100
    const pLin=g*L.larguraCm/100;
    entradas=[
      [t('teia')+' — '+fibraNome(fibT),`${''} ${sis1}`],
      [t('trama')+' — '+fibraNome(fibTr),`${''} ${sis2}`],
      [t('larguraTela'),`${L.valor} ${L.unidade}`+(L.unidade==='pol'?` (= ${L.larguraCm.toFixed(2)} cm)`:'')]
    ];
    res.push({label:t('gTeia'),val:gt.toFixed(2),unit:'g/m²'});
    res.push({label:t('gTrama'),val:gtr.toFixed(2),unit:'g/m²'});
    res.push({label:t('gTotal'),val:g.toFixed(2),unit:'g/m²',gold:true});
    res.push({label:t('pLinear'),val:pLin.toFixed(2),unit:'g/m',gold:true});
    return {g:g,pLin:pLin};
  }

  if(tipoAtual==='algodao'){
    materialLabel=t('matAlgodao');
    const gt=gramComp('Ne',v('al-ft'),v('al-net'),v('al-et'));
    const gtr=gramComp('Ne',v('al-ftr'),v('al-netr'),v('al-etr'));
    const L=lerLargura('al-larg','al-un');
    const r=montaResultado(`${v('al-ft')} ${t('fiosPol').toLowerCase()} · Ne ${v('al-net')} · ${v('al-et')}%`,`${v('al-ftr')} ${t('fiosPol').toLowerCase()} · Ne ${v('al-netr')} · ${v('al-etr')}%`,gt,gtr,L,'Ne','Ne',t('errAlgodao'));
    if(!r)return;
  }
  else if(tipoAtual==='linho'){
    materialLabel=t('matLinho');
    const gt=gramComp('Nm',v('li-ft'),v('li-nmt'),v('li-et'));
    const gtr=gramComp('Nm',v('li-ftr'),v('li-nmtr'),v('li-etr'));
    const L=lerLargura('li-larg','li-un');
    const r=montaResultado(`${v('li-ft')} ${t('fiosPol').toLowerCase()} · Nm ${v('li-nmt')} · ${v('li-et')}%`,`${v('li-ftr')} ${t('fiosPol').toLowerCase()} · Nm ${v('li-nmtr')} · ${v('li-etr')}%`,gt,gtr,L,'Nm','Nm',t('errLinho'));
    if(!r)return;
  }
  else if(tipoAtual==='poliester'){
    materialLabel=t('matPoli');
    const gt=gramComp('Dtex',v('po-ft'),v('po-dt'),v('po-et'));
    const gtr=gramComp('Dtex',v('po-ftr'),v('po-dtr'),v('po-etr'));
    const L=lerLargura('po-larg','po-un');
    const r=montaResultado(`${v('po-ft')} ${t('fiosPol').toLowerCase()} · ${v('po-dt')} dtex · ${v('po-et')}%`,`${v('po-ftr')} ${t('fiosPol').toLowerCase()} · ${v('po-dtr')} dtex · ${v('po-etr')}%`,gt,gtr,L,'Dtex','Dtex',t('errPoli'));
    if(!r)return;
  }
  else if(tipoAtual==='mistura'){
    const fibT=document.getElementById('mx-fibra-t').value;
    const fibTr=document.getElementById('mx-fibra-tr').value;
    materialLabel=fibraNome(fibT)+' + '+fibraNome(fibTr);
    const gt=gramComp(fibT,v('mx-ft'),v('mx-tit-t'),v('mx-et'));
    const gtr=gramComp(fibTr,v('mx-ftr'),v('mx-tit-tr'),v('mx-etr'));
    const L=lerLargura('mx-larg','mx-un');
    if(gt===null||gtr===null){err.textContent=t('errMistura');return}
    if(!L.valor){err.textContent=t('errLargura');return}
    const g=gt+gtr;
    const pLin=g*L.larguraCm/100;
    entradas=[
      [t('teia')+' — '+fibraNome(fibT),`${v('mx-ft')} ${t('fiosPol').toLowerCase()} · ${fibT} ${v('mx-tit-t')} · ${v('mx-et')}%`],
      [t('trama')+' — '+fibraNome(fibTr),`${v('mx-ftr')} ${t('fiosPol').toLowerCase()} · ${fibTr} ${v('mx-tit-tr')} · ${v('mx-etr')}%`],
      [t('larguraTela'),`${L.valor} ${L.unidade}`+(L.unidade==='pol'?` (= ${L.larguraCm.toFixed(2)} cm)`:'')]
    ];
    res.push({label:t('gTeia')+' ('+fibraNome(fibT)+')',val:gt.toFixed(2),unit:'g/m²'});
    res.push({label:t('gTrama')+' ('+fibraNome(fibTr)+')',val:gtr.toFixed(2),unit:'g/m²'});
    res.push({label:t('gTotal'),val:g.toFixed(2),unit:'g/m²',gold:true});
    res.push({label:t('pLinear'),val:pLin.toFixed(2),unit:'g/m',gold:true});
    res.push({label:t('pctTeia'),val:(gt/g*100).toFixed(1),unit:'%'});
    res.push({label:t('pctTrama'),val:(gtr/g*100).toFixed(1),unit:'%'});
  }

  ultimoCalculo={material:materialLabel,entradas:entradas,resultados:res.map(r=>[r.label,r.val+' '+r.unit])};
  document.getElementById('gram-result-grid').innerHTML=res.map(r=>`<div class="rcard${r.gold?' gold':''}"><div class="rlabel">${r.label}</div><div class="rval">${r.val}</div><div class="runit">${r.unit}</div></div>`).join('');
  document.getElementById('gram-results').style.display='block';
}

function limparGramagem(){
  ['al-ft','al-ftr','al-net','al-netr','al-et','al-etr','al-larg','li-ft','li-ftr','li-nmt','li-nmtr','li-et','li-etr','li-larg','po-ft','po-ftr','po-dt','po-dtr','po-et','po-etr','po-larg','mx-ft','mx-ftr','mx-tit-t','mx-tit-tr','mx-et','mx-etr','mx-larg','nome-projeto'].forEach(id=>document.getElementById(id).value='');
  ['al-un','li-un','po-un','mx-un'].forEach(id=>document.getElementById(id).value='cm');
  document.getElementById('gram-results').style.display='none';
  document.getElementById('gram-error').textContent='';
  ultimoCalculo=null;
}

// ════ PDF ════
function logoPDF(doc,cx,cy){
  doc.setFillColor(21,23,30);doc.circle(cx,cy,10,'F');
  doc.setLineWidth(1.1);
  doc.setDrawColor(226,84,43);
  [[cx-4,cy-7.5,cx+4,cy+0.5],[cx-1,cy-8.2,cx+6.5,cy-0.7],[cx+2.5,cy-7.5,cx+7.5,cy-2.5],[cx-6.2,cy-4,cx-1.2,cy+1]].forEach(l=>doc.line(l[0],l[1],l[2],l[3]));
  doc.setDrawColor(47,59,100);
  [[cx-8.2,cy+1,cx-3.2,cy-4],[cx-7.8,cy+4.5,cx-1.8,cy-1.5],[cx-6,cy+6.8,cx,cy+0.8],[cx-4,cy+9,cx+2,cy+3]].forEach(l=>doc.line(l[0],l[1],l[2],l[3]));
  doc.setDrawColor(150,60,50);
  [[cx+1,cy+2,cx+6,cy+7],[cx-1.5,cy+3.5,cx+3.5,cy+8.5],[cx+3.5,cy+1,cx+7.8,cy+5.3]].forEach(l=>doc.line(l[0],l[1],l[2],l[3]));
}
function exportPDF(){
  if(!ultimoCalculo){alert(t('errSemCalc'));return}
  const{jsPDF}=window.jspdf;const doc=new jsPDF();
  const nome=document.getElementById('nome-projeto').value||'—';
  doc.setFillColor(44,74,62);doc.rect(0,0,210,36,'F');
  doc.setFillColor(255,255,255);doc.circle(22,18,11.5,'F');logoPDF(doc,22,18);
  doc.setTextColor(255,255,255);doc.setFont('helvetica','bold');doc.setFontSize(20);doc.text('TINKAVE',40,16);
  doc.setFont('helvetica','normal');doc.setFontSize(9);doc.setTextColor(220,228,224);doc.text('Tinturaria & Acabamentos  ·  tinkave.pt',40,23);
  doc.setFontSize(10);doc.setTextColor(255,255,255);doc.text(t('appTitle'),40,30);
  doc.setTextColor(26,26,26);doc.setFont('helvetica','bold');doc.setFontSize(13);doc.text(nome,14,48);
  doc.setFont('helvetica','normal');doc.setFontSize(9);doc.setTextColor(110,110,110);
  doc.text(t('tipoCalc')+': '+ultimoCalculo.material,14,55);
  doc.text('Data: '+new Date().toLocaleDateString('pt-PT')+'  ·  '+new Date().toLocaleTimeString('pt-PT',{hour:'2-digit',minute:'2-digit'}),14,61);
  doc.setDrawColor(226,221,215);doc.line(14,66,196,66);
  let y=76;doc.setFont('helvetica','bold');doc.setFontSize(11);doc.setTextColor(44,74,62);doc.text(t('resultados').toUpperCase(),14,y);y+=9;
  ultimoCalculo.resultados.forEach(r=>{
    const dest=r[0].includes(t('gTotal'))||r[0].includes(t('pLinear'));
    if(dest){doc.setFillColor(253,246,227);doc.roundedRect(12,y-5.5,184,9,1.5,1.5,'F');}
    doc.setFont('helvetica','normal');doc.setFontSize(10);doc.setTextColor(dest?139:110,dest?105:110,dest?20:110);doc.text(r[0],16,y);
    doc.setFont('helvetica','bold');doc.setFontSize(11);doc.setTextColor(dest?139:26,dest?105:26,dest?20:26);doc.text(r[1],140,y);y+=10;
  });
  doc.setDrawColor(226,221,215);doc.line(14,280,196,280);
  doc.setFont('helvetica','normal');doc.setFontSize(8);doc.setTextColor(150,150,150);
  doc.text('© 2026 Tinkave — Tinturaria & Acabamentos  ·  tinkave.pt  ·  Todos os direitos reservados.',14,286);
  doc.save('tinkave-'+(nome==='—'?'calculo':nome.toLowerCase().replace(/[^a-z0-9]+/g,'-'))+'.pdf');
}

// ════ Conversão títulos ════
function toTex(val,u){return u==='Ne'?590.5/val:u==='Nm'?1000/val:u==='Denier'?val/9:u==='Tex'?val:val/10}
function fromTex(tx,u){return u==='Ne'?590.5/tx:u==='Nm'?1000/tx:u==='Denier'?tx*9:u==='Tex'?tx:tx*10}
function calcConversao(){
  const el=document.getElementById('conv-val');if(!el)return;
  const val=parseFloat((el.value||'').replace(',','.'));const unit=document.getElementById('conv-unit').value;const div=document.getElementById('conv-results');
  if(!val||val<=0){div.style.display='none';return}
  const tex=toTex(val,unit);
  const sysMap={Ne:{pt:'Inglês (cotton)',es:'Inglés (cotton)',fr:'Anglais (coton)',en:'English (cotton)'},Nm:{pt:'Métrico',es:'Métrico',fr:'Métrique',en:'Metric'},Denier:{pt:'Denier (Den)',es:'Denier (Den)',fr:'Denier (Den)',en:'Denier (Den)'},Tex:{pt:'Tex',es:'Tex',fr:'Tex',en:'Tex'},Dtex:{pt:'Decitex',es:'Decitex',fr:'Décitex',en:'Decitex'}};
  const defs=['Ne','Nm','Denier','Tex','Dtex'];
  document.getElementById('conv-tbody').innerHTML=defs.map(k=>`<tr${k===unit?' class="origin"':''}><td>${k}${k===unit?'<span class="origin-tag">'+t('origem')+'</span>':''}</td><td style="color:var(--ink3);font-size:13px">${sysMap[k][lang]||sysMap[k].pt}</td><td>${fromTex(tex,k).toFixed(4)}</td></tr>`).join('');
  div.style.display='block';
}

// ════ Cálculos rápidos ════
function calcPolCm(origem){
  const polEl=document.getElementById('pc-pol'),cmEl=document.getElementById('pc-cm');
  if(origem==='pol'){const p=parseFloat((polEl.value||'').replace(',','.'));cmEl.value=(!isNaN(p)&&p>0)?(p*2.54).toFixed(3):'';}
  else{const c=parseFloat((cmEl.value||'').replace(',','.'));polEl.value=(!isNaN(c)&&c>0)?(c/2.54).toFixed(3):'';}
}
function calcR1(){const p=parseFloat(vc('r1-plm')),l=parseFloat(vc('r1-larg'));document.getElementById('r1-result').value=(p>0&&l>0)?(p/l).toFixed(2):'';}
function calcR2(){const g=parseFloat(vc('r2-gram')),l=parseFloat(vc('r2-larg'));document.getElementById('r2-result').value=(g>0&&l>0)?(g*l).toFixed(2):'';}
function calcR3(){const p=parseFloat(vc('r3-plm')),tt=parseFloat(vc('r3-ptot'));document.getElementById('r3-result').value=(p>0&&tt>0)?((tt*1000)/p).toFixed(2):'';}
function calcR4(){const p=parseFloat(vc('r4-plm')),c=parseFloat(vc('r4-comp'));document.getElementById('r4-result').value=(p>0&&c>0)?((p*c)/1000).toFixed(4):'';}

// ════ Init ════
setTipo('algodao');updateMxLabels();setLang('pt');

// ════ PWA ════
(function(){
  const iconSVG='<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 100"><rect width="100" height="100" rx="20" fill="#2c4a3e"/><circle cx="50" cy="50" r="36" fill="#15171e"/><defs><clipPath id="c"><circle cx="50" cy="50" r="34"/></clipPath></defs><g clip-path="url(#c)" stroke-width="5.5" fill="none"><path d="M38 18 L74 54 M30 26 L66 62 M46 14 L80 48" stroke="#e2542b"/><path d="M18 52 L48 22 M22 64 L56 30 M32 74 L66 40 M46 84 L78 52" stroke="#2f3b64"/></g></svg>';
  const iconURI='data:image/svg+xml;charset=utf-8,'+encodeURIComponent(iconSVG);
  try{const img=new Image();img.onload=function(){const cv=document.createElement('canvas');cv.width=180;cv.height=180;cv.getContext('2d').drawImage(img,0,0,180,180);document.getElementById('apple-icon').href=cv.toDataURL('image/png');};img.src=iconURI;}catch(e){}
  const manifest={name:'Calculadora Têxtil Tinkave',short_name:'Tinkave',description:'Gramagem, peso por metro linear e conversão de títulos têxteis — Tinkave',start_url:'.',scope:'.',display:'standalone',orientation:'portrait',background_color:'#2c4a3e',theme_color:'#2c4a3e',lang:'pt',icons:[{src:iconURI,sizes:'any',type:'image/svg+xml',purpose:'any'},{src:iconURI,sizes:'192x192',type:'image/svg+xml'},{src:iconURI,sizes:'512x512',type:'image/svg+xml'}]};
  try{const blob=new Blob([JSON.stringify(manifest)],{type:'application/json'});document.getElementById('manifest-link').href=URL.createObjectURL(blob);}catch(e){}
  if('serviceWorker' in navigator){navigator.serviceWorker.register('sw.js').catch(function(){});}
})();
</script>
</body>
</html>
