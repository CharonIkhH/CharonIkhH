<h1 align="center">⚠️ ВНИМАНИЕ, USERNAME! ТЫ НА ГРАНИ УНИЧТОЖЕНИЯ ⚠️</h1>
<h3 align="center">🔪 Нет инструкций. Нет гарантий. Только боль и возможности. 🔪</h3>

---

<p align="center">
  <i>Ты на чужой земле, но если готов сражаться — дерзай. Против системы, против правил, против любого, кто встанет на пути.</i>
</p>

<p align="center">
  <b>⚡ В этом мире слабые не выживают. Тебя ждет либо триумф, либо крушение. Решай, на что ты готов. ⚡</b>
</p>

<h3 align="center">🔄 Инициализация захода... Пожалуйста, подождите. 🔄</h3>

<p align="center">
  <i>Загрузка протоколов доступа...</i>
</p>

<p align="center">
  <b>🕑 Текущее время: <span id="current-time"></span></b>
</p>

<p align="center">
  <i>Сканирование системы на наличие уязвимостей...</i>
</p>

<div align="center">
  <progress id="loading" value="0" max="100"></progress>
</div>

<p align="center" id="loading-status"></p>

<script>
  let loadingProgress = 0;
  const loadingInterval = setInterval(() => {
    loadingProgress += Math.floor(Math.random() * 10) + 5; // Увеличение прогресса случайно от 5 до 15
    document.getElementById("loading").value = loadingProgress;
    document.getElementById("loading-status").innerText = `Загрузка: ${loadingProgress}%`;

    if (loadingProgress >= 100) {
      clearInterval(loadingInterval);
      document.getElementById("loading-status").innerText = "✅ Загрузка завершена. Добро пожаловать в систему, USERNAME!";
      document.getElementById("current-time").innerText = new Date().toLocaleTimeString();
    }
  }, 500); // Обновление каждые 500 мс
</script>
