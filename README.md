# Lightweight-network
总结一些轻量级的网络,包含mobelnet系列,SqueezeNet, ShuffleNet系列,resnet系列

2070s显卡

mobilenet v2
1,3,400,400输入
avg time: 0.004585387229919434

1,3,816,682输入
avg time: 0.006614710807800293

1,3,1224,1024输入
avg time: 0.014484094619750977

1,3,1500,1500输入
avg time: 0.025329343795776366

mobilenetv3 (small)
1,3,400,400输入
avg time: 0.0067782230377197265

1,3,816,682输入
avg time: 0.006809538364410401

1,3,1224,1024输入
avg time: 0.006906617641448975

1,3,2448,2048
avg time: 0.022679887294769288


mobilenetv3 (large)
1,3,400,400输入
avg time: 0.0077113909721374515

1,3,816,682输入
avg time: 0.007752399444580078

1,3,1224,1024输入
avg time: 0.015697271347045898

1,3,1500,1500
avg time: 0.026915117740631104


resnet18
1,3,400,400输入
avg time: 0.002706225872039795

1,3,550,550输入
avg time: 0.00454154634475708

1,3,816,682输入
avg time: 0.007086463451385498

1,3,1224,1024输入
avg time: 0.012701252460479736

1,3,2448,2048输入
avg time: 0.04885279369354248

resnet50
1,3,400,400输入
avg time: 0.007387876510620117

1,3,550, 550输入
avg time: 0.012972342014312745

1,3,816,682输入
avg time: 0.019502767086029053

1,3,1224,1024输入
avg time: 0.0416026759147644


shufflenet v2 (shufflenet_v2_x0_5)
1,3,400,400 
avg time: 0.005986212253570556

1,3,550,550 
avg time: 0.005933603286743164

1,3,816,682输入  
avg time: 0.005825222492218018

1,3,1224,1024输入
avg time: 0.005854468345642089

1,3,2448,2048输入
avg time: 0.010617815017700195


shufflenet v2 (shufflenet_v2_x1_0)
1,3,400,400 
avg time: 0.005870607852935791

1,3,550,550 
avg time: 0.005898384094238282

1,3,816,682输入  
avg time: 0.005956595897674561

1,3,1224,1024输入
avg time: 0.006113113880157471

1,3,2448,2048输入
avg time: 0.020001214027404787

squeezenet (squeezenet1_0)
1,3,400,400 
avg time: 0.0021774859428405763

1,3,550,550 
avg time: 0.003764206409454346

1,3,816,682输入
avg time: 0.006173946380615234

1,3,1224,1024输入
avg time: 0.014607007026672364

1,3,2000,2000
avg time: 0.04851393270492554