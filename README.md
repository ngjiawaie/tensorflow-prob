# tensorflow-prob

Dataset from https://archive.ics.uci.edu/ml/datasets/Activity+Recognition+from+Single+Chest-Mounted+Accelerometer <br>

Activity recognition using CNN,<br><br>

Current Error facing: InvalidArgumentError (see above for traceback): logits and labels must be same size: logits_size=[1200,7] labels_size=[600,7]
	 [[Node: cost_9/SoftmaxCrossEntropyWithLogits = SoftmaxCrossEntropyWithLogits[T=DT_FLOAT, _device="/job:localhost/replica:0/task:0/cpu:0"](cost_9/Reshape, cost_9/Reshape_1)]]
