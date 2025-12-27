women-safety-demo/
├── index.html        # 主页面
├── style.css         # 页面样式
├── script.js         # JS逻辑（图片上传、展示报告）
├── assets/
│   └── icon.png      # 可选 App 图标
└── README.md
<!DOCTYPE html>
<html lang="zh-CN">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>女性居住安全检测 Demo</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <h1>女性居住安全检测</h1>

  <label for="photoInput">上传房间照片：</label>
  <input type="file" id="photoInput">

  <button id="analyzeBtn">开始安全检测</button>

  <div id="result">
    <p>⚠ 可疑摄像头：中风险</p>
    <p>⚠ 双面镜风险：低风险</p>
    <p>⚠ 门锁安全：中风险</p>
