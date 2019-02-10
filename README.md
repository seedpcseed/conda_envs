# conda_envs

* To download yaml files of this repository: 

```
git clone https://github.com/housw/conda_envs.git
```

* To get update from this repository:

```
git pull https://github.com/housw/conda_envs.git
```

* To create your conda env from yaml files in this repository:

```
conda update --all
conda env create --name ${ENV_NAME} --file ${YAML_FILE}
``` 

* To back up your own conda env: 

```
./backup_conda_env.sh
```
