## TABLE STRUCTURE

<img width="581" alt="Screen Shot 2021-04-30 at 9 10 23 AM" src="https://user-images.githubusercontent.com/74011624/116699711-e60f9680-a993-11eb-9535-f9bac0de05b6.png">

## TABLE TEMPLATE - CTA

```csv
EventTitle,EventNo,TicketNo,PrizeAmount,CardName,CardCode,CardPosition,Name,DrawDay,DrawMonth,DrawYear     
Week 1,1,A-4965515,83,8 of Hearts,eighth,52,Name Name,31,12,2022
```

## TABLE TEMPLATE - 5050

```csv
EventTitle,EventNo,TicketNo,PrizeTypeId,PrizeTitle,PrizeAmount,Name,DrawDay,DrawMonth,DrawYear
Early Bird,1,A-47382915,2,1000,0,John D.,8,7,2021
Grand Prize,1,A-00984627,1,827373,0,Carles M.,30,7,2021
```

Note:
- `PrizeTypeId` 2 : Early Bird
- `PrizeTypeId` 1 : Grand Prize
- If it is an early bird, the `PrizeTitle` will be displayed in the LP. We can leave the `PrizeAmount` as 0.
- If it is a grand prize, the `PrizeAmount` will be displayed in the LP. We can leave the `PrizeTitle` as "Jackpot"
- Make sure to chronologically order the events, from the earliest Early Bird, to the latest Early Bird, to the Grand Prize.
- If the early birds or grand prize are from the same event, ensure the `EventTitle` and `EventNo` are the same for these winners.

