
It is a manufaturing analytical dashboard of a ABC company. This dashboard is viewed in Streamlit platform. Where it has it's own database and tables related to it. It consists of analytics folder for each tables which provides the KPI's. 

Analytics folder consists of : 

    --init.py 
    --production.py 
    --factories.py 
    --machines.py 
    --quality.py 
    --employees.py 
    --trends.py

Dashboard folder consists of : 

    --init.py 
    --apps.py 
    --charts.py 
    --components.py 
    --dashboard_service.py

Includes charts like bar and donut charts fir factory production, machine status, factory production rate, factory defect rate and top performing employees.

Added filtering options like,

    --factories
    --shift
    --machine status (doesn't filters with the date)
    --date (time duration)

It filters the KPI cards, Factory production, Machine status, Monthly defects and Monthly production till now.
