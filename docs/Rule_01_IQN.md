IQN (iSCSI Qualified Name) — iSCSI-типизированные имена
Описание требования к формату имени в [RFC7143](https://www.rfc-editor.org/rfc/rfc7143) (https://www.rfc-editor.org/rfc/rfc7143) .
## 1. Формат:
iqn.yyyy-mm.ru.openyard:unique_name
* •	буквенная аббревиатура iqn
* •	дата (гггг-мм), когда блок присвоения имен завладел доменом
* •	имя домена в обратном порядке (ru.openyard)
* •	необязательное ":", служащее префиксом для имени хранилища, указанного блоком присвоения имен
* •	общая длина строки - не более 128 символов
## 2. Символы ASCII ([RFC3722](https://www.rfc-editor.org/rfc/rfc3722) (https://www.rfc-editor.org/rfc/rfc3722)):
*    -  ASCII dash character ('-' = U+002d)
*    -  ASCII dot character ('.' = U+002e)
*    -  ASCII colon character (':' = U+003a)
*    -  ASCII lower-case characters ('a'..'z' = U+0061..U+007a)
*    -  ASCII digit characters ('0'..'9' = U+0030..U+0039)