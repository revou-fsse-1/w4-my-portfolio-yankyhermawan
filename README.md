# Deploying Website on Netlify and Custom Domain

## Deploying Website on Netlify

1. Open [Netlify](https://www.netlify.com) and click log in or sign up
![Netlify Landing Page](./assets/netlify_landing_page.png)

2. Choose account for log in or sign up
![Netlify Login](./assets/netlify_login.png)

3. After log in success, click "Sites" --> "Add New Sites" --> "Import an existing project"
![Netlify Sites](./assets/netlify_sites.png)

4. Click on GitHub for import an existing project
![Netlify Choose](./assets/netlify_choose.png)

5. Pick a repository from GitHub
![Netlify Pick Repository](./assets/netlify_pick_repo.png)

6. Click "Deploy site"
![Netlify Deploy](./assets/netlify_deploy.png)

7. After a while, your site has deployed successfully
![Netlify Deploy Success](./assets/netlify_deploy_success.png)

## Using Custom Domain

1. Open [Niagahoster](https://client.niagahoster.co.id/) and scroll down until you find domain search bar. Type domain name you want then click search
![Niagahoster Landing Page](./assets/niagahoster_landing_page.png)

2. After search domain name, niagahoster will check availability of the domain name, and choose domain you want

![Niagahoster Domain](./assets/niagahoster_choose_domain.png)

3. Make a payment

4. Change nameserver on niagahoster
![Niagahoster change nameserver](./assets/niagahoster_change_nameserver.png)

5. Update nameserver1: ns3.niagahoster.com and nameserver2: ns4.niagahoster.com and click "Save"
![Update nameserver](./assets/niagahoster_update_nameserver.png)

6. Scroll down to DNS Management section and click "Manage DNS Record"
![Niagahoster Manage DNS](./assets/niagahoster_dns_management.png)

7. Click on the drop down option and choose "Add New DNS Record"
![Niagahoster Add New DNS](./assets/niagahoster_add_dns_record.png)

8. Choose CNAME from the option
![Niagahoster choose CNAME](./assets/niagahoster_choose_cname.png)
Scroll down and fill the blank (Sub Domain : "www", Hostname: your netlify deployed link, then click "Save")
![Niagahoster fill CNAME](./assets/niagahoster_fill_cname.png) 

9. Click on Add New DNS Record again

10. Choose A Record from the option
![Niagahoster choose A Record](./assets/niagahoster_choose_a.png)
Scroll down and fill the blank (IPv4 : "75.2.60.5")
![Niagahoster fill A](/assets/niagahoster_fill_a.png)

## Setup Domain on Netlify

1. Click Domain Settings on Netlify
![Netlify Domain Setting](./assets/netlify_domain_setting.png)

2. Click on Add a Domain
![Netlify add Domain](./assets/netlify_add_domain.png)

3. Verify your domain that you bought at Niagahoster
![Netlify verify domain](./assets/netlify_verify_domain.png)

4. Congratulation! Your website has successfully published using custom domain
![Netlify Success](./assets/netlify_done.png)