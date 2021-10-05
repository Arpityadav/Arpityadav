```php
<?php
namespace ArpitYadav;
class About extends Me
{
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'student' => 'RKGIT, Ghaziabad',         
            ]
        ];
    }
    public function getDailyKnowledge(): array
    {
        return [
            Php::class,
            Javascript::class,
            Laravel::class,
            Vuejs::class,
            Angular::class,
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
        return 'https://arpityadav.netlify.com';
    }
}
```
