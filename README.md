from pathlib import Path

# HTML content based on user's provided information
html_content = """
<!DOCTYPE html>
<html lang="zh-Hant">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>張育慈 - 房仲專業顧問</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            color: #333;
            margin: 0;
            padding: 20px;
            background-color: #f4f4f4;
        }
        .container {
            max-width: 900px;
            margin: auto;
            background: #fff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h1 {
            color: #4CAF50;
        }
        p {
            margin: 10px 0;
        }
        .contact-info {
            font-weight: bold;
            margin-top: 20px;
        }
        .service-list, .case-list {
            list-style-type: disc;
            margin-left: 20px;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>張育慈 - 房仲專業顧問</h1>
        <p>聯絡方式：0909-286636（Line同號）</p>

        <h2>職業背景</h2>
        <p>您好，我是張育慈，擁有18年的業務經驗，曾在全球知名的美商企業 Bristol Myers Squibb 及全台最大代理商 Harvest Co 擔任醫藥業務。兩年前，我決定轉戰房地產領域，並迅速在此領域中崛起。我的專業不僅限於房屋買賣，還涵蓋了市場趨勢分析、資產規劃、稅務計算等多方面，幫助買家在快速變化的房地產市場中做出明智選擇，達成他們的理想目標。</p>

        <h2>個人能力與服務特色</h2>
        <p>作為一名房仲人員，我深知購房是人生中的重大決定。為此，我提供以下專業服務，確保客戶在每一個交易過程中都能享有最貼心且專業的支持：</p>
        <ul class="service-list">
            <li><strong>精準的市場趨勢洞察</strong>：通過對市場動態和區域發展的深入了解，我能夠為客戶提供最新、最具價值的市場資訊，幫助他們在合適的時間做出最佳購買或賣出決策。</li>
            <li><strong>量身訂製的資產規劃</strong>：無論是首次購屋還是換屋需求，我都根據每位客戶的財務狀況與生活需求，提供量身訂製的資產規劃建議，確保每筆交易不僅符合當前需求，還具備長遠的增值潛力。</li>
            <li><strong>精通稅務計算與法規</strong>：購房涉及到的稅務與法律問題往往讓買賣雙方頭痛。我熟知相關稅務法規，能協助客戶做出合理規劃，減少購屋後的負擔與風險。</li>
            <li><strong>全程陪伴的服務理念</strong>：無論是看房過程還是簽約細節，我都親自跟進每個環節，並提供專業諮詢，確保每位客戶的需求都能被細心照顧。</li>
        </ul>

        <h2>銷售經歷</h2>
        <p>過去兩年，我有幸成功促成了多項房地產交易，為許多家庭實現了幸福安居的夢想。以下是部分成功案例：</p>
        <ul class="case-list">
            <li>新光特區 又一城花園別墅，協助客戶圓夢成交</li>
            <li>北屯區 總太2020兩房平車，小資成家成交</li>
            <li>總太青境 三房平車 視野公園戶，結婚成家成交</li>
            <li>東區 新業築願景，新竹工程師移居幸福成交</li>
            <li>西屯區 親家7up，台北移居幸福成交</li>
            <li>北屯區 晴綻花園三房車位，幸福三口換屋成交</li>
            <li>太平區 慶吉兩房，小資迎親房幸福成交</li>
            <li>北屯區 奧林匹克雙車別墅，一家四口歡喜移居成交</li>
            <li>太平區 非常台中 三房，彰化學子考上中一中快樂成交</li>
            <li>大里區 新生路公寓三房，好友三人共同開啟同住歡樂成交</li>
            <li>太平區 非常台中，協助長期租屋的一家四口擁有專屬的幸福家園</li>
        </ul>
        <p>這些幸福故事還在不斷延續，期待與您攜手共創下一個幸福篇章。如果您正在尋找夢想中的家，或希望進一步了解市場趨勢、資產規劃等資訊，隨時歡迎聯繫我。讓我們一起實現您的理想家園！</p>

        <div class="contact-info">
            張育慈<br>
            0909-286636（Line同號）
        </div>
    </div>
</body>
</html>
"""

# Write the HTML content to a file
output_path = Path("/mnt/data/zhang_yuci_real_estate.html")
output_path.write_text(html_content, encoding="utf-8")

output_path


<!---
Chris0909286636/Chris0909286636 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
