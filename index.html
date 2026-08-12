<!DOCTYPE html>
<html lang="tr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">

<title>Boss Torbası</title>

<style>
    * {
        box-sizing: border-box;
        -webkit-tap-highlight-color: transparent;
    }

    html, body {
        margin: 0;
        padding: 0;
        min-height: 100%;
        font-family: Arial, Helvetica, sans-serif;
        background:
            radial-gradient(circle at top, #26344d 0%, #111827 45%, #070b12 100%);
        color: white;
        overflow-x: hidden;
    }

    body {
        min-height: 100vh;
    }

    .container {
        width: min(1100px, 94%);
        margin: auto;
        padding: 25px 0 40px;
    }

    .header {
        text-align: center;
        margin-bottom: 20px;
    }

    .header h1 {
        margin: 0;
        font-size: clamp(30px, 6vw, 54px);
        font-weight: 900;
        letter-spacing: -2px;
    }

    .header p {
        margin: 8px 0 0;
        color: #aeb9ca;
        font-size: 15px;
    }

    /* PLAYER BAR */

    .player-bar {
        display: flex;
        gap: 12px;
        justify-content: center;
        align-items: center;
        flex-wrap: wrap;
        margin-bottom: 20px;
    }

    input {
        width: 260px;
        max-width: 90vw;
        padding: 14px 18px;
        border: 1px solid #374151;
        border-radius: 12px;
        background: #111827;
        color: white;
        outline: none;
        font-size: 16px;
    }

    input:focus {
        border-color: #60a5fa;
    }

    button {
        border: 0;
        border-radius: 12px;
        padding: 14px 22px;
        font-size: 16px;
        font-weight: 800;
        cursor: pointer;
        color: white;
        background: #2563eb;
        transition: transform .1s, filter .1s;
    }

    button:hover {
        filter: brightness(1.1);
    }

    button:active {
        transform: scale(.96);
    }

    .start-btn {
        background: #16a34a;
    }

    .finish-btn {
        background: #dc2626;
        display: none;
    }

    /* GAME */

    .game-area {
        position: relative;
        min-height: 560px;
        border: 1px solid rgba(255,255,255,.08);
        border-radius: 24px;
        background:
            linear-gradient(
                rgba(255,255,255,.025),
                rgba(255,255,255,.01)
            );
        box-shadow: 0 25px 80px rgba(0,0,0,.4);
        overflow: hidden;
    }

    .stats {
        position: absolute;
        left: 20px;
        right: 20px;
        top: 18px;
        display: flex;
        justify-content: center;
        gap: 12px;
        flex-wrap: wrap;
        z-index: 5;
    }

    .stat {
        min-width: 120px;
        padding: 10px 15px;
        text-align: center;
        border-radius: 12px;
        background: rgba(15,23,42,.85);
        border: 1px solid rgba(255,255,255,.08);
        backdrop-filter: blur(10px);
    }

    .stat-label {
        display: block;
        font-size: 11px;
        color: #9ca3af;
        text-transform: uppercase;
        letter-spacing: 1px;
    }

    .stat-value {
        display: block;
        margin-top: 3px;
        font-size: 22px;
        font-weight: 900;
    }

    /* BAG */

    .bag-zone {
        position: absolute;
        left: 50%;
        top: 58%;
        transform: translate(-50%, -50%);
        width: min(330px, 70vw);
        height: 390px;
        display: flex;
        justify-content: center;
        align-items: center;
    }

    .rope {
        position: absolute;
        top: -20px;
        width: 8px;
        height: 90px;
        border-radius: 8px;
        background: #6b7280;
        box-shadow: 0 0 8px rgba(0,0,0,.5);
    }

    .bag {
        position: relative;
        width: min(240px, 60vw);
        height: min(330px, 78vw);
        max-height: 330px;
        border-radius: 48% 48% 44% 44%;
        background:
            radial-gradient(
                circle at 35% 25%,
                #ef4444 0%,
                #b91c1c 25%,
                #7f1d1d 65%,
                #450a0a 100%
            );
        border: 5px solid #3f0b0b;
        box-shadow:
            inset -25px -30px 40px rgba(0,0,0,.35),
            inset 20px 20px 30px rgba(255,255,255,.08),
            0 30px 45px rgba(0,0,0,.5);
        cursor: pointer;
        user-select: none;
        touch-action: manipulation;
        transition: transform .07s;
    }

    .bag::before {
        content: "";
        position: absolute;
        top: 12%;
        left: 13%;
        width: 20%;
        height: 50%;
        border-radius: 50%;
        background: rgba(255,255,255,.07);
        filter: blur(5px);
    }

    .bag-text {
        position: absolute;
        left: 0;
        right: 0;
        top: 43%;
        text-align: center;
        font-size: clamp(20px, 5vw, 32px);
        font-weight: 1000;
        letter-spacing: 2px;
        text-shadow: 3px 3px 5px #450a0a;
        pointer-events: none;
    }

    .bag-sub {
        position: absolute;
        left: 0;
        right: 0;
        top: 54%;
        text-align: center;
        font-size: 11px;
        color: rgba(255,255,255,.6);
        pointer-events: none;
    }

    .bag.hit {
        animation: punch .12s linear;
    }

    @keyframes punch {
        0% {
            transform: scale(1) rotate(0deg);
        }

        35% {
            transform: scale(.94) rotate(-3deg);
        }

        70% {
            transform: scale(1.05) rotate(3deg);
        }

        100% {
            transform: scale(1) rotate(0deg);
        }
    }

    /* COMBO */

    .combo {
        position: absolute;
        left: 50%;
        top: 34%;
        transform: translate(-50%, -50%) scale(.8);
        font-size: clamp(28px, 7vw, 55px);
        font-weight: 1000;
        color: #fbbf24;
        text-shadow: 0 0 25px rgba(251,191,36,.45);
        opacity: 0;
        pointer-events: none;
        z-index: 10;
    }

    .combo.show {
        animation: comboPop .25s ease-out forwards;
    }

    @keyframes comboPop {
        0% {
            opacity: 0;
            transform: translate(-50%, -50%) scale(.5);
        }

        60% {
            opacity: 1;
            transform: translate(-50%, -50%) scale(1.15);
        }

        100% {
            opacity: 1;
            transform: translate(-50%, -50%) scale(1);
        }
    }

    /* FLOAT SCORE */

    .floating-score {
        position: absolute;
        font-size: 24px;
        font-weight: 1000;
        color: #86efac;
        pointer-events: none;
        z-index: 20;
        animation: floatScore .8s ease-out forwards;
    }

    @keyframes floatScore {
        0% {
            opacity: 1;
            transform: translate(-50%, 0) scale(1);
        }

        100% {
            opacity: 0;
            transform: translate(-50%, -90px) scale(1.3);
        }
    }

    /* LEADERBOARD */

    .leaderboard {
        margin-top: 22px;
        border-radius: 20px;
        background: rgba(15,23,42,.85);
        border: 1px solid rgba(255,255,255,.08);
        overflow: hidden;
    }

    .leaderboard-header {
        padding: 20px;
        display: flex;
        justify-content: space-between;
        align-items: center;
        gap: 10px;
    }

    .leaderboard-header h2 {
        margin: 0;
        font-size: 22px;
    }

    .table {
        width: 100%;
    }

    .row {
        display: grid;
        grid-template-columns: 60px 1fr 120px 100px;
        padding: 13px 20px;
        border-top: 1px solid rgba(255,255,255,.06);
        align-items: center;
    }

    .row.header-row {
        color: #9ca3af;
        font-size: 12px;
        text-transform: uppercase;
    }

    .rank {
        font-weight: 900;
    }

    .score {
        font-weight: 900;
        text-align: right;
    }

    .combo-score {
        text-align: right;
        color: #fbbf24;
        font-weight: 800;
    }

    .empty {
        padding: 30px;
        text-align: center;
        color: #9ca3af;
    }

    /* START OVERLAY */

    .overlay {
        position: absolute;
        inset: 0;
        background: rgba(3,7,18,.75);
        backdrop-filter: blur(6px);
        display: flex;
        align-items: center;
        justify-content: center;
        z-index: 30;
        text-align: center;
        padding: 20px;
    }

    .overlay-box {
        max-width: 500px;
    }

    .overlay h2 {
        font-size: clamp(28px, 7vw, 48px);
        margin: 0 0 10px;
    }

    .overlay p {
        color: #aeb9ca;
        line-height: 1.6;
    }

    .overlay.hidden {
        display: none;
    }

    /* SHAKE */

    .shake {
        animation: shake .16s linear;
    }

    @keyframes shake {
        0%,100% {
            transform: translate(0);
        }

        25% {
            transform: translate(-5px, 3px);
        }

        50% {
            transform: translate(5px, -3px);
        }

        75% {
            transform: translate(-3px, -2px);
        }
    }

    @media (max-width: 600px) {

        .container {
            width: 96%;
            padding-top: 15px;
        }

        .game-area {
            min-height: 570px;
            border-radius: 18px;
        }

        .stats {
            top: 12px;
            left: 8px;
            right: 8px;
            gap: 6px;
        }

        .stat {
            min-width: 95px;
            padding: 8px;
        }

        .stat-value {
            font-size: 18px;
        }

        .bag-zone {
            top: 57%;
        }

        .row {
            grid-template-columns: 45px 1fr 90px;
            padding: 12px;
        }

        .row .combo-score {
            display: none;
        }

        .header-row .combo-score {
            display: none;
        }
    }
</style>
</head>

<body>

<div class="container">

    <div class="header">
        <h1>🥊 BOSS TORBASI</h1>
        <p>Ne kadar hızlı vurursan o kadar yüksek combo!</p>
    </div>

    <div class="player-bar">
        <input
            id="playerName"
            type="text"
            maxlength="20"
            placeholder="Oyuncu adını yaz..."
            autocomplete="off"
        >

        <button class="start-btn" id="startBtn">
            OYUNA BAŞLA
        </button>

        <button class="finish-btn" id="finishBtn">
            OYUNU BİTİR
        </button>
    </div>

    <div class="game-area" id="gameArea">

        <div class="stats">

            <div class="stat">
                <span class="stat-label">Skor</span>
                <span class="stat-value" id="score">0</span>
            </div>

            <div class="stat">
                <span class="stat-label">Vuruş</span>
                <span class="stat-value" id="hits">0</span>
            </div>

            <div class="stat">
                <span class="stat-label">Combo</span>
                <span class="stat-value" id="comboValue">x0</span>
            </div>

            <div class="stat">
                <span class="stat-label">En yüksek</span>
                <span class="stat-value" id="best">0</span>
            </div>

        </div>

        <div class="combo" id="comboText">
            COMBO x2
        </div>

        <div class="bag-zone">

            <div class="rope"></div>

            <div
                class="bag"
                id="bag"
                aria-label="Kum torbası"
            >
                <div class="bag-text">
                    BOSS
                </div>

                <div class="bag-sub">
                    VUR!
                </div>
            </div>

        </div>

        <div class="overlay" id="overlay">

            <div class="overlay-box">

                <h2>🥊 Hazır mısın?</h2>

                <p>
                    İsmini yukarıya yaz ve oyuna başla.
                    Süre sınırı yok. Torbaya ne kadar hızlı
                    ve kesintisiz vurursan combo'n o kadar büyür.
                </p>

                <button class="start-btn" id="overlayStart">
                    BAŞLA
                </button>

            </div>

        </div>

    </div>

    <div class="leaderboard">

        <div class="leaderboard-header">
            <h2>🏆 Skor Tablosu</h2>

            <button id="clearScores"
                    style="background:#374151;font-size:12px;padding:9px 12px;">
                Sıfırla
            </button>
        </div>

        <div class="table">

            <div class="row header-row">
                <div>#</div>
                <div>Oyuncu</div>
                <div class="score">Skor</div>
                <div class="combo-score">Combo</div>
            </div>

            <div id="leaderboardRows"></div>

        </div>

    </div>

</div>

<script>

const playerName = document.getElementById("playerName");
const startBtn = document.getElementById("startBtn");
const finishBtn = document.getElementById("finishBtn");
const overlayStart = document.getElementById("overlayStart");

const overlay = document.getElementById("overlay");
const bag = document.getElementById("bag");
const gameArea = document.getElementById("gameArea");

const scoreElement = document.getElementById("score");
const hitsElement = document.getElementById("hits");
const comboElement = document.getElementById("comboValue");
const bestElement = document.getElementById("best");

const comboText = document.getElementById("comboText");
const leaderboardRows = document.getElementById("leaderboardRows");
const clearScores = document.getElementById("clearScores");

let gameStarted = false;

let score = 0;
let hits = 0;
let combo = 0;
let highestCombo = 0;

let lastHitTime = 0;

const COMBO_TIMEOUT = 900;

let audioContext = null;


/* -------------------------
   AUDIO
------------------------- */

function initAudio() {

    if (!audioContext) {
        audioContext =
            new (window.AudioContext || window.webkitAudioContext)();
    }

    if (audioContext.state === "suspended") {
        audioContext.resume();
    }
}

function punchSound(critical = false) {

    if (!audioContext) return;

    const oscillator =
        audioContext.createOscillator();

    const gain =
        audioContext.createGain();

    oscillator.connect(gain);
    gain.connect(audioContext.destination);

    oscillator.type = critical ? "square" : "sine";

    oscillator.frequency.setValueAtTime(
        critical ? 180 : 110,
        audioContext.currentTime
    );

    oscillator.frequency.exponentialRampToValueAtTime(
        critical ? 80 : 55,
        audioContext.currentTime + .08
    );

    gain.gain.setValueAtTime(
        critical ? .13 : .08,
        audioContext.currentTime
    );

    gain.gain.exponentialRampToValueAtTime(
        .001,
        audioContext.currentTime + .09
    );

    oscillator.start();

    oscillator.stop(
        audioContext.currentTime + .1
    );
}


/* -------------------------
   GAME
------------------------- */

function startGame() {

    let name = playerName.value.trim();

    if (!name) {
        playerName.focus();
        playerName.placeholder = "Önce isim gir!";
        return;
    }

    if (name.length < 2) {
        alert("Lütfen en az 2 karakterlik bir isim gir.");
        return;
    }

    initAudio();

    gameStarted = true;

    score = 0;
    hits = 0;
    combo = 0;
    highestCombo = 0;
    lastHitTime = 0;

    updateStats();

    overlay.classList.add("hidden");

    startBtn.style.display = "none";
    finishBtn.style.display = "inline-block";

    playerName.disabled = true;
}


function finishGame() {

    if (!gameStarted) return;

    gameStarted = false;

    finishBtn.style.display = "none";
    startBtn.style.display = "inline-block";

    playerName.disabled = false;

    combo = 0;

    updateStats();

    saveScore(
        playerName.value.trim(),
        score,
        highestCombo
    );

    overlay.classList.remove("hidden");

    overlay.innerHTML = `
        <div class="overlay-box">

            <h2>🏆 Oyun Bitti!</h2>

            <p>
                <strong>${escapeHtml(playerName.value.trim())}</strong>
                toplam <strong>${score.toLocaleString("tr-TR")}</strong>
                puan yaptı.
            </p>

            <p>
                Toplam vuruş: <strong>${hits}</strong><br>
                En yüksek combo: <strong>x${highestCombo}</strong>
            </p>

            <button class="start-btn" id="overlayStart">
                TEKRAR OYNA
            </button>

        </div>
    `;

    document
        .getElementById("overlayStart")
        .addEventListener("click", startGame);

    renderLeaderboard();
}


/* -------------------------
   HIT
------------------------- */

function hitBag(event) {

    if (!gameStarted) return;

    event.preventDefault();

    const now = performance.now();

    /*
        Combo mantığı:
        900ms içinde tekrar vurulursa combo artıyor.
    */

    if (now - lastHitTime <= COMBO_TIMEOUT) {
        combo++;
    } else {
        combo = 1;
    }

    lastHitTime = now;

    hits++;

    if (combo > highestCombo) {
        highestCombo = combo;
    }

    /*
        Combo çarpanı:

        1-4   = x1
        5-9   = x2
        10-19 = x3
        20-29 = x4
        30+   = x5
    */

    let multiplier = 1;

    if (combo >= 30) {
        multiplier = 5;
    } else if (combo >= 20) {
        multiplier = 4;
    } else if (combo >= 10) {
        multiplier = 3;
    } else if (combo >= 5) {
        multiplier = 2;
    }

    /*
        Kritik vuruş.
        Yaklaşık %7 ihtimal.
    */

    const critical =
        Math.random() < 0.07;

    let points =
        10 * multiplier;

    if (critical) {
        points *= 3;
    }

    score += points;

    updateStats();

    animateBag();

    punchSound(critical);

    showFloatingScore(
        event,
        points,
        critical
    );

    if (combo >= 2) {
        showCombo();
    }
}


/* -------------------------
   ANIMATION
------------------------- */

function animateBag() {

    bag.classList.remove("hit");

    /*
       Animation'ın tekrar tetiklenebilmesi için
       browser'ın layout hesaplamasını bekliyoruz.
    */

    void bag.offsetWidth;

    bag.classList.add("hit");

    gameArea.classList.remove("shake");

    void gameArea.offsetWidth;

    gameArea.classList.add("shake");
}


function showCombo() {

    comboText.textContent =
        `COMBO x${combo}`;

    comboText.classList.remove("show");

    void comboText.offsetWidth;

    comboText.classList.add("show");
}


function showFloatingScore(
    event,
    points,
    critical
) {

    const floating =
        document.createElement("div");

    floating.className =
        "floating-score";

    floating.textContent =
        critical
            ? `CRITICAL +${points}`
            : `+${points}`;

    const rect =
        gameArea.getBoundingClientRect();

    let x;
    let y;

    if (event.clientX !== undefined) {

        x =
            event.clientX -
            rect.left;

        y =
            event.clientY -
            rect.top;

    } else {

        const bagRect =
            bag.getBoundingClientRect();

        x =
            bagRect.left -
            rect.left +
            bagRect.width / 2;

        y =
            bagRect.top -
            rect.top +
            bagRect.height / 2;
    }

    floating.style.left = `${x}px`;
    floating.style.top = `${y}px`;

    if (critical) {
        floating.style.color = "#fbbf24";
    }

    gameArea.appendChild(floating);

    setTimeout(() => {
        floating.remove();
    }, 800);
}


/* -------------------------
   STATS
------------------------- */

function updateStats() {

    scoreElement.textContent =
        score.toLocaleString("tr-TR");

    hitsElement.textContent =
        hits;

    comboElement.textContent =
        `x${combo}`;

    const scores =
        getScores();

    const best =
        scores.length
            ? Math.max(...scores.map(x => x.score))
            : 0;

    bestElement.textContent =
        best.toLocaleString("tr-TR");
}


/* -------------------------
   LEADERBOARD
------------------------- */

function getScores() {

    try {

        return JSON.parse(
            localStorage.getItem("bossBagScores")
        ) || [];

    } catch {

        return [];

    }
}


function saveScore(
    name,
    score,
    combo
) {

    const scores =
        getScores();

    scores.push({
        name: name,
        score: score,
        combo: combo,
        date: Date.now()
    });

    scores.sort(
        (a,b) => b.score - a.score
    );

    /*
       Tarayıcıda en iyi 50 skor.
    */

    const topScores =
        scores.slice(0, 50);

    localStorage.setItem(
        "bossBagScores",
        JSON.stringify(topScores)
    );

    updateStats();
}


function renderLeaderboard() {

    const scores =
        getScores();

    leaderboardRows.innerHTML = "";

    if (!scores.length) {

        leaderboardRows.innerHTML = `
            <div class="empty">
                Henüz skor yok. İlk skor senin olsun! 🥊
            </div>
        `;

        return;
    }

    scores.forEach((item, index) => {

        const row =
            document.createElement("div");

        row.className = "row";

        let medal = "";

        if (index === 0) medal = "🥇";
        if (index === 1) medal = "🥈";
        if (index === 2) medal = "🥉";

        row.innerHTML = `
            <div class="rank">
                ${medal || index + 1}
            </div>

            <div>
                ${escapeHtml(item.name)}
            </div>

            <div class="score">
                ${item.score.toLocaleString("tr-TR")}
            </div>

            <div class="combo-score">
                x${item.combo}
            </div>
        `;

        leaderboardRows.appendChild(row);

    });
}


/* -------------------------
   SECURITY
------------------------- */

function escapeHtml(text) {

    return text
        .replaceAll("&", "&amp;")
        .replaceAll("<", "&lt;")
        .replaceAll(">", "&gt;")
        .replaceAll('"', "&quot;")
        .replaceAll("'", "&#039;");
}


/* -------------------------
   RESET
------------------------- */

clearScores.addEventListener(
    "click",
    () => {

        if (
            confirm(
                "Yerel skor tablosu tamamen silinsin mi?"
            )
        ) {

            localStorage.removeItem(
                "bossBagScores"
            );

            renderLeaderboard();
            updateStats();

        }

    }
);


/* -------------------------
   EVENTS
------------------------- */

startBtn.addEventListener(
    "click",
    startGame
);

overlayStart.addEventListener(
    "click",
    startGame
);

finishBtn.addEventListener(
    "click",
    finishGame
);


/*
   pointerdown kullanıyoruz.
   Böylece hem mouse hem dokunmatik
   cihazlarda hızlı tepki verir.
*/

bag.addEventListener(
    "pointerdown",
    hitBag
);


/*
   Enter ile oyuna başlama.
*/

playerName.addEventListener(
    "keydown",
    event => {

        if (event.key === "Enter") {
            startGame();
        }

    }
);


/*
   Combo timeout kontrolü.
   Oyuncu 900ms'den fazla beklerse
   combo göstergesi sıfırlanıyor.
*/

setInterval(() => {

    if (!gameStarted) return;

    if (
        lastHitTime &&
        performance.now() - lastHitTime > COMBO_TIMEOUT
    ) {

        combo = 0;

        comboElement.textContent = "x0";

    }

}, 100);


/* -------------------------
   INITIALIZE
------------------------- */

renderLeaderboard();
updateStats();

</script>

</body>
</html>
