# twine
1. добавление раздела [[какой то текст]]
2. добавление картинки персонажа  <img src="https://github.com/metyloran/twine/blob/main/kandinsky-download-1761044430673%20(1).png?raw=true" width="256" height="256"/>
```
 <img src="https://github.com/metyloran/twine/blob/main/kandinsky-download-1761044430673%20(1).png?raw=true" width="256" height="256"/>
```
3. добавление фона
```
   tw-story {
  background-image: url('https://github.com/metyloran/twine/blob/main/vintage-steampunk-frame-with-gears-clockwork-elements-parchment-background-concept-decorative-steampunk-frame-with-intricate-gears-antique-design_1102000-30032.jpg?raw=true');
   background-size: cover
}
```
4. добавление подложки под текст
```
    .passage {
  position: relative;
}
.text-box{
  background-color: rgba(0, 0, 0, 0.7);
  color: white;
  padding: 10px;
  margin-top: 10px;
  border-radius: 10px;
  position: fixed;
  bottom: 20px;
  left: 50%;
  transform: translateX(-50%);
   width: 100%;
  max-width: 880px;
  z-index: 100;
}
   ```


