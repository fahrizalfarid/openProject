# COVID19 X-RAY Classification

## Getting Started

Assalamualaikum Warahmatullahi Wabarakatuh.

Due to too long working at home and the current unrest, I decided to make the Open Project AI: COVID19 X-RAY Classification. This AI detects COVID 19 based on the results of a lung x-ray scan. The class consists of two namely COVID19 and NORMAL. I hope what I make can be useful for others, and of course it's free :)


### Prerequisites

What things you need to install the software and how to install them

```
sudo apt update && sudo apt upgrade -y
sudo apt install python3-pip -y
```

### Installing Library & Framework

```
pip3 install tensorflow
pip3 install jupyterlab
```

### Download Model from Google Drive

[Model](https://drive.google.com/file/d/1-r8DWQmpfoDW-21N5CEuch1khKB4ZkKs/view?usp=sharing)

```
mv final_model_covid19.h5 model/
```


## Running

Open Terminal or Powershell.

```
jupyter notebook
open predict.ipynb
```

and then

run cell by cell with **CTRL + ENTER**


## Authors

**Muhammad Fahrizal Farid** - *Machine Learning Enthusiast* - [Repo](https://github.com/fahrizalfarid)


