```php
<?php

namespace NaufalAns;

class About extends Me
{
    public function getDailyKnowledge(): array
    {
        return [
            Php::class,
            Laravel::class,
            Codeigniter::class
            Javascript::class,
            Vuejs::class,
            Css::class,
            Bootstrap::class,
            Tailwind::class,
        ];
    }
}
```
