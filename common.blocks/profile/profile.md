**Модификаторы**:

    {bool} followInfo - включает/отключает информацию о подписчиках, подписках и сидах
    {bool} description - включает/отключает информацию "О себе"
    {bool} subscribeButton - включает/отключает кнопку "Подписка"

**Поля**:

     {object} profile - объект пользователя. Должен содержать seedsCount. ОБЯЗАТЕЛЕН
     {string} currentUserId - идентификатор текущего пользователя. ОБЯЗАТЕЛЕН ДЛЯ subscribe-button == true.
     {bool} subscribe - признак подписан ли текущий пользователь на пользователя, чей profile отображается.
                        ОБЯЗАТЕЛЕН ДЛЯ subscribe-button == true.
     