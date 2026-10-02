<!DOCTYPE html>
<html lang="en"><head><meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<meta name="color-scheme" content="dark">
<title>Household Cleaning · Eickhoffweg</title>
<style>
:root{--bg:#1e1a17;--card:#2a2420;--ink:#f0e7de;--mut:#a89b8d;--line:#3d342d;--ok:#7fae8a;--okb:#223027;--bad:#c4655a;--badb:#36231f;--warn:#c9965a;--acc:#b98f6a;--away:#8a6446}
*{box-sizing:border-box}
body{margin:0;background:var(--bg);color:var(--ink);font:16px/1.4 system-ui,-apple-system,Segoe UI,sans-serif;padding:env(safe-area-inset-top) 0 env(safe-area-inset-bottom)}
main{max-width:560px;margin:0 auto;padding:20px 16px 48px}
h1{font-size:28px;margin:0}.sub{color:var(--mut);margin:2px 0}#quote{font-style:italic;min-height:1.4em;margin:10px 0 14px;color:var(--acc)}
h2{font-size:13px;text-transform:uppercase;letter-spacing:.08em;color:var(--mut);margin:26px 0 8px}
.notice{background:#33281c;border-left:4px solid var(--warn);padding:10px 12px;border-radius:8px;margin-bottom:10px}
.card{background:var(--card);border:2px solid var(--line);border-radius:14px;padding:14px;margin-bottom:10px}
.card.done{border-color:var(--ok);background:var(--okb)}.card.over,.card.hurry{border-color:var(--bad);background:var(--badb)}.card.soon{border-color:var(--warn)}
.card.sm{padding:10px;opacity:.9}.task{font-weight:700;font-size:18px}.sm .task{font-size:15px}.who{color:var(--mut);font-size:14px;margin-top:2px}
.mood{font-size:20px;margin:8px 0 4px}.sm .mood{font-size:15px}
.top{display:flex;justify-content:space-between;align-items:center;gap:8px}
.row{display:flex;gap:6px;flex-wrap:wrap;margin-top:10px;align-items:center}
button,input{font:inherit;border:1.5px solid var(--line);background:var(--card);color:var(--ink);padding:8px 13px;border-radius:10px}
input{width:100%;margin:6px 0}button{cursor:pointer}button:disabled{opacity:.55;cursor:default}
button.on{background:var(--acc);border-color:var(--acc);color:#1e1a17}button.ok{background:var(--ok);border-color:var(--ok);color:#1e1a17;font-weight:700}
.home{background:#4d7358;border-color:#7fae8a}.awayb{background:var(--away);border-color:#b98f6a}
.undo{background:none;border:none;color:var(--mut);text-decoration:underline;padding:4px 0;font-size:13px}
.log{display:flex;justify-content:space-between;align-items:center;font-size:13px;color:var(--mut);padding:4px 0}
table{width:100%;border-collapse:collapse;font-size:14px}td,th{padding:5px 4px;text-align:center;border-bottom:1px solid var(--line)}th:first-child,td:first-child{text-align:left}
.cal{display:grid;grid-template-columns:repeat(7,1fr);gap:3px}.dow{font-size:11px;color:var(--mut);text-align:center}
.day{aspect-ratio:1;border:1.5px solid var(--line);border-radius:8px;padding:3px 2px;font-size:13px;text-align:center;cursor:pointer;background:var(--card)}
.day.out{opacity:.35}.day.today{border-color:var(--acc);font-weight:700}.day.sel{background:var(--acc);border-color:var(--acc);color:#1e1a17}
.dots{display:flex;gap:2px;justify-content:center;margin-top:2px}.dot{width:7px;height:7px;border-radius:50%}
details summary{cursor:pointer;color:var(--mut);margin:6px 0;font-size:14px}.foot{color:var(--mut);font-size:12px;margin-top:24px}
</style></head><body><main>
<div id="cfgv" hidden><h1>Setup</h1><p class="sub">Paste your Firebase details once.</p>
<input id="durl" placeholder="Database URL (https://…firebasedatabase.app)"><input id="akey" placeholder="Web API key (AIza…)"><button class="on" id="cgo">Save</button></div>
<div id="login" hidden><h1>Moin ♡</h1><p class="sub">Household Cleaning · Eickhoffweg</p>
<input id="em" type="email" placeholder="Email" autocomplete="username"><input id="pw" type="password" placeholder="Password" autocomplete="current-password">
<button class="on" id="lgo">Log in</button><div class="who" id="lerr" style="margin-top:8px"></div></div>
<div id="app" hidden>
<h1>Moin ♡</h1><div class="sub">Household Cleaning · Eickhoffweg</div><div id="quote"></div>
<div id="err"></div><div id="notices"></div>
<div class="row" style="margin:0"><button id="calbtn">📅 Calendar</button><button id="notif" hidden>🔔 Reminders</button><button id="out">Log out</button></div>
<h2>Who's around?</h2><div class="row" id="away" style="margin:0"></div><div id="absum" style="margin-top:6px"></div>
<div class="card" id="calp" hidden style="margin-top:8px">
<div class="top"><button id="mprev">‹</button><b id="mtitle"></b><button id="mnext">›</button></div>
<div class="cal" id="calgrid" style="margin-top:8px"></div><div class="who" style="margin-top:10px" id="calsel"></div>
<input id="anote" placeholder="Note (optional), e.g. visiting family"><button class="ok" id="addabs">Add my away dates</button><div id="callist" style="margin-top:10px"></div></div>
<h2 id="curH"></h2><div id="cur"></div>
<div id="prevWrap" hidden><h2 id="prevH"></h2><div id="prev"></div></div>
<details><summary id="nextH"></summary><div id="nxt"></div></details>
<h2>🗑️ Bins</h2><div class="row" id="pick" style="margin:0"></div><div class="row"><button class="ok" id="logb"></button></div>
<div class="card" style="margin-top:10px"><table id="tally"></table></div><div id="recent"></div>
<h2>📝 Notiz</h2><input id="ntext" placeholder="Write a note…"><button id="npost">Post</button><div id="nlist" style="margin-top:8px"></div>
<h2>🛒 Shopping</h2><input id="stext" placeholder="Add an item…"><button id="sadd">Add</button><div id="slist" style="margin-top:8px"></div>
<details><summary>Cover history</summary><div id="cvh"></div></details>
<div class="foot">Rota changes every Monday and is due Sunday night. <a id="setl" href="#" style="color:var(--mut)">Copy setup link</a></div>
</div>
</main>
<script>
const P=["Bella","Melody","Lohans"],T=[["bath","🛁 Bathroom"],["kit","🍽️ Kitchen"],["floor","🧽 Floors (vacuum + mop)"]],B=[["bio","🟢 Bio","#4fa86a"],["paper","🔵 Paper","#4a86d4"],["plastic","🟡 Plastic","#e0b400"]],PC={Bella:"#d6819f",Melody:"#a88ad6",Lohans:"#5fb8bd"};
const Q=[["en","Many hands make light work."],["fr","Petit à petit, l'oiseau fait son nid."],["ar","يد واحدة لا تصفق"],["fa","قطره قطره جمع گردد وانگهی دریا شود"],["en","Don't put off till tomorrow what you can do today."],["fr","L'union fait la force."],["ar","من جدّ وجد"],["fa","کار امروز را به فردا مینداز"]];
const START=new Date(2026,8,21),RUN=new Date(2026,9,1),DAY=864e5;
let S={away:{},abs:{},done:{},cover:{},bins:{},notes:{},shop:{}},cfg=null,auth=null,tok=null,uid=null,exp=0,me=null,busy=0,sel=new Set(),calOpen=false,calM=new Date(new Date().getFullYear(),new Date().getMonth(),1),selA=null,selB=null,qi=Math.floor(Math.random()*8),began=false;
const $=id=>document.getElementById(id),mod=(a,n)=>((a%n)+n)%n;
const ls={g:k=>{try{return JSON.parse(localStorage.getItem(k))}catch(e){return null}},s:(k,v)=>{try{localStorage.setItem(k,JSON.stringify(v))}catch(e){}}};
const iso=d=>d.getFullYear()+"-"+String(d.getMonth()+1).padStart(2,"0")+"-"+String(d.getDate()).padStart(2,"0");
const fd=d=>d.toLocaleDateString("en-GB",{day:"numeric",month:"short"}),fdw=d=>d.toLocaleDateString("en-GB",{weekday:"short",day:"numeric",month:"short"});
const pd=s=>{const [y,m,d]=s.split("-");return new Date(+y,m-1,+d)},fr=a=>a.from===a.to?fd(pd(a.from)):fd(pd(a.from))+" – "+fd(pd(a.to));
function h(t,c,x,f){const e=document.createElement(t);if(c)e.className=c;if(x!=null)e.textContent=x;if(f)e.onclick=f;return e}
function monday(d){const x=new Date(d.getFullYear(),d.getMonth(),d.getDate());x.setDate(x.getDate()-((x.getDay()+6)%7));return x}
const endOf=m=>{const e=new Date(m);e.setDate(e.getDate()+6);e.setHours(23,59,59);return e},live=m=>endOf(m)>=RUN,range=m=>fd(m<RUN?RUN:m)+" – "+fd(endOf(m));
const show=id=>{["cfgv","login","app"].forEach(x=>$(x).hidden=x!==id)};
function msg(t){$("err").replaceChildren();if(t)$("err").append(h("div","notice",t))}
const ents=o=>Object.entries(o||{}).map(([id,v])=>({id,...v}));
// ---- config + login
function boot(){const q=new URLSearchParams(location.hash.slice(1));
  if(q.get("d")&&q.get("k")){ls.s("cfg",{d:q.get("d").replace(/\/$/,""),k:q.get("k")});history.replaceState(null,"",location.pathname)}
  cfg=ls.g("cfg");auth=ls.g("auth");
  $("cgo").onclick=()=>{const d=$("durl").value.trim().replace(/\/$/,""),k=$("akey").value.trim();if(!/^https:\/\//.test(d)||!k)return alert("Please fill in both fields");cfg={d,k};ls.s("cfg",cfg);show("login")};
  $("lgo").onclick=login;
  if(!cfg)show("cfgv");else if(auth)start();else show("login")}
async function login(){$("lerr").textContent="";try{
  const r=await fetch("https://identitytoolkit.googleapis.com/v1/accounts:signInWithPassword?key="+cfg.k,{method:"POST",headers:{"Content-Type":"application/json"},body:JSON.stringify({email:$("em").value.trim(),password:$("pw").value,returnSecureToken:true})});
  const j=await r.json();if(!r.ok)throw new Error("Wrong email or password");
  auth={rt:j.refreshToken};ls.s("auth",auth);tok=j.idToken;uid=j.localId;exp=Date.now()+(+j.expiresIn-120)*1000;$("pw").value="";start()}catch(e){$("lerr").textContent=e.message}}
async function token(){if(tok&&Date.now()<exp)return tok;
  const r=await fetch("https://securetoken.googleapis.com/v1/token?key="+cfg.k,{method:"POST",headers:{"Content-Type":"application/x-www-form-urlencoded"},body:"grant_type=refresh_token&refresh_token="+encodeURIComponent(auth.rt)});
  const j=await r.json();if(!r.ok)throw new Error("session expired");tok=j.id_token;uid=j.user_id;auth.rt=j.refresh_token;ls.s("auth",auth);exp=Date.now()+(+j.expires_in-120)*1000;return tok}
async function start(){try{const t=await token(),n=await (await fetch(cfg.d+"/users/"+uid+".json?auth="+t)).json();
  if(!P.includes(n)){ls.s("auth",null);show("login");$("lerr").textContent="This account isn't linked to Bella, Melody or Lohans yet.";return}
  me=n;show("app");begin()}catch(e){ls.s("auth",null);show("login");$("lerr").textContent="Please log in again."}}
async function api(p,m,b){const t=await token(),r=await fetch(cfg.d+"/h"+p+".json?auth="+t,{method:m||"GET",body:b===undefined?undefined:JSON.stringify(b)});if(!r.ok)throw new Error(r.status===401?"no access":r.status);return r.json()}
async function load(){if(busy)return;try{const j=(await api(""))||{};Object.keys(S).forEach(k=>S[k]=j[k]||{});msg("");render()}catch(e){msg("⚠️ Can't reach the database ("+e.message+").")}}
async function w(p,m,b){busy++;render();try{await api(p,m,b)}catch(e){msg("⚠️ Couldn't save ("+e.message+").")}busy--;load()}
function post(key,o){S[key]["tmp"+o.t]=o;busy++;api("/"+key,"POST",o).catch(e=>msg("⚠️ Couldn't save ("+e.message+").")).finally(()=>{busy--;load()});render()}
// ---- logic
const st=p=>S.away[p]===undefined?p==="Bella":!!S.away[p];
const absAt=(p,d)=>ents(S.abs).some(a=>a.p===p&&a.from<=d&&d<=a.to);
const isCur=m=>iso(monday(new Date()))===iso(m);
const planned=(p,m)=>ents(S.abs).some(a=>a.p===p&&a.from<=iso(endOf(m))&&a.to>=iso(m));
const awayIn=(p,m)=>isCur(m)?(S.away[p]===false?false:(st(p)||planned(p,m))):planned(p,m);
function begin(){if(began){load();return}began=true;
  $("calbtn").onclick=()=>{calOpen=!calOpen;cal()};$("mprev").onclick=()=>{calM=new Date(calM.getFullYear(),calM.getMonth()-1,1);cal()};$("mnext").onclick=()=>{calM=new Date(calM.getFullYear(),calM.getMonth()+1,1);cal()};
  $("addabs").onclick=()=>{if(!selA)return alert("Tap your dates on the calendar first");post("abs",{p:me,from:selA,to:selB||selA,note:$("anote").value.trim(),t:Date.now()});selA=selB=null;$("anote").value=""};
  $("out").onclick=()=>{ls.s("auth",null);tok=null;location.reload()};
  $("setl").onclick=async e=>{e.preventDefault();const u=location.origin+location.pathname+"#d="+encodeURIComponent(cfg.d)+"&k="+cfg.k;try{await navigator.clipboard.writeText(u);e.target.textContent="Copied ✓"}catch(x){prompt("Setup link:",u)}};
  $("logb").onclick=()=>{if(!sel.size)return alert("Pick the bins first");const e={t:Date.now(),by:me,bins:[...sel]};sel=new Set();post("bins",e)};
  $("npost").onclick=()=>{const v=$("ntext").value.trim();if(!v)return;$("ntext").value="";post("notes",{by:me,text:v,t:Date.now()})};
  $("sadd").onclick=()=>{const v=$("stext").value.trim();if(!v)return;$("stext").value="";post("shop",{by:me,text:v,done:false,t:Date.now()})};
  if("Notification" in window&&Notification.permission==="default"){$("notif").hidden=false;$("notif").onclick=()=>Notification.requestPermission().then(()=>{$("notif").hidden=true;render()})}
  const q=()=>{const [lg,t]=Q[qi++%Q.length],e=$("quote");e.textContent=t;e.lang=lg;e.dir=lg==="en"||lg==="fr"?"ltr":"rtl"};q();setInterval(q,9000);
  render();load();setInterval(()=>{if(!document.hidden)load()},8000)}
function cards(m,box,now,small){box.replaceChildren();const wk=Math.round((m-START)/(7*DAY)),due=endOf(m);let open=0,mine=0;
  T.forEach(([id,name],i)=>{const owner=P[mod(i+wk,3)],k=iso(m)+"_"+id,d=S.done[k],cv=S.cover[k],aw=awayIn(owner,m),left=(due-now)/DAY,fut=now<m;
    const sc=d?"done":now>due?"over":fut?"todo":left<=2?"hurry":left<=3?"soon":"todo";
    const tx=d?"I'm fresh & clean 🥳":sc==="over"||sc==="hurry"?"Hurry up! 😡":sc==="soon"?"🤨":"Clean me 🫠";
    const can=me===owner||(cv&&cv.by===me);if(!d){open++;if(can&&(sc==="soon"||sc==="hurry"||sc==="over"))mine++}
    const c=h("div","card "+sc+(small?" sm":"")),l=h("div");
    l.append(h("div","task",name),h("div","who",owner+(aw?" · away":"")+" · due "+fdw(due)));c.append(l,h("div","mood",tx));
    if(d){c.append(h("div","who","Done "+fdw(new Date(d.at))+" · "+d.by+(d.by!==d.for?" (covered for "+d.for+")":"")));
      if(d.by===me)c.append(h("button","undo","Undo",()=>{delete S.done[k];w("/done/"+k,"DELETE")}))}
    else{if(cv)c.append(h("div","who","Covered by "+cv.by));const r=h("div","row");
      if(can&&!fut)r.append(h("button","ok","Done ✓",()=>{const o={by:me,for:owner,at:Date.now()};S.done[k]=o;w("/done/"+k,"PUT",o)}));
      if(aw&&me!==owner&&!cv)r.append(h("button","","🤝 I'll cover",()=>{const o={by:me,for:owner,t:Date.now()};S.cover[k]=o;w("/cover/"+k,"PUT",o)}));
      if(cv&&cv.by===me)r.append(h("button","undo","Withdraw cover",()=>{delete S.cover[k];w("/cover/"+k,"DELETE")}));
      if(r.children.length)c.append(r)}
    box.append(c)});return{open,mine}}
function render(){if(!me)return;const now=new Date(),m=monday(now),pm=new Date(m),nm=new Date(m);pm.setDate(pm.getDate()-7);nm.setDate(nm.getDate()+7);
  const a=$("away");a.replaceChildren();P.forEach(p=>{const on=st(p),b=h("button",on?"awayb":"home",(on?"🧳 ":"🏠 ")+p+(on?" · away":" · home"),()=>{S.away[p]=!st(p);w("/away/"+p,"PUT",st(p))});b.disabled=p!==me;a.append(b)});
  $("curH").textContent="This week · "+range(m);$("prevH").textContent="Last week · still open";$("nextH").textContent="Next week · "+range(nm);
  const c=cards(m,$("cur"),now,false);cards(nm,$("nxt"),now,true);
  const pl=live(pm)&&T.some(([id])=>!S.done[iso(pm)+"_"+id]);$("prevWrap").hidden=!pl;if(pl)cards(pm,$("prev"),now,true);
  const n=$("notices");n.replaceChildren();if(c.mine)n.append(h("div","notice","⏰ You have "+c.mine+" task(s) to finish by Sunday night."));
  try{if(c.mine&&"Notification" in window&&Notification.permission==="granted"&&!localStorage.getItem("n"+iso(m))){localStorage.setItem("n"+iso(m),1);new Notification("Cleaning reminder",{body:"You still have "+c.mine+" task(s) this week."})}}catch(e){}
  const u=$("absum");u.replaceChildren();absList().slice(0,4).forEach(x=>u.append(h("div","who","🧳 "+x.p+" · "+fr(x)+(x.note?" · "+x.note:""))));
  cal();bins();notes();shop();cvh()}
function absList(){const t=iso(new Date());return ents(S.abs).filter(a=>a.to>=t).sort((a,b)=>a.from<b.from?-1:1)}
function cal(){$("calp").hidden=!calOpen;if(!calOpen)return;
  $("mtitle").textContent=calM.toLocaleDateString("en-GB",{month:"long",year:"numeric"});
  const g=$("calgrid");g.replaceChildren();["Mo","Tu","We","Th","Fr","Sa","Su"].forEach(d=>g.append(h("div","dow",d)));
  const f=monday(calM),t=iso(new Date()),hi=selB||selA;
  for(let i=0;i<42;i++){const d=new Date(f);d.setDate(f.getDate()+i);const s=iso(d);
    const c=h("div","day"+(d.getMonth()!==calM.getMonth()?" out":"")+(s===t?" today":"")+(selA&&s>=selA&&s<=hi?" sel":""),null,()=>{if(!selA||selB){selA=s;selB=null}else{if(s<selA){selB=selA;selA=s}else selB=s}cal()});
    c.append(h("div","",d.getDate()));const dots=h("div","dots");
    P.forEach(p=>{if(absAt(p,s)){const e=h("span","dot");e.style.background=PC[p];dots.append(e)}});c.append(dots);g.append(c)}
  $("calsel").textContent=selA?"Away "+fd(pd(selA))+" – "+fd(pd(selB||selA))+" (for "+me+")":"Tap your first day, then your last day (one tap = one day). Dots show who is away: "+P.map(p=>p).join(", ")+".";
  const L=$("callist");L.replaceChildren();
  absList().forEach(a=>{const r=h("div","log"),sp=h("span","",a.p+" · "+fr(a)+(a.note?" · "+a.note:""));sp.style.color=PC[a.p];r.append(sp);
    if(a.p===me&&!a.id.startsWith("tmp"))r.append(h("button","undo","✕",()=>{delete S.abs[a.id];w("/abs/"+a.id,"DELETE")}));L.append(r)})}
function bins(){const E=ents(S.bins).sort((x,y)=>y.t-x.t),cut=Date.now()-56*DAY,nm=b=>B.find(x=>x[0]===b)[1];
  const pk=$("pick");pk.replaceChildren();
  [...B,["all","All 3"]].forEach(([id,name,col])=>{const on=id==="all"?sel.size===3:sel.has(id);
    const b=h("button",on&&id==="all"?"on":"",name,()=>{if(id==="all"){sel=sel.size===3?new Set():new Set(B.map(x=>x[0]))}else sel.has(id)?sel.delete(id):sel.add(id);bins()});
    if(col){b.style.borderColor=col;if(on){b.style.background=col;b.style.color="#1e1a17"}}pk.append(b)});
  $("logb").textContent="Log as "+me;
  const tl=$("tally");tl.replaceChildren();const hr=h("tr");hr.append(h("th","","8 weeks"));B.forEach(b=>hr.append(h("th","",b[1].split(" ")[0])));hr.append(h("th","","Trips"));tl.append(hr);
  P.forEach(p=>{const r=h("tr");r.append(h("td","",p));B.forEach(([id])=>r.append(h("td","",E.filter(e=>e.t>=cut&&e.by===p&&(e.bins||[]).includes(id)).length)));r.append(h("td","",E.filter(e=>e.t>=cut&&e.by===p).length));tl.append(r)});
  const rc=$("recent");rc.replaceChildren();
  E.slice(0,8).forEach(e=>{const r=h("div","log");r.append(h("span","",fdw(new Date(e.t))+" · "+e.by+" · "+(e.bins||[]).map(nm).join(", ")));
    if(e.by===me&&!e.id.startsWith("tmp"))r.append(h("button","undo","✕",()=>{delete S.bins[e.id];w("/bins/"+e.id,"DELETE")}));rc.append(r)})}
function notes(){const L=$("nlist");L.replaceChildren();
  ents(S.notes).sort((a,b)=>b.t-a.t).slice(0,10).forEach(n=>{const c=h("div","card");c.append(h("div","",n.text),h("div","who",n.by+" · "+fdw(new Date(n.t))));
    if(n.by===me&&!n.id.startsWith("tmp"))c.append(h("button","undo","Delete",()=>{delete S.notes[n.id];w("/notes/"+n.id,"DELETE")}));L.append(c)})}
function shop(){const L=$("slist");L.replaceChildren();
  ents(S.shop).sort((a,b)=>(a.done-b.done)||b.t-a.t).forEach(n=>{const r=h("div","log");
    const b=h("button","undo",(n.done?"☑ ":"☐ ")+n.text+" · "+n.by,()=>{const o={by:n.by,text:n.text,t:n.t,done:!n.done};S.shop[n.id]=o;w("/shop/"+n.id,"PUT",o)});b.style.textDecoration=n.done?"line-through":"none";b.style.fontSize="15px";b.style.textAlign="left";r.append(b);
    if(!n.id.startsWith("tmp"))r.append(h("button","undo","✕",()=>{delete S.shop[n.id];w("/shop/"+n.id,"DELETE")}));L.append(r)})}
function cvh(){const L=$("cvh");L.replaceChildren();const c=ents(S.done).filter(d=>d.by!==d.for).sort((a,b)=>b.at-a.at);
  if(!c.length)L.append(h("div","who","No covers yet."));c.slice(0,15).forEach(d=>L.append(h("div","log",fdw(new Date(d.at))+" · "+d.by+" covered for "+d.for)))}
boot();
</script></body></html>
