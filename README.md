# lnxnwniie.github.io
<!DOCTYPE html>
<html>
<head>
    <title>给 小吉小宝的专属网站</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            text-align: center;
            background: url('https://imgur.com/a/cGdGVps') no-repeat center/cover;
            padding: 20px;
        }
        .container {
            background: rgba(255, 255, 255, 0.9);
            max-width: 600px;
            margin: 50px auto;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        h1 { color: #ff6b6b; }
        form { margin-top: 20px; }
        input, textarea, button { 
            width: 80%; 
            padding: 10px; 
            margin: 10px; 
            border: 1px solid #ddd; 
            border-radius: 5px;
        }
        button { 
            background: #4CAF50; 
            color: white; 
            border: none; 
            cursor: pointer;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>💗 Iove You, 张极张泽禹！</h1>
        <p>欢迎留下你的祝福或回忆～</p>
        
        <!-- 留言表单 -->
        <form action="https://formspree.io/f/xeoajpbe" method="POST">
            <input type="text" name="name" placeholder="你的名字" required>
            <textarea name="message" placeholder="写下祝福..." rows="4" required></textarea>
            <button type="submit">发送祝福</button>
        </form>
    </div>
</body>
</html>