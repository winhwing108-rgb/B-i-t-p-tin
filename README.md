 [index.html.](https://github.com/user-attachments/files/25661942/index.html)
<!DOCTYPE html>
<html lang="vi">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Báo Tường 8/3 - Tổ 2 Lớp 12A3</title>

<meta name="description" content="Báo tường chào mừng ngày 8/3 của tổ 2 lớp 12A3">

<style>
body {
    margin: 0;
    font-family: Arial, sans-serif;
    background: linear-gradient(to right, #ff9ccf, #ffd6eb);
    text-align: center;
    overflow-x: hidden;
}

header {
    background: #ff4da6;
    color: white;
    padding: 30px 10px;
}

header h1 {
    margin: 0;
    font-size: 32px;
}

section {
    padding: 20px;
}

.card {
    background: white;
    margin: 20px auto;
    padding: 20px;
    border-radius: 15px;
    max-width: 600px;
    box-shadow: 0 5px 15px rgba(0,0,0,0.2);
}

h2 {
    color: #e60073;
}

footer {
    background: #ff4da6;
    color: white;
    padding: 15px;
    margin-top: 30px;
}

/* Hiệu ứng trái tim rơi */
.heart {
    position: fixed;
    top: -10px;
    color: red;
    animation: fall linear infinite;
}

@keyframes fall {
    to {
        transform: translateY(100vh);
    }
}
</style>
</head>

<body>

<header>
    <h1>🌸 BÁO TƯỜNG 8/3 🌸</h1>
    <p>Tổ 2 - Lớp 12A3</p>
</header>

<section>

<div class="card">
    <h2>🌷 Ý Nghĩa Ngày 8/3</h2>
    <p>
        Ngày 8/3 là ngày Quốc tế Phụ nữ – dịp để tôn vinh những người phụ nữ 
        tuyệt vời trên thế giới. Đây là ngày để chúng ta gửi lời cảm ơn 
        đến mẹ, cô giáo và các bạn nữ thân yêu.
    </p>
</div>

<div class="card">
    <h2>💖 Lời Chúc</h2>
    <p>
        Chúc cô giáo luôn mạnh khỏe, hạnh phúc và thành công.  
        Chúc các bạn nữ lớp 12A3 luôn xinh đẹp, vui vẻ và đạt nhiều thành tích cao!
    </p>
</div>

<div class="card">
    <h2>✨ Thông Điệp Tổ 2</h2>
    <p>
        Tổ 2 xin gửi những lời chúc tốt đẹp nhất đến một nửa thế giới.  
        Mong rằng mỗi ngày đều tràn ngập yêu thương và hạnh phúc!
    </p>
</div>

</section>

<footer>
    © 2026 Tổ 2 - Lớp 12A3
</footer>

<script>
function createHeart() {
    const heart = document.createElement("div");
    heart.classList.add("heart");
    heart.innerHTML = "💗";
    heart.style.left = Math.random() * 100 + "vw";
    heart.style.animationDuration = (Math.random() * 3 + 2) + "s";
    document.body.appendChild(heart);

    setTimeout(() => {
        heart.remove();
    }, 5000);
}

setInterval(createHeart, 300);
</script>

</body>
</html>
