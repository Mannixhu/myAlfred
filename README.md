# myAlfred

个人Roam Research流程图方案: ProcessOn的Alfred workflow
- 总的方案
    - 1. [[ProcessOn]]画流程图
    - 2. [[Alfred]]快速格式化ProcessOn的流程图链接 
- 使用步骤
    - 1. 下载安装对应Alfred workflow: 文件[链接](https://github.com/Mannixhu/myAlfred)
    - 2. 打开ProcessOn网站, 新建流程图
    - 3. 在流程图页面 Option+F 触发Alfred脚本格式化流程图url到剪切板
    - 4. 粘贴到Roam Research
- 运行注意
    - Alfred wrokflow运行环境: 
        - Node.js: /usr/local/bin/node运行JS代码
        - Chrome: Apple script获取Chrome当前网页url
    - Alfred导入后设置下触发的快捷键
    - 说明: 第一次写Alfred workflow, 个人自用没问题, 兼容性待完善
