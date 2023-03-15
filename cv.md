# __[rsschool-cv](https://Tyiooo.github.io/rsschool-cv/)__

# __Egor Korotyuk__

## __Contacts__
- __Location:__ Minsk, Belarus
- __Phone:__ +375 33 351-406-10
- __Email:__ vailygione@gmail.com
- __GitHub:__ [korortuk-egor](https://github.com/Tyiooo)

## __About Me__
I communicate well with people, thanks to this there will always be a place for me in the team.\
I am very good at learning new information quickly. I am very good at using various search engines.

## __Skills__
- HTML
- CSS/SASS
- JavaScript (Basic)
- Git
- C++
- Python

## __Code Example__
```
void delCls(vector<Clothes*>& clothes) {
	int m = 0;
	cout << "\n\tВы хотите удалить :\n\t1 - Всю одежду, 2 - Один тип\n";
	m = CheckInt(2);
	if (m == 1)
	{
		clothes.clear();
		cout << "\n\tУдаление прошло успешно!\n";
	}
	if (m == 2)
	{
		ReadVector(clothes);
		int f;
		cout << "\n\tВведите пункт одежды для удаления :\n ";
		f = CheckInt(clothes.size());
		clothes.erase(clothes.begin() + f - 1);
		cout << "\n\tУдаление прошло успешно!\n";
		ReadVector(clothes);
	}
	return;
}
```

## __Experience__

## __Education__ 
- __University:__ Belarusian State University of Informatics and Radioelectronics, game design major
- __Courses:__
  - Stepik
  - Code Basics

## __English__
__B1__





