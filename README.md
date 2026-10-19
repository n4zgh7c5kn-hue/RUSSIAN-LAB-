<!DOCTYPE html>
<html lang="fr"><head><meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>Russian Lab by НайтСек</title>
<link href="https://fonts.googleapis.com/css2?family=Rubik:wght@400;600;800&display=swap" rel="stylesheet">
<style>
:root{--bg:#c9ced6;--p:#dde1e7;--b:#aab1bb;--t:#14171c;--m:#4d5560;--a:#c8261b;box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px)}
@media(prefers-color-scheme:dark){:root:not([data-theme=light]){--bg:#0f1114;--p:#181b20;--b:#2c3037;--t:#e4e7ec;--m:#8d949f;--a:#e03a2f}}
:root[data-theme=dark]{--bg:#0f1114;--p:#181b20;--b:#2c3037;--t:#e4e7ec;--m:#8d949f;--a:#e03a2f}
html{scroll-padding-top:env(safe-area-inset-top,0px)}
body{margin:0;font:400 15px/1.45 Rubik,system-ui,sans-serif;color:var(--t);background:radial-gradient(120% 60% at 50% 0,var(--p),var(--bg)),var(--bg)}
body::before{content:"";position:fixed;inset:0 0 auto;height:env(safe-area-inset-top,0px);background:var(--bg);z-index:10}
#sn{position:fixed;inset:0;width:100%;height:100%;pointer-events:none;z-index:100}
button{font:inherit;color:inherit;cursor:pointer}
header{position:sticky;top:env(safe-area-inset-top,0px);z-index:5;background:var(--bg);border-bottom:1px solid var(--b);padding:10px 14px}
.lg{display:flex;align-items:center;gap:10px;max-width:640px;margin:auto}
.lg b{display:block;font-weight:800;letter-spacing:.16em;line-height:1.1}
.lg small{color:var(--m);letter-spacing:.2em;font-size:11px}
.fl{display:block;width:30px;height:20px;border-radius:2px;background:linear-gradient(#fff 33%,#0039a6 33%,#0039a6 66%,#d52b1e 66%);box-shadow:0 0 0 1px var(--b)}
main{position:relative;z-index:2;max-width:640px;margin:auto;padding:12px 14px 110px}
.lb{display:flex;align-items:center;gap:8px;color:var(--m);font-size:12px;flex-wrap:wrap}
#lg{display:flex;gap:5px}
#lg button{background:var(--p);border:1px solid var(--b);border-radius:8px;padding:5px 9px;font-size:12px;font-weight:600}
#lg .on{background:var(--t);color:var(--bg)}
h2{font-size:22px;margin:14px 0 4px}
h2::after{content:"";display:block;width:42px;height:3px;background:var(--a);margin:6px 0 0}
.win h2::after{margin:6px auto 0}
h3{margin:18px 0 2px;color:var(--m);font-size:14px;font-weight:600}
.mu{color:var(--m);font-size:13px}
.bt,.card,.t,.win,.nd,.bb{background:var(--p);border:1px solid var(--b);box-shadow:0 6px 20px #0002}
.bt{display:block;width:100%;text-align:left;border-radius:12px;padding:12px 14px;margin:8px 0;transition:.2s}
.bt:active,.t:active{transform:scale(.96)}
.bt small{display:block;color:var(--m)}
.bt.ok{border-color:#3e9b5f}.bt.g{background:#2f7d4f;color:#fff}.bt.r{background:#a23a33;color:#fff}
.g2{display:grid;grid-template-columns:1fr 1fr;gap:8px}.g3{grid-template-columns:repeat(3,1fr)}
.card{display:flex;justify-content:space-between;align-items:center;gap:10px;border-radius:12px;padding:12px 14px;margin:8px 0}
.card b{font-size:20px}.card small{color:var(--m);margin-left:8px}.card em{display:block;color:var(--m);font-style:normal}
.sp{flex:none;width:38px;height:38px;border-radius:50%;background:var(--bg);border:1px solid var(--b)}
.al{display:grid;grid-template-columns:repeat(auto-fill,minmax(74px,1fr));gap:8px;margin-top:10px}
.t{border-radius:12px;padding:10px 2px;text-align:center}.t b{display:block;font-size:24px}.t small{color:var(--m)}.t.v{border-color:var(--a)}
.ch{display:flex;flex-direction:column}
.bb{max-width:86%;padding:10px 12px;border-radius:14px;margin:6px 0}.bb small{display:block;color:var(--m)}
.u{align-self:flex-end;background:var(--t);color:var(--bg)}
.win{text-align:center;padding:24px 10px;border-radius:16px;margin:10px 0}.big{font-size:52px}
.er{color:var(--a);font-weight:600}
.mm{position:relative;aspect-ratio:1/1.15;margin-top:10px}.mm svg{position:absolute;inset:0;width:100%;height:100%}
.mm line{stroke:var(--b);stroke-width:1.5;vector-effect:non-scaling-stroke}
.nd{position:absolute;transform:translate(-50%,-50%);width:29%;border-radius:12px;padding:6px 3px;font-size:11px;overflow-wrap:anywhere;text-align:center}
.nd b{display:block;font-size:13px}
.nd.c{background:var(--a);color:#fff;border:0;font-weight:800;font-size:13px;width:26%;border-radius:50%;aspect-ratio:1;display:grid;place-items:center}
.pb{height:4px;background:var(--b);border-radius:2px;margin:10px 0}.pb i{display:block;height:100%;background:var(--a);border-radius:2px;transition:width .4s}
#q{width:100%;box-sizing:border-box;background:var(--p);border:1px solid var(--b);color:var(--t);border-radius:12px;padding:14px;font:inherit;font-size:16px;margin:8px 0}
a{color:var(--t)}
footer{margin-top:26px;text-align:center;color:var(--m);font-size:12px}
nav{position:fixed;bottom:0;left:0;right:0;z-index:6;display:flex;background:var(--p);border-top:1px solid var(--b);padding-bottom:env(safe-area-inset-bottom,0px)}
nav button{flex:1;background:none;border:0;padding:8px 0 6px;color:var(--m);font-size:11px}
nav span{display:block;font-size:18px;font-weight:600}nav .on{color:var(--t);box-shadow:inset 0 2px var(--a)}
#in{position:fixed;inset:0;z-index:99;background:#08090b;color:#eceef1;display:grid;place-items:center;text-align:center;transition:opacity .9s,visibility .9s}
#in.x{opacity:0;visibility:hidden}
.fg{width:150px;height:100px;margin:0 auto 24px;display:grid;grid-template-rows:repeat(3,1fr);overflow:hidden;border-radius:3px;box-shadow:0 0 60px #fff3;transition:all 1s;animation:ri 1.4s backwards}
.fg i:nth-child(1){background:#fff}.fg i:nth-child(2){background:#0039a6}.fg i:nth-child(3){background:#d52b1e}
.m .fg{height:5px;width:min(260px,64vw);border-radius:0;margin-bottom:16px}
#nt{font:800 clamp(26px,9vw,52px) Rubik,sans-serif;letter-spacing:.4em;margin-right:-.4em;transition:letter-spacing 1s;animation:sp 1.6s .5s backwards}
.m #nt{letter-spacing:.1em;margin-right:0;animation:gl .7s}
#tt{margin-top:12px;color:#9aa1ab;font:600 15px Rubik,sans-serif;letter-spacing:.3em;opacity:0}
.m #tt{animation:up 1s 1s forwards}
#sk{position:absolute;bottom:calc(24px + env(safe-area-inset-bottom,0px));color:#6b727c;font-size:12px}
@keyframes ri{from{opacity:0;transform:translateY(40px) scale(.6);filter:blur(10px)}}
@keyframes sp{from{opacity:0;letter-spacing:1.2em;filter:blur(8px)}}
@keyframes gl{0%{text-shadow:-6px 0 #d52b1e,6px 0 #0039a6;transform:skewX(-14deg)}50%{text-shadow:5px 0 #d52b1e,-5px 0 #0039a6}100%{text-shadow:none}}
@keyframes up{from{opacity:0;transform:translateY(10px)}to{opacity:1;transform:none}}
@media(prefers-reduced-motion:reduce){#sn{display:none}}
</style></head><body>
<div id="in"><div class="st"><div class="fg"><i></i><i></i><i></i></div><div id="nt">NIGHTSEC</div><div id="tt">by НайтСек</div></div><small id="sk">toucher pour passer</small></div>
<canvas id="sn"></canvas>
<header><div class="lg"><i class="fl"></i><div><b>RUSSIAN LAB</b><small>by НайтСек</small></div></div></header>
<main><div class="lb">Je pars de : <div id="lg"></div></div><div id="v"></div>
<footer>Créé par НайтСек · TikTok <a href="https://www.tiktok.com/@ns.exe0101" target="_blank" rel="noopener">@ns.exe0101</a></footer></main>
<nav id="nav"></nav>
<script>
const $=s=>document.querySelector(s),LG=['fr','en','es','de','pt'],NM={fr:'français',en:'anglais',es:'espagnol',de:'allemand',pt:'portugais'};
let L='fr',tab='al',Q=null,K={i:0,h:1,e:'',m:0},S={};
try{S=JSON.parse(localStorage.getItem('rl'))||{}}catch(e){}
const sv=()=>{try{localStorage.setItem('rl',JSON.stringify(S))}catch(e){}};
const A='а a|б b|в v|г g|д d|е ye|ё yo|ж zh|з z|и i|й y|к k|л l|м m|н n|о o|п p|р r|с s|т t|у u|ф f|х kh|ц ts|ч ch|ш sh|щ shch|ъ ʺ|ы y|ь ʹ|э e|ю yu|я ya'.split('|').map(x=>x.split(' ')),M=Object.fromEntries(A);
const tr=s=>[...s].map((c,i,a)=>{const p=a[i-1];return c=='е'?(!p||' аеёиоуыэюяъь'.includes(p)?'ye':'e'):'ъь'.includes(c)?'':M[c]??c}).join('');
const D=`привет|salut|hi|hola|hallo|oi
спасибо|merci|thanks|gracias|danke|obrigado
да|oui|yes|sí|ja|sim
нет|non|no|no|nein|não
пожалуйста|s’il vous plaît|please|por favor|bitte|por favor
здравствуйте|bonjour|hello|buenos días|guten Tag|olá
до свидания|au revoir|goodbye|adiós|auf Wiedersehen|adeus
извините|pardon|sorry|perdón|Entschuldigung|desculpe
я|je|I|yo|ich|eu
ты|tu|you|tú|du|você
меня зовут|je m’appelle|my name is|me llamo|ich heiße|meu nome é
хорошо|bien|good|bien|gut|bem
вода|eau|water|agua|Wasser|água
хлеб|pain|bread|pan|Brot|pão
дом|maison|house|casa|Haus|casa
друг|ami|friend|amigo|Freund|amigo
любовь|amour|love|amor|Liebe|amor
книга|livre|book|libro|Buch|livro
город|ville|city|ciudad|Stadt|cidade
время|temps|time|tiempo|Zeit|tempo
мама|maman|mom|mamá|Mama|mamãe
школа|école|school|escuela|Schule|escola
работа|travail|work|trabajo|Arbeit|trabalho
снег|neige|snow|nieve|Schnee|neve
я понимаю|je comprends|I understand|entiendo|ich verstehe|eu entendo
я не понимаю|je ne comprends pas|I don’t understand|no entiendo|ich verstehe nicht|eu não entendo
как дела?|comment ça va ?|how are you?|¿qué tal?|wie geht’s?|como vai?
очень приятно|enchanté|nice to meet you|mucho gusto|freut mich|prazer
я люблю тебя|je t’aime|I love you|te quiero|ich liebe dich|eu te amo
сколько стоит?|combien ça coûte ?|how much is it?|¿cuánto cuesta?|wie viel kostet das?|quanto custa?
где туалет?|où sont les toilettes ?|where is the toilet?|¿dónde está el baño?|wo ist die Toilette?|onde fica o banheiro?
говорите медленнее|parlez plus lentement|speak more slowly|hable más despacio|sprechen Sie langsamer|fale mais devagar
я учу русский|j’apprends le russe|I’m learning Russian|aprendo ruso|ich lerne Russisch|estou aprendendo russo
добро пожаловать|bienvenue|welcome|bienvenido|willkommen|bem-vindo
доброе утро|bonjour (le matin)|good morning|buenos días|guten Morgen|bom dia
спокойной ночи|bonne nuit|good night|buenas noches|gute Nacht|boa noite
до завтра|à demain|see you tomorrow|hasta mañana|bis morgen|até amanhã`.split('\n').map(l=>l.split('|')),col=()=>1+LG.indexOf(L);
const LV=[['A1 Débutant',0,6,12],['A2 Intermédiaire',12,18,24],['B1 Avancé',24,30,37]];
const MP=[['Politesse',[0,1,4,5,6,7]],['La vie',[12,13,14,15,16,20]],['La ville',[17,18,19,21,22,23]]];
const CH=[
['Привет! Как тебя зовут?','Salut ! Comment tu t’appelles ?',[['Меня зовут Алекс.','Je m’appelle Alex.',1],['Спасибо, до свидания.','Merci, au revoir.']]],
['Очень приятно! Как дела?','Enchanté ! Comment ça va ?',[['Я хлеб.','Je suis du pain.'],['Хорошо, спасибо!','Bien, merci !',1]]],
['Ты говоришь по-русски?','Tu parles russe ?',[['Да, я учу русский.','Oui, j’apprends le russe.',1],['Меня зовут снег.','Je m’appelle neige.']]],
['Отлично! До завтра!','Super ! À demain !',[['Доброе утро!','Bonjour (le matin) !'],['До завтра!','À demain !',1]]]];
const cap=s=>s[0].toUpperCase()+s.slice(1),shuf=a=>[...a].sort(()=>Math.random()-.5);
const esc=s=>s.replace(/[&<>"]/g,c=>'&#'+c.charCodeAt(0)+';'),nz=s=>s.normalize('NFD').replace(/[\u0300-\u036f]/g,'').toLowerCase();
const GZ=()=>({fr:'Félicitations !',en:'Congratulations!',es:'¡Felicidades!',de:'Glückwunsch!',pt:'Parabéns!'}[L])+' Поздравляю!';
const say=(t,q)=>{try{q||speechSynthesis.cancel();const u=new SpeechSynthesisUtterance(t);u.lang='ru-RU';u.rate=.8;speechSynthesis.speak(u)}catch(e){}};
const card=i=>`<div class="card"><div><b>${cap(D[i][0])}</b><small>${tr(D[i][0])}</small><em>${D[i][col()]}</em></div><button class="sp" data-s="${D[i][0]}">🔊</button></div>`;
const nq=()=>{const i=Q.w[Q.n],c=col();Q.o=shuf([i,...shuf(D.map((_,x)=>x).filter(x=>x!=i&&D[x][c]!=D[i][c])).slice(0,3)])};
const V={
al:()=>`<h2>Alphabet russe</h2><p class="mu">Touche une lettre pour l’écouter. Contour rouge : voyelle.</p><button class="bt" data-all="1">▶ Tout écouter</button><div class="al">${A.map(x=>`<button class="t${'аеёиоуыэюя'.includes(x[0])?' v':''}" data-s="${x[0]}"><b>${x[0].toUpperCase()}${x[0]}</b><small>${x[1]}</small></button>`).join('')}</div>`,
le:()=>{
if(!Q)return `<h2>Leçons</h2><p class="mu">${Object.keys(S).length}/6 leçons terminées</p>`+LV.map((v,k)=>`<h3>${v[0]}</h3><div class="g2">${[0,1].map(j=>{const d=S[k+'-'+j];return `<button class="bt${d!=null?' ok':''}" data-l="${k}-${j}">Leçon ${j+1}<small>${v[2+j]-v[1+j]} mots${d!=null?', réussi '+d:''}</small></button>`}).join('')}</div>`).join('');
const bk='<button class="sp" data-b="1">←</button>';
if(Q.r)return `<div class="win"><div class="big">🎉</div><h2>${GZ()}</h2><p>Leçon terminée : ${Q.s}/${Q.w.length}</p></div><button class="bt" data-b="1">Retour aux leçons</button>`;
if(Q.o){const i=Q.w[Q.n];return `${bk}<div class="pb"><i style="width:${Q.n/Q.w.length*100}%"></i></div><div class="card"><div><b>${cap(D[i][0])}</b><small>${tr(D[i][0])}</small></div><button class="sp" data-s="${D[i][0]}">🔊</button></div>`+Q.o.map(x=>`<button class="bt${Q.p!=null?(x==i?' g':x==Q.p?' r':''):''}" data-a="${x}">${D[x][col()]}</button>`).join('')}
return `${bk}<h3>${LV[Q.lv][0]}, leçon ${Q.j+1}</h3>`+Q.w.map(card).join('')+'<button class="bt" data-q="1">Commencer le quiz</button>'},
di:()=>{let h=`<h2>Dialogue</h2><button class="bt" data-h="1">Aide en français : ${K.h?'activée':'désactivée'}</button><div class="ch">`;
for(let j=0;j<=K.i&&j<CH.length;j++){const s=CH[j];h+=`<div class="bb"><div>${s[0]} <button class="sp" data-s="${s[0]}" style="width:30px;height:30px">🔊</button></div>${K.h?`<small>${tr(s[0])}<br>🇫🇷 ${s[1]}</small>`:''}</div>`;if(j<K.i)h+=`<div class="bb u">${s[2].find(o=>o[2])[0]}</div>`}
h+='</div>';
if(K.i<CH.length)h+=CH[K.i][2].map((o,k)=>`<button class="bt" data-o="${k}">${o[0]}${K.h?`<small>${o[1]}</small>`:''}</button>`).join('')+(K.e?`<p class="er">${K.e}</p>`:'');
else h+=`<div class="win"><div class="big">🎉</div><h2>${GZ()}</h2><p>Conversation terminée !</p></div><button class="bt" data-r="1">Recommencer</button>`;
return h},
ca:()=>{const[n,w]=MP[K.m],c=w.length,P=k=>{const a=k/c*6.283-1.571;return[50+34*Math.cos(a),50+40*Math.sin(a)]};
return `<h2>Cartes mentales</h2><div class="g2 g3">${MP.map((x,k)=>`<button class="bt${k==K.m?' ok':''}" data-m="${k}" style="text-align:center">${x[0]}</button>`).join('')}</div><div class="mm"><svg viewBox="0 0 100 100" preserveAspectRatio="none">${w.map((_,k)=>`<line x1="50" y1="50" x2="${P(k)[0]}" y2="${P(k)[1]}"></line>`).join('')}</svg><div class="nd c" style="left:50%;top:50%">${n}</div>${w.map((i,k)=>`<button class="nd" style="left:${P(k)[0]}%;top:${P(k)[1]}%" data-s="${D[i][0]}"><b>${cap(D[i][0])}</b>${tr(D[i][0])}<br>${D[i][col()]}</button>`).join('')}</div>`},
se:()=>`<h2>Dictionnaire</h2><input id="q" placeholder="Mot en ${NM[L]}, traduit en russe" autocomplete="off"><div id="res"></div>`};
function fnd(){const raw=$('#q').value.trim(),q=nz(raw),r=$('#res');if(!q){r.innerHTML='';return}
const m=D.map((_,i)=>i).filter(i=>nz(D[i][col()]).includes(q)||D[i][0].includes(q));
r.innerHTML=m.length?m.map(card).join(''):`<p class="mu">Ce mot n’est pas dans le mini-dictionnaire (37 mots).</p><a href="https://translate.google.com/?sl=${L}&tl=ru&text=${encodeURIComponent(raw)}&op=translate" target="_blank" rel="noopener">Chercher « ${esc(raw)} » sur Google Traduction</a>`}
const TB=[['al','Аб','Alphabet'],['le','📚','Leçons'],['di','💬','Dialogue'],['ca','🧠','Cartes'],['se','🔎','Dico']];
function render(){$('#v').innerHTML=V[tab]();
$('#nav').innerHTML=TB.map(t=>`<button data-t="${t[0]}" class="${t[0]==tab?'on':''}"><span>${t[1]}</span>${t[2]}</button>`).join('');
$('#lg').innerHTML=LG.map(g=>`<button data-g="${g}" class="${g==L?'on':''}">${g.toUpperCase()}</button>`).join('')}
document.addEventListener('input',e=>{if(e.target.id=='q')fnd()});
document.addEventListener('click',e=>{const t=e.target.closest('button');if(!t)return;const d=t.dataset;
if(d.t){tab=d.t;Q=null;scrollTo(0,0)}
else if(d.g)L=d.g;
else if(d.s)return say(d.s);
else if(d.all){try{speechSynthesis.cancel()}catch(x){}A.forEach(x=>say(x[0],1));return}
else if(d.l){const[k,j]=d.l.split('-').map(Number),v=LV[k];Q={id:d.l,lv:k,j,w:Array.from({length:v[2+j]-v[1+j]},(_,x)=>v[1+j]+x),n:0,s:0,p:null,o:null,r:0}}
else if(d.q){Q.w=shuf(Q.w);Q.n=0;Q.s=0;nq()}
else if(d.a&&Q&&Q.p==null){const q=Q,i=q.w[q.n];q.p=+d.a;say(D[i][0]);if(q.p==i)q.s++;
setTimeout(()=>{if(Q!==q)return;q.n++;q.p=null;if(q.n>=q.w.length){q.r=1;q.o=null;S[q.id]=Math.max(S[q.id]||0,q.s);sv()}else nq();render()},900)}
else if(d.b)Q=null;
else if(d.h)K.h=!K.h;
else if(d.o){const o=CH[K.i][2][+d.o];say(o[0]);if(o[2]){K.i++;K.e='';if(K.i<CH.length)say(CH[K.i][0],1)}else K.e='Pas tout à fait… écoute et réessaie 🙂'}
else if(d.r){K.i=0;K.e=''}
else if(d.m)K.m=+d.m;
else return;
render()});
render();
(()=>{const c=$('#sn'),x=c.getContext('2d');let w,h;const R=()=>{w=c.width=innerWidth;h=c.height=innerHeight};R();addEventListener('resize',R);
const F=Array.from({length:110},()=>({x:Math.random()*innerWidth,y:Math.random()*innerHeight,r:Math.random()*2.3+.6,v:Math.random()*.9+.3,p:Math.random()*6}));
(function d(){x.clearRect(0,0,w,h);x.fillStyle='#fff';x.shadowColor='#5a6475';x.shadowBlur=4;x.beginPath();
F.forEach(f=>{f.y+=f.v;f.p+=.01;f.x+=Math.sin(f.p)*.4;if(f.y>h+5){f.y=-5;f.x=Math.random()*w}x.moveTo(f.x+f.r,f.y);x.arc(f.x,f.y,f.r,0,7)});x.fill();requestAnimationFrame(d)})()})();
const scr=(e,s,ms)=>{const n=performance.now(),g='ABEGKLMPRSЖЩФЦЯЮ';(function f(t){const p=Math.min(1,(t-n)/ms);e.textContent=[...s].map((c,i)=>c==' '||i<p*s.length?c:g[Math.random()*g.length|0]).join('');if(p<1)requestAnimationFrame(f)})(n)};
setTimeout(()=>{$('#in').classList.add('m');scr($('#nt'),'RUSSIAN LAB',1000)},2300);
const out=()=>$('#in').classList.add('x');setTimeout(out,5400);$('#in').onclick=out;
</script></body></html>
