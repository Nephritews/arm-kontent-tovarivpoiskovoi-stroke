# Пользовательская инструкция по работе с инфоблоком "Товары в поисковой строке" 
### Данная инструкция предназначена для контент-менеджеров сайта https://vitaexpress.ru (далее Вита-сайт). Инструкция описывает инфоблок «АРМ контент-менеджера» "Товары в поисковой строке"  и регламентирует порядок действий, необходимых для решения задач контент-менеджера по наполнению сайта. 
![Безымянный11](https://user-images.githubusercontent.com/85296765/124230949-bc542680-db20-11eb-91ae-8b71615eb107.png)
#  Настройка.
Настройка - базовая настройка инфоблока. Название - данное поле является основным названием для инфоблока и используется для его идентификации (обязательны для заполнения). Код - автогенерируемое поле, составляемое на основе названия и использует латинские символы (обязательны для заполнения). Предназначено для идентификации инфоблока и формирования маршрутизации. Родительский элемент - список родительских инфоблоков, предназначенная для организации древовидной структуры разделов и подразделов. Также имеются дополнительные вкладки для заполнения, такие как: "SEO", "Свойства", "Cвойства разделов", "Свойство элементов". В них находится основная информация как о инфоблоке, так и об элементах, которые в нём располагаются.
### Образец
![5678](https://user-images.githubusercontent.com/85296765/123426059-f75fd280-d5d3-11eb-8e4f-0bdb2e1365ee.png)
* Настройка > Ввод названия. Название - данное поле является основным названием для инфоблока и используется для его идентификации на сайте (обязательны для заполнения).
![1](https://user-images.githubusercontent.com/85296765/123248453-002fa600-d4f9-11eb-9cb5-696611787a85.png)
*  Настройка > Сгенерировать > Код. Код генерируется на основе названия. Код - автогенерируемое поле, составляемое на основе названия и использует латинские символы (обязательны для заполнения). Предназначено для идентификации инфоблока и формирования роутинга. Код служит для идентификации элементов может использоваться в маршрутизации и формирование ссылки.
![2](https://user-images.githubusercontent.com/85296765/123248136-a3cc8680-d4f8-11eb-88d3-1a651189bd54.png)
* Настройка > Родительский элемент. При указании каталога дочерним он будет использовать свойства родительского каталога. Родительский элемент описание кнопок (при выборе пропадают вкладки свойства, свойства разделов, свойства элементов). Дочерний элемент использует свойства разделов элементов родительского каталога. Родительский элемент, указывается при отсутствии элементов у каталога. Родительский элемент - список родительских инфоблоков, предназначенная для организации древовидной структуры разделов и подразделов. 
![45](https://user-images.githubusercontent.com/85296765/123248670-3e2cca00-d4f9-11eb-8c04-737f44e76bf8.png)
* Активность для промышленного и тестового сервера. При создании каталога или элемента их нет, они будут видны, если после создания открыть вкладку "Настройка или "Элементы". После создания, по умолчанию они создадутся неактивными - с пустыми полями. Используются, чтобы указать их активность для промышленного или тестового сервера и даты их активность, ограничивающую.
![67](https://user-images.githubusercontent.com/85296765/123419429-43f2e000-d5cb-11eb-91bd-eec3ad479e9f.png)
# Элементы.
Примеры товаров в поисковой строке: настройка и свойства (базовая информация об элементах). Во вкладке элементы - оранжевая кнопка с плюсом. При нажатии выскакивает вкладка новый элемент в ней вкладка настройки с названием и кодом элемента. Название - данное поле является основным для инфоблока и используется для его идентификации. Код - автогенерируемое поле, составляемое на основе названия и использует латинские символы (код генерируется на основе названия). Вкладка свойства берёт информацию от первого родителя.
### Образец созданных элементов.
![14](https://user-images.githubusercontent.com/85296765/123380732-df229000-d5a0-11eb-9984-d53166f61205.png)
* Поиск элемента. Навигация по списку элементов.
![23](https://user-images.githubusercontent.com/85296765/123264745-61607500-d50b-11eb-8467-dc03ad0adfd6.png)
* Для поиска введите названия элемента в строку поиска (например, терафлекс).
![Безымянный564](https://user-images.githubusercontent.com/85296765/123417394-c5953e80-d5c8-11eb-9a35-4c26525c577c.png)
# Создание элемента.
* Оранжевая кнопка с плюсом, добавить новый элемент.
![23](https://user-images.githubusercontent.com/85296765/123254268-80f1a080-d4ff-11eb-8165-7c81a081c09f.png)
* При нажатии на новый элемент откроется окно с новым элементом.
![27](https://user-images.githubusercontent.com/85296765/123595178-a7665300-d801-11eb-9d22-a216f634b44c.png)
* Окно с новым элементом, настройками и свойством.
![23](https://user-images.githubusercontent.com/85296765/123254746-13923f80-d500-11eb-8af9-6d6ba81731ff.png)
* Введите название (обязательны для заполнения).
![234](https://user-images.githubusercontent.com/85296765/123395979-d9817600-d5b1-11eb-93a9-13705bfe8eac.png)
* Сгенерируйте код (код генерируется на основе названия) (обязательны для заполнения).
![23](https://user-images.githubusercontent.com/85296765/123255028-6bc94180-d500-11eb-8c7f-00b12c3cf1fd.png)
* Введите свойства. Имеется два типа свойств: приоритет (PRIORITY) и Ссылка (LINK).
![25](https://user-images.githubusercontent.com/85296765/123259819-f8c2c980-d505-11eb-9282-0db0943125b8.png)
* Нажмите сохранить.
![25](https://user-images.githubusercontent.com/85296765/123256949-97e5c200-d502-11eb-8b51-1c361be8d3b2.png)
* Оранжевая кнопка с плюсом, добавить новый элемент не использовать.
![Безымянный11](https://user-images.githubusercontent.com/85296765/124233350-d04d5780-db23-11eb-836f-e71b29dfc460.png)

# Активности разделов и элементов.
https://vitaexpress.ru/ (промышленный сервер) и https://dev.vitaexpress.ru/ (тестовый сервер). 
У разделов и элементов во вкладке "Настройки" присутствуют дополнительные поля, отвечающие за активность и временной диапазон активности, как показано на рисунке ниже. 
Чекбокс активности влияет на отображение элемента. Все создаваемые разделы и элементы являются неактивными. Если галочка активность элемента не проставлена, элемент на сайте отображен не будет, вне зависимости от даты и времени. 
### Образец
![56](https://user-images.githubusercontent.com/85296765/123396897-e5ba0300-d5b2-11eb-9a38-257eb71d784a.png)
* Для того чтобы элемент или раздел отображался на сайте задайте ему временной диапазон.
![Безымянный11](https://user-images.githubusercontent.com/85296765/124233764-3cc85680-db24-11eb-9460-d4b59f5a910f.png)
![Безымянный11](https://user-images.githubusercontent.com/85296765/124234910-b280f200-db25-11eb-8bc4-17a6eef38ff1.png)
* Если поля даты и времени будут пустыми, элемент по умолчанию будет показываться.
![Безымянный11](https://user-images.githubusercontent.com/85296765/124233995-84e77900-db24-11eb-93ca-8bad98ad437a.png)
* Если раздел отключен, вне зависимости от активности внутренних элементов, отображаться на сайте как раздел, так и все дочерние элементы не будут.
# Обновление свойств элемента.
* Для изменения свойств элемента перейдите во вкладку раздела "Элементы". Далее, выбрав элемент из списка, необходимо на него нажать, после появления элемента в модальном окне, изменить данные во вкладке "Свойства". На примере раздела "Товары в поисковой строке" заполняемыми свойствами являются 2 свойства: Приоритет (PRIORITY) и Ссылка (LINK). Приоритетность отвечает за место расположения в поисковой строке. Ссылка фигурирует для перехода по слову. Ссылка формируется от корня сайта: vitaexpress.ru/LINK. Переход на сторонние под домены не предусматривается данным функционалом.
![23](https://user-images.githubusercontent.com/85296765/123264193-d7b0a780-d50a-11eb-9f03-e951506b5f3c.png)
* Для навигации по списку элементов предусмотрена пагинация и поиск элементов.
![Безымянный12](https://user-images.githubusercontent.com/85296765/124237648-cda13100-db28-11eb-9c4c-9a27f26ad927.png)
* При редактировании одного и более элементов перед переходом на новую страницу необходимо сохранить все текущие изменения, как показано на рисунке:
![Безымянный11](https://user-images.githubusercontent.com/85296765/124238125-4acca600-db29-11eb-9543-85d2faf64855.png)
* При обновление списка несохранённые измениния будут потеряны, продолжить?

![Безымянный11](https://user-images.githubusercontent.com/85296765/124237731-e578b500-db28-11eb-95e8-8f2f52c23da0.png)
# Удаление данных.
* Элементы удаляются по отдельности. Для удаления элемента нужно нажать на иконку корзины с правой стороны от элемента и подтвердить удаление во всплывающем окне.
![254](https://user-images.githubusercontent.com/85296765/123245853-459ea400-d4f6-11eb-9847-ae8e4052e022.png)
* При попытках удалить каталог изначально нужно удалить вложенные дочерние элементы. 
![Безымянный503](https://user-images.githubusercontent.com/85296765/123597859-eb0e8c00-d804-11eb-871e-ad7d3e512f42.png)











