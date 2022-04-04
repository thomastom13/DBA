# DBA
update employee set age=round((sysdate-dob)/365) where empno<>0;
