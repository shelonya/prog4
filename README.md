# prog4
Prompts user for a beginning bank balance and the number of checks written then computs the service charges and directs the report to an output file.

A bank charges a $10.00 a month plus check fees for a commercial account, the check fees are:
  $0.10 each for 1-19 checks
  $0.08 each for 20-39 checks
  $0.06 each for 40-59 checks
  $0.04 each for 60 or more checks 
The bank also charges a low balance fee of $15.00 if the balance of the account falls below $400.00 (before any check fees are applied) 

This C++ program is processed as follows:
1. write the authors personal information to the console screen + two blank lines 
2. write the authors personal infromation to the output file
3. prompt the user for the beginning balance
4. if a negative value is given for the beginning balance,
     a) write an urgent message to the console screen indicating the account is overdrawn
5. do
    a) prompt the user for the number of checks written
    b) if the number of checks less than zero
      i. write a message to the console screen informing user the checks must be zero or more and ask to them to try again
   while the number of checks is less than zero 
 6. calculate the check fee using a multiway branch
 7. if the account balance is less than the minimum allowable monthly balance,
      a) calclate the total monthly fees (standard monthly fee + check fee + low balance fee) 
      b) write the low balance fee along with an appropraite meessage to the banks monthly service fee report (output file)
    otherwise (else)
      a) calculate the total monthly fees (standard monthly fee + check fee)
 8. write the banks monthly service fee report to the output file
 9. write a message to the console screen indicating the name of the file to which te service fee report has been written 
    
