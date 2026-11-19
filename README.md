# Health Map: Senegal

### High-resolution population and health intelligence for local health planning

**Health Map Senegal** addresses spatial health inequalities by providing high-resolution, disaggregated population and health information to support **evidence-based health planning, policy formulation, and resource allocation in Senegal**.

The project integrates **population modelling, vaccination coverage estimation, identification of under-vaccinated and zero-dose children, healthcare accessibility analysis, and demographic and socioeconomic profiling** within an interactive decision-support framework.

Population estimates will be produced at **100 m spatial resolution** using Random Forest machine-learning approaches. These estimates will provide a high-resolution population denominator for subsequent health analyses, including Bayesian modelling of vaccination coverage and estimation of populations with incomplete or no routine immunisation.

Geospatial accessibility analysis will estimate travel times to healthcare facilities and identify populations experiencing geographical barriers to healthcare. The resulting population, vaccination, accessibility, demographic, and socioeconomic indicators will be integrated into **health district profiles** and an interactive **R Shiny dashboard**.

---

## Project at a glance

|  |  |
|---|---|
| **Geographic focus** | Senegal |
| **Population resolution** | 100 m |
| **Core methods** | Random Forest, Bayesian spatial modelling, geospatial accessibility analysis |
| **Dashboard platform** | R Shiny |
| **Funding** | Gates Foundation |
| **Project period** | May 2026 – July 2027 |

---

# Analytical framework

The project is organised around **six interconnected analytical components**, moving from high-resolution population estimation to an interactive system for health monitoring and decision support.

### 1. Population modelling
High-resolution estimation of population distributions and health-relevant demographic groups.

### 2. Modelling vaccination coverage
Bayesian spatial modelling of routine childhood vaccination coverage and associated uncertainty.

### 3. Estimating unvaccinated children
Identification and quantification of under-vaccinated and zero-dose children.

### 4. Accessibility to healthcare services
Assessment of travel time and geographical accessibility to healthcare facilities.

### 5. Health and demographic profiles
Integration of demographic, socioeconomic, vaccination, and accessibility indicators.

### 6. Interactive dashboard
Interactive exploration and comparison of indicators across health districts and medical regions.

---

# 1. Population modelling

High-resolution population modelling provides the **demographic foundation** for the Health Map Senegal analytical framework.

## Population totals

Estimation of total population counts and demographic aggregates across administrative and health reporting units.

## Age and sex breakdown

Population estimates will be disaggregated into health-relevant age and sex groups, including:

- Children under 1 year
- Children under 5 years
- Women aged 15–49 years
- Other age- and sex-specific population groups relevant to health planning

The resulting estimates will be available at **100 m spatial resolution**, enabling detailed assessment of population distributions and concentrations.

---

# 2. Modelling vaccination coverage

Bayesian spatial models will be used to estimate geographical variation in routine childhood vaccination coverage and associated uncertainty.

## Vaccination coverage

Coverage estimates will include:

- **DTP1**
- **DTP2**
- **DTP3**
- **MCV1**

These indicators represent the estimated proportion of the eligible child population receiving each vaccine dose.

## DTP1–DTP3 drop-out rate

The drop-out rate represents the proportion of children who receive DTP1 but do not complete the vaccination sequence through DTP3.

This indicator helps identify locations where children enter the vaccination programme but do not complete the recommended vaccination schedule.

## Probability of attaining 80% coverage

The modelling framework will estimate the probability that vaccination coverage reaches or exceeds **80%** within a given geographic area.

This probabilistic measure allows geographic patterns in vaccination coverage to be interpreted alongside model uncertainty.

---

# 3. Estimating unvaccinated children

High-resolution population estimates will be combined with modelled vaccination coverage to estimate the **number and spatial distribution of children who remain insufficiently vaccinated**.

## Under-vaccinated children

Estimated number of children with incomplete vaccination schedules and missing one or more essential vaccine doses.

## Unvaccinated and zero-dose children

Estimated number of children who have not received routine immunisation.

These estimates will support the identification of **zero-dose populations** and geographic areas where additional vaccination interventions may be required.

District-level summaries will translate these estimates into information that can support **programme planning, geographic prioritisation, and resource allocation**.

---

# 4. Accessibility to healthcare services

Spatial accessibility analysis will assess geographical barriers between populations and healthcare infrastructure.

## Location of health facilities

Geographic locations of healthcare facilities will be used to characterise the spatial distribution of health services, including:

- Hospitals
- Health centres
- Health posts
- Primary healthcare facilities

## Travel-time isochrones

Travel-time isochrones will represent accessibility from residential areas to healthcare facilities.

Example thresholds include:

- **15 minutes**
- **20 minutes**
- **25 minutes**
- **30 minutes**
- **45 minutes**

These travel-time zones will help identify populations experiencing relatively limited physical access to healthcare services.

## Population within each isochrone

High-resolution population estimates will be integrated with travel-time isochrones to estimate the number of people living within different healthcare accessibility thresholds.

This allows accessibility to be interpreted not only geographically but also in terms of the **population affected**.

## Accessibility index

A composite accessibility indicator will quantify geographical access to healthcare services using relevant spatial determinants, including:

- Travel time
- Transport connectivity
- Healthcare facility availability

---

# 5. Health and demographic profiles

Population, vaccination, accessibility, demographic, and socioeconomic information will be integrated to develop comprehensive profiles for health planning.

## Sociodemographic characteristics

Key demographic indicators may include:

- Median age
- Dependency ratio
- Proportion of women of childbearing age
- Proportion of children
- Proportion of adolescents
- Proportion of adults
- Proportion of older people
- Literacy rate

Together, these indicators describe **population age structure, dependency burden, reproductive-age populations, and educational characteristics** relevant to health planning.

## Socioeconomic characteristics

Socioeconomic profiles will incorporate indicators related to living conditions and access to basic services, subject to data availability.

Potential indicators include:

- Access to improved water services
- Access to sanitation
- Access to electricity
- Poverty levels
- Multidimensional poverty indicators

Combining demographic and socioeconomic characteristics with population and health indicators will support the identification of areas experiencing **multiple dimensions of vulnerability**.

---

# 6. Interactive dashboard

An interactive **R Shiny dashboard** will bring together the major outputs of Health Map Senegal within a single environment for **data exploration, comparison, monitoring, and decision support**.

## Summaries by medical region

Population, vaccination, accessibility, demographic, and socioeconomic indicators will be summarised by medical region to support regional monitoring and comparison.

## Summaries by health district

Detailed health district summaries will support local analysis, planning, and identification of priority areas.

## Thematic exploration

Indicators will be organised into major analytical themes:

- **Population**
- **Vaccination coverage**
- **Under-vaccinated and zero-dose children**
- **Healthcare accessibility**
- **Demographic characteristics**
- **Socioeconomic characteristics**

## Customised queries

Users will be able to select specific indicators and geographic areas to generate targeted outputs for health analysis and planning.

The dashboard will translate complex spatial population and health datasets into **accessible and actionable information for decision-makers**.

---

# Project workflow

**High-resolution population modelling**

↓

**Vaccination coverage modelling**

↓

**Estimation of under-vaccinated and zero-dose children**

↓

**Healthcare accessibility and travel-time modelling**

↓

**Health, demographic, and socioeconomic profiling**

↓

**Health district and medical region summaries**

↓

**Interactive monitoring and decision-support dashboard**

---

# Project outputs

| Output | Description |
|---|---|
| **High-resolution population estimates** | 100 m population estimates for the total population and specific age- and sex-disaggregated groups |
| **Vaccination coverage models** | Spatial estimates and uncertainty for DTP1, DTP2, and DTP3 vaccination coverage |
| **Zero-dose estimates** | District-level estimates of under-vaccinated and unvaccinated children |
| **Travel-time isochrones** | Spatial accessibility zones representing travel times to healthcare facilities |
| **Accessibility analysis** | Population-based assessment of geographical inequalities in access to healthcare |
| **Demographic and health profiles** | Integrated profiles combining population, vaccination, accessibility, demographic, and socioeconomic characteristics |
| **Interactive monitoring dashboard** | R Shiny dashboard for interactive exploration, comparison, and customised analysis |

---

# Geographic levels of analysis

Health Map Senegal will provide information across multiple spatial scales, allowing high-resolution analytical outputs to be translated into information relevant to health-system planning.

| Geographic level | Primary application |
|---|---|
| **100 m grid** | High-resolution population and spatial health analysis |
| **Health district** | Local health planning and prioritisation |
| **Medical region** | Regional monitoring and comparison |
| **National** | Strategic overview and national-level assessment |

---

# From data to decision-making

Health Map Senegal is designed to support evidence-based health planning by enabling users to:

- Identify where populations are concentrated
- Understand the demographic composition of populations
- Examine spatial variation in vaccination coverage
- Identify under-vaccinated and zero-dose populations
- Evaluate geographical accessibility to healthcare facilities
- Identify populations facing multiple health and socioeconomic vulnerabilities
- Compare indicators across health districts and medical regions
- Support geographic prioritisation of health interventions and resources

The overall objective is to transform complex geospatial population and health information into **clear, locally relevant, and actionable evidence for health planning and decision-making**.

---

# Project team

### Project Lead

**Assane Gadiaga**

### Team

- **Edson Utazi**
- **Somnath Chaudhuri**
- **Kathryn Baxter**
- **Jess Espey**
- **Andrew Tatem**
- **Sada Saxton**

---

# Project information

|  |  |
|---|---|
| **Project** | Health Map: Senegal |
| **Lead organisation** | WorldPop |
| **Funding** | Gates Foundation |
| **Start** | May 2026 |
| **Completion** | July 2027 |
| **Population mapping resolution** | 100 m |
| **Dashboard platform** | R Shiny |
| **Geographic focus** | Senegal |

---

# More information

For further information about the project, visit:

**[Health Map Senegal – WorldPop](https://www.worldpop.org/current-projects/health-map-senegal/)**

---

### Health Map: Senegal

**High-resolution population and health intelligence for evidence-based local health planning**

**WorldPop | University of Southampton**