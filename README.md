# RL-Final-REDQ
Course project: Reinforcement Learning


This report investigated the performance of REDQ Chen et al. (2021) with five different trained variants on two MoJoCo (Todorov et al., 2012; Brockman et al., 2016) environments: HalfCheetah and Hopper. Six REDQ variants are trained to aim at investigating the following aspects of model training: 1)Training data steps 2)Action noise in evaluation phrase 3)Network structure - deeper network & more parameters
## Environment & Dependency
To setup the MoJoCo environment and related denpendencies please reffer to this github page: [https://github.com/YumengggZhang/Reinforcement-Learning-Final-Project](https://github.com/YumengggZhang/Reinforcement-Learning-Final-Project)

## How to Run
- run experiment/redq_sac_part2 for sequentially training REDQ agent rendering different hyper parameters
- experiment/train_with_save.py for training REDQ agent and saving checkpoints at epoch 0,100,300 (this can be adjusted)
- experiment/train_redq_sac_reset.py for training REDQ agent and reset the parameters after 150 epochs

## Results and Plots
![readme_pic](./performance.png)
![readme_pic](./Halfcheetah.png)
![readme_pic](./Hopper.png)
