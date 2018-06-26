FROM erikdubbelboer/phpredisadmin:v1.10.2

//添加redis密码认证
COPY includes/config.environment.inc.php /src/app/includes/config.inc.php

WORKDIR /src/app

EXPOSE 80

ENTRYPOINT [ "php", "-S", "0.0.0.0:80" ]
