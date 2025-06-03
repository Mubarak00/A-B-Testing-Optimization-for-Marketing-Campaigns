
# A/B Testing Optimization for Marketing Campaigns

## Project Summary
Implemented A/B testing framework to evaluate and optimize homepage layouts and email messaging. Resulted in a measurable 7% lift in overall click-through rates (CTR).

## Problem Statement
Marketing efforts lacked quantifiable insight into which messaging, layout, and calls-to-action (CTAs) performed best. Needed a systematic experimentation framework to drive engagement improvements.

## Tools & Technologies Used
- **Language**: Python, SQL  
- **Data Tools**: Google Analytics, Power BI  
- **Statistical Testing**: t-tests, chi-square, Bayesian methods  
- **Infrastructure**: Segment, Snowflake, internal dashboards

## Experimental Design
- Designed split tests for homepage layout (headline, CTA color, button text)
- Conducted subject line and send-time tests for email campaigns
- Defined primary metric as click-through rate (CTR), with secondary metrics including open rate and time on page

## Example Test Summary
| Variant | CTR (%) | Sample Size | Statistical Sig |
|---------|---------|-------------|-----------------|
| A (Control) | 11.2 | 10,000 | -- |
| B (Test) | 12.0 | 10,100 | ✅ p < 0.01 |

**Lift:** +7.1%

## Results & Business Impact
- **7% increase in CTR**, leading to higher product engagement and conversion rates  
- Campaign results used to permanently update the homepage CTA design  
- Email optimization reduced bounce rates and increased re-engagement from dormant users

## Monitoring & Maintenance
- Set up automated pipelines to monitor experiment KPIs in real-time
- Power BI dashboards updated daily for performance visibility

## Challenges & Learnings
- Had to account for uneven traffic sources between variants
- Learned to align statistical rigor with business urgency (e.g., stopping tests early with Bayesian methods)

## Team Collaboration
- Collaborated with marketing and product design teams to select testable variables
- Shared weekly insights and next steps with the executive growth team

## Code Availability
Due to organizational confidentiality, full test data and scripts are not available for public access.
