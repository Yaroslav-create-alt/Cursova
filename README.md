<!DOCTYPE html>
<html lang="uk">
<head>
<meta charset="UTF-8">
<title>Меню</title>
<style>
    body {
        margin: 0;
        font-family: Arial, sans-serif;
        background: #111;
    }

    nav {
        background: #1b1b1b;
        padding: 15px 0;
        box-shadow: 0 2px 10px rgba(0,0,0,0.5);
    }

    ul {
        list-style: none;
        margin: 0;
        padding: 0;
        display: flex;
        justify-content: center;
        gap: 35px;
    }

    li a {
        color: #fff;
        text-decoration: none;
        font-size: 18px;
        padding: 8px 12px;
        transition: 0.3s;
        border-radius: 6px;
    }

    li a:hover {
        background: #3a3a3a;
        color: #00eaff;
        transform: translateY(-3px);
    }
</style>
</head>
<body>

<nav>
    <ul>
        <li><a href="#">Головна</a></li>
        <li><a href="#">Про нас</a></li>
        <li><a href="#">Послуги</a></li>
        <li><a href="#">Галерея</a></li>
        <li><a href="#">Контакти</a></li>
    </ul>
</nav>

</body>
</html>
