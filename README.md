```php
<?php
namespace ArpitYadav;
class About extends Me
{
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'Backend Developer' => 'Ripenapps, Nodia',         
            ]
        ];
    }
    public function getDailyKnowledge(): array
    {
        return [
            PHP::class,
            Javascript::class,
            Laravel::class,
            Vue::class,
            React::class,
            Inertia::class,
            TailwindCss::class,
            Aws::class,
        ];
    }
    public function getFutureGoal(): string
    {
        return [
            'I am determined to launch the next greatest thing',
            'To contribute to open source',    
        ];
    }
    
    public function moreAboutme(): string
    {
        return 'http://arpityadav.me';
    }
}
```
