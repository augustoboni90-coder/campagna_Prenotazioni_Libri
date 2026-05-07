<!doctype html>
<html lang="it">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Prenotazioni libri scolastici 2026/27</title>
<style>
:root{
  --blu:#1f4e78;
  --blu-2:#2d6aa3;
  --arancio:#c65911;
  --arancio-2:#e27a2b;
  --verde:#128C7E;
  --verde-2:#16a085;
  --rosso:#b91c1c;
  --sfondo:#eef3f9;
  --sfondo-2:#f8fbff;
  --bordo:#d8e3ef;
  --testo:#1f2937;
  --muted:#64748b;
  --ombra:0 10px 30px rgba(31,78,120,.10);
  --ombra-soft:0 4px 14px rgba(15,23,42,.08);
  --radius:16px;
}
*{box-sizing:border-box}
html{scroll-behavior:smooth}
body{
  margin:0;
  font-family:Arial, Helvetica, sans-serif;
  color:var(--testo);
  background:
    radial-gradient(circle at top left, rgba(45,106,163,.10), transparent 28%),
    radial-gradient(circle at top right, rgba(198,89,17,.08), transparent 22%),
    linear-gradient(180deg, #f7fbff 0%, var(--sfondo) 42%, #edf3f8 100%);
}
header{
  position:sticky;
  top:0;
  z-index:20;
  color:#fff;
  padding:22px 22px 18px;
  background:
    linear-gradient(135deg, rgba(18,61,102,.96), rgba(31,78,120,.95) 50%, rgba(45,106,163,.92));
  box-shadow:0 8px 24px rgba(31,78,120,.22);
  backdrop-filter: blur(6px);
}
header h1{
  margin:0;
  font-size:24px;
  letter-spacing:.2px;
}
header p{
  margin:7px 0 0;
  opacity:.92;
  font-size:14px;
}
main{
  max-width:1180px;
  margin:20px auto;
  padding:0 14px 40px;
}
.card{
  position:relative;
  background:rgba(255,255,255,.96);
  border:1px solid var(--bordo);
  border-radius:var(--radius);
  padding:18px;
  box-shadow:var(--ombra);
  margin-bottom:16px;
}
.card::before{
  content:"";
  position:absolute;
  inset:0 0 auto 0;
  height:4px;
  border-radius:16px 16px 0 0;
  background:linear-gradient(90deg, var(--blu), var(--arancio));
}
.grid{
  display:grid;
  grid-template-columns:repeat(4, minmax(0,1fr));
  gap:14px;
}
.grid-2{
  display:grid;
  grid-template-columns:repeat(2, minmax(0,1fr));
  gap:14px;
}
.full{grid-column:1/-1}
label{
  display:block;
  font-weight:700;
  font-size:12px;
  margin-bottom:6px;
  color:#334155;
  text-transform:uppercase;
  letter-spacing:.45px;
}
input, select, textarea{
  width:100%;
  padding:11px 12px;
  border:1px solid #c9d7e6;
  border-radius:12px;
  font-size:15px;
  background:#fff;
  color:var(--testo);
  outline:none;
  transition:border-color .18s ease, box-shadow .18s ease, transform .12s ease;
  box-shadow: inset 0 1px 2px rgba(15,23,42,.03);
}
input:hover, select:hover, textarea:hover{
  border-color:#adc3d8;
}
input:focus, select:focus, textarea:focus{
  border-color:var(--blu-2);
  box-shadow:0 0 0 4px rgba(45,106,163,.14);
}
input[readonly]{
  background:#f4f7fb;
  color:#475569;
}
textarea{
  min-height:84px;
  resize:vertical;
  line-height:1.35;
}
.section-title{
  display:flex;
  align-items:center;
  gap:10px;
  font-size:18px;
  font-weight:800;
  color:var(--blu);
  margin:0 0 14px;
}
.badge{
  display:inline-flex;
  align-items:center;
  padding:5px 10px;
  border-radius:999px;
  background:linear-gradient(180deg, #edf6ff, #e4f0fb);
  color:var(--blu);
  border:1px solid #c9dff3;
  font-weight:700;
  font-size:12px;
}
.actions{
  display:flex;
  flex-wrap:wrap;
  gap:10px;
  margin-top:14px;
}
button{
  border:0;
  border-radius:12px;
  padding:11px 15px;
  font-weight:800;
  cursor:pointer;
  font-size:14px;
  background:linear-gradient(180deg, var(--blu-2), var(--blu));
  color:#fff;
  box-shadow:var(--ombra-soft);
  transition:transform .12s ease, box-shadow .18s ease, filter .18s ease;
}
button:hover{
  transform:translateY(-1px);
  filter:saturate(1.02);
  box-shadow:0 10px 20px rgba(31,78,120,.18);
}
button:active{
  transform:translateY(0);
}
button.secondary{background:linear-gradient(180deg, #7b8a9c, #64748b)}
button.orange{background:linear-gradient(180deg, var(--arancio-2), var(--arancio))}
button.green{background:linear-gradient(180deg, var(--verde-2), var(--verde))}
button.danger{background:linear-gradient(180deg, #dc2626, var(--rosso))}
.small{
  font-size:12px;
  color:var(--muted);
  margin-top:5px;
}
.okmsg, .errmsg{
  padding:11px 12px;
  border-radius:12px;
  font-weight:700;
}
.okmsg{
  background:#ecfdf3;
  border:1px solid #a7f3d0;
  color:#166534;
}
.errmsg{
  background:#fff1f2;
  border:1px solid #fecdd3;
  color:#9f1239;
}
table{
  width:100%;
  border-collapse:separate;
  border-spacing:0;
  font-size:13px;
}
th, td{
  padding:10px 9px;
  border-bottom:1px solid #e5edf5;
  text-align:left;
  vertical-align:top;
}
th{
  position:sticky;
  top:0;
  z-index:1;
  background:linear-gradient(180deg, #f2f7fc, #e8f0f8);
  color:var(--blu);
  font-weight:800;
}
tbody tr:nth-child(even){
  background:#fbfdff;
}
tbody tr:hover{
  background:#f1f7fc;
}
.table-wrap{
  max-height:320px;
  overflow:auto;
  border:1px solid #e2eaf2;
  border-radius:14px;
  background:#fff;
}
.table-wrap::-webkit-scrollbar{width:10px;height:10px}
.table-wrap::-webkit-scrollbar-thumb{background:#c9d7e6;border-radius:20px}
.table-wrap::-webkit-scrollbar-track{background:#f3f6fa}
.required{color:var(--rosso)}
.result-row{cursor:pointer}
.hidden{display:none !important}
.tabs{
  display:flex;
  gap:10px;
  flex-wrap:wrap;
  margin-top:14px;
}
.tabs button{
  border:1px solid rgba(255,255,255,.42);
  background:rgba(255,255,255,.16);
  box-shadow:none;
  backdrop-filter: blur(4px);
}
.tabs button.active{
  background:#fff;
  color:var(--blu);
  border-color:#fff;
}
.screen.hidden{display:none !important}
#areaStampaRicevuta{
  background:white;
  border-radius:0;
}
hr{
  border:0;
  border-top:1px dashed #cbd5e1;
  margin:12px 0;
}
::placeholder{color:#94a3b8}
@media (max-width:900px){
  .grid{grid-template-columns:repeat(2, minmax(0,1fr))}
}
@media (max-width:620px){
  header{padding:18px 14px 16px}
  header h1{font-size:20px}
  main{padding:0 10px 30px}
  .card{padding:14px}
  .grid,.grid-2{grid-template-columns:1fr}
  .actions{gap:8px}
  button{width:100%}
  .tabs button{width:auto}
}
@media print{
  body *{visibility:hidden}
  #areaStampaRicevuta, #areaStampaRicevuta *{visibility:visible}
  #areaStampaRicevuta{
    position:absolute;
    left:0;
    top:0;
    width:100%;
    box-shadow:none;
    border:0;
    padding:0;
    background:white;
  }
  .no-print{display:none !important}
}

/* MODALE RIEPILOGO GRANDE */
#riepilogoOverlay {
  position: fixed;
  inset: 0;
  background: rgba(15, 23, 42, .62);
  z-index: 9999;
  display: none;
  align-items: center;
  justify-content: center;
  padding: 22px;
}

#riepilogoOverlay.show {
  display: flex;
}

#riepilogoModal {
  width: min(900px, 96vw);
  max-height: 92vh;
  overflow: auto;
  background: #ffffff;
  border-radius: 22px;
  box-shadow: 0 24px 80px rgba(15, 23, 42, .35);
  border: 1px solid #dbe7f3;
}

#riepilogoHeader {
  background: linear-gradient(135deg, #1f4e78, #2d6aa3);
  color: white;
  padding: 18px 22px;
  border-radius: 22px 22px 0 0;
}

#riepilogoHeader h2 {
  margin: 0;
  font-size: 23px;
}

#riepilogoHeader p {
  margin: 6px 0 0;
  opacity: .92;
}

#riepilogoContent {
  padding: 20px 22px;
}

.riepilogoGrid {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 14px;
}

.riepilogoSection {
  border: 1px solid #dbe7f3;
  border-radius: 16px;
  padding: 14px;
  background: #f8fbff;
}

.riepilogoSection.full {
  grid-column: 1 / -1;
}

.riepilogoSection h3 {
  margin: 0 0 10px;
  color: #1f4e78;
  font-size: 16px;
  border-bottom: 1px dashed #cbd5e1;
  padding-bottom: 8px;
}

.riepilogoRow {
  display: grid;
  grid-template-columns: 160px 1fr;
  gap: 8px;
  padding: 5px 0;
  font-size: 15px;
}

.riepilogoLabel {
  font-weight: 800;
  color: #475569;
}

.riepilogoValue {
  font-weight: 700;
  color: #111827;
  word-break: break-word;
}

#riepilogoActions {
  display: flex;
  justify-content: flex-end;
  gap: 10px;
  padding: 16px 22px 22px;
  border-top: 1px solid #e5edf5;
  background: #fbfdff;
  border-radius: 0 0 22px 22px;
}

@media (max-width: 760px) {
  .riepilogoGrid {
    grid-template-columns: 1fr;
  }

  .riepilogoRow {
    grid-template-columns: 1fr;
    gap: 2px;
  }

  #riepilogoActions {
    flex-direction: column;
  }
}

</style>
</head>
<body>
<header class="no-print">
  <h1>Prenotazioni libri scolastici 2026/27</h1>
  <p>Unica pagina con prenotazione, ricerca, controllo non prenotati e stampa ricevuta.</p>
  <div class="tabs">
    <button id="tabPrenotazione" class="active" type="button" onclick="mostraSchermata('prenotazione')">Prenotazione</button>
    <button id="tabRicevuta" type="button" onclick="mostraSchermata('ricevuta')">Ricerca prenotazioni</button>
  </div>
</header>

<main>
  <section id="screenPrenotazione" class="screen">
    <section class="card no-print">
      <p class="section-title">1) Cerca prenotazione</p>
      <div class="grid-2">
        <div>
          <label for="searchBox">Cerca alunno, genitore, codice fiscale o telefono</label>
          <div style="display:flex; gap:8px;">
            <input id="searchBox" placeholder="Es. BONI, Aurora, codice fiscale, telefono..." autocomplete="off">
            <button type="button" onclick="cercaArchivio()">Cerca</button>
          </div>
          <div class="small">La ricerca legge il foglio Google <b>Prenotazioni_2025_2026</b>.</div>
        </div>
        <div>
          <label for="quickStatus">Stato</label>
          <input id="quickStatus" readonly value="Nessuna prenotazione selezionata">
        </div>
      </div>
      <div class="actions">
        <button type="button" class="orange" onclick="nuovaAnagrafica()">Nuova anagrafica non presente</button>
      </div>
      <div id="msgRicerca" class="hidden" style="margin-top:12px;"></div>
      <div id="searchResults" class="table-wrap hidden" style="margin-top:12px;"></div>
    </section>

    <section class="card no-print">
      <p class="section-title">2) Dati anagrafici <span id="modeBadge" class="badge">da archivio scorso anno</span></p>
      <div class="grid">
        <div><label>ID alunno</label><input id="ID_ALUNNO" readonly></div>
        <div><label>Cognome alunno</label><input id="COGNOME_ALUNNO" readonly></div>
        <div><label>Nome alunno</label><input id="NOME_ALUNNO" readonly></div>
        <div><label>Codice fiscale alunno <span class="required">*</span></label><input id="CODICE_FISCALE_ALUNNO" readonly></div>

        <div><label>Classe vecchia</label><input id="CLASSE_VECCHIA" readonly></div>
        <div><label>Sezione vecchia</label><input id="SEZIONE_VECCHIA" readonly></div>
        <div><label>Istituto</label><input id="ISTITUTO_NOME" list="istitutiList"></div>
        <div><label>Città istituto</label><select id="ISTITUTO_CITTA"></select></div>

        <div><label>Comune residenza <span class="required">*</span></label><select id="COMUNE_RESIDENZA"></select></div>
        <div><label>Comune fuori provincia</label><input id="COMUNE_FUORI_PROVINCIA" placeholder="Solo se non è in provincia VT"></div>
      </div>
      <datalist id="istitutiList"></datalist>
    </section>

    <section class="card no-print">
      <p class="section-title">3) Dati genitore</p>
      <div class="grid">
        <div><label>Cognome genitore</label><input id="COGNOME_GENITORE"></div>
        <div><label>Nome genitore</label><input id="NOME_GENITORE"></div>
        <div><label>Cellulare / WhatsApp</label><input id="CELLULARE_GENITORE"></div>
        <div><label>Codice fiscale genitore <span class="required">*</span></label><input id="COD_FISC_GENITORE"></div>
      </div>
      <div class="actions">
        <button type="button" class="secondary" onclick="mostraFigliGenitore()">Mostra figli collegati</button>
        <button type="button" class="orange" onclick="aggiungiFiglioStessoGenitore()">Aggiungi altro figlio stesso genitore</button>
      </div>
      <div id="figliBox" class="table-wrap hidden" style="margin-top:12px;"></div>
    </section>

    <section class="card no-print">
      <p class="section-title">4) Dati nuovi da inserire <span class="required">*</span></p>
      <div class="grid">
        <div><label>Nuova classe <span class="required">*</span></label><select id="NUOVA_CLASSE" onchange="aggiornaSezioni()"></select></div>
        <div><label>Nuova sezione <span class="required">*</span></label><select id="NUOVA_SEZIONE"></select><div class="small">Classe 1: Tempo corto/Tempo lungo. Altre classi: sezioni A-Z.</div></div>
        <div><label>Religione <span class="required">*</span></label><select id="RELIGIONE"><option value=""></option><option>SI</option><option>NO</option></select></div>
        <div><label>Foderati <span class="required">*</span></label><select id="FODERATI"><option value=""></option><option>SI</option><option>NO</option></select></div>

        <div><label>Libro vacanze <span class="required">*</span></label><select id="LIBRO_VACANZE"><option value=""></option><option>SI</option><option>NO</option></select></div>
        <div><label>Etichette</label><select id="ETICHETTE"><option value=""></option><option>SI</option><option>NO</option></select></div>
        <div><label>Data prenotazione</label><input id="DATA_PRENOTAZIONE" type="date"></div>
        <div><label>Notifica WhatsApp</label><select id="WHATSAPP_NOTIFICA"><option>NO</option><option>SI</option></select></div>

        <div><label>Stato</label><select id="STATO_PRENOTAZIONE"><option>DA COMPLETARE</option><option>COMPLETATA</option><option>ANNULLATA</option></select></div>
        <div class="full"><label>Note nuovo anno</label><textarea id="NOTE_NUOVO_ANNO" placeholder="Note su libri, cedola, esigenze particolari..."></textarea></div>
      </div>
      <div class="actions">
        <button type="button" onclick="salvaPrenotazione()">Salva prenotazione</button>
        <button type="button" class="green" onclick="apriWhatsApp()">Invia/apri WhatsApp</button>
        <button type="button" class="orange" onclick="apriRicevutaDaPrenotazione()">Stampa ricevuta</button>
        <button type="button" class="secondary" onclick="pulisciMaschera()">Pulisci maschera</button>
      </div>
      <div id="msgSalva" class="hidden" style="margin-top:12px;"></div>
    </section>

    <section class="card no-print">
      <p class="section-title">Ultime prenotazioni salvate</p>
      <div class="actions"><button type="button" class="secondary" onclick="caricaUltime()">Aggiorna elenco</button></div>
      <div id="tabellaSalvati" class="table-wrap" style="margin-top:12px;"><div style="padding:12px;">Premi “Aggiorna elenco”.</div></div>
    </section>
  </section>

  <section id="screenRicevuta" class="screen hidden">
    <section class="card no-print">
      <p class="section-title">Ricerca prenotazioni</p>
      <div class="grid-2">
        <div>
          <label>Cerca alunno, genitore, codice fiscale, telefono o ID prenotazione</label>
          <div style="display:flex; gap:8px;">
            <input id="searchReceipt" placeholder="Es. BONI, PREN-..., codice fiscale...">
            <button type="button" onclick="cercaRicevute()">Cerca</button>
          </div>
          <div class="small">La ricerca prenotazioni legge il foglio nuovo <b>PRENOTAZIONI_2026_27</b>.</div>
        </div>
        <div><label>Stato</label><input id="statusReceipt" readonly value="Nessuna prenotazione selezionata"></div>
      </div>
      <div id="msgRicevuta" class="hidden" style="margin-top:12px;"></div>
      <div id="receiptResults" class="table-wrap hidden" style="margin-top:12px;"></div>
    </section>

    <section id="areaStampaRicevuta" class="card">
      <h2 style="margin:0 0 10px;color:var(--blu);">Ricevuta prenotazione libri scolastici 2026/27</h2>
      <div id="ricevutaBody"><p>Cerca e seleziona una prenotazione salvata.</p></div>
    </section>

    <section class="card no-print">
      <div class="actions">
        <button type="button" class="orange" onclick="window.print()">Stampa ricevuta</button>
        <button type="button" class="secondary" onclick="mostraSchermata('prenotazione')">Torna alla prenotazione</button>
      </div>
    </section>
  </section>
</main>

<script>
const API_URL = "https://script.google.com/macros/s/AKfycbyJsOR7OrCZj_WpK0Dd8AIFqMAor1LjFa2vDv8J-tBFlIkKb4U1Q_csK7y7JKgwXX80/exec";
const COMUNI_VT = ["ACQUAPENDENTE","ARLENA DI CASTRO","BAGNOREGIO","BARBARANO ROMANO","BASSANO IN TEVERINA","BASSANO ROMANO","BLERA","BOLSENA","BOMARZO","CALCATA","CANEPINA","CANINO","CAPODIMONTE","CAPRANICA","CAPRAROLA","CARBOGNANO","CASTEL SANT'ELIA","CASTIGLIONE IN TEVERINA","CELLENO","CELLERE","CIVITA CASTELLANA","CIVITELLA D'AGLIANO","CORCHIANO","FABRICA DI ROMA","FALERIA","FARNESE","GALLESE","GRADOLI","GRAFFIGNANO","GROTTE DI CASTRO","ISCHIA DI CASTRO","LATERA","LUBRIANO","MARTA","MONTALTO DI CASTRO","MONTE ROMANO","MONTEFIASCONE","MONTEROSI","NEPI","ONANO","ORIOLO ROMANO","ORTE","PIANSANO","PROCENO","RONCIGLIONE","SAN LORENZO NUOVO","SORIANO NEL CIMINO","SUTRI","TARQUINIA","TESSENNANO","TUSCANIA","VALENTANO","VALLERANO","VASANELLO","VEJANO","VETRALLA","VIGNANELLO","VILLA SAN GIOVANNI IN TUSCIA","VITERBO","VITORCHIANO"];
const ISTITUTI_BASE = ["PIO FEDI"];
const CAMPI = ["ID_ALUNNO","COGNOME_ALUNNO","NOME_ALUNNO","CODICE_FISCALE_ALUNNO","CLASSE_VECCHIA","SEZIONE_VECCHIA","ISTITUTO_NOME","ISTITUTO_CITTA","COMUNE_RESIDENZA","COMUNE_FUORI_PROVINCIA","COGNOME_GENITORE","NOME_GENITORE","CELLULARE_GENITORE","COD_FISC_GENITORE","NUOVA_CLASSE","NUOVA_SEZIONE","RELIGIONE","FODERATI","LIBRO_VACANZE","ETICHETTE","DATA_PRENOTAZIONE","WHATSAPP_NOTIFICA","STATO_PRENOTAZIONE","NOTE_NUOVO_ANNO"];
let ID_PRENOTAZIONE_CORRENTE = "";
let risultatiArchivio = [];
let risultatiRicevuta = [];

function api(action, params = {}) {
  return new Promise((resolve, reject) => {
    const callback = "cb_" + Date.now() + "_" + Math.floor(Math.random()*100000);
    const url = new URL(API_URL);
    url.searchParams.set("action", action);
    url.searchParams.set("callback", callback);
    Object.keys(params).forEach(k => url.searchParams.set(k, params[k]));

    const script = document.createElement("script");
    const timeout = setTimeout(() => { cleanup(); reject(new Error("Timeout collegamento Google Script")); }, 20000);

    window[callback] = data => { clearTimeout(timeout); cleanup(); resolve(data); };
    script.onerror = () => { clearTimeout(timeout); cleanup(); reject(new Error("Errore collegamento Google Script")); };

    function cleanup() {
      delete window[callback];
      if (script.parentNode) script.parentNode.removeChild(script);
    }

    script.src = url.toString();
    document.body.appendChild(script);
  });
}

function esc(v) {
  return String(v || "").replace(/&/g,"&amp;").replace(/</g,"&lt;").replace(/>/g,"&gt;").replace(/"/g,"&quot;");
}
function setMsg(id, testo, tipo="ok") {
  const el = document.getElementById(id);
  if (!el) return;
  el.className = tipo === "err" ? "errmsg" : "okmsg";
  el.textContent = testo;
  el.classList.remove("hidden");
}
function fillSelect(id, values, blank=true) {
  const el = document.getElementById(id);
  if (!el) return;
  el.innerHTML = "";
  if (blank) {
    const o = document.createElement("option");
    o.value = "";
    o.textContent = "";
    el.appendChild(o);
  }
  values.forEach(v => {
    const o = document.createElement("option");
    o.value = v;
    o.textContent = v;
    el.appendChild(o);
  });
}
function setField(id, value) {
  const el = document.getElementById(id);
  if (!el) return;
  const v = value == null ? "" : String(value);
  if (el.tagName === "SELECT" && v) {
    let exists = Array.from(el.options).some(o => o.value === v || o.textContent === v);
    if (!exists) {
      const opt = document.createElement("option");
      opt.value = v;
      opt.textContent = v;
      el.appendChild(opt);
    }
  }
  el.value = v;
}
function getField(id) {
  const el = document.getElementById(id);
  return el ? String(el.value || "").trim() : "";
}
function today() {
  return new Date().toISOString().slice(0, 10);
}

function mostraSchermata(nome) {
  document.getElementById("screenPrenotazione").classList.toggle("hidden", nome !== "prenotazione");
  document.getElementById("screenRicevuta").classList.toggle("hidden", nome !== "ricevuta");
  document.getElementById("tabPrenotazione").classList.toggle("active", nome === "prenotazione");
  document.getElementById("tabRicevuta").classList.toggle("active", nome === "ricevuta");
  window.scrollTo(0,0);
}

function init() {
  fillSelect("ISTITUTO_CITTA", COMUNI_VT);
  fillSelect("COMUNE_RESIDENZA", COMUNI_VT);
  fillSelect("NUOVA_CLASSE", ["1","2","3","4","5"]);
  aggiornaSezioni();

  const dl = document.getElementById("istitutiList");
  ISTITUTI_BASE.forEach(i => {
    const o = document.createElement("option");
    o.value = i;
    dl.appendChild(o);
  });

  setField("DATA_PRENOTAZIONE", today());

  document.getElementById("searchBox").addEventListener("keydown", e => {
    if (e.key === "Enter") { e.preventDefault(); cercaArchivio(); }
  });
  document.getElementById("searchReceipt").addEventListener("keydown", e => {
    if (e.key === "Enter") { e.preventDefault(); cercaRicevute(); }
  });
}

function aggiornaSezioni() {
  const classe = getField("NUOVA_CLASSE");
  const corrente = getField("NUOVA_SEZIONE");
  const opzioni = classe === "1" ? ["TEMPO CORTO","TEMPO LUNGO"] : (classe ? "ABCDEFGHIJKLMNOPQRSTUVWXYZ".split("") : []);
  fillSelect("NUOVA_SEZIONE", opzioni);
  if (corrente && opzioni.includes(corrente)) setField("NUOVA_SEZIONE", corrente);
}

async function cercaArchivio() {
  const q = getField("searchBox");
  if (!q) { alert("Inserisci un testo da cercare."); return; }
  document.getElementById("quickStatus").value = "Ricerca in corso...";
  setMsg("msgRicerca", "Ricerca nel vecchio archivio Google...", "ok");
  try {
    const res = await api("cercaArchivio", { q });
    if (!Array.isArray(res)) throw new Error(res && res.message ? res.message : "Risposta non valida.");
    risultatiArchivio = res;
    mostraRisultatiArchivio(res);
  } catch (err) {
    setMsg("msgRicerca", "Errore ricerca: " + err.message, "err");
    document.getElementById("quickStatus").value = "Errore ricerca";
  }
}

function mostraRisultatiArchivio(rows) {
  const box = document.getElementById("searchResults");
  box.classList.remove("hidden");
  if (!rows.length) {
    box.innerHTML = '<div style="padding:12px;color:#b91c1c;font-weight:800;">Nessun risultato trovato.</div>';
    document.getElementById("quickStatus").value = "Nessun risultato trovato";
    return;
  }
  document.getElementById("quickStatus").value = "Risultati trovati: " + rows.length;
  setMsg("msgRicerca", "Risultati trovati: " + rows.length + ". Clicca una riga per caricarla.", "ok");
  let t = '<table><thead><tr><th>Alunno</th><th>Genitore</th><th>Telefono</th><th>CF alunno</th><th>Classe vecchia</th><th>Istituto</th></tr></thead><tbody>';
  rows.forEach((r, i) => {
    const alunno = ((r.COGNOME_ALUNNO || "") + " " + (r.NOME_ALUNNO || "")).trim();
    const genitore = ((r.COGNOME_GENITORE || "") + " " + (r.NOME_GENITORE || "")).trim();
    const classe = ((r.CLASSE_VECCHIA || "") + " " + (r.SEZIONE_VECCHIA || "")).trim();
    const istituto = ((r.ISTITUTO_NOME || "") + " " + (r.ISTITUTO_CITTA || "")).trim();
    t += `<tr class="result-row" onclick="caricaDaArchivio(${i})"><td>${esc(alunno)}</td><td>${esc(genitore)}</td><td>${esc(r.CELLULARE_GENITORE)}</td><td>${esc(r.CODICE_FISCALE_ALUNNO)}</td><td>${esc(classe)}</td><td>${esc(istituto)}</td></tr>`;
  });
  t += '</tbody></table>';
  box.innerHTML = t;
}

function caricaDaArchivio(i) {
  const r = risultatiArchivio[i];
  if (!r) return;
  ID_PRENOTAZIONE_CORRENTE = "";
  CAMPI.forEach(c => setField(c, r[c] || ""));
  setField("DATA_PRENOTAZIONE", today());
  aggiornaSezioni();
  if (r.NUOVA_SEZIONE) setField("NUOVA_SEZIONE", r.NUOVA_SEZIONE);
  document.getElementById("modeBadge").textContent = "caricato da Google Fogli";
  document.getElementById("quickStatus").value = "Selezionato: " + ((r.COGNOME_ALUNNO || "") + " " + (r.NOME_ALUNNO || "")).trim();
  document.getElementById("searchResults").classList.add("hidden");
}

function nuovaAnagrafica() {
  pulisciMaschera();
  ["ID_ALUNNO","COGNOME_ALUNNO","NOME_ALUNNO","CODICE_FISCALE_ALUNNO"].forEach(id => {
    const el = document.getElementById(id);
    if (el) el.removeAttribute("readonly");
  });
  document.getElementById("modeBadge").textContent = "nuova anagrafica";
  document.getElementById("quickStatus").value = "Nuova anagrafica: compila i dati";
  setField("STATO_PRENOTAZIONE", "DA COMPLETARE");
  setField("DATA_PRENOTAZIONE", today());
}

function pulisciMaschera() {
  ID_PRENOTAZIONE_CORRENTE = "";
  CAMPI.forEach(c => setField(c, ""));
  ["ID_ALUNNO","COGNOME_ALUNNO","NOME_ALUNNO","CODICE_FISCALE_ALUNNO","CLASSE_VECCHIA","SEZIONE_VECCHIA"].forEach(id => {
    const el = document.getElementById(id);
    if (el) el.setAttribute("readonly", "readonly");
  });
  fillSelect("ISTITUTO_CITTA", COMUNI_VT);
  fillSelect("COMUNE_RESIDENZA", COMUNI_VT);
  fillSelect("NUOVA_CLASSE", ["1","2","3","4","5"]);
  aggiornaSezioni();
  setField("DATA_PRENOTAZIONE", today());
  setField("WHATSAPP_NOTIFICA", "NO");
  setField("STATO_PRENOTAZIONE", "DA COMPLETARE");
  document.getElementById("modeBadge").textContent = "da archivio scorso anno";
}

function raccogliDati() {
  const d = {};
  CAMPI.forEach(c => d[c] = getField(c));
  d.ID_PRENOTAZIONE = ID_PRENOTAZIONE_CORRENTE;
  return d;
}

function validaLocale(d) {
  const checks = [
    ["COGNOME_ALUNNO", "Cognome alunno obbligatorio"],
    ["NOME_ALUNNO", "Nome alunno obbligatorio"],
    ["CODICE_FISCALE_ALUNNO", "Codice fiscale del figlio/alunno obbligatorio"],
    ["COD_FISC_GENITORE", "Codice fiscale del genitore obbligatorio"],
    ["NUOVA_CLASSE", "Nuova classe obbligatoria"],
    ["NUOVA_SEZIONE", "Nuova sezione obbligatoria"],
    ["RELIGIONE", "Religione obbligatoria"],
    ["FODERATI", "Foderati obbligatorio"],
    ["LIBRO_VACANZE", "Libro vacanze obbligatorio"]
  ];
  for (const [id, msg] of checks) {
    if (!d[id]) {
      alert(msg);
      const el = document.getElementById(id);
      if (el) el.focus();
      return false;
    }
  }
  if (!d.COMUNE_RESIDENZA && !d.COMUNE_FUORI_PROVINCIA) {
    alert("Comune di residenza del figlio obbligatorio. Se fuori provincia, usa Comune fuori provincia.");
    document.getElementById("COMUNE_RESIDENZA").focus();
    return false;
  }
  return true;
}

async function salvaPrenotazione() {
  const d = raccogliDati();
  if (!validaLocale(d)) return;
  setMsg("msgSalva", "Salvataggio in corso...", "ok");
  try {
    const res = await api("salva", { data: encodeURIComponent(JSON.stringify(d)) });
    if (!res || !res.ok) throw new Error(res && res.message ? res.message : "Errore salvataggio");
    ID_PRENOTAZIONE_CORRENTE = res.id;
    setMsg("msgSalva", "Prenotazione salvata correttamente. ID: " + res.id, "ok");
    document.getElementById("quickStatus").value = "Salvata: " + res.id;
    caricaUltime();
  } catch (err) {
    setMsg("msgSalva", "Errore salvataggio: " + err.message, "err");
    alert("Errore salvataggio: " + err.message);
  }
}

async function mostraFigliGenitore() {
  const d = raccogliDati();
  const box = document.getElementById("figliBox");
  box.classList.remove("hidden");
  box.innerHTML = '<div style="padding:12px;">Ricerca figli collegati...</div>';
  try {
    const res = await api("figli", { data: encodeURIComponent(JSON.stringify(d)) });
    if (!Array.isArray(res) || !res.length) {
      box.innerHTML = '<div style="padding:12px;">Nessun figlio collegato trovato.</div>';
      return;
    }
    let t = '<table><thead><tr><th>Alunno</th><th>Classe vecchia</th><th>Istituto</th></tr></thead><tbody>';
    res.forEach(r => {
      t += `<tr><td>${esc((r.COGNOME_ALUNNO || "") + " " + (r.NOME_ALUNNO || ""))}</td><td>${esc((r.CLASSE_VECCHIA || "") + " " + (r.SEZIONE_VECCHIA || ""))}</td><td>${esc(r.ISTITUTO_NOME || "")}</td></tr>`;
    });
    t += '</tbody></table>';
    box.innerHTML = t;
  } catch (err) {
    box.innerHTML = '<div style="padding:12px;color:#b91c1c;">Errore: ' + esc(err.message) + '</div>';
  }
}

function aggiungiFiglioStessoGenitore() {
  const gen = {
    COGNOME_GENITORE: getField("COGNOME_GENITORE"),
    NOME_GENITORE: getField("NOME_GENITORE"),
    CELLULARE_GENITORE: getField("CELLULARE_GENITORE"),
    COD_FISC_GENITORE: getField("COD_FISC_GENITORE"),
    COMUNE_RESIDENZA: getField("COMUNE_RESIDENZA"),
    COMUNE_FUORI_PROVINCIA: getField("COMUNE_FUORI_PROVINCIA")
  };
  nuovaAnagrafica();
  Object.keys(gen).forEach(k => setField(k, gen[k]));
}

function apriWhatsApp() {
  const tel = getField("CELLULARE_GENITORE").replace(/\D/g, "");
  if (!tel) { alert("Numero WhatsApp mancante."); return; }
  let n = tel;
  if (n.startsWith("0")) n = "39" + n.substring(1);
  if (!n.startsWith("39")) n = "39" + n;
  const alunno = (getField("COGNOME_ALUNNO") + " " + getField("NOME_ALUNNO")).trim();
  const msg = `Buongiorno, confermiamo la prenotazione libri scolastici 2026/27 per ${alunno}. Classe ${getField("NUOVA_CLASSE")}, sezione ${getField("NUOVA_SEZIONE")}.`;
  window.open("https://wa.me/" + n + "?text=" + encodeURIComponent(msg), "_blank");
}

function apriRicevutaDaPrenotazione() {
  if (!ID_PRENOTAZIONE_CORRENTE) {
    alert("Prima salva la prenotazione, poi apri la ricevuta.");
    return;
  }
  mostraSchermata("ricevuta");
  caricaRicevutaDaId(ID_PRENOTAZIONE_CORRENTE);
}

async function caricaUltime() {
  const box = document.getElementById("tabellaSalvati");
  box.innerHTML = '<div style="padding:12px;">Caricamento...</div>';
  try {
    const res = await api("cercaNuove", { q: "" });
    if (!Array.isArray(res) || !res.length) {
      box.innerHTML = '<div style="padding:12px;">Nessuna prenotazione nuova salvata.</div>';
      return;
    }
    let t = '<table><thead><tr><th>Alunno</th><th>Genitore</th><th>Classe</th><th>Rel.</th><th>Fod.</th><th>Vacanze</th><th>Etichette</th><th>Stato</th></tr></thead><tbody>';
    res.forEach(r => {
      t += `<tr><td>${esc((r.COGNOME_ALUNNO || "") + " " + (r.NOME_ALUNNO || ""))}</td><td>${esc((r.COGNOME_GENITORE || "") + " " + (r.NOME_GENITORE || ""))}</td><td>${esc((r.NUOVA_CLASSE || "") + " " + (r.NUOVA_SEZIONE || ""))}</td><td>${esc(r.RELIGIONE)}</td><td>${esc(r.FODERATI)}</td><td>${esc(r.LIBRO_VACANZE)}</td><td>${esc(r.ETICHETTE)}</td><td>${esc(r.STATO_PRENOTAZIONE)}</td></tr>`;
    });
    t += '</tbody></table>';
    box.innerHTML = t;
  } catch (err) {
    box.innerHTML = '<div style="padding:12px;color:#b91c1c;">Errore: ' + esc(err.message) + '</div>';
  }
}

async function cercaRicevute() {
  const q = getField("searchReceipt");
  if (!q) { alert("Scrivi un testo da cercare."); return; }
  document.getElementById("statusReceipt").value = "Ricerca in corso...";
  try {
    const res = await api("cercaNuove", { q });
    if (!Array.isArray(res)) throw new Error(res && res.message ? res.message : "Risposta non valida");
    risultatiRicevuta = res;
    mostraRisultatiRicevuta(res);
  } catch (err) {
    setMsg("msgRicevuta", "Errore ricerca: " + err.message, "err");
  }
}

function mostraRisultatiRicevuta(rows) {
  const box = document.getElementById("receiptResults");
  box.classList.remove("hidden");
  if (!rows.length) {
    box.innerHTML = '<div style="padding:12px;color:#b91c1c;font-weight:800;">Nessuna prenotazione salvata trovata.</div>';
    document.getElementById("statusReceipt").value = "Nessun risultato";
    return;
  }
  document.getElementById("statusReceipt").value = "Risultati trovati: " + rows.length;
  let t = '<table><thead><tr><th>ID</th><th>Alunno</th><th>Genitore</th><th>Classe</th><th>Data</th></tr></thead><tbody>';
  rows.forEach((r, i) => {
    t += `<tr class="result-row" onclick="selezionaRicevuta(${i})"><td>${esc(r.ID_PRENOTAZIONE)}</td><td>${esc((r.COGNOME_ALUNNO || "") + " " + (r.NOME_ALUNNO || ""))}</td><td>${esc((r.COGNOME_GENITORE || "") + " " + (r.NOME_GENITORE || ""))}</td><td>${esc((r.NUOVA_CLASSE || "") + " " + (r.NUOVA_SEZIONE || ""))}</td><td>${esc(r.DATA_PRENOTAZIONE)}</td></tr>`;
  });
  t += '</tbody></table>';
  box.innerHTML = t;
}

function selezionaRicevuta(i) {
  const r = risultatiRicevuta[i];
  if (r) renderRicevuta(r);
}

async function caricaRicevutaDaId(id) {
  try {
    const r = await api("ricevuta", { id });
    if (!r) throw new Error("Ricevuta non trovata.");
    renderRicevuta(r);
  } catch (err) {
    setMsg("msgRicevuta", "Errore: " + err.message, "err");
  }
}

function renderRicevuta(r) {
  document.getElementById("statusReceipt").value = "Ricevuta selezionata: " + (r.ID_PRENOTAZIONE || "");
  document.getElementById("ricevutaBody").innerHTML = `
    <p><strong>ID prenotazione:</strong> ${esc(r.ID_PRENOTAZIONE || "-")}</p>
    <p><strong>Data prenotazione:</strong> ${esc(r.DATA_PRENOTAZIONE || "-")}</p>
    <hr>
    <p><strong>Alunno:</strong> ${esc((r.COGNOME_ALUNNO || "") + " " + (r.NOME_ALUNNO || ""))}</p>
    <p><strong>Codice fiscale alunno:</strong> ${esc(r.CODICE_FISCALE_ALUNNO || "-")}</p>
    <p><strong>Comune residenza:</strong> ${esc(r.COMUNE_RESIDENZA || r.COMUNE_FUORI_PROVINCIA || "-")}</p>
    <p><strong>Istituto:</strong> ${esc(r.ISTITUTO_NOME || "-")} - ${esc(r.ISTITUTO_CITTA || "-")}</p>
    <hr>
    <p><strong>Genitore:</strong> ${esc((r.COGNOME_GENITORE || "") + " " + (r.NOME_GENITORE || ""))}</p>
    <p><strong>Codice fiscale genitore:</strong> ${esc(r.COD_FISC_GENITORE || "-")}</p>
    <p><strong>Cellulare / WhatsApp:</strong> ${esc(r.CELLULARE_GENITORE || "-")}</p>
    <hr>
    <p><strong>Nuova classe:</strong> ${esc(r.NUOVA_CLASSE || "-")}</p>
    <p><strong>Nuova sezione:</strong> ${esc(r.NUOVA_SEZIONE || "-")}</p>
    <p><strong>Religione:</strong> ${esc(r.RELIGIONE || "-")}</p>
    <p><strong>Foderati:</strong> ${esc(r.FODERATI || "-")}</p>
    <p><strong>Libro vacanze:</strong> ${esc(r.LIBRO_VACANZE || "-")}</p>
    <p><strong>Etichette:</strong> ${esc(r.ETICHETTE || "-")}</p>
    <p><strong>Note:</strong> ${esc(r.NOTE_NUOVO_ANNO || "-")}</p>
    <br><br>
    <p>Firma operatore __________________________</p>
    <p>Firma genitore ___________________________</p>
  `;
}

window.addEventListener("DOMContentLoaded", init);

/* =========================================================
   PATCH RICEVUTA DA MODULO PRENOTAZIONE
   - Stampa direttamente dalla scheda prenotazione
   - Include sempre DATA_PRENOTAZIONE
   - Non dipende dalla ricerca ricevute
   ========================================================= */

function recordDaModuloPrenotazione() {
  const r = {};

  CAMPI.forEach(campo => {
    r[campo] = getField(campo);
  });

  r.ID_PRENOTAZIONE = ID_PRENOTAZIONE_CORRENTE || "";
  return r;
}

function valoreRicevuta(v) {
  return String(v || "").trim() || "-";
}

function htmlRicevutaDaRecord(r) {
  const alunno = valoreRicevuta((r.COGNOME_ALUNNO || "") + " " + (r.NOME_ALUNNO || ""));
  const genitore = valoreRicevuta((r.COGNOME_GENITORE || "") + " " + (r.NOME_GENITORE || ""));
  const comune = valoreRicevuta(r.COMUNE_RESIDENZA || r.COMUNE_FUORI_PROVINCIA);
  const dataPrenotazione = valoreRicevuta(r.DATA_PRENOTAZIONE || new Date().toLocaleDateString("it-IT"));

  return `
    <p><strong>ID prenotazione:</strong> ${esc(r.ID_PRENOTAZIONE || "Non ancora salvata")}</p>
    <p><strong>Data prenotazione:</strong> ${esc(dataPrenotazione)}</p>
    <hr>
    <p><strong>Alunno:</strong> ${esc(alunno)}</p>
    <p><strong>Codice fiscale alunno:</strong> ${esc(valoreRicevuta(r.CODICE_FISCALE_ALUNNO))}</p>
    <p><strong>Comune residenza:</strong> ${esc(comune)}</p>
    <p><strong>Istituto:</strong> ${esc(valoreRicevuta(r.ISTITUTO_NOME))} - ${esc(valoreRicevuta(r.ISTITUTO_CITTA))}</p>
    <hr>
    <p><strong>Genitore:</strong> ${esc(genitore)}</p>
    <p><strong>Codice fiscale genitore:</strong> ${esc(valoreRicevuta(r.COD_FISC_GENITORE))}</p>
    <p><strong>Cellulare / WhatsApp:</strong> ${esc(valoreRicevuta(r.CELLULARE_GENITORE))}</p>
    <hr>
    <p><strong>Nuova classe:</strong> ${esc(valoreRicevuta(r.NUOVA_CLASSE))}</p>
    <p><strong>Nuova sezione:</strong> ${esc(valoreRicevuta(r.NUOVA_SEZIONE))}</p>
    <p><strong>Religione:</strong> ${esc(valoreRicevuta(r.RELIGIONE))}</p>
    <p><strong>Foderati:</strong> ${esc(valoreRicevuta(r.FODERATI))}</p>
    <p><strong>Libro vacanze:</strong> ${esc(valoreRicevuta(r.LIBRO_VACANZE))}</p>
    <p><strong>Etichette:</strong> ${esc(valoreRicevuta(r.ETICHETTE))}</p>
    <p><strong>Note:</strong> ${esc(valoreRicevuta(r.NOTE_NUOVO_ANNO))}</p>
    <br><br>
    <p>Firma operatore __________________________</p>
    <p>Firma genitore ___________________________</p>
  `;
}

function stampaRicevutaRecordDiretta(r) {
  const alunno = String((r.COGNOME_ALUNNO || "") + (r.NOME_ALUNNO || "")).trim();

  if (!alunno) {
    alert("Prima seleziona o compila una prenotazione.");
    return;
  }

  const body = document.getElementById("ricevutaBody");
  const area = document.getElementById("areaStampaRicevuta");

  if (!body || !area) {
    alert("Area ricevuta non trovata.");
    return;
  }

  body.innerHTML = htmlRicevutaDaRecord(r);

  const status = document.getElementById("statusReceipt");
  if (status) {
    status.value = "Ricevuta pronta";
  }

  // Rendo visibile la schermata ricevuta per evitare stampa bianca.
  mostraSchermata("ricevuta");

  setTimeout(() => {
    window.print();
  }, 250);
}

// Sovrascrive la vecchia funzione: ora stampa direttamente dal modulo.
function apriRicevutaDaPrenotazione() {
  const r = recordDaModuloPrenotazione();

  if (!r.DATA_PRENOTAZIONE) {
    r.DATA_PRENOTAZIONE = new Date().toISOString().slice(0, 10);
    setField("DATA_PRENOTAZIONE", r.DATA_PRENOTAZIONE);
  }

  stampaRicevutaRecordDiretta(r);
}

// Migliora anche la ricevuta dalla ricerca: assicura sempre la data prenotazione.
const renderRicevutaOriginale = renderRicevuta;
renderRicevuta = function(r) {
  if (!r.DATA_PRENOTAZIONE) {
    r.DATA_PRENOTAZIONE = "-";
  }

  renderRicevutaOriginale(r);
};


/* =========================================================
   PATCH RICERCA PRENOTAZIONI
   - Aggiunge Modifica, WhatsApp, Ristampa ricevuta
   - Corregge ricevuta dalla ricerca con data prenotazione
   ========================================================= */

function recordRicercaConData(r) {
  const copia = Object.assign({}, r || {});
  if (!copia.DATA_PRENOTAZIONE) {
    copia.DATA_PRENOTAZIONE = "-";
  }
  return copia;
}

function stampaRicevutaDaRicerca(index) {
  const r = risultatiRicevuta[index];

  if (!r) {
    alert("Prenotazione non trovata.");
    return;
  }

  stampaRicevutaRecordDiretta(recordRicercaConData(r));
}

function caricaPrenotazioneDaRicerca(index) {
  const r = risultatiRicevuta[index];

  if (!r) {
    alert("Prenotazione non trovata.");
    return;
  }

  ID_PRENOTAZIONE_CORRENTE = r.ID_PRENOTAZIONE || "";

  CAMPI.forEach(campo => {
    setField(campo, r[campo] || "");
  });

  aggiornaSezioni();

  if (r.NUOVA_SEZIONE) {
    setField("NUOVA_SEZIONE", r.NUOVA_SEZIONE);
  }

  // Se è una nuova anagrafica senza ID alunno, lascia modificabili i dati alunno.
  if (!r.ID_ALUNNO) {
    ["ID_ALUNNO", "COGNOME_ALUNNO", "NOME_ALUNNO", "CODICE_FISCALE_ALUNNO"].forEach(id => {
      const el = document.getElementById(id);
      if (el) el.removeAttribute("readonly");
    });
  } else {
    ["ID_ALUNNO", "COGNOME_ALUNNO", "NOME_ALUNNO", "CODICE_FISCALE_ALUNNO"].forEach(id => {
      const el = document.getElementById(id);
      if (el) el.setAttribute("readonly", "readonly");
    });
  }

  document.getElementById("modeBadge").textContent = "prenotazione salvata da modificare";
  document.getElementById("quickStatus").value = "Modifica prenotazione: " + (r.ID_PRENOTAZIONE || "");

  mostraSchermata("prenotazione");
}

function inviaWhatsAppDaRicerca(index) {
  const r = risultatiRicevuta[index];

  if (!r) {
    alert("Prenotazione non trovata.");
    return;
  }

  let telefono = String(r.CELLULARE_GENITORE || "").replace(/\D/g, "");

  if (!telefono) {
    alert("Numero WhatsApp mancante per questa prenotazione.");
    return;
  }

  if (telefono.startsWith("0")) {
    telefono = "39" + telefono.substring(1);
  }

  if (!telefono.startsWith("39")) {
    telefono = "39" + telefono;
  }

  const alunno = ((r.COGNOME_ALUNNO || "") + " " + (r.NOME_ALUNNO || "")).trim();

  const messaggio =
    "Buongiorno, confermiamo la prenotazione libri scolastici 2026/27 per " +
    alunno +
    ". Classe " +
    (r.NUOVA_CLASSE || "-") +
    ", sezione " +
    (r.NUOVA_SEZIONE || "-") +
    ".";

  window.open("https://wa.me/" + telefono + "?text=" + encodeURIComponent(messaggio), "_blank");
}

// Sovrascrive la tabella ricerca: ora include i pulsanti azione.
mostraRisultatiRicevuta = function(rows) {
  const box = document.getElementById("receiptResults");
  box.classList.remove("hidden");

  if (!rows.length) {
    box.innerHTML = '<div style="padding:12px;color:#b91c1c;font-weight:800;">Nessuna prenotazione salvata trovata.</div>';
    document.getElementById("statusReceipt").value = "Nessun risultato";
    return;
  }

  document.getElementById("statusReceipt").value = "Risultati trovati: " + rows.length;

  let t = '<table><thead><tr>';
  t += '<th>ID</th>';
  t += '<th>Alunno</th>';
  t += '<th>Genitore</th>';
  t += '<th>Telefono</th>';
  t += '<th>CF alunno</th>';
  t += '<th>CF genitore</th>';
  t += '<th>Classe</th>';
  t += '<th>Data</th>';
  t += '<th>Azioni</th>';
  t += '</tr></thead><tbody>';

  rows.forEach((r, i) => {
    const alunno = ((r.COGNOME_ALUNNO || "") + " " + (r.NOME_ALUNNO || "")).trim();
    const genitore = ((r.COGNOME_GENITORE || "") + " " + (r.NOME_GENITORE || "")).trim();
    const classe = ((r.NUOVA_CLASSE || "") + " " + (r.NUOVA_SEZIONE || "")).trim();

    t += '<tr>';
    t += `<td>${esc(r.ID_PRENOTAZIONE || "")}</td>`;
    t += `<td>${esc(alunno)}</td>`;
    t += `<td>${esc(genitore)}</td>`;
    t += `<td>${esc(r.CELLULARE_GENITORE || "")}</td>`;
    t += `<td>${esc(r.CODICE_FISCALE_ALUNNO || "")}</td>`;
    t += `<td>${esc(r.COD_FISC_GENITORE || "")}</td>`;
    t += `<td>${esc(classe)}</td>`;
    t += `<td>${esc(r.DATA_PRENOTAZIONE || "-")}</td>`;
    t += '<td>';
    t += '<div style="display:flex;gap:6px;flex-wrap:wrap;">';
    t += `<button type="button" onclick="caricaPrenotazioneDaRicerca(${i})">Modifica</button>`;
    t += `<button type="button" class="green" onclick="inviaWhatsAppDaRicerca(${i})">WhatsApp</button>`;
    t += `<button type="button" class="orange" onclick="stampaRicevutaDaRicerca(${i})">Ricevuta</button>`;
    t += '</div>';
    t += '</td>';
    t += '</tr>';
  });

  t += '</tbody></table>';
  box.innerHTML = t;
};

// Sovrascrive il click sulla riga: cliccare una riga ora stampa la ricevuta,
// ma i pulsanti permettono modifica/whatsapp/ricevuta.
selezionaRicevuta = function(i) {
  stampaRicevutaDaRicerca(i);
};

// Sovrascrive renderRicevuta per includere sempre DATA_PRENOTAZIONE.
renderRicevuta = function(r) {
  const rec = recordRicercaConData(r);

  document.getElementById("statusReceipt").value = "Ricevuta selezionata: " + (rec.ID_PRENOTAZIONE || "");
  document.getElementById("ricevutaBody").innerHTML = htmlRicevutaDaRecord(rec);
};


/* =========================================================
   PATCH DATA PRENOTAZIONE RICERCA/RICEVUTA
   - Mostra DATA_PRENOTAZIONE nella tabella ricerca
   - La passa correttamente alla ricevuta stampata da ricerca
   ========================================================= */

function dataPrenotazioneVisibile(r) {
  return String(
    r.DATA_PRENOTAZIONE ||
    r.DATA_ORA_SALVATAGGIO ||
    r.DATA ||
    ""
  ).trim() || "-";
}

function recordRicercaConDataFinale(r) {
  const copia = Object.assign({}, r || {});
  copia.DATA_PRENOTAZIONE = dataPrenotazioneVisibile(copia);
  return copia;
}

function stampaRicevutaDaRicerca(index) {
  const r = risultatiRicevuta[index];

  if (!r) {
    alert("Prenotazione non trovata.");
    return;
  }

  stampaRicevutaRecordDiretta(recordRicercaConDataFinale(r));
}

mostraRisultatiRicevuta = function(rows) {
  const box = document.getElementById("receiptResults");
  box.classList.remove("hidden");

  if (!rows.length) {
    box.innerHTML = '<div style="padding:12px;color:#b91c1c;font-weight:800;">Nessuna prenotazione salvata trovata.</div>';
    document.getElementById("statusReceipt").value = "Nessun risultato";
    return;
  }

  document.getElementById("statusReceipt").value = "Risultati trovati: " + rows.length;

  let t = '<table><thead><tr>';
  t += '<th>ID</th>';
  t += '<th>Data prenotazione</th>';
  t += '<th>Alunno</th>';
  t += '<th>Genitore</th>';
  t += '<th>Telefono</th>';
  t += '<th>CF alunno</th>';
  t += '<th>CF genitore</th>';
  t += '<th>Classe</th>';
  t += '<th>Azioni</th>';
  t += '</tr></thead><tbody>';

  rows.forEach((r, i) => {
    const rec = recordRicercaConDataFinale(r);
    const alunno = ((rec.COGNOME_ALUNNO || "") + " " + (rec.NOME_ALUNNO || "")).trim();
    const genitore = ((rec.COGNOME_GENITORE || "") + " " + (rec.NOME_GENITORE || "")).trim();
    const classe = ((rec.NUOVA_CLASSE || "") + " " + (rec.NUOVA_SEZIONE || "")).trim();

    t += '<tr>';
    t += `<td>${esc(rec.ID_PRENOTAZIONE || "")}</td>`;
    t += `<td>${esc(rec.DATA_PRENOTAZIONE || "-")}</td>`;
    t += `<td>${esc(alunno)}</td>`;
    t += `<td>${esc(genitore)}</td>`;
    t += `<td>${esc(rec.CELLULARE_GENITORE || "")}</td>`;
    t += `<td>${esc(rec.CODICE_FISCALE_ALUNNO || "")}</td>`;
    t += `<td>${esc(rec.COD_FISC_GENITORE || "")}</td>`;
    t += `<td>${esc(classe)}</td>`;
    t += '<td>';
    t += '<div style="display:flex;gap:6px;flex-wrap:wrap;">';
    t += `<button type="button" onclick="caricaPrenotazioneDaRicerca(${i})">Modifica</button>`;
    t += `<button type="button" class="green" onclick="inviaWhatsAppDaRicerca(${i})">WhatsApp</button>`;
    t += `<button type="button" class="orange" onclick="stampaRicevutaDaRicerca(${i})">Ricevuta</button>`;
    t += '</div>';
    t += '</td>';
    t += '</tr>';
  });

  t += '</tbody></table>';
  box.innerHTML = t;
};

selezionaRicevuta = function(i) {
  stampaRicevutaDaRicerca(i);
};

renderRicevuta = function(r) {
  const rec = recordRicercaConDataFinale(r);
  document.getElementById("statusReceipt").value = "Ricevuta selezionata: " + (rec.ID_PRENOTAZIONE || "");
  document.getElementById("ricevutaBody").innerHTML = htmlRicevutaDaRecord(rec);
};


/* =========================================================
   PATCH ETICHETTE E NOTE IN RICEVUTA DA RICERCA
   - Recupera Etichette anche da nomi colonna alternativi
   - Recupera Note anche da nomi colonna alternativi
   ========================================================= */

function primoValoreNonVuoto() {
  for (let i = 0; i < arguments.length; i++) {
    const v = arguments[i];
    if (v !== undefined && v !== null && String(v).trim() !== "") {
      return String(v).trim();
    }
  }
  return "";
}

function normalizzaRecordRicevutaCompleto(r) {
  const copia = Object.assign({}, r || {});

  copia.DATA_PRENOTAZIONE = primoValoreNonVuoto(
    copia.DATA_PRENOTAZIONE,
    copia.DATA_ORA_SALVATAGGIO,
    copia.DATA,
    "-"
  );

  copia.ETICHETTE = primoValoreNonVuoto(
    copia.ETICHETTE,
    copia.ETICHETTA,
    copia.ETICHETE,
    copia.ETIC,
    copia.LIBRI_ETICHETTE,
    "-"
  );

  copia.NOTE_NUOVO_ANNO = primoValoreNonVuoto(
    copia.NOTE_NUOVO_ANNO,
    copia.NOTE,
    copia.NOTA,
    copia.NOTE_PRENOTAZIONE,
    copia.NOTE_LIBRI,
    copia.NOTE_RICEVUTA,
    "-"
  );

  return copia;
}

function htmlRicevutaDaRecordCompleto(r) {
  const rec = normalizzaRecordRicevutaCompleto(r);

  const alunno = valoreRicevuta((rec.COGNOME_ALUNNO || "") + " " + (rec.NOME_ALUNNO || ""));
  const genitore = valoreRicevuta((rec.COGNOME_GENITORE || "") + " " + (rec.NOME_GENITORE || ""));
  const comune = valoreRicevuta(rec.COMUNE_RESIDENZA || rec.COMUNE_FUORI_PROVINCIA);
  const dataPrenotazione = valoreRicevuta(rec.DATA_PRENOTAZIONE);

  return `
    <p><strong>ID prenotazione:</strong> ${esc(rec.ID_PRENOTAZIONE || "Non ancora salvata")}</p>
    <p><strong>Data prenotazione:</strong> ${esc(dataPrenotazione)}</p>
    <hr>
    <p><strong>Alunno:</strong> ${esc(alunno)}</p>
    <p><strong>Codice fiscale alunno:</strong> ${esc(valoreRicevuta(rec.CODICE_FISCALE_ALUNNO))}</p>
    <p><strong>Comune residenza:</strong> ${esc(comune)}</p>
    <p><strong>Istituto:</strong> ${esc(valoreRicevuta(rec.ISTITUTO_NOME))} - ${esc(valoreRicevuta(rec.ISTITUTO_CITTA))}</p>
    <hr>
    <p><strong>Genitore:</strong> ${esc(genitore)}</p>
    <p><strong>Codice fiscale genitore:</strong> ${esc(valoreRicevuta(rec.COD_FISC_GENITORE))}</p>
    <p><strong>Cellulare / WhatsApp:</strong> ${esc(valoreRicevuta(rec.CELLULARE_GENITORE))}</p>
    <hr>
    <p><strong>Nuova classe:</strong> ${esc(valoreRicevuta(rec.NUOVA_CLASSE))}</p>
    <p><strong>Nuova sezione:</strong> ${esc(valoreRicevuta(rec.NUOVA_SEZIONE))}</p>
    <p><strong>Religione:</strong> ${esc(valoreRicevuta(rec.RELIGIONE))}</p>
    <p><strong>Foderati:</strong> ${esc(valoreRicevuta(rec.FODERATI))}</p>
    <p><strong>Libro vacanze:</strong> ${esc(valoreRicevuta(rec.LIBRO_VACANZE))}</p>
    <p><strong>Etichette:</strong> ${esc(valoreRicevuta(rec.ETICHETTE))}</p>
    <p><strong>Note:</strong> ${esc(valoreRicevuta(rec.NOTE_NUOVO_ANNO))}</p>
    <br><br>
    <p>Firma operatore __________________________</p>
    <p>Firma genitore ___________________________</p>
  `;
}

// Sovrascrive la funzione usata dalla ricevuta, mantenendo stesso nome.
htmlRicevutaDaRecord = function(r) {
  return htmlRicevutaDaRecordCompleto(r);
};

// Sovrascrive la stampa da ricerca per passare il record completo.
stampaRicevutaDaRicerca = function(index) {
  const r = risultatiRicevuta[index];

  if (!r) {
    alert("Prenotazione non trovata.");
    return;
  }

  stampaRicevutaRecordDiretta(normalizzaRecordRicevutaCompleto(r));
};

// Sovrascrive renderRicevuta per usare Etichette e Note corrette.
renderRicevuta = function(r) {
  const rec = normalizzaRecordRicevutaCompleto(r);
  document.getElementById("statusReceipt").value = "Ricevuta selezionata: " + (rec.ID_PRENOTAZIONE || "");
  document.getElementById("ricevutaBody").innerHTML = htmlRicevutaDaRecordCompleto(rec);
};


/* =========================================================
   PATCH NON PRENOTATI + RICEVUTA ETICHETTE/NOTE ROBUSTA
   ========================================================= */

let risultatiNonPrenotati = [];

function getRecValue(rec, keys) {
  for (const k of keys) {
    if (rec && rec[k] !== undefined && rec[k] !== null && String(rec[k]).trim() !== "") {
      return String(rec[k]).trim();
    }
  }
  return "";
}

function normalizzaRecordCompleto(rec) {
  const r = Object.assign({}, rec || {});

  r.DATA_PRENOTAZIONE = getRecValue(r, [
    "DATA_PRENOTAZIONE",
    "DATA_ORA_SALVATAGGIO",
    "DATA",
    "DATA_PREN"
  ]) || "-";

  r.ETICHETTE = getRecValue(r, [
    "ETICHETTE",
    "ETICHETTA",
    "ETICHETE",
    "ETIC",
    "ETIC.",
    "LIBRI_ETICHETTE"
  ]) || "-";

  r.NOTE_NUOVO_ANNO = getRecValue(r, [
    "NOTE_NUOVO_ANNO",
    "NOTE",
    "NOTA",
    "NOTE_PRENOTAZIONE",
    "NOTE_LIBRI",
    "NOTE_RICEVUTA",
    "NOTE_LOG"
  ]) || "-";

  return r;
}

htmlRicevutaDaRecord = function(r) {
  const rec = normalizzaRecordCompleto(r);

  const alunno = valoreRicevuta((rec.COGNOME_ALUNNO || "") + " " + (rec.NOME_ALUNNO || ""));
  const genitore = valoreRicevuta((rec.COGNOME_GENITORE || "") + " " + (rec.NOME_GENITORE || ""));
  const comune = valoreRicevuta(rec.COMUNE_RESIDENZA || rec.COMUNE_FUORI_PROVINCIA);
  const dataPrenotazione = valoreRicevuta(rec.DATA_PRENOTAZIONE);

  return `
    <p><strong>ID prenotazione:</strong> ${esc(rec.ID_PRENOTAZIONE || "Non ancora salvata")}</p>
    <p><strong>Data prenotazione:</strong> ${esc(dataPrenotazione)}</p>
    <hr>
    <p><strong>Alunno:</strong> ${esc(alunno)}</p>
    <p><strong>ID alunno:</strong> ${esc(valoreRicevuta(rec.ID_ALUNNO))}</p>
    <p><strong>Codice fiscale alunno:</strong> ${esc(valoreRicevuta(rec.CODICE_FISCALE_ALUNNO))}</p>
    <p><strong>Comune residenza:</strong> ${esc(comune)}</p>
    <p><strong>Istituto:</strong> ${esc(valoreRicevuta(rec.ISTITUTO_NOME))} - ${esc(valoreRicevuta(rec.ISTITUTO_CITTA))}</p>
    <hr>
    <p><strong>Genitore:</strong> ${esc(genitore)}</p>
    <p><strong>Codice fiscale genitore:</strong> ${esc(valoreRicevuta(rec.COD_FISC_GENITORE))}</p>
    <p><strong>Cellulare / WhatsApp:</strong> ${esc(valoreRicevuta(rec.CELLULARE_GENITORE))}</p>
    <hr>
    <p><strong>Nuova classe:</strong> ${esc(valoreRicevuta(rec.NUOVA_CLASSE))}</p>
    <p><strong>Nuova sezione:</strong> ${esc(valoreRicevuta(rec.NUOVA_SEZIONE))}</p>
    <p><strong>Religione:</strong> ${esc(valoreRicevuta(rec.RELIGIONE))}</p>
    <p><strong>Foderati:</strong> ${esc(valoreRicevuta(rec.FODERATI))}</p>
    <p><strong>Libro vacanze:</strong> ${esc(valoreRicevuta(rec.LIBRO_VACANZE))}</p>
    <p><strong>Etichette:</strong> ${esc(valoreRicevuta(rec.ETICHETTE))}</p>
    <p><strong>Note:</strong> ${esc(valoreRicevuta(rec.NOTE_NUOVO_ANNO))}</p>
    <br><br>
    <p>Firma operatore __________________________</p>
    <p>Firma genitore ___________________________</p>
  `;
};

stampaRicevutaDaRicerca = function(index) {
  const r = risultatiRicevuta[index];

  if (!r) {
    alert("Prenotazione non trovata.");
    return;
  }

  stampaRicevutaRecordDiretta(normalizzaRecordCompleto(r));
};

renderRicevuta = function(r) {
  const rec = normalizzaRecordCompleto(r);
  document.getElementById("statusReceipt").value = "Ricevuta selezionata: " + (rec.ID_PRENOTAZIONE || "");
  document.getElementById("ricevutaBody").innerHTML = htmlRicevutaDaRecord(rec);
};

function assicuraBoxNonPrenotati() {
  if (document.getElementById("nonPrenotatiBox")) {
    return;
  }

  const screen = document.getElementById("screenRicevuta");
  const firstCard = screen ? screen.querySelector(".card") : null;

  if (!firstCard) {
    return;
  }

  const actions = document.createElement("div");
  actions.className = "actions";
  actions.innerHTML = `
    <button type="button" class="orange" onclick="caricaNonPrenotati()">Vecchi alunni non prenotati</button>
  `;

  const box = document.createElement("div");
  box.id = "nonPrenotatiBox";
  box.className = "table-wrap hidden";
  box.style.marginTop = "12px";

  firstCard.appendChild(actions);
  firstCard.appendChild(box);
}

async function caricaNonPrenotati() {
  assicuraBoxNonPrenotati();

  const box = document.getElementById("nonPrenotatiBox");
  box.classList.remove("hidden");
  box.innerHTML = '<div style="padding:12px;">Controllo vecchio archivio e nuove prenotazioni...</div>';

  try {
    const res = await api("nonPrenotati", {});

    if (!Array.isArray(res)) {
      throw new Error(res && res.message ? res.message : "Risposta non valida.");
    }

    risultatiNonPrenotati = res;

    if (!res.length) {
      box.innerHTML = '<div style="padding:12px;color:#166534;font-weight:800;">Tutti gli alunni del vecchio archivio risultano prenotati.</div>';
      return;
    }

    let t = '<table><thead><tr>';
    t += '<th>ID</th>';
    t += '<th>Alunno</th>';
    t += '<th>Genitore</th>';
    t += '<th>Telefono</th>';
    t += '<th>CF alunno</th>';
    t += '<th>Classe vecchia</th>';
    t += '<th>Azioni</th>';
    t += '</tr></thead><tbody>';

    res.forEach((r, i) => {
      const alunno = ((r.COGNOME_ALUNNO || "") + " " + (r.NOME_ALUNNO || "")).trim();
      const genitore = ((r.COGNOME_GENITORE || "") + " " + (r.NOME_GENITORE || "")).trim();
      const classe = ((r.CLASSE_VECCHIA || "") + " " + (r.SEZIONE_VECCHIA || "")).trim();

      t += '<tr>';
      t += `<td>${esc(r.ID_ALUNNO || "")}</td>`;
      t += `<td>${esc(alunno)}</td>`;
      t += `<td>${esc(genitore)}</td>`;
      t += `<td>${esc(r.CELLULARE_GENITORE || "")}</td>`;
      t += `<td>${esc(r.CODICE_FISCALE_ALUNNO || "")}</td>`;
      t += `<td>${esc(classe)}</td>`;
      t += '<td>';
      t += '<div style="display:flex;gap:6px;flex-wrap:wrap;">';
      t += `<button type="button" onclick="caricaNonPrenotatoInScheda(${i})">Prenota</button>`;
      t += `<button type="button" class="green" onclick="whatsAppNonPrenotato(${i})">WhatsApp</button>`;
      t += '</div>';
      t += '</td>';
      t += '</tr>';
    });

    t += '</tbody></table>';
    box.innerHTML = t;
  } catch (err) {
    box.innerHTML = '<div style="padding:12px;color:#b91c1c;">Errore: ' + esc(err.message) + '</div>';
  }
}

function caricaNonPrenotatoInScheda(index) {
  const r = risultatiNonPrenotati[index];

  if (!r) {
    return;
  }

  ID_PRENOTAZIONE_CORRENTE = "";
  CAMPI.forEach(campo => setField(campo, r[campo] || ""));

  setField("DATA_PRENOTAZIONE", today());
  aggiornaSezioni();

  document.getElementById("modeBadge").textContent = "vecchio alunno non ancora prenotato";
  document.getElementById("quickStatus").value = "Da prenotare: " + ((r.COGNOME_ALUNNO || "") + " " + (r.NOME_ALUNNO || "")).trim();

  mostraSchermata("prenotazione");
}

function whatsAppNonPrenotato(index) {
  const r = risultatiNonPrenotati[index];

  if (!r) {
    return;
  }

  let telefono = String(r.CELLULARE_GENITORE || "").replace(/\D/g, "");

  if (!telefono) {
    alert("Numero WhatsApp mancante per questo alunno.");
    return;
  }

  if (telefono.startsWith("0")) {
    telefono = "39" + telefono.substring(1);
  }

  if (!telefono.startsWith("39")) {
    telefono = "39" + telefono;
  }

  const alunno = ((r.COGNOME_ALUNNO || "") + " " + (r.NOME_ALUNNO || "")).trim();

  const messaggio =
    "Buongiorno, risulta ancora da completare la prenotazione dei libri scolastici 2026/27 per " +
    alunno +
    ". Potete contattarci o passare in negozio per confermare la prenotazione. Grazie.";

  window.open("https://wa.me/" + telefono + "?text=" + encodeURIComponent(messaggio), "_blank");
}

document.addEventListener("DOMContentLoaded", assicuraBoxNonPrenotati);


/* =========================================================
   PATCH CONTROLLO DOPPIA PRENOTAZIONE
   - Prima di salvare controlla se l'alunno è già presente
     nel foglio PRENOTAZIONI_2026_27
   - Blocca la nuova prenotazione se trova un doppione
   - Permette aggiornamento se stai modificando la stessa prenotazione
   ========================================================= */

async function controllaDoppiaPrenotazionePrimaDiSalvare() {
  const idAlunno = getField("ID_ALUNNO");
  const cfAlunno = getField("CODICE_FISCALE_ALUNNO");
  const cognome = getField("COGNOME_ALUNNO");
  const nome = getField("NOME_ALUNNO");
  const idPrenotazioneCorrente = String(ID_PRENOTAZIONE_CORRENTE || "").trim();

  const query = cfAlunno || idAlunno || ((cognome + " " + nome).trim());

  if (!query) {
    return true;
  }

  try {
    const risultati = await api("cercaNuove", { q: query });

    if (!Array.isArray(risultati) || risultati.length === 0) {
      return true;
    }

    const cfNorm = String(cfAlunno || "").trim().toUpperCase();
    const idNorm = String(idAlunno || "").trim().toUpperCase();
    const nomeNorm = String((cognome + " " + nome) || "").trim().toUpperCase();

    const doppione = risultati.find(r => {
      const idPrenTrovata = String(r.ID_PRENOTAZIONE || "").trim();

      // Se sto modificando la stessa prenotazione, non è un doppione.
      if (idPrenotazioneCorrente && idPrenTrovata === idPrenotazioneCorrente) {
        return false;
      }

      const cfTrovato = String(r.CODICE_FISCALE_ALUNNO || "").trim().toUpperCase();
      const idTrovato = String(r.ID_ALUNNO || "").trim().toUpperCase();
      const nomeTrovato = String(((r.COGNOME_ALUNNO || "") + " " + (r.NOME_ALUNNO || ""))).trim().toUpperCase();

      if (cfNorm && cfTrovato && cfNorm === cfTrovato) {
        return true;
      }

      if (idNorm && idTrovato && idNorm === idTrovato) {
        return true;
      }

      if (nomeNorm && nomeTrovato && nomeNorm === nomeTrovato) {
        return true;
      }

      return false;
    });

    if (doppione) {
      const alunno = ((doppione.COGNOME_ALUNNO || "") + " " + (doppione.NOME_ALUNNO || "")).trim();
      const classe = ((doppione.NUOVA_CLASSE || "") + " " + (doppione.NUOVA_SEZIONE || "")).trim();
      const idPren = doppione.ID_PRENOTAZIONE || "-";

      alert(
        "ATTENZIONE: questo alunno risulta già prenotato.\\n\\n" +
        "Alunno: " + (alunno || "-") + "\\n" +
        "Classe/sezione: " + (classe || "-") + "\\n" +
        "ID prenotazione: " + idPren + "\\n\\n" +
        "Per modificare la prenotazione esistente vai su 'Ricerca prenotazioni' e usa il pulsante Modifica."
      );

      const msg = document.getElementById("msgSalva");
      if (msg) {
        setMsg(
          "msgSalva",
          "Salvataggio bloccato: alunno già presente in una prenotazione. Usa Ricerca prenotazioni → Modifica.",
          "err"
        );
      }

      return false;
    }

    return true;
  } catch (err) {
    const procedi = confirm(
      "Non riesco a controllare se esiste già una prenotazione per questo alunno.\\n\\n" +
      "Errore: " + (err && err.message ? err.message : err) + "\\n\\n" +
      "Vuoi salvare comunque?"
    );

    return procedi;
  }
}

// Salvo la funzione originale e la sovrascrivo con il controllo doppioni.
const salvaPrenotazioneOriginaleConDoppioni = salvaPrenotazione;

salvaPrenotazione = async function() {
  const okDoppione = await controllaDoppiaPrenotazionePrimaDiSalvare();

  if (!okDoppione) {
    return;
  }

  return salvaPrenotazioneOriginaleConDoppioni();
};


/* =========================================================
   PATCH MIGLIORIE OPERATIVE v9
   - Riepilogo prenotazione leggibile
   - Evidenzia campi obbligatori mancanti
   - Pulsante scarica CSV completo anno 2026/27
   - Conferma riepilogativa prima del salvataggio
   ========================================================= */

function evidenziaCampo(id) {
  const el = document.getElementById(id);
  if (!el) return;

  el.style.border = "2px solid #b91c1c";
  el.style.boxShadow = "0 0 0 4px rgba(185,28,28,.12)";
  setTimeout(() => {
    el.style.border = "";
    el.style.boxShadow = "";
  }, 2800);
}

function focusCampo(id) {
  const el = document.getElementById(id);
  if (el) {
    el.focus();
    evidenziaCampo(id);
  }
}

function getVal(id) {
  return getField(id) || "-";
}

function riepilogoPrenotazioneTesto() {
  return [
    "RIEPILOGO PRENOTAZIONE",
    "",
    "Alunno: " + getVal("COGNOME_ALUNNO") + " " + getVal("NOME_ALUNNO"),
    "CF alunno: " + getVal("CODICE_FISCALE_ALUNNO"),
    "Genitore: " + getVal("COGNOME_GENITORE") + " " + getVal("NOME_GENITORE"),
    "CF genitore: " + getVal("COD_FISC_GENITORE"),
    "Telefono: " + getVal("CELLULARE_GENITORE"),
    "Comune: " + (getField("COMUNE_RESIDENZA") || getField("COMUNE_FUORI_PROVINCIA") || "-"),
    "Istituto: " + getVal("ISTITUTO_NOME") + " - " + getVal("ISTITUTO_CITTA"),
    "",
    "Nuova classe: " + getVal("NUOVA_CLASSE"),
    "Nuova sezione: " + getVal("NUOVA_SEZIONE"),
    "Religione: " + getVal("RELIGIONE"),
    "Foderati: " + getVal("FODERATI"),
    "Libro vacanze: " + getVal("LIBRO_VACANZE"),
    "Etichette: " + getVal("ETICHETTE"),
    "Data prenotazione: " + getVal("DATA_PRENOTAZIONE"),
    "Note: " + getVal("NOTE_NUOVO_ANNO")
  ].join("\n");
}

function mostraRiepilogoPrenotazione() {
  alert(riepilogoPrenotazioneTesto());
}

// Rafforza validaLocale: evidenzia visivamente il campo mancante.
const validaLocaleOriginale_v9 = validaLocale;
validaLocale = function(d) {
  const obbligatori = [
    ["COGNOME_ALUNNO", "Cognome alunno obbligatorio"],
    ["NOME_ALUNNO", "Nome alunno obbligatorio"],
    ["CODICE_FISCALE_ALUNNO", "Codice fiscale del figlio/alunno obbligatorio"],
    ["COD_FISC_GENITORE", "Codice fiscale del genitore obbligatorio"],
    ["NUOVA_CLASSE", "Nuova classe obbligatoria"],
    ["NUOVA_SEZIONE", "Nuova sezione obbligatoria"],
    ["RELIGIONE", "Religione obbligatoria"],
    ["FODERATI", "Foderati obbligatorio"],
    ["LIBRO_VACANZE", "Libro vacanze obbligatorio"]
  ];

  for (const [id, msg] of obbligatori) {
    if (!d[id]) {
      alert(msg);
      focusCampo(id);
      return false;
    }
  }

  if (!d.COMUNE_RESIDENZA && !d.COMUNE_FUORI_PROVINCIA) {
    alert("Comune di residenza del figlio obbligatorio. Se fuori provincia, usa Comune fuori provincia.");
    focusCampo("COMUNE_RESIDENZA");
    return false;
  }

  return true;
};

// Conferma riepilogativa prima del salvataggio.
const salvaPrenotazioneConDoppioniOriginale_v9 = salvaPrenotazione;
salvaPrenotazione = async function() {
  const d = raccogliDati();

  if (!validaLocale(d)) {
    return;
  }

  const conferma = confirm(
    riepilogoPrenotazioneTesto() +
    "\n\nConfermi il salvataggio di questa prenotazione?"
  );

  if (!conferma) {
    return;
  }

  return salvaPrenotazioneConDoppioniOriginale_v9();
};

function csvEscape(value) {
  const s = String(value == null ? "" : value);
  return '"' + s.replace(/"/g, '""') + '"';
}

function downloadTextFile(filename, content, mime) {
  const blob = new Blob([content], { type: mime || "text/plain;charset=utf-8" });
  const url = URL.createObjectURL(blob);
  const a = document.createElement("a");

  a.href = url;
  a.download = filename;
  document.body.appendChild(a);
  a.click();

  setTimeout(() => {
    document.body.removeChild(a);
    URL.revokeObjectURL(url);
  }, 200);
}

async function scaricaCsvPrenotazioniAnno() {
  try {
    const res = await api("tuttePrenotazioni", {});

    if (!res || !res.ok) {
      throw new Error(res && res.message ? res.message : "Errore esportazione CSV.");
    }

    const rows = Array.isArray(res.rows) ? res.rows : [];
    const headers = Array.isArray(res.headers) ? res.headers : [];

    if (!rows.length) {
      alert("Non ci sono prenotazioni da esportare.");
      return;
    }

    const csv = [
      headers.map(csvEscape).join(";"),
      ...rows.map(row => headers.map(h => csvEscape(row[h] || "")).join(";"))
    ].join("\n");

    const oggi = new Date().toISOString().slice(0, 10);
    downloadTextFile("prenotazioni_libri_2026_27_" + oggi + ".csv", csv, "text/csv;charset=utf-8");

  } catch (err) {
    alert("Errore download CSV: " + (err && err.message ? err.message : err));
  }
}

function aggiungiPulsantiOperativiV9() {
  const cards = document.querySelectorAll("#screenPrenotazione .card");
  const target = cards[cards.length - 1];

  if (!target || document.getElementById("btnScaricaCsvAnno")) {
    return;
  }

  const actions = document.createElement("div");
  actions.className = "actions";
  actions.innerHTML = `
    <button id="btnScaricaCsvAnno" type="button" class="green" onclick="scaricaCsvPrenotazioniAnno()">Scarica CSV prenotazioni 2026/27</button>
    <button id="btnRiepilogoScheda" type="button" class="secondary" onclick="mostraRiepilogoPrenotazione()">Mostra riepilogo scheda</button>
  `;

  const note = document.createElement("div");
  note.className = "small";
  note.style.marginTop = "8px";
  note.textContent = "Il CSV esporta tutte le prenotazioni salvate nel foglio PRENOTAZIONI_2026_27.";

  target.appendChild(actions);
  target.appendChild(note);
}

document.addEventListener("DOMContentLoaded", aggiungiPulsantiOperativiV9);


/* =========================================================
   PATCH RIEPILOGO GRANDE E LEGGIBILE
   ========================================================= */

let risolviRiepilogoGrande = null;

function rigaRiepilogoGrande(label, value) {
  return `
    <div class="riepilogoRow">
      <div class="riepilogoLabel">${esc(label)}</div>
      <div class="riepilogoValue">${esc(value || "-")}</div>
    </div>
  `;
}

function creaHtmlRiepilogoGrande() {
  const comune = getField("COMUNE_RESIDENZA") || getField("COMUNE_FUORI_PROVINCIA") || "-";

  return `
    <div class="riepilogoGrid">
      <div class="riepilogoSection">
        <h3>Alunno</h3>
        ${rigaRiepilogoGrande("Cognome", getField("COGNOME_ALUNNO"))}
        ${rigaRiepilogoGrande("Nome", getField("NOME_ALUNNO"))}
        ${rigaRiepilogoGrande("ID alunno", getField("ID_ALUNNO"))}
        ${rigaRiepilogoGrande("Codice fiscale", getField("CODICE_FISCALE_ALUNNO"))}
        ${rigaRiepilogoGrande("Comune", comune)}
      </div>

      <div class="riepilogoSection">
        <h3>Genitore</h3>
        ${rigaRiepilogoGrande("Cognome", getField("COGNOME_GENITORE"))}
        ${rigaRiepilogoGrande("Nome", getField("NOME_GENITORE"))}
        ${rigaRiepilogoGrande("Codice fiscale", getField("COD_FISC_GENITORE"))}
        ${rigaRiepilogoGrande("Cellulare", getField("CELLULARE_GENITORE"))}
        ${rigaRiepilogoGrande("WhatsApp", getField("WHATSAPP_NOTIFICA"))}
      </div>

      <div class="riepilogoSection">
        <h3>Scuola</h3>
        ${rigaRiepilogoGrande("Istituto", getField("ISTITUTO_NOME"))}
        ${rigaRiepilogoGrande("Città istituto", getField("ISTITUTO_CITTA"))}
        ${rigaRiepilogoGrande("Classe vecchia", getField("CLASSE_VECCHIA"))}
        ${rigaRiepilogoGrande("Sezione vecchia", getField("SEZIONE_VECCHIA"))}
      </div>

      <div class="riepilogoSection">
        <h3>Nuova prenotazione</h3>
        ${rigaRiepilogoGrande("Nuova classe", getField("NUOVA_CLASSE"))}
        ${rigaRiepilogoGrande("Nuova sezione", getField("NUOVA_SEZIONE"))}
        ${rigaRiepilogoGrande("Religione", getField("RELIGIONE"))}
        ${rigaRiepilogoGrande("Foderati", getField("FODERATI"))}
        ${rigaRiepilogoGrande("Libro vacanze", getField("LIBRO_VACANZE"))}
        ${rigaRiepilogoGrande("Etichette", getField("ETICHETTE"))}
        ${rigaRiepilogoGrande("Data prenotazione", getField("DATA_PRENOTAZIONE"))}
        ${rigaRiepilogoGrande("Stato", getField("STATO_PRENOTAZIONE"))}
      </div>

      <div class="riepilogoSection full">
        <h3>Note</h3>
        ${rigaRiepilogoGrande("Note nuovo anno", getField("NOTE_NUOVO_ANNO"))}
      </div>
    </div>
  `;
}

function apriRiepilogoGrande() {
  return new Promise(resolve => {
    risolviRiepilogoGrande = resolve;

    const overlay = document.getElementById("riepilogoOverlay");
    const content = document.getElementById("riepilogoContent");

    content.innerHTML = creaHtmlRiepilogoGrande();
    overlay.classList.add("show");
  });
}

function chiudiRiepilogoGrande(esito) {
  const overlay = document.getElementById("riepilogoOverlay");
  overlay.classList.remove("show");

  if (risolviRiepilogoGrande) {
    risolviRiepilogoGrande(!!esito);
    risolviRiepilogoGrande = null;
  }
}

function mostraRiepilogoPrenotazione() {
  const overlay = document.getElementById("riepilogoOverlay");
  const content = document.getElementById("riepilogoContent");

  content.innerHTML = creaHtmlRiepilogoGrande();
  overlay.classList.add("show");

  // In modalità solo lettura cambio il bottone conferma in "Chiudi" temporaneamente.
  const actions = document.getElementById("riepilogoActions");
  actions.innerHTML = `
    <button type="button" class="green" onclick="chiudiRiepilogoGrande(false)">Chiudi</button>
  `;
}

// Sovrascrive il salvataggio con riepilogo grande al posto del confirm piccolo.
const salvaPrenotazioneConRiepilogoPiccoloOriginale = salvaPrenotazione;

salvaPrenotazione = async function() {
  const d = raccogliDati();

  if (!validaLocale(d)) {
    return;
  }

  const actions = document.getElementById("riepilogoActions");
  actions.innerHTML = `
    <button type="button" class="secondary" onclick="chiudiRiepilogoGrande(false)">Annulla</button>
    <button type="button" class="green" onclick="chiudiRiepilogoGrande(true)">Conferma salvataggio</button>
  `;

  const conferma = await apriRiepilogoGrande();

  if (!conferma) {
    return;
  }

  return salvaPrenotazioneConRiepilogoPiccoloOriginale();
};

// Chiude cliccando fuori dal riquadro.
document.addEventListener("DOMContentLoaded", function() {
  const overlay = document.getElementById("riepilogoOverlay");
  const modal = document.getElementById("riepilogoModal");

  if (overlay && modal) {
    overlay.addEventListener("click", function(e) {
      if (e.target === overlay) {
        chiudiRiepilogoGrande(false);
      }
    });
  }
});

</script>

<div id="riepilogoOverlay" class="no-print">
  <div id="riepilogoModal">
    <div id="riepilogoHeader">
      <h2>Riepilogo prenotazione</h2>
      <p>Controlla bene i dati prima di salvare.</p>
    </div>
    <div id="riepilogoContent"></div>
    <div id="riepilogoActions">
      <button type="button" class="secondary" onclick="chiudiRiepilogoGrande(false)">Annulla</button>
      <button type="button" class="green" onclick="chiudiRiepilogoGrande(true)">Conferma salvataggio</button>
    </div>
  </div>
</div>

</body>
</html>
