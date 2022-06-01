```php
<?php

namespace Invertime;

class About extends Me
{
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'place' => 'High school',
                'position' => 'Student'         
            ]
        ];
    }

    public function getDailyKnowledge(): array
    {
        return [
            Html::class,
            Css::class,
            Javascript::class,
            Php::class,            
            Laravel::class,
            Vuejs::class,
            CyberSecurity::class,
        ];
    }

    public function getFutureGoal(): string
    {
        return 'To get a job in cybersecurity';
    }
}
```