## CN

简单日期格式化。

|参数名|类型|说明|
|-----|----|---|
|date=new Date|Date|要格式化的日期对象|
|mask|string|日期格式|
|utc=false|boolean|是否是 UTC|
|gmt=false|boolean|是否是 GMT|

|掩码|说明|
|----|----|
|d|月份天数，不补零|
|dd|月份天数，不足两位补零|
|ddd|星期几，简称|
|dddd|星期几，全称|
|m|月份，数字，不补零|
|mm|月份，数字，不足两位补零|
|mmm|月份，简称|
|mmmm|月份，全称|
|yy|年份，只显示后两位数字，不足两位补零|
|yyyy|年份，显示四位数字|
|h|小时，不补零 (12 小时制)|
|hh|小时，不足两位补零（12 小时制）|
|H|小时，不补零（24 小时制）|
|HH|小时，不足两位补零（24 小时制）|
|M|分钟，不补零|
|MM|分钟，不足两位补零|
|s|秒数，不补零|
|ss|秒数，不足两位补零|
|l L|毫秒，l 显示 3 位， L 显示 2 位|
|t|小写显示上午下午，a 或 p|
|tt|小写显示上午下午，am 或 pm|
|T|大写显示上午下午，A 或 P|
|TT|大写显示上午下午，AM 或 PM|
|Z|美国时区缩写，比如 EST 或 MDT|
|o|GMT/UTC 时区时差，比如 -0500 或 +0230|
|S|月份天数序数后缀 （st，nd，rd，或 th）|
|UTC:|是否是 UTC，必须写在最前面|

