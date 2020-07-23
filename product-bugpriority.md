# Bug Priority Levels
Bug priority is always up for significant debate and can vary widely from company to company (and product to product). But defining things clearly for your whole team is important to set expectations about how to handle bugs. Here's a simple table of how I have defined bug priority alongside engineering leads in the past.

|Issue Level|Impact to Functionality|Impact to Users|Prioritization Expectations|
|:---------|:-----|:----|:-----|
P0 - Emergency |Impacts availability of entire app/site or core services (API, etc) for entire system/all customers|Applicable to all users or the majority of users|Immediate / 24-hrs
P1 - High|Impacts core functionality localized to a specific area of the app |Applicable to all users or the majority of users|This sprint (mid-sprint addition)
P2 - Medium|Impacts core functionality but localized to a specific area of the app|Applicable to only a subset of users|Next sprint (or a workaround developed which lowers priority to P3)
P2 - Medium|Impacts specific/auxiliary functionality |Applicable to all users or the majority of users|Next sprint 
P3 - Low|Impacts specific/auxiliary functionality or is a P2 with a workaround.|Applicable to only specific users or a small number of users|Prioritized against other product priorities