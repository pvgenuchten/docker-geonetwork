# Usage

To be able to generate a elasticsearch-ready docker image, you will have:

1. Build your geonetwork.war (https://geonetwork-opensource.org/manuals/trunk/en/maintainer-guide/installing/installing-from-source-code.html#the-quick-way)
2. Clone this repository

```shell
git clone https://github.com/geonetwork/docker-geonetwork.git
cd docker-geonetwork/3.99.0
```

3.Get the generated webapp in the current directory, name it `geonetwork.war
```shell
cp ../../core-geonetwork/web/target/geonetwork.war .
```

4. Run the docker-composition from the current directory:

```shell
docker-compose build && docker-compose up
```

5. Open http://localhost:8080/geonetwork/ in a browser
