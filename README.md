<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>FIRE Movement - 당신의 재무적 독립을 위한 도구</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: 'Arial', sans-serif;
            line-height: 1.6;
            color: #333;
        }
        .container {
            width: 100%;
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }
        .banner {
            background-color: #ff5733;
            color: white;
            padding: 10px 0;
            text-align: center;
            font-weight: bold;
        }
        header {
            background-color: #fff;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            padding: 20px 0;
        }
        header .container {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        .logo {
            font-size: 24px;
            font-weight: bold;
            color: #ff5733;
        }
        nav ul {
            list-style: none;
            display: flex;
        }
        nav ul li {
            margin-left: 20px;
        }
        nav ul li a {
            text-decoration: none;
            color: #333;
        }
        .hero {
            background-color: #f9f9f9;
            padding: 80px 0;
            text-align: center;
        }
        .hero h1 {
            font-size: 2.5em;
            margin-bottom: 20px;
        }
        .cta-button {
            display: inline-block;
            background-color: #ff5733;
            color: white;
            padding: 12px 24px;
            text-decoration: none;
            border-radius: 5px;
            font-weight: bold;
            margin-top: 20px;
        }
        .features, .strategies, .pricing {
            padding: 60px 0;
        }
        .feature-grid, .strategy-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 30px;
            margin-top: 40px;
        }
        .feature, .strategy {
            background-color: #fff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
        }
        .pricing-plans {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
            margin-top: 40px;
        }
        .pricing-plan {
            background-color: #fff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
            width: 100%;
            max-width: 400px;
            margin-bottom: 20px;
        }
        .coming-soon {
            background-color: #f0f0f0;
            border: 2px dashed #ccc;
        }
        footer {
            background-color: #333;
            color: #fff;
            padding: 40px 0;
            text-align: center;
        }
        .video-container {
            margin: 40px 0;
        }
        .video-container h2 {
            margin-bottom: 20px;
            font-size: 1.5em;
            color: #333;
        }
        .video-container img {
            max-width: 100%;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
            cursor: pointer;
        }
        .video-container p {
            margin-top: 10px;
            font-style: italic;
            color: #666;
        }
        .calculator {
            background-color: #f9f9f9;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
            margin-top: 20px;
        }
        .calculator h3 {
            margin-bottom: 15px;
        }
        .calculator-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 20px;
        }
        .input-group {
            margin-bottom: 15px;
        }
        .input-group label {
            display: block;
            margin-bottom: 5px;
        }
        .input-group input {
            width: 100%;
            padding: 8px;
            border: 1px solid #ddd;
            border-radius: 4px;
        }
        .result {
            background-color: #0077be;
            color: white;
            padding: 15px;
            text-align: center;
            font-size: 1.2em;
            border-radius: 4px;
            margin-top: 20px;
        }
        .input-won::before {
            content: "₩";
            position: absolute;
            left: 10px;
            top: 50%;
            transform: translateY(-50%);
        }
        .input-won {
            position: relative;
        }
        .input-won input {
            padding-left: 25px;
        }
        @media (max-width: 768px) {
            header .container {
                flex-direction: column;
            }
            nav ul {
                margin-top: 20px;
            }
            nav ul li {
                margin: 0 10px;
            }
            .calculator-grid {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <div class="banner">
        <div class="container">
            현재 모든 기능 무료 이용 가능 - 프리미엄 기능 곧 출시 예정!
        </div>
    </div>
    <header>
        <div class="container">
            <div class="logo">FIRE Movement</div>
            <nav>
                <ul>
                    <li><a href="#features">기능</a></li>
                    <li><a href="#strategies">전략</a></li>
                    <li><a href="#calculator">계산기</a></li>
                    <li><a href="#pricing">요금제</a></li>
                    <li><a href="#contact">문의</a></li>
                </ul>
            </nav>
        </div>
    </header>
    <section class="hero">
        <div class="container">
            <h1>당신의 재무적 독립을 위한 움직임</h1>
            <p>Financial Independence, Retire Early - 더 빠르고 스마트하게 재무적 자유를 실현하세요.</p>
            <div class="video-container">
                <h2>매일 인사이트를 얻어 가세요!</h2>
                <a href="https://www.youtube.com/watch?v=ImIGpbtgtiY" target="_blank">
                    <img src="https://img.youtube.com/vi/ImIGpbtgtiY/0.jpg" alt="YouTube 비디오 썸네일" style="width:100%; max-width:560px;">
                </a>
                <p>비디오를 보려면 이미지를 클릭하세요</p>
            </div>
            <a href="#" class="cta-button">무료로 시작하기</a>
        </div>
    </section>
    <section id="features" class="features">
        <div class="container">
            <h2>주요 기능</h2>
            <div class="feature-grid">
                <div class="feature">
                    <h3>포트폴리오 관리</h3>
                    <p>다양한 자산을 한 눈에 관리하고 분석하세요.</p>
                </div>
                <div class="feature">
                    <h3>자산 배분 최적화</h3>
                    <p>개인의 목표에 맞는 최적의 자산 배분을 제안합니다.</p>
                </div>
                <div class="feature">
                    <h3>실시간 동기화</h3>
                    <p>PC, 태블릿, 모바일에서 실시간으로 데이터가 동기화됩니다.</p>
                </div>
                <div class="feature">
                    <h3>FIRE 계산기</h3>
                    <p>나만의 FIRE 달성 시기를 계산해보세요.</p>
                </div>
            </div>
        </div>
    </section>
    <section id="strategies" class="strategies">
        <div class="container">
            <h2>FIRE 전략</h2>
            <div class="strategy-grid">
                <div class="strategy">
                    <h3>지출 최적화</h3>
                    <p>불필요한 지출을 줄이고 저축률을 높이세요.</p>
                </div>
                <div class="strategy">
                    <h3>투자 다각화</h3>
                    <p>다양한 자산에 투자하여 리스크를 분산하세요.</p>
                </div>
                <div class="strategy">
                    <h3>패시브 인컴</h3>
                    <p>추가적인 수입원을 만들어 재무적 안정성을 높이세요.</p>
                </div>
                <div class="strategy">
                    <h3>세금 최적화</h3>
                    <p>효율적인 세금 관리로 순자산을 늘리세요.</p>
                </div>
            </div>
        </div>
    </section>
    <section id="calculator" class="calculator">
        <div class="container">
            <h2>FIRE 계산기 – 얼마나 많은 돈이 필요할까요?</h2>
            <p>이 계산기를 사용하여 당신만의 FIRE 숫자를 추정할 수 있습니다. 하지만 이 숫자에 대해 스트레스 받지 않는 것이 중요하며, 당신의 상황이 변함에 따라 이 숫자도 변할 수 있음을 이해해야 합니다. 핵심은 추정치를 계산하고, 성장하고 삶이 변화함에 따라 자신의 숫자를 조정하는 데 익숙해지는 것입니다.</p>
            <div class="calculator-grid">
                <div class="base-assumptions">
                    <h3>기본 가정</h3>
                    <div class="input-group input-won">
                        <label for="current-expenses">현재 연간 지출</label>
                        <input type="number" id="current-expenses" placeholder="36,000,000">
                    </div>
                    <div class="input-group">
                        <label for="withdrawal-rate">목표 인출률: <span id="withdrawal-rate-value">4.0</span>%</label>
                        <input type="range" id="withdrawal-rate" min="1" max="10" value="4" step="0.1">
                    </div>
                    <div class="input-group">
                        <label for="investment-return">예상 연간 투자 수익률: <span id="investment-return-value">7.0</span>%</label>
                        <input type="range" id="investment-return" min="1" max="15" value="7" step="0.1">
                    </div>
                    <div class="input-group input-won">
                        <label for="recurring-income">월 경상 소득 (임대료, 부업 등)</label>
                        <input type="number" id="recurring-income" placeholder="0">
                    </div>
                </div>
                <div class="future-expenses">
                    <h3>일회성 미래 지출</h3>
                    <div class="input-group input-won">
                        <label for="expense1">지출 1</label>
                        <input type="number" id="expense1" placeholder="0">
                        <input type="number" id="expense1-years" placeholder="0년 후">
                    </div>
                    <div class="input-group input-won">
                        <label for="expense2">지출 2</label>
                        <input type="number" id="expense2" placeholder="0">
                        <input type="number" id="expense2-years" placeholder="0년 후">
                    </div>
                    <div class="input-group input-won">
                        <label for="expense3">지출 3</label>
                        <input type="number" id="expense3" placeholder="0">
                        <input type="number" id="expense3-years" placeholder="0년 후">
                    </div>
                    <div class="input-group input-won">
                        <label for="expense4">지출 4</label>
                        <input type="number" id="expense4" placeholder="0">
                        <input type="number" id="expense4-years" placeholder="0년 후">
                    </div>
                </div>
            </div>
            <div class="result">
                <h3>당신의 재무적 독립 숫자:</h3>
                <p id="fi-number">₩900,000,000</p>
            </div>
        </div>
    </section>

    <script>
    // FIRE 계산기 로직
    function calculateFIRE() {
        const currentExpenses = parseFloat(document.getElementById('current-expenses').value) || 0;
        const withdrawalRate = parseFloat(document.getElementById('withdrawal-rate').value) / 100;
        const investmentReturn = parseFloat(document.getElementById('investment-return').value) / 100;
        const recurringIncome = (parseFloat(document.getElementById('recurring-income').value) || 0) * 12;

        // 일회성 미래 지출 계산 (간단화를 위해 현재 무시)

        const annualExpenses = currentExpenses - recurringIncome;
        const fireNumber = annualExpenses / withdrawalRate;

        document.getElementById('fi-number').textContent = `₩${fireNumber.toFixed(0).replace(/\B(?=(\d{3})+(?!\d))/g, ",")}`;
    }

    // 모든 입력 필드에 이벤트 리스너 추가
    document.querySelectorAll('#calculator input').forEach(input => {
        input.addEventListener('input', calculateFIRE);
    });

    // 초기 계산
    calculateFIRE();

    // 슬라이더 값 실시간 업데이트
    document.getElementById('withdrawal-rate').addEventListener('input', function() {
        document.getElementById('withdrawal-rate-value').textContent = this.value;
        calculateFIRE();
    });

    document.getElementById('investment-return').addEventListener('input', function() {
        document.getElementById('investment-return-value').textContent = this.value;
        calculateFIRE();
    });
    </script>
    <section id="savings-calculator" class="savings-calculator">
        <div class="container">
            <h2>Savings Calculator</h2>
            <p>이 계산기를 사용하여 재무 목표 달성에 필요한 저축 금액을 계산해보세요.</p>
            <div class="calculator-input">
                <div class="input-group">
                    <label for="financial-freedom-target">재무 자유 목표액 (₩)</label>
                    <input type="number" id="financial-freedom-target" placeholder="1000000000">
                </div>
                <div class="input-group">
                    <label for="current-savings">현재 저축액 (₩)</label>
                    <input type="number" id="current-savings" placeholder="0">
                </div>
                <div class="input-group">
                    <label for="years-to-target">목표 달성 기간 (년)</label>
                    <input type="number" id="years-to-target" placeholder="15" min="1" max="50">
                </div>
            </div>
            <div class="calculator-results">
                <h3>기간과 저축금액에 따른 결과:</h3>
                <table class="results-table">
                    <thead>
                        <tr>
                            <th>기간</th>
                            <th>저축 금액</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr>
                            <td>연간</td>
                            <td id="annual-savings">₩0</td>
                        </tr>
                        <tr>
                            <td>월간</td>
                            <td id="monthly-savings">₩0</td>
                        </tr>
                        <tr>
                            <td>주간</td>
                            <td id="weekly-savings">₩0</td>
                        </tr>
                        <tr>
                            <td>일간</td>
                            <td id="daily-savings">₩0</td>
                        </tr>
                    </tbody>
                </table>
            </div>
        </div>
    </section>

    <script>
    // Savings 계산기 로직
    function calculateSavings() {
        const target = parseFloat(document.getElementById('financial-freedom-target').value) || 0;
        const current = parseFloat(document.getElementById('current-savings').value) || 0;
        const years = parseFloat(document.getElementById('years-to-target').value) || 15;

        const totalSavingsNeeded = target - current;
        const annualSavings = totalSavingsNeeded / years;
        const monthlySavings = annualSavings / 12;
        const weeklySavings = annualSavings / 52;
        const dailySavings = annualSavings / 365;

        document.getElementById('annual-savings').textContent = `₩${annualSavings.toFixed(0).replace(/\B(?=(\d{3})+(?!\d))/g, ",")}`;
        document.getElementById('monthly-savings').textContent = `₩${monthlySavings.toFixed(0).replace(/\B(?=(\d{3})+(?!\d))/g, ",")}`;
        document.getElementById('weekly-savings').textContent = `₩${weeklySavings.toFixed(0).replace(/\B(?=(\d{3})+(?!\d))/g, ",")}`;
        document.getElementById('daily-savings').textContent = `₩${dailySavings.toFixed(0).replace(/\B(?=(\d{3})+(?!\d))/g, ",")}`;
    }

    // 모든 입력 필드에 이벤트 리스너 추가
    document.querySelectorAll('#savings-calculator input').forEach(input => {
        input.addEventListener('input', calculateSavings);
    });

    // 초기 계산
    calculateSavings();
    </script>

            <section id="pricing" class="pricing">
                <div class="container">
                    <h2>요금제</h2>
                    <div class="pricing-plans">
                        <div class="pricing-plan">
                            <h3>기본 플랜 (현재 무료)</h3>
                            <ul>
                                <li>기본 포트폴리오 관리</li>
                                <li>자산 배분 가이드</li>
                                <li>FIRE 기본 계산기</li>
                                <li>실시간 동기화</li>
                            </ul>
                            <a href="#" class="cta-button">무료로 시작하기</a>
                        </div>
                        <div class="pricing-plan coming-soon">
                            <h3>프리미엄 플랜 (출시 예정)</h3>
                            <ul>
                                <li>고급 포트폴리오 분석</li>
                                <li>AI 기반 자산 배분</li>
                                <li>실시간 시장 분석</li>
                                <li>전문가 1:1 상담</li>
                            </ul>
                            <p>곧 출시됩니다!</p>
                        </div>
                    </div>
                </div>
            </section>

    <html lang="ko">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>FIRE Movement - 당신의 재무적 독립을 위한 도구</title>
        <style>
            /* 기존 스타일 코드 */

            /* 여기에 새로운 footer 스타일 추가 */
            footer a {
                color: #ff5733;
                text-decoration: none;
            }

            footer a:hover {
                text-decoration: underline;
            }
        </style>
    </head>
    <body>
        <!-- 기존 body 내용 -->

        <!-- 여기에 새로운 footer 추가 -->
        <footer id="contact">
            <div class="container">
                <p>© 2024 FIRE Movement - 현재 모든 기능 무료 제공 중. 향후 요금제 변경될 수 있음.</p>
                <p>문의: <a href="mailto:contact@firemovement.com">contact@firemovement.com</a></p>
            </div>
        </footer>
    </body>
    </html>
        </body>
        </html>
