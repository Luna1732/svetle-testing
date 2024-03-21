<svelte:head>
        <title>Контакты</title>
    </svelte:head>
    <div class="container1">
        <h1>    <span class="red">К</span>
            <span class="black">о</span>
            <span class="blue">н</span>
            <span class="green">т</span>
            <span class="orange">а</span>
            <span class="purple">к</span>
            <span class="yellow">т</span>
            <span class="pink">ы</span>
        </h1>

        <div class="social-buttons">
            <button class="telegram" onclick="window.location.href = 'https://t.me/premium';">
                <img src="https://photos.google.com/photo/AF1QipN2jMZ4BgVelAPPJ8M3IypBI4K1E3w-EnkujX7g" alt="Telegram">
            </button>
            <button class="whatsapp" onclick="window.location.href = 'https://wa.me/+79434314511';">
                <img src="/src/lib/Images/whatsapp-png-whatsapp-logo-vetor-png-5000.png" alt="WhatsApp">
            </button>
            <button class="vk" onclick="window.location.href = 'https://www.4chan.org/?ref=infernosites';">
                <img src="/src/lib/Images/vk-4096.png" alt="VKontakte">
            </button>
        </div>
    </div>
    
    <style>
        .social-buttons {
            display: flex;
            justify-content: space-between;
            margin-top: 20px;
        }
    
        .social-buttons button {
            border: none;
            background-color: transparent;
            cursor: pointer;
        }
    
        .social-buttons button img {
            width: 400px; /* Размер логотипа */
        }
    
        .container1 {
            background: url(https://photos.app.goo.gl/ujRQBzWpH5hKG1gD9) center center/cover no-repeat;
    }
      
    .red { color: red; }
    .green { color: green; }
    .blue { color: blue; }
    .orange { color: orange; }
    .purple { color: purple; }
    .yellow { color: yellow; }
    .pink   { color: pink; }
      
    </style>
    
