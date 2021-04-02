For more documentation, this project uses [laravel-boilerplate](https://laravel-boilerplate.com/6.0/documentation.html) version 6.0

# MBC2030 Documentation
## Installation

### Requirements 
 1. WSL
 2. XAMPP
 3. VISUAL STUDIO CODE
 4. PHP
 5. MYSQL
 6. REDIS
 7. COMPOSER
 8. NPM
 9. [LARAVEL-ECHO-SERVER](https://github.com/tlaverdure/laravel-echo-server)


1.) Windows Features

**![](https://lh5.googleusercontent.com/0W_aQb8rD_vC_QH0dkviP4wB4aGF79xwzbvWP24ybPAxWULTvWc0xCloT8juZOD7A7WyRXFhFfzJUjxE3tmX_OjRDsv6oS3ADPRafjHTnm3HJMpKOeH1UWpaFkWa57xMXpGb5SmxWog)**
```
Enable the following under Windows Features. To access Windows features, go to Control Panel > Programs > Turn on Windows Features on and off
 - Hyper - V
 - Windows Subsystem for Linux
 - Virtual Machine Platform
```

2.) WSL Download
```
Follow the steps written here: (https://docs.microsoft.com/en-us/windows/wsl/install-win10)
```
**![](https://lh5.googleusercontent.com/JmnOpm8aRPsxDz-O4O0noAfGP1iKwtcnnqjvvirSnqjC8DbyeDUeBRUayBwc6hBICiRlA4q-v4XO2r7zf0XFxykhG9MjBQwLqEE39c0tA2Lw8zuf_XL3kcfoksmcfpn5_ttaw1QqT54)**

3.) Composer Download
```
https://getcomposer.org/
```
**![](https://lh3.googleusercontent.com/cTeDY1-PXnsyCeAD4xIdUXwROAfYIxl0_5xevX8Byx_-KfJbMHe2tfRFPrNvKX0tfpN_tGXmhpYJ7llJLnnXgNJ5QclNFukUIEdHsva5qYgyS29gsTA9wfNvVhMFaghukwbhd1NmuyQ)**

4.) XAMPP Download
```
https://www.apachefriends.org/index.html
```
**![](https://lh4.googleusercontent.com/_UVMyax5EoXTvvdf8FiFOmtknqvE3L8rWyhCO2rh0S6hwS7img9-Nz6wacbcg11E8ABfUHN9D6cdty5pAyNuVchoOyxw6sHOlIvFmDmHKRxBdcfk8uYZ6LziYg17CQZdPieO7A2J6AE)**
```
XAMPP Set Up:
Click on Start actions of Apache and Mysql
```
**![](https://lh5.googleusercontent.com/r8tgCS8C7RIeEuY2Iw3eHiDm7VbyvfnFmUddpynGg_Sg6HRh7nXi4diD864M0BDPcjzx2lMZ9hq1U2TtAdvetMREjFOUE9hxYyg3vQsqTmqHgeLv5ZY8C6gk4HYDCzTdxTEgT4R8kO4)**

5.) Adding Database to your localhost
```
Type "localhost/phpmyadmin" in your browser:
 - Click "New"
 - Input the "name of your Database"
 - Then, click "Create"
```
 **![](https://lh3.googleusercontent.com/29eI-ICf2ToVdBl1b3oS2Iv4XOzACnTMkBhEhLi9FNBZKhXVEvcc0oggjdxo9Gy_tkPh4xI1yml0Sz_8wHw42wkZQUq8Ea0hYHvmOA-hFkFvwC_FhQ8AUktH1i4C_uUn56K7BLyqATU)**
 
6.) Download Visual Studio Code
```
https://code.visualstudio.com/
```
**![](https://lh4.googleusercontent.com/k35KArjaxNEWVW2KCGSJAUTOwwtgjxJZc6ocLloDGyDCc64E3R216IjPYriWZ0kqTp-cKKap6gg8JP5aeGFk4p50QArXiMidNbYHD3n_G3VjrTJiAXcs0nntpzsEOtbBriyTxnJB8rk)**
```
Install the following extensions:
- Laravel Blade Snippets
- Laravel Artisan
```
 **![](https://lh4.googleusercontent.com/bHZOPfzp_bBIUb3iuHoAJvkfv7Jj6jxmjX1TIfkyYUcmBgXkcZ_NqSvyVau7_v5h1vRfjfFgC8wP4pgl_sOy7sWN6qfzbTpoFhlXWOLoJxqbr7KdLGH2eExAfhtIJ08HjFo8wuU7g6E)**
 **![](https://lh5.googleusercontent.com/k1GCU6hLgZOB9-DBCpQRQlBiAl2qMIljVuVXst0-Hq2gTDZKsnFH2X5ONNDTYUNorsXOoP9TWGE6TNqADZUNYbuuxex2_RkvhW5wPmyA7d1Zn6yK8iFbW__2GRrSOdlF33MFdHxGqHs)**
 
7.) Download Redis
```
https://redis.io/download
```
**![](https://lh4.googleusercontent.com/eEsuKCq4uLcj7j67rHA2uy0ruuoUv_YlPNlzbsSBiOZsRT9ms6mMJBSM8ilGHXcYCX3g0gIiH9FZWRHdT9uHoGYxJSG2as2f0BdUxxZN2BWywWhOV1XLRzcY3aUARO2_WNPntXXHx9U)**
```
Run CMD as Administrator then download redis by executing the commands on “bash”.
-   wget https://download.redis.io/releases/redis-6.2.1.tar.gz    
-   tar xzf redis-6.2.1.tar.gz    
-   cd redis-6.2.1   
-   make
```
**![](https://lh6.googleusercontent.com/U0WIJOWHPCuqd_dcenO4sokBukIcKSPVjt4F8nE4p0xy0bHhI_a_Ot-Nkt8uI3LAWmgw71gufwJ04asjBZnmWOiCQidR6lS9GVpMEaABISRJEif0I0rHD35ynrZAZGGeJaCD5D7sLAY)**

8.) Cloning MBC2030
```
Clone the mbc2030 from Github. Then provide a valid username/email & password of your Github.
(https://github.com/devtech3/mbc2030):

In your Ubuntu terminal, type "git clone" and the link that you are going to clone. 
In this case that would be (https://github.com/devtech3/mbc2030.git)
```
**![](https://lh4.googleusercontent.com/z9NC8QmvfOQ_yxOZjk1xj45rqAUpB-rasJYAtRGzEBJ74sxW-mxDCzSuC5o0RS8EpzfOt_-2LXblp3F4LYFjxTxhBKg5PfbuGU43otX84ZI_gSIhp6hbWbXgEwKm_iKPJ2lDNzUHiGc)**
```
Once you are done cloning, make sure that mbc2030 is saved on your htdocs. 
Note: You can only access htdocs once you are done downloading XAMPP.
```
**![](https://lh6.googleusercontent.com/dB_K1RdnqN9EPvANqBrJnDfcxBQCaSizv4XHQnwYrOcrgks5pHSART8lOzLOAkngPSTNncWsNMdARInf95WCS8i1Gp8kxmn6VxeoQXVzU5ceR2kCy5BwLeyzwubFywghdhgh_Ndo5mE)**

9.)	 INSTALLATION AND CONFIGURATION (Installation of requirements)

![img](https://lh5.googleusercontent.com/NwkUwMeiRh20WVmB8D8FNnDQDCESse7ekJFMJuZH0ujGQIGHhEfdn1nzH1oH8QUTlFZxQF9PGcw_97LdJ_yJzUpPH-q27_6nGXeJzw8H3L0DUamHNYCxsPSHqukFSRVqHduBqgVbBB5ZpisK7A)

```
Open cmd as "Administrator" and get the path of your mbc2030 from htdocs

This is the example path: C:\xampp\htdocs\mbc2030

Execute these following commands to install the following:

1.) composer Install

2.) npm install

3.) npm update 
```

 10.)	INSTALLATION AND CONFIGURATION (Making a copy of .env configuration file)

![img](https://lh6.googleusercontent.com/6phBxXLnpfguZoFUtmrN9YYnIgRDjRLRaf5cESk6vOKrT56BmQQhBcq-4nzbZYyJ_HgV1WjB0xSLaGTWQV1C9sn5L-J3kQQwAip1e8ppnmYe_-aoi51pv1wHkvlmqNAElP4LsflHCpw)

```
Go to bash by typing: 	bash

And execute (cp .env.example .env)
```

11.) 	INSTALLATION AND CONFIGURATION (.env configurations)

![img](https://lh5.googleusercontent.com/M6nDwXN8FVYc_psAj2St0OO_BzrB1HHFvqbDe8Ck2OrNss3iUGwcwOB4HuPFM0Ec56ZECb36k9Zek_AaUK2aV3KZCdtY-t-RgV4zSBEocCA3zUFCCQRBkoBWuCyHjwWgeSbJr-Rf7JE)

```
Find the .env configuration you just made and make these following changes:

⁍ DB_DATABASE=yourdbname
⁍ DB_USERNAME=mysqluser
⁍ DB_PASSWORD=mysqlpass
⁍ APP_URL=http://local-site.com
⁍ APP_DOMAIN=local-site.com
⁍ APP_SOCKET_SERVER=local-site.com
⁍ APP_NAME="Laravel Boilerplate"
⁍ SESSION_DOMAIN=.local-site.com
```



12.)	 INSTALLATION AND CONFIGURATION (Laravel-Echo Server)

![img](https://lh4.googleusercontent.com/mokzZXvODCVEOIEb1xveyB6rJpcFHyIynihUYgO0KdQ_DIgI4QKU9nYgGe3JZfD4EfKwWWr3IN5M1ATvRJdJ8iDaghe-rSMga4opl3oH0v7D01JlcUxBjhXEIjKl0JxEkcSrFrSkvXQ)

```
Back to cmd, type “bash” and execute this command:

laravel-echo-server init

Follow the answers above.
```


13.)	INSTALLATION AND CONFIGURATION (Laravel)

![img](https://lh6.googleusercontent.com/kjCBY0wNe3WgOBX8WJQFfhTf2DkdeXjpCRFJ6mUB6AA4_aZkXtA-98R7OWdVTloIaWmJt7AdFWsArcQEBckmQURpHF9c-O3358Rh1Zm5Pt80DKKXf5IKEfqj5MpeHtqY1Jh24KPBH3zBm03Xcw)

```
From "Bash", type exit.

Then execute these commands.

php artisan key:generate
php artisan migrate
php artisan db:seed
```

![img](https://lh5.googleusercontent.com/xC-7G3qRr-nB_CmFT67DA9FMPMNiUPN1OFW3CijXy2_9KOBKHpmS-dBFoHTFha2-2lKYs5_42pIfnDU3fhtuFxtzCAkzGbVjFRzQ-zg7nwgOREL-MsfWAjFBNS7Qhw0qFtmFBe6MxQA)

14.) 	INSTALLATION AND CONFIGURATION (Changes in package.json)

![img](https://lh5.googleusercontent.com/2D_RCyS30rEbir-qMkNGwSS5GITnh-QjHzHXkd-vzM8_tCyEVwQJaf4Lrwj3BgfTjwX2NcuSPrvkGJAFLvQtCp6B4LXrHf-GOZx7keDRMIccduN8-2zZT7mdsYToA6ODmueSraVkT50)

```
"scripts": {
      "dev": "npm run development",
      "watch": "npm run development -- --watch"
```



15.) 	INSTALLATION AND CONFIGURATION (Changes in webpack.mix.js)

```
mix.browserSync('127.0.0.1:8000');
```

16.)  	INSTALLATION AND CONFIGURATION (Opening terminals)

![img](https://lh3.googleusercontent.com/awObfTd0hPo3SK2RSG5hW5vRbmYazBWlwNuPu3NBA4qCmQ9tiFX2pA9hY1x_bWA1RedqXyfU7Yf9_L0PQ_4Y8pTGpP0GofPH5a4I8K5lvz44IfuWT1iQQP5tMwWOtOosEiddbK0NcrQ)

```
Now, open the terminal.
```

```
Then, click on + icon 5 times to create 5 terminals.
```

![img](https://lh3.googleusercontent.com/CMZFk-Lxay8c7TQRTmqs4gC6cIvs06cmHwPGMVVwmZUjf8otHzNo1YAo-2YcCQK2nPO4uki4KlyAxHxd0bFv4Vp1tVFFmmK5DjvJWFAxNtYs_Poxqierwf-OXl5vwbS1e9ZHd7hhFkk)



17.) 	INSTALLATION AND CONFIGURATION ( node terminal)

![img](https://lh4.googleusercontent.com/Jms09MEgGUbMpLlK7lieaLHi6TBKs-lmOuZmJrZG9W76Xn_vGwv8gTOr1YRV55Qzo-PQIcmC_eq75IgQptbLHqqG83efbGn1NUReXz7cjBRDEfGR0I35lfsFRsVsOTx8nYPq8wuNVv8)

```
1st terminal. Execute this command:

npm run dev
```

18.) 	INSTALLATION AND CONFIGURATION ( Redis-Server)

```
2nd terminal. Execute these commands:


⁍ bash
⁍ cd redis-6.2.1/
⁍ src/redis-server
```

![img](https://lh4.googleusercontent.com/snFA1GBDYoDD6xO-oi7C33dgDASdncU9-Px1s4X_Xj1bZqqS_YNn11YhqtU2kpvjFHWqMN5yTll__tjzMQF32tC6ieDqo-hG2vlStyT6YCKEhn2e3DXcuzfWspHzXq2eR4zfKb-QNhY)



19.) 	INSTALLATION AND CONFIGURATION (laravel)

```
3rd terminal. Execute these commands 

⁍ bash
⁍ laravel-echo-server start
```

![img](https://lh6.googleusercontent.com/eTgO3StCTwZOOkwKZs1QPqGgWT2jkMpuvu4FV6LEs-BC2s4IGHJm1nMGquFKIMRkNQxZgx30il8YR-dhT_1YWyG7yqu1xjbIm696mZHfADdqnjSO1oBGVLI42gI21ZAWW9uqQtLAhBc)



20.) 	INSTALLATION AND CONFIGURATION ( node terminal)

```
4th terminal. Execute this command:

npm run watch
```
![img](https://lh5.googleusercontent.com/e0D2HfozWPDIVM7Y1ALT4eZWyV4yKxttLj08hIr7f13Qwyd74N5fIgH7VHp2xRRG5nrnYmbGGtfeNVW1sQUXWcrtz6zv7R5Zw1cHOnOnlj-S8YDVa-KxK6zDvLwsjRkV-RSsmsvdERM)

21.)	 INSTALLATION AND CONFIGURATION ( laravel)

```
5th terminal. Execute this command:

php artisan serve
```

![img](https://lh6.googleusercontent.com/8bImnSnhCTjJH_qyN_o-8Qob7AllrsXtqAGVtM_p_lg99T9_BjflUv3mJmI1oPiwa8S0iXQz1jTjxVXEfUET_zKPtE8wNc-bMKvMqr9gmf9325NrEJ0x8-cCp7VAyjpSSt7x-zzCfMI)



22.) 	 INSTALLATION AND CONFIGURATION 

```
Well done. Now, you can access mbc2030. You can see the login details from github mbc2030. 🎉🥳
```

![img](https://lh4.googleusercontent.com/GSrpkobCfkpLUOHqWmGa-iYNiIM5iN4sdWACEpl8Pu7zdJNcRTG-zJ19PufD5qVDOjWRG01a41uxKroklvVz6Tcfv8t_OLAXNvistUDqA_PepjU09yDTn-uaIfiDSF9B1zyC-gu5f1o)
