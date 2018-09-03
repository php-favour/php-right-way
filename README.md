# php编程之道资源细化

基于<a href="https://phptherightway.golaravel.com/" targe="_blank">php编程之道</a>整理相关的学习资源

## php调试
#### phpstorm & xdebug 调试
1. 应用篇
  * 本地基于web-server的调试配置
  * 本地基于cli的调试配置
  * 远程基于web-server调试配置
  * 远程基于cli的调试配置
  
2. 原理篇
  * <a href="https://laravel-china.org/articles/4090/the-first-step-to-becoming-a-senior-php-programmer-debugging-xdebug-principle" target="_blank">成为高级 PHP 程序员的第一步——调试（xdebug 原理篇）</a>

## 依赖管理

### composer & pear

#### composer自动加载的实现
* <a href="https://www.zybuluo.com/phper/note/66447" target="_blank"> php中的自动加载 </a>
* <a href="http://laravelacademy.org/post/7074.html" target="_blank"> 深入学习 Composer 自动加载（autoload）机制 </a>
* <a href="https://docs.phpcomposer.com/04-schema.html#autoload" target="_blank"> composer所支持的四种自动加载形式 </a>
  > psr-4对应vendor/composer/autoload_psr4.php文件
  
  > psr-0对应vendor/composer/autoload_namespaces.php文件
  
  > classmap对应vendor/composer/autoload_classmap.php文件
  
  > file对应vendor/composer/autoload_files.php文件
