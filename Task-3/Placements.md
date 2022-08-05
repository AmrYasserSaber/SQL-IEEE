select name from Students s , Packages p1 , Friends f ,Packages p2
where 
s.ID = f.ID 
and 
s.ID = p1.ID 
and
 f.friend_ID = p2.ID
and
p2.Salary >p1.Salary
order by p2.Salary;