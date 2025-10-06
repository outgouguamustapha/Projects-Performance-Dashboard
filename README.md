# Projects Performance Dashboard - Power BI

![Dashboard Version](https://img.shields.io/badge/version-1.0-blue)
![Power BI](https://img.shields.io/badge/Power%20BI-Desktop-yellow)
![Status](https://img.shields.io/badge/status-active-success)

**Dashboard Link**: [Live Dashboard](https://app.powerbi.com/view?r=eyJrIjoiZmNkNWJmYTQtMWFjZS00MTkzLWFhMjItZTc4NzBmMWQ0NDQ3IiwidCI6Ijg0ZDI3MGQyLTBiYzUtNGQ1NS1iZjBhLTI3NGYxYTU3NmNiZiJ9&pageName=ba8417c84e1328159a55)

---

## Executive Summary

This comprehensive Power BI dashboard provides real-time insights into project management performance across a portfolio of 53 projects and 163 tasks. The dashboard monitors critical metrics including budget utilization (83.4%), task completion rates (75.0%), and financial performance with total costs of $8,733K against a budget of $10,469K. The solution delivers actionable insights across four key dimensions: executive KPIs, cost analysis, project timelines, and manager performance, enabling data-driven decision-making for stakeholders at all levels of the organization.

---

## Business Problem

Organizations managing multiple concurrent projects face significant challenges in maintaining visibility and control over:

- **Budget Overruns**: 22 out of 53 projects (42%) are currently over budget, with the highest overrun at 105.1% for the Skylink Metro project
- **Schedule Delays**: 16 projects (30%) are overdue, with the Urban Trade Hub project delayed by 154 days
- **Resource Allocation**: Uneven workload distribution across 8 project managers, with some managers handling 7 pending tasks while maintaining only 61.4% completion rates
- **Performance Visibility**: Lack of real-time insights into project status, cost trends, and team performance across 6 different project types (Infrastructure, Residential, Commercial, Industrial, Renovation, Institutional)
- **Geographic Distribution**: Inability to track performance across multiple locations and identify regional bottlenecks

Without centralized monitoring and analytics, leadership teams struggle to identify at-risk projects, optimize resource allocation, and prevent budget overruns before they escalate.

---

## Methodology

### Data Collection & Preparation
- **Data Source**: Consolidated project management dataset containing 53 projects with 163 associated tasks
- **Data Scope**: Projects spanning from February 2025 to September 2026
- **Key Dimensions**: Project type, location, manager assignment, priority levels, status, and financial metrics

### Dashboard Development Process
1. **Data Modeling**: Established relationships between projects, tasks, budgets, and resource assignments in Power BI Desktop
2. **KPI Definition**: Identified and calculated critical metrics including budget utilization, completion rates, and variance analysis
3. **Visualization Design**: Created four specialized dashboard pages:
   - **Executive Summary Dashboard**: Real-time KPIs, status distribution, and priority categorization
   - **Cost Analysis**: Monthly trends, budget vs. actual comparisons, and over-budget identification
   - **Project Timeline**: Interactive Gantt charts with task-level tracking and status indicators
   - **Project Manager Performance**: Individual manager metrics, workload distribution, and completion rates
4. **Interactive Features**: Implemented filters, slicers, and drill-through capabilities for dynamic analysis
5. **Deployment**: Published to Power BI Service for organization-wide access and automated refresh scheduling

### Analytical Approach
- Comparative analysis of budget utilization across project types
- Trend analysis of monthly costs vs. budgets
- Geographic mapping of task completion rates
- Performance benchmarking across project managers
- Priority-based risk assessment

---

## Skills

### Technical Skills Demonstrated
- **Power BI Desktop**: Advanced dashboard design and development
- **Data Modeling**: Relationship management and calculated measures using DAX
- **ETL Process**: Data transformation and preparation
- **Data Visualization**: Chart selection, color theory, and information hierarchy
- **Business Intelligence**: KPI design and metric definition

### Analytical Capabilities
- Financial analysis and budget variance tracking
- Project performance metrics and trend analysis
- Resource utilization analysis
- Time-series forecasting and planning
- Geographic data analysis

### Tools & Technologies
- Power BI Desktop & Power BI Service
- Microsoft Excel (data source integration)
- DAX (Data Analysis Expressions)
- Power Query (data transformation)
- SharePoint/Teams integration capabilities

### Business Acumen
- Project management principles
- Financial management and budgeting
- Stakeholder communication
- Performance optimization strategies
- Risk identification and mitigation

---

## Results & Business Recommendation

### Key Performance Indicators
- **Portfolio Health**: 53 active projects with $10.5M total budget
- **Financial Performance**: $8.7M actual costs with 83.4% budget utilization
- **Delivery Status**: 75% task completion rate with 44% of projects completed
- **Budget Management**: $1.7M remaining budget across active projects

### Critical Findings

**High-Risk Projects Requiring Immediate Attention**:
- **P037 - Skylink Metro**: 105.1% budget utilization ($342K cost) - requires immediate cost control measures
- **P017 - Urban Trade Hub**: 154 days overdue - needs schedule recovery plan or scope reassessment

**Project Type Performance**:
- Infrastructure projects show highest budget utilization (87.5%), indicating either efficient resource use or potential underbudgeting
- Institutional projects demonstrate best budget management (79.3%), providing a benchmark for other categories
- 22 projects flagged as over-budget across all categories

**Manager Performance Insights**:
- Hakima Amrani requires workload balancing or additional support (7 pending tasks, 61.4% completion)
- Opportunity to redistribute tasks from overloaded managers to optimize team capacity

### Business Impact
- **Enhanced Visibility**: Real-time monitoring enables proactive intervention on at-risk projects
- **Cost Savings**: Early identification of budget overruns prevents further financial escalation
- **Resource Optimization**: Workload insights enable better task distribution and team efficiency
- **Improved Decision-Making**: Data-driven insights support strategic planning and resource allocation
- **Stakeholder Confidence**: Transparent reporting builds trust with executives and clients

---

## Recommendation

### Immediate Actions (0-30 days)
1. **Address Critical Projects**:
   - Conduct immediate cost review for Skylink Metro (P037) to prevent further budget escalation
   - Initiate recovery plan for Urban Trade Hub (P017) or negotiate timeline extension with stakeholders
   
2. **Rebalance Workloads**:
   - Redistribute 3-4 tasks from Hakima Amrani to managers with lower pending task counts
   - Establish maximum task limits per manager to prevent future bottlenecks

3. **Budget Control Measures**:
   - Implement weekly budget reviews for the 22 over-budget projects
   - Establish approval gates for additional spending requests

### Short-Term Improvements (1-3 months)
1. **Enhance Monitoring**:
   - Add automated alerts for projects approaching 90% budget utilization
   - Create weekly digest reports for executives highlighting at-risk projects
   
2. **Process Optimization**:
   - Standardize project budgeting methodology based on Institutional project success rates
   - Develop project type-specific templates incorporating lessons learned

3. **Training & Support**:
   - Conduct dashboard training sessions for all project managers
   - Create user guides for self-service reporting

### Long-Term Strategic Initiatives (3-12 months)
1. **Predictive Analytics**:
   - Integrate machine learning models to forecast project delays and budget overruns
   - Develop risk scoring algorithms based on historical project data
   
2. **Expanded Capabilities**:
   - Add resource capacity planning features
   - Incorporate client satisfaction metrics
   - Link to procurement and change order systems

3. **Portfolio Optimization**:
   - Establish data-driven project prioritization framework
   - Create "what-if" scenario planning tools for resource allocation

---

## Next Steps

### For Dashboard Users
1. **Access Training**: Schedule onboarding session to maximize dashboard utilization
2. **Customize Views**: Set up personalized filters and bookmarks for your role
3. **Enable Notifications**: Subscribe to automated alerts for your projects
4. **Provide Feedback**: Share enhancement requests via [GitHub Issues](https://github.com/outgouguamustapha/Projects-Performance-Dashboard/issues)

### For Administrators
1. **Data Refresh Schedule**: Configure automated daily/weekly refresh in Power BI Service
2. **User Access Management**: Assign appropriate permissions based on organizational hierarchy
3. **Integration Setup**: Connect dashboard to SharePoint/Teams for embedded access
4. **Documentation**: Create role-specific user guides and video tutorials

### Development Roadmap
- **Phase 1 (Q4 2025)**: Implement automated alerting system and expand KPI library
- **Phase 2 (Q1 2026)**: Add predictive analytics and resource capacity planning
- **Phase 3 (Q2 2026)**: Integrate with external systems (ERP, procurement, HR)
- **Phase 4 (Q3 2026)**: Deploy mobile-optimized version and advanced scenario planning

### Customization & Extension
To add new data or modify visualizations:
1. Open the .pbix file in Power BI Desktop
2. Navigate to "Transform Data" to update data sources
3. Ensure new columns match existing schema
4. Refresh the data model and test all visuals
5. Publish updated version to Power BI Service

---

## 📁 Project Structure

```
power-bi-projects-dashboard/
├── README.md
├── data/
│   └── Project Management Dataset.xlsx
├── screenshots/
│   ├── Project_Board.png
│   ├── Cost_analysis.png
│   ├── Project_timeline.png
│   └── Project_manager.png
└── docs/
    └── Projects Performance Dashboard.pdf
```

---

## 📧 Contact & Support

- **Project Maintainer**: OUTGOUGUA MUSTAPHA
- **LinkedIn**: [Profile](https://www.linkedin.com/in/mustapha-outgougua/)
- **Issues**: [GitHub Issues](https://github.com/outgouguamustapha/Projects-Performance-Dashboard/issues)

---

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

---

**Last Updated:** October 6, 2025  
**Version:** 1.0