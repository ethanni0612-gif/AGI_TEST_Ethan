# LLM API Tests

Test scripts for:
- Qwen-Max (text)
- Wen-TTS (speech)
- Wan2.5 (video)

## Setup
```
# 1. 创建虚拟环境（目录名 venv）
$ python3 -m venv venv

# 2. 激活虚拟环境
$ source venv/bin/activate
(venv) $  # 提示符变化，表示已激活

# 3. 在虚拟环境中操作（示例）
(venv) $ pip install requests  # 包被安装到 venv/lib/pythonX.X/site-packages
(venv) $ python -c "import requests; print('OK')"

# 4. 退出虚拟环境
(venv) $ deactivate
$  # 回到系统全局环境
