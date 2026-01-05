#!/usr/bin/env sh
# Compute the mean image from the imagenet training lmdb
# N.B. this is available in data/ilsvrc12

EXAMPLE=/home/visionadmin/deep-residual-networks-master/examples
DATA=/home/visionadmin/deep-residual-networks-master/data
TOOLS=~/code/caffe-1.0/build/tools

$TOOLS/compute_image_mean $EXAMPLE/residual_train_lmdb \
  $DATA/residual_mean.binaryproto

echo "Done."
