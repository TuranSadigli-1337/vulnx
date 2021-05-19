<h1 align="center">
  <br>
  <a href="https://github.com/anouarbensaad/VulnX"><img src="https://i.ibb.co/ZxxFqxQ/vxv2.png" alt="VulnX"></a>
  <br>
  VulnX
  <br>
</h1>

<h4 align="center">Vulnx 🕷️ hörümçək çoxsaylı sms zəifliklərini aşkarlayan ağıllı bir bot avtomatik qabıq enjektorudur. </h4>

<p align="center">
   <a href="https://github.com/anouarbensaad/vulnx/releases">
    <img src="https://img.shields.io/github/release/anouarbensaad/vulnx.svg">
  </a>

  <a href="https://pypi.org/project/vulnx/">
    <img src="https://img.shields.io/badge/pypi-vulnx-red.svg">
  </a>

  <a href="https://github.com/anouarbensaad/vulnx/issues?q=is%3Aissue+is%3Aclosed">
      <img src="https://img.shields.io/github/issues-closed/anouarbensaad/vulnx.svg">
  </a>
  <a href="https://travis-ci.com/anouarbensaad/vulnx">
    <img src="https://img.shields.io/travis/com/anouarbensaad/vulnx.svg">
  </a>
</p>

![Screenshot from 2019-06-19 05-22-04](https://user-images.githubusercontent.com/23563528/59736664-7c2fed00-9252-11e9-936d-53ea02628711.png)

https://github.com/anouarbensaad/vulnx/archive/master.zip
<p align="center">
  <a href="https://github.com/anouarbensaad/vulnx/wiki">VulnX Wiki</a> •
  <a href="https://github.com/anouarbensaad/vulnx/wiki/Usage">How To Use</a> •
  <a href="https://github.com/anouarbensaad/vulnx/wiki/Compatibility-&-Dependencies">Compatibility</a> •
  <a href="https://github.com/anouarbensaad/vulnx/wiki/Vulnx-Library">Library</a> •
</p>

**Vulnx** çoxsaylı sms, sürətli cms aşkarlanması, məlumat toplama zəifliklərini aşkarlayan Ağıllı Bot Auto [Shell Enjector] (https://github.com/anouarbensaad/vulnx/wiki/Usage#run-exploits). və subabilains, ipaddresses, country, org, timezone, region, ans və daha çox kimi hədəfin taranması ...

Bütün digər alətlər kimi hər bir qabığa əl ilə enjekte etmək əvəzinə, VulnX, hədəfin veb saytını bir həssaslığın mövcudluğunu yoxlayır, əgər qabıq enjekte edilsə. URL'ləri [dorks] ilə axtarın (https://github.com/anouarbensaad / vulnx / wiki / Usage # searching-dorks) Alət.

-------------------------------------

### _🕷️ Xüsusiyyətlər _

- Cms (wordpress, joomla, prestashop, drupal, açıq kart, magento, lokomedia) aşkarlayır
- Hədəf məlumat yığıncaqları
- Hədəf Subdomains toplanması
- Tələbə görə çox dişli
- Zəifliklərin yoxlanılması
- Avtomatik qabıq enjektoru
- Dork axtarışını istismar edin 
- [`Ports Scan`](https://user-images.githubusercontent.com/23563528/58365946-40a83a00-7ec3-11e9-87c5-055ed67109b7.jpg) Yüksək Səviyyə 
- [`Dns`](https://user-images.githubusercontent.com/23563528/58365784-09388e00-7ec1-11e9-8a05-e71fa39f146d.png) -Servers Dump 
- Taramaq üçün birdən çox hədəfi daxil edin.
- Adı və ExploitName tərəfindən Dork Listing.
- Dork-dan bir çox hədəfi bir qeyd sənədinə ixrac edin. 

-------------------------------------


### _🕷️ DNS-Xəritə-Nəticələr_

Bunu etmək üçün, alt domenlər üçün --dns bayrağı və -d ilə bir tarama aparın.
İsetso.rnu.tn xəritəsini yaratmaq üçün əmri işə sala bilərsiniz
`vulnx -u isetso.rnu.tn --dns -d - $ PATH`yeni bir terminalda çıxartmaq.

`$ PATH`: Qrafik nəticələrinin harada saxlanacağı. 

![vokoscreen-2019-06-19_05-44-07](https://user-images.githubusercontent.com/23563528/59737395-696ae780-9255-11e9-9e09-26416de89bee.gif)


Hədəf Subdomains, MX & DNS məlumatlarını göstərən bir şəkil yaradırıq.

![demo](https://i.ibb.co/WfdhvWC/isetso-rnu-tn.png)

-------------------------------------

### _🕷️ İstismarlar_
<h1 align="center">
<a href="https://github.com/anouarbensaad/VulnX"><img src="https://user-images.githubusercontent.com/23563528/59737042-06c51c00-9254-11e9-87f8-876b33c87be1.gif" alt="Exploits Running"></a>
</h1>

##### Joomla
- [x] [Com Jce            ]('#')
- [x] [Com Jwallpapers    ]('#')
- [x] [Com Jdownloads     ]('#')
- [x] [Com Jdownloads2    ]('#')
- [x] [Com Weblinks       ]('#')
- [x] [Com Fabrik         ]('#')
- [x] [Com Fabrik2        ]('#')
- [x] [Com Jdownloads Index]('#')
- [x] [Com Foxcontact     ]('#')
- [x] [Com Blog           ]('#')
- [x] [Com Users          ]('#')
- [x] [Com Ads Manager    ]('#')
- [x] [Com Sexycontactform]('#')
- [x] [Com Media          ]('#')
- [x] [Mod_simplefileupload]('#')
- [x] [Com Facileforms    ]('#')
- [x] [Com Facileforms    ]('#')
- [x] [Com extplorer      ]('#')

##### Wordpress
- [x] [Simple Ads Manager   ](https://www.exploit-db.com/exploits/36614)
- [x] [InBoundio Marketing  ](https://www.rapid7.com/db/modules/exploit/unix/webapp/wp_inboundio_marketing_file_upload) 
- [x] [WPshop eCommerce     ](https://www.rapid7.com/db/modules/exploit/unix/webapp/wp_wpshop_ecommerce_file_upload)
- [x] [Synoptic             ](https://cxsecurity.com/issue/WLB-2017030099) 
- [x] [Showbiz Pro          ](https://www.exploit-db.com/exploits/35385) 
- [x] [Job Manager          ](https://www.exploit-db.com/exploits/45031) 
- [x] [Formcraft            ](https://www.exploit-db.com/exploits/30002)
- [x] [PowerZoom            ](http://www.exploit4arab.org/exploits/399)
- [x] [Download Manager     ](https://www.exploit-db.com/exploits/35533)
- [x] [CherryFramework      ](https://www.exploit-db.com/exploits/45896)
- [x] [Catpro               ](https://vulners.com/zdt/1337DAY-ID-20256)
- [x] [Blaze SlideShow      ](https://0day.today/exploits/18500)
- [x] [Wysija-Newsletters   ](https://www.exploit-db.com/exploits/33991)

##### Drupal
- [ ] [Add Admin            ]('#')
- [ ] [Drupal BruteForcer   ]('#')
- [ ] [Drupal Geddon2       ]('#')

##### PrestaShop
- [x] [attributewizardpro   ]('#')
- [x] [columnadverts        ]('#')
- [ ] [soopamobile          ]('#')
- [x] [pk_flexmenu          ]('#')
- [x] [pk_vertflexmenu      ]('#')
- [x] [nvn_export_orders    ]('#')
- [x] [megamenu             ]('#')
- [x] [tdpsthemeoptionpanel ]('#')
- [ ] [psmodthemeoptionpanel]('#')
- [x] [masseditproduct      ]('#')
- [ ] [blocktestimonial     ]('#')
- [x] [soopabanners         ]('#')
- [x] [Vtermslideshow       ]('#')
- [x] [simpleslideshow      ]('#')
- [x] [productpageadverts   ]('#')
- [x] [homepageadvertise    ]('#')
- [ ] [homepageadvertise2   ]('#')
- [x] [jro_homepageadvertise]('#')
- [x] [advancedslider       ]('#')
- [x] [cartabandonmentpro   ]('#')
- [x] [cartabandonmentproOld]('#')
- [x] [videostab            ]('#')
- [x] [wg24themeadministration]('#')
- [x] [fieldvmegamenu       ]('#')
- [x] [wdoptionpanel        ]('#')

##### Opencart
- [ ] [Opencart BruteForce]('#')


-------------------------------------

### _🕷️ VulnxMode_
`YENİ`
vulnx artıq interaktiv bir rejimə sahibdir.
***URLSET***

![vulnxmode_url](https://user-images.githubusercontent.com/23563528/68983791-fddd7400-080c-11ea-8e2b-c463a2c8f8c5.png)

***DORKSET***

![vulnxmode_dorks](https://user-images.githubusercontent.com/23563528/68985825-bf01eb00-0819-11ea-83ea-3db022b1d645.png)

-------------------------------------



### _🕷️ Mövcud komanda xətti seçimləri_
[`VULNX WIKI'yi oxuyun`](https://github.com/anouarbensaad/vulnx/wiki/Usage)

    istifadə: vulnx [seçimlər]
    
      -u - url url hədəfi
      -D - Dork ilə axtarış şəbəkələrini pisləşdirir
      -o - Çıxış qovluğunu göstərin
      -t --timeout http istəkləri zaman aşımı
      -c - cms-info axtarış cms info [mövzular, plaginlər, istifadəçi, versiya ..]
      -e - axtarış zəifliyini istismar edin və istismarları istifadə edin
      -w --web-info veb məlumatların toplanması
      -d - etki-məlumat alt domenlər məlumatların toplanması
      -l, --dork istismarının siyahı siyahısı
      -n, - axtarış motorunun say nömrəli səhifə nömrəsi (Google)
      -p, - tarama üçün limanları dəstəkləyir
      -i, - giriş faylından taranacaq domenləri daxil edin
      - sapların sayı
      --dns dns məlumat toplama 

-------------------------------------

### _🕷️ Docker_

VulnX DOCKER'da !!.

```bash
$ git clone https://github.com/anouarbensaad/VulnX.git
$ cd VulnX
$ docker build -t vulnx ./docker/
$ docker run -it --name vulnx vulnx:latest -u http://example.com
```

vulnx konteynerini interaktiv rejimdə çalışdırın


![vokoscreen-2019-06-23_11-53-20](https://user-images.githubusercontent.com/23563528/59975226-a31d5480-95ad-11e9-8252-ddd8291cbee4.gif)


günlük sənədlərinə baxmaq üçün onu belə bir cilddə yerləşdirin:

```bash
$ docker run -it --name vulnx -v "$PWD/logs:/VulnX/logs" vulnx:latest -u http://example.com
```
dəyişdirin - [montaj kataloqu](https://github.com/anouarbensaad/vulnx/blob/master/docker/Dockerfile#L46)..

```Dockerfile
VOLUME [ "$PATH" ]
```

-------------------------------------

### _🕷️ Ubuntu_-da vulnx quraşdırın

```bash
$ git clone https://github.com/anouarbensaad/vulnx.git
$ cd VulnX
$ chmod +x install.sh
$ ./install.sh
```
Now run `vulnx`

![vokoscreen-2019-07-05_03-59-48](https://user-images.githubusercontent.com/23563528/60695392-7a645b80-9ed9-11e9-94fb-f6025594a9e3.gif)


### _🕷️ Termux_-da vulnx quraşdırın

```BASH
$ pkg update
$ pkg install -y git
$ git clone http://github.com/anouarbensaad/vulnx
$ cd vulnx
$ chmod +x install.sh
$ ./install.sh
```
[**NƏTİCƏNİ GÖSTERMƏK ÜÇÜN BURAYI TIKLAYIN**](https://user-images.githubusercontent.com/23563528/58364091-98847800-7ea6-11e9-9a9a-c27717e4dda1.png)


### _🕷️ Windows-da vulnx quraşdırın

- [bura basın](https://github.com/anouarbensaad/vulnx/archive/master.zip) to download vulnx
- python3 yükləyin və quraşdırın
- unzip **vulnx-master.zip** in ***c:/***
- - **cmd** açın.
```
> cd c:/vulnx-master
> python vulnx.py
```

-------------------------------------

Seçimlərlə ##### misal əmri: settimeout = 3, cms-gathering = all, -d subdomains-gathering, run --exploits
`vulnx -u http://example.com --timeout 3 -c all -d -w --exploit` 

##### dorkları axtarmaq üçün nümunə əmri: -D və ya --dorks, -l - list-dorks
`vulnx --list-dorks`
istismar adının qaytarılması cədvəli.
`vulnx -D blaze`
qayıdan URL-lər alovlu dork ilə tapıldı 

-------------------------------------

### _🕷️ Versiyalar_
- [v1.9](https://github.com/anouarbensaad/vulnx/releases/tag/v1.9)
- [v1.8](https://github.com/anouarbensaad/vulnx/releases/tag/v1.8)
- [v1.7](https://github.com/anouarbensaad/vulnx/releases/tag/v1.7)
- [v1.6](https://github.com/anouarbensaad/vulnx/releases/tag/v1.6)
- [v1.5](https://github.com/anouarbensaad/vulnx/releases/tag/v1.5)
- [v1.4](https://github.com/anouarbensaad/vulnx/releases/tag/v1.4)
- [v1.3](https://github.com/anouarbensaad/vulnx/releases/tag/v1.3)
- [v1.2](https://github.com/anouarbensaad/vulnx/releases/tag/v1.2)
- [v1.1](https://github.com/anouarbensaad/vulnx/releases/tag/v1.1)

-------------------------------------

###: xəbərdarlıq: Xəbərdarlıq!

***Heç bir qanunsuz istifadədən cavabdeh deyiləm!***

-------------------------------------

### _🕷️ Töhfə və Lisenziya_

Aşağıdakı yollarla töhfə verə bilərsiniz:

- [Xətaları bildirin və problem əlavə edin](https://github.com/anouarbensaad/VulnX/issues/new)
- Yeni zəiflik axtarın
- Plugins inkişaf etdirin
- İstismar Axtarış
- Daha yaxşı etmək üçün təkliflər **(Fikirlər)** verin

Şəxsi söhbət etmək istəyirsiniz? mənə e-poçt: lastomocha@gmail.com və ya Qurucu'nun Gmaili: Bensaad.tig@gmail.com
***VulnX*** lisenziyalıdır [GPL-3.0 License](https://github.com/LasTOmocha/VulnX/blob/master/LICENSE)
