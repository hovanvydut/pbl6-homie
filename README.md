
# Homie - INN Findor System
## Repositories 🔥
* Mobile [https://github.com/hovanvydut/pbl6-mobile](https://github.com/hovanvydut/pbl6-mobile)
* Client End User [https://github.com/hovanvydut/pbl6-frontend-client](https://github.com/hovanvydut/pbl6-frontend-client)
* Client Admin [https://github.com/hovanvydut/pbl6-frontend-admin](https://github.com/hovanvydut/pbl6-frontend-admin)
* Backend Service [https://github.com/hovanvydut/pbl6-be-monolithic](https://github.com/hovanvydut/pbl6-be-monolithic)
* AI Service [https://github.com/hovanvydut/pbl6-ai](https://github.com/hovanvydut/pbl6-ai)
* Migration [https://github.com/hovanvydut/pbl6-ai](https://github.com/hovanvydut/pbl6-ai)


## Contributor 🌟
<table>
  <tr>
    <td align="center"><img src="https://avatars.githubusercontent.com/u/61351523?v=4" width="100px;" alt=""/><br /><sub><b>Phuong Tran</b><a href="https://github.com/hovanvydut/pbl6-frontend-client/commits?author=pphuongdut" title="Frontend Dev">💻</a> </sub></td><br />
    <td align="center"><img src="https://avatars.githubusercontent.com/u/65323507?v=4" width="100px;" alt=""/><br /><sub><b>Truong Minh Phuoc</b><a href="https://github.com/hovanvydut/pbl6-frontend-client/commits?author=phuocleoceo" title="Frontend Dev">💻</a> </sub></td><br />
    <td align="center"><img src="https://avatars.githubusercontent.com/u/54426113?v=4" width="100px;" alt=""/><br /><sub><b>Ho Van Vy</b><a href="https://github.com/hovanvydut/pbl6-frontend-client/commits?author=hovanvydut" title="Devops">🛠</a></sub></td><br />
    <td align="center"><img src="https://avatars.githubusercontent.com/u/63831488?v=4" width="100px;" alt=""/><br /><sub><b>Nguyen Minh Dung</b></sub></a><br /><a href="https://github.com/hovanvydut/pbl6-mobile/commits?author=dungngminh" title="Mobile Dev">💻📱</a>
</tr>
</table>

## GUIDE use tsrc

### Requirements
- Python version 3

### Setup

Create the workspace
```
mkdir pbl6
cd pbl6
```

Install `tsrc` tool - help manage many repos
```
pip install tsrc
tsrc init git@github.com:hovanvydut/pbl6.git
```

Synchronize all the repositories in the workspace (git pull):
```
tsrc sync
```

Checkout all repo of group BE to main branch
```
tsrc foreach -g be -- git checkout main
```

Use `tsrc foreach -g be -- <command>`

## References

* https://your-tools.github.io/tsrc/