# JS-Calculator
Напишите калькулятор для студии печати. Цены даны в таблице ниже.
Услуга
Цена за единицу
Печать черно-белая
20
Копия черно-белая
15
Печать цветная
50
Копия цветная
40
Фото 30х40
60
Фото 50х60
100

Цены лучше всего хранить в объекте.
Сам калькулятор разместите  в виде таблицы. Например
    <table border=1>
       <tr>
        <td>Услуга</td>
        <td>Цена за ед.</td>
        <td>Количество</td>
        <td>Итого</td>
       </tr>
       <tr>
        <td>Черно-белая печать (лист)</td>
        <td id="bwPrint"></td>
        <td><input type="number" min=0 value=0></td>
        <td id="sum0">0</td>
       </tr>
       <tr>
        <td>Черно-белая копия (лист)</td>
        <td id="bwCopy"></td>
        <td><input type="number" min=0  value=0></td>
        <td id="sum1">0</td>
       </tr>
       <tr>
        <td>Цветная печать (лист)</td>
        <td id="colorPrint"></td>
        <td><input type="number" min=0  value=0></td>
        <td id="sum2">0</td>
       </tr>
       <tr>
        <td>Цветная копия (лист)</td>
        <td id="colorCopy"></td>
        <td><input type="number" min=0  value=0></td>
        <td id="sum3">0</td>
       </tr>
       <tr>
        <td>Фото 30х40</td>
        <td id="photo3040"></td>
        <td><input type="number" min=0  value=0></td>
        <td id="sum4">0</td>
       </tr>
       <tr>
        <td>Фото 50х60</td>
        <td id="photo5060"></td>
        <td><input type="number" min=0  value=0></td>
        <td id="sum5">0</td>
       </tr>
      <tr>
        <td colspan="3">ИТОГО</td>
        <td id="itogo"></td>
       </tr>
    </table>

Когда пользователь увеличивает или уменьшает количество за единицу, автоматически должны меняться значения в ячейках столбца «Итого за услугу» и последняя ячейка с общей стоимостью заказа ИТОГО. 
