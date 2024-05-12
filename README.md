<!DOCTYPE html>
ABAAS BW
<html lang="ar">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>زخرفة الاسماء ورموز زخرفه bw</title>
<style>
    .rectangle {
        width: 300px;
        height: 100px;
        background-color: lightgray;
        text-align: center;
        line-height: 100px;
        font-size: 24px;
        margin-bottom: 20px;
    }
</style>
<script>
    function addCharacter(char) {
        document.getElementById("input").value += char;
        updateRectangles();
    }
ABAAS BW
    function updateRectangles() {
        var input = document.getElementById("input").value;
        var output1 = "";
        var output2 = "";
        var output3 = "";
        var output4 = "";
        var output5 = "";
        for (var i = 0; i < input.length; i++) {
            var ch = input.charAt(i);
            switch (ch) {
                case 'ج': output1 += 'ج'; output2 += 'جـ'; output3 += 'جہ'; output4 += 'ج̷'; output5 += ''; break;
                case 'ح': output1 += 'ح'; output2 += 'حـ'; output3 += 'حہ'; output4 += 'ح̷'; output5 += ''; break;
                case 'خ': output1 += 'خ'; output2 += 'خـ'; output3 += 'خہ'; output4 += 'خ̷'; output5 += ''; break;
                case 'ه': output1 += 'ه'; output2 += 'ه'; output3 += 'هےـِ'; output4 += 'ہ̷'; output5 += ''; break;
                case 'ع': output1 += 'ع'; output2 += 'عےـ'; output3 += 'عہ'; output4 += 'ع̷'; output5 += ''; break;
                case 'غ': output1 += 'غ'; output2 += 'غےـ'; output3 += 'غہ'; output4 += 'غ̷'; output5 += ''; break;
                case 'ف': output1 += 'ف'; output2 += 'فےـ'; output3 += 'فُ'; output4 += 'ف̷َ'; output5 += ''; break;
                case 'ق': output1 += 'ق'; output2 += 'قےـ'; output3 += 'ق'; output4 += 'ق̷'; output5 += ''; break;
                case 'ث': output1 += 'ث'; output2 += 'ثےـ'; output3 += 'ثہ'; output4 += 'ث̷'; output5 += ''; break;
                case 'ص': output1 += 'ص'; output2 += 'صےـ'; output3 += 'صہ'; output4 += 'ص̷'; output5 += ''; break;
                case 'ض': output1 += 'ض'; output2 += 'ضےـ'; output3 += 'ضہ'; output4 += 'ض'; output5 += ''; break;
                case 'ط': output1 += 'ط'; output2 += 'طےـ'; output3 += 'طہ'; output4 += 'ط̷ُ'; output5 += ''; break;
                case 'ك': output1 += 'ك'; output2 += 'كےـ'; output3 += 'كہ'; output4 += 'ك̷'; output5 += ''; break;
                case 'م': output1 += 'م'; output2 += 'مےـ'; output3 += 'مہ'; output4 += 'م̷'; output5 += ''; break;
                case 'ن': output1 += 'ن'; output2 += 'نےـ'; output3 += 'نہ'; output4 += 'ن̷'; output5 += ''; break;
                case 'ت': output1 += 'ت'; output2 += 'تےـ'; output3 += 'تہ'; output4 += 'ت̷'; output5 += ''; break;
                case 'ا': output1 += 'ا'; output2 += 'ا'; output3 += 'ا'; output4 += 'ا'; output5 += ''; break;
                case 'ل': output1 += 'ل'; output2 += 'ل'; output3 += 'ل'; output4 += 'ل̷'; output5 += ''; break;
                case 'ب': output1 += 'ب'; output2 += 'بےـ'; output3 += 'ب'; output4 += 'ب̷'; output5 += ''; break;
                case 'ب': output1 += 'بےـ'; output2 += 'ب'; output3 += 'ب'; output4 += 'ب̷'; output5 += ''; break;
                case 'ي': output1 += 'ي'; output2 += 'يےـ'; output3 += 'يہ'; output4 += 'ي̷'; output5 += ''; break;
                case 'س': output1 += 'س'; output2 += 'سےـ'; output3 += 'سہ'; output4 += 'س̷'; output5 += ''; break;
                case 'ش': output1 += 'ش'; output2 += 'شےـ'; output3 += 'شہ'; output4 += 'ش̷'; output5 += ''; break;
                case 'د': output1 += 'د'; output2 += 'د'; output3 += 'د'; output4 += 'د'; output5 += ''; break;
                case 'ظ': output1 += 'ظ'; output2 += 'ظےـ'; output3 += 'ظہ'; output4 += 'ظ'; output5 += ''; break;
                case 'ز': output1 += 'ز'; output2 += 'ز'; output3 += 'ز'; output4 += 'ز'; output5 += ''; break;
                case 'و': output1 += 'و'; output2 += 'و'; output3 += 'و'; output4 += 'و'; output5 += ''; break;
                case 'ة': output1 += 'ة'; output2 += 'ة'; output3 += 'ة'; output4 += 'ة'; output5 += ''; break;
                case 'ى': output1 += 'ى'; output2 += 'ى'; output3 += 'ى'; output4 += 'ى'; output5 += ''; break;
                case 'ر': output1 += 'ر'; output2 += 'ر'; output3 += 'ر'; output4 += 'ر'; output5 += ''; break;
                case 'ؤ': output1 += 'ؤ'; output2 += 'ؤ'; output3 += 'ؤ'; output4 += 'ؤ'; output5 += ''; break;
                case 'ء': output1 += 'ء'; output2 += 'ء'; output3 += 'ء'; output4 += 'ء'; output5 += ''; break;
                case 'ذ': output1 += 'ذ'; output2 += 'ذ'; output3 += 'ذ'; output4 += 'ذ'; output5 += ''; break;
                case 'ئ': output1 += 'ئ'; output2 += 'ئ'; output3 += 'ئ'; output4 += 'ئ'; output5 += ''; break;
                case 'أ': output1 += 'أ'; output2 += 'أ'; output3 += 'أ'; output4 += 'أ'; output5 += ''; break;
                default: output1 += ch; output2 += ch; output3 += ch; output4 += ch; output5 += ch; break;
            }
        }
        document.getElementById("output1").innerText = output1;
        document.getElementById("output2").innerText = output2;
        document.getElementById("output3").innerText = output3;
        document.getElementById("output4").innerText = output4;
        document.getElementById("output5").innerText = output5;
    }
    
</script>
</head>
<body>
<input type="text" id="input" oninput="updateRectangles()" placeholder="اكتب الكلمة هنا">
<div class="rectangle" id="output1"></div>
<div class="rectangle" id="output2"></div>
<div class="rectangle" id="output3"></div>
<div class="rectangle" id="output4"></div>
<div class="rectangle" id="output5"></div>
<!DOCTYPE html>
رموز يمكنك اضافتها بعد الزخرفه
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Zahrafy Website</title>
<style>
  .container {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
  }
  .box {
    margin: 10px;
    padding: 20px;
    border: 2px solid black;
    text-align: center;
    font-size: 24px;
    font-family: Arial, sans-serif;
  }
</style>
</head>
<body>
<div class="container">
  <div class="box">ᯓ</div>
  <div class="box">ᡣ</div>
  <div class="box">𐭩</div>
  <div class="box">⋆</div>
  <div class="box">౨</div>
  <div class="box">˚</div>
  <div class="box">⟡</div>
  <div class="box">˖</div>
  <div class="box">࣪</div>
  <div class="box">𐙚</div>
  <div class="box">ᯓ</div>
  <div class="box">★</div>
  <div class="box">ها</div>
  <div class="box">𐭩</div>
  <div class="box">🎧</div>
  <div class="box">ྀ</div>
  <div class="box">ི</div>
  <div class="box">شكرا</div>
  <div class="box">جزيلا</div>
  <div class="box">★</div>
  <div class="box">─</div>
  <div class="box">⋆</div>
  <div class="box">⋅</div>
  <div class="box">☆</div>
  <div class="box">⋅</div>
  <div class="box">⋆</div>
  <div class="box">─</div>
  <div class="box">.</div>
  <div class="box">ᐟ</div>
  <div class="box">⋆</div>
  <div class="box">˚</div>
  <div class="box">꩜</div>
  <div class="box">🫧</div>
  <div class="box">𓇼</div>
  <div class="box">𓏲</div>
  <div class="box">*ੈ</div>
  <div class="box">✩</div>
  <div class="box">‧₊</div>
  <div class="box">˚</div>
  <div class="box">🎐</div>
  <div class="box">شكرا</div>
  <div class="box">˚</div>
  <div class="box">˖</div>
  <div class="box">𓍢</div>
  <div class="box">⭐</div>
  <div class="box">໋</div>
  <div class="box">🌷</div>
  <div class="box">͙</div>
  <div class="box">uv</div>
  <div class="box">✧</div>
  <div class="box">˚</div>
  <div class="box">.</div>
  <div class="box">🎀</div>
  <div class="box">༘</div>
  <div class="box">⋆</div>
  <div class="box">𝄞</div>
  <div class="box">⨾</div>
  <div class="box">𓍢</div>
  <div class="box">⭐</div>
  <div class="box">໋</div>
  <div class="box">₊</div>
  <div class="box">˚</div>
  <div class="box">⊹</div>
  <div class="box">♡</div>
  <div class="box">𓍯</div>
  <div class="box">𓂃</div>
  <div class="box">⋆</div>
  <div class="box">˚</div>
  <div class="box">✮</div>
  <div class="box">🎧</div>
  <div class="box">✮</div>
  <div class="box">˚</div>
  <div class="box">.</div>
  <div class="box">⋆</div>
  <div class="box">「</div>
  <div class="box">✦</div>
  <div class="box">𝐍</div>
  <div class="box">𝐚</div>
  <div class="box">𝐦</div>
  <div class="box">𝐞</div>
  <div class="box">✦</div>
  <div class="box">」</div>
  <div class="box">.</div>
  <div class="box">⟡</div>
  <div class="box">♥</div>
<div class="box">♡</div>
<div class="box">☜</div>
<div class="box">☞</div>
<div class="box">☎</div>
<div class="box">☏</div>
<div class="box">⊙</div>
<div class="box">◎</div>
<div class="box">▨</div>
<div class="box">♨</div>
<div class="box">◐</div>
<div class="box">◑</div>
<div class="box">↔</div>
<div class="box">↕</div>
<div class="box">☏</div>
<div class="box">℡</div>
<div class="box">™</div>
<div class="box">№</div>
<div class="box">◈</div>
<div class="box">⊙</div>
<div class="box">◈</div>
<div class="box">♨</div>
<div class="box">§</div>
<div class="box">ξ</div>
<div class="box">∮</div>
<div class="box">￥</div>
<div class="box">￡</div>
<div class="box">♠</div>
<div class="box">♣</div>
<div class="box">♥</div>
<div class="box">●</div>
<div class="box">•</div>
<div class="box">0</div>
<div class="box">♡</div>
<div class="box">•</div>
<div class="box">0</div>
<div class="box">•</div>
<div class="box">●</div>
<div class="box">◐</div>
<div class="box">◑</div>
<div class="box">｡</div>
<div class="box">๑</div>
<div class="box">∞</div>
<div class="box">•</div>
<div class="box">◦</div>
<div class="box">♀</div>
<div class="box">◎</div>
<div class="box">♨</div>
<div class="box">◊</div>
<div class="box">▣</div>
<div class="box">▤</div>
<div class="box">▥</div>
<div class="box">▦</div>
<div class="box">▩</div>
<div class="box">▧</div>
<div class="box">▨</div>
<div class="box">♬</div>
<div class="box">♪</div>
<div class="box">♩</div>
<div class="box">♭</div>
<div class="box">♧</div>
<div class="box">∏</div>
<div class="box">۩</div>
<div class="box">۞</div>
<div class="box">ю</div>
<div class="box">Ю</div>
<div class="box">ღ</div>
<div class="box">ㄨ</div>
<div class="box">※</div>
<div class="box">Ψ</div>
<div class="box">彡</div>
<div class="box">乀</div>
<div class="box">∑</div>
<div class="box">⌒</div>
<div class="box">@</div>
<div class="box">▓</div>
<div class="box">↑</div>
<div class="box">↓</div>
<div class="box">←</div>
<div class="box">→</div>
<div class="box">↘</div>
<div class="box">↙</div>
<div class="box">↔</div>
<div class="box">↕</div>
<div class="box">ω</div>
<div class="box">‰</div>
<div class="box">Ω</div>
<div class="box">ж</div>
<div class="box">ф</div>
<div class="box">ò</div>
<div class="box">べ</div>
<div class="box">あ</div>
<div class="box">ぃ</div>
<div class="box">∈</div>
<div class="box">┣</div>
<div class="box">┓</div>
<div class="box">┏</div>
<div class="box">▄</div>
<div class="box">█</div>
<div class="box">▌</div>
<div class="box">▒</div>
<div class="box">『</div>
<div class="box">』</div>
<div class="box">〖</div>
<div class="box">〗</div>
<div class="box">◢</div>
<div class="box">◣</div>
<div class="box">◥</div>
<div class="box">◤</div>
<div class="box">△</div>
<div class="box">▲</div>
<div class="box">▄</div>
<div class="box">█</div>
<div class="box">▌</div>
<div class="box">▒</div>
<div class="box">◊</div>
<div class="box">→</div>
<div class="box">♡</div>
<div class="box">๑</div>
<div class="box">۩</div>
<div class="box">۞</div>
<div class="box">●</div>
<div class="box">☆</div>
<div class="box">★</div>
<div class="box">〓</div>
<div class="box">۩</div>
<div class="box">๑</div>
<div class="box">⊙</div>
<div class="box">▽</div>
<div class="box">⊙</div>
<div class="box">◑</div>
<div class="box">▂</div>
<div class="box">◐</div>
<div class="box">⊙</div>
<div class="box">ω</div>
<div class="box">⊙</div>
<div class="box">⊙</div>
<div class="box">︿</div>
<div class="box">⊙</div>
<div class="box">ω</div>
<div class="box">⊙</div>
<div class="box">﹏</div>
<div class="box">⊙</div>
<div class="box">△</div>
<div class="box">⊙</div>
<div class="box">▽</div>
<div class="box">●</div>
<div class="box">▂</div>
<div class="box">●</div>
<div class="box">●</div>
<div class="box">0</div>
<div class="box">●</div>
<div class="box">┍</div>
<div class="box">┎</div>
<div class="box">┏</div>
<div class="box">┐</div>
<div class="box">┑</div>
<div class="box">┒</div>
<div class="box">┓</div>
<div class="box">└</div>
<div class="box">┕</div>
<div class="box">┖</div>
<div class="box">┗</div>
<div class="box">┘</div>
<div class="box">┙</div>
<div class="box">┚</div>
<div class="box">┛</div>
<div class="box">├</div>
<div class="box">┝</div>
<div class="box">┞</div>
<div class="box">┟</div>
<div class="box">┠</div>
<div class="box">┡</div>
<div class="box">┢</div>
<div class="box">┣</div>
<div class="box">┤</div>
<div class="box">┥</div>
<div class="box">┦</div>
<div class="box">┧</div>
<div class="box">┨</div>
<div class="box">┩</div>
<div class="box">┪</div>
<div class="box">┫</div>
<div class="box">┬</div>
<div class="box">┭</div>
<div class="box">┮</div>
<div class="box">┯</div>
<div class="box">┰</div>
<div class="box">┱</div>
<div class="box">┲</div>
<div class="box">┳</div>
<div class="box">┴</div>
<div class="box">┵</div>
<div class="box">┶</div>
<div class="box">┷</div>
<div class="box">┸</div>
<div class="box">┹</div>
<div class="box">┺</div>
<div class="box">┻</div>
<div class="box">┼</div>
<div class="box">┽</div>
<div class="box">┾</div>
<div class="box">┿</div>
<div class="box">╀</div>
<div class="box">╁</div>
<div class="box">╂</div>
<div class="box">╃</div>
<div class="box">╄</div>
<div class="box">╅</div>
<div class="box">╆</div>
<div class="box">╇</div>
<div class="box">╈</div>

  
</div>
</body>
</html>
</style>

</body>
</html>

</script>
</body>
</html>
</body>
</html><!DOCTYPE html>
ABAAS BW
<html lang="ar">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>زخرفة الاسماء ورموز زخرفه bw</title>
<style>
    .rectangle {
        width: 300px;
        height: 100px;
        background-color: lightgray;
        text-align: center;
        line-height: 100px;
        font-size: 24px;
        margin-bottom: 20px;
    }
</style>
<script>
    function addCharacter(char) {
        document.getElementById("input").value += char;
        updateRectangles();
    }
ABAAS BW
    function updateRectangles() {
        var input = document.getElementById("input").value;
        var output1 = "";
        var output2 = "";
        var output3 = "";
        var output4 = "";
        var output5 = "";
        for (var i = 0; i < input.length; i++) {
            var ch = input.charAt(i);
            switch (ch) {
                case 'ج': output1 += 'ج'; output2 += 'جـ'; output3 += 'جہ'; output4 += 'ج̷'; output5 += ''; break;
                case 'ح': output1 += 'ح'; output2 += 'حـ'; output3 += 'حہ'; output4 += 'ح̷'; output5 += ''; break;
                case 'خ': output1 += 'خ'; output2 += 'خـ'; output3 += 'خہ'; output4 += 'خ̷'; output5 += ''; break;
                case 'ه': output1 += 'ه'; output2 += 'ه'; output3 += 'هےـِ'; output4 += 'ہ̷'; output5 += ''; break;
                case 'ع': output1 += 'ع'; output2 += 'عےـ'; output3 += 'عہ'; output4 += 'ع̷'; output5 += ''; break;
                case 'غ': output1 += 'غ'; output2 += 'غےـ'; output3 += 'غہ'; output4 += 'غ̷'; output5 += ''; break;
                case 'ف': output1 += 'ف'; output2 += 'فےـ'; output3 += 'فُ'; output4 += 'ف̷َ'; output5 += ''; break;
                case 'ق': output1 += 'ق'; output2 += 'قےـ'; output3 += 'ق'; output4 += 'ق̷'; output5 += ''; break;
                case 'ث': output1 += 'ث'; output2 += 'ثےـ'; output3 += 'ثہ'; output4 += 'ث̷'; output5 += ''; break;
                case 'ص': output1 += 'ص'; output2 += 'صےـ'; output3 += 'صہ'; output4 += 'ص̷'; output5 += ''; break;
                case 'ض': output1 += 'ض'; output2 += 'ضےـ'; output3 += 'ضہ'; output4 += 'ض'; output5 += ''; break;
                case 'ط': output1 += 'ط'; output2 += 'طےـ'; output3 += 'طہ'; output4 += 'ط̷ُ'; output5 += ''; break;
                case 'ك': output1 += 'ك'; output2 += 'كےـ'; output3 += 'كہ'; output4 += 'ك̷'; output5 += ''; break;
                case 'م': output1 += 'م'; output2 += 'مےـ'; output3 += 'مہ'; output4 += 'م̷'; output5 += ''; break;
                case 'ن': output1 += 'ن'; output2 += 'نےـ'; output3 += 'نہ'; output4 += 'ن̷'; output5 += ''; break;
                case 'ت': output1 += 'ت'; output2 += 'تےـ'; output3 += 'تہ'; output4 += 'ت̷'; output5 += ''; break;
                case 'ا': output1 += 'ا'; output2 += 'ا'; output3 += 'ا'; output4 += 'ا'; output5 += ''; break;
                case 'ل': output1 += 'ل'; output2 += 'ل'; output3 += 'ل'; output4 += 'ل̷'; output5 += ''; break;
                case 'ب': output1 += 'ب'; output2 += 'بےـ'; output3 += 'ب'; output4 += 'ب̷'; output5 += ''; break;
                case 'ب': output1 += 'بےـ'; output2 += 'ب'; output3 += 'ب'; output4 += 'ب̷'; output5 += ''; break;
                case 'ي': output1 += 'ي'; output2 += 'يےـ'; output3 += 'يہ'; output4 += 'ي̷'; output5 += ''; break;
                case 'س': output1 += 'س'; output2 += 'سےـ'; output3 += 'سہ'; output4 += 'س̷'; output5 += ''; break;
                case 'ش': output1 += 'ش'; output2 += 'شےـ'; output3 += 'شہ'; output4 += 'ش̷'; output5 += ''; break;
                case 'د': output1 += 'د'; output2 += 'د'; output3 += 'د'; output4 += 'د'; output5 += ''; break;
                case 'ظ': output1 += 'ظ'; output2 += 'ظےـ'; output3 += 'ظہ'; output4 += 'ظ'; output5 += ''; break;
                case 'ز': output1 += 'ز'; output2 += 'ز'; output3 += 'ز'; output4 += 'ز'; output5 += ''; break;
                case 'و': output1 += 'و'; output2 += 'و'; output3 += 'و'; output4 += 'و'; output5 += ''; break;
                case 'ة': output1 += 'ة'; output2 += 'ة'; output3 += 'ة'; output4 += 'ة'; output5 += ''; break;
                case 'ى': output1 += 'ى'; output2 += 'ى'; output3 += 'ى'; output4 += 'ى'; output5 += ''; break;
                case 'ر': output1 += 'ر'; output2 += 'ر'; output3 += 'ر'; output4 += 'ر'; output5 += ''; break;
                case 'ؤ': output1 += 'ؤ'; output2 += 'ؤ'; output3 += 'ؤ'; output4 += 'ؤ'; output5 += ''; break;
                case 'ء': output1 += 'ء'; output2 += 'ء'; output3 += 'ء'; output4 += 'ء'; output5 += ''; break;
                case 'ذ': output1 += 'ذ'; output2 += 'ذ'; output3 += 'ذ'; output4 += 'ذ'; output5 += ''; break;
                case 'ئ': output1 += 'ئ'; output2 += 'ئ'; output3 += 'ئ'; output4 += 'ئ'; output5 += ''; break;
                case 'أ': output1 += 'أ'; output2 += 'أ'; output3 += 'أ'; output4 += 'أ'; output5 += ''; break;
                default: output1 += ch; output2 += ch; output3 += ch; output4 += ch; output5 += ch; break;
            }
        }
        document.getElementById("output1").innerText = output1;
        document.getElementById("output2").innerText = output2;
        document.getElementById("output3").innerText = output3;
        document.getElementById("output4").innerText = output4;
        document.getElementById("output5").innerText = output5;
    }
    
</script>
</head>
<body>
<input type="text" id="input" oninput="updateRectangles()" placeholder="اكتب الكلمة هنا">
<div class="rectangle" id="output1"></div>
<div class="rectangle" id="output2"></div>
<div class="rectangle" id="output3"></div>
<div class="rectangle" id="output4"></div>
<div class="rectangle" id="output5"></div>
<!DOCTYPE html>
رموز يمكنك اضافتها بعد الزخرفه
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Zahrafy Website</title>
<style>
  .container {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
  }
  .box {
    margin: 10px;
    padding: 20px;
    border: 2px solid black;
    text-align: center;
    font-size: 24px;
    font-family: Arial, sans-serif;
  }
</style>
</head>
<body>
<div class="container">
  <div class="box">ᯓ</div>
  <div class="box">ᡣ</div>
  <div class="box">𐭩</div>
  <div class="box">⋆</div>
  <div class="box">౨</div>
  <div class="box">˚</div>
  <div class="box">⟡</div>
  <div class="box">˖</div>
  <div class="box">࣪</div>
  <div class="box">𐙚</div>
  <div class="box">ᯓ</div>
  <div class="box">★</div>
  <div class="box">ها</div>
  <div class="box">𐭩</div>
  <div class="box">🎧</div>
  <div class="box">ྀ</div>
  <div class="box">ི</div>
  <div class="box">شكرا</div>
  <div class="box">جزيلا</div>
  <div class="box">★</div>
  <div class="box">─</div>
  <div class="box">⋆</div>
  <div class="box">⋅</div>
  <div class="box">☆</div>
  <div class="box">⋅</div>
  <div class="box">⋆</div>
  <div class="box">─</div>
  <div class="box">.</div>
  <div class="box">ᐟ</div>
  <div class="box">⋆</div>
  <div class="box">˚</div>
  <div class="box">꩜</div>
  <div class="box">🫧</div>
  <div class="box">𓇼</div>
  <div class="box">𓏲</div>
  <div class="box">*ੈ</div>
  <div class="box">✩</div>
  <div class="box">‧₊</div>
  <div class="box">˚</div>
  <div class="box">🎐</div>
  <div class="box">شكرا</div>
  <div class="box">˚</div>
  <div class="box">˖</div>
  <div class="box">𓍢</div>
  <div class="box">⭐</div>
  <div class="box">໋</div>
  <div class="box">🌷</div>
  <div class="box">͙</div>
  <div class="box">uv</div>
  <div class="box">✧</div>
  <div class="box">˚</div>
  <div class="box">.</div>
  <div class="box">🎀</div>
  <div class="box">༘</div>
  <div class="box">⋆</div>
  <div class="box">𝄞</div>
  <div class="box">⨾</div>
  <div class="box">𓍢</div>
  <div class="box">⭐</div>
  <div class="box">໋</div>
  <div class="box">₊</div>
  <div class="box">˚</div>
  <div class="box">⊹</div>
  <div class="box">♡</div>
  <div class="box">𓍯</div>
  <div class="box">𓂃</div>
  <div class="box">⋆</div>
  <div class="box">˚</div>
  <div class="box">✮</div>
  <div class="box">🎧</div>
  <div class="box">✮</div>
  <div class="box">˚</div>
  <div class="box">.</div>
  <div class="box">⋆</div>
  <div class="box">「</div>
  <div class="box">✦</div>
  <div class="box">𝐍</div>
  <div class="box">𝐚</div>
  <div class="box">𝐦</div>
  <div class="box">𝐞</div>
  <div class="box">✦</div>
  <div class="box">」</div>
  <div class="box">.</div>
  <div class="box">⟡</div>
  <div class="box">♥</div>
<div class="box">♡</div>
<div class="box">☜</div>
<div class="box">☞</div>
<div class="box">☎</div>
<div class="box">☏</div>
<div class="box">⊙</div>
<div class="box">◎</div>
<div class="box">▨</div>
<div class="box">♨</div>
<div class="box">◐</div>
<div class="box">◑</div>
<div class="box">↔</div>
<div class="box">↕</div>
<div class="box">☏</div>
<div class="box">℡</div>
<div class="box">™</div>
<div class="box">№</div>
<div class="box">◈</div>
<div class="box">⊙</div>
<div class="box">◈</div>
<div class="box">♨</div>
<div class="box">§</div>
<div class="box">ξ</div>
<div class="box">∮</div>
<div class="box">￥</div>
<div class="box">￡</div>
<div class="box">♠</div>
<div class="box">♣</div>
<div class="box">♥</div>
<div class="box">●</div>
<div class="box">•</div>
<div class="box">0</div>
<div class="box">♡</div>
<div class="box">•</div>
<div class="box">0</div>
<div class="box">•</div>
<div class="box">●</div>
<div class="box">◐</div>
<div class="box">◑</div>
<div class="box">｡</div>
<div class="box">๑</div>
<div class="box">∞</div>
<div class="box">•</div>
<div class="box">◦</div>
<div class="box">♀</div>
<div class="box">◎</div>
<div class="box">♨</div>
<div class="box">◊</div>
<div class="box">▣</div>
<div class="box">▤</div>
<div class="box">▥</div>
<div class="box">▦</div>
<div class="box">▩</div>
<div class="box">▧</div>
<div class="box">▨</div>
<div class="box">♬</div>
<div class="box">♪</div>
<div class="box">♩</div>
<div class="box">♭</div>
<div class="box">♧</div>
<div class="box">∏</div>
<div class="box">۩</div>
<div class="box">۞</div>
<div class="box">ю</div>
<div class="box">Ю</div>
<div class="box">ღ</div>
<div class="box">ㄨ</div>
<div class="box">※</div>
<div class="box">Ψ</div>
<div class="box">彡</div>
<div class="box">乀</div>
<div class="box">∑</div>
<div class="box">⌒</div>
<div class="box">@</div>
<div class="box">▓</div>
<div class="box">↑</div>
<div class="box">↓</div>
<div class="box">←</div>
<div class="box">→</div>
<div class="box">↘</div>
<div class="box">↙</div>
<div class="box">↔</div>
<div class="box">↕</div>
<div class="box">ω</div>
<div class="box">‰</div>
<div class="box">Ω</div>
<div class="box">ж</div>
<div class="box">ф</div>
<div class="box">ò</div>
<div class="box">べ</div>
<div class="box">あ</div>
<div class="box">ぃ</div>
<div class="box">∈</div>
<div class="box">┣</div>
<div class="box">┓</div>
<div class="box">┏</div>
<div class="box">▄</div>
<div class="box">█</div>
<div class="box">▌</div>
<div class="box">▒</div>
<div class="box">『</div>
<div class="box">』</div>
<div class="box">〖</div>
<div class="box">〗</div>
<div class="box">◢</div>
<div class="box">◣</div>
<div class="box">◥</div>
<div class="box">◤</div>
<div class="box">△</div>
<div class="box">▲</div>
<div class="box">▄</div>
<div class="box">█</div>
<div class="box">▌</div>
<div class="box">▒</div>
<div class="box">◊</div>
<div class="box">→</div>
<div class="box">♡</div>
<div class="box">๑</div>
<div class="box">۩</div>
<div class="box">۞</div>
<div class="box">●</div>
<div class="box">☆</div>
<div class="box">★</div>
<div class="box">〓</div>
<div class="box">۩</div>
<div class="box">๑</div>
<div class="box">⊙</div>
<div class="box">▽</div>
<div class="box">⊙</div>
<div class="box">◑</div>
<div class="box">▂</div>
<div class="box">◐</div>
<div class="box">⊙</div>
<div class="box">ω</div>
<div class="box">⊙</div>
<div class="box">⊙</div>
<div class="box">︿</div>
<div class="box">⊙</div>
<div class="box">ω</div>
<div class="box">⊙</div>
<div class="box">﹏</div>
<div class="box">⊙</div>
<div class="box">△</div>
<div class="box">⊙</div>
<div class="box">▽</div>
<div class="box">●</div>
<div class="box">▂</div>
<div class="box">●</div>
<div class="box">●</div>
<div class="box">0</div>
<div class="box">●</div>
<div class="box">┍</div>
<div class="box">┎</div>
<div class="box">┏</div>
<div class="box">┐</div>
<div class="box">┑</div>
<div class="box">┒</div>
<div class="box">┓</div>
<div class="box">└</div>
<div class="box">┕</div>
<div class="box">┖</div>
<div class="box">┗</div>
<div class="box">┘</div>
<div class="box">┙</div>
<div class="box">┚</div>
<div class="box">┛</div>
<div class="box">├</div>
<div class="box">┝</div>
<div class="box">┞</div>
<div class="box">┟</div>
<div class="box">┠</div>
<div class="box">┡</div>
<div class="box">┢</div>
<div class="box">┣</div>
<div class="box">┤</div>
<div class="box">┥</div>
<div class="box">┦</div>
<div class="box">┧</div>
<div class="box">┨</div>
<div class="box">┩</div>
<div class="box">┪</div>
<div class="box">┫</div>
<div class="box">┬</div>
<div class="box">┭</div>
<div class="box">┮</div>
<div class="box">┯</div>
<div class="box">┰</div>
<div class="box">┱</div>
<div class="box">┲</div>
<div class="box">┳</div>
<div class="box">┴</div>
<div class="box">┵</div>
<div class="box">┶</div>
<div class="box">┷</div>
<div class="box">┸</div>
<div class="box">┹</div>
<div class="box">┺</div>
<div class="box">┻</div>
<div class="box">┼</div>
<div class="box">┽</div>
<div class="box">┾</div>
<div class="box">┿</div>
<div class="box">╀</div>
<div class="box">╁</div>
<div class="box">╂</div>
<div class="box">╃</div>
<div class="box">╄</div>
<div class="box">╅</div>
<div class="box">╆</div>
<div class="box">╇</div>
<div class="box">╈</div>

  
</div>
</body>
</html>
</style>

</body>
</html>

</script>
</body>
</html>
</body>
</html>
