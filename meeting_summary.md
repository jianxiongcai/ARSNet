## Meeting 1 
1. Faster-RCNN speed:
	1) Feature map -> 1*1 convolution
	2) Share 3*3 Conv  (jinlei)
	3) Lower the number Proposal Number (Evaluation, parameter-tuning)

2. Pre-clustering

3. Change the Pooling (Change the pooling), ROI w.r.t Aspect Ratio

5. Coco Test

6. GPU

Others on the slide

Coco Aspect Ratio Analysis + Test (Val-Test?)

Paper

Related Work
	Better Proposal

Experiment


## Meeting 2
Done:
	+ COCO datatset aspect ratio analysis

- Filter second-step NMS by scores

- ResNet

- Related Work (Pang)

- coco Test (jianxiong)

- Alibation Test Result (li ruijian)

- Trace where does the stuff come from

Idea:
	Rotated Bottle =  Aspect Ratio + classification (maybe rotate bottle)

## Meeting 3 
Summary:
	Related Work: Scale + Template => FPN + SNIP
	Where does valid proposal comes from
	Alibation Experiemnt => Check if we got all experiment
	Network Changes : Sharing features + 1 by 1 conv => testing
	COCO Test => Training undergoing

	Weights => To folder weights

Ongoing:
	Related Work (Pang Anqi) -> Starting Writing
	Paper (Ruijian Li)
	Experiment (Jianxiong Cai + Lei Jin)
	COCO Test (Jianxiong Cai)
	
Q:
	ResNet 



paper of asrNMS:http://www.mdpi.com/2072-4292/9/12/1312

