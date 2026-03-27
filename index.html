<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>رادار الأسعار المباشر</title>

<style>
body{
    background:#000;
    color:#fff;
    font-family:Tahoma, Arial, sans-serif;
    text-align:center;
    margin:0;
    padding:0;
}

h1{
    color:gold;
    margin:20px 10px 10px;
    font-size:32px;
}

.top-box{
    width:95%;
    max-width:1100px;
    margin:15px auto;
    background:#111;
    border:1px solid #333;
    border-radius:16px;
    padding:18px;
    box-sizing:border-box;
}

.top-title{
    color:#FFD700;
    font-size:26px;
    margin-bottom:18px;
    font-weight:bold;
}

.controls{
    display:flex;
    flex-wrap:wrap;
    justify-content:center;
    gap:14px;
    margin-bottom:20px;
}

.control-item{
    background:#1a1a1a;
    border:1px solid #333;
    border-radius:12px;
    padding:12px;
    min-width:220px;
    box-sizing:border-box;
}

.control-item label{
    display:block;
    margin-bottom:8px;
    color:#bbb;
    font-size:16px;
}

.control-item input{
    width:100%;
    padding:12px;
    border:none;
    border-radius:10px;
    background:#000;
    color:#fff;
    text-align:center;
    font-size:22px;
    box-sizing:border-box;
}

button{
    background:gold;
    color:#000;
    border:none;
    border-radius:12px;
    padding:14px 24px;
    font-size:20px;
    font-weight:bold;
    cursor:pointer;
    margin-bottom:20px;
}

button:hover{
    opacity:0.9;
}

.price-windows{
    display:flex;
    flex-wrap:wrap;
    justify-content:center;
    gap:16px;
    margin-bottom:10px;
}

.price-card{
    flex:1 1 320px;
    min-width:280px;
    max-width:500px;
    border-radius:14px;
    padding:24px 18px;
    box-sizing:border-box;
    border:1px solid #333;
}

.buy-card{
    background:linear-gradient(145deg,#053d16,#0a6b24);
}

.sell-card{
    background:linear-gradient(145deg,#5f0909,#8f1010);
}

.card-label{
    font-size:22px;
    margin-bottom:18px;
    font-weight:bold;
}

.buy-card .card-label{
    color:#8CFF9D;
}

.sell-card .card-label{
    color:#FF9A9A;
}

.card-price{
    font-size:38px;
    font-weight:bold;
    margin-bottom:12px;
}

.unit{
    font-size:22px;
    color:#ddd;
}

.mini-note{
    margin-top:14px;
    font-size:16px;
    color:#ccc;
}

.karat-box{
    width:95%;
    max-width:1100px;
    margin:18px auto;
    display:flex;
    flex-wrap:wrap;
    justify-content:center;
    gap:16px;
}

.karat-card{
    background:#111;
    border:1px solid #333;
    border-radius:14px;
    padding:18px;
    min-width:210px;
    flex:1 1 210px;
    max-width:260px;
    box-sizing:border-box;
}

.karat-title{
    color:gold;
    font-size:28px;
    margin-bottom:12px;
    font-weight:bold;
}

.karat-price{
    font-size:44px;
    color:#00ff99;
    font-weight:bold;
}

.live-widget-wrap{
    width:95%;
    max-width:1100px;
    margin:20px auto 35px auto;
    background:#111;
    border:1px solid #333;
    border-radius:16px;
    padding:18px;
    box-sizing:border-box;
}

.live-title{
    color:#FFD700;
    font-size:26px;
    margin-bottom:16px;
    font-weight:bold;
}

@media (max-width:768px){
    h1{
        font-size:26px;
    }

    .top-title,
    .live-title{
        font-size:22px;
    }

    .card-label{
        font-size:20px;
    }

    .card-price{
        font-size:34px;
    }

    .unit{
        font-size:18px;
    }

    .karat-title{
        font-size:22px;
    }

    .karat-price{
        font-size:34px;
    }

    .control-item{
        min-width:100%;
    }
}
</style>
</head>

<body>

<h1>🏆 رادار الأسعار المباشر</h1>

<div class="top-box">
    <div class="top-title">🇾🇪 تسعير الذهب الخليجي</div>

    <div class="controls">
        <div class="control-item">
            <label for="yerRate">سعر الصرف</label>
            <input type="number" id="yerRate" value="520">
        </div>

        <div class="control-item">
            <label for="buyExtra">زيادة على الشراء</label>
            <input type="number" id="buyExtra" value="0">
        </div>

        <div class="control-item">
            <label for="sellDiff">فارق البيع عن الشراء</label>
            <input type="number" id="sellDiff" value="4000">
        </div>
    </div>

    <button onclick="updateGold()">تحديث الأسعار</button>

    <div class="price-windows">
        <div class="price-card buy-card">
            <div class="card-label">سعر الشراء منكم</div>
            <div class="card-price" id="buyPrice">جاري التحميل...</div>
            <div class="unit">ريال يمني / جرام 21</div>
            <div class="mini-note">يمكنك التحكم بالزيادة من الأعلى</div>
        </div>

        <div class="price-card sell-card">
            <div class="card-label">سعر البيع لكم</div>
            <div class="card-price" id="sellPrice">جاري التحميل...</div>
            <div class="unit">ريال يمني / جرام 21</div>
            <div class="mini-note">البيع = الشراء + فارق البيع</div>
        </div>
    </div>
</div>

<div class="karat-box">
    <div class="karat-card">
        <div class="karat-title">سعر الأونصة</div>
        <div class="karat-price" id="ouncePrice">...</div>
    </div>

    <div class="karat-card">
        <div class="karat-title">جرام 24</div>
        <div class="karat-price" id="gram24">...</div>
    </div>

    <div class="karat-card">
        <div class="karat-title">جرام 21</div>
        <div class="karat-price" id="gram21">...</div>
    </div>

    <div class="karat-card">
        <div class="karat-title">جرام 18</div>
        <div class="karat-price" id="gram18">...</div>
    </div>
</div>

<div class="live-widget-wrap">
    <div class="live-title">📊 المؤشرات الحية المجانية</div>

    <div class="tradingview-widget-container">
        <div class="tradingview-widget-container__widget"></div>
        <script src="https://s3.tradingview.com/external-embedding/embed-widget-tickers.js" async>
        {
            "symbols": [
                {
                    "proName": "OANDA:XAUUSD",
                    "title": "الذهب / دولار"
                },
                {
                    "proName": "OANDA:XAGUSD",
                    "title": "الفضة / دولار"
                },
                {
                    "proName": "ICEUS:DX1!",
                    "title": "مؤشر الدولار"
                },
                {
                    "proName": "TVC:UKOIL",
                    "title": "نفط برنت"
                },
                {
                    "proName": "TVC:USOIL",
                    "title": "النفط الخفيف"
                }
            ],
            "isTransparent": false,
            "showSymbolLogo": true,
            "colorTheme": "dark",
            "locale": "ar"
        }
        </script>
    </div>
</div>

<script>
const API_KEY = "2cad562e57af449282b26db26e53403e";

function formatYER(num){
    return Math.round(num).toLocaleString("ar-YE") + " ريال";
}

async function updateGold(){
    try{
        const yerRate = parseFloat(document.getElementById("yerRate").value) || 0;
        const buyExtra = parseFloat(document.getElementById("buyExtra").value) || 0;
        const sellDiff = parseFloat(document.getElementById("sellDiff").value) || 0;

        const url = `https://api.twelvedata.com/price?symbol=XAU/USD&apikey=${API_KEY}`;
        const res = await fetch(url);
        const data = await res.json();

        if(!data.price){
            throw new Error("لم يتم جلب السعر");
        }

        const ounce = parseFloat(data.price);

        const gram24USD = ounce / 31.1035;
        const gram21USD = gram24USD * 0.875;
        const gram18USD = gram24USD * 0.750;

        const gram24YER = gram24USD * yerRate;
        const gram21YER = gram21USD * yerRate;
        const gram18YER = gram18USD * yerRate;

        const buyPrice = gram21YER + buyExtra;
        const sellPrice = buyPrice + sellDiff;

        document.getElementById("buyPrice").innerHTML = formatYER(buyPrice);
        document.getElementById("sellPrice").innerHTML = formatYER(sellPrice);
        document.getElementById("ouncePrice").innerHTML = ounce.toFixed(2) + " $";
        document.getElementById("gram24").innerHTML = formatYER(gram24YER);
        document.getElementById("gram21").innerHTML = formatYER(gram21YER);
        document.getElementById("gram18").innerHTML = formatYER(gram18YER);

    }catch(error){
        document.getElementById("buyPrice").innerHTML = "خطأ";
        document.getElementById("sellPrice").innerHTML = "خطأ";
        document.getElementById("ouncePrice").innerHTML = "خطأ";
        document.getElementById("gram24").innerHTML = "خطأ";
        document.getElementById("gram21").innerHTML = "خطأ";
        document.getElementById("gram18").innerHTML = "خطأ";
    }
}

updateGold();
setInterval(updateGold, 30000);
</script>

</body>
</html>
