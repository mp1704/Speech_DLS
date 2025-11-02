### Семинар

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/DeepLearningSchool/Speech/blob/main/week_06_speech_asr_2/Practice/asr_sem_2.ipynb)

На семинаре мы разберём практическое применение методов адаптации к системе распознавания речи. Работа будет построена вокруг аудио датасета, в транскрипциях которого много медицинских терминов. Вы научитесь использовать библиотеку pyctcdecode для лучевого поиска лучшей гипотезы. Также поработаем с Oracle-WER и горячими словами (hotwords). Детально посмотрим на то как использовать pyctcdecode с shallow fusion и дополнительной лингвистической моделью, с помощью библиотеки kenlm обучим внутри-доменную лингвистическую модель для медицинских текстов и применим её для улучшения качества распознавания на датасете.


### Домашнее задание

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/DeepLearningSchool/Speech/blob/main/week_06_speech_asr_2/Homework/asr_hw.ipynb)

В домашнем задании вам предстоит реализовать архитектуру Conformer по статье, написать свой класс CTC-loss'а на torch и обучить ваш Conformer с вашим лоссов на датасете LibriSpeech. Во второй части домашнего задания вам нужно будет адаптировать вашу модель к аудио из медицинского домена, реализовать shallow fusion подход с N-Gram и с RNN-LM моделями. Результатом вашей работы станет пайплайн с обученной вами моделью, которая сохранит высокое качество распознавания на LibriSpeech и достигнет достаточного качества на данных медицинского домена.