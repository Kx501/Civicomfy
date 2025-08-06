# Civicomfy - ComfyUI Civitai Downloader Extension

一个用于ComfyUI的Civitai模型下载器扩展，支持从Civitai.com下载各种模型。

Fork from [MoonGoblinDev/Civicomfy](https://github.com/MoonGoblinDev/Civicomfy)

## 功能特性

### 最新更新
- ✅ **支持相对路径的自定义文件名**: 现在可以在自定义文件名中使用相对路径，例如 `subfolder/model_name.safetensors`
- ✅ **完整的中文界面**: 已汉化所有用户界面元素
- ✅ **文件扩展名处理**: 自动处理文件扩展名并创建子目录

## 安装

Git clone
```bash
cd ComfyUI/custom_nodes
git clone https://github.com/MoonGoblinDev/Civicomfy.git
```

手动安装：
1. 将整个文件夹复制到ComfyUI的`custom_nodes`目录
2. 重启ComfyUI
3. 在ComfyUI界面中找到"Civicomfy"按钮

## 使用方法

### 自定义文件名功能
现在支持在自定义文件名中使用相对路径：
- `my_model.safetensors` - 保存在默认目录
- `anime/my_model.safetensors` - 保存在anime子目录
- `characters/waifu/model.safetensors` - 创建多层子目录

## 截图

<img width="911" alt="Screenshot 2025-04-08 at 11 24 40" src="https://github.com/user-attachments/assets/b9be0c32-729d-490e-be61-2dc072cd9b15" />
<img width="911" alt="Screenshot 2025-04-08 at 11 23 17" src="https://github.com/user-attachments/assets/cb747c22-afd0-4baf-a9a2-39c70fb11e46" />
<img width="911" alt="Screenshot 2025-04-08 at 11 25 15" src="https://github.com/user-attachments/assets/02b6d841-a0fa-484c-91a4-4095a7554c3f" />
<img width="911" alt="Screenshot 2025-04-08 at 11 25 24" src="https://github.com/user-attachments/assets/20fcfcb5-3345-4a72-89fe-ee9c50626ebc" />

## 许可证

MIT License
