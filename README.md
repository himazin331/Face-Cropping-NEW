# Face-Cropping-NEW
An improved version of face cropping that I created before.

[これ](https://github.com/himazin331/Face-Cropping)の改良版。
以前作成したものは、１つの画像に複数個の顔が含まれていても１個しか切り取ることができなかったが、
改良版では顔として認識したもの全てを切り取るようにしました。
その他、修正や機能追加を加えてあります。

## face_cut_v2.py

**Command**  
```
python face_cut_v2.py -d <IMG_DIR> -c <CASCADE>
                                (-o <OUT_PATH> -s <OUT_SIZE> -ch <IMG_CH> -l <Index>)
                                                          
CASCADE   : ./haar_cascade.xml (Default)  
OUT_PATH  : ./result_crop (Default)
OUT_SIZE  : 32 (Default) *Output image size N x N.
IMG_CH    : 1 (Default) * Image Channels
Index     : 1 (Default) *Output image name index. Starting from dataN.jpg when you specify `-l N`.
```
