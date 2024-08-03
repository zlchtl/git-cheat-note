---
# *Шпаргалка по git*

Собрал все свои заметки с курса "[Основы работы с Git](https://practicum.yandex.ru/trainer/git-basics/lesson/2b82fb35-f581-4cd4-8806-c2a780e53347/)" [Яндекс практикума](https://practicum.yandex.ru/) в одном месте
---

## Содержание:  
1. **Знакомство с командной строкой**  
  [1.Навигация в командной строке.md](https://github.com/BadRedCrab/git-cheat-note/blob/master/1.%20%D0%9D%D0%B0%D0%B2%D0%B8%D0%B3%D0%B0%D1%86%D0%B8%D1%8F%20%D0%B2%20%D0%BA%D0%BE%D0%BC%D0%B0%D0%BD%D0%B4%D0%BD%D0%BE%D0%B9%20%D1%81%D1%82%D1%80%D0%BE%D0%BA%D0%B5.md)  
2. **Начало работы с Git**  
  [2.Создание локальной репозитории.md](https://github.com/BadRedCrab/git-cheat-note/blob/master/2.%20%D0%A1%D0%BE%D0%B7%D0%B4%D0%B0%D0%BD%D0%B8%D0%B5%20%D0%BB%D0%BE%D0%BA%D0%B0%D0%BB%D1%8C%D0%BD%D0%BE%D0%B9%20%D1%80%D0%B5%D0%BF%D0%BE%D0%B7%D0%B8%D1%82%D0%BE%D1%80%D0%B8%D0%B8.md)  
  [3.Работа с локальной репозиторией.md](https://github.com/BadRedCrab/git-cheat-note/blob/master/3.%20%D0%A0%D0%B0%D0%B1%D0%BE%D1%82%D0%B0%20%D1%81%20%D0%BB%D0%BE%D0%BA%D0%B0%D0%BB%D1%8C%D0%BD%D0%BE%D0%B9%20%D1%80%D0%B5%D0%BF%D0%BE%D0%B7%D0%B8%D1%82%D0%BE%D1%80%D0%B8%D0%B5%D0%B9.md)  
  [4.Связывание локального и удаленного репозитория.md](https://github.com/BadRedCrab/git-cheat-note/blob/master/4.%20%D0%A1%D0%B2%D1%8F%D0%B7%D1%8B%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5%20%D0%BB%D0%BE%D0%BA%D0%B0%D0%BB%D1%8C%D0%BD%D0%BE%D0%B3%D0%BE%20%D0%B8%20%D1%83%D0%B4%D0%B0%D0%BB%D0%B5%D0%BD%D0%BD%D0%BE%D0%B3%D0%BE%20%D1%80%D0%B5%D0%BF%D0%BE%D0%B7%D0%B8%D1%82%D0%BE%D1%80%D0%B8%D1%8F.md)  
  [5.Отправление изменений на удаленный репозиторий.md](https://github.com/BadRedCrab/git-cheat-note/blob/master/5.%20%D0%9E%D1%82%D0%BF%D1%80%D0%B0%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5%20%D0%B8%D0%B7%D0%BC%D0%B5%D0%BD%D0%B5%D0%BD%D0%B8%D0%B9%20%D0%BD%D0%B0%20%D1%83%D0%B4%D0%B0%D0%BB%D0%B5%D0%BD%D0%BD%D1%8B%D0%B9%20%D1%80%D0%B5%D0%BF%D0%BE%D0%B7%D0%B8%D1%82%D0%BE%D1%80%D0%B8%D0%B9.md)  
  [6.Создание README.md](https://github.com/BadRedCrab/git-cheat-note/blob/master/6.%20%D0%A1%D0%BE%D0%B7%D0%B4%D0%B0%D0%BD%D0%B8%D0%B5%20README.md)  
  [7.Файл HEAD.md](https://github.com/BadRedCrab/git-cheat-note/blob/master/7.%20%D0%A4%D0%B0%D0%B9%D0%BB%20HEAD.md)  
  [8.Статусы файлов.md](https://github.com/BadRedCrab/git-cheat-note/blob/master/8.%20%D0%A1%D1%82%D0%B0%D1%82%D1%83%D1%81%D1%8B%20%D1%84%D0%B0%D0%B9%D0%BB%D0%BE%D0%B2.md)  
  [9.Оформление коммитов.md](https://github.com/BadRedCrab/git-cheat-note/blob/master/9.%20%D0%9E%D1%84%D0%BE%D1%80%D0%BC%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5%20%D0%BA%D0%BE%D0%BC%D0%BC%D0%B8%D1%82%D0%BE%D0%B2.md)  
  [10.Исправление коммита.md](https://github.com/BadRedCrab/git-cheat-note/blob/master/10.%20%D0%98%D1%81%D0%BF%D1%80%D0%B0%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5%20%D0%BA%D0%BE%D0%BC%D0%BC%D0%B8%D1%82%D0%B0.md)  
  [11.Откат к предыдущему коммиту.md](https://github.com/BadRedCrab/git-cheat-note/blob/master/11.%D0%9E%D1%82%D0%BA%D0%B0%D1%82%20%D0%BA%20%D0%BF%D1%80%D0%B5%D0%B4%D1%8B%D0%B4%D1%83%D1%89%D0%B5%D0%BC%D1%83%20%D0%BA%D0%BE%D0%BC%D0%BC%D0%B8%D1%82%D1%83.md)  
  [12.Просматриваем изменения в файлах.md](https://github.com/BadRedCrab/git-cheat-note/blob/master/12.%D0%9F%D1%80%D0%BE%D1%81%D0%BC%D0%B0%D1%82%D1%80%D0%B8%D0%B2%D0%B0%D0%B5%D0%BC%20%D0%B8%D0%B7%D0%BC%D0%B5%D0%BD%D0%B5%D0%BD%D0%B8%D1%8F%20%D0%B2%20%D1%84%D0%B0%D0%B9%D0%BB%D0%B0%D1%85.md)  
  [13.Сопоставляем коммиты.md](https://github.com/BadRedCrab/git-cheat-note/blob/master/13.%D0%A1%D0%BE%D0%BF%D0%BE%D1%81%D1%82%D0%B0%D0%B2%D0%BB%D1%8F%D0%B5%D0%BC%20%D0%BA%D0%BE%D0%BC%D0%BC%D0%B8%D1%82%D1%8B.md)  
  [14.Игнорирование файлов в Git.md](https://github.com/BadRedCrab/git-cheat-note/blob/master/14.%D0%98%D0%B3%D0%BD%D0%BE%D1%80%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5%20%D1%84%D0%B0%D0%B9%D0%BB%D0%BE%D0%B2%20%D0%B2%20Git.md)  
  [15.Шпаргалка. Начало работы с Git.md](https://github.com/BadRedCrab/git-cheat-note/blob/master/15.%D0%A8%D0%BF%D0%B0%D1%80%D0%B3%D0%B0%D0%BB%D0%BA%D0%B0.%20%D0%9D%D0%B0%D1%87%D0%B0%D0%BB%D0%BE%20%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D1%8B%20%D1%81%20Git.md)  
3. **Работа с ветками**  
  [16.Клонируем репозиторий.md](https://github.com/BadRedCrab/git-cheat-note/blob/master/16.%D0%9A%D0%BB%D0%BE%D0%BD%D0%B8%D1%80%D1%83%D0%B5%D0%BC%20%D1%80%D0%B5%D0%BF%D0%BE%D0%B7%D0%B8%D1%82%D0%BE%D1%80%D0%B8%D0%B9.md)  
  [17.Выполняем Fork.md](https://github.com/BadRedCrab/git-cheat-note/blob/master/17.%D0%92%D1%8B%D0%BF%D0%BE%D0%BB%D0%BD%D1%8F%D0%B5%D0%BC%20Fork.md)  
  [18.Ветка, создание, переключение между ними.md](https://github.com/BadRedCrab/git-cheat-note/blob/master/18.%D0%92%D0%B5%D1%82%D0%BA%D0%B0%2C%20%D1%81%D0%BE%D0%B7%D0%B4%D0%B0%D0%BD%D0%B8%D0%B5%2C%20%D0%BF%D0%B5%D1%80%D0%B5%D0%BA%D0%BB%D1%8E%D1%87%D0%B5%D0%BD%D0%B8%D0%B5%20%D0%BC%D0%B5%D0%B6%D0%B4%D1%83%20%D0%BD%D0%B8%D0%BC%D0%B8.md)  
  [19.Сравнение веток.md](https://github.com/BadRedCrab/git-cheat-note/blob/master/19.%D0%A1%D1%80%D0%B0%D0%B2%D0%BD%D0%B5%D0%BD%D0%B8%D0%B5%20%D0%B2%D0%B5%D1%82%D0%BE%D0%BA.md)  
  [20.Слияние и удаление веток.md](https://github.com/BadRedCrab/git-cheat-note/blob/master/20.%D0%A1%D0%BB%D0%B8%D1%8F%D0%BD%D0%B8%D0%B5%20%D0%B8%20%D1%83%D0%B4%D0%B0%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5%20%D0%B2%D0%B5%D1%82%D0%BE%D0%BA.md)  
  [21.Пушим ветки на GitHub.md](https://github.com/BadRedCrab/git-cheat-note/blob/master/21.%D0%9F%D1%83%D1%88%D0%B8%D0%BC%20%D0%B2%D0%B5%D1%82%D0%BA%D0%B8%20%D0%BD%D0%B0%20GitHub.md)  
  [22.Создание pull request.md](https://github.com/BadRedCrab/git-cheat-note/blob/master/22.%D0%A1%D0%BE%D0%B7%D0%B4%D0%B0%D0%BD%D0%B8%D0%B5%20pull%20request.md)  
  [23.Забираем изменения из удалённого репозитория.md](https://github.com/BadRedCrab/git-cheat-note/blob/master/23.%D0%97%D0%B0%D0%B1%D0%B8%D1%80%D0%B0%D0%B5%D0%BC%20%D0%B8%D0%B7%D0%BC%D0%B5%D0%BD%D0%B5%D0%BD%D0%B8%D1%8F%20%D0%B8%D0%B7%20%D1%83%D0%B4%D0%B0%D0%BB%D1%91%D0%BD%D0%BD%D0%BE%D0%B3%D0%BE%20%D1%80%D0%B5%D0%BF%D0%BE%D0%B7%D0%B8%D1%82%D0%BE%D1%80%D0%B8%D1%8F.md)  
  [24.Шпаргалка. Работа с ветками.md](https://github.com/BadRedCrab/git-cheat-note/blob/master/24.%D0%A8%D0%BF%D0%B0%D1%80%D0%B3%D0%B0%D0%BB%D0%BA%D0%B0.%20%D0%A0%D0%B0%D0%B1%D0%BE%D1%82%D0%B0%20%D1%81%20%D0%B2%D0%B5%D1%82%D0%BA%D0%B0%D0%BC%D0%B8.md)  
4. **Продвинутая командная работа с Git**  
  [25.Что такое fast-forward.md](https://github.com/BadRedCrab/git-cheat-note/blob/master/25.%D0%A7%D1%82%D0%BE%20%D1%82%D0%B0%D0%BA%D0%BE%D0%B5%20fast-forward.md)  
  [26.Non-fast-forward.md](https://github.com/BadRedCrab/git-cheat-note/blob/master/26.Non-fast-forward.md)  
  [27.git push и fast-forward.md](https://github.com/BadRedCrab/git-cheat-note/blob/master/27.git%20push%20%D0%B8%20fast-forward.md)  
  [28.Модели веток. Простая feature branch модель.md](https://github.com/BadRedCrab/git-cheat-note/blob/master/28.%D0%9C%D0%BE%D0%B4%D0%B5%D0%BB%D0%B8%20%D0%B2%D0%B5%D1%82%D0%BE%D0%BA.%20%D0%9F%D1%80%D0%BE%D1%81%D1%82%D0%B0%D1%8F%20feature%20branch%20%D0%BC%D0%BE%D0%B4%D0%B5%D0%BB%D1%8C.md)  
  [29.Pull request и code review.md](https://github.com/BadRedCrab/git-cheat-note/blob/master/29.Pull%20request%20%D0%B8%20code%20review.md)  
  [30.Работа с PR.md](https://github.com/BadRedCrab/git-cheat-note/blob/master/30.%D0%A0%D0%B0%D0%B1%D0%BE%D1%82%D0%B0%20%D1%81%20PR.md)  
  [31.Разрешение конфликта.md](https://github.com/BadRedCrab/git-cheat-note/blob/master/31.%D0%A0%D0%B0%D0%B7%D1%80%D0%B5%D1%88%D0%B5%D0%BD%D0%B8%D0%B5%20%D0%BA%D0%BE%D0%BD%D1%84%D0%BB%D0%B8%D0%BA%D1%82%D0%B0.md)  
  [32.Основная ветка «убежала» вперёд.md](https://github.com/BadRedCrab/git-cheat-note/blob/master/32.%D0%9E%D1%81%D0%BD%D0%BE%D0%B2%D0%BD%D0%B0%D1%8F%20%D0%B2%D0%B5%D1%82%D0%BA%D0%B0%20%C2%AB%D1%83%D0%B1%D0%B5%D0%B6%D0%B0%D0%BB%D0%B0%C2%BB%20%D0%B2%D0%BF%D0%B5%D1%80%D1%91%D0%B4.md)  
  [33.Шпаргалка. Командная работа в Git.md](https://github.com/BadRedCrab/git-cheat-note/blob/master/33.%D0%A8%D0%BF%D0%B0%D1%80%D0%B3%D0%B0%D0%BB%D0%BA%D0%B0.%20%D0%9A%D0%BE%D0%BC%D0%B0%D0%BD%D0%B4%D0%BD%D0%B0%D1%8F%20%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%B0%20%D0%B2%20Git.md)  