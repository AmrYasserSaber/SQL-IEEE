select  c.company_code,
        founder,
        count(distinct Lead_Manager_code),
        count(distinct Senior_Manager_code),
        count(distinct Manager_code),
        count(distinct employee_code)
from  COMPANY c
LEFT JOIN employee e on e.company_code=c.company_code
group by c.company_code ,founder
order by company_code asc