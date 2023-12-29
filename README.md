# **Cervical Screening Self-Book with Accurx**
`Brompton Health PCN`

> The introduction of SMS self-book interventions at participating practices appears to have correlated with an **immediate spike in cervical screenings**, suggesting an effective strategy for increasing health engagement, though further analysis is necessary to **confirm long-term efficacy and causation**. 

## **The SMS Self-Book Campaign**
The SMS Self-Book Campaign, implemented by three GP practices under Brompton Health Primary Care Network (PCN) utilizing the Accrux messaging platform, represents a significant stride towards enhancing cervical screening rates in general practice. This innovative approach aimed to explore the potential impact of direct SMS communication on the participation rate in cervical screenings. Patients eligible for screening received an initial SMS, meticulously crafted to inform and reassure them about the nature and frequency of the messages. This step was crucial in establishing trust and clarity right from the onset. Subsequently, the campaign leveraged the Accrux Self-book platform, making all nurse appointments accessible for direct booking. This seamless integration of technology into routine healthcare practice signifies a modern approach to patient engagement, resonating with the increasingly digital-centric lifestyle of many patients.

A notable feature of this campaign was the frequency and timing of the SMS invitations. Patients received weekly invitations, a strategic decision aligning with the one-week validity of Accrux invitations. This consistency ensured that patients always had a current and actionable opportunity to schedule their screening, thereby reducing barriers to access and participation. Such an approach not only empowered patients to manage their health proactively but also accommodated diverse schedules and life circumstances. The campaign culminated with a patient survey, an insightful tool aimed at gathering feedback to refine future initiatives. This emphasis on patient feedback underscores the PCN’s commitment to patient-centered care, where the experiences and inputs of patients are pivotal in shaping healthcare services. This campaign not only aimed at increasing immediate screening rates but also at establishing a foundation for sustained patient engagement and proactive health management, potentially setting a new standard for public health campaigns in general practice.

## **Here's what we can discern from the charts**:
[See Notebook](CxScreeningTimeSeries.ipynb)<BR><BR>
Interpreting the plots, it appears to show two key data trends over time: the number of female registrations aged 24-64 years and the monthly cervical screening count at participating practices. The vertical dashed red line indicates the start of an intervention using SMS (text messaging), which began on October 12, 2023. for ECS and Nov,1 2023 for the TCP and SMW.

Interpreting the plots, it appears to show two key data trends over time: the number of female registrations aged 24-64 years and the monthly cervical screening count at participating practices. The vertical dashed red line indicates the start of an intervention using SMS (text messaging), which began on October 12, 2023. for ECS and Nov,1 2023 for the TCP and SMW.

![Show Chart](https://github.com/janduplessis883/Cervical-Screening-Self-Book-with-Accurx/blob/main/images/Cervical%20Screening%20Outcome.png?raw=true)

**Before the Intervention:** Prior to the SMS intervention, there is a fluctuating but generally consistent gap between female registrations and the number of cervical screenings. This suggests a variance in the uptake of cervical smear tests among those registered.

**After the Intervention:** There is a significant spike in the number of cervical screenings in the month following the start of the SMS intervention, indicating a potential positive impact of the SMS reminders on the uptake of cervical smear tests. This peak is the highest point on the graph for the monthly cervical screening count, suggesting that the SMS intervention might have been effective in encouraging more women to undergo screening.

**Statistical Summary**: The mean monthly cervical screening rate before the intervention is noted as 111.58, and the mean monthly registrations for females in the cervical screening age group is 88.11. The mean difference of 23.47 could reflect the average gap between registrations and screenings conducted each month.

It’s important to note that while the **immediate increase in screenings after the start of the SMS intervention suggests a correlation, further analysis would be required to establish causation.** This would include looking at longer-term trends, ruling out other factors that might have influenced the spike, and potentially comparing with a control group.

Additionally, the sharp decline in screenings right after the peak might indicate that while the SMS intervention had an initial impact, its effect may not have been sustained over time, or it could be due to other factors not visible on this graph, such as seasonal variations or operational issues at the practice. A careful examination of the full context of the data and additional data points beyond the scope of this graph would be needed for a comprehensive understanding.
## **General Observations**
There are seasonal trends or patterns in the data which could correspond to specific health campaigns or periodic health check-ups.
The spikes in the Chelsea Practice and Stanhope Mews West graphs may require investigation to understand their cause.


The "Effectiveness of Screening Program" might be a calculated metric to assess how many more screenings are performed compared to new registrations, potentially indicating the reach or success of the screening program.

## Data Interpretation Considerations
The time series data might need further analysis to understand the context of the peaks and troughs fully.

It would be important to consider external factors that could influence these numbers, such as public health initiatives, changes in policy, or even external events like pandemics.

Understanding the goal of the screening program is crucial in interpreting these figures. For instance, if the objective is early detection, higher screening rates compared to new registrations could be a positive indicator.

## **Post Intervention Patient Survey**
We care currently collecting patient feedback to aid furhter analysis.<BR>
[Patient Survery Questionnaire](https://docs.google.com/forms/d/e/1FAIpQLSc_iWioKWfGq01BLFWX47sINgZhDGwaspM3yo0ewbQUES3FMw/viewform)
<BR><BR>
![Static Badge](https://img.shields.io/badge/GitHub-janduplessis883-%23aabd3b)  ![Static Badge](https://img.shields.io/badge/Python-3.10.6-%23ae4f4d) ![Static Badge](https://img.shields.io/badge/Telegram-%40jdp145-%2354a7e5?logo=telegram)<BR>
