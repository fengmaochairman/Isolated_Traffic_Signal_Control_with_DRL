# Isolated_Traffic_Signal_Control_with_DRL
A comparison of islated traffic signal control with DRL algorithms

### Usage ###

The repository's high-level structure is:
 
    ├── main.py (模型训练、测试框架) 
    ├── agents  (智能体模块)               
        └── models.py  (策略模型)
        └── experience_buffer.py  (经验回放池)
    ├── envs  (环境模块)
        └── envs.py(envs_fix.py) (环境模型)
        └── tls.py  (信号灯模型)
    ├── libs  (预处理、参数模块)           
        └── hyperparameters.py  (参数模型)
        └── utils.py  (环境配置预处理)
    ├── networks (路网、流量数据)           
        └── build_grid_file.py  (生成路网、交通流量文件)
    ├── .tmp  (实验实时记录)     
    ├── outputs  (实验结果处理模块)        
        └── models  (实验模型)
        └── results  (实验结果)
