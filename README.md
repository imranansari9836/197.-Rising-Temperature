SELECT W2.ID FROM Weather  AS W1, Weather AS W2
WHERE W2.temperature>W1.temperature 
AND DATEDIFF(W2.recordDate,W1.recordDate)=1;
