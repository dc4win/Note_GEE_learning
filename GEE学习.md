# GEE中文教程 By 吴秋生

## 1、geemap

![image-20240102210804279](assets/image-20240102210804279.png)

![image-20240103072801553](assets/image-20240103072801553.png)

![image-20240103072910769](assets/image-20240103072910769.png)

![image-20240103170110338](assets/image-20240103170110338.png)

![image-20240103072948406](assets/image-20240103072948406.png)

![image-20240105214906456](assets/image-20240105214906456.png)

***问题：***加载geemap时出现”Error displaying widget: model not found“

***解决方法：***

```shell
conda activate env # 进入目标虚拟环境
jupyter labextension install @jupyter-widgets/jupyterlab-manager jupyter-leaflet #重新安装jupyterlab manager和leaflet插件
```