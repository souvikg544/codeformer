```
python basicsr/train.py -opt options/VQGAN_512_ds32_nearest_stage1_our.yml
```

```

python -m torch.distributed.launch --nproc_per_node=4 --master_port=4321 basicsr/train.py -opt options/VQGAN_512_ds32_nearest_stage1_our.yml --launcher pytorch
```
