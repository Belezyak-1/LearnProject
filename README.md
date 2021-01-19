Мобильное приложение для благотворительных организаций


**Инструменты, языки, платформы**
Платформа для разработки: Android Studio  
Язык: Java  
База данных: Firebase  
Карты: Google Maps SDK Android   

Для тестирования преокта его необходимо открыть в Android Studio. Основной экран: activity_maps.xml.   
Тестирование на эмуляторах и телефонах с версией Android не ниже 6.0 (Marshmallow).  
Необходимо памяти не менее 50Мб.  
____
**Основные библиотеки/классы:**
Работа с картами  
• android.gms.maps.GoogleMap  
• android.gms.maps.model.LatLng;  
• android.gms.maps.model.Marker;  
Работа с базой данных  
• firebase.database.ChildEventListener;  
• firebase.database.DataSnapshot;  
• firebase.database.FirebaseDatabase;  
____
**Необходимый функционал:**
- Просмотр карт, отметка точек по координатам  
- Возможность регистрации пользователей  
- Организации могут добавлять и редактировать список необходимой помощи  
- Организация вывода данных из БД в карточки организаций  
____
**Реализованный функционал:**
- Добавление данных об организации в базу  
- Чтение данных из базы  
- Отметка маркеров на карте по координатам  
- Вывод информации об организации в информационное окно  
