# Monetha Bug Bounty Program
[https://bounty.monetha.io](https://bounty.monetha.io)

Monetha’s Bug Bounty Program provides bounties for identifying vulnerability bugs. Our development and security teams have made every effort to eliminate all bugs in our systems, however, there's always the chance that we might have missed some potential vulnerabilities. We appreciate you working with us around any bug you discover. We do offer rewards to show our appreciation. Before getting started, please see our Service Level Agreements & Eligibility sections for more details.

**Do not submit any vulnerability to** [github Issues](https://github.com/monetha/bug-bounty/issues). For bounty program all issues must be submitted to [Submit a Vulnerability](https://docs.google.com/forms/d/e/1FAIpQLSepEDPWlHn2CVFHHaOlrE_YSnQo7Uj-mV051SmrXZ0t85SYBg/viewform)

### Service Level Agreements
We appreciate you taking the time to participate in Monetha's Bug Bounty Program. We have invested time and energy into our program to make it the best it can be. There are some things you can expect from us when participating in our program:

#### Monetha will make our best effort to:
* Provide an initial response on all reports within one business day.
* Let you know if your report qualifies for a bounty within five business days.
* If the report qualifies for a bounty, we will set a risk level of severity and the reward size within five business days.
* Resolve qualifying vulnerabilities within 90 days (1 day for critical, 1-2 weeks for high, 4-8 weeks for medium and 90 days for low issues). More complex issues may require longer to fix. If you have a question regarding the remediation timeline, please inquire on the relevant report.
* Notify you within five business days once an issue has been resolved.
* The value of rewards paid out will vary depending on Severity. The severity is calculated according to the OWASP risk rating model based on Impact and Likelihood: 
* Please allow up to one week from the time the report was approved and validated to receive your bounty payment. Reward sizes are guided by the rules below and payable in ETH.
    - Critical: $500 - $1000
    - High: $100 - $500
    - Medium: $50 - $100
    - Low: $10 - $50
    - Note: up to $10
    
### Eligibility
The following requirements must be adhered to in order to participate in Monetha's Bug Bounty Program, and for any report to qualify. Not following these requirements can result in anything from your report being rejected to being banned from the program.

* Report format - for any report to be considered, you must provide clear instructions on how to reproduce the issue, as well as how it could be exploited (attack scenario), and what you think the security impact is. This information helps us assess eligibility and appropriate bounty amounts.
* First come, first served - only the first person to identify a particular vulnerability will qualify for a bounty. Any additional reports will be considered as duplicates and will not qualify.
* Play it safe - all testing must be performed on test accounts under your control. Any attacks against other users without provable express consent are not allowed and may result in a ban from our program. If a particular issue is severe enough that a PoC in itself may expose other users’ data, please ask us for help first so we can work together on how to safely demonstrate the bug.
* Don't disclose too early - to best protect our users, please keep all identified vulnerability details between you and us until we've had a chance to fix the issue. Public disclosure prior to us notifying you of the fix may result in a ban from the program. If you have questions regarding the remediation timeline, please inquire on the relevant report.
* No social engineering - bugs that require social engineering to exploit (e.g. tricking someone into clicking a link) may qualify, but please do not actually attempt to socially engineer another user, Monetha team members, etc., during your testing. Providing a clear explanation of how social engineering could be used in conjunction with an identified vulnerability is sufficient.

### Scope
Any design or implementation issue that substantially affects the confidentiality or integrity of user data is likely to be within the scope of the program.

* Smart contracts: [TrustReputationSmartContracts](https://github.com/monetha/TrustReputationSmartContracts)
* Payment integrations: [magento](https://github.com/monetha/magento), [woocommerce](https://github.com/monetha/woocommerce), [buynowbutton](https://github.com/monetha/buynowbutton)
* Monetha [Android](https://play.google.com/store/apps/details?id=com.monetha.app) and [iOS](https://itunes.apple.com/app/id1351311808) app
* Monetha [web](https://www.monetha.io/user/login) application 
* Monetha [API paynment gateway](https://api.monetha.io/mth-gateway/v1/docs) and [mobile api](https://api.monetha.io/mth/v1/docs)

### Out-Of-Scope
* Phishing Monetha workers, users, clients and anyone who is related with Monetha.
* Monetha web page and all subpages: https://www.monetha.io
* Monetha demo shop and all subpages: https://shop-sandbox.monetha.io (except payment integration).
* Monetha blog and all subpages: https://blog.monetha.io
* Or any other similar static pages
* [Known issues](https://github.com/monetha/bug-bounty/issues)
