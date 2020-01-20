# imagenet_script
imagenet dataset preprocess

Download 
ILSVRC2012_img_test.tar  
ILSVRC2012_img_train.tar  
ILSVRC2012_img_train_t3.tar  
ILSVRC2012_img_val.tar

1.  
mkdir train

mkdir val


2.
tar xvf ILSVRC2012_img_train.tar -C ./train

tar xvf ILSVRC2012_img_val.tar -C ./val


3.
cd train

sh unzip.sh

cd ../val

sh valprep.sh
