# Lab-5-2
# Сабуров Сергей Фт-200008
# Прикладное программирование
# Добавлена проверка на ошибку ввода
## Среда Разработки
## С++ Visual Studio 2015

## Лабораторная №2
Запускается в с++
## Код
``` 
using namespace std;
#include <iostream>
//функции F1,F2,F3,F4 отвечают за значения больше 1000 (это всё из-за заглавных буков.)
//функция F1 проверяет количество тысяч
//функции F2/22 проверяет сотни
//функции F3/23/223 проверяет значения больше двадцати
//функции F4/24/224/2224 проверяет значения меньше двадцати
//функции F22,F23,F24 отвечают за значения больше 100
//функции F223,F224 отвечают за значения больше 20
//функция F2224 отвечает за значения меньше 20
void F1(int s)
{
	switch (s)
	{
	case 1:
		cout << "Одна тысяча ";
		break;
	case 2:
		cout << "Две тысячи ";
		break;
	case 3:
		cout << "Три тысячи ";
		break;
	case 4:
		cout << "Четыре тысячи ";
		break;
	case 5:
		cout << "Пять тысяч ";
		break;
	case 6:
		cout << "Шесть тысяч ";
		break;
	case 7:
		cout << "Семь тысяч ";
		break;
	case 8:
		cout << "Восемь тысяч ";
		break;
	case 9:
		cout << "Девять тысяч ";
		break;
	}
}

void F2(int s)
{
	switch (s)
	{
	case 1:
		cout << "сто ";
		break;
	case 2:
		cout << "двести ";
		break;
	case 3:
		cout << "триста ";
		break;
	case 4:
		cout << "четыреста ";
		break;
	case 5:
		cout << "пятьсот ";
		break;
	case 6:
		cout << "шестьсот ";
		break;
	case 7:
		cout << "семьсот ";
		break;
	case 8:
		cout << "восемьсот ";
		break;
	case 9:
		cout << "девятьсот ";
		break;
	}
}

void F3(int s)
{
	switch (s)
	{
	case 2:
		cout << "двадцать ";
		break;
	case 3:
		cout << "тридцать ";
		break;
	case 4:
		cout << "сорок ";
		break;
	case 5:
		cout << "пятьдесят ";
		break;
	case 6:
		cout << "шестьдесят ";
		break;
	case 7:
		cout << "семьдесят ";
		break;
	case 8:
		cout << "восемьдесят ";
		break;
	case 9:
		cout << "девяносто ";
		break;
	}
}
void F4(int s)
{
	switch (s)
	{
	case 0:
		cout << "рублей" << endl;
		break;
	case 1:
		cout << "один рубль" << endl;
		break;
	case 2:
		cout << "два рубля" << endl;
		break;
	case 3:
		cout << "три рубля" << endl;
		break;
	case 4:
		cout << "четыре рубля" << endl;
		break;
	case 5:
		cout << "пять рублей" << endl;
		break;
	case 6:
		cout << "шесть рублей" << endl;
		break;
	case 7:
		cout << "семь рублей" << endl;
		break;
	case 8:
		cout << "восемь рублей" << endl;
		break;
	case 9:
		cout << "девять рублей" << endl;
		break;
	case 10:
		cout << "десять рублей" << endl;
		break;
	case 11:
		cout << "одиннадцать рублей" << endl;
		break;
	case 12:
		cout << "двенадцать рублей" << endl;
		break;
	case 13:
		cout << "тринадцать рублей" << endl;
		break;
	case 14:
		cout << "четырнадцать рублей" << endl;
		break;
	case 15:
		cout << "пятнадцать рублей" << endl;
		break;
	case 16:
		cout << "шестнадцать рублей" << endl;
		break;
	case 17:
		cout << "семнадцать рублей" << endl;
		break;
	case 18:
		cout << "восемнадцать рублей" << endl;
		break;
	case 19:
		cout << "девятнадцать рублей" << endl;
		break;
	case 20:
		cout << "двадцать рублей" << endl;
		break;
	}
}
void F22(int s)
{
	switch (s)
	{
	case 1:
		cout << "Сто ";
		break;
	case 2:
		cout << "Двести ";
		break;
	case 3:
		cout << "Триста ";
		break;
	case 4:
		cout << "Четыреста ";
		break;
	case 5:
		cout << "Пятьсот ";
		break;
	case 6:
		cout << "Шестьсот ";
		break;
	case 7:
		cout << "Семьсот ";
		break;
	case 8:
		cout << "Восемьсот ";
		break;
	case 9:
		cout << "Девятьсот ";
		break;
	}
}

void F23(int s)
{
	switch (s)
	{
	case 2:
		cout << "двадцать ";
		break;
	case 3:
		cout << "тридцать ";
		break;
	case 4:
		cout << "сорок ";
		break;
	case 5:
		cout << "пятьдесят ";
		break;
	case 6:
		cout << "шестьдесят ";
		break;
	case 7:
		cout << "семьдесят ";
		break;
	case 8:
		cout << "восемьдесят ";
		break;
	case 9:
		cout << "девяносто ";
		break;
	}
}
void F24(int s)
{
	switch (s)
	{
	case 0:
		cout << "рублей" << endl;
		break;
	case 1:
		cout << "один рубль" << endl;
		break;
	case 2:
		cout << "два рубля" << endl;
		break;
	case 3:
		cout << "три рубля" << endl;
		break;
	case 4:
		cout << "четыре рубля" << endl;
		break;
	case 5:
		cout << "пять рублей" << endl;
		break;
	case 6:
		cout << "шесть рублей" << endl;
		break;
	case 7:
		cout << "семь рублей" << endl;
		break;
	case 8:
		cout << "восемь рублей" << endl;
		break;
	case 9:
		cout << "девять рублей" << endl;
		break;
	case 10:
		cout << "десять рублей" << endl;
		break;
	case 11:
		cout << "одиннадцать рублей" << endl;
		break;
	case 12:
		cout << "двенадцать рублей" << endl;
		break;
	case 13:
		cout << "тринадцать рублей" << endl;
		break;
	case 14:
		cout << "четырнадцать рублей" << endl;
		break;
	case 15:
		cout << "пятнадцать рублей" << endl;
		break;
	case 16:
		cout << "шестнадцать рублей" << endl;
		break;
	case 17:
		cout << "семнадцать рублей" << endl;
		break;
	case 18:
		cout << "восемнадцать рублей" << endl;
		break;
	case 19:
		cout << "девятнадцать рублей" << endl;
		break;
	case 20:
		cout << "двадцать рублей" << endl;
		break;
	}
}
void F223(int s)
{
	switch (s)
	{
	case 2:
		cout << "Двадцать ";
		break;
	case 3:
		cout << "Тридцать ";
		break;
	case 4:
		cout << "Сорок ";
		break;
	case 5:
		cout << "Пятьдесят ";
		break;
	case 6:
		cout << "Шестьдесят ";
		break;
	case 7:
		cout << "Семьдесят ";
		break;
	case 8:
		cout << "Восемьдесят ";
		break;
	case 9:
		cout << "Девяносто ";
		break;
	}
}
void F224(int s)
{
	switch (s)
	{
	case 0:
		cout << "рублей" << endl;
		break;
	case 1:
		cout << "один рубль" << endl;
		break;
	case 2:
		cout << "два рубля" << endl;
		break;
	case 3:
		cout << "три рубля" << endl;
		break;
	case 4:
		cout << "четыре рубля" << endl;
		break;
	case 5:
		cout << "пять рублей" << endl;
		break;
	case 6:
		cout << "шесть рублей" << endl;
		break;
	case 7:
		cout << "семь рублей" << endl;
		break;
	case 8:
		cout << "восемь рублей" << endl;
		break;
	case 9:
		cout << "девять рублей" << endl;
		break;
	case 10:
		cout << "десять рублей" << endl;
		break;
	case 11:
		cout << "одиннадцать рублей" << endl;
		break;
	case 12:
		cout << "двенадцать рублей" << endl;
		break;
	case 13:
		cout << "тринадцать рублей" << endl;
		break;
	case 14:
		cout << "четырнадцать рублей" << endl;
		break;
	case 15:
		cout << "пятнадцать рублей" << endl;
		break;
	case 16:
		cout << "шестнадцать рублей" << endl;
		break;
	case 17:
		cout << "семнадцать рублей" << endl;
		break;
	case 18:
		cout << "восемнадцать рублей" << endl;
		break;
	case 19:
		cout << "девятнадцать рублей" << endl;
		break;
	case 20:
		cout << "двадцать рублей" << endl;
		break;
	}
}
void F2224(int s)
{
	switch (s)
	{
	case 0:
		cout << "рублей" << endl;
		break;
	case 1:
		cout << "Один рубль" << endl;
		break;
	case 2:
		cout << "Два рубля" << endl;
		break;
	case 3:
		cout << "Три рубля" << endl;
		break;
	case 4:
		cout << "Четыре рубля" << endl;
		break;
	case 5:
		cout << "Пять рублей" << endl;
		break;
	case 6:
		cout << "Шесть рублей" << endl;
		break;
	case 7:
		cout << "Семь рублей" << endl;
		break;
	case 8:
		cout << "Восемь рублей" << endl;
		break;
	case 9:
		cout << "Девять рублей" << endl;
		break;
	case 10:
		cout << "Десять рублей" << endl;
		break;
	case 11:
		cout << "Одиннадцать рублей" << endl;
		break;
	case 12:
		cout << "Двенадцать рублей" << endl;
		break;
	case 13:
		cout << "Тринадцать рублей" << endl;
		break;
	case 14:
		cout << "Четырнадцать рублей" << endl;
		break;
	case 15:
		cout << "Пятнадцать рублей" << endl;
		break;
	case 16:
		cout << "Шестнадцать рублей" << endl;
		break;
	case 17:
		cout << "Семнадцать рублей" << endl;
		break;
	case 18:
		cout << "Восемнадцать рублей" << endl;
		break;
	case 19:
		cout << "Девятнадцать рублей" << endl;
		break;
	case 20:
		cout << "Двадцать рублей" << endl;
		break;
	}
}

int main()
{
	int s;
	int m;
	int g;
	int d;
	setlocale(LC_ALL, "RUS");
	cout << "Выдать сумму от 1 до 9999 " << endl;
	cin >> s;
	if ((s < 1) | (s > 9999))
	{
		cout << "Ошибка ввода s";
		return(0);
	}
	if (s >= 1000)
	{
		m = s / 1000; //делим на тысячу находим соостветствующее слово с большой буквы
		F1(m);//вызываем функцию тысяч
		s = s - m * 1000;//меняем значение так как тысяча уже была использована, так переходим к сотням
		g = s / 100;//проверяем количество сотен
		F2(g);//находим соответствующие слова для сотен
		s = s - g * 100;//убираем сотни
		d = s / 10;//проверяем десятки
		F3(d);
		s = s - d * 10;//проверяем оставшуюся часть
		F4(s);
	}
	else if (s >= 100)//аналогично для сотен
	{
		g = s / 100;
		F22(g);
		s = s - g * 100;
		d = s / 10;
		F23(d);
		s = s - d * 10;
		F24(s);
	}
	else if (s >= 20)
	{
		d = s / 10;
		F223(d);
		s = s - d * 10;
		F224(s);
	}
	else if (s < 20)
	{
		F2224(s);
	}

	system("pause");
	return 0;
}
```
