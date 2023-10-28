# Installation

```
git clone https://github.com/atareao/self-hosted.git
cd self-hosted/portainer
cp sample.env .env
sed -i "s/portainer.tuservidor.es/el_fqdn_que_quieras/g" .env
```

Llega el momento de levantar el servicio y comprobar el funcionamiento. Esto lo puedes hacer con las siguientes l-ineas

```
docker compose up -d
docker compose logs -f
```