# 3d-printing-quote-site
3d列印估價網
<!DOCTYPE html>
<html lang="zh">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>3D列印估價網站</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #333;
            color: white;
            padding: 10px 0;
            text-align: center;
        }
        nav a {
            color: white;
            text-decoration: none;
            padding: 10px;
        }
        .container {
            max-width: 1200px;
            margin: 20px auto;
            padding: 20px;
            background-color: white;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h1, h2 {
            text-align: center;
        }
        .file-upload, .examples, .info, .calculator, .registration, .contact {
            margin-bottom: 40px;
        }
        .file-upload input, .contact textarea {
            width: 100%;
            padding: 10px;
            margin-top: 10px;
        }
        .chat {
            position: fixed;
            bottom: 20px;
            right: 20px;
            background-color: #007bff;
            color: white;
            padding: 10px;
            border-radius: 5px;
            cursor: pointer;
        }
        .social-links a {
            margin-right: 10px;
        }
    </style>
</head>
<body>
    <header>
        <h1>3D列印估價網站</h1>
        <nav>
            <a href="#upload">上傳設計文件</a>
            <a href="#examples">案例展示</a>
            <a href="#info">3D列印資訊</a>
            <a href="#calculator">價格計算器</a>
            <a href="#registration">用戶註冊</a>
            <a href="#contact">聯絡我們</a>
        </nav>
    </header>
    
    <div class="container">
        <section id="upload" class="file-upload">
            <h2>上傳設計文件</h2>
            <form>
                <input type="file" name="design-file" accept=".stl, .obj">
                <button type="submit">上傳</button>
            </form>
        </section>
        
        <section id="examples" class="examples">
            <h2>案例展示</h2>
            <p>這裡展示一些3D列印的案例。</p>
            <!-- 範例圖片和描述 -->
        </section>
        
        <section id="info" class="info">
            <h2>3D列印資訊</h2>
            <p>這裡提供關於3D列印材料、技術和價格範圍的資訊。</p>
            <!-- 相關資訊 -->
        </section>
        
        <section id="calculator" class="calculator">
            <h2>價格計算器</h2>
            <p>選擇材料和其他選項來計算估價。</p>
            <!-- 價格計算器的表單 -->
        </section>
        
        <section id="registration" class="registration">
            <h2>用戶註冊</h2>
            <form>
                <input type="text" name="username" placeholder="用戶名">
                <input type="password" name="password" placeholder="密碼">
                <button type="submit">註冊</button>
            </form>
        </section>
        
        <section id="contact" class="contact">
            <h2>聯絡我們</h2>
            <form>
                <textarea name="message" placeholder="你的訊息"></textarea>
                <button type="submit">發送</button>
            </form>
        </section>
        
        <div class="social-links">
            <a href="#" target="_blank">Facebook</a>
            <a href="#" target="_blank">Twitter</a>
            <a href="#" target="_blank">Instagram</a>
        </div>
    </div>
    
    <div class="chat" onclick="openChat()">即時聊天</div>
    
    <script>
        function openChat() {
            alert("這裡應該打開即時聊天窗口。");
            // 這裡會集成即時聊天的實際代碼，例如使用第三方服務或API
        }
    </script>
</body>
</html>
