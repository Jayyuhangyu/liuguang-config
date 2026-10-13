# liuguang-config

流光（Liuguang）默认订阅配置仓库。

- `box.json`：默认订阅（豆瓣[py] 首页推荐 + 4 个 Apple CMS 采集站点播/搜索通道）
- `py/douban.py`：豆瓣爬虫修复版（基于社区版本修补：补齐 tv_domestic / tv_american / tv_japanese / tv_korean / show_domestic / show_foreign 六个分类分支，热门类目正确响应分类筛选参数）

## 使用

TVBox 类客户端填入订阅地址（jsDelivr 直链，国内可达性较好）：

```
https://cdn.jsdelivr.net/gh/Jayyuhangyu/liuguang-config@main/box.json
```

或直连 GitHub raw：

```
https://raw.githubusercontent.com/Jayyuhangyu/liuguang-config/main/box.json
```

## 声明

本仓库不存储、不制作任何视频内容，仅提供第三方公开接口的聚合配置；内容的合法性由对应数据源负责。douban.py 系社区流传版本的修补衍生，仅供个人学习使用。
