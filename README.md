# Twinee
1. Добавление раздела [[привет как дела]]
2. Добавление катинки персонажа - <img src="https://github.com/kamila2030/Twinee/blob/main/kandinsky-download-1761045311484%20(1).png?raw=true">
```
<img src="https://github.com/kamila2030/Twinee/blob/main/kandinsky-download-1761045311484%20(1).png?raw=true">
```
3. Добавление фона
```
tw-story {
    background-image: url('https://github.com/Z1dipex/Twine/blob/main/image.png?raw=true');
    background-size: cover
}

```
4. Добавление подложки у текста
```
<div class="text-box">
Студентка совмещает учебу с работой, стремясь обрести опыт и финансовую независимость. 
</div>
```
```
.text-box {
    background-color: rgba(0, 0, 0, 0.7);
    color: white;
    padding: 10px;
    border-radius: 10px;
    margin-top: 10px;
    position: fixed;
    bottom: 20px;
    left: 50%;
    transform: translateX(-50%);
    width: 80%;
    max-width: 800px;
    z-index: 100;
}

