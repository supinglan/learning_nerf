# My-MDM

An unofficial PyTorch implementation of the paper [**"Human Motion Diffusion Model"**](https://arxiv.org/abs/2209.14916).

#### **1. Setup environment**



#### 2. Download Dependencies

##### **Text to Motion**

```shell
bash prepare/download_smpl_files.sh
bash prepare/download_glove.sh
bash prepare/download_t2m_evaluators.sh
```

##### **Action to Motion**

```shell
bash prepare/download_smpl_files.sh
bash prepare/download_recognition_models.sh
```

#### 3. Download datasets

##### **Text to Motion**

**HumanML3D** - Follow the instructions in [HumanML3D](https://github.com/EricGuo5513/HumanML3D.git), then copy the result dataset to our repository:

```
cp -r ../HumanML3D/HumanML3D ./dataset/HumanML3D
```

**KIT** - Download from [HumanML3D](https://github.com/EricGuo5513/HumanML3D.git) (no processing needed this time) and the place result in `./dataset/KIT-ML`

##### **Action to Motion**

```bash
bash prepare/a2m/download_datasets.sh
```

