.jshintrc ： JSHint是一种JS代码检查工具，这个文件是其个性化的配置文件
.gitinore : 是git配置需要忽略文件的配置文件
.travis.yml : travis是一个持续集成的平台，这是其配置文件

nodeclub 以 express + mongodb + mongoose 作为基本框架, 典型的 MVC 应用
Model: 对应mongoose orm， models目录
view： ejs模板， views目录
controler：express middleware , contollers目录

### 使用的模块

#### bcryptjs

bcrypt是一个跨平台的文件加密工具，How To Safely Store A Password

#### bytes

bytes(1024);
// output: '1kB' 
 
bytes(1000);
// output: '1000B' 
 
bytes(1000, {thousandsSeparator: ' '});
// output: '1 000B' 
 
bytes(1024 * 1.7, {decimalPlaces: 0});
// output: '2kB' 
 
bytes(1024, {unitSeparator: ' '});
// output: '1 kB' 

#### colors

让你的console.log呈现颜色

var colors = require('colors');
 
console.log('hello'.green); // outputs green text 
console.log('i like cake and pies'.underline.red) // outputs red underlined text 

#### compression

代码压缩中间件
支持：deflate，gzip

#### connect-redis

connect-redis is a Redis session store backed by node_redis
connect-radis 是一个Radis的会话缓存，被node_redis支持‘

#### cookie-parser

Parse Cookie header and populate req.cookies with an object keyed by the cookie names.
Optionally you may enable signed cookie support by passing a secret string, 
which assigns req.secret so it may be used by other middleware.

解析Cookie

