<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>do you still love me?</title>
<link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Pixelify+Sans:wght@500;700&display=swap">
<style>
:root{--bg1:#f6d9ea;--bg2:#f1e4f3;--ink:#c2288a;--soft:#a77a98;--btn1:#f7a6d0;--btn2:#e06bb0;--btnink:#fff;--spark:rgba(255,255,255,.8);
  box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px)}
@media (prefers-color-scheme:dark){:root:not([data-theme="light"]){--bg1:#2a1326;--bg2:#1d1022;--ink:#ff7cc8;--soft:#b98aae;--spark:rgba(255,200,240,.35)}}
html,body{height:100%;margin:0}
body{background:linear-gradient(160deg,var(--bg1),var(--bg2));font-family:"Pixelify Sans",ui-monospace,monospace;color:var(--ink);overflow:hidden;position:relative}
.spark{position:absolute;border-radius:50%;background:var(--spark);filter:blur(6px);animation:float 9s ease-in-out infinite;pointer-events:none}
@keyframes float{0%,100%{transform:translateY(0) scale(1);opacity:.5}50%{transform:translateY(-30px) scale(1.2);opacity:1}}
main{position:relative;height:100%;display:flex;flex-direction:column;align-items:center;justify-content:center;gap:10px;text-align:center;padding:20px}
h1{font-size:clamp(28px,8vw,46px);margin:0;font-weight:700;letter-spacing:.5px}
.sub{font-size:13px;color:var(--soft);margin:0 0 14px}
.row{display:flex;gap:14px;align-items:center;justify-content:center;min-height:52px;position:relative}
button{font:inherit;font-size:16px;color:var(--btnink);border:0;border-radius:999px;padding:10px 26px;cursor:pointer;
  background:linear-gradient(var(--btn1),var(--btn2));box-shadow:0 3px 0 rgba(150,40,110,.35);transition:transform .25s,opacity .3s}
button:active{transform:translateY(2px)}
#no{position:relative}
#no.gone{opacity:0;pointer-events:none;transform:scale(0)}
.hint{font-size:13px;color:var(--soft);min-height:18px;opacity:0;transition:opacity .4s}
.hint.show{opacity:1}
#win{display:none;flex-direction:column;align-items:center;gap:14px;animation:pop .5s ease}
#win .rose{font-size:96px;line-height:1}
#win p{font-size:clamp(16px,4.5vw,22px);margin:0;font-weight:700}
@keyframes pop{from{transform:scale(.6);opacity:0}to{transform:scale(1);opacity:1}}
</style>
</head>
<body>
<main>
  <div id="ask">
    <h1>do you still love me?</h1>
    <p class="sub">be honest</p>
    <div class="row">
      <button id="yes">Yes</button>
      <button id="no">No</button>
    </div>
    <p class="hint" id="hint">shut up and say yes</p>
  </div>
  <div id="win">
    <div class="rose">🌹</div>
    <p>I knew it, you are literally obsessed with me</p>
  </div>
</main>
<script>
// sparkles
for(let i=0;i<22;i++){
  const s=document.createElement('div');s.className='spark';
  const d=6+Math.random()*16;
  s.style.cssText=`width:${d}px;height:${d}px;left:${Math.random()*100}%;top:${Math.random()*100}%;animation-delay:${-Math.random()*9}s`;
  document.body.prepend(s);
}
const yes=document.getElementById('yes'), no=document.getElementById('no'), hint=document.getElementById('hint');
let tries=0;
function dodge(e){
  if(no.classList.contains('gone'))return;
  e.preventDefault();
  tries++;
  if(tries>=3){                       // after 3 attempts the No button disappears
    no.classList.add('gone');
    hint.classList.add('show');
    yes.style.transform='scale(1.15)';
    return;
  }
  const x=(Math.random()-.5)*140, y=(Math.random()-.5)*80;
  no.style.transform=`translate(${x}px,${y}px) scale(${1-tries*0.2})`;
}
no.addEventListener('mouseenter',dodge);
no.addEventListener('touchstart',dodge,{passive:false});
no.addEventListener('click',dodge);
yes.addEventListener('click',()=>{
  document.getElementById('ask').style.display='none';
  document.getElementById('win').style.display='flex';
});
</script>
</body>
</html>
