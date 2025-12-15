# Digital Marketing Portfolio - Mert Ali Erün

## About Me
I'm a digital marketing professional specializing in marketing automation and product marketing for B2B and SaaS companies. Over the past six years, I've built and executed multi-market campaigns, managed complex technical integrations, and led cross-functional projects for global enterprises including DuPont, Wolters Kluwer, Unilever, Shimano, and JAMS across EMEA, APAC, and US markets.My expertise centers on email marketing, automation workflows, and technical implementation. I design responsive templates, build automated campaigns in platforms like Marketo and Eloqua, manage CRM integrations with Salesforce, and coordinate with IT, legal, and sales teams to deliver measurable results. I approach problems analytically and handle both strategic planning and hands-on execution.

## Core Competencies & Technical Expertise

### Email Marketing & Marketing Automation 

- **Platform Expertise**: Advanced proficiency in Eloqua, Marketo, Braze, Mailchimp, Adobe Campaign Standard, HubSpot, Email on Acid
- **Campaign Management**: End-to-end email campaign execution from strategy to deployment, including A/B testing, segmentation, and performance optimization
- **Workflow and CRM integrations**: Created and optimized complex marketing automation workflows, including API integrations between CRM systems and databases
- **Responsive email template development**: Designed and coded sophisticated, responsive email templates compatible across multiple devices and email clients (HTML, CSS, VML for Outlook)
- **Database Management**: Expert in user database management, segmentation, scraping, cleaning, and maintenance, including bounce management and deliverability optimization
- **End-to-end tracking implementation & Performance Analytics**: Advanced email performance tracking, conversion optimization, and ROI measurement

- Multi-market product launch execution
- **Content Strategy**: Development and execution of content marketing strategies aligned with email campaigns and SEO objectives
- Go-to-market strategy and implementation
- **Web Development**: Designed and developed fully functional websites and landing pages using HTML, CSS, and JavaScript, including frameworks like Bootstrap and Sass
- Lead scoring and nurture campaign development
- Performance analytics and optimization

### Project Management & Cross-functional Leadership

- **Campaign Project Management**: Led complex, multi-market email marketing projects involving creative teams, developers, legal compliance, and stakeholder coordination
- **Agile/Scrum Implementation**: Using mostly Kanban in projects
- **Stakeholder Management**: Coordinated with C-suite executives, technical teams, legal advisors, and external agencies across 13+ countries
- **Resource Coordination**: Managed project timelines and cross-functional teams to ensure on-time, on-budget campaign delivery
- **Quality Assurance**: Developed comprehensive QA processes and templates for email campaigns and project deliverables

### Analytics & Data-Driven Marketing

- **Tools**: Google Analytics, PowerBI, Tableau, R, SQL for campaign performance analysis and project reporting
- **Reporting**: Creation of comprehensive email performance reports and project status dashboards focusing on key metrics and ROI
- **Optimization**: Implementation of data-driven improvements in email campaign performance and project efficiency
- **Marketing Intelligence**: Market research and trend analysis to inform both email strategy and project planning decisions

### Technical Stack

- **Email/Marketing Automation**: Eloqua, Marketo, Braze, Mailchimp, HubSpot, Adobe Campaign Standard, SFDC, Email on Acid
- **Project Management**: JIRA, Asana, Trello, Slack
- **Analytics**: Google Analytics, Google Data Studio, R, SQL
- **Content Management**: Sitecore, Crownpeak, WordPress 
- **SEO Tools**: Google Search Console, SEMrush, Keyword Planner, Ahrefs, SimilarWeb
- **Development**: HTML, CSS, JavaScript, Bootstrap, Sass for email template development and landing page creation

## Key Projects & Achievements

### Unilever Food Solutions Lead Scoring System Implementation

##
 Project Overview

Led the complete implementation of a sophisticated lead scoring model for Unilever Food Solutions across UK and Ireland markets, encompassing 54,401+ leads in the Marketo database. The project evolved from a standard scoring system update into a comprehensive technical investigation that uncovered critical tracking infrastructure gaps affecting marketing automation capabilities since 2022.
**
Timeline:
**
 September - December 2025  
**
Platform:
**
 Marketo Engage  
**
Client:
**
 Unilever Food Solutions (UKI)  
**
Impact:
**
 Established data-driven SQL qualification framework and restored visibility into buyer journey analytics
---

##
 Project Scope

###
 Core Deliverables

-
 
**
24 scoring triggers
**
 across email, web, and form-based activities
-
 
**
SQL qualification framework
**
 with 100-point threshold
-
 
**
Multi-stakeholder alignment
**
 across marketing, operations, and technical teams
-
 
**
Comprehensive technical investigation
**
 identifying systemic tracking issues
-
 
**
Implementation documentation
**
 with testing protocols and optimization roadmap
###
 Technical Environment

-
 Marketing automation platform: Marketo Engage
-
 Integration method: REST API (syncLead)
-
 Tracking mechanism: Munchkin JavaScript
-
 Lead volume: 54,401 records (2025)
-
 Trigger complexity: 24 distinct scoring rules with conditional logic
---

##
 Key Features & Achievements

###
 Strategic Framework Development

Designed and implemented a comprehensive scoring model that assigns point values based on engagement intent:
-
 
**
High-intent actions
**
 (75 points): Sample requests, order initiation, product inquiries
-
 
**
Moderate engagement
**
 (17-50 points): Content downloads, account registration, form submissions
-
 
**
Light engagement
**
 (5-10 points): Email opens, website visits, video views
-
 
**
Negative scoring
**
 (-25 points): Unsubscribes and inactivity decay
###
 Technical Investigation & Discovery

Conducted systematic testing that revealed critical infrastructure gaps:
-
 
**
Data Analysis:
**
 Identified that only 0.1% of leads (57 out of 54,401) had website activity tracked
-
 
**
Root Cause Analysis:
**
 Determined that API-based lead creation bypassed cookie association mechanisms
-
 
**
Browser-Level Validation:
**
 Confirmed through console testing that logged-in users were tracked as anonymous visitors
-
 
**
Pattern Recognition:
**
 Discovered that 89% of tracked leads gained visibility only through email click-through attribution
###
 Solution Architecture

Designed technical remediation approach addressing the tracking gap:
-
 Documented implementation requirements for 
`Munchkin.munchkinFunction('associateLead')`
 integration
-
 Created testing protocols for validation across login/signup workflows
-
 Established monitoring framework for trigger health and scoring accuracy
-
 Developed comprehensive technical documentation for cross-functional teams
###
 Stakeholder Management

Facilitated alignment across multiple organizational levels:
-
 Conducted discovery workshops with marketing operations teams
-
 Presented technical findings to digital leadership (Head of Digital & Operator Marketing)
-
 Coordinated with Marketo administrators on infrastructure optimization
-
 Delivered actionable recommendations to web development teams
---

##
 Measurable Impact

###
 Immediate Outcomes

✅ 
**
Email-based scoring fully operational
**
 - Tracking opens, clicks, form fills, and engagement decay  
✅ 
**
SQL definition established
**
 - Clear 100-point qualification threshold for sales handoff  
✅ 
**
System health monitoring
**
 - Active tracking of trigger performance and scoring patterns  
✅ 
**
Knowledge transfer
**
 - Comprehensive documentation enabling future optimization
###
 Projected Impact (Post-Fix Implementation)

-
 
**
20-40% improvement
**
 in lead tracking coverage (from 0.1% to estimated 20-40% of active users)
-
 
**
Enhanced lead qualification accuracy
**
 through complete buyer journey visibility
-
 
**
Behavioral trigger enablement
**
 for 12 web-based automation campaigns
-
 
**
Data-driven optimization
**
 capabilities for ongoing scoring refinement
---

##
 Technical Challenges Overcome

###
 Challenge 1: Zero Historical Baseline

**
Problem:
**
 Existing scoring system was outdated and not monitored, providing no performance baseline  
**
Solution:
**
 Built comprehensive testing framework to validate each trigger independently and establish new performance metrics
###
 Challenge 2: Systemic Tracking Failure

**
Problem:
**
 Web-based triggers showed 0-2 activities per year despite significant website traffic  
**
Solution:
**
 Conducted multi-phase investigation using smart lists, web activity reports, and browser console testing to isolate root cause
###
 Challenge 3: Complex Data Flow Architecture

**
Problem:
**
 100% API-based lead creation created disconnect between backend systems and frontend tracking  
**
Solution:
**
 Mapped complete data flow from lead creation through cookie association, identifying the specific integration gap
###
 Challenge 4: Anonymous vs. Known Attribution

**
Problem:
**
 Thousands of page views captured but not connected to lead records  
**
Solution:
**
 Analyzed attribution patterns, confirmed email click-through as only working mechanism, and designed cookie association solution
---

##
 Key Skills Demonstrated

**
Technical Analysis
**

-
 Marketing automation platform optimization (Marketo)
-
 JavaScript tracking implementation (Munchkin)
-
 API integration architecture (REST API, syncLead)
-
 Browser-based debugging and testing (Console, Network tab)
-
 Data analysis across 54,000+ lead records
**
Strategic Planning
**

-
 Lead scoring model design and optimization
-
 SQL qualification framework development
-
 Multi-phase project planning and execution
-
 Risk identification and mitigation planning
**
Stakeholder Communication
**

-
 Technical documentation for non-technical audiences
-
 Cross-functional workshop facilitation
-
 Executive-level presentation of findings
-
 Vendor coordination (Marketo administrators)
**
Problem Solving
**

-
 Systematic hypothesis testing and validation
-
 Root cause analysis of complex technical issues
-
 Solution design for integration challenges
-
 Performance monitoring and optimization
---

##
 Project Outcomes

**
Operational Excellence
**

Established a robust lead scoring infrastructure that provides real-time qualification of marketing leads based on demonstrated buyer intent, enabling more efficient sales handoff and resource allocation.
**
Technical Innovation
**

Uncovered and documented a multi-year tracking gap that had gone undiagnosed, providing a clear implementation path for full marketing automation capability restoration.
**
Strategic Foundation
**

Created a scalable framework that can evolve with business needs, supported by comprehensive documentation and monitoring protocols for continuous optimization.
---

##
 Tools & Technologies

-
 
**
Marketing Automation:
**
 Marketo Engage
-
 
**
Analytics:
**
 Marketo Reporting Suite, Smart Lists, Web Activity Reports
-
 
**
Testing Tools:
**
 Browser DevTools (Console, Network, Cookie inspection)
-
 
**
Integration:
**
 Marketo REST API, Munchkin JavaScript
-
 
**
Documentation:
**
 Technical specifications, testing protocols, implementation guides
---

### Shimano 2025 Email Newsletter Templates
A comprehensive email template development project creating four distinct, responsive newsletter designs for different interest groups within Shimano's customer base.

Project Scope:

Four custom email templates were developed from scratch using HTML and CSS
Implemented responsive design for mobile optimization
Ensured cross-client compatibility (Gmail, Outlook, Apple Mail, etc.)
Created modular components for easy content updates
Optimized for accessibility and loading speed
Comprehensive testing

Key Features:

Mobile-responsive layouts
Dark mode compatibility
Interactive elements with fallbacks
Optimized image handling
Custom font implementation with web-safe fallbacks
VML fallbacks for Outlook rendering

<details>
<summary>Template 1: Gravel Newsletter</summary>
https://www.dropbox.com/scl/fi/aaguhthvn4nf65ew4nf6h/screencapture-file-Users-merte-Downloads-Templates-Gravel-template-html-2024-12-30-16_33_02.png?rlkey=xkvu2onkukqzhq5kfq4rcrht1&st=r0yovgzf&dl=0
</details>
<details>
<summary>Template 2: Mountain Biking Newsletter</summary>
https://www.dropbox.com/scl/fi/h240yz3i36ztmk8jz5lix/screencapture-file-C-Users-mert-erun-OneDrive-NMQ-Digital-Desktop-Shimano-Bike-template-study-MTB-Templates-MTB-Template-html-2024-12-30-16_01_23.png?rlkey=ldsigcwknyairfhykm2tkpqwi&st=q9v5vikk&dl=0
</details>
<details>
<summary>Template 3: Lifestyle Newsletter</summary>
https://www.dropbox.com/scl/fi/b9epdijfttdl40aclsslo/screencapture-file-C-Users-mert-erun-OneDrive-NMQ-Digital-Desktop-Shimano-Bike-template-study-Lifestyle-Template-Lifestyle-Template-html-2024-12-30-16_01_49.png?rlkey=7kmqj6v368nosssaeg4a1e81i&st=rb3wrytl&dl=0
</details>
<details>
<summary>Template 4: Road Newsletter</summary>
Still ongoing
</details>

### Future Ready Lawyer - Wolters Kluwer - https://www.wolterskluwer.com/en/know/future-ready-lawyer-2023
A comprehensive branding project spanning 13 countries, focusing on legal industry trends including AI, ESG, and LegalTech.

**Role & Responsibilities:**
- Led cross-functional collaboration with local marketers, agencies, and C-suite executives
- Lead and managed content creation and quality assurance
- Designed Emails, Forms and Landing pages
- Email campaign flows and webpage development
- Over 160 pieces of content including emails, articles, forms and landing pages were created

**Results:**
- Successfully launched in all 13 target markets
- Achieved high engagement rates across all content types
- Established Wolters Kluwer as a thought leader in legal technology trends

**Page examples**
- https://www.wolterskluwer.com/en/expert-insights/ai-for-lawyers-mixed-perceptions-of-this-technology
- https://www.wolterskluwer.com/en/expert-insights/legal-trends-2023-law-firm-recruitment-and-remote-legal-work
- https://www.wolterskluwer.com/en/expert-insights/esg-and-law-navigating-a-critical-growth-area
- https://www.wolterskluwer.com/en/expert-insights/legal-technology-increasing-value-for-the-clients

### Kleos Browser Project - https://www.wolterskluwer.com/en/solutions/kleos
A technical marketing initiative for Wolters Kluwer's practice management software. Form renewals of 14 countries in accordance with GDPR practices. Updated forms, landing pages and workflows for proper data collection, accuracy and protection.

**Role & Responsibilities:**
- Coordinated with legal advisors, IT teams, and marketers
- Managed complex system integrations (Eloqua/Marketo to SFDC)
- Developed GDPR-compliant forms for multiple European markets
- Created and optimized marketing funnels

### AI Contract Reader Launch Project - https://www.wolterskluwer.com/en-gb/solutions/legisway/contract-review-for-legal-departments
A strategic product launch campaign for Wolters Kluwer's innovative AI-powered contract analysis solution, targeting existing product users across multiple markets for upselling/cross-selling opportunities.
Campaign Strategy:

**Market Research & Planning:**

Collaborated with local marketers to develop market-specific approaches
Conducted extensive market research to identify target segments
Created data-driven content strategy based on market insights
Developed multi-touch funnel architecture with precise timing

**Campaign Structure:**

**Initial Awareness Phase**

High-impact email highlighting key capability: "1800 contracts in 2 hours"
CTA leading to educational content hub
Video demonstration and detailed article integration

**Value Demonstration(Consideration) Phase**

Progress update email showcasing real-time performance
Strategic timing to capture peak business hours
Whitepaper integration for deep-dive technical content

**Conversion Phase**

Triggered email based on user engagement
Demo offer with exclusive discount
Optimized landing page with lead capture form
Direct connection to sales team for demo scheduling


**Technical Implementation:**

Created automated workflow triggers based on user interactions
Integrated CRM systems for lead tracking and nurturing
Developed responsive landing pages and forms
Implemented analytics tracking for campaign measurement

**Content Development:**

Product demonstration videos
Technical whitepapers
Educational articles
Email copies
Landing page content
Sales enablement materials

**Cross-functional Collaboration:**

Local marketing teams for market-specific adaptations
Sales team for demo process alignment
Technical teams for product integration
Content teams for asset creation
Legal team for compliance review

**Results:**

Successful multi-market launch
High engagement rates with educational content
Strong demo conversion rates
Positive sales team feedback on lead quality
Established effective framework for future product launches

### Smartlaw.de Migration Project
A complex migration project following Wolters Kluwer's acquisition of Smartlaw.de, involving the transfer and optimization of 89 web pages while maintaining user experience.

**Project Scope:**
- Migration of 89 web pages from legacy platform to Adobe Experience Manager (AEM)
- SEO preservation and enhancement
- Content optimization and brand alignment
- Technical infrastructure transition
- User experience maintenance and improvement

**Technical Implementation:**
- **Platform Migration:**
  - Transferred content to Adobe Experience Manager
  - Implemented responsive design principles
  - Set up new technical infrastructure
  - Created custom templates and components

- **SEO Preservation:**
  - Developed comprehensive 301 redirect mapping
  - Preserved existing URL structures where possible
  - Implemented metadata migration strategy
  - Maintained search engine rankings during transition
  - Set up SEO monitoring and tracking

- **Content Optimization:**
  - Audited and updated all page content
  - Aligned with Wolters Kluwer brand guidelines
  - Enhanced content structure and hierarchy
  - Implemented new visual assets and branding elements

**Quality Assurance:**
- Cross-browser testing
- Mobile responsiveness verification
- Page speed optimization
- Link integrity checking
- Content accuracy verification
- SEO compliance validation

**Migration Process:**
1. Initial content audit and inventory
2. Technical requirements gathering
3. Template development and testing
4. Content migration and optimization
5. QA and testing phase
6. Staged rollout
7. Post-migration monitoring

**Risk Mitigation:**
- Created comprehensive backup systems
- Developed rollback procedures
- Implemented monitoring alerts
- Established contingency plans
- Set up emergency response protocols

### Bethabit Product Launch
**Results:**
- Acquired 2,000 users within first month
- Scaled to 4,000 users in three months
- Developed and executed successful go-to-market strategies
- Created engaging community presence on Quora and Reddit
