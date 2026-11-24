# naomiface keepalive

Pings https://naomiface.co/api/awake every five minutes so the free Render web service does not spin down. The route does not touch the database.

Render's free allowance is 750 instance hours per workspace per month, which is about one service kept awake all month.
