<table style="width: 100%;">
  <tr>
    <td style="text-align: center; border: none;">
    Министерство образования и науки РФ<br>
Государственное бюджетное профессиональное образовательное учреждение Республики Марий Эл<br>
Йошкар-Олинский технологический колледж
</td>
  </tr>
  <tr>
    <td style="text-align: center; border: none; height: 15em;">
    <h2 style="font-size:3em;">Отчет</h2>
      <h3>по лабораторной работе<br><br> по дисциплине "Основы алгоритмизации и программирования"<br><br> Тема:<b> "Исключения. Null."<b> </h3></td>
  </tr>
  <tr>
    <br><br><td style="text-align: right; border: none; height: 20em;">
      Разработал:<br/>
      Григорьв Ярослав<br>
      Группа: И-21<br>
      Преподаватель:<br>
      Колесников Евгений Иванович
    </td>
  </tr>
  <tr>
    <td style="text-align: center; border: none; height: 5em;">
    г.Йошкар-Ола, 2021</td>
  </tr>
</table>

<div style="page-break-after: always;"></div>

# Цели и задачи:
1: Исследовать исключения и операции с нуллабельными типами данных.

2: Результат (исследуемый код и логи) оформить в отдельную ветку в репозитории и отчет о лабораторной работе

# Краткий материал.

```
try
{
     
}
catch
{
     
}
finally
{
     
}
```
При использовании блока ``` try...catch..finally ``` вначале выполняются все инструкции в блоке ```try```. Если в этом блоке не возникло исключений, то после его выполнения начинает выполняться блок ```finally```. И затем конструкция ```try..catch..finally``` завершает свою работу.

Если же в блоке ```try``` вдруг возникает исключение, то обычный порядок выполнения останавливается, и среда **CLR** начинает искать блок ```catch```, который может обработать данное исключение. Если нужный блок ```catch``` найден, то он выполняется, и после его завершения выполняется блок ```finally```.

Если нужный блок ```catch``` не найден, то при возникновении исключения программа аварийно завершает свое выполнение.

# Вывод

Используя примеры из лекции я исследоваk исключения и операции с нуллабельными типами данных. Результат (исследуемый код и логи) оформил в отдельную ветку в репозитории и отчет о лабораторной работе.