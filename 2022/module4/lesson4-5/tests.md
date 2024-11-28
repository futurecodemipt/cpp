1. Какой класс в SFML представляет собой объект, который может быть отображен на экране и содержит текстуру?
```
a) sf::Texture
b) sf::Sprite
c) sf::Window
d) sf::RectangleShape

Ответ: b) sf::Sprite
```


2. Как установить позицию спрайта в SFML?
```
a) sprite.position(x, y);
b) sprite.setPosition(x, y);
c) sprite.setPos(x, y);
d) sprite.setXY(x, y);

Ответ: b) sprite.setPosition(x, y);
```

3. Как изменить масштаб спрайта в SFML?
```
a) sprite.scale(x, y);
b) sprite.setScale(x, y);
c) sprite.resize(x, y);
d) sprite.setZoom(x, y);


Ответ: b) sprite.setScale(x, y);
```
4. Как повернуть спрайт в SFML?
```
a) sprite.rotate(angle);
b) sprite.setAngle(angle);
c) sprite.turn(angle);
d) sprite.spin(angle);

Ответ: a) sprite.rotate(angle);
```

5. Как создать окно в SFML?
```
a) sf::Window window(sf::VideoMode(width), "Title");
b) sf::RenderWindow window(sf::VideoMode(width, height), "Title");
c) sf::Window window(width, height, "Title");
d) sf::RenderWindow window(width, height, "Title");

Ответ: b) sf::RenderWindow window(sf::VideoMode(width, height), "Title");
```

6. Как отобразить спрайт на экране в SFML?
```
a) window.draw(sprite);
b) sprite.draw(window);
c) sprite.display(window);
d) window.display(sprite);

Ответ: a) window.draw(sprite);
```

7. Как получить размеры окна в SFML?
```
a) window.getSize();
b) window.getWidth(), window.getHeight();
c) window.width(), window.height();
d) window.getDimensions();

Ответ: a) window.getSize();
```

8. Как закрыть окно в SFML?
```
a) window.close();
b) window.exit();
c) window.quit();
d) window.terminate();

Ответ: a) window.close();
```

9. Как проверить, была ли нажата клавиша на клавиатуре в SFML?
```
a) if (event.type == sf::Event::KeyPressed)
b) if (event.type == sf::Event::KeyReleased)
c) if (event.type == sf::Event::MouseButtonPressed)
d) if (event.type == sf::Event::MouseButtonReleased)

Ответ: a) if (event.type == sf::Event::KeyPressed)
```