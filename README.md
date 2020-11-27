# docker-demo

Source code of docker-demo for Article:
https://protonalex.com/lokalnyj-veb-sever-vnutri-docker

## Inside

- PHP 7.2
- Nginx
- MySQL
- Composer

## Clone project via GIT

```
git clone https://github.com/dignityinside/docker-demo
cd docker-demo
```

#### Build and run Docker

- `docker-compose build` - Build Docker
- `docker-compose up -d` - Start Docker
- `docker-compose exec php /bin/bash` - SSH Login to Docker
- `docker-compose down` - Stop Docker

#### Add new hosts to your `hosts` File:

```
127.0.0.1 demo.local
```

#### Development links
```
http://demo.local:8025
```

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Contributing
1. Fork it
2. Create your feature branch (git checkout -b my-new-feature)
3. Make your changes
4. Commit your changes (git commit -am 'Added some feature')
5. Push to the branch (git push origin my-new-feature)
6. Create new Pull Request
