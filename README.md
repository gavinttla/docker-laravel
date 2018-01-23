# docker-laravel
dev environment using docker. modify from laradock with my own use/setting.

# Notes

- 根目录下的 '.env' 里面的mysql host用：mysql， 不是localhost，也不是127.0.0.1 
- 如果想添加workspace里面的模块，例如: less, less-watch-compiler。直接修改 /workspace/Dockerfiler-71，71是当前php版本号，完了之后需要重新build一下， docker-compose build workspace