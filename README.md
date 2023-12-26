rrЗапуск проекта

0. Установка python 3.9 (arch linux): `yay -S python39`
1. Установить Rasa: `pip3 install rasa`
2. Добавить библиотеку: 
```
pip3 install 'rasa[spacy]'
python3 -m spacy download ru_core_news_sm
```
3. Обучить модель: `rasa train`
4. Запустить обученную модель в терминале: `rasa shell`
5. Запустить сервер: `rasa run actions`