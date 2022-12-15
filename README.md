# Financial information notifier

<img width="919" alt="image" src="https://user-images.githubusercontent.com/102631336/207750330-49812e33-c03f-48a0-b000-3cb614331531.png">
<img width="918" alt="image" src="https://user-images.githubusercontent.com/102631336/207750305-fa3e2888-78dc-4a3c-bc9a-46349895c21a.png">

<img width="917" alt="image" src="https://user-images.githubusercontent.com/102631336/207750115-4c0c528a-414b-4748-9595-4b9d1b824bf2.png">


Developed a system that sends an email with critical real-time financial information to a list of subscribers.  Two notifiers were developed for: 1) stocks (stocks_notifier) and 2) arbitrage opportunities (arbitrage_notifier).

1) Every day at 8:00 am, an email is sent with a specification of stocks whose last close prices are lower than the 200-day SMA's from user-inputted stock portfolios.

2) Every 5 hours, an email is sent if there is a new arbitrage sports betting opportunity with over 2% guaranteed profit in the user-inputted US state.
