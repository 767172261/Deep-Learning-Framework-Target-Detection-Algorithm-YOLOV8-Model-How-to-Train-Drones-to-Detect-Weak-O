1![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/e12fe7ab71f54347b31de228cda9e61b.png)
**数据集文字描述：**

10类无人机弱小物体检测数据集

用于物体检测任务。它用于弱小物体的检测和无人机检查领域以及地理空间研究。

该数据集包含 844 幅图像，其中有 18334 个标记对象，属于 10 个不同类别，包括建筑物、预制房屋、水井和其他：电缆塔、车辆、船舶、采石场、养殖网笼、水池和山体滑坡。

数据集中的图像带有边界框标注。所有图像均已标注（即带有标注）。数据集中没有预定义的训练/验证/测试集划分。该数据集由中国地质大学于 2022 年发布。
以下是您提供的 **10类无人机弱小物体检测数据集** 的详细表格描述，适用于目标检测、无人机遥感分析、地理空间研究及灾害监测等领域的科研与应用。

---

### 📊 10类无人机弱小物体检测数据集 描述表格

| **项目** | **详细信息** |
|---------|-------------|
| **数据集名称** | 10类无人机弱小物体检测数据集（UAV Small Object Detection Dataset） |
| **发布单位** | 中国地质大学（China University of Geosciences, CUG） |
| **发布时间** | 2022年 |
| **图像总数** | **844 张** |
| **标注对象总数** | **18,334 个** |
| **平均对象密度** | 约 **21.7 个/图**（高密度标注） |
| **任务类型** | 多类别目标检测（Object Detection） |
| **应用场景** | - 无人机遥感检测<br>- 弱小目标识别<br>- 地理空间信息提取<br>- 地质灾害监测（如滑坡）<br>- 基础设施巡检 |
| **图像来源** | 无人机航拍影像（低空遥感），覆盖城市、乡村、山区、水域等多种地形 |
| **图像特点** | - 高分辨率<br>- 小目标为主（目标像素占比小，检测难度高）<br>- 复杂背景干扰多 |
| **标注方式** | 边界框标注（Bounding Box） |
| **标注完整性** | 所有图像均已标注，无未标注图像 |
| **标注格式** | 通用边界框格式（可转换为 YOLO、COCO、Pascal VOC 等） |
| **训练/验证/测试划分** | **无预定义划分**，需用户自行按比例分割（如 70%/15%/15% 或 80%/10%/10%） |

---

### 🧩 类别信息明细表

| **类别ID** | **类别名称（中文）** | **类别名称（英文）** | **说明与典型特征** |
|-----------|------------------------|------------------------|----------------------|
| 1 | 建筑物 | Building | 固定结构的房屋或公共设施，形状规则，顶部清晰可见 |
| 2 | 预制房屋 | Prefabricated House | 工地临时板房、集装箱式房屋，颜色单一，排列整齐 |
| 3 | 水井 | Well | 圆形或方形小结构，常位于农田或村庄附近，尺寸较小 |
| 4 | 电缆塔 | Cable Tower | 高耸金属结构，呈网格状，用于输电线路支撑 |
| 5 | 车辆 | Vehicle | 包括汽车、卡车等地面交通工具，通常停放在道路或停车场 |
| 6 | 船舶 | Ship / Boat | 水域中的船只，大小不一，常见于河流、湖泊或港口 |
| 7 | 采石场 | Quarry | 开采痕迹明显的裸露岩石区域，形状不规则，纹理粗糙 |
| 8 | 养殖网笼 | Aquaculture Net Cage | 水面漂浮的圆形或多边形养殖设施，成片分布于湖泊或近海 |
| 9 | 水池 | Pond / Reservoir | 人工或自然水体，呈封闭几何形状，反射性强 |
| 10 | 山体滑坡 | Landslide | 地质灾害区域，表现为土体位移、植被破坏、裸露坡面等 |

> ✅ 总类别数：**10 类**


![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/31b0c1c2fac74e25abbd3bafa88195b0.png)
1
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/a3678db1ccca468092b7bf6893f0094d.png)
1
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/0fadcc1078574dbc83d0dd699fdfe6cf.png)
1
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/10b20a61b90344c788a00938ab3a8230.png)
1
：

- 无人机巡检
- 弱小目标检测（small object detection）
- 地理信息系统（GIS）分析
- 灾害监测（如山体滑坡）
- 基础设施监控

---

## ✅ 一、数据集信息总结

| 项目 | 内容 |
|------|------|
| 图像数量 | 844 张 |
| 标注对象总数 | 18,334 个 |
| 类别数量 | 10 类 |
| 标注格式 | YOLO 格式（`.txt`）或 COCO？（默认按 YOLO 处理） |
| 发布单位 | 中国地质大学（CUG） |
| 应用领域 | 遥感、地理空间、无人机巡检、灾害识别 |

### 📌 10 类目标（建议英文命名）

| ID | 中文类别 | 推荐英文名 | 说明 |
|----|----------|------------|------|
| 0 | 建筑物 | building | 固定结构 |
| 1 | 预制房屋 | prefab_house | 可移动房屋 |
| 2 | 水井 | well | 小型圆形结构 |
| 3 | 电缆塔 | power_tower | 高耸线性结构 |
| 4 | 车辆 | vehicle | 小型移动目标 |
| 5 | 船舶 | ship | 水面目标 |
| 6 | 采石场 | quarry | 大型地表开挖区域 |
| 7 | 养殖网笼 | fish_cage | 水面养殖结构 |
| 8 | 水池 | pond | 人工或自然水体 |
| 9 | 山体滑坡 | landslide | 灾害区域，不规则形状 |

> 📝 **注意**：该数据集未预划分训练/验证/测试集，需自行划分。

---

## ✅ 二、目录结构建议

```
uav_small_objects/
├── images/
│   ├── train/
│   ├── val/
│   └── test/
├── labels/
│   ├── train/
│   ├── val/
│   └── test/
├── data.yaml
└── split_dataset.py
```

---

## ✅ 三、创建 `data.yaml`

```yaml
# data.yaml
train: ./uav_small_objects/images/train
val: ./uav_small_objects/images/val
test: ./uav_small_objects/images/test

# 类别数量
nc: 10

# 类别名称（英文）
names:
  - building
  - prefab_house
  - well
  - power_tower
  - vehicle
  - ship
  - quarry
  - fish_cage
  - pond
  - landslide
```

---

## ✅ 四、自动划分数据集脚本（8:1:1）

```python
# split_dataset.py
import os
import random
import shutil
from pathlib import Path

def split_dataset(image_dir, label_dir, output_dir, train_ratio=0.8, val_ratio=0.1, test_ratio=0.1):
    assert train_ratio + val_ratio + test_ratio == 1.0

    image_dir = Path(image_dir)
    label_dir = Path(label_dir)
    output_dir = Path(output_dir)

    # 支持常见图像格式
    images = list(image_dir.glob("*.jpg")) + \
             list(image_dir.glob("*.png")) + \
             list(image_dir.glob("*.jpeg")) + \
             list(image_dir.glob("*.tif"))

    random.seed(42)  # 固定随机种子
    random.shuffle(images)

    n = len(images)
    train_size = int(n * train_ratio)
    val_size = int(n * val_ratio)

    train_images = images[:train_size]
    val_images = images[train_size:train_size + val_size]
    test_images = images[train_size + val_size:]

    # 创建目录
    for folder in ['images/train', 'images/val', 'images/test',
                   'labels/train', 'labels/val', 'labels/test']:
        (output_dir / folder).mkdir(parents=True, exist_ok=True)

    # 复制图像和标签
    def copy_files(img_list, phase):
        for img in img_list:
            shutil.copy(img, output_dir / f'images/{phase}' / img.name)
            label = label_dir / f"{img.stem}.txt"
            if label.exists():
                shutil.copy(label, output_dir / f'labels/{phase}' / label.name)

    copy_files(train_images, 'train')
    copy_files(val_images, 'val')
    copy_files(test_images, 'test')

    print(f"✅ 数据集划分完成！")
    print(f"   训练集: {len(train_images)} 张")
    print(f"   验证集: {len(val_images)} 张")
    print(f"   测试集: {len(test_images)} 张")

# 使用（请替换路径）
split_dataset(
    image_dir='raw/images',
    label_dir='raw/labels',
    output_dir='uav_small_objects'
)
```

---

## ✅ 五、环境准备

```bash
# 创建环境
conda create -n uav_detect python=3.9
conda activate uav_detect

# 安装 PyTorch（CUDA）
pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu118

# 安装 YOLOv8
pip install ultralytics opencv-python numpy matplotlib tqdm

# 验证
python -c "import torch; print(torch.cuda.is_available())"
```

---

## ✅ 六、YOLOv8 训练代码（`train.py`）

```python
# train.py
from ultralytics import YOLO
import torch

# 设置设备
device = 'cuda' if torch.cuda.is_available() else 'cpu'
print(f"Using device: {device}")

# 加载模型（推荐使用 yolov8m 或 yolov8l）
model = YOLO('yolov8m.pt')  # 可换为 yolov8l.pt 提升精度

# 开始训练
results = model.train(
    data='uav_small_objects/data.yaml',   # 数据配置
    imgsz=640,                            # 输入尺寸（可尝试 800）
    epochs=300,                           # 弱小目标需充分训练
    batch=16,                             # 显存不足可调小
    name='yolov8m_uav_small',
    project='runs/uav',
    device=device,
    workers=8,
    optimizer='AdamW',
    lr0=0.001,
    weight_decay=0.0005,
    patience=60,                          # 早停
    save_period=10,
    augment=True,
    mosaic=1.0,
    mixup=0.1,
    copy_paste=0.3,                       # 关键：增强小目标
    close_mosaic=50,
    amp=True,                             # 混合精度
    val=True,
    plots=True                            # 生成混淆矩阵等图
)

print("✅ 无人机弱小物体检测模型训练完成！")
```

---

## ✅ 七、关键训练技巧（针对“弱小物体”）

| 技巧 | 说明 |
|------|------|
| `copy_paste: 0.3` | 将小目标复制粘贴到新位置，增强小目标学习 |
| `imgsz: 800` | 提高分辨率，让小目标更清晰（需显存支持） |
| `mosaic: 1.0` | 拼接4图，增加上下文信息 |
| `AdamW` | 比SGD更稳定，适合复杂遥感图像 |
| `epochs: 300` | 数据量小，需充分训练 |

> 💡 **建议**：如果显存允许，使用 `imgsz=800` 和 `yolov8l` 模型。

---

## ✅ 八、模型验证与测试

```python
# val.py
from ultralytics import YOLO

model = YOLO('runs/uav/yolov8m_uav_small/weights/best.pt')

# 验证
metrics = model.val(
    data='uav_small_objects/data.yaml',
    batch=16,
    imgsz=640,
    device='cuda',
    project='val_results',
    name='uav_val',
    save_json=True
)

print(f"mAP@0.5:       {metrics.box.map:.4f}")
print(f"mAP@0.5:0.95:  {metrics.box.map50_95:.4f}")
print(f"Precision:     {metrics.box.precision:.4f}")
print(f"Recall:        {metrics.box.recall:.4f}")
print(f"FPS:           {metrics.speed['inference']:.2f}")
```

---

## ✅ 九、推理代码

### 1. 单图检测

```python
results = model.predict(
    source='uav_image.jpg',
    conf=0.4,
    iou=0.5,
    show=True,
    save=True,
    project='inference_output',
    name='demo'
)
```

### 2. 视频检测

```python
model.predict(
    source='drone_video.mp4',
    conf=0.4,
    show=True,
    save=True
)
```

### 3. 批量预测

```python
model.predict(
    source='uav_small_objects/images/test',
    save=True,
    project='inference_output',
    name='test_results'
)
```

---

## ✅ 十、模型导出（用于部署）

```python
# 导出为 ONNX
model.export(format='onnx', dynamic=True, opset=13)

# 导出为 TensorRT（NVIDIA）
# model.export(format='engine', device=0)

# 导出为 TorchScript
model.export(format='torchscript')
```

---

## ✅ 十一、可视化分析

- 查看 `runs/uav/yolov8m_uav_small/results.png` → mAP 曲线
- 查看 `val_batch*.jpg` → 检测效果图
- 启动 TensorBoard：

```bash
tensorboard --logdir runs/uav
```

---

## ✅ 十二、应用场景扩展

| 场景 | 应用 |
|------|------|
| 🛰️ 无人机巡检 | 自动识别基础设施 |
| 🌋 灾害监测 | 山体滑坡、水灾识别 |
| 🏗️ 城市规划 | 建筑物、采石场统计 |
| 🐟 水产养殖 | 养殖网笼监控 |
| 🚗 交通监控 | 车辆、船舶统计 |

---

## ✅ 十三、总结

| 步骤 | 工具 |
|------|------|
| 🧰 数据 | 手动划分 + copy_paste 增强 |
| 🏃‍♂️ 训练 | YOLOv8 + AdamW + 高分辨率 |
| 🔍 检测 | 小目标优化策略 |
| 📊 评估 | mAP@0.5, mAP@0.5:0.95 |
| 🚀 部署 | ONNX / TensorRT |

---

🎁 **可扩展功能**：
- 添加 **GIS 坐标映射**（结合 GPS 信息）
- 构建 **Web 地图平台**（Leaflet + Flask）
- 实现 **变化检测**（对比多期图像）
- 使用 **红外/多光谱图像** 扩展模态

需要我为你生成：
- 🖼️ 小目标密度热力图
- 🌐 Web 可视化系统
- 📈 模型对比实验脚本（YOLOv5 vs YOLOv8）
- 📊 类别分布统计与可视化

欢迎继续提问！祝你构建出强大的 **无人机弱小目标检测系统**！🚁🔍🌍
