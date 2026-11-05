# Kosovo: rent and landlord rules index 2026

Open, source-linked data on residential rent and landlord obligations in Kosovo: deposits, rent increases, termination notice, lease terms and landlord duties, with a primary-source link for every value.

- Version: 1.0
- Facts checked: 2026-11-05
- Author: Leonid Gorok
- Project site: [izirento.com](https://izirento.com)
- Related: [UK Rent & Landlord Obligations Index 2026](https://izirento.com/en-gb/research/data/uk-rents-and-landlord-duties-index), [UK repository](https://github.com/izirento/izirento-uk-rent-index), [catalog of country repositories](https://github.com/izirento/izirento-rent-index-international)
- Licence: CC BY 4.0 (see [`LICENSE`](LICENSE) and [`LICENSE.md`](LICENSE.md)). Laws and official statistics are cited, not copied.

## Disclaimer

The data is provided as is, without any liability. We only collect and organise what the official sources publish. Laws change and local rules differ: always check each value against the primary source linked next to it before relying on it. This is information, not legal advice.

## Scope and limits

Law No. 04/L-077 on Obligational Relationships, Part VIII lease contract (qiraja), Articles 585-614. Special laws on social or public housing are not covered.

## Key facts

| Topic | Field | Value | Source |
| --- | --- | --- | --- |
| tenancy_law | Main law | Law No. 04/L-077 on Obligational Relationships (2012), Part VIII lease contract, Articles 585-614. | [Gazeta Zyrtare e Republikës së Kosovës (Official Gazette of the Republic of Kosovo)](https://gzk.rks-gov.net/ActDetail.aspx?ActID=2828) |
| rent | Rent payment | Rent is paid on the dates set by the contract or law; if not agreed and there is no local practice, rent is paid every six months for leases of one or more years, or at the end of a shorter lease (Art. 600). | [Gazeta Zyrtare e Republikës së Kosovës (Official Gazette of the Republic of Kosovo)](https://gzk.rks-gov.net/ActDetail.aspx?ActID=2828) |
| termination | Termination for non-payment | The lessor may terminate if the tenant does not pay rent within 15 days after being called on to pay; the contract stays in force if the tenant pays before the termination notice is delivered (Art. 601). | [Gazeta Zyrtare e Republikës së Kosovës (Official Gazette of the Republic of Kosovo)](https://gzk.rks-gov.net/ActDetail.aspx?ActID=2828) |
| end_of_tenancy | Return of the property | The tenant must return the property undamaged where it was handed over, but is not liable for wear from ordinary use or ageing (Art. 602). | [Gazeta Zyrtare e Republikës së Kosovës (Official Gazette of the Republic of Kosovo)](https://gzk.rks-gov.net/ActDetail.aspx?ActID=2828) |
| sale | Sale of rented property | If the rented property is transferred after handover, the acquirer takes the lessor's place and cannot demand handover before the agreed lease term (or the notice period) ends (Art. 606). | [Gazeta Zyrtare e Republikës së Kosovës (Official Gazette of the Republic of Kosovo)](https://gzk.rks-gov.net/ActDetail.aspx?ActID=2828) |
| end_of_tenancy | Fixed-term lease | A fixed-term lease ends when the term expires; if the tenant keeps using the property without the lessor objecting, a new open-ended lease on the same terms is deemed concluded (Arts. 610-611). | [Gazeta Zyrtare e Republikës së Kosovës (Official Gazette of the Republic of Kosovo)](https://gzk.rks-gov.net/ActDetail.aspx?ActID=2828) |
| notice | Notice period | An open-ended lease ends by notice; if no notice period is set by contract, law or local custom, it is eight days. The tenant may terminate without notice if the property endangers health (Art. 612). | [Gazeta Zyrtare e Republikës së Kosovës (Official Gazette of the Republic of Kosovo)](https://gzk.rks-gov.net/ActDetail.aspx?ActID=2828) |
| death | Death of a party | On the death of the tenant or the lessor the lease continues with the heirs unless agreed otherwise (Art. 614). | [Gazeta Zyrtare e Republikës së Kosovës (Official Gazette of the Republic of Kosovo)](https://gzk.rks-gov.net/ActDetail.aspx?ActID=2828) |

## Shqip

**Kosova.** Të dhëna të hapura për qiranë sipas Ligjit Nr. 04/L-077 për Marrëdhëniet e Detyrimeve: pagesa e qirasë, denoncimi, kthimi i sendit, tjetërsimi dhe shuarja, me lidhje me burimin zyrtar për çdo vlerë.

*Të dhënat jepen ashtu siç janë, pa asnjë përgjegjësi. Ne vetëm rendisim atë që publikojnë burimet zyrtare. Kontrolloni çdo vlerë në burimin parësor.*

Details: see the table above and `sources.md`.

## Files

| File | Content |
| --- | --- |
| `kosovo_rent_landlord_rules_2026.csv` | One row per fact, with source URL, optional cross-check URL and check date |
| `sources.md` | Every field with publisher and links, plus fields left empty and notes |
| `LICENSE`, `LICENSE.md` | CC BY 4.0 legal code; attribution and source statements |
| `CITATION.cff` | Citation metadata |

## Field dictionary

| Field | Meaning |
| --- | --- |
| `country_code, country` | Code and name |
| `topic` | Group: tenancy_law, deposit, rent_increase, rent_control, termination, contract_form, registration, rent_payment, landlord_duties, rent_level_change and similar |
| `field` | Specific item |
| `value` | The fact in our own words; empty where no verified figure was found |
| `source_publisher` | Body that publishes the source |
| `source_url` | Link to the primary source |
| `cross_check_url` | Second source actually read, if any |
| `checked_on` | Date the source was read |
| `note` | Scope, language of the source or caveat |

## Method

1. Each value comes from a primary source: the statute on the official legal portal, a government service page or a statistics office dataset. Where a second official or institutional page confirms it, that link is in `cross_check_url`.
2. Values are written in our own words. Nothing is estimated or calculated; where no verified value exists the cell is empty and the reason is given in `sources.md`.
3. Where a statute is translated or summarised from another language, the original-language text prevails.

## Citation

Gorok, L. (2026). *Kosovo: rent and landlord rules index 2026* (Version 1.0) [Data set]. IziRento. https://github.com/izirento/izirento-kosovo-rent-index

## Attribution

Sources are listed in `sources.md` and in `LICENSE.md`.
