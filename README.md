[![Build status](https://ci.appveyor.com/api/projects/status/xjclbmwo4k46ty2q?svg=true)](https://ci.appveyor.com/project/LiquidAssContainer/ra-observable)

# Redux Observable

[GitHub Pages](https://liquidasscontainer.github.io/ra_observable).

За основу взята предыдущая домашняя работа, сделанная на Redux Toolkit. Поскольку чистый Redux мне не очень нравится, я решил переписать часть кода [прошлого проекта](https://github.com/LiquidAssContainer/ra_thunk-2) (написанного на Toolkit), но пришлось «подружить» Tookit и Observable. Наверное, не самая рациональная идея (всё же проще использовать встроенный в Toolkit `createAsyncThunk`), но задачей было использовать Redux Observable.

Загрузка списка услуг, поиск и подгрузка описания у конкретной услуги сделаны с использованием epic’ов. Остальные функции, которые не требовались в этом задании, могут быть убраны или не работать. Могут быть невостребованные куски кода на тулкитовских thunk’ах и т. п.

Со стороны сервера была добавлена вероятность возниковения ошибки при запросе (если есть query-параметр `fortune`), присутствует кнопка повторения запроса.

Спиннер взят [отсюда](https://codepen.io/supah/pen/BjYLdW).
