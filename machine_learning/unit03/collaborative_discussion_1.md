# Collaborative Discussion 1

## Brief

- Identify a specific incident (not covered in your reading list) where the failure of an information system has had a significant impact.
- Your post could consider a range of impacts of the failure, including: the implications to customers, the economic cost, the reputational cost, or any other relevant impacts.
- Review lecturecast 1 and read papers provided in the references list.

## Navigation
- [Initial Post](#initial-post)
  - [Peer Response 1](#peer-response-1)
  - [Peer Response 2](#peer-response-2)
  - [Peer Response 3](#peer-response-3)
- [Summary Post](#summary-post)
- [Back to Machine Learning](/machine_learning)


## Initial Post

Two prominent features of the Fourth Industrial Revolution are the unparalleled speed and the extensive reach of technological advancements (Schwab, 2016). As organizations strive to stay competitive in this fast-evolving environment, the speed of digital change has become a critical factor. Benson and Magee (2018) highlight the importance of aligning business strategies with the accelerating pace of technological advancements in order to remain relevant in a fast-paced world.

This speed, however, may come at a cost. While the ability to adapt and innovate quickly is essential, this increased speed can present significant challenges, particularly concerning system quality. A mapping study on agile development practices highlights that higher development velocity may negatively impact systems' safety and reliability (Kasauli et al., 2018). The demand for quick releases often leads to insufficient testing and oversight, compromising system integrity and safety.

A recent wide-scale incident highlights the potential impact of software failure and, coupled with wide industry reach, the devastating impact such a failure can have. With nearly half of the Fortune 100 companies relying on an AI-powered cybersecurity platform, CrowdStrike, a faulty update from the service providers' Falcon endpoint protection software caused widespread outages in July 2024. The incident led to disruptions in many industries, including healthcare services, travel and cloud providers (Weston, 2024), affecting over 8 million devices worldwide (Tidy, 2024). While a software fix was released soon after the issue was identified, the impact persisted for much longer due to the number of affected systems, with a cost to business estimated in billions of dollars (George, 2024). This failure underscores the risks of prioritizing rapid release cycles and depending on addressing issues as they emerge in production (Khern-am-nuai, 2024), all in the pursuit of faster time-to-market for competitive advantage.
 

References

Benson, C.L. and Magee, C.L. (2018) 'Data-Driven Investment Decision-Making: Applying Moore's Law and S-Curves to Business Strategies'. arXiv. Available at: https://doi.org/10.48550/arXiv.1805.06339.

George, D.A.S. (2024) 'When Trust Fails: Examining Systemic Risk in the Digital Economy from the 2024 CrowdStrike Outage', Partners Universal Multidisciplinary Research Journal, 1(2), pp. 134–152. Available at: https://doi.org/10.5281/zenodo.12828222.

Kasauli, R. et al. (2018) 'Safety-Critical Systems and Agile Development: A Mapping Study', in 2018 44th Euromicro Conference on Software Engineering and Advanced Applications (SEAA). 2018 44th Euromicro Conference on Software Engineering and Advanced Applications (SEAA), pp. 470–477. Available at: https://doi.org/10.1109/SEAA.2018.00082.

Khern-am-nuai, W. (2024) 'Key Lessons Learned for Technology Managers from CrowdStrike Global IT Outage', IEEE Engineering Management Review, pp. 1–5. Available at: https://doi.org/10.1109/EMR.2024.3452090.

Schwab, K. (2016) The Fourth Industrial Revolution: what it means and how to respond, World Economic Forum. Available at: https://www.weforum.org/stories/2016/01/the-fourth-industrial-revolution-what-it-means-and-how-to-respond/ (Accessed: 31 January 2025).

Tidy, J. (2024) CrowdStrike IT outage affected 8.5 million Windows devices, Microsoft says. Available at: https://www.bbc.com/news/articles/cpe3zgznwjno (Accessed: 6 February 2025).

Weston, D. (2024) Helping our customers through the CrowdStrike outage, The Official Microsoft Blog. Available at: https://blogs.microsoft.com/blog/2024/07/20/helping-our-customers-through-the-crowdstrike-outage/ (Accessed: 2 February 2025)

[Back to the top](#)

## Peer Responses

### Peer response 1

I found your post about the CrowdStrike incident both insightful and relevant, especially as my own company was similarly affected. It's remarkable how a relatively minor technical failure can quickly escalate into a significant disruption, underscoring the interdependencies of our digital infrastructure.

The CrowdStrike incident was based on a faulty sensor configuration update in CrowdStrike’s Falcon platform. Specifically, a logic error in a particular file introduced during a routine update led to the massive IT outage (Kerner, 2024). This failure should have been prevented, which underscores the importance of a robust patch management process to mitigate risks associated with software updates (Souppaya and Scarfone, 2013). In response, CrowdStrike updated its processes by upgrading its content configuration system test procedures, adding deployment layers and acceptance checks, and implementing enhanced validation to prevent similar faulty updates in the future (O'Flaherty, 2024).

There is a high risk of similar incidents recurring in the future. Some companies, such as Microsoft, Amazon, and Google, have accumulated significant market power in the tech sector, which raises concerns about the fragility of our digital infrastructure. This concentration of power could lead to systemic vulnerabilities, as a failure by one major player might trigger widespread disruptions and stifle competition in the future (Riley, 2024).

References

Kerner, S.M. (2024) ‘CrowdStrike outage explained: What caused it and what’s next’, published 29 October. Available at: [URL if applicable] (Accessed: 7 February 2025).

Souppaya, M. and Scarfone, K., 2013. Guide to enterprise patch management technologies. NIST Special Publication, 800(40), p.2013.

O'Flaherty, K. (2024) ‘CrowdStrike reveals what happened, why—And what’s changed’, Forbes, 7 August. Available at: https://www.forbes.com/sites/kateoflahertyuk/2024/08/07/crowdstrike-reveals-what-happened-why-and-whats-changed/ (Accessed: 7 February 2025).

Riley, G. (2024) ‘Crowdstrike and Monopoly Power - The Day the Digital World Stood Still’, 21 July. Available at: https://www.tutor2u.net/economics/blog/crowdstrike-and-monopoly-power-the-day-the-digital-world-stood-still (Accessed: 7 February 2025).

[Back to the top](#)

### Peer response 2

Your insight into IT system failures highlights a critical dimension:  IT failures and data breaches often result not only from cyber-attacks and cyber-threats but also from hastily implemented fixes and insufficiently tested releases.  As you argue in your post, this failure underscores the risks of prioritising rapid release cycles and depending on addressing issues as they emerge in production (Khern-am-nuai, 2024), all in the pursuit of faster time-to-market for competitive advantage.  In such scenarios, a robust rollback strategy becomes indispensable, allowing organisations to revert to a previous version of software seamlessly.

Consider the incident in March 2017, where personal data of hundreds of millions of individuals was stolen from Equifax, a major credit reporting agency in the United States (Fruhlinger, 2020).  This incident, which compromised the assessment of the financial health of nearly everyone nationwide, might have been mitigated with an effective rollback procedure in place.  However, as Fellows (2023) highlights, rollbacks are not without risks.  While they offer a crucial safety net for software development teams, enabling swift issue resolution post-deployment, they can also complicate matters.  Mismanaged rollback attempts can exacerbate issues, leading to significant financial ramifications and eroding customer trust and satisfaction.

In essence, preparing a comprehensive rollback strategy is crucial for addressing IT failures effectively.  This process involves a detailed focus on multiple factors such as:

- starting with careful planning and documentation of rollback procedures to ensure all steps are clear and executable
- conducting trials to simulate rollback scenarios to identify potential issues before they occur in a live environment
- establishing robust communication channels to ensure all teams are aligned and informed during rollback actions
- regularly updating and testing rollback documentation to keep the strategy relevant and effective
- learning from previous IT failures by analysing the root causes and outcomes to provide invaluable insights for future preparedness and
- monitoring rollback performance to help identify areas for improvement and enhance system resilience.

By integrating these elements into the rollback strategy, organisations can strengthen their capacity to handle IT failures, thereby safeguarding operational continuity and maintaining stakeholder trust (Fellows, 2023).


Bibliography

Fruhlinger, J. (12 February 2020) Equifax data breach FAQ: What happened, who was affected, what was the impact? CSO Available at  https://www.csoonline.com/article/567833/equifax-data-breach-faq-what-happened-who-was-affected-what-was-the-impact.html [Accessed on 7 February 2025]

Fellows, B. (10 July 2023) The Dangers of Ineffective Rollbacks in Software Releases, LoopQA, Available from https://www.workwithloop.com/blog/the-dangers-of-ineffective-rollbacks-in-software-releases [Accessed on 7 February 2025]

Khern-am-nuai, W. (2024) 'Key Lessons Learned for Technology Managers from CrowdStrike Global IT Outage', IEEE Engineering Management Review, pp. 1–5. Available at: https://doi.org/10.1109/EMR.2024.345209

[Back to the top](#)

### Peer Response 3

> [!NOTE]
> This is a late peer response and was not incorporated into the final summary post

In general, the discussion provides a good clarity and has provided good citations. Selection of speed of digital change is critical one. However, there are certain areas of improvement.

It is good to look at the incident related to how higher development velocity negatively impact system’s safety and reliability and identifying a demand for quick releases seems to a generic concern over a period of time. If the discussion identifies one specific incident on such quick release issue would help in the discussion.

The incident related to Falcon endpoint protection software issue which caused an outage is very critical to understand. The disruptions it caused in many domains due to the software fix release. However, the discussion is about quick release based on speed on development using Agile is not identified as root cause of the issue. The discussion states that software fix was released soon after the issue was identified and hence it proves Agile is helping in making such quick release fixes which is against the discussion.

Incident impact to the economy or financial details could help. The incident caused about 30 billion market value loss (Stacey, 2025) could help the readers understand the real impact. The incident also caused customer loss of 500 million for Delta Airlines, which was compensated (AP News, 2024).

References

Stacey, S. (2025). CrowdStrike bounces back after triggering largest IT outage in history. [online] @FinancialTimes. Available at: https://www.ft.com/content/e98e0d35-38f4-476e-bd22-7f74162df5b4.

AP News. (2024). Delta sues cybersecurity firm CrowdStrike over tech outage. [online] Available at: https://apnews.com/article/delta-airlines-crowdstrike-outage-lawsuit-43bb230d2edf235bb9f7928c4279fec2.

[Back to the top](#)

## Summary Post

The Fourth Industrial Revolution is characterised by the rapid pace and extensive reach of technological advancements, which organisations must adapt to in order to remain competitive (Schwab, 2016). In this fast-changing landscape, aligning business strategies with digital transformation is critical (Benson and Magee, 2018). While the ability to innovate quickly is essential, the demand for rapid development and releases can compromise system integrity, especially when testing and oversight are insufficient (Kasauli et al., 2018).

A notable incident in 2024 illustrates these risks. A faulty update from CrowdStrike’s Falcon endpoint protection software, used by many Fortune 100 companies, triggered widespread disruptions in industries such as healthcare, travel, and cloud services, impacting over 8 million devices (Tidy, 2024; Weston, 2024). The incident, although quickly fixed, continued to cause disruptions due to the wide reach of the affected systems. The financial toll on businesses was estimated in the billions (George, 2024).

This event highlights a critical aspect of IT system failures: the prioritisation of rapid release cycles and the practice of addressing issues only as they emerge in production can have disastrous consequences (Khern-am-nuai, 2024). In pursuing faster time-to-market for competitive advantage, organisations may overlook the importance of system safety and reliability, leading to costly failures.

As was highlighted during peer discussion, several big-tech companies have gained substantial market power, which raises concerns about the fragility of our digital infrastructure when so much influence is exerted by a handful of service providers. A failure by one of these companies might trigger widespread disruptions, further jeopardising the reliability of digital services (Riley, 2024).

While not without risks, a robust rollback strategy is indispensable in such scenarios (Fellows, 2023). The ability to revert to a previous software version allows organisations to minimise the impact of a failure. Therefore, balancing speed with careful testing, oversight, and the ability to revert changes is crucial to maintaining system integrity and minimising the potential for system failures.



References

Benson, C.L. and Magee, C.L. (2018) ‘Data-Driven Investment Decision-Making: Applying Moore’s Law and S-Curves to Business Strategies’. arXiv. Available at: https://doi.org/10.48550/arXiv.1805.06339.

Fellows, B. (2023) The Dangers of Ineffective Rollbacks in Software Releases. Available at: https://www.workwithloop.com/blog/the-dangers-of-ineffective-rollbacks-in-software-releases (Accessed: 15 February 2025).

George, D.A.S. (2024) ‘When Trust Fails: Examining Systemic Risk in the Digital Economy from the 2024 CrowdStrike Outage’, Partners Universal Multidisciplinary Research Journal, 1(2), pp. 134–152. Available at: https://doi.org/10.5281/zenodo.12828222.

Kasauli, R. et al. (2018) ‘Safety-Critical Systems and Agile Development: A Mapping Study’, in 2018 44th Euromicro Conference on Software Engineering and Advanced Applications (SEAA). 2018 44th Euromicro Conference on Software Engineering and Advanced Applications (SEAA), pp. 470–477. Available at: https://doi.org/10.1109/SEAA.2018.00082.

Khern-am-nuai, W. (2024) ‘Key Lessons Learned for Technology Managers from CrowdStrike Global IT Outage’, IEEE Engineering Management Review, pp. 1–5. Available at: https://doi.org/10.1109/EMR.2024.3452090.

Riley, G. (2024) Crowdstrike and Monopoly Power - The Day the Digital World Stood Still. Available at: https://www.tutor2u.net/economics/blog/crowdstrike-and-monopoly-power-the-day-the-digital-world-stood-still (Accessed: 15 February 2025).

Schwab, K. (2016) The Fourth Industrial Revolution: what it means and how to respond, World Economic Forum. Available at: https://www.weforum.org/stories/2016/01/the-fourth-industrial-revolution-what-it-means-and-how-to-respond/ (Accessed: 31 January 2025).

Tidy, J. (2024) CrowdStrike IT outage affected 8.5 million Windows devices, Microsoft says. Available at: https://www.bbc.com/news/articles/cpe3zgznwjno (Accessed: 6 February 2025).

Weston, D. (2024) Helping our customers through the CrowdStrike outage, The Official Microsoft Blog. Available at: https://blogs.microsoft.com/blog/2024/07/20/helping-our-customers-through-the-crowdstrike-outage/ (Accessed: 2 February 2025).

[Back to the top](#) or [Back to Machine Learning](/machine_learning/)