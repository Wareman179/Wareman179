<!DOCTYPE html>
<html lang="th">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>เรียนภาษาจีนออนไลน์</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #e0f7fa; /* สีฟ้าอ่อน */
            color: #333;
        }
        header {
            background-color: #00796b; /* สีเขียวเข้ม */
            color: white;
            padding: 20px;
            text-align: center;
            border-bottom: 4px solid #004d40; /* สีเขียวเข้มมาก */
        }
        nav {
            background-color: #004d40; /* สีเขียวเข้มมาก */
            padding: 10px;
            display: flex;
            justify-content: space-around;
            border-bottom: 2px solid #00796b; /* สีเขียวเข้ม */
        }
        nav a {
            color: white;
            text-decoration: none;
            padding: 8px;
            font-weight: bold;
        }
        nav a:hover {
            background-color: #00796b; /* สีเขียวเข้ม */
            border-radius: 4px;
        }
        .hero {
            background: url('hero-image.jpg') no-repeat center center/cover;
            color: white;
            text-align: center;
            padding: 100px 20px;
        }
        .hero h1 {
            font-size: 2.5em;
            margin: 0;
        }
        .hero p {
            font-size: 1.2em;
        }
        main {
            padding: 20px;
            max-width: 1200px;
            margin: 20px auto;
            background-color: #ffffff; /* สีขาว */
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
            border-radius: 8px;
        }
        section {
            margin-bottom: 40px;
        }
        footer {
            background-color: #00796b; /* สีเขียวเข้ม */
            color: white;
            text-align: center;
            padding: 10px;
            border-top: 4px solid #004d40; /* สีเขียวเข้มมาก */
        }
        .cta-button {
            background-color: #004d40; /* สีเขียวเข้มมาก */
            color: white;
            padding: 10px 20px;
            border: none;
            cursor: pointer;
            font-size: 1.2em;
            border-radius: 5px;
            transition: background-color 0.3s, transform 0.3s;
        }
        .cta-button:hover {
            background-color: #00796b; /* สีเขียวเข้ม */
            transform: scale(1.05);
        }
        h1, h2 {
            color: #00796b; /* สีเขียวเข้ม */
        }
        ul {
            list-style-type: none;
            padding: 0;
        }
        li {
            padding: 8px 0;
            border-bottom: 1px solid #ddd;
        }
    </style>
</head>
<body>
    <header>
        <h1>เรียนภาษาจีนออนไลน์</h1>
        <p>เพิ่มทักษะของคุณทุกวันด้วยบทเรียนที่เข้าใจง่าย</p>
    </header>
    
    <nav>
        <a href="#home">หน้าหลัก</a>
        <a href="#courses">คอร์สเรียน</a>
        <a href="#about">เกี่ยวกับเรา</a>
        <a href="#contact">ติดต่อเรา</a>
    </nav>

    <section class="hero">
        <h1>เรียนภาษาจีนได้ทุกที่ ทุกเวลา</h1>
        <p>มาร่วมเรียนรู้ภาษาจีนกับเราวันนี้!</p>
        <button class="cta-button">เริ่มเรียนรู้เลย</button>
    </section>

    <main>
        <section id="home">
            <h2>ยินดีต้อนรับสู่การเรียนภาษาจีนออนไลน์</h2>
            <p>เรียนรู้ภาษาจีนจากระดับพื้นฐานจนถึงระดับสูง ผ่านบทเรียนที่ออกแบบมาเฉพาะเพื่อให้คุณเรียนรู้อย่างเป็นขั้นเป็นตอน</p>
            <button class="cta-button">เริ่มเรียนรู้เลย</button>
        </section>

        <section id="courses">
            <h2>คอร์สเรียนที่มีให้เลือก</h2>
            <ul>
                <li>คอร์สพื้นฐาน: เรียนรู้การออกเสียงและตัวอักษรจีน</li>
                <li>คอร์สกลาง: เรียนรู้ไวยากรณ์และการสนทนาระดับกลาง</li>
                <li>คอร์สขั้นสูง: เรียนรู้การอ่านเขียนบทความและสนทนาขั้นสูง</li>
            </ul>
        </section>

        <section id="about">
            <h2>เกี่ยวกับเรา</h2>
            <p>เราเป็นทีมงานที่มุ่งมั่นให้ผู้เรียนทุกคนสามารถเข้าใจและใช้ภาษาจีนได้อย่างคล่องแคล่ว ด้วยหลักสูตรที่พัฒนาอย่างต่อเนื่องและเหมาะสมกับผู้เรียนทุกระดับ</p>
        </section>

        <section id="contact">
            <h2>ติดต่อเรา</h2>
            <p>อีเมล: contact@chinonline.com</p>
            <p>โทร: 012-345-6789</p>
        </section>
    </main>

    <footer>
        <p>&copy; 2024 เรียนภาษาจีนออนไลน์. All Rights Reserved.</p>
    </footer>
</body>
</html>
