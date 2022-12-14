/* Реализуйте игру в жизнь на прямоугольном конечном поле.
     
     На каждом ходе клетка меняет свое состояние по таким правилам:
     1. Если у нее менее 2 живых соседей или более трех живых — она становится мертвой (false).
     2. Если ровно 3 живых соседа, то клетка становится живой (true)
     3. Если ровно 2 живых соседа, то клетка сохраняет своё состояние.

     У каждой неграничной клетки есть 8 соседей (в том числе по диагонали)

    Работу над игрой постройте итеративно в стиле TDD:
        1. Сначала напишите какой-нибудь простейший тест в файле Tests.cs. Тест должен быть красным.
        То есть должен проверять ещё нереализованное требование.
        2. Только потом напшишите простейшую реализацию, которая делает тест зеленым. 
        Не старайтесь реализовать всю логику, просто сделайте тест зеленым как можно быстрее.
        3. Повторяйте процесс, пока ещё можете придумать новые красные тесты.

     На каждый шаг (тест и реализация) у вас должно уходить не более 5 минут.
     Если вы не успели поднять тест за 5 минут — удалите этот тест и придумайте тест попроще.
     Засекайте время таймером на телефоне.

     После каждого шага (тест или реализация) меняйте активного человека за клавиатурой.

     Начните с простейших тестов. 

     Проект настроен так, что при каждой сборке библиотека копируется в данные для GameOfLife.exe (Unity)
     Т.е. алгоритм такой: меняете код, собираете проект, запускаете GameOfLife.exe по пути Unity\Build

     Управление в игре - клик мыши (меняет состояние клетки), стрелки, пробел (пауза), колесико мыши, F1-F10 (скорость)
     После запуска игра на паузе
    */