# Vcode简单的验证码扩展

include "./vendor/autoload.php";

use VcodeName\Vcode;

$code = new Vcode(150, 80, 6);
$code->outimg();


