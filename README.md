# phastest
Instalação do Phastest


### Download phastest-docker
```bash
wget -c https://phastest.ca/download_file/phastest-docker -O phastest-docker.zip 
```
* unzip
```bash
unzip phastest-docker.zip 
```

### Download docker-database
```bash
wget -c https://phastest.ca/download_file/docker-database -O docker-database.zip
```

* unzip
```bash
unzip docker-database.zip
```

### mover DB para 
```bash
mv DB phastest/phastest-app-docker/
```

### Run (teste)
```bash
cd phastest/phastest_inputs
docker compose run phastest -i fasta -s seq_test.fna
```
