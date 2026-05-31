VFI 指令：
python main_test_vrt.py --task 009_VRT_videofi_Vimeo_4frames --folder_lq testsets/Vid4/BIx4 --folder_gt testsets/Vid4/BIx4 --save_result --tile 30 64 64 --num_workers 0
VFR 指令：
python main_test_vrt.py --task 003_VRT_videosr_bi_Vimeo_7frames --folder_lq testsets/Vid4/BIx4 --folder_gt testsets/Vid4/GT/ --tile 20 64 64 --num_workers 0 --save_result    


data/dataset_video_test.py用于准备数据集
model_zoo用于存放预训练权重文件
testsets/用于存放下载好的数据集
utils是工具包
