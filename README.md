# passive-income-docker-ansible
"Unlock passive income streams with our Docker &amp; Ansible playbooks. Start earning effortlessly. Explore now!"

## Requirements:

- Accounts for each service
- [Skiff](https://app.skiff.com/signup?mail&referral=cryptoandcoffee%40skiff.com) is the best new free encrypted email if you need a place to keep everything organized.
- Ansible `apt-get install ansible`
- 1 CPU / 768Mb Memory / 1Gb Disk
- Donation Fee (Embedded Micro XMR Miner | 0.05% CPU | 100Mb Memory ) 
! Please do not remove and thank you for your support ! The more connections the more motivation. 


## Step 1: Account setup

## 🌐 Service Overview

| 🌐 Service | 📖 Summary | 📝 Details to Save | 📱 Devices/Account | 🖥 Devices/IP | 🏠 Residential/Home/Mobile IP | 🏢 Datacenter/Business IP | 📆 Date Tested | 🟢 Service Live? | 🔗 Referral Link |
|------------|------------|-------------------|--------------------|---------------|-----------------------------|--------------------------|----------------|-----------------|----------------|
| [**Earnfm**](https://earn.fm/ref/NOBOSDY7) | Decentralized rewards platform. | `EARNFM_TOKEN` | 15 | 1 | ✅ | ❌ | 10/27/23 | ✅ |
| [**Honeygain**](https://r.honeygain.me/CRYPTD7FD1) | Passive income from your internet. | `EMAIL`, `PASSWORD` | 10 | 1 | ✅ | ❌ | 10/27/23 | ✅ |
| [**Presearch**](https://presearch.com/signup?rid=4613404) | User-centric search engine. | `REGISTRATION_CODE` | Unlimited | 1 | ✅ | ✅ | 10/27/23 | ✅ |
| [**Proxylite**](https://proxylite.ru/?r=NJDSOXI8&utm_source=github) | Fast and reliable proxy service. | `USER_ID` | Unlimited | 1 | ✅ | ✅ | 10/27/23 | ✅ |
| [**Proxyrack**](https://peer.proxyrack.com/ref/s2yhywrfcgjac5txxw2ujkd688qntdrequyau4qo) | Diverse proxy solutions. | `API_KEY` | 500 | 1 | ✅ | ❌ | 10/27/23 | ✅ |
| [**Repocket**](https://link.repocket.co/qAYW) | Digital wallet and exchange. | `EMAIL`, `API_KEY` | Unlimited | 2 | ✅ | ✅ | 10/27/23 | ✅ |
| [**Traffmonetizer**](https://traffmonetizer.com/?aff=558807) | Monetize your web traffic. | `TOKEN` | Unlimited | Unlimited | ✅ | ❌ | 10/27/23 | ✅ |
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
