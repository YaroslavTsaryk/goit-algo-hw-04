# goit-algo-hw-04

Сотрування вставкою ділить масив на сортовану частину на початку і несортовану далі. Кожне значення з несортованого списку порівнюється з максимальним у сортованій частині і після цього проводиться пошук 
правильної позиції для нового елемента. Найгірший випадок складатиме O(n**2) для зворотньо відсортованого масиву.
Алгоритм злиттям використовую розбиття масиву на 2 рівні частини і сортує кожну частину окремо.
Це дає кількість операцій рівня О(n*log n)
Алгоритм TimSort знаходить частково впорядковані набори значень і намагається їх об"єднувати.
Теоретична складність О(n*log n) для поганих випадків і O(n-1) для найкращих.


Виконано 10 запусків для випадково згенерованих масивів даних, 
які складаються з 2000 елементів до 100000. 
Алгоритм вставкою показав найгірший час 0,1+ с
Алгоритм злиттям виконувався 0,4-0,5 с
Метод sorted має значення часу виконання 1,7е-5 до 3,85е-5
Метод sort показав найкращі результати близько 1е-5 до 2,78е-5
При виконанні на однакових наборах вхідних даних метод sort 
приблизно вдвічі швидший за sorted


Execution time 'merge': 0.005084000000351807 seconds
Execution time 'insertion_sort': 0.10314590000052704 seconds
Execution time 'sorted': 2.2000000171829015e-05 seconds
Execution time 'sort': 9.60000033956021e-06 seconds    

Execution time 'merge': 0.00435020000077202 seconds
Execution time 'insertion_sort': 0.10868080000000191 seconds
Execution time 'sorted': 1.7500000467407517e-05 seconds
Execution time 'sort': 1.0199999451288022e-05 seconds

Execution time 'merge': 0.004155200000241166 seconds
Execution time 'insertion_sort': 0.10821949999990466 seconds
Execution time 'sorted': 1.7600001228856854e-05 seconds
Execution time 'sort': 1.0800000382005237e-05 seconds

Execution time 'merge': 0.00479309999900579 seconds
Execution time 'insertion_sort': 0.10345439999946393 seconds
Execution time 'sorted': 1.6900001355679706e-05 seconds
Execution time 'sort': 1.06999996205559e-05 seconds

Execution time 'merge': 0.004776499999934458 seconds
Execution time 'insertion_sort': 0.11054150000018126 seconds
Execution time 'sorted': 3.549999928509351e-05 seconds
Execution time 'sort': 1.5600000551785342e-05 seconds

Execution time 'merge': 0.004158200001256773 seconds
Execution time 'insertion_sort': 0.1022121000005427 seconds
Execution time 'sorted': 3.8500000300700776e-05 seconds
Execution time 'sort': 2.7800000680144876e-05 seconds

Execution time 'merge': 0.004719100001238985 seconds
Execution time 'insertion_sort': 0.12333980000039446 seconds
Execution time 'sorted': 1.8900000213761814e-05 seconds
Execution time 'sort': 9.800000043469481e-06 seconds

Execution time 'merge': 0.004164800000580726 seconds
Execution time 'insertion_sort': 0.10204930000145396 seconds
Execution time 'sorted': 1.8799999452312477e-05 seconds
Execution time 'sort': 1.1399999493733048e-05 seconds

Execution time 'merge': 0.004424500000823173 seconds
Execution time 'insertion_sort': 0.10231449999992037 seconds
Execution time 'sorted': 1.809999957913533e-05 seconds
Execution time 'sort': 1.049999991664663e-05 seconds

Execution time 'merge': 0.004171800001131487 seconds
Execution time 'insertion_sort': 0.11195240000051854 seconds
Execution time 'sorted': 3.49000001733657e-05 seconds
Execution time 'sort': 1.2700000297627412e-05 seconds