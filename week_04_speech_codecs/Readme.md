## Материалы модуля 4

<div align="center">
  <img src="../images/dls.png">
</div>

### Аудио кодеки

На лекции обсудим основополагающую технологию VQ-VAE и дойдем до современных подходов к обучению аудио кодеков. Попутно обсудим все проблемы, которые специфичны для аудио кодеков и узнаем как решать их. В частности, недифференцируемость в процессе обучения, коллапс кодовой книги, неэффективное покрытие домена и репрезентативность для последующих задач. 

Также посмотрим, какие тренды наблюдаются в последних работах. Разберем конкретные примеры актуальных аудио кодеков и как объединить существующие подходы для обучения своего кодека, потенциально лучше текущих. Узнаем о практических советах для обучения кодеков, обсудим дополнительную литературу.

### Лекция

<div style="display: flex; gap: 8px; align-items: baseline; white-space: nowrap; line-height: 1.2; margin-bottom: 16px;">
  <span>Запись лекции &laquo;Аудио кодеки, часть 1&raquo; доступна на</span>
  <a href="https://youtu.be/kOS6qHc6K2g?si=NRuxkxcYAB1eaGnt" target="_blank" rel="noopener" aria-label="Watch on YouTube" style="text-decoration: none;">
    <img src="https://cdn.simpleicons.org/youtube" alt="YouTube" width="20" style="vertical-align: bottom;"> YouTube
  </a>
  <span>и</span>
  <a href="https://vk.com/video-155161349_456239323" target="_blank" rel="noopener" aria-label="Watch on VK" style="text-decoration: none;">
    <img src="https://cdn.simpleicons.org/vk" alt="VK" width="20" style="vertical-align: bottom;"> VK Видео
  </a>
</div>


<div style="display: flex; gap: 8px; align-items: baseline; white-space: nowrap; line-height: 1.2; margin-bottom: 16px;">
  <span>Запись лекции &laquo;Аудио кодеки, часть 1&raquo; доступна на</span>
  <a href="https://youtu.be/kOS6qHc6K2g?si=qulQ8iK0BarTVudQ" target="_blank" rel="noopener" aria-label="Watch on YouTube" style="text-decoration: none;">
    <img src="https://cdn.simpleicons.org/youtube" alt="YouTube" width="20" style="vertical-align: bottom;"> YouTube
  </a>
  <span>и</span>
  <a href="https://vk.com/video-155161349_456239322" target="_blank" rel="noopener" aria-label="Watch on VK" style="text-decoration: none;">
    <img src="https://cdn.simpleicons.org/vk" alt="VK" width="20" style="vertical-align: bottom;"> VK Видео
  </a>
</div>


Занятие ведёт Захар Варфоломеев

### Семинар


[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/DeepLearningSchool/Speech/blob/main/week_04_speech_codecs/Practice/seminar_audio_codecs_dls.ipynb)

<div style="display: flex; gap: 8px; align-items: baseline; white-space: nowrap; line-height: 1.2; margin-bottom: 16px;">
  <span>Запись семинара &laquo;Аудио кодеки, часть 1&raquo; доступна на</span>
  <a href="https://youtu.be/L-z1oGIyboo" target="_blank" rel="noopener" aria-label="Watch on YouTube" style="text-decoration: none;">
    <img src="https://cdn.simpleicons.org/youtube" alt="YouTube" width="20" style="vertical-align: bottom;"> YouTube
  </a>
  <span>и</span>
  <a href="https://vkvideo.ru/video-155161349_456239324" target="_blank" rel="noopener" aria-label="Watch on VK" style="text-decoration: none;">
    <img src="https://cdn.simpleicons.org/vk" alt="VK" width="20" style="vertical-align: bottom;"> VK Видео
  </a>
</div>


В этом семинаре мы обучим поверх кодов Mimi кодека классификатор голосов на мужской и женский 😄

Используем 8 кодбуков, обучаем 8 трансформер-энкодеров, делаем темпоральный пулинг по токенам, а затем атеншн пулинг между энкодерами. Потом обычный классификатор. Из прикольного - визуализация атеншна на разные уровни RVQ.

Научились работать с RVQ и в качестве упражнения можете посчитать разные статистики для кодовых книг, например perpexity по кодбуку (покажет насколько равномерно используются коды) или утилизацию кодов на разных уровнях/на первом. Или попробовать другую простенькую задачу и посмотреть как интерпретируются уровни RVQ, вероятно на разных уровнях содержится разная семантика/смысл.


Занятие ведёт Захар Варфоломеев
