# Arounabot-
Analyse paris sportifs 
<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>SMART PREDICT AUTO</title>
<style>
body{margin:0;background:#000;color:#fff;font-family:Arial}
.header{padding:10px;text-align:center;font-weight:bold;color:#00ff66}
.match{border:2px solid #00ff66;margin:8px;border-radius:6px}
.h{display:flex;justify-content:space-between;padding:6px;background:#111}
.o{padding:8px;text-align:center}
</style>
</head>
<body>

<div class="header">SMART PREDICT AUTO – 16 MATCHS (AUTO)</div>

<script>
const picks=[
"1X","Plus de 1.5 buts","BTTS OUI","X2",
"Plus de 2.5 buts","1X","Moins de 3.5 buts","BTTS OUI",
"1X","Plus de 1.5 buts","X2","Plus de 2.5 buts",
"BTTS OUI","1X","Moins de 3.5 buts","12"
];
for(let i=0;i<16;i++){
document.write(`
<div class="match">
 <div class="h">Match ${i+1}</div>
 <div class="o">${picks[i]}</div>
</div>
`);
}
</script>

</body>
</html>
