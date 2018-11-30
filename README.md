# Vcode简单的验证码扩展
### 安装
composer require chaodada/Vcode:dev-master
### 使用
include "./vendor/autoload.php";

use VcodeName\Vcode;

$code = new Vcode(150, 80, 6);
$code->outimg();


