<h2 align="center">Hi there, I'm <a href="https://daniilshat.ru/" target="_blank">Pavel</a> 
<img src="https://github.com/blackcater/blackcater/raw/main/images/Hi.gif" height="32"/></h2>
<h3 align="center">I am a student from GeegBrains</h3>

### Выполнил: Шутылев П.В. 19.06.2024

### Задача 44: В ячейке ниже представлен код генерирующий DataFrame, которая состоит всего из 1 столбца. Ваша задача перевести его в one hot вид. Сможете ли вы это сделать без get_dummies?
* **`import random`**
* **`lst = ['robot'] * 10`**
* **`lst += ['human'] * 10`**
* **`random.shuffle(lst)`**
* **`data = pd.DataFrame({'whoAmI':lst})`**
* **`data.head()`**


### Решение:

#### Пример полученного результата:
* **`whoAmI_human  whoAmI_robot`**
* **`0          True         False`**
* **`1         False          True`**
* **`2          True         False`**
* **`3         False          True`**
* **`4          True         False`**

![PrintResult](Result c)

