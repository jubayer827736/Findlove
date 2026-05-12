<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Task Earn Pro - Premium Reward App</title>
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">
    <!-- Font Awesome for Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    
    <style>
        :root {
            --primary: #00f2fe;
            --secondary: #4facfe;
            --accent: #f093fb;
            --danger: #ff416c;
            --bg: #0b0e14;
            --card-bg: rgba(255, 255, 255, 0.05);
            --glass-border: rgba(255, 255, 255, 0.1);
            --text-main: #ffffff;
            --text-dim: #b0b3b8;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Poppins', sans-serif;
            -webkit-tap-highlight-color: transparent;
        }

        body {
            background: var(--bg);
            color: var(--text-main);
            display: flex;
            justify-content: center;
            min-height: 100vh;
            overflow-x: hidden;
        }

        /* --- UI Containers --- */
        .app-container {
            width: 100%;
            max-width: 480px;
            background: radial-gradient(circle at top right, #1a222f, #0b0e14);
            min-height: 100vh;
            position: relative;
            padding-bottom: 80px;
        }

        /* --- Header --- */
        header {
            background: rgba(11, 14, 20, 0.8);
            backdrop-filter: blur(15px);
            padding: 20px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            position: sticky;
            top: 0;
            z-index: 100;
            border-bottom: 1px solid var(--glass-border);
        }

        .logo-section {
            display: flex;
            align-items: center;
            gap: 10px;
        }

        .logo-icon {
            font-size: 24px;
            background: linear-gradient(45deg, var(--primary), var(--secondary));
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        .app-name { font-weight: 700; font-size: 1.1rem; }

        .balance-badge {
            background: linear-gradient(135deg, var(--primary), var(--secondary));
            padding: 6px 15px;
            border-radius: 20px;
            font-weight: 600;
            box-shadow: 0 4px 15px rgba(0, 242, 254, 0.3);
            font-size: 0.9rem;
        }

        /* --- Dashboard Stats --- */
        .stats-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 12px;
            padding: 20px;
        }

        .stat-card {
            background: var(--card-bg);
            padding: 15px;
            border-radius: 15px;
            border: 1px solid var(--glass-border);
            text-align: center;
        }

        .stat-card i { color: var(--accent); margin-bottom: 5px; }
        .stat-val { font-size: 1.2rem; font-weight: 700; display: block; }
        .stat-label { font-size: 0.75rem; color: var(--text-dim); }

        /* --- Warning Notice --- */
        .warning-box {
            margin: 0 20px;
            padding: 15px;
            background: rgba(255, 65, 108, 0.1);
            border: 1px solid var(--danger);
            border-radius: 12px;
            color: var(--danger);
            font-size: 0.85rem;
            text-align: center;
            animation: glow-red 2s infinite alternate;
        }

        @keyframes glow-red {
            from { box-shadow: 0 0 5px rgba(255, 65, 108, 0.2); }
            to { box-shadow: 0 0 15px rgba(255, 65, 108, 0.5); }
        }

        /* --- Task Section --- */
        .task-container {
            margin: 20px;
            background: var(--card-bg);
            border-radius: 20px;
            padding: 25px;
            border: 1px solid var(--glass-border);
            backdrop-filter: blur(10px);
        }

        .task-header { margin-bottom: 20px; text-align: center; }
        .task-question { font-size: 1.2rem; font-weight: 600; margin-bottom: 15px; }

        .option-btn {
            width: 100%;
            padding: 12px;
            margin-bottom: 10px;
            background: rgba(255, 255, 255, 0.05);
            border: 1px solid var(--glass-border);
            border-radius: 10px;
            color: white;
            text-align: left;
            transition: 0.3s;
            cursor: pointer;
        }

        .option-btn:active { transform: scale(0.98); background: var(--secondary); }
        .option-btn.selected { background: var(--secondary); border-color: var(--primary); }

        .submit-btn {
            width: 100%;
            padding: 15px;
            margin-top: 10px;
            border: none;
            border-radius: 12px;
            background: linear-gradient(45deg, #00c6ff, #0072ff);
            color: white;
            font-weight: 700;
            font-size: 1rem;
            cursor: pointer;
            box-shadow: 0 4px 15px rgba(0, 114, 255, 0.4);
        }

        .submit-btn:disabled { opacity: 0.5; cursor: not-allowed; }

        /* --- Timer Overlay --- */
        #timer-overlay {
            position: fixed;
            top: 0; left: 0; width: 100%; height: 100%;
            background: rgba(11, 14, 20, 0.98);
            z-index: 1000;
            display: none;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
        }

        .circular-timer {
            position: relative;
            width: 150px;
            height: 150px;
        }

        .timer-svg { transform: rotate(-90deg); }
        .timer-circle-bg { fill: none; stroke: rgba(255,255,255,0.1); stroke-width: 8; }
        .timer-circle-progress {
            fill: none; stroke: var(--primary); stroke-width: 8;
            stroke-dasharray: 440; stroke-dashoffset: 440;
            stroke-linecap: round; transition: stroke-dashoffset 1s linear;
        }

        .timer-text {
            position: absolute;
            top: 50%; left: 50%; transform: translate(-50%, -50%);
            font-size: 2rem; font-weight: 700; color: var(--primary);
        }

        /* --- Withdraw Section --- */
        .withdraw-section {
            margin: 20px;
            background: var(--card-bg);
            border-radius: 20px;
            padding: 20px;
            border: 1px solid var(--glass-border);
        }

        .withdraw-info { margin-bottom: 15px; font-size: 0.9rem; color: var(--text-dim); }

        /* --- Referral Section --- */
        .refer-section {
            margin: 20px;
            background: linear-gradient(135deg, rgba(79, 172, 254, 0.1), rgba(0, 242, 254, 0.1));
            border-radius: 20px;
            padding: 20px;
            border: 1px solid var(--glass-border);
        }

        .refer-code-box {
            background: rgba(0,0,0,0.3);
            padding: 10px;
            border-radius: 8px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-top: 10px;
        }

        /* --- Notifications --- */
        .toast {
            position: fixed;
            bottom: 100px; left: 50%; transform: translateX(-50%);
            background: #333; color: white; padding: 10px 20px;
            border-radius: 30px; font-size: 0.8rem; z-index: 2000;
            display: none; animation: fadeIn 0.3s;
        }

        @keyframes fadeIn { from { opacity: 0; bottom: 80px; } to { opacity: 1; bottom: 100px; } }

        /* --- Bottom Nav --- */
        .bottom-nav {
            position: fixed; bottom: 0; max-width: 480px; width: 100%;
            background: rgba(11, 14, 20, 0.9); backdrop-filter: blur(10px);
            display: flex; justify-content: space-around; padding: 12px;
            border-top: 1px solid var(--glass-border);
        }

        .nav-item { color: var(--text-dim); text-align: center; font-size: 0.7rem; cursor: pointer; }
        .nav-item i { font-size: 1.2rem; display: block; margin-bottom: 4px; }
        .nav-item.active { color: var(--primary); }

        .hidden { display: none !important; }
    </style>
</head>
<body>

<div class="app-container">
    <!-- Header -->
    <header>
        <div class="logo-section">
            <i class="fas fa-bolt logo-icon"></i>
            <span class="app-name">Task Earn Pro</span>
        </div>
        <div class="balance-badge">
            <i class="fas fa-wallet"></i> ৳ <span id="header-balance">0</span>
        </div>
    </header>

    <!-- Page: Dashboard -->
    <div id="page-dashboard">
        <div class="stats-grid">
            <div class="stat-card">
                <i class="fas fa-coins"></i>
                <span class="stat-val" id="stat-today">৳ 0</span>
                <span class="stat-label">Today Earn</span>
            </div>
            <div class="stat-card">
                <i class="fas fa-check-circle"></i>
                <span class="stat-val" id="stat-tasks">0</span>
                <span class="stat-label">Tasks Done</span>
            </div>
        </div>

        <div class="warning-box">
            🔥 <strong>সতর্কবার্তা:</strong> Submit Task এ ক্লিক করার পরে যেই Ad আসুক না কেন, অবশ্যই ৩০ সেকেন্ড অপেক্ষা করতে হবে। অন্যথায় Payment বাতিল করা হবে।
        </div>

        <!-- Task Card -->
        <div class="task-container">
            <div class="task-header">
                <span style="color: var(--primary); font-size: 0.8rem; text-transform: uppercase;">Unlimited Task</span>
            </div>
            <div id="task-box">
                <!-- Task content injected by JS -->
                <p class="task-question" id="q-text">Loading Task...</p>
                <div id="options-container"></div>
                <button class="submit-btn" id="btn-submit" onclick="submitTask()" disabled>Submit Task</button>
            </div>
        </div>

        <!-- Mini Feature: Daily Bonus -->
        <div style="padding: 0 20px 20px;">
            <button class="option-btn" onclick="claimDailyBonus()" style="text-align: center; background: linear-gradient(90deg, #f093fb, #f5576c); border:none;">
                <i class="fas fa-gift"></i> Claim Daily Bonus (৳ 10)
            </button>
        </div>
    </div>

    <!-- Page: Withdraw -->
    <div id="page-withdraw" class="hidden">
        <div class="withdraw-section">
            <h3 style="margin-bottom:15px">Withdraw Money</h3>
            <div class="stat-card" style="margin-bottom:20px">
                <span class="stat-label">Available Balance</span>
                <span class="stat-val" style="font-size:2rem; color:var(--primary)">৳ <span id="withdraw-balance">0</span></span>
            </div>
            <div class="withdraw-info">
                <p><i class="fas fa-info-circle"></i> Minimum Withdraw: ৳ 600</p>
                <p><i class="fas fa-clock"></i> Payment Time: 24 Hours</p>
            </div>
            <button id="btn-withdraw-action" class="submit-btn" onclick="processWithdraw()">
                Minimum 600 টাকা প্রয়োজন
            </button>
        </div>
    </div>

    <!-- Page: Referral -->
    <div id="page-refer" class="hidden">
        <div class="refer-section">
            <h3>Refer & Earn</h3>
            <p style="font-size:0.8rem; color:var(--text-dim); margin-top:5px;">প্রতিটি রেফারেলের জন্য পাবেন ২০ টাকা এবং ২০% লাইফটাইম কমিশন!</p>
            
            <div class="refer-code-box">
                <span id="refer-code" style="font-weight:700; color:var(--primary)">PRO5821</span>
                <button onclick="copyReferral()" style="background:none; border:none; color:white; cursor:pointer">
                    <i class="far fa-copy"></i> Copy
                </button>
            </div>

            <div class="stats-grid" style="padding: 20px 0 0;">
                <div class="stat-card">
                    <span class="stat-val" id="ref-count">0</span>
                    <span class="stat-label">Total Refers</span>
                </div>
                <div class="stat-card">
                    <span class="stat-val" id="ref-earn">৳ 0</span>
                    <span class="stat-label">Refer Income</span>
                </div>
            </div>
        </div>
    </div>

    <!-- Bottom Navigation -->
    <nav class="bottom-nav">
        <div class="nav-item active" onclick="showPage('dashboard', this)">
            <i class="fas fa-home"></i> Dashboard
        </div>
        <div class="nav-item" onclick="showPage('refer', this)">
            <i class="fas fa-users"></i> Refer
        </div>
        <div class="nav-item" onclick="showPage('withdraw', this)">
            <i class="fas fa-wallet"></i> Wallet
        </div>
    </nav>
</div>

<!-- Timer Overlay -->
<div id="timer-overlay">
    <div class="circular-timer">
        <svg class="timer-svg" width="150" height="150">
            <circle class="timer-circle-bg" cx="75" cy="75" r="70"></circle>
            <circle id="progress-bar" class="timer-circle-progress" cx="75" cy="75" r="70"></circle>
        </svg>
        <div class="timer-text" id="timer-num">30</div>
    </div>
    <h2 style="margin-top:20px; color:var(--primary)">Processing Reward...</h2>
    <p style="color:var(--text-dim); margin-top:10px; padding: 0 30px;">বিজ্ঞাপনে ৩০ সেকেন্ড অপেক্ষা করুন। এর আগে ব্যাক করলে টাকা পাবেন না।</p>
</div>

<!-- Toast -->
<div id="toast" class="toast">Success!</div>

<script>
    // --- Config ---
    const ADSTERRA_LINK = "https://www.profitablecpmratenetwork.com/uk084qgw?key=41d92c666f328deb5e8416ad59fb2dc8";
    const WITHDRAW_LINK = "https://www.profitablecpmratenetwork.com/kivumeh6u7?key=4e2fb95dd41c9bd72487d8ab76b54327";
    const REWARD_AMOUNT = 6;
    const MIN_WITHDRAW = 600;

    // --- State Management ---
    let userData = {
        balance: 0,
        todayEarn: 0,
        totalTasks: 0,
        refers: 0,
        refEarn: 0,
        lastBonus: null,
        referCode: "TASK" + Math.floor(1000 + Math.random() * 9000)
    };

    let currentTask = null;
    let selectedOption = null;
    let timerActive = false;

    // --- Initialize ---
    window.onload = () => {
        const savedData = localStorage.getItem('taskEarnPro_data');
        if(savedData) userData = JSON.parse(savedData);
        
        updateUI();
        generateTask();
        checkAntiCheat();
    };

    function updateUI() {
        document.getElementById('header-balance').innerText = userData.balance;
        document.getElementById('withdraw-balance').innerText = userData.balance;
        document.getElementById('stat-today').innerText = "৳ " + userData.todayEarn;
        document.getElementById('stat-tasks').innerText = userData.totalTasks;
        document.getElementById('refer-code').innerText = userData.referCode;
        document.getElementById('ref-count').innerText = userData.refers;
        document.getElementById('ref-earn').innerText = "৳ " + userData.refEarn;

        const wBtn = document.getElementById('btn-withdraw-action');
        if(userData.balance >= MIN_WITHDRAW) {
            wBtn.innerText = "Withdraw Now";
            wBtn.disabled = false;
            wBtn.style.background = "linear-gradient(45deg, #00f2fe, #4facfe)";
        } else {
            wBtn.innerText = `Minimum ${MIN_WITHDRAW} টাকা প্রয়োজন`;
            wBtn.disabled = true;
            wBtn.style.background = "#333";
        }
        
        localStorage.setItem('taskEarnPro_data', JSON.stringify(userData));
    }

    // --- Task Engine ---
    const taskBank = [
        { q: "বাংলাদেশের রাজধানী কোথায়?", a: ["ঢাকা", "খুলনা", "সিলেট", "চট্টগ্রাম"], c: 0 },
        { q: "৫ + ১২ কত হয়?", a: ["১৫", "১৭", "১৮", "২০"], c: 1 },
        { q: "সূর্য কোন দিকে উদিত হয়?", a: ["পশ্চিম", "উত্তর", "পূর্ব", "দক্ষিণ"], c: 2 },
        { q: "আমাদের জাতীয় পশুর নাম কি?", a: ["সিংহ", "রয়েল বেঙ্গল টাইগার", "হাতি", "হরিণ"], c: 1 },
        { q: "১০ x ৩ কত?", a: ["২০", "২৫", "৩০", "৪০"], c: 2 },
        { q: "আইফোন ১৬ প্রো ম্যাক্স কোন কোম্পানির?", a: ["স্যামসাং", "অ্যাপল", "শাওমি", "গুগল"], c: 1 }
    ];

    function generateTask() {
        currentTask = taskBank[Math.floor(Math.random() * taskBank.length)];
        document.getElementById('q-text').innerText = currentTask.q;
        const container = document.getElementById('options-container');
        container.innerHTML = "";
        selectedOption = null;
        document.getElementById('btn-submit').disabled = true;

        currentTask.a.forEach((opt, index) => {
            const btn = document.createElement('button');
            btn.className = "option-btn";
            btn.innerText = opt;
            btn.onclick = () => {
                document.querySelectorAll('.option-btn').forEach(b => b.classList.remove('selected'));
                btn.classList.add('selected');
                selectedOption = index;
                document.getElementById('btn-submit').disabled = false;
            };
            container.appendChild(btn);
        });
    }

    // --- Submission Logic ---
    function submitTask() {
        if(selectedOption === null) return;

        if(selectedOption === currentTask.c) {
            // Open Adsterra Link
            window.open(ADSTERRA_LINK, '_blank');
            startTimer();
        } else {
            showToast("ভুল উত্তর! আবার চেষ্টা করুন।");
            generateTask();
        }
    }

    // --- Timer System ---
    function startTimer() {
        timerActive = true;
        const overlay = document.getElementById('timer-overlay');
        const timerNum = document.getElementById('timer-num');
        const progress = document.getElementById('progress-bar');
        
        overlay.style.display = 'flex';
        let timeLeft = 30;
        const total = 30;

        const interval = setInterval(() => {
            timeLeft--;
            timerNum.innerText = timeLeft;
            
            // Update circular progress
            const offset = 440 - (timeLeft / total) * 440;
            progress.style.strokeDashoffset = offset;

            if(timeLeft <= 0) {
                clearInterval(interval);
                completeTask();
            }
        }, 1000);
    }

    function completeTask() {
        timerActive = false;
        document.getElementById('timer-overlay').style.display = 'none';
        
        userData.balance += REWARD_AMOUNT;
        userData.todayEarn += REWARD_AMOUNT;
        userData.totalTasks += 1;
        
        showToast(`অভিনন্দন! আপনি ৳${REWARD_AMOUNT} পেয়েছেন।`);
        updateUI();
        generateTask();
    }

    // --- Features ---
    function claimDailyBonus() {
        const today = new Date().toDateString();
        if(userData.lastBonus === today) {
            showToast("আপনি আজ বোনাস নিয়েছেন!");
        } else {
            userData.balance += 10;
            userData.lastBonus = today;
            showToast("৳১০ ডেইলি বোনাস সফল!");
            updateUI();
        }
    }

    function processWithdraw() {
        if(userData.balance >= MIN_WITHDRAW) {
            window.location.href = WITHDRAW_LINK;
        }
    }

    function showPage(pageId, navEl) {
        document.querySelectorAll('.app-container > div').forEach(div => {
            if(div.id.startsWith('page-')) div.classList.add('hidden');
        });
        document.getElementById('page-' + pageId).classList.remove('hidden');
        
        document.querySelectorAll('.nav-item').forEach(nav => nav.classList.remove('active'));
        navEl.classList.add('active');
    }

    function copyReferral() {
        navigator.clipboard.writeText(userData.referCode);
        showToast("Referral Code Copied!");
    }

    function showToast(msg) {
        const t = document.getElementById('toast');
        t.innerText = msg;
        t.style.display = 'block';
        setTimeout(() => t.style.display = 'none', 3000);
    }

    // --- Anti Cheat ---
    function checkAntiCheat() {
        document.addEventListener("visibilitychange", () => {
            if (document.hidden && timerActive) {
                alert("Warning: ট্যাব পরিবর্তন করলে রিওয়ার্ড পাবেন না! ৩০ সেকেন্ড অপেক্ষা করুন।");
            }
        });
    }
</script>

</body>
</html>
