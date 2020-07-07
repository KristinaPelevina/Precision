# Отчёт о тестировании приложения "Precision"

## Краткое описание

C помощью IntelliJ IDEA было создано базовое приложение, где были указаны следующие входные данные:

``` public class Main {
  public static void main(String[] args) {
    double regularBonus = 0.3;
    double specialBonus = 0.6;
    double totalBonus = regularBonus + specialBonus;
    System.out.println(totalBonus);
  }
} 
```

## Описание тестов

Использовалось позитивное и функциональное тестирование. 

Мы складывали regularBonus с specialBonus.

При использовании исходных данных в результате получали очевидно неправильную сумму.

Вывод об ошибке был основан на опыте и здравом смысле.


## Результаты
100% - отрицательных тестов. 

## Баг-репорт
https://github.com/KristinaPelevina/MoneyTransfer/issues/1#issue-652369758

