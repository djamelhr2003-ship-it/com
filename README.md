<!DOCTYPE html>
<html lang="ar" dir="rtl" class="js">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>علامتي | Mon Brand - المتجر الجزائري</title>
<link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Cairo:wght@400;600;800&family=Reem+Kufi:wght@600;700&display=swap">
<style>
:root{--dz-bg:#090d0b;--dz-card:rgba(255,255,255,.045);--dz-tx:#f5f2ea;--dz-mu:#9ba79f;--dz-gd:#d9b65c;--dz-gr:#006233;--dz-rd:#d21034;--dz-bd:rgba(255,255,255,.1)}
body,.gradient,.color-scheme-1,.color-scheme-2,.color-scheme-3{background:var(--dz-bg)!important;color:var(--dz-tx)!important;font-family:Cairo,Tahoma,Arial,sans-serif!important}
h1,h2,h3,.h0,.h1,.h2,.h3,.card__heading,.header__heading-link{font-family:"Reem Kufi",Cairo,sans-serif!important;color:var(--dz-tx)}

.header-wrapper,.shopify-section-header-sticky .header-wrapper{background:rgba(9,13,11,.7)!important;backdrop-filter:blur(10px);border-bottom:1px solid var(--dz-bd)}
.header__menu-item,.header__icon{color:var(--dz-tx)!important}
.card-wrapper,.card,.card--card,.product-card-wrapper .card{background:var(--dz-card)!important;border:1px solid var(--dz-bd)!important;border-radius:22px!important;overflow:hidden;transition:transform .3s,box-shadow .3s}
.card-wrapper:hover{transform:translateY(-6px);box-shadow:0 16px 32px rgba(0,0,0,.45),0 0 0 1px rgba(217,182,92,.35)}
.button,.shopify-challenge__button,.customer button{background:linear-gradient(90deg,#d9b65c,#f2d98c)!important;color:#241c06!important;font-weight:800;border-radius:12px!important;border:0!important;cursor:pointer}
.button:after,.button:before{display:none!important}
.field__input,.select__select,.customer .field input{background:rgba(255,255,255,.05)!important;color:var(--dz-tx)!important;border-radius:10px}
.footer{background:#050806!important;border-top:1px solid var(--dz-bd)}
.badge{background:var(--dz-rd)!important;color:#fff!important}
h2.title:after,.collection-hero__title:after{content:"";display:block;width:90px;height:4px;margin:8px auto 0;border-radius:4px;background:linear-gradient(90deg,var(--dz-gd),transparent)}

/* ===== DZ sections ===== */
.dz-hero{position:relative;overflow:hidden;color:#fff;text-align:center;padding:96px 16px 60px;background:#090d0b}
.dz-hero:before{content:"";position:absolute;inset:-25%;background:conic-gradient(from 0deg,#006233,#d9b65c55,#d21034,#006233);filter:blur(100px);opacity:.35;animation:dzspin 26s linear infinite}
@keyframes dzspin{to{transform:rotate(1turn)}}@keyframes dzfl{50%{transform:translateY(-14px)}}@keyframes dzup{from{opacity:0;transform:translateY(24px)}}
@keyframes dzmq{to{transform:translateX(50%)}}@keyframes dzmq2{to{transform:translateX(-50%)}}@keyframes dzpulse{50%{transform:scale(1.08)}}
.dz-in{position:relative;z-index:2;max-width:700px;margin:auto}
.dz-tag{display:inline-block;border:1px solid rgba(217,182,92,.5);color:var(--dz-gd);border-radius:99px;padding:3px 16px;font-size:.9rem;margin-bottom:14px;animation:dzup .8s both}
.dz-hero h1{font-size:clamp(2.4rem,9vw,4.8rem);line-height:1.15;margin:0 0 10px;font-weight:800;background:linear-gradient(180deg,#fff 30%,#d9b65c);-webkit-background-clip:text;background-clip:text;-webkit-text-fill-color:transparent;animation:dzup .9s .15s both}
.dz-hero p{margin:0;opacity:.9;animation:dzup .9s .3s both}
.dz-doors{position:relative;z-index:2;max-width:780px;margin:36px auto 0;display:grid;grid-template-columns:1fr 1fr;gap:14px}
.dz-door{display:block;border-radius:22px;padding:30px 10px;color:#fff!important;text-decoration:none;border:1px solid rgba(255,255,255,.18);box-shadow:0 12px 40px rgba(0,0,0,.4);transition:transform .3s;animation:dzup .9s .45s both}
.dz-door:hover{transform:translateY(-8px)}.dz-door.w{background:linear-gradient(150deg,rgba(210,16,52,.8),rgba(80,5,25,.9))}.dz-door.m{background:linear-gradient(150deg,rgba(0,98,51,.85),rgba(5,38,24,.9))}
.dz-door span{display:block;font-size:2.6rem;animation:dzfl 6s ease-in-out infinite}.dz-door b{display:block;font-size:1.4rem}.dz-door small{opacity:.85}
.dz-mq{overflow:hidden;white-space:nowrap;padding:12px 0;background:#0d1410;border-block:1px solid var(--dz-bd)}
.dz-mq div{display:inline-block;animation:dzmq 32s linear infinite;color:var(--dz-gd);font-weight:600}html[dir=ltr] .dz-mq div{animation-name:dzmq2}.dz-mq i{font-style:normal;margin:0 22px}
.dz-sec{max-width:1100px;margin:auto;padding:70px 16px}
.dz-hd{text-align:center;margin-bottom:34px}.dz-hd small{display:block;color:var(--dz-gd);letter-spacing:.12em;font-weight:600}
.dz-hd h2{font-size:clamp(1.7rem,5vw,2.6rem);margin:6px 0}.dz-hd p{color:var(--dz-mu);margin:0}
.dz-grid{display:grid;gap:16px;grid-template-columns:repeat(auto-fit,minmax(220px,1fr))}
.dz-card{background:var(--dz-card);border:1px solid var(--dz-bd);border-radius:22px;padding:24px;backdrop-filter:blur(10px);transition:transform .3s,border-color .3s}
.dz-card:hover{transform:translateY(-6px);border-color:rgba(217,182,92,.45)}
.dz-ic{font-size:2.2rem;display:block;margin-bottom:6px}.dz-card h3{margin:0 0 4px;font-size:1.15rem}.dz-card p{margin:0;color:var(--dz-mu);font-size:.92rem}
.dz-rv{transition:all .8s}.js .dz-rv{opacity:0;transform:translateY(34px)}.js .dz-rv.on{opacity:1;transform:none}
.dz-btn{display:inline-block;background:linear-gradient(90deg,#d9b65c,#f2d98c);color:#241c06!important;font-weight:800;border-radius:14px;padding:13px 28px;text-decoration:none;box-shadow:0 8px 24px rgba(217,182,92,.3);transition:transform .2s;border:0;cursor:pointer}
.dz-btn:hover{transform:translateY(-3px)}
.dz-st{color:var(--dz-gd);letter-spacing:2px;margin-bottom:6px}.dz-who{margin-top:12px;font-weight:700}.dz-who small{display:block;color:var(--dz-mu);font-weight:400}
.dz-faq details{background:var(--dz-card);border:1px solid var(--dz-bd);border-radius:16px;margin-bottom:10px;padding:14px 18px}.dz-faq summary{cursor:pointer;font-weight:700;list-style:none}.dz-faq summary:after{content:"+";float:inline-end;color:var(--dz-gd);font-size:1.3rem}.dz-faq details[open] summary:after{content:"–"}.dz-faq p{color:var(--dz-mu);margin:10px 0 0}
.dz-wa{position:fixed;inset-inline-start:16px;bottom:calc(16px + env(safe-area-inset-bottom,0px));z-index:50;width:56px;height:56px;border-radius:50%;background:#25d366;display:grid;place-items:center;box-shadow:0 8px 24px rgba(37,211,102,.45);animation:dzpulse 2.6s ease-in-out infinite;color:#fff;text-decoration:none;font-size:1.7rem}
@media(prefers-reduced-motion:reduce){.dz-hero:before,.dz-mq div,.dz-wa,.dz-door span{animation:none!important}.js .dz-rv{opacity:1;transform:none}}

html{box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px);scroll-behavior:smooth}
*{box-sizing:border-box}body{margin:0;line-height:1.6;overflow-x:hidden}
.hd{position:sticky;top:env(safe-area-inset-top,0px);z-index:30;display:flex;align-items:center;justify-content:space-between;padding:10px 16px;background:rgba(9,13,11,.7);backdrop-filter:blur(10px);border-bottom:1px solid var(--dz-bd)}
.hd b{font-family:"Reem Kufi",Cairo,sans-serif;font-size:1.4rem;color:var(--dz-gd)}.hd div{display:flex;gap:12px;align-items:center}
.hd a{color:var(--dz-tx)!important;text-decoration:none;font-size:.9rem;font-weight:600}
.lg2{background:rgba(255,255,255,.08);border:1px solid var(--dz-bd);color:var(--dz-tx);border-radius:99px;padding:5px 14px;font:inherit;cursor:pointer}
.ft{background:#050806;border-top:1px solid var(--dz-bd);text-align:center;padding:34px 16px;color:var(--dz-mu)}.ft b{color:var(--dz-gd)}
.pc{padding:16px;display:flex;flex-direction:column;justify-content:space-between}.pc svg{width:100%;height:150px}.pc .pvv{border-radius:14px;background:radial-gradient(circle at 50% 40%,rgba(217,182,92,.22),transparent 70%)}
.pc h3{margin:8px 0 2px;font-size:1.1rem}.pc .pr{color:var(--dz-gd);font-weight:800;margin-bottom:12px}.pc .ct{font-size:.75rem;color:#ff8a9c}
.bar{background:linear-gradient(90deg,var(--dz-gr),#0a8a4a);text-align:center;font-size:.85rem;padding:6px;color:#fff}

/* نموذج الطلب المنبثق (Modal) */
.modal{position:fixed;inset:0;background:rgba(0,0,0,.8);backdrop-filter:blur(8px);z-index:100;display:grid;place-items:center;padding:16px;opacity:0;pointer-events:none;transition:opacity .3s}
.modal.active{opacity:1;pointer-events:auto}
.modal-box{background:#111814;border:1px solid var(--dz-bd);border-radius:24px;width:100%;max-width:450px;padding:24px;box-shadow:0 20px 40px rgba(0,0,0,.6);position:relative}
.modal-box h3{margin-top:0;color:var(--dz-gd);font-family:"Reem Kufi",Cairo,sans-serif}
.form-group{margin-bottom:14px}
.form-group label{display:block;margin-bottom:6px;font-size:.9rem;color:var(--dz-mu)}
.form-control{width:100%;background:rgba(255,255,255,.05);border:1px solid var(--dz-bd);border-radius:10px;padding:10px 14px;color:var(--dz-tx);font-family:inherit;font-size:1rem}
.form-control:focus{outline:none;border-color:var(--dz-gd)}
.close-modal{position:absolute;inset-inline-end:18px;top:18px;background:none;border:none;color:var(--dz-mu);font-size:1.5rem;cursor:pointer}
</style>
</head>
<body>
<div id="app"></div>

<!-- نافذة الطلب المنبثقة -->
<div class="modal" id="orderModal">
  <div class="modal-box">
    <button class="close-modal" onclick="closeOrderModal()">×</button>
    <h3>إتمام الطلب (الدفع عند الاستلام 🇩🇿)</h3>
    <p id="selectedProductTitle" style="color:var(--dz-gd);margin-top:0;font-weight:bold;"></p>
    <form id="checkoutForm" onsubmit="submitOrder(event)">
      <div class="form-group">
        <label>الاسم الكامل:</label>
        <input type="text" id="custName" class="form-control" required placeholder="مثال: أمين جزائري">
      </div>
      <div class="form-group">
        <label>رقم الهاتف:</label>
        <input type="tel" id="custPhone" class="form-control" required placeholder="مثال: 0612345678">
      </div>
      <div class="form-group">
        <label>الولاية:</label>
        <select id="custWilaya" class="form-control" required>
          <option value="">اختر ولايتك...</option>
          <option value="01 - أدرار">01 - أدرار</option>
          <option value="02 - الشلف">02 - الشلف</option>
          <option value="16 - الجزائر العاصمة">16 - الجزائر العاصمة</option>
          <option value="31 - وهران">31 - وهران</option>
          <option value="25 - قسنطينة">25 - قسنطينة</option>
          <!-- وباقي الولايات -->
          <option value="أخرى (سيتم تحديدها بالهاتف)">ولاية أخرى</option>
        </select>
      </div>
      <div class="form-group">
        <label>العنوان بالتفصيل:</label>
        <input type="text" id="custAddress" class="form-control" required placeholder="البلدية، الحي...">
      </div>
      <button type="submit" class="dz-btn" style="width:100%;margin-top:10px;text-align:center;">تأكيد الطلب عبر واتساب 🛒</button>
    </form>
  </div>
</div>

<script>
// ضع رقم واتساب الخاص بك هنا (بدون علامة + وبإدراج رمز الدولة 213 بدون الصفر الأول، مثلاً: 213600000000)
var MY_WHATSAPP_NUMBER = "213600000000"; 

var L=(function(){try{return localStorage.getItem("l")||"ar"}catch(e){return"ar"}})();
function tee(c){return '<svg viewBox="0 0 200 160"><path d="M70 10 L30 30 L8 70 L36 84 L48 66 L48 150 L152 150 L152 66 L164 84 L192 70 L170 30 L130 10 Q100 32 70 10Z" fill="'+c+'" stroke="rgba(0,0,0,.25)" stroke-width="2"/><circle cx="100" cy="85" r="20" fill="none" stroke="#d9b65c" stroke-width="3"/></svg>'}
function robe(c){return '<svg viewBox="0 0 200 220"><path d="M80 8Q100 24 120 8L152 24L192 122L166 132L152 98L158 214L42 214L48 98L34 132L8 122L48 24Z" fill="'+c+'" stroke="rgba(0,0,0,.25)" stroke-width="2"/><path d="M100 24V212M52 196H148M52 176H148" stroke="#c9a24b" stroke-width="2" stroke-dasharray="4 4" fill="none"/><circle cx="100" cy="110" r="9" fill="none" stroke="#c9a24b" stroke-width="2"/></svg>'}

var currentProductToOrder = "";

function openOrderModal(productName, price) {
  currentProductToOrder = productName + " (" + price + " دج)";
  document.getElementById("selectedProductTitle").innerText = "المنتج: " + currentProductToOrder;
  document.getElementById("orderModal").classList.add("active");
}

function closeOrderModal() {
  document.getElementById("orderModal").classList.remove("active");
}

function submitOrder(e) {
  e.preventDefault();
  var name = document.getElementById("custName").value;
  var phone = document.getElementById("custPhone").value;
  var wilaya = document.getElementById("custWilaya").value;
  var address = document.getElementById("custAddress").value;

  var msg = "السلام عليكم، أريد طلب هذا المنتج:%0A" +
            "🛍 *المنتج:* " + encodeURIComponent(currentProductToOrder) + "%0A" +
            "👤 *الاسم:* " + encodeURIComponent(name) + "%0A" +
            "📞 *الهاتف:* " + encodeURIComponent(phone) + "%0A" +
            "📍 *الولاية:* " + encodeURIComponent(wilaya) + "%0A" +
            "🏠 *العنوان:* " + encodeURIComponent(address) + "%0A" +
            "💵 *الدفع:* عند الاستلام";

  var url = "https://wa.me/" + MY_WHATSAPP_NUMBER + "?text=" + msg;
  window.open(url, "_blank");
  closeOrderModal();
}

function R(){
 var f=L==="fr",t=function(a,b){return f?b:a};
 document.documentElement.dir=f?"ltr":"rtl";document.documentElement.lang=L;
 var tk=t("طباعة بالحرارة|طرز بالمكينة|الدفع عند الاستلام|توصيل لـ 69 ولاية","Transfert thermique|Broderie machine|Paiement à la livraison|Livraison 69 wilayas").split("|"),tkh="";
 for(var i=0;i<2;i++)tk.forEach(function(x){tkh+="<i>✦</i>"+x});
 var trust=[["🚚","توصيل لـ 69 ولاية","Livraison 69 wilayas","نوصل طلبك لباب بيتك","Chez vous, partout en Algérie"],["💵","الدفع عند الاستلام","Paiement à la livraison","تدفع بعد استلام طلبك","Vous payez à la réception"],["🧵","طرز بالمكينة بدقة","Broderie machine précise","غرزات متينة وتفاصيل راقية","Points solides, finitions soignées"],["🎨","لوقو بطابعك","Votre propre logo","حرارة أو طرز حسب اختيارك","Thermique ou broderie, au choix"]];
 var prods=[["عباية دبي","Abaya Dubaï","عباءات","Abayas","#1b1b1b",6000,1],["كراكو","Karakou","لباس تقليدي","Traditionnel","#d21034",12000,1],["تريكو أوفرسايز","T-shirt oversize","تريكوات","T-shirts","#f4f1e8",1600,0],["بولو","Polo","تريكوات","T-shirts","#006233",1800,0]];
 var cmp=[["♨️","الطباعة بالحرارة","Transfert thermique","الأنسب سعراً","Meilleur prix","ألوان زاهية ودقيقة|تنفيذ سريع","Couleurs vives et précises|Rapide"],["🧵","الطرز بالمكينة","Broderie machine","أغلى بـ 600 دج","+600 DA","مظهر فاخر وملمس بارز|تدوم لسنوات","Rendu premium en relief|Durable"]];
 var faq=[["كم مدة التوصيل؟","Quel est le délai de livraison ?","من 2 إلى 4 أيام حسب الولاية.","De 2 à 4 jours selon la wilaya."],["هل الدفع عند الاستلام؟","Le paiement se fait-il à la livraison ?","نعم، تدفع عند استلام طلبك للمندوب.","Oui, vous payez à la réception."]];

 var h='<div class="bar">'+t("🇩🇿 صنع في الجزائر · الدفع عند الاستلام","🇩🇿 Made in Algeria · Paiement à la livraison")+'</div>'+
 '<div class="hd"><b>'+t("علامتي","Mon Brand")+'.dz</b><div><a href="#sh">'+t("المتجر","Boutique")+'</a><button class="lg2" id="lb">'+(f?"العربية":"Français")+'</button></div></div>'+
 '<div class="dz-hero"><div class="dz-in"><span class="dz-tag">'+t("🇩🇿 صنع في الجزائر · نوصل لـ 69 ولاية","🇩🇿 Made in Algeria · Livraison 69 wilayas")+'</span><h1>'+t("أزياء مطرّزة ومطبوعة بلمسة جزائرية","Mode brodée et imprimée, signée Algérie")+'</h1><p>'+t("عباءات، لباس تقليدي، وتريكوات بالطباعة الحرارية أو الطرز بالمكينة.","Abayas, tenues traditionnelles et t-shirts.")+'</p></div>'+
 '<div class="dz-doors"><a class="dz-door w" href="#sh"><span>👗</span><b>'+t("للنساء","Femmes")+'</b><small>'+t("عباءات · لباس تقليدي","Abayas · Traditionnel")+'</small></a><a class="dz-door m" href="#sh"><span>👕</span><b>'+t("للرجال","Hommes")+'</b><small>'+t("تريكوات · بولو","T-shirts · Polos")+'</small></a></div></div>'+
 '<div class="dz-mq"><div>'+tkh+'</div></div>'+
 '<div class="dz-sec"><div class="dz-grid">'+trust.map(function(x){return '<div class="dz-card dz-rv"><span class="dz-ic">'+x[0]+'</span><h3>'+t(x[1],x[2])+'</h3><p>'+t(x[3],x[4])+'</p></div>'}).join("")+'</div></div>'+
 '<div class="dz-sec" id="sh"><div class="dz-hd dz-rv"><small>'+t("مختارات","Sélection")+'</small><h2>'+t("الأكثر طلباً","Les plus demandés")+'</h2></div><div class="dz-grid">'+
 prods.map(function(p){
   return '<div class="dz-card pc dz-rv"><div class="pvv">'+(p[6]?robe(p[4]):tee(p[4]))+'</div><span class="ct">'+t(p[2],p[3])+'</span><h3>'+t(p[0],p[1])+'</h3><div class="pr">'+p[5].toLocaleString("fr-DZ")+' '+t("دج","DA")+'</div><button class="dz-btn" onclick="openOrderModal(\''+p[0]+'\', '+p[5 కుమార్)+')">'+t("اطلب الآن 🛒","Commander 🛒")+'</button></div>'
 }).join("")+
 '</div></div>'+
 '<div class="dz-sec dz-cmp"><div class="dz-hd dz-rv"><small>'+t("اختر أسلوبك","Style")+'</small><h2>'+t("حرارة أم طرز؟","Thermique ou broderie ?")+'</h2></div><div class="dz-grid" style="grid-template-columns:repeat(auto-fit,minmax(280px,1fr))">'+cmp.map(function(c){return '<div class="dz-card dz-rv"><span class="dz-ic">'+c[0]+'</span><span class="dz-pr">'+t(c[3],c[4])+'</span><h3>'+t(c[1],c[2])+'</h3></div>'}).join("")+'</div></div>'+
 '<div class="dz-sec dz-faq" style="max-width:780px"><div class="dz-hd dz-rv"><h2>'+t("أسئلة شائعة","FAQ")+'</h2></div>'+faq.map(function(q){return '<details class="dz-rv"><summary>'+t(q[0],q[1])+'</summary><p>'+t(q[2],q[3])+'</p></details>'}).join("")+'</div>'+
 '<div class="ft"><b>'+t("علامتي","Mon Brand")+'</b> · '+t("الجزائر","Algérie")+' 🇩🇿<br>'+t("الدفع عند الاستلام · توصيل لكل الولايات","Paiement à la livraison")+'</div>'+
 '<a class="dz-wa" href="https://wa.me/'+MY_WHATSAPP_NUMBER+'" aria-label="WhatsApp" target="_blank">💬</a>';
 
 document.getElementById("app").innerHTML=h;
 document.getElementById("lb").onclick=function(){L=f?"ar":"fr";try{localStorage.setItem("l",L)}catch(e){}R();window.scrollTo(0,0)};
 var io=new IntersectionObserver(function(es){es.forEach(function(e){if(e.isIntersecting){e.target.classList.add("on");io.unobserve(e.target)}})},{threshold:.1});
 document.querySelectorAll(".dz-rv").forEach(function(e){io.observe(e)});
}
R();
</script>
</body>
</html>
