# Гринько Михайло Миколайович (23.121 ПЗПІп.0104) - Лабораторна 1

## Завдання (варіант 4)
Почавши тренування, лижник у перший день пробіг 10 км. Кожний наступний день він збільшував пробіг на 10% від пробігу попереднього дня. Визначити:
- пробіг лижника за другий, третій, ..., десятий день тренувань;
- який сумарній путь він пробіг за перші 7 днів тренувань.

### Денна відстань
```csharp
double dayDistance(int numberOfDays, double firstDayDistance = 10) {
  if (numberOfDays < 1) {
    return 0;
  }

  double distance = firstDayDistance;

  for (int day = 2; day <= numberOfDays; day++) {
    distance *= 1.1;
  }
  
  Console.WriteLine($"{distance} during {numberOfDays} day");

  return distance;
}

dayDistance(0);
dayDistance(1);
dayDistance(2);
dayDistance(3);
dayDistance(7);
```
**Результат**:
```text
10 during 1 day
11 during 2 day
12,100000000000001 during 3 day
17,715610000000005 during 7 day
```

### Загальна відстань за декілька днів 
```csharp
double totalDistance(int numberOfDays, double firstDayDistance = 10) {
  if (numberOfDays < 1) {
    return 0;
  }

  double distance = firstDayDistance;
  double total = firstDayDistance;

  for (int day = 2; day <= numberOfDays; day++) {
    distance *= 1.1;
    total += distance;
  }
  
  Console.WriteLine($"{total} in total during {numberOfDays} days");

  return total;
}
```
**Результат**:
```text
10 in total during 1 days
21 in total during 2 days
94,87171000000001 in total during 7 days
```
