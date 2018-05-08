## Задача 1

Даден е следния абстрактен клас:

    class Shape
    {
    public:
        virtual void print() const = 0;
        virtual void getArea() const = 0;
    };

Да се реализират следните класове, наследяващи класът Shape:

- Circle, характеризиращ се с радиус;
- Rectangle, характеризиращ се с височина и ширина.

## Задача 2

Имате да създадете програма, която създава отчет за стоките в един магазин. Всяка една стока бива в три разновидности - акцизни и неакцизни.

Направете йерархия, в която Stock  е абстрактен клас в който имате методи за принтиране, за връщане на цена и връщане на тип(вида стока), връщане на стойност за фактура (за акцизни стойността се изчислява цена + цена * акциза% , за неакцизни връщате цената, а ако е здравословна - цената - 10%). За член данни имате наименование на стоката и единична цена.

Акцизни и неакцизни са имплементации на стоката. Като трябва да добавите в акцизни процент на акциза, още set-ъри и get-ъри и връщане и да имплементирате всички методи на Stock.

Неакцизни - добавяте дали е здравословен продукт, реализирайте всички методи.

В клас магазин имате списък/вектор/масив от стоки  (най - добре е от указатели от стоки), да имате метод зареждане, в който да заредите магазина със стоки. Да направите фактура, където трябва да съставите документ (разширете задачата като запазите във файл информацията) с име- крайна цена накрая -------- и задавате общо количество: крайна цена



Choco - 3.56
Vodka - 40
Kiwi - 99
=========
3 - 142.56