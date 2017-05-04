Реализовать функцию  fuzzysearch как в редакторе  sublime text 3 . Пример работы:
    fuzzysearch('car', 'cartwheel');        // true
    fuzzysearch('cwhl', 'cartwheel');       // true
    fuzzysearch('cwheel', 'cartwheel');     // true
    fuzzysearch('cartwheel', 'cartwheel');  // true
    fuzzysearch('cwheeel', 'cartwheel');    // false
    fuzzysearch('lw', 'cartwheel');         // false
По факту требуется проверить, является ли первая строка подпоследовательностью второй.
