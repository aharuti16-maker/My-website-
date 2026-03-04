<!DOCTYPE html>
<html lang="ku" dir="rtl">
<head>
    <meta charset="UTF-8">
    <title>احمد سیامند انوەر</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="card">
        <div class="img-bx">
            <img src="https://via.placeholder.com/150" alt="https://www.facebook.com/p/%D8%AC%D9%88%D8%A7%D9%86%D8%AA%D8%B1%DB%8C%D9%86-%D9%88%DB%8E%D9%86%DB%95-100063628214041/ class="profile-img">
        </div>
        <div class="content">
            <h2> ڕۆژانی خەم<br><span>دیزاینەر </span></h2>
            <a href="https://github.com" class="btn">سەردانی گیت‌هاب بکە</a>
        </div>
    </div>
  <style>
    body {
    margin: 0;
    padding: 0;
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
    background: linear-gradient(45deg, #2196f3, #e91e63); /* ڕەنگی پشتێنە */
    font-family: sans-serif;
}
card {
    position: relative;
    width: 320px;
    height: 400px;
    background: rgba(255, 255, 255, 0.1); /* شێوازی شووشەیی */
    border-radius: 20px;
    backdrop-filter: blur(15px);
    border: 1px solid rgba(255, 255, 255, 0.2);
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    color: #fff;
    transition: 0.5s;
}
.card:hover {
    transform: translateY(-10px); /* جوڵە لە کاتی دەست لێدان */
}
.img-bx img {
    width: 120px;
    height: 120px;
    border-radius: 50%;
    border: 3px solid #fff;
}
.content {
    text-align: center;
    margin-top: 20px;
}
.btn {
    display: inline-block;
    padding: 10px 20px;
    background: #fff;
    color: #333;
    border-radius: 25px;
    text-decoration: none;
    font-weight: bold;
    margin-top: 15px;
}
  </style>
</body>
</html>
