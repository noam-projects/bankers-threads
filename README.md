# bankers-threads
each banker is a thread and they will get a transaction amount and will try to perform it but if they cant because balace has to be above 0, they will wait to be woken up by other threads.
program will end only when all transactions has been made.
deadlock will most likely happen because transactions may not allow balance to be alawys positive because amounts are random.
