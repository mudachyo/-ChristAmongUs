![Showcase Image](https://i.imgur.com/OZkyV5W.png)
## ChristWare: Among Us Edition
Это чит, который я разработал примерно за неделю для недавно популярной увлекательной игры Among Us.


Библиотеки и программное обеспечение, использованные для создания этого чита, включают magic_enum, Dear IMGUI, Il2CppInspector и Il2CppDumper. Я настоятельно рекомендую использовать генератор скаффолдинга C ++ Il2CppInspector, если вы хотите возиться с играми Il2Cpp; это сэкономило мне много времени на этом проекте.

## Особенности:
- Force a meeting (Заставить встречу)
- NoClip
- Mark imposters (Отметить самозванцев)
- Radar (любезно предоставлено [v0idp](https://github.com/v0idp))
- Reset disconnection ban time (Сбросить время запрета отключения)
- Spam chat, and force other players to spam (Спамить в чате и заставить других игроков спамить)
- Player list displaying imposters, crew members (Список игроков с отображением самозванцев, членов экипажа)
- Murder all players instantly as imposter (Убейте всех игроков мгновенно как самозванец)
- Instawin as imposter by the feature above (Победа как самозванец из-за функции выше)
- Kill all crew (Убить весь экипаж)
- Kill all imposters (Убить всех самозванцев)
- Kill any player (Убить любого игрока)
- Teleport to any player (Телепорт к любому игроку)
- Force a vote on any player (Принудительно проголосовать за любого игрока)
- Kick any player (Кик любого игрока)
- Instawin as crew by the two features above (Победа в качестве экипажа двумя функциями выше)
- Close any or all doors, and keep them closed (Закройте любую или все двери и держите их закрытыми.)
- Repair systems (Системы ремонта (могут быть глючные))
- Sabotage systems (Системы саботажа (может глючить))
- Change your color in game (Измени свой цвет в игре)
- Cycle through colors rapidly (Быстрое переключение цветов)
- Modifiers:
    - Light (Свет)
    - Speed (Скорость)
    - Kill Distance (Расстояние убийства)
    - Kill Cooldown (Перезарядка убийства)
- Make everybody rainbow colors (Сделать всех цветов радуги)
- Make everybody swap through clothes, hats (Заставьте всех поменяться одеждой, шляпами)

Ни одна из этих функций не предназначена только для клиентов. Изменения * должны * отражаться в глазах всех игроков. Убедитесь, что интервал для повторения действий не слишком мал, иначе он не появится.

## Применение
Скомпилируйте проект (x86, Release)

Внедрите ChristWareAU.dll в Among Us.exe с помощью вашего любимого инжектора (следует использовать LoadLibrary)

Убедитесь, что чит успешно инициализирован в консоли, которая появляется.

Нажмите Delete в игре, чтобы открыть меню.
