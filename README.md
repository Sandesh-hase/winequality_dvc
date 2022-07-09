Create env

```bash
conda create -n wineq python==3.7 -y
```
```bash
conda activate wineq
```

```bash
create req.txt file
```


install requirements

```bash
pip install -r requirements.txt
```

Download the data

https://www.kaggle.com/datasets/rajyellow46/wine-quality?resource=download

```bash
git init
```

```bash
dvc init
```
```bash
dvc add data_given/winequality.csv
```
```bash
git add .
```
```bash
git commit - "first commit"
```
```bash
gt remote add origin https://gitub.com/Sandesh-hase/winequality_dvc.git
git branch -M main
git push origin main
```



