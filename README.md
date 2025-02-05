# phastest
Instalação do Phastest


### Download phastest-docker
```bash
wget -c https://phastest.ca/download_file/phastest-docker
```
* unzip
```bash
unzip phastest-docker.zip 
```

### Download docker-database
```bash
wget -c https://phastest.ca/download_file/docker-database
```

* unzip
```bash
unzip phastest-docker.zip 
```

### mover DB para 
```bash
mv DB phastest-app-docker/
```

### Run (teste)
```bash
cd phastest-docker/phastest_inputs
docker compose run phastest -i fasta -s seq_test.fna
```
