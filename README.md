# Основное задание
Написать SPA web-приложение, которое при запуске будет считывать находящийся в корневой директории json-файл и отображать его в виде нумерованного отсортированного списка.
Элемент списка должен быть написан цветом style.color и содержать данные вида: "1A - красный".
Сортировка по убыванию на основе поля sortOrder.


Входные данные Файл data.json
```json
    {
    	"1A": { 
    		"name": "Красный",
    		"sortOrder": 3,
    		"style": { "color": "#FF0000" }
    	},
    	"H5": {
     		"name": "Синий",
    		"sortOrder": 1,
    		"style": { "color": "#00FF00" }
    	}, 
    	"RE": {
    		"name": "Зеленый",
    		"sortOrder": 53, 
    		"style": { "color": "#0000FF" } 
    	}
     }
```


## Дополнительное задание
Под список добавить кнопку "Сохранить", по нажатию на которую должен быть скачан файл modified-data.json.
Данный файл должен содержать массив следующей структуры, сформированный на основе исходного файла data.json.
```json
[ { "id": "1A", "name": "Красный", "sortOrder": 3, "color": "#FF0000" } ]
```

