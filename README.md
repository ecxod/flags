
# Flags (ecxod/flags)

## Description 

This library supplies a folder containig following flags to use with i18n.  
It was originally designed as part of the `ecxod` framework, but it can be used in any other `symfony` project, to use the flags directly from the vendor folder:

 Abkhazia, Afghanistan, Aland, Albania, Algeria, American-Samoa, Andorra, Angola, Anguilla, Antarctica, Antigua-and-Barbuda, Argentina, Armenia, Aruba, Australia, Austria, Azerbaijan, Bahamas, Bahrain, Bangladesh, Barbados, Basque-Country, Belarus, Belgium, Belize, Benin, Bermuda, Bhutan, Bolivia, Bosnia-and-Herzegovina, Botswana, Brazil, British-Antarctic-Territory, British-Virgin-Islands, Brunei, Bulgaria, Burkina-Faso, Burundi, Cambodia, Cameroon, Canada, Canary-Islands, Cape-Verde, Cayman-Islands, Central-African-Republic, Chad, Chile, China, Christmas-Island, Cocos-Keeling-Islands, Colombia, Commonwealth, Comoros, Cook-Islands, Costa-Rica, Cote-dIvoire, Croatia, Cuba, Curacao, Cyprus, Czech-Republic, Democratic-Republic-of-the-Congo, Denmark, Djibouti, Dominican-Republic, Dominica, East-Timor, Ecuador, Egypt, El-Salvador, England, Equatorial-Guinea, Eritrea, Estonia, Ethiopia, European-Union, Falkland-Islands, Faroes, Fiji, Finland, France, French-Polynesia, French-Southern-Territories, Gabon, Gambia, Georgia, Germany, Ghana, Gibraltar, GoSquared, Greece, Greenland, Grenada, Guam, Guatemala, Guernsey, Guinea-Bissau, Guinea, Guyana, Haiti, Honduras, Hong-Kong, Hungary, Iceland, India, Indonesia, Iran, Iraq, Ireland, Isle-of-Man, Israel, Italy, Jamaica, Japan, Jersey, Jordan, Kazakhstan, Kenya, Kiribati, Kosovo, Kuwait, Kyrgyzstan, Laos, Latvia, Lebanon, Lesotho, Liberia, Libya, Liechtenstein, Lithuania, Luxembourg, Macau, Macedonia, Madagascar, Malawi, Malaysia, Maldives, Mali, Malta, Marshall-Islands, Mars, Martinique, Mauritania, Mauritius, Mayotte, Mexico, Micronesia, Moldova, Monaco, Mongolia, Montenegro, Montserrat, Morocco, Mozambique, Myanmar, Nagorno-Karabakh, Namibia, NATO, Nauru, Nepal, Netherlands-Antilles, Netherlands, New-Caledonia, New-Zealand, Nicaragua, Nigeria, Niger, Niue, Norfolk-Island, Northern-Cyprus, Northern-Mariana-Islands, North-Korea, Norway, Olympics, Oman, Pakistan, Palau, Palestine, Panama, Papua-New-Guinea, Paraguay, Peru, Philippines, Pitcairn-Islands, Poland, Portugal, Puerto-Rico, Qatar, Red-Cross, Republic-of-the-Congo, Romania, Russia, Rwanda, Saint-Barthelemy, Saint-Helena, Saint-Kitts-and-Nevis, Saint-Lucia, Saint-Martin, Saint-Vincent-and-the-Grenadines, Samoa, San-Marino, Sao-Tome-and-Principe, Saudi-Arabia, Scotland, Senegal, Serbia, Seychelles, Sierra-Leone, Singapore, Slovakia, Slovenia, Solomon-Islands, Somalia, Somaliland, South-Africa, South-Georgia-and-the-South-Sandwich-Islands, South-Korea, South-Ossetia, South-Sudan, Spain, Sri-Lanka, Sudan, Suriname, Swaziland, Sweden, Switzerland, Syria, Taiwan, Tajikistan, Tanzania, Thailand, Togo, Tokelau, Tonga, Trinidad-and-Tobago, Tunisia, Turkey, Turkmenistan, Turks-and-Caicos-Islands, Tuvalu, Uganda, Ukraine, United-Arab-Emirates, United-Kingdom, United-Nations, United-States, Unknown, Uruguay, US-Virgin-Islands, Uzbekistan, Vanuatu, Vatican-City, Venezuela, Vietnam, Wales, Wallis-And-Futuna, Western-Sahara, Yemen, Zambia, Zimbabwe

The flags are in `png`, `icns` and `ico` format.

## Content of the package

```tree
tree -d flags
flags
├── flags
│   ├── flat
│   │   ├── 16 (png)
│   │   ├── 24 (png)
│   │   ├── 32 (png)
│   │   ├── 48 (png)
│   │   ├── 64 (png)
│   │   ├── icns
│   │   └── ico
│   └── shiny
│       ├── 16 (png)
│       ├── 24 (png)
│       ├── 32 (png)
│       ├── 48 (png)
│       ├── 64 (png)
│       ├── icns
│       └── ico
└── flags-iso
    ├── flat
    │   ├── 16 (png)
    │   ├── 24 (png)
    │   ├── 32 (png)
    │   ├── 48 (png)
    │   ├── 64 (png)
    │   ├── icns
    │   └── ico
    └── shiny
        ├── 16 (png)
        ├── 24 (png)
        ├── 32 (png)
        ├── 48 (png)
        ├── 64 (png)
        ├── icns
        └── ico
```

## Install 

```sh
php composer.phar require ecxod/flags
```

We assume that your web space is in `/public`, and that you apply the `symfony` convention, according to which such images are usually located in the `/public/assets/images` folder.

After installing composer will create a link from the vendor folder containig the flag pictures to the workspace into `public/assets/images`, As shown in the lower tree.

```tree
├── public
│   └── assets
│       └── images
│           └── flags -> ../../vendor/ecxod/flags
├── vendor
│   └── ecxod
│       └── flags
            ├── flags
                ├── flags
                    ├── flat
                        ├── 16
                        ├── 24
                        ├── ...
                │   │   └── ico
                │   └── shiny
                ├── flags-iso
                │   ├── flat
                        ├── 16
                        ├── 24
                        ├── ...
```
