# coinhive-miner
coinhive miner auto build

## Usage
Edit the last line of your Dockerfile
>CMD coin-hive {your site key}

then 
```
docker build -t coinhive .
docker run coinhive
```