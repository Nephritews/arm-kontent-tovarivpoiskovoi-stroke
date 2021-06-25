# Пользовательская инструкция по работе с инфоблоком "Товары в поисковой строке" 
### Данная инструкция предназначена для контент-менеджеров сайта https://vitaexpress.ru (далее Вита-сайт). Инструкция описывает функциональные вкладки системы «АРМ контент-менеджера» и регламентирует порядок действий, необходимых для решения задач контент-менеджера по наполнению сайта. 

#  Настройка.
Настройка - базовая настройка инфоблока. Название - данное поле является основным для инфоблока и используется для его идентификации (обязательны для заполнения). Код - автогенерируемое поле, составляемое на основе названия и использует латинские символы (обязательны для заполнения). Предназначено для идентификации инфоблока и формирования роутинга. Родительский элемент - список родительских инфоблоков, предназначенная для организации древовидной структуры разделов и подразделов. Также имеются дополнительные вкладки для заполнения, такие как: "SEO", "Свойства", "Cвойства разделов", "Свойство элементов". В них находится основная информация как о инфоблоке, так и об элементах, которые в нём располагаются.
### Образец
![товары в поисковой строке](https://user-images.githubusercontent.com/85296765/123216066-33af0800-d4da-11eb-84cd-01a08e2d9fa3.png)
* Настройка > Ввод названия. Название - данное поле является основным для инфоблока и используется для его идентификации на сайте (обязательны для заполнения).
![1](https://user-images.githubusercontent.com/85296765/123248453-002fa600-d4f9-11eb-9cb5-696611787a85.png)
*  Настройка > Сгенерировать > Код > Код генерируется на основе названия. Код - автогенерируемое поле, составляемое на основе названия и использует латинские символы (обязательны для заполнения). Предназначено для идентификации инфоблока и формирования роутинга. Код служит для идентификации элементов может использоваться в маршрутизации и формирование ссылки.
![2](https://user-images.githubusercontent.com/85296765/123248136-a3cc8680-d4f8-11eb-88d3-1a651189bd54.png)
* Настройка > Родительский элемент > При указании каталога дочерним он будет использовать свойства каталога. Родительский элемент описание кнопок (при выборе пропадают вкладки свойства, свойства разделов, свойства элементов). Дочерний элемент использует свойства разделов элементов родительского каталога. Родительский элемент, указывается при отсутствии элементов у каталога. Родительский элемент - список родительских инфоблоков, предназначенная для организации древовидной структуры разделов и подразделов. 
![45](https://user-images.githubusercontent.com/85296765/123248670-3e2cca00-d4f9-11eb-8c04-737f44e76bf8.png)
* Активность для промышленного и тестового сервера. При создании каталога или элемента их нет, они будут видны если открыть каталог или элемент после создания, по умолчанию они создадутся неактивными - с пустыми полями. Используются, чтобы указать их активность для промышленного или тестового сервера и даты их активность ограничивающую.
![активности](https://user-images.githubusercontent.com/85296765/123218690-14fe4080-d4dd-11eb-9ffd-830b18fb02cb.png)
# Элементы.
Примеры товаров в поисковой строке: настройка и свойства (базовая информация об элементах). Во вкладке элементы - оранжевая кнопка с плюсом. При нажатии выскакивает вкладка новый элемент в ней вкладка настройки с названием и кодом элемента. Название - данное поле является основным для инфоблока и используется для его идентификации. Код - автогенерируемое поле, составляемое на основе названия и использует латинские символы (код генерируется на основе названия). Вкладка свойства берёт информацию от первого родителя.
### Образец созданных элементов.
![14](https://user-images.githubusercontent.com/85296765/123380732-df229000-d5a0-11eb-9984-d53166f61205.png)
# Создание элемента.
* Оранжевая кнопка с плюсом, добавить новый элемент.
![23](https://user-images.githubusercontent.com/85296765/123254268-80f1a080-d4ff-11eb-8165-7c81a081c09f.png)
* При нажатии на новый элемент откроется окно с новым элементом.
![23](https://user-images.githubusercontent.com/85296765/123254436-b5fdf300-d4ff-11eb-9649-105aa5467260.png)
* Окно с новым элементом, настройками и свойством.
![23](https://user-images.githubusercontent.com/85296765/123254746-13923f80-d500-11eb-8af9-6d6ba81731ff.png)
* Введите название (обязательны для заполнения).
![234](https://user-images.githubusercontent.com/85296765/123395979-d9817600-d5b1-11eb-93a9-13705bfe8eac.png)
* Сгенерируйте код (код генерируется на основе названия) (обязательны для заполнения).
![23](https://user-images.githubusercontent.com/85296765/123255028-6bc94180-d500-11eb-8c7f-00b12c3cf1fd.png)
*   Введите свойства. Имеется два типа свойств приоритетность и ссылка. 
![25](https://user-images.githubusercontent.com/85296765/123259819-f8c2c980-d505-11eb-9282-0db0943125b8.png)
* Нажмите сохранить.
![25](https://user-images.githubusercontent.com/85296765/123256949-97e5c200-d502-11eb-8b51-1c361be8d3b2.png)
* Поиск элемента.
![23](https://user-images.githubusercontent.com/85296765/123264745-61607500-d50b-11eb-8467-dc03ad0adfd6.png)
* Для поиска введите названия элемента в строку поиска (например, терафлекс).
![567](https://user-images.githubusercontent.com/85296765/123391849-7b529400-d5ad-11eb-8e56-c7b562eec7e0.png)
# Активностир разделов.
Активности разделов делятся на два типа: промышленный и тестовый сервер.
https://vitaexpress.ru/ (мастер и прод платформа) и https://dev.vitaexpress.ru/ (дев и тест платформа). Тестовый проверяется на дев версии сайта (для этого будет указан дев сервера и даты начала и конца активности блока). Даты нужны для того чтобы можно было указать в каком временном диапазоне этот блок используется, например только в следующем месяце. Промышленный 
![56](https://user-images.githubusercontent.com/85296765/123396897-e5ba0300-d5b2-11eb-9a38-257eb71d784a.png)
# Обновление данных элементов.
* При изменении каталогов элементов появляется иконка, указывающая о изменение.
![23](https://user-images.githubusercontent.com/85296765/123264193-d7b0a780-d50a-11eb-9f03-e951506b5f3c.png)
* При переходе на новую страницу обновления не будут сохранены.
![обнова 23](https://user-images.githubusercontent.com/85296765/122167531-2cf61480-ce8c-11eb-8edf-f24b994207c9.png)
* Если вы хотите сохранить элемент, нажмите кнопку сохранить.
![солх](https://user-images.githubusercontent.com/85296765/123393647-57904d80-d5af-11eb-91a9-2462402ff022.png)
# Удаление данных.
* При удалении элементов, нажмите на икону корзины. В открывшемся окне, нажмите кнопку ок.
![254](https://user-images.githubusercontent.com/85296765/123245853-459ea400-d4f6-11eb-9847-ae8e4052e022.png)
* Подтвердите действия на странице, нажмите кнопку ок.
![ок](https://user-images.githubusercontent.com/85296765/123262825-5dcbee80-d509-11eb-8771-c29f2ab5bc3a.png)







