# 工具使用说明

## `mask2labelmeJson.py`使用
* 把`igbt4`的`mask`数据转换为`labelme`格式的`json`格式
```shell
python3 mask2labelmeJson.py --mask_root="/home/e00130/workspace/igbt/training/zjw/igbt_defect_seg/igbt4_pred/2022_06_28_11_27_53/masks" \
--output_root="/home/e00130/workspace/igbt/training/zjw/igbt_defect_seg/igbt4_pred/2022_06_28_11_27_53/labelme_json"
```
* 把`pin4`的`mask`数据转换为`labelme`格式的`json`格式
```shell
python3 mask2labelmeJson.py --mask_root="/home/e00130/workspace/igbt/training/zjw/igbt_defect_seg/pin4_pred/2022_06_28_11_29_30/masks" \
--output_root="/home/e00130/workspace/igbt/training/zjw/igbt_defect_seg/pin4_pred/2022_06_28_11_29_30/labelme_json"
```