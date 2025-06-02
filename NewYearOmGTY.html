   <!-- Кнопка для показа сюрприза -->
        <button onclick="showSurprise()">Зажечь праздничный салют!</button>
        
        <!-- Подпись -->
        <div class="signature">С уважением, группа ИСТ-241</div>
    </div>
    
    <!-- Секция с сюрпризом (изначально скрыта) -->
    <div class="card hidden" id="surprise">
        <!-- Логотип ОмГТУ -->
        <a href="https://www.omgtu.ru/" target="_blank">
        <img src="C:\Users\хуй с горы\Desktop\кр\image\omgtu.png" alt="Логотип ОмГТУ" class="omgtu-logo">
        </a>
        
        <!-- Заголовок сюрприза -->
        <h1>🎇 С Новым 2025 Годом! 🎇</h1>
        <p>Пусть этот год будет таким же ярким, как наши фейерверки!</p>
        
        <!-- Контейнер для фейерверков -->
        <div id="fireworks-container" style="height: 200px; position: relative; margin: 20px 0;"></div>
        
        <!-- Дополнительный текст -->
        <p>Желаем вам успешной сессии, интересных исследований и новых научных достижений!</p>
        
        <!-- Кнопка для возврата к открытке -->
        <button onclick="backToCard()">Вернуться к открытке</button>
    </div>
    
    <script>
        // Начало JavaScript кода
        
        // Функция для создания снежинок
        function createSnowflakes() {
            const snowflakesCount = 50; // Количество создаваемых снежинок
            
            // Цикл для создания снежинок
            for (let i = 0; i < snowflakesCount; i++) {
                // Задержка для каждой снежинки
                setTimeout(() => {
                    // Создаем элемент div для снежинки
                    const snowflake = document.createElement('div');
                    // Устанавливаем символ снежинки
                    snowflake.innerHTML = '❄';
                    // Добавляем класс snowflake
                    snowflake.classList.add('snowflake');
                    
                    // Устанавливаем случайные свойства:
                    // - Позиция по горизонтали
                    snowflake.style.left = `${Math.random() * 100}vw`;
                    // - Длительность анимации
                    snowflake.style.animationDuration = `${Math.random() * 5 + 5}s`;
                    // - Прозрачность
                    snowflake.style.opacity = Math.random();
                    // - Размер
                    snowflake.style.fontSize = `${Math.random() * 1 + 0.5}em`;
                    
                    // Добавляем снежинку на страницу
                    document.body.appendChild(snowflake);
                    
                    // Удаляем снежинку после завершения анимации
                    setTimeout(() => {
                        snowflake.remove();
                    }, parseFloat(snowflake.style.animationDuration) * 1000);
                }, i * 300); // Задержка между созданием снежинок
            }
        }
        
        // Функция для показа сюрприза
        function showSurprise() {
            // Скрываем основную открытку
            document.getElementById('card').classList.add('hidden');
            // Показываем сюрприз
            document.getElementById('surprise').classList.remove('hidden');
            // Запускаем создание фейерверков
            createFireworks();
        }
        
        // Функция для возврата к открытке
        function backToCard() {
            // Скрываем сюрприз
            document.getElementById('surprise').classList.add('hidden');
            // Показываем основную открытку
            document.getElementById('card').classList.remove('hidden');
        }
        
        // Функция для создания фейерверков
        function createFireworks() {
            // Получаем контейнер для фейерверков
            const container = document.getElementById('fireworks-container');
            // Массив возможных цветов
            const colors = ['#FFD700', '#FFFFFF', '#0066CC', '#FF0000'];
            
            // Создаем 8 фейерверков с интервалом
            for (let i = 0; i < 8; i++) {
                // Задержка для каждого фейерверка
                setTimeout(() => {
                    // Случайная позиция центра фейерверка
                    const centerX = Math.random() * 80 + 10;
                    const centerY = Math.random() * 80 + 10;
                    // Случайный цвет из массива
                    const color = colors[Math.floor(Math.random() * colors.length)];
                    
                    // Создаем 30 частиц для каждого фейерверка
                    for (let j = 0; j < 30; j++) {
                        // Создаем элемент частицы
                        const particle = document.createElement('div');
                        // Добавляем класс firework
                        particle.classList.add('firework');
                        // Устанавливаем позицию
                        particle.style.left = `${centerX}%`;
                        particle.style.top = `${centerY}%`;
                        // Устанавливаем цвет
                        particle.style.backgroundColor = color;
                        // Добавляем свечение
                        particle.style.boxShadow = `0 0 10px 2px ${color}`;
                        
                        // Случайное направление полета частицы
                        const angle = Math.random() * Math.PI * 2;
                        // Случайное расстояние полета
                        const distance = Math.random() * 50 + 30;
                        
                        // Создаем уникальное имя анимации
                        const animationName = `firework-${i}-${j}`;
                        // Определяем ключевые кадры анимации
                        const keyframes = `
                            @keyframes ${animationName} {
                                0% { 
                                    transform: translate(0, 0) scale(1); 
                                    opacity: 1; 
                                }
                                100% { 
                                    transform: translate(${Math.cos(angle) * distance}px, ${Math.sin(angle) * distance}px) scale(0); 
                                    opacity: 0; 
                                }
                            }
                        `;
                        
                        // Создаем элемент стиля с анимацией
                        const style = document.createElement('style');
                        style.innerHTML = keyframes;
                        document.head.appendChild(style);
                        
                        // Применяем анимацию к частице
                        particle.style.animationName = animationName;
                        // Добавляем частицу в контейнер
                        container.appendChild(particle);
                        
                        // Удаляем частицу и стиль после завершения анимации
                        setTimeout(() => {
                            particle.remove();
                            style.remove();
                        }, 1000);
                    }
                }, i * 800); // Интервал между фейерверками
            }
        }
        
        // Инициализация при загрузке страницы
        window.onload = function() {
            // Создаем снежинки
            createSnowflakes();
            // Устанавливаем интервал для создания новых снежинок каждые 10 секунд
            setInterval(createSnowflakes, 10000);
        };
    </script>
</body>
</html>
