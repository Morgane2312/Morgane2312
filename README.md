<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MasterJudah - Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #0d1117;
            color: #c9d1d9;
            margin: 0;
            padding: 0;
        }

        header {
            text-align: center;
            padding: 20px;
            background-color: #161b22;
        }

        header h1 {
            color: #58a6ff;
            font-size: 2.5rem;
        }

        header p {
            margin-top: 5px;
            font-size: 1.2rem;
            color: #8b949e;
        }

        section {
            margin: 20px auto;
            max-width: 900px;
            padding: 20px;
            background-color: #161b22;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }

        section h2 {
            border-bottom: 2px solid #58a6ff;
            padding-bottom: 5px;
            margin-bottom: 20px;
            color: #58a6ff;
        }

        .icons-container {
            display: flex;
            flex-wrap: wrap;
            gap: 15px;
        }

        .icons-container img {
            width: 50px;
            height: 50px;
            transition: transform 0.3s;
        }

        .icons-container img:hover {
            transform: scale(1.2);
        }

        .profile-stats, .footer {
            text-align: center;
            margin: 20px auto;
        }

        .footer {
            font-size: 0.9rem;
            color: #8b949e;
        }

        .button-support {
            display: inline-block;
            padding: 10px 20px;
            color: #fff;
            background-color: #238636;
            text-decoration: none;
            border-radius: 5px;
            font-size: 1rem;
            transition: background-color 0.3s;
        }

        .button-support:hover {
            background-color: #2ea043;
        }
    </style>
</head>
<body>

<header>
    <h1>MasterJudah here 🔥!</h1>
    <p>Namaste 🙏 I'm Joshua Thadi</p>
</header>

<section>
    <h2>About Me</h2>
    <p>🌍 Based in France</p>
    <p>🌱 Currently learning web-oriented programming</p>
    <p>🤝 Open to collaboration on open-source projects</p>
</section>

<section>
    <h2>Languages & Tools</h2>
    <div class="icons-container">
        <img src="https://github.com/user-attachments/assets/689ee4d6-cffa-406d-abdd-ad02bbfcff72" alt="HTML">
        <img src="https://github.com/user-attachments/assets/5945e9f4-f1b4-457b-a416-9bcfc17373fb" alt="CSS">
        <img src="https://github.com/user-attachments/assets/99d10541-9cdc-496b-be6e-0fa8a33f2e56" alt="JavaScript">
        <img src="https://github.com/user-attachments/assets/6cc147aa-a913-4884-9184-ead80772fa98" alt="PHP">
        <img src="https://github.com/user-attachments/assets/1b10a3ca-6e2a-426e-987b-0fc780e128a2" alt="WordPress">
    </div>
</section>

<section>
    <h2>Platforms</h2>
    <div class="icons-container">
        <img src="https://github.com/user-attachments/assets/0fe84737-1f5f-4e65-bab6-fe9a5fd6fcfa" alt="iOS">
        <img src="https://github.com/user-attachments/assets/a3a4e555-4251-426f-add6-d4f83a73077f" alt="Windows">
    </div>
</section>

<section>
    <h2>Design Tools</h2>
    <div class="icons-container">
        <img src="https://github.com/user-attachments/assets/30c6ed56-2b45-48c5-b801-f9e7708ed1bf" alt="Photoshop">
        <img src="https://github.com/user-attachments/assets/3a6c2741-ce03-431e-9966-d57e0655fd1d" alt="InDesign">
        <img src="https://github.com/user-attachments/assets/18531da6-1a17-462d-80ad-99554a697f6b" alt="Figma">
    </div>
</section>

<section class="profile-stats">
    <h2>Support Me</h2>
    <a href="#" class="button-support">Buy Me a Coffee</a>
</section>

<footer class="footer">
    <p>&copy; 2024 MasterJudah. All rights reserved.</p>
</footer>

</body>
</html>
