<!doctype html>
<html lang="de">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>SoHacks Web</title>
<style>
:root{box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px);
--bg:#0E1411;--surface:#151B18;--raised:#1A211D;--line:#242C28;--text:#EAF0ED;--muted:#7B8983;--accent:#35D69A;--accent-soft:#1E3A30;--on-accent:#0E1411;--warn:#F2A93B;--danger:#FF8A80;color-scheme:dark}
@media (prefers-color-scheme:light){:root:not([data-theme="dark"]){--bg:#F3F7F5;--surface:#FFFFFF;--raised:#E9F0ED;--line:#D5DEDA;--text:#13201A;--muted:#55645D;--accent:#12805A;--accent-soft:#D3EFE3;--on-accent:#FFFFFF;--warn:#9A6200;--danger:#B3261E;color-scheme:light}}
html{scroll-padding-top:env(safe-area-inset-top,0px)}
*{box-sizing:border-box}
body{margin:0;background:var(--bg);color:var(--text);font:16px/1.4 ui-rounded,"SF Pro Rounded",system-ui,-apple-system,"Segoe UI",sans-serif}
main{max-width:520px;margin:0 auto;padding:14px 14px 40px;display:grid;gap:12px}
h1{margin:0;font-size:22px;letter-spacing:.2px}h2{margin:0 0 10px;font-size:15px;font-weight:600;color:var(--muted)}
p{margin:0}.muted{color:var(--muted);font-size:13px}
.top{display:flex;justify-content:space-between;align-items:center;gap:10px}
.chip{padding:6px 12px;border-radius:99px;background:var(--raised);border:1px solid var(--line);font-size:13px}
.chip.on{background:var(--accent-soft);color:var(--accent);border-color:var(--accent)}
.card{background:var(--surface);border:1px solid var(--line);border-radius:18px;padding:14px}
.speed{display:flex;align-items:baseline;gap:8px}.speed b{font-size:64px;line-height:1;font-variant-numeric:tabular-nums;font-weight:700}.speed span{color:var(--muted)}
.meta{display:flex;gap:14px;color:var(--muted);font-size:13px;margin:6px 0 10px}
.bar{height:8px;background:var(--raised);border-radius:9px;overflow:hidden}.bar i{display:block;height:100%;width:0;background:var(--accent);transition:width .3s}
.tiles{display:grid;grid-template-columns:repeat(3,1fr);gap:8px;margin:12px 0 8px}
.tile{background:var(--raised);border-radius:12px;padding:8px 10px}.tile small{display:block;color:var(--muted);font-size:12px}.tile b{font-size:17px;font-variant-numeric:tabular-nums}
.row{display:grid;gap:8px}.r2{grid-template-columns:1fr 1fr}.r4{grid-template-columns:repeat(4,1fr)}.r5{grid-template-columns:repeat(5,1fr)}
button,select,input[type=text],input[type=number],input[type=color]{font:inherit;color:var(--text)}
button{border:1px solid var(--line);background:var(--raised);border-radius:12px;padding:11px 6px;cursor:pointer;min-height:44px}
button.pri{background:var(--accent);color:var(--on-accent);border-color:var(--accent);font-weight:600}
button:disabled{opacity:.4;cursor:default}button:focus-visible,input:focus-visible,select:focus-visible{outline:2px solid var(--accent);outline-offset:2px}
button.bub{border-radius:99px;min-width:64px;min-height:64px;color:#0E1411;font-weight:600;border:0}
select,input[type=text],input[type=number]{width:100%;background:var(--raised);border:1px solid var(--line);border-radius:12px;padding:11px}
input[type=range]{width:100%;accent-color:var(--accent)}
.sl{display:flex;align-items:center;gap:12px;margin-bottom:10px}.sl b{min-width:70px;text-align:right}
label.sw{display:flex;justify-content:space-between;align-items:center;gap:10px}
.hide{display:none!important}
pre{margin:8px 0 0;padding:10px;background:var(--raised);border-radius:12px;font-size:12px;white-space:pre-wrap;word-break:break-all;color:var(--muted)}
.chips{display:flex;flex-wrap:wrap;gap:6px;margin:8px 0}.chips button{min-height:34px;padding:4px 10px;border-radius:99px}
#toast{position:fixed;left:50%;bottom:calc(20px + env(safe-area-inset-bottom,0px));transform:translateX(-50%);background:var(--text);color:var(--bg);padding:10px 16px;border-radius:12px;max-width:88vw;font-size:14px;opacity:0;pointer-events:none;transition:opacity .2s;z-index:30}
#toast.show{opacity:1}
#gate{position:fixed;inset:0;background:var(--bg);z-index:20;overflow:auto;padding:calc(20px + env(safe-area-inset-top,0px)) 18px 30px}
#gate>div{max-width:480px;margin:0 auto;display:grid;gap:14px}
.warn{border-color:var(--warn)}
@media (prefers-reduced-motion:reduce){.bar i,#toast{transition:none}}
</style>
</head>
<body>
<main>
 <header class="top"><div><h1>SoHacks</h1><p class="muted">Web-Version für SoFlow-Scooter</p></div><span id="status" class="chip">Nicht verbunden</span></header>
 <p id="nobt" class="card warn hide">Dieser Browser unterstützt kein Web Bluetooth. Öffne die Seite in Bluefy (iOS) oder Chrome/Edge.</p>

 <section class="card">
  <div class="speed"><b id="spd">00.0</b><span>km/h</span></div>
  <div class="meta"><span id="light">Licht –</span><span id="watt"></span></div>
  <div class="bar"><i id="batbar"></i></div>
  <div class="tiles" id="tiles"></div>
  <p id="details" class="muted">Keine Telemetrie</p>
 </section>

 <section class="card"><h2>Modell</h2><select id="model" aria-label="Modell"></select><p id="mdesc" class="muted" style="margin-top:8px"></p></section>

 <section class="card"><h2>Fahrmodus</h2>
  <div class="row r4"><button id="bEco">Eco</button><button id="bNormal">Normal</button><button id="bSport">Sport</button><button id="bDev">Dev</button></div></section>

 <section class="card"><h2>Geschwindigkeit</h2>
  <div class="sl"><input type="range" id="sl" aria-label="Geschwindigkeit" min="8" max="30" step="1" value="20"><b id="slv">20 km/h</b></div>
  <div class="row r5" id="hot"></div></section>

 <section class="card"><div class="row r2"><button id="bLock">Sperren</button><button id="bUnlock">Entsperren</button></div></section>

 <section class="card"><div class="row r2"><button id="bConn" class="pri">Verbinden</button><button id="bDisc">Trennen</button></div></section>

 <section class="card"><h2>Schnelloptionen</h2>
  <div class="row r4" id="bubs"></div>
  <div class="row r2" style="margin-top:10px"><button id="bNewBub">Neue Bubble</button><button id="bEditBub">Bearbeiten</button></div>
  <div id="ed" class="hide" style="margin-top:12px;display:grid;gap:8px">
   <input type="text" id="edName" maxlength="10" placeholder="Name (max. 10 Zeichen)">
   <input type="color" id="edColor" value="#35d69a" aria-label="Farbe" style="width:100%;height:44px;border-radius:12px;border:1px solid var(--line);background:var(--raised)">
   <div class="row r2"><select id="edType" aria-label="Aktion"></select><input type="number" id="edVal" placeholder="Wert"><select id="edExtra" class="hide" aria-label="Zusatzkommando"></select></div>
   <button id="edAdd">Aktion hinzufügen</button>
   <div class="chips" id="edList"></div>
   <div class="row r2"><button id="edSave" class="pri">Speichern</button><button id="edDel">Löschen</button></div>
   <button id="edCancel">Abbrechen</button>
  </div></section>

 <section class="card">
  <label class="sw"><span>Advanced-Optionen</span><input type="checkbox" id="swAdv"></label>
  <div id="adv" class="hide" style="margin-top:12px;display:grid;gap:10px">
   <select id="modeSel" aria-label="Advanced-Mode"></select>
   <label class="sw"><span>Mehr Speed (1–65 km/h)</span><input type="checkbox" id="cbMore"></label>
   <label class="sw"><span>Display anlassen</span><input type="checkbox" id="cbWake"></label>
   <div id="extras" class="row r2"></div>
   <div class="row" style="grid-template-columns:1fr auto"><input type="text" id="hex" placeholder="Hex, z. B. D706A30001AA" autocapitalize="characters" autocomplete="off" spellcheck="false"><button id="bHex">Senden</button></div>
   <div><p class="muted">Letzte Antwort (entschlüsselt)</p><pre id="out">–</pre></div>
  </div></section>
</main>
<div id="toast" role="status"></div>

<div id="gate"><div>
 <h1>Risiko-Hinweis</h1>
 <p class="card warn">Die Nutzung dieser App kann das Verhalten deines Scooters verändern. Tuning und veränderte Geschwindigkeiten können im Straßenverkehr illegal sein und zu Bußgeldern, Versicherungsverlust oder Gefährdungen führen.</p>
 <p class="card">Diese App wird ohne Gewähr bereitgestellt. Der Entwickler übernimmt keine Haftung für Schäden, Rechtsfolgen oder Fehlfunktionen. Nutze die App ausschließlich auf eigene Verantwortung und nur dort, wo es rechtlich zulässig ist.</p>
 <p class="muted">Web-Port der Android-App SoHacks (GPL-3.0). Getestet wurden laut Projekt nur SO1 und SO4 Pro Gen 2.</p>
 <button id="gOk" class="pri">Ich akzeptiere das Risiko</button><button id="gNo">Abbrechen</button>
</div></div>

<script src="https://cdnjs.cloudflare.com/ajax/libs/crypto-js/4.2.0/crypto-js.min.js"></script>
<script>
"use strict";
/* ---------- Hilfsfunktionen (HexCodec, D7-Generator) ---------- */
const $=s=>document.querySelector(s);
const hex2=n=>(n&255).toString(16).toUpperCase().padStart(2,"0");
const norm=h=>h.replace(/\s/g,"").toUpperCase();
const toBytes=h=>{const c=norm(h);if(c.length%2)throw new Error("Hex muss eine gerade Länge haben");if(/[^0-9A-F]/.test(c))throw new Error("Hex enthält ungültige Zeichen");return Uint8Array.from(c.match(/../g)||[],x=>parseInt(x,16))};
const toHex=b=>Array.from(b,hex2).join("");
const d7=(cmd,prefix,payload=[])=>{const len=5+payload.length;const sum=(len+cmd+prefix+payload.reduce((a,b)=>a+b,0))&255;return"D7"+hex2(len)+hex2(cmd)+hex2(prefix)+payload.map(hex2).join("")+hex2(sum)};
const sleep=ms=>new Promise(r=>setTimeout(r,ms));
const store={get(k,d){try{const v=localStorage.getItem(k);return v==null?d:JSON.parse(v)}catch(e){return d}},set(k,v){try{localStorage.setItem(k,JSON.stringify(v))}catch(e){}}};

/* ---------- Befehlskatalog (ScooterCommandCatalog) ---------- */
const fixed=h=>({fixed:h}),tok=h=>({fixed:h,tok:true}),dyn=(c,...p)=>({dyn:{c,p}});
const resolve=(s,rt)=>{if(s.fixed!=null)return s.tok?(rt.token?s.fixed.replace("<TOKEN>",rt.token):null):s.fixed;if(rt.secret==null)return null;return d7(s.dyn.c,rt.secret,s.dyn.p)};
const stat={},dynS={};
for(let s=1;s<=65;s++){const t=s*10;stat[s]=fixed(d7(0xA9,0,[(t>>8)&255,t&255]));dynS[s]=dyn(0xA9,(t>>8)&255,t&255)}
const F=fixed,startA0=fixed(d7(0xA0,0,[0,1])),startA6=fixed(d7(0xA6,0,[0,1]));
const gen2={eco:F("D706A30000A9"),normal:F("D706A30001AA"),sport:F("D706A30002AB"),dev:F("D706A30003AC"),lock:F("D706A00001A7"),unlock:F("D706A00000A6"),speeds:stat,startup:F("D706A60001AD")};
const cmds={
 s04Pro:{eco:F("D707A45A000005"),normal:F("D706A30001AA"),sport:F("D706A30002AB"),dev:F("D706A30003AC"),lock:F("D707A0000101A9"),unlock:F("D707A0000301AB"),speeds:stat},
 gen2,gen2NoStart:{...gen2,startup:null},
 s04:{eco:F("D707A0000100A8"),normal:F("D707A0000300AA"),sport:F("D707A0000500AC"),dev:F("D706A30003AC"),lock:F("D707A0000301AB"),unlock:F("D707A0000300AA"),speeds:stat},
 t51:{eco:F("D707A0000000A7"),normal:F("D707A0000200A9"),sport:F("D707A0000400AB"),dev:F("D706A30003AC"),lock:F("D707A0000201AA"),unlock:F("D707A0000200A9"),speeds:stat,startup:F("D707A60001AE")},
 dyn:{eco:dyn(0xA4,0,0),normal:dyn(0xA4,0,1),sport:dyn(0xA4,0,2),dev:dyn(0xA4,0,2),lock:dyn(0xA2,0,1),unlock:dyn(0xA2,0,0),speeds:dynS,startup:startA0},
 a0:{eco:dyn(0xA0,1,0),normal:dyn(0xA0,3,0),sport:dyn(0xA0,5,0),dev:dyn(0xA0,5,0),lock:dyn(0xA0,3,1),unlock:dyn(0xA0,3,0),speeds:dynS,startup:startA0},
 token:{lock:tok("050C0101<TOKEN>"),unlock:tok("050106303030303030<TOKEN>"),sessionToken:F("060101"),rtStart:tok("0546020101<TOKEN>"),rtStop:tok("0546020001<TOKEN>")}
};
cmds.a0air={...cmds.a0,startup:startA6};
const NORDIC={svc:"6e400001-b5a3-f393-e0a9-e50e24dcca9e",w:"6e400002-b5a3-f393-e0a9-e50e24dcca9e",n:"6e400003-b5a3-f393-e0a9-e50e24dcca9e"};
const aes52={...NORDIC,wkey:"30572F52364B3F473050415811632D2B"};
const two={...NORDIC,key:"20572F52364B3F473050415811632D2B"};
const so6p={svc:"60000001-0000-1000-8000-00805f9b34fb",w:"60000003-0000-1000-8000-00805f9b34fb",n:"60000002-0000-1000-8000-00805f9b34fb",key:"20572F52364B3F473050415811632D2B"};
const extra=[["lock_state","Lock-State lesen","050E0101"],["cycling_data","Cycling-Data lesen","05480101"],["light_state","Lichtstatus lesen","05450101"],["light_on","Licht an","05470101"],["light_off","Licht aus","05470100"],["speed_limit_read","Speed-Limit lesen","05490101"]].map(([id,label,h])=>({id,label,spec:tok(h+"<TOKEN>")}));
const M=(id,name,desc,c,o={})=>({id,name,desc,c,profile:NORDIC,family:"D7_SO4_V51_PLUS",maxAdv:0,extra:[],...o});
const MODELS=[
 M("s04_pro_gen2","SO4 Pro Gen 2","SO4 Pro Gen 2 unverschlüsseltes Nordic-UART-Profil.",cmds.gen2NoStart,{family:"SO4_PRO",maxAdv:254}),
 M("s04_pro_gen3","SO4 Pro Gen 3","SO4 Gen3 / SO4T-v5.2 Profil.",cmds.gen2,{profile:aes52,maxAdv:254}),
 M("s04_pro_legacy_test","SO4 Pro Legacy Test","Altes gemischtes SO4-Pro-Profil zum Vergleichen, falls dein Scooter nur darauf reagiert.",cmds.s04Pro,{family:"LEGACY_STATUS",maxAdv:254}),
 M("so4","SO4","SO4Tv1.0 D7-Profil mit Legacy-Telemetrie-Indizes.",cmds.s04,{family:"D7_SO4_V1",maxAdv:254}),
 M("so4_5_1","SO4 5.1","SO4T-v5.1-Profil mit Connection-Status-, Lock- und Speed-Kommandos.",cmds.t51,{maxAdv:254}),
 M("so4_5_2","SO4 5.2","SO4T-v5.2-Profil aus dem Command-Maker.",cmds.gen2,{profile:aes52,maxAdv:254}),
 M("somytier","SO myTier","myTier-Profil mit SO4T-v5.2-Kommandostruktur und Transport-AES-Hinweis.",cmds.gen2,{profile:aes52}),
 M("so1","SO1","D7-Profil mit Live-Secret aus Realtime-Daten.",cmds.dyn,{family:"DYNAMIC_D7"}),
 M("so1_a0_test","SO1 A0 Test","Alternatives SO1-Testprofil mit A0-basierten Fahr- und Lock-Kommandos.",cmds.a0,{family:"DYNAMIC_D7"}),
 M("so2_air","SO2 Air","D7 Profil",cmds.dyn,{family:"DYNAMIC_D7"}),
 M("so2_air_a0_test","SO2 Air A0 Test","Alternatives SO2-Air-Testprofil mit A0/A6-basierten Kommandos.",cmds.a0air,{family:"DYNAMIC_D7"}),
 M("so3","SO3","D7 Profil",cmds.dyn,{family:"DYNAMIC_D7",maxAdv:254}),
 M("so4ul","SO4 UL","Tokenbasiertes Zwei-Byte-Protokoll über Nordic UART.",cmds.token,{profile:two,family:"TWO_BYTE",extra}),
 M("so6","SO6","Tokenbasiertes Zwei-Byte-Protokoll mit SO6-Service-UUIDs.",cmds.token,{profile:so6p,family:"TWO_BYTE",extra})
];
MODELS.forEach(m=>{m.speeds=m.c.speeds||{};m.supported=Object.keys(m.speeds).map(Number).sort((a,b)=>a-b)});
const findModel=id=>MODELS.find(m=>m.id===id)||MODELS[0];

/* ---------- Telemetrie-Parser (ScooterTelemetryParser) ---------- */
const u16=(b,i)=>(b[i]<<8)|b[i+1];
const ver=v=>((v>>4)&15)+"."+(v&15);
const bits8=n=>n.toString(2).padStart(8,"0").slice(-8);
const find=(b,min,t)=>{if(b.length<min)return null;for(let i=0;i<=b.length-min;i++)if(t(i))return i;return null};
function pSo4(b,v51){
 const f=find(b,v51?20:19,i=>b[i+2]===0x1D&&(v51?b[i+1]>=0x15:b[i+1]===0x14));if(f==null)return null;
 const bits=bits8(b[f+4]),mi=v51?f+15:f+14,ti=v51?f+17:f+16,bi=v51?f+19:f+18;
 if(b.length<=bi)return null;
 const vs=i=>b[i]!=null?ver(b[i]):null;
 return{speedKmh:u16(b,f+5)/10,currentA:u16(b,f+9)/10,voltageV:u16(b,f+7)/10,batteryLevel:b[bi],mileageOfRideKm:u16(b,mi)/10,totalMileageKm:u16(b,ti),lockState:bits[0]==="1",speedMode:parseInt(bits.slice(4,7),2),protocolVersion:vs(f+12),displayVersion:v51?vs(f+13):null,cpuVersion:vs(v51?f+14:f+13)}}
function secretOf(b,f){if(b.length<=f+16)return null;const b3=b[f+3],mixed=(b[f+16]^b3)^(b[f+15]^b3);return((((((((mixed+0xCE)^0xB2)+0xA5)^0xCA)+(b3&15))^0x2B)+0x33)^0x1D)&0x7F}
function pDynRt(b){
 let f=find(b,20,i=>b[i]===0xD7&&b[i+2]===0x1D);if(f==null)f=find(b,18,i=>b[i+2]===0x1D);if(f==null)return null;
 const s=f+4;if(b.length<=s+15)return null;const bits=bits8(b[s]);
 return{speedKmh:u16(b,s+1)/10,currentA:u16(b,s+5)/10,voltageV:u16(b,s+3)/10,speedMode:parseInt(bits.slice(4,7),2),energy:u16(b,s+9)/10,speedInMiles:bits[3]==="1",dynamicSecret:secretOf(b,f)}}
function pDynStandby(b){
 let f=find(b,17,i=>b[i]===0xD7&&b[i+2]===0x2D);if(f==null)f=find(b,17,i=>b[i+2]===0x2D);if(f==null)return null;
 if(b.length<=f+16)return null;const fault=b[f+3],bat=b[f+11];
 return{fault,lockState:(fault&1)!==0,protocolVersion:ver(b[f+4]),displayVersion:ver(b[f+5]),cpuVersion:ver(b[f+5]),mileageOfRideKm:u16(b,f+6)/10,totalMileageKm:u16(b,f+8),averageCurrentA:b[f+10]/10,batteryLevel:bat>=90?100:bat,remainingMileageKm:b[f+12]/10,averageSpeedKmh:u16(b,f+13)/10,chargeCycle:b[f+15],overflowDischarge:b[f+16]}}
function pLegacy(b){
 const s=find(b,0x11,i=>b[i]>=0x40&&b[i]<=0x4F&&b[i+3]===2&&b[i+7]===0x40&&b[i+8]===0x54&&b[i+9]===0x44&&b[i+10]===0x43);if(s==null)return null;
 return{speedKmh:b[s+2]/10,lightOn:(b[s]&1)===1}}
function pTwo(b){
 const h=toHex(b);let s=h.indexOf("0546");
 if(s>=0&&h.length>=s+32&&h.substr(s+4,2)!=="01"){const x=(a,l)=>parseInt(h.substr(s+a,l),16);
  return{speedKmh:x(6,4)/10,currentA:x(10,4)/100,voltageV:x(14,4)/100,remainingMileageKm:x(18,4)/10,batteryLevel:x(22,2),charge:x(24,2)!==0,lockState:h.substr(s+26,2)==="00",fault:x(28,4),errorCode:x(28,4)}}
 s=h.indexOf("0548");
 if(s>=0&&h.length>=s+22){const x=(a,l)=>parseInt(h.substr(s+a,l),16);
  return{timeOfRide:x(6,4),mileageOfRideKm:x(10,4)/10,totalMileageKm:x(14,8)/100}}
 return null}
function parseTelemetry(b,fam){
 switch(fam){
  case"LEGACY_STATUS":return pLegacy(b);
  case"SO4_PRO":return pSo4(b,true)||pSo4(b,false)||pLegacy(b);
  case"D7_SO4_V1":return pSo4(b,false);
  case"D7_SO4_V51_PLUS":return pSo4(b,true);
  case"DYNAMIC_D7":return pDynRt(b)||pDynStandby(b);
  case"TWO_BYTE":return pTwo(b)}
 return null}
const sessionTokenOf=hex=>{const c=norm(hex);return(!c.startsWith("0601")||c.length<14)?null:c.substring(6,14)};
let frameBuf=[];
function frameAppend(bytes,fam){frameBuf.push(...bytes);const t=parseTelemetry(Uint8Array.from(frameBuf),fam);if(t)frameBuf=[];else if(frameBuf.length>160)frameBuf=frameBuf.slice(-64);return t}

/* ---------- Zustand ---------- */
let model=findModel(store.get("modelId")),moreSpeed=store.get("moreSpeed",false);
let secret=null,token=null,rtStarted=false,tele=null,conn="DISCONNECTED",lastOut=null;
let dev=null,wch=null,nch=null,rxBuf=[],queue=Promise.resolve(),wake=null,connecting=false;

function toast(msg){const t=$("#toast");t.textContent=msg;t.classList.add("show");clearTimeout(toast.t);toast.t=setTimeout(()=>t.classList.remove("show"),2600)}
function resetProto(){secret=null;token=null;rtStarted=false;tele=null;frameBuf=[];rxBuf=[]}

/* ---------- Transport (ScooterBleManager) ---------- */
const aesOpts={mode:CryptoJS.mode.ECB,padding:CryptoJS.pad.NoPadding};
function txBytes(hex){
 const key=model.profile.wkey||model.profile.key,plain=toBytes(hex);if(!key)return plain;
 const kb=toBytes(key);if(kb.length!==16)throw new Error("AES-Key muss 16 Byte lang sein");
 const padded=new Uint8Array(Math.ceil(plain.length/16)*16);padded.set(plain);
 const ct=CryptoJS.AES.encrypt(CryptoJS.lib.WordArray.create(padded),CryptoJS.enc.Hex.parse(key),aesOpts).ciphertext.toString(CryptoJS.enc.Hex);
 return toBytes(ct)}
function rxDecode(bytes){
 const key=model.profile.rkey||model.profile.key;if(!key)return bytes;
 rxBuf.push(...bytes);if(rxBuf.length%16!==0)return null;
 try{const ct=CryptoJS.lib.WordArray.create(Uint8Array.from(rxBuf));rxBuf=[];
  const pl=toBytes(CryptoJS.AES.decrypt({ciphertext:ct},CryptoJS.enc.Hex.parse(key),aesOpts).toString(CryptoJS.enc.Hex));
  let n=pl.length;while(n>0&&pl[n-1]===0)n--;return pl.slice(0,n)}catch(e){rxBuf=[];return null}}
function sendHex(hex){
 if(!wch){toast("Nicht verbunden oder kein Write-Char");return Promise.resolve()}
 let bytes;try{bytes=txBytes(norm(hex))}catch(e){toast(e.message||"Ungültiges Hex");return Promise.resolve()}
 queue=queue.then(async()=>{try{if(wch.properties.writeWithoutResponse)await wch.writeValueWithoutResponse(bytes);else await wch.writeValue(bytes)}catch(e){toast("Senden fehlgeschlagen: "+(e.message||e))}});
 return queue}
function onRx(ev){
 const raw=new Uint8Array(ev.target.value.buffer.slice(ev.target.value.byteOffset,ev.target.value.byteOffset+ev.target.value.byteLength));
 const plain=rxDecode(raw);if(!plain)return;
 const hex=toHex(plain),t0=sessionTokenOf(hex);if(t0)token=t0;
 const t=conn==="CONNECTED"?frameAppend(plain,model.family):null;
 if(t&&t.dynamicSecret!=null)secret=t.dynamicSecret;
 lastOut=hex;
 if(t){const m={...tele};for(const k in t)if(t[k]!=null)m[k]=t[k];tele=m}
 if(token&&!rtStarted&&model.c.rtStart){rtStarted=true;sendCatalog(model.c.rtStart,"Realtime-Start",true)}
 render()}
function setConn(s){conn=s;if(s==="DISCONNECTED"){wch=nch=null;resetProto();releaseWake()}render()}
async function connect(){
 if(!navigator.bluetooth){toast("Kein Web Bluetooth verfügbar");return}
 if(connecting||conn!=="DISCONNECTED")return;connecting=true;
 try{
  dev=await navigator.bluetooth.requestDevice({acceptAllDevices:true,optionalServices:[NORDIC.svc,so6p.svc]});
  setConn("CONNECTING");
  dev.addEventListener("gattserverdisconnected",()=>setConn("DISCONNECTED"));
  const nm=(dev.name||"").toUpperCase(),hint=[["SFSO4UL","so4ul"],["SFSOMT","somytier"],["SFSO6","so6"],["SFSC6","so6"],["SFSO1","so1"],["SFSC1","so1"],["SFS1","so1"],["SFSO2","so2_air"],["SFSC2","so2_air"],["SFS2","so2_air"],["SFSO3","so3"],["SFSC3","so3"],["SFS3","so3"]].find(([p])=>nm.startsWith(p));
  if(hint&&hint[1]!==model.id){setModel(findModel(hint[1]));toast("Modell erkannt: "+model.name)}
  const srv=await dev.gatt.connect();resetProto();
  let svc;try{svc=await srv.getPrimaryService(model.profile.svc);wch=await svc.getCharacteristic(model.profile.w);nch=await svc.getCharacteristic(model.profile.n)}
  catch(e){toast("Profil-UUIDs nicht gefunden. Falsches Modell?");try{srv.disconnect()}catch(_){}setConn("DISCONNECTED");return}
  toast("Profil-UUIDs gefunden");
  nch.addEventListener("characteristicvaluechanged",onRx);await nch.startNotifications();
  setConn("CONNECTED");requestWake();
  if(model.c.sessionToken)sendCatalog(model.c.sessionToken,"Session-Token",true);else if(model.c.startup)sendCatalog(model.c.startup,"Startup",true)
 }catch(e){if(e&&e.name!=="NotFoundError")toast("Verbindung fehlgeschlagen: "+(e.message||e));setConn("DISCONNECTED")}
 finally{connecting=false}}
function disconnect(){try{if(dev&&dev.gatt.connected)dev.gatt.disconnect()}catch(e){}setConn("DISCONNECTED")}
async function requestWake(){try{if($("#cbWake").checked&&navigator.wakeLock)wake=await navigator.wakeLock.request("screen")}catch(e){}}
function releaseWake(){try{wake&&wake.release()}catch(e){}wake=null}

/* ---------- Kommandos (MainViewModel) ---------- */
const rt=()=>({secret,token});
function sendCatalog(spec,label,quiet){
 if(!spec){if(!quiet)toast("Kein "+label+"-Kommando für "+model.name);return}
 if(spec.tok&&token==null){const s=model.c.sessionToken&&resolve(model.c.sessionToken,rt());if(s)sendHex(s);if(!quiet)toast("Session-Token wird angefragt, Kommando danach erneut senden");return}
 const h=resolve(spec,rt());if(h==null){if(!quiet)toast(label+" konnte nicht aufgelöst werden");return}
 sendHex(h)}
function sendSpeed(v){const s=model.speeds[v];const h=s&&resolve(s,rt());if(!h){toast(model.name+" unterstützt "+v+" km/h nicht");return}sendHex(h)}
function sendAdv(n){if(n<1||n>model.maxAdv){toast("Kein Kommando für Mode "+n);return}sendHex(d7(0xA3,0,[n]));toast("Mode "+n+" gesendet")}
const SIMPLE={ECO:["eco","Eco"],NORMAL:["normal","Normal"],SPORT:["sport","Sport"],DEV:["dev","Dev"],LOCK:["lock","Lock"],UNLOCK:["unlock","Unlock"]};
function runAction(a){
 if(SIMPLE[a.type])return sendCatalog(model.c[SIMPLE[a.type][0]],SIMPLE[a.type][1]);
 const n=parseInt(a.value,10);
 if(a.type==="SPEED")return isNaN(n)?toast("Ungültige Geschwindigkeit"):sendSpeed(n);
 if(a.type==="ADV")return isNaN(n)?toast("Ungültiger Mode"):sendAdv(n);
 if(a.type==="EXTRA"){const e=model.extra.find(x=>x.id===a.value);return e?sendCatalog(e.spec,e.label):toast("Kommando nicht verfügbar")}}

/* ---------- Verfügbarkeit / Anzeige ---------- */
const ready=s=>!!s&&(!s.dyn||secret!=null);
function speedRange(){
 const sp=model.supported,rq=moreSpeed?[1,65]:[8,30],a=Math.max(sp[0],rq[0]),b=Math.min(sp[sp.length-1],rq[1]);
 return a<=b?[a,b]:[sp[0],sp[sp.length-1]]}
const fmt=(v,u,d=1)=>v==null?"—":v.toFixed(d)+" "+u;
const TILES=[["Akku",t=>t.batteryLevel==null?"—":Math.min(100,Math.max(0,t.batteryLevel))+" %"],["Spannung",t=>fmt(t.voltageV,"V")],["Strom",t=>fmt(t.currentA,"A")],["Restweite",t=>fmt(t.remainingMileageKm,"km")],["Trip",t=>fmt(t.mileageOfRideKm,"km")],["Modus",t=>t.speedMode==null?"—":String(t.speedMode)]];
const nt=v=>v%1===0?String(v):v.toFixed(1);
function details(t){
 const d=[];
 if(t.totalMileageKm!=null)d.push("Total "+nt(t.totalMileageKm)+" km");
 if(t.averageSpeedKmh!=null)d.push("Ø "+t.averageSpeedKmh.toFixed(1)+" km/h");
 if(t.averageCurrentA!=null)d.push("Ø "+t.averageCurrentA.toFixed(1)+" A");
 if(t.timeOfRide!=null)d.push("Fahrt "+t.timeOfRide+"s");
 if(t.energy!=null)d.push("Energie "+t.energy.toFixed(1));
 if(t.lockState!=null)d.push(t.lockState?"Gesperrt":"Entsperrt");
 if(t.charge!=null)d.push(t.charge?"Lädt":"Lädt nicht");
 if(t.speedInMiles)d.push("Meilen");
 if(t.chargeCycle!=null)d.push("Zyklen "+t.chargeCycle);
 if(t.overflowDischarge)d.push("Overflow "+t.overflowDischarge);
 if(t.errorCode)d.push("Fehler 0x"+hex2(t.errorCode));
 if(t.fault)d.push("Fault 0x"+hex2(t.fault));
 return d.length?d.join("   •   "):"Telemetrie empfangen"}
function render(){
 const on=conn==="CONNECTED",st=$("#status");
 st.textContent={DISCONNECTED:"Nicht verbunden",CONNECTING:"Verbinde…",CONNECTED:"Verbunden"}[conn];st.classList.toggle("on",on);
 const t=tele||{};
 $("#spd").textContent=(t.speedKmh||0).toFixed(1).padStart(4,"0");
 $("#light").textContent=t.lightOn==null?"Licht –":t.lightOn?"Licht an":"Licht aus";
 $("#watt").textContent=t.voltageV!=null&&t.currentA!=null?Math.round(t.voltageV*t.currentA)+" W":"";
 $("#batbar").style.width=(t.batteryLevel==null?0:Math.min(100,Math.max(0,t.batteryLevel)))+"%";
 $("#tiles").innerHTML=TILES.map(([l,f])=>"<div class=tile><small>"+l+"</small><b>"+f(t)+"</b></div>").join("");
 $("#details").textContent=tele?details(t):"Keine Telemetrie";
 $("#out").textContent=lastOut||"–";
 [["bEco","eco"],["bNormal","normal"],["bSport","sport"],["bDev","dev"],["bLock","lock"],["bUnlock","unlock"]].forEach(([id,k])=>$("#"+id).disabled=!(on&&ready(model.c[k])));
 const sp=model.supported,speedOk=on&&sp.length>0&&ready(model.speeds[sp[0]]),sl=$("#sl");
 if(sp.length){const[a,b]=speedRange(),cur=Math.min(b,Math.max(a,+sl.value||20));sl.min=a;sl.max=b;sl.value=cur;$("#slv").textContent=cur+" km/h"}
 else{sl.min=0;sl.max=1;sl.value=0;$("#slv").textContent="—"}
 sl.disabled=!speedOk;
 document.querySelectorAll("#hot button").forEach(b=>b.disabled=!(speedOk&&model.speeds[+b.dataset.v]));
 $("#bConn").disabled=conn!=="DISCONNECTED"||!navigator.bluetooth;$("#bDisc").disabled=conn==="DISCONNECTED";
 $("#bHex").disabled=!on;$("#extras").querySelectorAll("button").forEach(b=>b.disabled=!on);$("#modeSel").disabled=!on;
 document.querySelectorAll("#bubs button").forEach(b=>b.disabled=!on&&!editMode)}

/* ---------- Modell & Advanced ---------- */
function setModel(m){
 const changed=m.id!==model.id;model=m;store.set("modelId",m.id);
 if(changed){resetProto();lastOut=null}
 $("#model").value=m.id;$("#mdesc").textContent=m.desc;
 const ms=$("#modeSel");ms.innerHTML=m.maxAdv?"<option value=''>Mode wählen…</option>"+Array.from({length:m.maxAdv},(_,i)=>"<option value="+(i+1)+">Mode "+(i+1)+"</option>").join(""):"<option value=''>Keine Advanced-Modes</option>";
 $("#extras").innerHTML=m.extra.map(e=>"<button data-id="+e.id+">"+e.label+"</button>").join("");
 $("#extras").querySelectorAll("button").forEach(b=>b.onclick=()=>runAction({type:"EXTRA",value:b.dataset.id}));
 renderBubbles();render()}

/* ---------- Quick-Bubbles ---------- */
const TYPES={ECO:"Eco",NORMAL:"Normal",SPORT:"Sport",DEV:"Dev",LOCK:"Sperren",UNLOCK:"Entsperren",SPEED:"Geschwindigkeit",ADV:"Advanced-Mode",EXTRA:"Zusatzkommando"};
const bKey=()=>"bubbles::"+model.id+"::"+(dev&&dev.id?dev.id.toUpperCase():"no-device");
const actLabel=a=>a.type==="SPEED"?a.value+" km/h":a.type==="ADV"?"Mode "+a.value:a.type==="EXTRA"?(model.extra.find(e=>e.id===a.value)||{label:"Kommando"}).label:TYPES[a.type];
const actOk=a=>SIMPLE[a.type]?!!model.c[SIMPLE[a.type][0]]:a.type==="SPEED"?model.supported.includes(+a.value):a.type==="ADV"?+a.value>=1&&+a.value<=model.maxAdv:model.extra.some(e=>e.id===a.value);
let editMode=false,editing=null;
function renderBubbles(){
 const list=store.get(bKey(),[]),box=$("#bubs");box.innerHTML="";
 list.forEach(b=>{const el=document.createElement("button");el.className="bub";el.textContent=b.name;el.style.background=b.color;
  el.onclick=async()=>{if(editMode){openEditor(b);return}for(const a of b.actions){if(actOk(a)){runAction(a);await sleep(350)}}};box.appendChild(el)});
 if(!list.length)box.innerHTML="<p class=muted style='grid-column:1/-1'>Noch keine Bubbles. Lege eine neue Schnelloption an.</p>";
 render()}
function openEditor(b){
 editing=b?{...b,actions:[...b.actions]}:{id:String(Date.now()),name:"",color:"#35d69a",actions:[]};
 $("#edName").value=editing.name;$("#edColor").value=editing.color;$("#edDel").classList.toggle("hide",!b);
 $("#edType").innerHTML=Object.entries(TYPES).filter(([k])=>!(k==="ADV"&&!model.maxAdv)&&!(k==="EXTRA"&&!model.extra.length)&&!(k==="SPEED"&&!model.supported.length)).map(([k,v])=>"<option value="+k+">"+v+"</option>").join("");
 $("#edExtra").innerHTML=model.extra.map(e=>"<option value="+e.id+">"+e.label+"</option>").join("");
 typeChanged();drawEd();$("#ed").classList.remove("hide");$("#ed").scrollIntoView({block:"nearest"})}
function typeChanged(){const t=$("#edType").value;$("#edVal").classList.toggle("hide",!(t==="SPEED"||t==="ADV"));$("#edExtra").classList.toggle("hide",t!=="EXTRA")}
function drawEd(){const l=$("#edList");l.innerHTML=editing.actions.length?"":"<span class=muted>Noch keine Aktionen</span>";
 editing.actions.forEach((a,i)=>{const c=document.createElement("button");c.textContent=(i+1)+". "+actLabel(a)+" ×";c.onclick=()=>{editing.actions.splice(i,1);drawEd()};l.appendChild(c)})}

/* ---------- Verdrahtung ---------- */
$("#model").innerHTML=MODELS.map(m=>"<option value="+m.id+">"+m.name+"</option>").join("");
$("#model").onchange=e=>{if(conn!=="DISCONNECTED")disconnect();setModel(findModel(e.target.value))};
[["bEco","ECO"],["bNormal","NORMAL"],["bSport","SPORT"],["bDev","DEV"],["bLock","LOCK"],["bUnlock","UNLOCK"]].forEach(([id,t])=>$("#"+id).onclick=()=>runAction({type:t}));
$("#hot").innerHTML=[8,15,20,25,30].map(v=>"<button data-v="+v+">"+v+"</button>").join("");
$("#hot").querySelectorAll("button").forEach(b=>b.onclick=()=>{const v=+b.dataset.v;$("#sl").value=v;$("#slv").textContent=v+" km/h";sendSpeed(v)});
$("#sl").oninput=e=>$("#slv").textContent=e.target.value+" km/h";
$("#sl").onchange=e=>sendSpeed(+e.target.value);
$("#bConn").onclick=connect;$("#bDisc").onclick=()=>{disconnect();toast("Getrennt")};
$("#swAdv").checked=store.get("adv",false);$("#adv").classList.toggle("hide",!$("#swAdv").checked);
$("#swAdv").onchange=e=>{store.set("adv",e.target.checked);$("#adv").classList.toggle("hide",!e.target.checked)};
$("#cbMore").checked=moreSpeed;$("#cbMore").onchange=e=>{moreSpeed=e.target.checked;store.set("moreSpeed",moreSpeed);render()};
$("#cbWake").checked=store.get("wake",false);$("#cbWake").onchange=e=>{store.set("wake",e.target.checked);e.target.checked?requestWake():releaseWake()};
$("#modeSel").onchange=e=>{if(e.target.value)sendAdv(+e.target.value)};
$("#bHex").onclick=()=>{const h=$("#hex").value;if(!norm(h)){toast("Bitte Hex eingeben");return}sendHex(h)};
$("#bNewBub").onclick=()=>openEditor(null);
$("#bEditBub").onclick=()=>{editMode=!editMode;$("#bEditBub").textContent=editMode?"Fertig":"Bearbeiten";if(editMode)toast("Tippe eine Bubble zum Bearbeiten");render()};
$("#edType").onchange=typeChanged;
$("#edAdd").onclick=()=>{const t=$("#edType").value;let v=null;
 if(t==="SPEED"||t==="ADV"){v=$("#edVal").value;if(!v)return toast("Wert eingeben")}else if(t==="EXTRA")v=$("#edExtra").value;
 const a={type:t,value:v};if(!actOk(a))return toast("Für dieses Modell nicht verfügbar");editing.actions.push(a);drawEd()};
$("#edSave").onclick=()=>{if(!editing.actions.length)return toast("Mindestens eine Aktion hinzufügen");
 editing.name=($("#edName").value.trim()||"Quick").slice(0,10);editing.color=$("#edColor").value;
 const l=store.get(bKey(),[]),i=l.findIndex(x=>x.id===editing.id);if(i>=0)l[i]=editing;else l.push(editing);store.set(bKey(),l);
 $("#ed").classList.add("hide");renderBubbles()};
$("#edDel").onclick=()=>{store.set(bKey(),store.get(bKey(),[]).filter(x=>x.id!==editing.id));$("#ed").classList.add("hide");renderBubbles()};
$("#edCancel").onclick=()=>$("#ed").classList.add("hide");
document.addEventListener("visibilitychange",()=>{if(document.visibilityState==="visible"&&conn==="CONNECTED")requestWake()});

/* ---------- Start ---------- */
if(!navigator.bluetooth)$("#nobt").classList.remove("hide");
const accepted=store.get("accepted",false);
if(accepted)$("#gate").classList.add("hide");
$("#gOk").onclick=()=>{store.set("accepted",true);$("#gate").classList.add("hide")};
$("#gNo").onclick=()=>{$("#gate").innerHTML="<div><h1>SoHacks Web</h1><p class=muted>Ohne Zustimmung zum Risiko-Hinweis bleibt die Seite gesperrt. Lade sie neu, um erneut zu entscheiden.</p></div>"};
setModel(model);
</script>
</body>
</html>
