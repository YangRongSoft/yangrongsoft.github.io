### DESCRIPTION

This template implements the Maverick Form on the website. 

### INSTRUCTIONS
The Website loads the form with JavaScript.

First, Create a form on Maverick and you can see the Form HTML on the right top. Click Automatic and remember the form id. Or you can get it on the form list page.

In the Form ID field, add your Maverick Form ID.

Insert the GTM code into website and it can be automatically display the form.

### RELEASE NOTES

| Date  | Changeset |
| --- | --- |
| 6 January 2021 | Initial release. |



| 命令行名字 | 说明 | Cron | 代码调用 |
| --- | --- | --- | --- |
| `larabbs:calculate-active-user` |  生成活跃用户 | 一小时运行一次 | 无 |
| `larabbs:sync-user-actived-at` | 从 Redis 中同步最后登录时间到数据库中 | 每天早上 0 点准时 | 无 |
