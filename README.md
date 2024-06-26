## Serialization.NET

**Сериализация** представляет собой процесс преобразования состояния объекта в форму, пригодную для сохранения или передачи. Дополнением к сериализации служит десериализация, при которой осуществляется преобразование потока в объект. Вместе эти процессы обеспечивают хранение и передачу данных.

**В .NET доступны следующие технологии сериализации:**

* При двоичной сериализации сохраняется правильность типов, что полезно для сохранения состояния объекта между разными вызовами приложения. Например, можно обеспечить совместный доступ к объекту для разных приложений, сериализовав его в буфер обмена. Объект можно сериализовать в поток, на диск, в память, передать по сети и т. д. При удаленном управлении сериализация используется для передачи объектов "по значению" с одного компьютера или домена приложения на другой.

* При сериализации XML и SOAP сериализуются только открытые свойства и поля, а правильность типов не сохраняется. Этот метод полезен для предоставления или использования данных без ограничений работающего с ними приложения. Будучи открытым стандартом, XML привлекателен для совместного использования данных в Интернете. Аналогичным образом и SOAP представляет собой открытый стандарт, использование которого эффективно и удобно.

* При сериализации JSON сериализуются только открытые свойства, а правильность типов не сохраняется. Будучи открытым стандартом, JSON привлекателен для совместного использования данных в Интернете.
