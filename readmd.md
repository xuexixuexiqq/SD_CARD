
progen命令：
1、初始化
	progen init -p sd_card -tar stm32f103rb

2、生成工程
	progen generate -f projects.yaml -p sd_card -t uvision5
	progen generate -f projects.yaml -p sd_card -t iar-arm
	progen generate -f projects.yaml -p sd_card -t make_gcc_arm