# Yuugen-Bespoke
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Yuugen Design Studio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5;
            color: #333;
        }
        header {
            background-color: #2c3e50;
            color: #ecf0f1;
            padding: 20px 0;
            text-align: center;
        }
        header h1 {
            margin: 0;
            font-size: 2.5em;
        }
        .content {
            padding: 20px;
        }
        .intro {
            text-align: center;
            margin-bottom: 20px;
        }
        .intro p {
            font-size: 1.2em;
        }
        .portfolio {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: center;
        }
        .portfolio-item {
            background-color: #fff;
            border: 1px solid #ddd;
            border-radius: 5px;
            overflow: hidden;
            width: 300px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        .portfolio-item img {
            width: 100%;
            height: auto;
        }
        .portfolio-item h3 {
            padding: 10px;
            margin: 0;
            font-size: 1.5em;
        }
        .portfolio-item p {
            padding: 0 10px 10px;
            margin: 0;
        }
        .contact {
            text-align: center;
            margin: 40px 0;
        }
        .contact h2 {
            font-size: 2em;
            margin-bottom: 20px;
        }
        .contact form {
            display: inline-block;
            text-align: left;
            max-width: 400px;
            width: 100%;
        }
        .contact form input, .contact form textarea {
            width: 100%;
            padding: 10px;
            margin-bottom: 10px;
            border: 1px solid #ddd;
            border-radius: 5px;
            box-sizing: border-box;
        }
        .contact form button {
            width: 100%;
            padding: 10px;
            border: none;
            border-radius: 5px;
            background-color: #2c3e50;
            color: #ecf0f1;
            font-size: 1em;
            cursor: pointer;
        }
        footer {
            background-color: #2c3e50;
            color: #ecf0f1;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        footer p {
            margin: 0;
        }
    </style>
</head>
<body>

<header>
    <h1>Yuugen Design Studio</h1>
</header>

<div class="content">
    <div class="intro">
        <p>Yuugen is a multifunctional design studio specializing in design, development, and manufacturing of unique and exclusive furniture and lighting solutions with a focus on sustainability and aesthetic-functional perfection. Our Bespoke line of products offers a wide range of one-of-a-kind pieces, a result of decades of combined experience and creative expression.</p>
    </div>

    <div class="portfolio">
        <div class="portfolio-item">
            <img src="https://via.placeholder.com/300" alt="Portfolio Item 1">
            <h3>Portfolio Item 1</h3>
            <p>Description of Portfolio Item 1.</p>
        </div>
        <div class="portfolio-item">
            <img src="https://via.placeholder.com/300" alt="Portfolio Item 2">
            <h3>Portfolio Item 2</h3>
            <p>Description of Portfolio Item 2.</p>
        </div>
        <!-- Add more portfolio items as needed -->
    </div>
</div>

<div class="contact">
    <h2>Contact Us</h2>
    <form action="mailto:post@yuugen.no" method="post" enctype="text/plain">
        <input type="text" name="name" placeholder="Your Name" required>
        <input type="email" name="email" placeholder="Your Email" required>
        <textarea name="message" placeholder="Your Message" rows="5" required></textarea>
        <button type="submit">Send</button>
    </form>
    <p>Visit us at: <a href="http://www.yuugen.no" target="_blank">www.yuugen.no</a></p>
    <p>Email: <a href="mailto:post@yuugen.no">post@yuugen.no</a></p>
    <p>Phone: +47 966 777 52</p>
    <p>Instagram: <a href="https://www.instagram.com/yuugendesignfabrikk" target="_blank">@YuugenDesignFabrikk</a></p>
</div>

<footer>
    <p>&copy; 2024 Yuugen Design Studio. All rights reserved.</p>
</footer>

</body>
</html>
