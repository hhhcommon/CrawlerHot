### 说明
我的博客热点展示：https://www.panglb.top/hot/
```shell
├── crawler.py  所有爬取内容的函数
├── helper.py   
├── LICENSE
├── README.md
├── requments.txt  环境依赖包
├── result  保存爬取结果的文件夹
└── web  前端
    ├── hot.html  显示页面
    └── layui  依赖
├── run.py  运行入口
└── settings.py  配置文件
```

- 目前只写了以下热点信息的爬取

  - 知乎热榜
  - V2EX
  - GitHub
  - 新浪微博
  - 天涯
  - 贴吧
  - 豆瓣
  - 云音乐

- 环境

  - python3

- 运行

  - 下载

    ```shell
     git clone https://github.com/pangxiaobin/CrawlerHot.git
     cd CrawlerHot
    ```

  - 安装依赖

    ```shell
    pip install -r requments.txt
    ```

  - 运行

    ```shell
    python run.py
    ```
 - 查看前端展示效果
 - 浏览器打开hot.html

### 新增内容
- 增加定时爬取任务
- 增加前端页面显示
### 效果



