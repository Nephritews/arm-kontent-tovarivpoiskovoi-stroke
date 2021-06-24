# Пользовательской инструкции по работе с инфоблоком "Товары в поисковой строке" 
### Данная инструкция предназначена для контент-менеджеров сайта https://vitaexpress.ru (далее Вита-сайт). Инструкция описывает функциональные вкладки системы «АРМ контент-менеджера» и регламентирует порядок действий, необходимых для решения задач контент-менеджера по наполнению сайта. 
* Раздел инфоблоки http://172.16.31.17/#/login.
#  Настройка.
Настройка - базовая настройка инфоблока. Название - данное поле является основным названием для инфоблока и используется для его идентификации. Код - автогенерируемое поле, составляемое на основе названия и использует латинские символы. Предназначено для идентификации инфоблока и формирования роутинга. Родительский элемент - список родительских инфоблоков, предназначенная для организации древовидной структуры разделов и подразделов. Также имеются дополнительные вкладки для заполнения, такие как: "SEO", "Свойства", "Cвойства разделов", "Свойство элементов". В них находится основная информация как о инфоблоке, так и об элементах, которые в нем располагаются.

![товары в поисковой строке](https://user-images.githubusercontent.com/85296765/123216066-33af0800-d4da-11eb-84cd-01a08e2d9fa3.png)
* Настройка > Ввод названия.
![1](https://user-images.githubusercontent.com/85296765/123248453-002fa600-d4f9-11eb-9cb5-696611787a85.png)
*  Настройка > Сгенерировать > Код > Код генерируется на основе названия.
![2](https://user-images.githubusercontent.com/85296765/123248136-a3cc8680-d4f8-11eb-88d3-1a651189bd54.png)
* Настройка > Родительский контроль > При указании каталога дочерним он будет использовать свойства каталога.  
![3](https://user-images.githubusercontent.com/85296765/123248162-a9c26780-d4f8-11eb-98cc-462f6fa32524.png)
* Родительский контроль описание кнопок (при выборе пропадают вкладки свойства, свойства разделов, свойства элементов). Дочерний элемент использует свойства разделов элементов родительского каталога. Родительский элемент, указывается при отсутствии элементов у каталога.
![45](https://user-images.githubusercontent.com/85296765/123248670-3e2cca00-d4f9-11eb-8c04-737f44e76bf8.png)

* Активность для промышленного и тестового сервиса.
Активность для каталогов, те же поля есть для элементов. При создании каталога или элемента их нет, они будут видны если открыть каталог или элемент после создания, по умолчанию они создадутся неактивными - с пустыми полями. Используются, чтобы указать их активность для пром или тест сервера и даты их активность ограничивающую.
![активности](https://user-images.githubusercontent.com/85296765/123218690-14fe4080-d4dd-11eb-9ffd-830b18fb02cb.png)

# Элементы.
Элементы - товары в поисковой строке: настройка и свойства (базовая информация об элементах). Во вкладке элементы - оранжевая кнопка с плюсом. При нажатии выскакивает вкладка новый элемент в ней вкладка настройки с названием и кодом элемента. Название - данное поле является основным названием для инфоблока и используется для его идентификации. Код - автогенерируемое поле, составляемое на основе названия и использует латинские символы (код генерируется на основе названия). Вкладка свойства берёт информацию от первого родителя.

![товары в поиской строке элементы](https://user-images.githubusercontent.com/85296765/123217430-9ead0e80-d4db-11eb-9e60-989ef831cbc7.png)
# Создание элемента.
* Оранжевая кнопка с плюсом, добавить новый раздел.
![оранд](https://user-images.githubusercontent.com/85296765/120998556-de13f500-c790-11eb-8f03-86c343d5eaf3.png)
* Новый элемент.
![оранд2](https://user-images.githubusercontent.com/85296765/120998822-1ca9af80-c791-11eb-9bd6-b87ec5fcbf90.png)
* Настройки.
![оранд3](https://user-images.githubusercontent.com/85296765/120998981-46fb6d00-c791-11eb-9734-ed9e2b066895.png)
* Название
![орандж4](https://user-images.githubusercontent.com/85296765/120999116-6befe000-c791-11eb-8601-0e0577064ff9.png)
* Сгенерировать код (код генерируется на основе названия).
![орандж5](https://user-images.githubusercontent.com/85296765/120999279-9cd01500-c791-11eb-8618-d07a8ee9d3df.png)
* Свойства.
![oranj](https://user-images.githubusercontent.com/85296765/121000481-f127c480-c792-11eb-9a95-71791b0a9f38.png)
* Нажмите сохранить.
![сохра](https://user-images.githubusercontent.com/85296765/123246869-53a0f480-d4f7-11eb-89f2-c1db59ac3509.png)

# Созданные свойства (образец).
* Вкладка настройка.
![настройки готовая](https://user-images.githubusercontent.com/85296765/123233011-c22b8580-d4ea-11eb-88df-785c6f4b6bad.png)

* Активность для промышленного и тестового сервиса.
Активность для элементов, те же поля есть для каталогов. При создании элемента или каталога их нет, они будут видны если открыть элемент или каталог после создания, по умолчанию они создадутся неактивными - с пустыми полями. Используются, чтобы указать их активность для пром или тест сервера и даты их активность ограничивающую.
![активности23](https://user-images.githubusercontent.com/85296765/123226178-75dd4700-d4e4-11eb-92c9-4f75519609ac.png)
* Вкладка свойства.
![свойства](https://user-images.githubusercontent.com/85296765/123233253-f4d57e00-d4ea-11eb-9d8c-83ccb6d3a710.png)

# Обновление данных элементов.

* При изменение каталогов элементов появляется иконка, указывающая о изменение.
![MicrosoftTeams-image (2)](https://user-images.githubusercontent.com/85296765/122168014-cc1b0c00-ce8c-11eb-8f92-3c94dca705b5.png)
* При переходе на новую страницу обновления не будут сохранены.
![обнова 23](https://user-images.githubusercontent.com/85296765/122167531-2cf61480-ce8c-11eb-8edf-f24b994207c9.png)

# Удаление данных.
* Удаление элементов. 
![254](https://user-images.githubusercontent.com/85296765/123245853-459ea400-d4f6-11eb-9847-ae8e4052e022.png)





