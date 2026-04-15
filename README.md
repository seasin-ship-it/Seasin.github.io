# Seasin.github.io[index.html](https://github.com/user-attachments/files/26747870/index.html)
<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>我的个人网站</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Microsoft YaHei', sans-serif;
        }

        body {
            background: #f5f7fa;
            color: #333;
        }

        /* 导航栏 */
        nav {
            background: #2c3e50;
            color: white;
            padding: 18px 30px;
            position: fixed;
            width: 100%;
            top: 0;
            left: 0;
            z-index: 999;
        }

        .container {
            max-width: 1100px;
            margin: 0 auto;
            padding: 0 20px;
        }

        .nav-wrap {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .logo {
            font-size: 22px;
            font-weight: bold;
        }

        .nav-links a {
            color: white;
            text-decoration: none;
            margin-left: 24px;
            font-size: 16px;
        }

        /* 头部横幅 */
        .hero {
            height: 100vh;
            background: linear-gradient(135deg, #42a5f5, #478ed1);
            color: white;
            display: flex;
            align-items: center;
            text-align: center;
            padding-top: 60px;
        }

        .hero-content {
            width: 100%;
        }

        .hero h1 {
            font-size: 48px;
            margin-bottom: 20px;
        }

        .hero p {
            font-size: 20px;
            max-width: 700px;
            margin: 0 auto 30px;
            line-height: 1.6;
        }

        .btn {
            display: inline-block;
            padding: 14px 32px;
            background: white;
            color: #42a5f5;
            border-radius: 50px;
            text-decoration: none;
            font-weight: bold;
            font-size: 16px;
            transition: 0.3s;
        }

        .btn:hover {
            transform: translateY(-3px);
            box-shadow: 0 8px 16px rgba(0,0,0,0.15);
        }

        /* 内容区 */
        .section {
            padding: 80px 0;
            background: white;
        }

        .section h2 {
            text-align: center;
            font-size: 32px;
            margin-bottom: 50px;
            color: #2c3e50;
        }

        .card-group {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 30px;
        }

        .card {
            background: #f9fbfd;
            padding: 30px;
            border-radius: 16px;
            box-shadow: 0 4px 12px rgba(0,0,0,0.05);
            transition: 0.3s;
        }

        .card:hover {
            transform: translateY(-6px);
        }

        .card h3 {
            margin-bottom: 12px;
            color: #2c3e50;
        }

        /* 底部 */
        footer {
            background: #2c3e50;
            color: white;
            text-align: center;
            padding: 30px 0;
        }
    </style>
</head>
<body>

<!-- 导航 -->
<nav>
    <div class="container">
        <div class="nav-wrap">
            <div class="logo">我的网站</div>
            <div class="nav-links">
                <a href="#home">首页</a>
                <a href="#about">关于</a>
                <a href="#service">服务</a>
                <a href="#contact">联系</a>
            </div>
        </div>
    </div>
</nav>

<!-- 首页横幅 -->
<section class="hero" id="home">
    <div class="container hero-content">
        <h1>欢迎来到我的个人网站</h1>
        <p>这里是我的专属展示空间，记录生活、分享作品、展示技能。简约而不简单，干净又好看。</p>
        <a href="#about" class="btn">了解更多</a>
    </div>
</section>

<!-- 关于我 -->
<section class="section" id="about">
    <div class="container">
        <h2>关于我</h2>
        <div style="max-width: 700px; margin: 0 auto; line-height: 1.8; font-size: 17px; text-align: center;">
            我是一名热爱设计与编程的创作者，喜欢制作简洁、实用、高颜值的网站。专注于前端开发、UI设计与内容创作。
        </div>
    </div>
</section>

<!-- 服务/技能 -->
<section class="section" id="service" style="background: #f5f7fa;">
    <div class="container">
        <h2>我的技能</h2>
        <div class="card-group">
            <div class="card">
                <h3>网页设计</h3>
                <p>设计美观、响应式、现代化的网页界面。</p>
            </div>
            <div class="card">
                <h3>前端开发</h3>
                <p>使用 HTML、CSS、JavaScript 开发完整网站。</p>
            </div>
            <div class="card">
                <h3>内容创作</h3>
                <p>撰写文案、制作教程、分享知识与经验。</p>
            </div>
        </div>
    </div>
</section>

<!-- 底部 -->
<footer id="contact">
    <div class="container">
        <p>© 2025 我的个人网站 | 保留所有权利</p>
    </div>
</footer>

</body>
</html>
