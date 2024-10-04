# Array Sorting
## Описание
    Простая функция, написанная на языке С++, выполняющая алгоритм сортировки вставкой.

Требование - С++11
```bash
git clone - https://github.com/podyan7/amogus.git

```markdown
## Использование:

Пример использования функции:
```C++

int a [] = {5,3,2,4,1,7,9,8};
# Вывод: [2, 3, 4, 5, 1, 7, 9, 8]

##Примеры кода
##Вставка
void Vstavka(a[], n)
{
    for (int i=0; i < N; i++)
    cout<< a [i]<< " ";
    cout<<"\n";
    for (int i=1; i< N/2; i++)
    {
        int tmp = a [i];
        int j;
        for (j=i - 1; j >=0 && a [j] > tmp; j--)
        a [j + 1] = a [j];
        a [j + 1] = tmp;
    }
    for (int i=0; i < N; i++)
    cout<< a[i]<< " ";
}

## Лицензия

Этот проект лицензирован под MIT License — подробнее в файле [LICENSE](LICENSE).
