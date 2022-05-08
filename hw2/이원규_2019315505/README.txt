Environment
	Os: windows10
	cpu: ryzen5 5600x
	gpu: GTX3060ti
	ram:32GB

Prerequisite
	Anaconda: conda 4.10.3
	Python: 3.7
	Pytorch: 1.11.0
	Cuda: 11.3.
	matplotlib: 3.5.1
	jupyter              1.0.0
	jupyter-client       7.2.2
	jupyter-console      6.4.3
	jupyter-core         4.10.0
	jupyterlab-pygments  0.1.2
	jupyterlab-widgets   1.0.0

	

Files
	hw2.ipynb :  source code.
	model1.pt : save file of m1
	model2.pt :            of m2
	model3.pt :            of m3

Usage
	model(번호).pt 파일 load 방법.
	" model = torch.load('model(번호).pt') " 코드를 추가한 뒤 실행시키면 됩니다.
