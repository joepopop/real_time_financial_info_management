# Financial information notifier

Developed a system that sends an email with critical real-time financial information to a list of subscribers.  Two notifiers were developed for: 1) stocks (stocks_notifier) and 2) arbitrage opportunities (arbitrage_notifier).

1) Every day at 8:00 am, an email is sent with a specification of stocks whose last close prices are lower than the 200-day SMA's from user-inputted stock portfolios.

2) Every 5 hours, an email is sent if there is a new arbitrage sports betting opportunity with over 2% guaranteed profit in the user-inputted US state.
