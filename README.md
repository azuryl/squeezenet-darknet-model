# squeezenet-darknet-mode
convert from https://github.com/DeepScale/SqueezeNet/tree/master/SqueezeNet_v1.1

validating on ImageNet 

you should build you image database as 

https://pjreddie.com/darknet/imagenet/

then 

./darknet classifier valid cfg/imgenet1k.data squeezenet.cfg  squeezenet_darknetformat.weights
