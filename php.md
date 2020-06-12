# PHP Style Guide



Most of the structure of variable naming, array style/structure will be same as javascript. Below is the way a class is organized to show you what type of style the php will follow.



```php
<?php
    
namespace App\Namespace;

use Some\SomeTrait;
use Some\OtherTrait;
use Some\Package\PackageName;

class FileName extends Parent implements Interface
{
    use SomeTrait, OtherTrait;
    
    public $varName = 'something';
    private $otherVarName;
    protected $someOtherVarName;
    
    public function __construct($varName, $otherVarName, $someOtherVarName)
    {
        $this->varName = $varName;
        $this->otherVarName = $otherVarName;
        $this->someOtherVarName = $someOtherVarName;
    }
    
    public function __construct(
    	PackageName $varName,
        PackageName $otherVarName,
        PackageName $someOtherVarName
    ) {
        $this->varName = $varName;
        $this->otherVarName = $otherVarName;
        $this->someOtherVarName = $someOtherVarName;
    }
    
    public function otherFunctionName()
    {
        $this->doSomething();
        
        // for loop structured like this. spaces between ; and opening curly brace in the same line
        for ($x = 0; $x < 10; $x++) {
            
        }
        
        // if condition is also same as for loop
        if ($someLogic === true) {
            
        }
        
        // if there is not operator it should have space in between
        if (! $someLogic) {
            
        }
        
        return $something; // return always on it own line and 1 line break before it
    }
}
```

