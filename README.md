# Projects Performance Dashboard - Power BI

A comprehensive Power BI dashboard for monitoring and analyzing project performance, budget utilization, and task completion across multiple project types and locations.

![Dashboard Version](https://img.shields.io/badge/version-1.0-blue)
![Power BI](https://img.shields.io/badge/Power%20BI-Desktop-yellow)
![Status](https://img.shields.io/badge/status-active-success)

## 📊 Overview

This Power BI dashboard provides real-time insights into project management metrics, enabling stakeholders to make data-driven decisions. It tracks 53 projects with 163 tasks, monitoring costs, budgets, timelines, and team performance.

### Key Metrics at a Glance
- **Total Projects:** 53
- **Total Tasks:** 163
- **Total Budget:** $10,469K
- **Total Cost:** $8,733K
- **Budget Utilization:** 83.4%
- **Task Completion:** 75.0%

## ✨ Features

### 1. **Executive Summary Dashboard**
- Real-time KPI tracking (projects, tasks, costs, budget utilization)
- Project status distribution (Not Started, In Progress, Completed, Overdue)
- Priority-based project categorization (Critical, High, Medium, Low)
- Budget vs. Over-budget project comparison by type

### 2. **Cost Analysis**
- Monthly trend analysis of budget vs. actual costs
- Cost breakdown by project type and location
- Budget allocation, utilization, and remaining budget tracking
- Individual task-level cost analysis
- Identification of over-budget projects (22 flagged)

### 3. **Project Timeline**
- Interactive Gantt chart visualization
- Task-level timeline tracking
- Status indicators (Not Started, In Progress, Completed, Pending)
- Resource assignment visualization
- Timeline spanning from February 2025 to September 2026

### 4. **Project Manager Performance**
- Individual manager metrics and KPIs
- Overdue task tracking per manager
- Budget utilization rates by manager
- Task completion percentages
- Workload distribution analysis

### 5. **Geographic Analysis**
- Location-based task completion mapping
- Regional performance insights
- Uncompleted tasks by location

## 📁 Project Structure

```
power-bi-projects-dashboard/
├── README.md
├── data/
│   └── Project Management Dataset.xlsx
├── screenshots/
│   ├── dashboard_overview.png
│   ├── cost_analysis.png
│   ├── timeline_view.png
│   └── manager_performance.png
└── docs/
    └── Projects Performance Dashboard.pdf
```

## 📈 Key Insights from Current Data

### Critical Findings
- **Most Overdue Project:** P017 - Urban Trade Hub (154 days delayed)
- **Highest Budget Utilization:** P037 - Skylink Metro (105.1%)
- **Highest Cost Project:** P037 - Skylink Metro ($342,264)
- **Projects Over Budget:** 22 out of 53 projects
- **Manager Needing Assistance:** Hakima Amrani (7 pending tasks, 61.4% completion)

### Performance by Project Type
| Project Type | Budget Utilization |
|--------------|-------------------|
| Infrastructure | 87.5% |
| Residential | 86.2% |
| Commercial | 82.2% |
| Industrial | 82.1% |
| Renovation | 79.8% |
| Institutional | 79.3% |

### Project Status Distribution
- Completed: 24 (44%)
- Overdue: 16 (30%)
- In Progress: 13 (24%)
- Not Started: 1 (2%)

## 🎯 Use Cases

1. **Executive Leadership**: High-level overview of portfolio performance
2. **Project Managers**: Detailed tracking of assigned projects and tasks
3. **Finance Teams**: Budget monitoring and cost control
4. **Resource Managers**: Team workload and capacity planning
5. **Stakeholders**: Project status and timeline visibility

## 🔧 Customization

### Adding New Data
1. Navigate to "Transform Data" in Power BI Desktop
2. Update your data source connections
3. Ensure column names match the existing schema
4. Refresh the data model

### Modifying Visualizations
1. Click on any visual to select it
2. Use the Visualizations pane to modify chart types
3. Adjust filters and slicers in the Filters pane
4. Customize colors in the Format visual pane

### Creating New Pages
1. Click the "+" icon at the bottom to add a new page
2. Drag and drop visuals from the Visualizations pane
3. Connect to data fields from the Fields pane

## 📱 Deployment Options

### Power BI Service
1. Sign in to [Power BI Service](https://app.powerbi.com)
2. Click "Get Data" > "Files" > "Local File"
3. Upload the .pbix file
4. Configure refresh schedule
5. Share with stakeholders

### Embedded Analytics
- Embed dashboards in SharePoint
- Integrate with Microsoft Teams
- Use Power BI Embedded for custom applications


## 📧 Contact & Support

- **Project Maintainer**: [OUTGOUGUA MUSTAPHA]
- **LinkedIn**: [GitHub Issues](https://www.linkedin.com/in/mustapha-outgougua/)
- **Issues**: [GitHub Issues](https://github.com/outgouguamustapha/Projects-Performance-Dashboard/issues)

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Power BI Community for visualization inspiration

## 📅 Changelog

### Version 1.0 (October 2025)
- Initial release
- 53 projects tracked across 6 project types
- 4 main dashboard pages
- 8 project managers monitored
- Real-time KPI tracking

---

**Last Updated:** October 6, 2025

