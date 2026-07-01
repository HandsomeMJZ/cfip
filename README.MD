# 🌐 Cloudflare 优选 IP


**本次更新**: 2026-07-01 15:02:34
> **✨ 新增节点**: 北京电信优选    
> **测试环境**: 中国四川联通 / 北京电信    
> **更新频率**: 每 45 分钟自动更新    

---

## 🔗 订阅链接

> **⚠️ 注意：** 现使用R2存储的新订阅链接,更快更推荐!

| 线路分类 | 高速优选 (推荐) | 所有可用 (适合二次测速) |
| --- | --- | --- |
| **四川联通** | [https://cf.junzhen.qzz.io/best_ips.txt](https://cf.junzhen.qzz.io/best_ips.txt) | [https://cf.junzhen.qzz.io/full_ips.txt](https://cf.junzhen.qzz.io/full_ips.txt) |
| **北京电信 ✨** | [https://cf.junzhen.qzz.io/best_ips_bj.txt](https://cf.junzhen.qzz.io/best_ips_bj.txt) | [https://cf.junzhen.qzz.io/full_ips_bj.txt](https://cf.junzhen.qzz.io/full_ips_bj.txt) |

### 💡 链接区别说明

* **高速优选**: 已通过自动化测速，直接筛选出的最优节点，**强烈推荐小白用户直接使用**。
* **所有可用**: 筛选出各地区延迟最低的前 10 个节点，不保证最终吞吐速度，适合有进阶需求的用户二次筛选。

---

## 🛠️ 同款工具

如果你希望在本地自主测速，请访问：

* **仓库地址**: [HandsomeMJZ/cfip-tools](https://github.com/HandsomeMJZ/cfip-tools)
* **提示**: 仓库提供已编译好的 Windows 版本，开箱即用。

---

## 📖 使用说明

### 1. 适用范围

已有大量用户反馈，该订阅对绝大多数地区的**电信**与**联通**网络具有良好适配性。若你的网络环境不匹配，建议使用上述工具自行测速。

### 2. 自动化配置

* **本地优选**: 若无需上传同步，直接运行对应系统的 start 脚本即可。
* **自动上传**: 若需将结果同步至 GitHub，请编辑对应系统的 push 脚本，配置好你的 Token 与仓库地址。

### 3. EdgeTunnel 部署流程

1. 复制上述对应的**订阅链接**。
2. 进入 **EdgeTunnel 后台**。
3. 创建优选订阅，模式选择 **“优选订阅模式 - 自定义”**。
4. 在 **“订阅接口 / API / URL”** 栏中粘贴链接。
5. 点击 **“验证可用性”**，随后选择 **“追加 API”**。
6. 保存并重新订阅即可。
