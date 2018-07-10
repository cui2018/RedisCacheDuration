# RedisCacheDuration
扩展自Spring-Data-Redis，自定义注解实现缓存有效期的灵活设置，如您觉得该项目对您有用，欢迎点击右上方的Star按钮，给予支持！

# 使用方法
将包代码加入项目后，将SpringRedisCacheManager注册为bean，然后在类或方法上标注CacheDuration注解，并设置缓存有效时间，如果不设置，默认是60秒
