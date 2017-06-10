```
     ___    ____  _____  ____
    / _ \  / __ \|  ___||  _  \
   / /_\ \| /  \/| |__  | | | |
   |  _  || |    |  __| | | | |
   | | | || \__/\| |___ | |/ /
   \_| |_/ \____/\____/ |___/

   ACED: AWS Cloud Easy Deploy

```
AWS Cloud Easy Deploy (ACED) is an Amazon Web Services (AWS) EC2 instance generator. Highly opinionated, yet user configurable, ACED automates the provisioning of a secure and lightweight cloud environment that allows for wicked-fast teardowns/rebuilds. As configured, ACED provides a solid platform to serve websites built by static site generators, such as [Hugo](https://gohugo.io), [Hexo](https://hexo.io) and [Jekyll](https://jekyllrb.com). Since ACED is comprised of bash scripts, it can be expanding upon to install the run-time and/or server scripting of your choice to serve dynamic websites and/or web apps.

To read more, see my blog post at [www.DevOpsEtc.com](https://www.DevOpsEtc.com/post/aced-aws-cloud-easy-deploy/)

**Road Map:**
- Install MTA (fail2ban notifications)
- Rotate AWS IAM access_keys
- Rotate EC2 public/private key
- Add IP6Tables rules
- Implement port knocking
- Install openVPN

**PRs welcome, or just fork it (YMMV!)**
