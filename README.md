# End-to-End-Object-Detection

## Workflows

- constants
- config_entity
- artifact_entity
- components
- pipeline

## Project Configuration
```bash
#install aws cli from the following link
https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html
```
```bash
#Configure aws crediential (secret key & access key)
aws configure
```
```bash
#Create a s3 bucket for model pusher. name is mentioned in the constant
```

## How to run:

```bash
    git clone https://github.com/nhanth301/End-to-End-Object-Detection.git
```

```bash
    cd End-to-End-Object-Detection
```

```bash
    conda create -p env python=3.7 -y
```

```bash
    conda activate env
```

```bash
    pip install -r requirements.txt
```

```bash
    python3 app.py
```