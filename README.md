# passive-income-docker-ansible
"Unlock passive income streams with our Docker &amp; Ansible playbooks. Start earning effortlessly. Explore now!"

## Requirements:

- Accounts on each service
- Ansible `apt-get install ansible`
- 1 CPU / 768Mb Memory / 1Gb Disk
- Supports on DePin networks like [Akash](https://deploy.cloudmos.io/sdl-builder)
- Donation Fee (Micro XMR Miner | 0.05% CPU usage ) ! Thank you for your support!

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
    earnfm_token: "{{ EARNFM_TOKEN }}"
    honeygain_email: "{{ EMAIL }}"
    honeygain_password: "{{ PASSWORD }}"
    presearch_registration_code: "{{ REGISTRATION_CODE }}"
    proxylite_user_id: "{{ USER_ID }}"
    proxyrack_api_key: "{{ API_KEY }}"
    repocket_email: "{{ RP_EMAIL }}"
    repocket_api_key: "{{ RP_API_KEY }}"
    traffmonetizer_token: "{{ TOKEN }}"
```

## Step 3: Deploy the Ansible playbook

```
ansible-playbook -i hosts.ini playbook.yml
```
