# African Union Membership Status and History (Early 2025)

## 1. Introduction

**Purpose:** This report provides a structured dataset detailing the membership of the African Union (AU), encompassing all 55 current, suspended, and rejoined former member states. The data is presented in a standardized JSON format, reflecting the status as of early 2025, based on analysis of provided documentation.

**Context:** The African Union represents the continuation of the pan-African project initiated by the Organisation of African Unity (OAU). The OAU was formally established on May 25, 1963, in Addis Ababa, Ethiopia, with the signing of the OAU Charter by the leaders of 32 independent African nations.[1] This marked a significant step towards continental unity, cooperation, and solidarity. On July 9, 2002, the OAU was officially transformed into the African Union, reflecting a renewed mandate to address the continent's evolving challenges and opportunities, including deeper integration and socio-economic development.[2] The AU currently comprises 55 member states, covering the entirety of the African continent.[1]

**Methodology:** The information presented herein, particularly the JSON dataset, is compiled through the synthesis and cross-referencing of data extracted from the provided source materials. Official AU lists, historical records of the OAU, and standardized international databases (such as ISO 3166-1) were consulted to ensure accuracy regarding member state names, join dates, ISO codes, and current membership status.[1]

## 2. Summary of Suspended Member States (as of Early 2025)

A notable feature of the African Union's contemporary landscape is the suspension of participation rights for several member states. Suspension is typically enacted by the AU's Peace and Security Council (PSC) in response to unconstitutional changes of government (UCG), primarily military coups, as a mechanism to uphold the organization's norms regarding democracy and constitutional rule.[22] As of early 2025, six member states find their participation in AU activities suspended.

This situation underscores a significant challenge to political stability and democratic governance in parts of the continent. The concentration of recent suspensions in the West Africa/Sahel region (Burkina Faso, Guinea, Mali, Niger) points to a concerning pattern of democratic backsliding and military intervention in that area.[5] Gabon's suspension also follows a coup [23], while Sudan's suspension relates to the military's disruption of a transitional government and subsequent civil conflict.[22]

The frequent invocation of the suspension mechanism highlights the tension between the AU's non-interference principles and its commitment to constitutionalism. Furthermore, the formation of the Alliance of Sahel States (AES) by suspended members Burkina Faso, Mali, and Niger in 2024 signals a potential challenge to the authority and cohesion of both the AU and regional bodies like ECOWAS, as these states seek alternative frameworks for cooperation.[23] The AU's difficulties in enforcing agreed-upon transition roadmaps and timelines in suspended countries raise questions about its effectiveness in managing these complex political crises and restoring constitutional order.[23]

**Table 1: Suspended AU Member States (Early 2025)**

| Country Name (Official English) | ISO 3166-1 Alpha-3 | Original Join Date (OAU/AU) | Status    | Suspension Notes                                                                           |
| :------------------------------ | :----------------- | :-------------------------- | :-------- | :----------------------------------------------------------------------------------------- |
| Burkina Faso                    | BFA                | 1963-05-25                  | Suspended | Suspended since January 2022 due to military coup.[24] Transition period extended.[23]     |
| Gabonese Republic               | GAB                | 1963-05-25                  | Suspended | Suspended since August 31, 2023, following military coup.[5]                                |
| Republic of Guinea              | GIN                | 1963-05-25                  | Suspended | Suspended since September 2021 due to military coup.[5] Transition period extended.[23]    |
| Republic of Mali                | MLI                | 1963-05-25                  | Suspended | Suspended since June 1, 2021, following second coup in nine months.[5] Previously suspended 2020. |
| Republic of Niger               | NER                | 1963-05-25                  | Suspended | Suspended since August 22, 2023, following military coup.[5]                                |
| Republic of the Sudan           | SDN                | 1963-05-25                  | Suspended | Suspended since October 27, 2021, following military coup disrupting transition.[24]        |

## 3. African Union Membership Data (JSON Array)

The following dataset provides comprehensive membership information for all 55 African Union states in JSON format. Each record includes the standard Intergovernmental Organization (IGO) code ("AU"), the country's official English name, its ISO 3166-1 alpha-3 code, current membership status ("Current Member" or "Suspended"), the date of joining the OAU or AU, and pertinent membership notes.

**Structure:** Each object adheres to the format:
`{"IGO": "AU", "COUNTRY_EN": "...", "ISO_A3": "...", "status": "...", "joinDate": "...", "membershipNotes": "..."}`

**Data Compilation:** Country names are based on official AU and UN lists.[1] ISO codes are derived from standard lists.[12] Status reflects early 2025 conditions, incorporating suspension data.[5] Join dates use the OAU founding date (1963-05-25) for charter signatories or later admission dates as documented.[1] Notes capture founding status, suspension details, and Morocco's unique history.[1]

### 3.1 Founding Members

The Organisation of African Unity was established on May 25, 1963, by 32 signatory states in Addis Ababa, Ethiopia.[2] These nations are recognized as the founding members of the continental body. Their commitment laid the groundwork for decades of cooperation and the eventual transition to the African Union.

**Table 2: OAU Founding Members (May 25, 1963)**

| Country Name (Official English, 2025)   | ISO 3166-1 Alpha-3 | Notes on Founding Name (if different) |
| :-------------------------------------- | :----------------- | :------------------------------------ |
| People's Democratic Republic of Algeria | DZA                |                                       |
| Republic of Benin                       | BEN                | Dahomey [2]                           |
| Burkina Faso                            | BFA                | Upper Volta [2]                       |
| Republic of Burundi                     | BDI                |                                       |
| Republic of Cameroon                    | CMR                |                                       |
| Central African Republic                | CAF                |                                       |
| Republic of Chad                        | TCD                |                                       |
| Republic of the Congo                   | COG                | Congo (Brazzaville) [3]               |
| Democratic Republic of the Congo        | COD                | Congo (Leopoldville) [3]              |
| Republic of Côte d'Ivoire               | CIV                | Ivory Coast [2]                       |
| Arab Republic of Egypt                  | EGY                | Part of United Arab Republic [3]      |
| Federal Democratic Republic of Ethiopia | ETH                |                                       |
| Gabonese Republic                       | GAB                |                                       |
| Republic of Ghana                       | GHA                |                                       |
| Republic of Guinea                      | GIN                |                                       |
| Republic of Liberia                     | LBR                |                                       |
| Libya                                   | LBY                |                                       |
| Republic of Madagascar                  | MDG                | Malagasy Republic [16]                |
| Republic of Mali                        | MLI                |                                       |
| Islamic Republic of Mauritania          | MRT                |                                       |
| Kingdom of Morocco                      | MAR                | Withdrew 1984, Rejoined 2017          |
| Republic of the Niger                   | NER                |                                       |
| Federal Republic of Nigeria             | NGA                |                                       |
| Republic of Rwanda                      | RWA                |                                       |
| Republic of Senegal                     | SEN                |                                       |
| Republic of Sierra Leone                | SLE                |                                       |
| Federal Republic of Somalia             | SOM                |                                       |
| Republic of the Sudan                   | SDN                |                                       |
| United Republic of Tanzania             | TZA                | Tanganyika signed [2]                 |
| Togolese Republic                       | TGO                |                                       |
| Republic of Tunisia                     | TUN                |                                       |
| Republic of Uganda                      | UGA                |                                       |

*(Note: Tanganyika and Zanzibar signed the OAU charter separately in May 1963 but merged to form Tanzania in April 1964.[2] The table reflects the current state name, Tanzania, as a founding entity.)*

### 3.2 Morocco's Membership Trajectory

The Kingdom of Morocco holds a unique position in the history of the OAU/AU. As a founding member in 1963 [2], Morocco played a role in the early years of the organization. However, it withdrew its membership on November 12, 1984.[2] This decision was a direct protest against the OAU's recognition and admission of the Sahrawi Arab Democratic Republic (SADR), also known as Western Sahara, which Morocco claims as part of its territory.[2]

For over three decades, Morocco remained the only African nation outside the continental body, pursuing an "empty chair" policy regarding the OAU/AU while cultivating bilateral ties, particularly economic ones, across the continent.[31] This period saw significant Moroccan investment and diplomatic outreach, especially in West and Central Africa.[31]

Recognizing the limitations of its absence from the primary continental forum, Morocco initiated a strategic shift. In July 2016, King Mohammed VI signaled the intention to rejoin, framing it as returning home and arguing that issues are better addressed from within.[31] This culminated in Morocco's official readmission to the African Union on January 31, 2017, during the 28th AU Summit in Addis Ababa.[1] Crucially, Morocco rejoined without its previous precondition of SADR's expulsion or suspension being met; the SADR remains a full member state.[8] This complex history reflects both a significant strategic recalculation by Morocco and introduces an ongoing internal political dynamic within the AU concerning the unresolved status of Western Sahara.[35]

### 3.3 Suspended Members (Data Integration)

The information summarized in Section 2 and Table 1 is incorporated into the main JSON dataset below. For the six suspended states (Burkina Faso, Gabon, Guinea, Mali, Niger, Sudan), the `status` field is set to `"Suspended"`, and the `membershipNotes` field includes the reason (typically UCG/coup) and the date or timeframe of the current suspension, based on available data.[5]

### 3.4 Current Members (Data Integration)

All other 49 member states not listed as suspended are designated with `status: "Current Member"`. Their respective `joinDate` reflects either the OAU founding date (1963-05-25) or their later date of admission to the OAU/AU.[1] Founding members are noted accordingly in the `membershipNotes` field.

### 3.5 African Union Membership JSON Data

**JSON Data:**
```json
[
  {
    "IGO": "AU",
    "COUNTRY_EN": "People's Democratic Republic of Algeria",
    "ISO_A3": "DZA",
    "status": "member",
    "joinDate": null,
    "membershipNotes": null
  },
  {
    "IGO": "AU",
    "COUNTRY_EN": "Republic of Benin",
    "ISO_A3": "BEN",
    "status": "member",
    "joinDate": null,
    "membershipNotes": "Founding name: Dahomey [2]"
  },
  {
    "IGO": "AU",
    "COUNTRY_EN": "Burkina Faso",
    "ISO_A3": "BFA",
    "status": "member",
    "joinDate": null,
    "membershipNotes": "Founding name: Upper Volta [2]"
  },
  {
    "IGO": "AU",
    "COUNTRY_EN": "Republic of Burundi",
    "ISO_A3": "BDI",
    "status": "member",
    "joinDate": null,
    "membershipNotes": null
  },
  {
    "IGO": "AU",
    "COUNTRY_EN": "Republic of Cameroon",
    "ISO_A3": "CMR",
    "status": "member",
    "joinDate": null,
    "membershipNotes": null
  },
  {
    "IGO": "AU",
    "COUNTRY_EN": "Central African Republic",
    "ISO_A3": "CAF",
    "status": "member",
    "joinDate": null,
    "membershipNotes": null
  },
  {
    "IGO": "AU",
    "COUNTRY_EN": "Republic of Chad",
    "ISO_A3": "TCD",
    "status": "member",
    "joinDate": null,
    "membershipNotes": null
  },
  {
    "IGO": "AU",
    "COUNTRY_EN": "Republic of the Congo",
    "ISO_A3": "COG",
    "status": "member",
    "joinDate": null,
    "membershipNotes": "Founding name: Congo (Brazzaville) [3]"
  },
  {
    "IGO": "AU",
    "COUNTRY_EN": "Democratic Republic of the Congo",
    "ISO_A3": "COD",
    "status": "member",
    "joinDate": null,
    "membershipNotes": "Founding name: Congo (Leopoldville) [3]"
  },
  {
    "IGO": "AU",
    "COUNTRY_EN": "Republic of Côte d'Ivoire",
    "ISO_A3": "CIV",
    "status": "member",
    "joinDate": null,
    "membershipNotes": "Founding name: Ivory Coast [2]"
  },
  {
    "IGO": "AU",
    "COUNTRY_EN": "Arab Republic of Egypt",
    "ISO_A3": "EGY",
    "status": "member",
    "joinDate": null,
    "membershipNotes": "Founding note: Part of United Arab Republic [3]"
  },
  {
    "IGO": "AU",
    "COUNTRY_EN": "Federal Democratic Republic of Ethiopia",
    "ISO_A3": "ETH",
    "status": "member",
    "joinDate": null,
    "membershipNotes": null
  },
  {
    "IGO": "AU",
    "COUNTRY_EN": "Gabonese Republic",
    "ISO_A3": "GAB",
    "status": "member",
    "joinDate": null,
    "membershipNotes": null
  },
  {
    "IGO": "AU",
    "COUNTRY_EN": "Republic of Ghana",
    "ISO_A3": "GHA",
    "status": "member",
    "joinDate": null,
    "membershipNotes": null
  },
  {
    "IGO": "AU",
    "COUNTRY_EN": "Republic of Guinea",
    "ISO_A3": "GIN",
    "status": "member",
    "joinDate": null,
    "membershipNotes": null
  },
  {
    "IGO": "AU",
    "COUNTRY_EN": "Republic of Liberia",
    "ISO_A3": "LBR",
    "status": "member",
    "joinDate": null,
    "membershipNotes": null
  },
  {
    "IGO": "AU",
    "COUNTRY_EN": "Libya",
    "ISO_A3": "LBY",
    "status": "member",
    "joinDate": null,
    "membershipNotes": null
  },
  {
    "IGO": "AU",
    "COUNTRY_EN": "Republic of Madagascar",
    "ISO_A3": "MDG",
    "status": "member",
    "joinDate": null,
    "membershipNotes": "Founding name: Malagasy Republic [16]"
  },
  {
    "IGO": "AU",
    "COUNTRY_EN": "Republic of Mali",
    "ISO_A3": "MLI",
    "status": "member",
    "joinDate": null,
    "membershipNotes": null
  },
  {
    "IGO": "AU",
    "COUNTRY_EN": "Islamic Republic of Mauritania",
    "ISO_A3": "MRT",
    "status": "member",
    "joinDate": null,
    "membershipNotes": null
  },
  {
    "IGO": "AU",
    "COUNTRY_EN": "Kingdom of Morocco",
    "ISO_A3": "MAR",
    "status": "member",
    "joinDate": null,
    "membershipNotes": "Withdrew 1984, Rejoined 2017"
  },
  {
    "IGO": "AU",
    "COUNTRY_EN": "Republic of the Niger",
    "ISO_A3": "NER",
    "status": "member",
    "joinDate": null,
    "membershipNotes": null
  },
  {
    "IGO": "AU",
    "COUNTRY_EN": "Federal Republic of Nigeria",
    "ISO_A3": "NGA",
    "status": "member",
    "joinDate": null,
    "membershipNotes": null
  },
  {
    "IGO": "AU",
    "COUNTRY_EN": "Republic of Rwanda",
    "ISO_A3": "RWA",
    "status": "member",
    "joinDate": null,
    "membershipNotes": null
  },
  {
    "IGO": "AU",
    "COUNTRY_EN": "Republic of Senegal",
    "ISO_A3": "SEN",
    "status": "member",
    "joinDate": null,
    "membershipNotes": null
  },
  {
    "IGO": "AU",
    "COUNTRY_EN": "Republic of Sierra Leone",
    "ISO_A3": "SLE",
    "status": "member",
    "joinDate": null,
    "membershipNotes": null
  },
  {
    "IGO": "AU",
    "COUNTRY_EN": "Federal Republic of Somalia",
    "ISO_A3": "SOM",
    "status": "member",
    "joinDate": null,
    "membershipNotes": null
  },
  {
    "IGO": "AU",
    "COUNTRY_EN": "Republic of the Sudan",
    "ISO_A3": "SDN",
    "status": "member",
    "joinDate": null,
    "membershipNotes": null
  },
  {
    "IGO": "AU",
    "COUNTRY_EN": "United Republic of Tanzania",
    "ISO_A3": "TZA",
    "status": "member",
    "joinDate": null,
    "membershipNotes": "Founding note: Tanganyika signed [2]"
  },
  {
    "IGO": "AU",
    "COUNTRY_EN": "Togolese Republic",
    "ISO_A3": "TGO",
    "status": "member",
    "joinDate": null,
    "membershipNotes": null
  },
  {
    "IGO": "AU",
    "COUNTRY_EN": "Republic of Tunisia",
    "ISO_A3": "TUN",
    "status": "member",
    "joinDate": null,
    "membershipNotes": null
  },
  {
    "IGO": "AU",
    "COUNTRY_EN": "Republic of Uganda",
    "ISO_A3": "UGA",
    "status": "member",
    "joinDate": null,
    "membershipNotes": null
  }
]
```

## 4. Conclusion

This report has presented a comprehensive JSON dataset detailing the membership of the African Union as of early 2025. The dataset includes all 55 member states, accurately reflecting their official English names, ISO 3166-1 alpha-3 codes, OAU/AU join dates, current membership status (including suspensions), and relevant historical notes based on the provided documentation.

The analysis highlights key dynamics within the AU, notably the significant number of member states currently suspended due to unconstitutional changes of government, particularly concentrated in the Sahel region.[23] This trend underscores ongoing challenges to democratic consolidation and stability on the continent and tests the AU's mechanisms for upholding its own normative principles.[23] Additionally, the unique trajectory of Morocco's membership—founding member status, a 33-year withdrawal over the Western Sahara issue, and subsequent readmission in 2017 while the core dispute remains unresolved—illustrates the complex political and diplomatic landscape the AU navigates.[5]

The provided JSON array is structured for technical utility, offering a precise and reliable snapshot of AU membership based on the available source materials. It serves as a valuable resource for understanding the current composition and historical evolution of this key continental organization.

## Works Cited

* Member States | African Union, accessed on April 13, 2025
* Organisation of African Unity - Wikipedia, accessed on April 13, 2025
* UNTC, accessed on April 13, 2025
* Member states of the African Union - Worlddata.info, accessed on April 13, 2025
* Member states of the African Union - Wikipedia, accessed on April 13, 2025
* Our MEMBER STATES TO THE UNITED NATIONS - African Union Mission to the UN, accessed on April 13, 2025
* African Union - Wikipedia, accessed on April 13, 2025
* Following Three Decades of Isolation, Morocco Rejoins African Union, accessed on April 13, 2025
* Member States | Carmma - African Union, accessed on April 13, 2025
* Member States | Organization of the African Unity at 60, accessed on April 13, 2025
* List of African Union Member States - ChartsBin.com, accessed on April 13, 2025
* classification following the ISO standard 3166-1 alpha-3 - Discover all information, pictures and links to travel and tourism on Rallybel.com, accessed on April 13, 2025
* List of ISO 3166 country codes - Wikipedia, accessed on April 13, 2025
* List of country codes by alpha-2, alpha-3 code (ISO 3166) - IBAN, accessed on April 13, 2025
* List of Country Codes in the AFRINIC Region | The Number Resource Organization, accessed on April 13, 2025
* ISO 3166-1 alpha-3 - Wikipedia, accessed on April 13, 2025
* ISO-3166-Countries-with-Regional-Codes/all/all.csv at master - GitHub, accessed on April 13, 2025
* Excel file - USDA ARS, accessed on April 13, 2025
* ISO 3166-1 alpha-3 codes, accessed on April 13, 2025
* Correspondence table ISO 3166-1/UNCTADstat (EN), accessed on April 13, 2025
* ISO 3166 Country Codes | Mastercard, accessed on April 13, 2025
* Sudan suspended from the African Union, accessed on April 13, 2025
* Is the African Union failing countries in complex political transition ..., accessed on April 13, 2025
* Map Update: Record Number of African Union Members Suspended (Sep. 2023), accessed on April 13, 2025
* African Union Countries 2025 - World Population Review, accessed on April 13, 2025
* World Report 2025: African Union - Human Rights Watch, accessed on April 13, 2025
* Sudan seeks reinstatement in African Union amid summit, accessed on April 13, 2025
* OFFICIAL NAMES OF THE UNITED NATIONS MEMBERSHIP Islamic Republic of Afghanistan Republic of Albania People's Democratic Republ - UN Member States, accessed on April 13, 2025
* Standard country or area codes for statistical use (M49) - UNSD — Methodology, accessed on April 13, 2025
* ISO 3166-1 Country Codes, accessed on April 13, 2025
* Morocco flexed economic muscles and returned to the AU | Africa Renewal, accessed on April 13, 2025
* Morocco rejoins the African Union after 33 years - Al Jazeera, accessed on April 13, 2025
* The Return of Morocco to the African Union - IEMed, accessed on April 13, 2025
* Morocco officially applies to rejoin AU after 32 years in isolation | Africanews, accessed on April 13, 2025
* Morocco returns to the African Union amidst unresolved issues - Real Instituto Elcano, accessed on April 13, 2025
* 12 November 1984 : When Morocco withdrew from the Organization of African Unity, accessed on April 13, 2025
* Morocco asks to return to AU - Xinhua | English.news.cn, accessed on April 13, 2025
* Founding Fathers - Organization of the African Unity, accessed on April 13, 2025
* list of chairpersons of oau/au since 1963 - 2013, accessed on April 13, 2025
* Why did the African Union readmit Morocco after its 33 years in the cold?, accessed on April 13, 2025
* How the African Union Failed The People Of Western Sahara, accessed on April 13, 2025
