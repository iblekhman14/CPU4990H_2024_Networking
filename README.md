## Plan of Action

The project will be structured into three main phases over the 15-week semester:

1. **Initial Analysis & Data Collection (Weeks 1–8)**  
   - Acquire necessary hardware and software.  
   - Form initial hypotheses regarding network congestion and performance bottlenecks.  
   - Analyze both high- and low-density areas and calculate various performance metrics.  
   - Collect preliminary data, including manual verification of initial theories and expectations.

2. **Data Analysis & Modeling (Weeks 7–12)**  
   - Overlap data collection and analysis in Weeks 7–8 to ensure continuous refinement of hypotheses.  
   - Use Python scripts and other tools to scrape and process data (mean, median, variance, etc.).  
   - Run simulation models to predict the impact of proposed changes on bandwidth congestion.  
   - Draw conclusions and propose improved network models or suggestions.

3. **Conclusion & Presentation (Weeks 13–15)**  
   - Finalize all collected data and results.  
   - Prepare a project poster summarizing key findings, methods, and recommendations.  
   - All major work (except finalizing the poster) should be completed by December 1, allowing ample time for poster creation and final wrap-up.

## Notable Events

- **8/29/2024 (1–3 PM):** A school-wide partial Wi-Fi outage occurred.  
- **9/3/2024:** A similar Wi-Fi outage occurred, likely related to the same underlying issue.
- **9/6/2024:** Final Wi-Fi outage occurred, likely related to the same underlying issue.
- **9/13/2024:** Campus IT resolved reported issues.



## Detailed Timeline

- **Weeks 1–2:** Acquire necessary tools and solidify initial hypotheses.  
- **Weeks 3–8:** Gather comprehensive data and complete initial projections.  
- **Weeks 7–10:** Analyze data using scripting tools (e.g., Python) to determine performance metrics.  
- **Weeks 9–12:** Draw conclusions and propose improved models or suggestions.  
- **Weeks 13–15:** Finalize the project, create the poster, and prepare the final presentation.

## General Hypothesis

Network speeds slow down due to high congestion, potentially caused by too many simultaneous users on access points, insufficient total bandwidth, or configuration issues (e.g., eduroam setup, insufficient IP addresses, or a problematic RADIUS server).

## Campus Network Hardware

- **CPP Village:** Aruba Campus 303/305 models (or similar).  
- **Library:** To be determined (further investigation needed).

## Tools & Testing Methodologies

- **Tests Under Load:**  
  - Downloading a large file from a known high-speed server on one device while running ping and speed tests in parallel on another device.  
  - Repeating similar tests with uploads to observe changes in latency and throughput.

- **Local Speed Tests:**  
  - Conducting speed tests between two local devices (Device 1 → Access Point → Device 2, or Device 1 → Access Point → Router → Access Point → Device 2).

- **Ping Tests:**  
  - Running multiple ping tests to compare wired vs. wireless performance, helping identify if issues are tied to wireless access points or higher-level routing infrastructure.

- **Consulting IT:**  
  - Discussing with IT staff to understand known issues, network architecture, and to gather insights on potential configuration problems.

## Potential Solutions

- Implementing Quality of Service (QoS) measures.  
- Increasing the number of access points or upgrading hardware to handle higher concurrency.  
- Reconfiguring or upgrading underlying network infrastructure (routers, servers, eduroam parameters).

---
