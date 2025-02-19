#### 1.Введение
В любом подразделении/воинской части/гарнизоне существует такой вид несения службы, как несение службы в суточном наряде. Существуют различные типы и виды суточных нарядов, служба в которых должна нестись непрерывно. Также стоит отметить, что любой наряд по службе – нагрузка для любого военнослужащего, поэтому служба в них должна нестись согласно строго утвержденного графика и делиться поровну между всеми военнослужащими данного подразделения/воинской части/гарнизона. Именно поэтому, для расстановки и контроля несения службы в суточном наряде, я решил взяться за разработку базы данных, содержащую графики нарядов, как инстурмент контроля, в которых будут отмечаться наряды, отхоженные военнослужащими. База данных будет содержать в себе графики нарядов для каждого подразделения какой-либо отдельно взятой воинской части. Каждый командир в воинской части сможет получить доступ к графикам нарядов в своем подразделении и сможет контролировать несение службы в суточном наряде.

### 2. Требования пользователя.
## 2.1. Программные интерфейсы.
Язык программирования: С#.
Среда разработки:Visual Studio.
## 2.2. Интерфейс пользователя.

При запросе роты/команды приложение будет выдавать график наряда подразделения .
Возможность в 3 клика добавить или убрать наряд отдельному военнослужащему.
Возможность добавить информацию о военнослужащем, а так же удалить ее.
Возможность изменять информацию о уже добавленом в базу военнослужащем.

## 2.3. Характеристики пользователей
Простой интерфейс приложение будет позволять использовать его практически любым категориям пользователей. Особенно это будет актуально для армии-среды, отдаленной от компьютерной техники. Приложение разрабатывается для командиров подразделений различных рангов и должностей: от командира взвода, до командира воинской части.


### 3. Системные требования
## 3.1. Функциональные требования
1. Список подразделений и военнослужащих воинской части.
2. Возможность добавления и удаления военнослужащих и подразделений.
3. Возможность редактирования графика нарядов, а именно, замена нарядов и добавления нарядов вне очереди.
4. Система поиска по приложению. Предполагает под собой поиск графиков нарядов подразделений по их наименованиям. Поиск информации об отдельном военнослужащем по фамилии и воинскому званию.
## 3.2. Нефункциональные требования
1.Простота. Для пользования приложением достаточно будет владеть школьным курсом информатики.
2.Добавление данных о военнослужащем или подразделении в базу в 3 клика.
