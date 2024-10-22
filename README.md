# Ansible playbook to install Virtualbox and Vagrant

![](https://i.imgur.com/waxVImv.png)
### [View all Roadmaps](https://github.com/nholuongut/all-roadmaps) &nbsp;&middot;&nbsp; [Best Practices](https://github.com/nholuongut/all-roadmaps/blob/main/public/best-practices/) &nbsp;&middot;&nbsp; [Questions](https://www.linkedin.com/in/nholuong/)
<br/>


## Variables

| Name                       | Default Value | Description                                                 |
| -------------------------- | ------------- | ----------------------------------------------------------- |
| virtualbox_version         | `5.1`         | Sets the version number which should be installed           |
| virtualbox_apt_key_url     | ...           | The url of the VB apt key                                   |
| virtualbox_apt_key_url_old | ...           | The url of the VB apt key for older OS's                    |
| virtualbox_apt_repo_url    | ...           | The url of the VB repository                                |
| virtualbox_users           | `[]`          | An Array of usernames which should be added to the VB-Group |
| vagrant_version            | `1.9.8`       | Sets the version number which should be installed           |
| vagrant_deb_url            | ...           | The url to download the debian package                      |
| vagrant_deb_sha_url        | ...           | The url to download the sha256 of the debain package        |

## Example Playbook
```YAML
- hosts: localhost
  roles:
    - nholuong.install-virtualbox-vagrant
```

# 🚀 I'm are always open to your feedback.  Please contact as bellow information:
### [Contact ]
* [Name: nho Luong]
* [Skype](luongutnho_skype)
* [Github](https://github.com/nholuongut/)
* [Linkedin](https://www.linkedin.com/in/nholuong/)
* [Email Address](luongutnho@hotmail.com)

![](https://i.imgur.com/waxVImv.png)
![](Donate.png)
[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/nholuong)

# License
* Nho Luong (c). All Rights Reserved.🌟
