# Трансформации и переходы 
## CSS Transforms
Transform - свойство CSS, позволяющее визуально трансформировать элемент (перемещать, вращать, масштабировать) без изменения документального потока. 

Основные функции трансформации:
transform: translateX(50px); /* по горизонтали */
transform: translateY(30px); /* по вертикали */
transform: translate(50px, 30px);  /* по обеим осям */
transform: scale(1.5); /* увеличение элемента в 1.5 раза */ 
transform: scaleX(2); /* только по ширине */
transform: scale(1.2, 0.8); /* разные значения для осей */ 
transform: rotate(45deg); /* поворот на 45 градусов */;
transform: rotate(0.25turn); /* поворот на четверть */
transform: skew(15deg);  /* наклон по обеим осям */;
transform: skewX(20deg);  /* наклон по горизонтали */
transform: translateY(-2px) scale(1.05); /* комбинация двух свойств */

## CSS Transition 
Transition - свойство CSS, которое позволяет плавно изменять значения свойств в течение определенного времени. 

Синтаксис:
transition: свойство | длительность анимации | функция скорости (ease, linear, ease-in-out) | delay (задержка перед началом анимации)

.element {
    transition: all 0.3s ease; /* все свойства за 0.3 сек */
    transition: opacity 0.5s linear; /* только одно свойство */

    transition: transform 0.4s ease-out 0.1s; /* с задержкой */
}