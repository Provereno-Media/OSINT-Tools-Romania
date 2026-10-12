# OSINT-Tools-Romania
<img src="https://flagcdn.com/w320/ro.png" alt="Romania_FLAG"/>
A list of OSINT resources and tools that may be useful to you when conducting investigations related to Romania. Most of the resources and tools has versions in Romanian; some in English (and Hungarian for parts of the Official Gazette). Access to the beneficial-ownership register kept by the Trade Register Office (ONRC) has been limited since May 2025 (Law 86/2025 amending Law 129/2019, following CJEU judgment C-37/20 and C-601/20 of 22 November 2022): applicants must show a legitimate interest, so UBO data is not openly searchable. The public platforms of the cadastre agency ANCPI (Geoportal, owners' register) have been offline since a cyberattack in July 2026; as of late September 2026 the e-Terra system was back for professionals only. Check its status before relying on cadastral data. Many Romanian state websites block automated access, so open links in a normal browser.

**Last Updated:** 2026-10-12

## Contributions
Feel free to join this project — [OSINT For Countries V2.0](https://github.com/Provereno-Media/OSINT-for-countries-V2.0)

## Table of contents:
 - [Open Data portals](#open-data-portals)
 - [Legal Entities](#legal-entities)
 - [Cadastral and other Maps](#maps)
 - [Vehicles](#vehicles)
 - [People, phones, social etc.](#people)
 - [Public procurements](#public-procurement)
 - [WHOIS](#whois)

## Open Data portals
(Country Open Data, Stock Exchange, Courts)
- [data.gov.ro (National Open Data Portal)](https://data.gov.ro/) — national CKAN open data portal run by the General Secretariat of the Government; datasets from public institutions, including companies' annual financial statements; search by keyword, organization. *Lang: RO.* 🏛️
- [TEMPO Online (National Institute of Statistics database)](http://statistici.insse.ro:8077/tempo-online/) — official statistics database of the Institutul Național de Statistică (INS): time series by topic and territorial level, downloadable tables. *Lang: RO.* 🏛️
- [Portalul instanțelor de judecată (Courts Portal)](https://portal.just.ro/) — Ministry of Justice portal for Romanian courts (courts of appeal, tribunals, local courts): case search (dosare), hearing dates and panels, summons by publication, judicial atlas. Search may be unavailable during maintenance. *Lang: RO.* 🏛️
- [ReJust (Superior Council of Magistracy case-law portal)](https://www.rejust.ro/) — free portal of the Superior Council of Magistracy (CSM) with anonymized decisions of local courts, tribunals and courts of appeal; filter by solution, document type, court level; related documents from the same case. *Lang: RO.* 🏛️
- [Înalta Curte de Casație și Justiție (High Court of Cassation and Justice)](https://www.scj.ro/) — supreme court website with case files (Dosare), hearing lists and case-law (Jurisprudență) sections. *Lang: RO.* 🏛️
- [Monitorul Oficial – e-monitor (Official Gazette, free electronic access)](https://monitoruloficial.ro/e-monitor/) — free PDFs of Part I (2000 onward; Hungarian edition 2008 onward) and Part II (2000 onward); Parts III–VII, including Part IV company notices, are readable for 10 days after publication only. *Lang: RO, HU.* 🏛️
- [Bursa de Valori București (Bucharest Stock Exchange)](https://www.bvb.ro/) — listed issuers on the Main and AeRO markets, current reports, financial results, indices and trading statistics. *Lang: RO.*

## Legal Entities
- [Portal ONRC – RECOM (Trade Register Office online services)](https://myportal.onrc.ro/home) — national trade register portal; free RECOM search by company name, registration number, unique registration code (CUI) or county returns name, legal form, seat, EUID, status, legal representatives; certificates and detailed reports are paid. *Lang: RO.* 🏛️ ⚠️ 💲 Freemium: basic RECOM data free with an account; certificates and extended reports paid
- [Buletinul Procedurilor de Insolvență (Insolvency Proceedings Bulletin)](http://www.bpi.ro/) — official insolvency bulletin kept by ONRC; free searches "Persoane publicate în BPI" (name, CUI, registration no., court case, procedure type) and "Sumar număr BPI" through the ONRC portal; full procedural acts by subscription. *Lang: RO.* 🏛️ ⚠️ 💲 Freemium: summary searches free with an account; full bulletin text by subscription
- [Registrul persoanelor impozabile înregistrate în scopuri de TVA (ANAF VAT Register)](https://www.anaf.ro/RegistruTVA/) — tax authority (ANAF) lookup of VAT registration under Art. 316 of the Fiscal Code; search by tax identification code (CUI), captcha. *Lang: RO.* 🏛️
- [Termene.ro](https://termene.ro/) — company intelligence platform; public profiles show CUI, trade register number, seat, status (e.g. insolvency/reorganisation), CAEN code, turnover/profit/employees and OSIM trademarks; search by name or CUI. *Lang: RO.* 💲 Freemium: basic profile without login; a free account unlocks shareholders and administrators, court and BPI cases, balance sheets and procurement data; full report paid (181.50 RON)
- [RisCo](https://www.risco.ro/) — company verification site; profiles give CUI, registration number, EUID, address, CAEN code and a 10-year table of turnover, profit, debts, assets, equity and employees. *Lang: RO.* 💲 Freemium: identifiers and financial table free without login; contacts, administrators, risk profile with a client account or paid
- [TopFirme](https://www.topfirme.com/) — free company profiles with CUI, registration number, address, CAEN code and yearly financial indicators (1999 onward), plus rankings by turnover, profit, employees, county and activity code; search by name. *Lang: RO.*

## Maps
(Cadastral Maps if available, GIS etc.)
- [Repertoriul Arheologic Național – RAN (National Archaeological Record)](https://ran.cimec.ro/) — National Heritage Institute database of 29,000+ archaeological sites; search by county, locality, period; each record links to a map viewer. *Lang: RO.* 🏛️
- [GIS Primăria Cluj-Napoca (Cluj-Napoca City Hall public GIS)](https://gis.primariaclujnapoca.ro/Public/) — municipal map viewer with urban planning layers (approved PUZ/PUD plans, urbanism certificates and building permits), coordinate search and report tools. *Lang: RO, EN.* 🏛️
- [Inspectorul Pădurii (Forest Inspector)](https://inspectorulpadurii.ro/) — Ministry of Environment app mapping timber transports (recent permits) and logging authorizations (APV); search transport permits by vehicle plate number, permit code or APV. *Lang: RO.* 🏛️
- [geo-spatial.org](https://www.geo-spatial.org/) — Romanian open geodata community: interactive maps and dashboards, downloadable open datasets and a GeoNetwork data catalogue. *Lang: RO.*
- [Copernicus Browser](https://browser.dataspace.copernicus.eu/) — browse and download full-resolution imagery from all Copernicus satellite missions, with time ranges, visualisations and timelapses. *Lang: EN.*

## Vehicles

### Land
- [Verificare ITP – Registrul Auto Român (Roadworthiness inspection check)](https://prog.rarom.ro/rarpol/rarpol.asp) — RAR check of whether a valid periodic technical inspection (ITP) is recorded; search by VIN (17 characters) or vehicle identity card (C.I.V.) series, captcha. *Lang: RO.* 🏛️
- [Campanii de rechemare – RAR (Vehicle recall campaigns)](https://www.rarom.ro/?page_id=300784) — RAR list of manufacturer recall campaigns by brand, with links to brand pages and manufacturers' VIN recall lookups. *Lang: RO.* 🏛️

### Maritime
- [VesselFinder](https://www.vesselfinder.com/) — free AIS vessel tracking with real-time ship positions, useful for Constanța and the Danube ports. *Lang: EN.*
- [Equasis](https://www.equasis.org) — free maritime safety database of ships and companies (incl. Romanian-flagged and Constanța-calling vessels); ship and company search requires free registration. *Lang: EN.* ⚠️

### Aviation
- [București Airports – Zboruri (Bucharest Airports flight board)](https://bucharestairports.ro/) — arrivals and departures for Henri Coandă (OTP) and Băneasa – Aurel Vlaicu (BBU) airports; filters by airline, status, destination; search by date and flight number (archive from 26 Oct 2025). *Lang: RO.*
- [Flightradar24](https://www.flightradar24.com/) — live flight tracking map with flight status and airport information. *Lang: EN.* 💲 Freemium: live map free; extra features with subscription plans (7-day trial)

## People
(Names, Addresses, Yellow Pages, White Pages etc.)
- [Declarații de avere și interese – ANI (Asset and Interest Declarations)](https://declaratii.integritate.eu/) — National Integrity Agency portal for searching the asset and interest declarations of public officials. *Lang: RO.* 🏛️
- [Camera Deputaților (Chamber of Deputies)](https://www.cdep.ro/) — deputies listed alphabetically and by constituency, their asset and interest declarations, electronic voting records and legislative process tracking. *Lang: RO, EN, FR.* 🏛️
- [Senatul României (Romanian Senate)](https://www.senat.ro/) — parliamentary structures, monthly expenses of senators and salary transparency pages. *Lang: RO.* 🏛️
- [BPI – Persoane fizice (Insolvency Bulletin for individuals)](https://bpipf.onrc.ro/bpi_fo/) — ONRC section on personal insolvency proceedings: debtor name, personal numeric code (CNP), domicile, administrator/liquidator and procedural acts. *Lang: RO.* 🏛️ ⚠️
- [Uniunea Națională a Barourilor din România – UNBR (National Union of Bar Associations)](https://www.unbr.ro/) — official site of the Romanian bar; "Tabloul avocaților" menu links to the national lawyer search (Caut avocat) and the IFEP lawyers' panel. *Lang: RO.*
- Try [OSINT Industries](https://app.osint.industries) and don't forget about the [Digital Profiler's Toolkit](https://github.com/paulpogoda/Digital-Profiler-s-Toolkit)

## Public procurement
- [SEAP / e-licitatie.ro (Electronic Public Procurement System)](https://www.e-licitatie.ro/pub) — national electronic public procurement system (SEAP/SICAP); public area for procurement notices and award information. *Lang: RO.* 🏛️
- [Curtea de Conturi a României (Romanian Court of Accounts)](https://www.curteadeconturi.ro) — supreme audit institution: annual public reports and audit reports on public-sector entities and spending (incl. own-initiative audits). *Lang: RO.* 🏛️
- [TED – Tenders Electronic Daily](https://ted.europa.eu/en/) — official EU procurement notices portal (Supplement to the EU Official Journal), including above-threshold Romanian tenders; browse by place of performance, advanced and expert search. *Lang: EN.*
- [Kohesio (European Commission)](https://kohesio.ec.europa.eu/en/projects) — EU cohesion-policy project database (2.1M+ projects EU-wide, incl. Romanian projects): project, budget, period, country/priority tags; open data downloads. *Lang: EN.*
- [OCP Data Registry – Romania: OpenTender](https://data.open-contracting.org/en/publication/75) — free bulk OCDS dataset of Romanian procurement 2007–2024 (TED + national data.gov.ro data): ~448k tenders, ~1M awards, buyers and suppliers; JSON/CSV/XLSX, weekly source updates, CC BY-NC-SA 4.0. *Lang: EN.*

## WHOIS
- [RoTLD WHOIS (.ro registry)](https://www.rotld.ro/whois/) — official WHOIS lookup of the .ro registry operated by ICI Bucharest; query by domain name. *Lang: RO.* 🏛️
- [RoTLD – Parteneri (.ro registrar partners list)](https://www.rotld.ro/registrar-list/) — list of RoTLD partner companies (registrars/resellers) with addresses and websites; useful to identify who registered a .ro domain. *Lang: RO.* 🏛️
- [ANCOM – Caută furnizorul (Provider registers)](https://www.ancom.ro/category/cauta-furnizorul/) — entry point to the telecom regulator's registers of authorised electronic-communications and postal providers and numbering-resource holders (identify ISPs, hosting/telecom operators, phone-number blocks). *Lang: RO.* 🏛️
- [ICANN Lookup](https://lookup.icann.org/en) — registration data lookup for domain names and Internet number resources. *Lang: EN.*
- [IANA – .ro delegation record](https://www.iana.org/domains/root/db/ro.html) — root-zone record for .ro: registry manager (ICI Bucharest), admin/tech contacts, WHOIS server whois.rotld.ro (no RDAP listed), last updated 2026-09-28. *Lang: EN.*

---

## Contributing

To contribute to this repository:
1. Verify all links are working and accessible
2. Provide accurate descriptions of database contents
3. Follow the 7-category structure
4. Include official government sources when available
5. Submit pull requests with detailed change descriptions

## Legal Disclaimer

This repository is for educational and legitimate investigative purposes only. Users are responsible for:
- Complying with all applicable laws and regulations
- Respecting terms of service for all databases and tools
- Using information ethically and responsibly
- Obtaining proper authorization when required

The information provided is for informational purposes only and should not be considered legal advice.

---

**Repository maintained by the [OSINT-for-Countries-V2.0 community](https://github.com/Provereno-Media/OSINT-for-countries-V2.0)**
