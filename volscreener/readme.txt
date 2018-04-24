Attached is a prototype for the volscreener.  

The real power is in the  backend, which contains a cloud-database (scalable) and python code (fast and easily adaptable).

The first step is for me to permission your IP address so that you can pull data from the database.  Please go here: www.ip-adress.eu/ and send me your IP address.  Ex: My IP address is 24.131.112.80

Once you are permissioned, this should work out of the box (tested on Excel 2010).

This version contains PYTHON embedded in file, so you do not need to have PYTHON and corresponding libraries installed on your machine.  If this were a webapp, those libraries would just be installed onto the application server.


How volscreener excel file works...

(1) Enter stock ticker in cell B1.

(2) Press Update Button (make sure macros enabled and that I have permissioned your IP address).

	a) Tool pulls entire option chain 
	b) Calculates every 1x1 and 1x2 ratio spread combinations for each maturity (1000+ permutations)
		- can easily add additional strategies
	c) Displays table including calculated fields: including net premium, net premium as pct Spot, max net payout, max net payout ratio, break-even 1, break-even 2.
		- future iterations can show (and chart) optimal strategies based on cost/pnl profile
	d) Toggle button in cell A12 allows you to see or hide filter options.
		- Filter(s) can be added by expanding Filter Options and entering values into gray entry boxes
		- Press update button to apply filter(s)
	e) Applied filters to current output can be seen in cell A16.
	f) Output table starts in cell A18.


Email Darryl.Pinkus@gmail.com with any questions.

Best,
DP  