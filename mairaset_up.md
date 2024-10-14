First install necessary channels

```shell
conda config --add channels conda-forge
```
--
```shell
jovyan@ostorozhno-zlaya-sobaka-0:~$ conda config --add channels nodefaults
```
--
```shell
jovyan@ostorozhno-zlaya-sobaka-0:~$ conda config --show channels
```
--
Install the env with only pytorch in it
```shell
conda create -n Maira2 python=3.10.12 pytorch::pytorch pytorch::pytorch-cuda=12.1 -c pytorch -c nvidia
```
--
Install latest transformers

```shell
pip install git+https://github.com/huggingface/transformers.git@main
```

Install kernel
```shell
conda install ipykernel
python3 -m ipykernel install --user --name Maira2 --display-name "Maira2"
```

To install matplotlib
```shell
```

