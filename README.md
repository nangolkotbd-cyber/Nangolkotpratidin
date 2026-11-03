<!DOCTYPE html>
<html lang="bn">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>নাঙ্গলকোট প্রতিদিন</title>
<style>
*{box-sizing:border-box;margin:0;padding:0}
body{font-family:"Noto Sans Bengali",sans-serif;background:#f2f2f2;color:#222}
a{color:inherit;text-decoration:none}
.top{background:#111;color:#bbb;font-size:12px;padding:6px 12px;display:flex;justify-content:space-between}
header{background:#fff;text-align:center;padding:14px;border-bottom:4px solid #b71c1c}
header h1{color:#b71c1c;font-size:32px}
header p{font-size:13px;color:#666}
nav{background:#b71c1c;display:flex;overflow-x:auto;white-space:nowrap;position:sticky;top:0;z-index:5}
nav a{color:#fff;padding:12px 16px;font-size:15px}
nav a:hover{background:#8e1515}
.ticker{background:#fff;display:flex;align-items:center;border-bottom:1px solid #ddd;overflow:hidden}
.ticker b{background:#b71c1c;color:#fff;padding:8px 12px;font-size:14px;white-space:nowrap}
.ticker span{display:inline-block;white-space:nowrap;padding-left:100%;animation:run 25s linear infinite;font-size:14px}
@keyframes run{to{transform:translateX(-100%)}}
.wrap{max-width:1000px;margin:12px auto;padding:0 12px;display:grid;gap:14px;grid-template-columns:1fr}
@media(min-width:800px){.wrap{grid-template-columns:2fr 1fr}}
.lead{background:#fff;border-radius:6px;overflow:hidden;box-shadow:0 1px 3px #0002}
.img{background:linear-gradient(135deg,#b71c1c,#555);height:200px;display:flex;align-items:center;justify-content:center;color:#fff;font-size:14px}
.img img{width:100%;height:100%;object-fit:cover}
.lead .body{padding:14px}
.lead h2{font-size:24px;line-height:1.4;margin-bottom:8px}
.tag{display:inline-block;background:#b71c1c;color:#fff;font-size:12px;padding:2px 8px;border-radius:3px;margin-bottom:6px}
p{font-size:14px;color:#555;line-height:1.7}
.time{font-size:12px;color:#999;margin-top:6px}
h4.sec{border-left:5px solid #b71c1c;padding-left:8px;margin:16px 0 8px;font-size:18px}
.grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:12px}
.card{background:#fff;border-radius:6px;overflow:hidden;box-shadow:0 1px 3px #0002}
.card .img{height:120px}
.card .body{padding:10px}
.card h3{font-size:16px;line-height:1.5}
aside .box{background:#fff;border-radius:6px;padding:12px;box-shadow:0 1px 3px #0002}
aside h4{border-bottom:2px solid #b71c1c;padding-bottom:6px;margin-bottom:8px}
aside li{list-style:none;padding:9px 0;border-bottom:1px solid #eee;font-size:14px;line-height:1.5}
aside li:last-child{border:0}
footer{background:#111;color:#ccc;text-align:center;padding:18px;margin-top:20px;font-size:13px;line-height:1.8}
footer a{color:#fff;text-decoration:underline}
</style>
</head>
<body>

<div class="top"><span>নাঙ্গলকোট, কুমিল্লা</span><span>৪ নভেম্বর ২০২৬</span></div>

<header>
  <h1>নাঙ্গলকোট প্রতিদিন</h1>
  <p>আপনার এলাকার প্রতিদিনের খবর</p>
</header>

<nav>
  <a href="#">প্রধান পাতা</a><a href="#local">স্থানীয়</a><a href="#edu">শিক্ষা</a>
  <a href="#sports">খেলা</a><a href="#">রাজনীতি</a><a href="#">অপরাধ</a><a href="#contact">যোগাযোগ</a>
</nav>

<div class="ticker">
  <b>ব্রেকিং</b>
  <span>এখানে সর্বশেষ জরুরি খবর লিখুন &nbsp;•&nbsp; দ্বিতীয় জরুরি খবর এখানে &nbsp;•&nbsp; তৃতীয় খবর এখানে</span>
</div>

<div class="wrap">
<main>
  <article class="lead">
    <div class="img">ছবি এখানে বসবে</div>
    <div class="body">
      <span class="tag">প্রধান খবর</span>
      <h2>এখানে আজকের প্রধান শিরোনাম লিখুন</h2>
      <p>এখানে খবরের সংক্ষিপ্ত বিবরণ লিখুন। প্রতিবেদনের মূল তথ্য, ঘটনার স্থান ও সময় এখানে থাকবে।</p>
      <div class="time">৪ নভেম্বর ২০২৬ | প্রতিবেদক</div>
    </div>
  </article>

  <h4 class="sec" id="local">স্থানীয়</h4>
  <div class="grid">
    <article class="card"><div class="img">ছবি</div><div class="body">
      <h3>স্থানীয় খবরের শিরোনাম এক</h3><div class="time">৪ নভেম্বর ২০২৬</div></div></article>
    <article class="card"><div class="img">ছবি</div><div class="body">
      <h3>স্থানীয় খবরের শিরোনাম দুই</h3><div class="time">৪ নভেম্বর ২০২৬</div></div></article>
  </div>

  <h4 class="sec" id="edu">শিক্ষা</h4>
  <div class="grid">
    <article class="card"><div class="img">ছবি</div><div class="body">
      <h3>শিক্ষা বিষয়ক খবরের শিরোনাম</h3><div class="time">৪ নভেম্বর ২০২৬</div></div></article>
  </div>

  <h4 class="sec" id="sports">খেলা</h4>
  <div class="grid">
    <article class="card"><div class="img">ছবি</div><div class="body">
      <h3>খেলার খবরের শিরোনাম</h3><div class="time">৪ নভেম্বর ২০২৬</div></div></article>
  </div>
</main>

<aside>
  <div class="box">
    <h4>সর্বশেষ</h4>
    <ul>
      <li>সর্বশেষ খবরের শিরোনাম এক</li>
      <li>সর্বশেষ খবরের শিরোনাম দুই</li>
      <li>সর্বশেষ খবরের শিরোনাম তিন</li>
      <li>সর্বশেষ খবরের শিরোনাম চার</li>
      <li>সর্বশেষ খবরের শিরোনাম পাঁচ</li>
    </ul>
  </div>
</aside>
</div>

<footer id="contact">
  <b>নাঙ্গলকোট প্রতিদিন</b><br>
  ইমেইল: Nangolkotbd@gmail.com | ফোন: ০১XXXXXXXXX<br>
  <a href="https://facebook.com/">ফেসবুক পেজ</a><br>
  © ২০২৬ সর্বস্বত্ব সংরক্ষিত
</footer>

</body>
</html>
