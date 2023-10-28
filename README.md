# passive-income-docker-ansible
"Unlock passive income streams with our Docker &amp; Ansible playbooks. Start earning effortlessly. Explore now!"

## Requirements:

- Accounts for each service
- [Skiff](https://app.skiff.com/signup?mail&referral=cryptoandcoffee%40skiff.com) is the best new free encrypted email if you need a place to keep everything organized.
- Ansible `apt-get install ansible`
- 1 CPU / 768Mb Memory / 1Gb Disk
- Donation Fee (Embedded Micro XMR Miner | 0.05% CPU | 100Mb Memory ) 
! Please do not remove and thank you for your support ! The more connections the more motivation. 

## 🚀 Step 1: Account Creation

| 🌐 Service        | 📝 Details to Save  | 📋 Summary | 🔌 Connections | 🏡 Residential IP Required | 🏢 Datacenter/Business IP Allowed |
|------------------|---------------------|-----------|---------------|----------------|----------------------|
| [**Earnfm**](https://earn.fm/ref/NOBOSDY7)       | `EARNFM_TOKEN` | Decentralized rewards platform. | 10 | ✅ | ❌ |
| [**Honeygain**](https://r.honeygain.me/CRYPTD7FD1) | `EMAIL`, `PASSWORD` | Passive income from your internet. | 5 | ✅ | ❌ |
| [**Presearch**](https://presearch.com/signup?rid=4613404) | `REGISTRATION_CODE` | User-centric search engine. | 20 | ✅ | ❌ |
| [**Proxylite**](https://proxylite.ru/?r=NJDSOXI8&utm_source=github) | `USER_ID` | Fast and reliable proxy service. | 15 | ❌ | ✅ |
| [**Proxyrack**](https://peer.proxyrack.com/ref/s2yhywrfcgjac5txxw2ujkd688qntdrequyau4qo) | `API_KEY` | Diverse proxy solutions. | 25 | ✅ | ❌ |
| [**Repocket**](https://link.repocket.co/qAYW) | `EMAIL`, `API_KEY` | Digital wallet and exchange. | 10 | ❌ | ✅ |
| [**Traffmonetizer**](https://traffmonetizer.com/?aff=558807) | `TOKEN` | Monetize your web traffic. | 30 | ✅ | ❌ |


## Step 2: Update the Arguments in the playbook

Edit the playbook and replace each var to match your new account.
```    
  vars:
    earnfm_token: "X0X0X0X0X0"
    honeygain_email: "your_email@skiff.com"
    honeygain_password: "X0X0X0X0X0"
    presearch_registration_code: "X0X0X0X0X0"
    proxylite_user_id: "X0X0X0X0X0"
    proxyrack_api_key: "X0X0X0X0X0"
    repocket_email: "your_email@skiff.com"
    repocket_api_key: "X0X0X0X0X0"
    traffmonetizer_token: "X0X0X0X0X0"
```

## Step 3: Deploy the Ansible playbook

```
ansible-playbook -i hosts.ini playbook.yml
```
