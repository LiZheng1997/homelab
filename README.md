# Homelab

This is a summary of my homelab servers. I want to self-host some of my own services or applications online. For instance, My NAS services, JupyterLab, Personal Blog, Gitlab, Pihole, OpenWrt, Coderserver etc.

*Note: This repo only displays for fast visiting my own services, so I will merely display some public visit websites, but no private internal services. Dashboards will be divided into two parts, one is for public visiting, another is for private visiting.*

---
## Public Dashboard
I make a home page based on a github project named homer, https://github.com/bastienwirtz/homer. This dashboard is easy to deploy through a docker container.
avaliable URL: [homelab.gputek.cn](http://homelab.gputek.cn/)

All Public services are listed bellow:
|        Applications       |  Hosted-servers   |URLs|
| :-----------------------: | :--------------:  |:------------------------------------:|
|      Personal Blogs       |   Ubuntu22-blog   |[www.bluenote.top](https://www.bluenote.top )|
|       Hexo-Blog           |   Ubuntu22-blog   |[www.bluenote.top](https://www.bluenote.top/)|
| Personal Academic Website |      Github       |[neuronsvisioncom](https://neuronsvisioncom/)|
|      Baota-Panel-hexo     |    Ubuntu22-blog  |[Baota-Hexo](https://www.gputek.cn:26459/ad31e4e2)|
|       Coder-Server        | Ubuntu22.04-Prod  |[coder.gputek.cn](http://coder.gputek.cn)|
|       Homer               | Ubuntu22.04-Prod  |[homelab.gputek.cn](http://homelab.gputek.cn/)|
|      1Panel-Main          | Ubuntu22-Test     |[1panel.gputek.cn](http://1panel.gputek.cn/)|
|      JumpServer           | Ubuntu-JumpServer |[jumpserver.gputek.cn](http://jumpserver.gputek.cn/)|
|      1Panel-JumpServer    | Ubuntu-JumpServer |[1Panel-Jumpserver](https://www.gputek.cn:34307/7bea1109d8)|
|       Baota-Panel-Main    |Ubuntu22-Baota-Prod|[baota.gputek.cn](http://baota.gputek.cn/)|
|       Calibre             |Synology-NAS       |[Calibre](http://www.synotech.top:8888/)|
|      Harbor               |    Synology-NAS   |[Harbor](https://www.synotech.top:4001)|


### Private Dashboard
**Keep secret.** (*Nobody knows except me.*)
avaliable URL: internal URL


All Private services are listed bellow:
|        Applications       |  Hosted-servers       |                  URLs                  |
| :-----------------------: | :--------------:      | :------------------------------------: |
|      JupyterLab-GPU       |    GPU-server         |           ***secret***                 |
|      Nextcloud            |    Ubuntu22-Test      |           ***secret***                 |
|      Center Homelab NAS   |    NAS-QunHui         |           ***secret***                 |
|      Rancher              |    Ubuntu22-Dev       |           ***secret***                 |
|      Istoreos             |    istoreos           |           ***secret***                 |
|      MinIO                |    NAS-QunHui         |           ***secret***                 |
|      CVAT                 |    Synology-NAS       |           ***secret***                 |
|      Istoreos             |    istoreos           |           ***secret***                 |
|      Shanghai-NAS         |    Synology-NAS       |           ***secret***                 |
|      Harbor               |    Synology-NAS       |           ***secret***                 |
|      LLama                |    Supermicro         |***secret***                            |

## Logs
This logs are used as backup notes for maintenance.
### DONE
- [x] Test if all public services are avaliable
- [x] Add a istoreos server
- [x] Add a minio OSS server
- [x] Delete previous openwrt VM

### TODO
- [ ] Deploy CVAT on NAS-Qunhui for testing.
- [ ] Change CVAT from Shanghai to center homelab
- [ ] Connect CVAT with MinIO
- [ ] Transfer some datasets to the MinIO OSS data pool.
- [ ] Change the DNS supplier to cloudflare or others with HTTPS
- [ ] Apply CDN to some services after last step, in order to speed up websites loading effect.





