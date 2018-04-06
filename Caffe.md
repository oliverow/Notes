### Differences between deploy.prototxt, solver.prototxt, and train.prototxt
https://ceciliavision.wordpress.com/2016/02/29/caffe-what-files-do-you-need-to-train-your-own-network/

### cannot find module caffe when import caffe
export PYTHONPATH=$CAFFE_ROOT/python

### Generating LMDB occpies all RAM
add writemap=True to lmdb.open()
