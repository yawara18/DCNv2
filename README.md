https://github.com/CharlesShang/DCNv2/pull/92#issuecomment-801983581

Finally build successfully!!!
clone the code from this version https://github.com/lbin/DCNv2/tree/pytorch_1.7
and replace all the floor(...) to floorf(...),
ceil(...) to ceilf(...),
round(...) to roundf(...)

```
cd CV_yolact/external/DCNv2
python setup.py build develop 
```
