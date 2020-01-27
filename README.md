# lendico
Steps to clone
-> mkdir lendico
-> cd lendico
-> git init
-> git clone https://github.com/sivasyam/lendico.git
-> cd lendico

Import the project to IntelliJ (from existing sources)
-> Select File -> New -> projects from existing sources
-> Select the project location from the explorer

Import the project from Git
-> select File -> New -> import projects from Version Control -> Git
-> Enter "git clone https://github.com/sivasyam/lendico.git” in URL section of Clone Repository window
-> Choose Directory
-> Click on Clone (if you already connected to Git) or else Login to Git and follow the same


To Run project 
go to src/main/java/de/lendico in IntelliJ and right click on Application.java and select Run 'Application.main()’

Sample Request
{
"loanAmount": "5000",
"nominalRate": "5.0",
"duration": 24,
"startDate": "2018-01-01T00:00:01Z"
}

Sample Response

{
    "loanResponseList": [
        {
            "borrowerPaymentAmount": "219.35",
            "date": "2018-01-01T00:00:01Z",
            "initialOutstandingPrincipal": "5000",
            "interest": "20.83",
            "principal": "198.52",
            "remainingOutstandingPrincipal": "4801.47"
        },
        {
            "borrowerPaymentAmount": "219.35",
            "date": "2018-02-01T01:00:01Z",
            "initialOutstandingPrincipal": "5000",
            "interest": "20",
            "principal": "199.35",
            "remainingOutstandingPrincipal": "4602.12"
        },
        {
            "borrowerPaymentAmount": "219.35",
            "date": "2018-03-01T02:00:01Z",
            "initialOutstandingPrincipal": "5000",
            "interest": "19.17",
            "principal": "200.18",
            "remainingOutstandingPrincipal": "4401.94"
        },
        {
            "borrowerPaymentAmount": "219.35",
            "date": "2018-04-01T03:00:01+0200",
            "initialOutstandingPrincipal": "5000",
            "interest": "18.34",
            "principal": "201.01",
            "remainingOutstandingPrincipal": "4200.92"
        },
        {
            "borrowerPaymentAmount": "219.35",
            "date": "2018-05-01T03:00:01+0200",
            "initialOutstandingPrincipal": "5000",
            "interest": "17.5",
            "principal": "201.85",
            "remainingOutstandingPrincipal": "3999.07"
        },
        {
            "borrowerPaymentAmount": "219.35",
            "date": "2018-06-01T03:00:01+0200",
            "initialOutstandingPrincipal": "5000",
            "interest": "16.66",
            "principal": "202.69",
            "remainingOutstandingPrincipal": "3796.38"
        },
        {
            "borrowerPaymentAmount": "219.35",
            "date": "2018-07-01T03:00:01+0200",
            "initialOutstandingPrincipal": "5000",
            "interest": "15.81",
            "principal": "203.53",
            "remainingOutstandingPrincipal": "3592.84"
        },
        {
            "borrowerPaymentAmount": "219.35",
            "date": "2018-08-01T03:00:01+0200",
            "initialOutstandingPrincipal": "5000",
            "interest": "14.97",
            "principal": "204.38",
            "remainingOutstandingPrincipal": "3388.45"
        },
        {
            "borrowerPaymentAmount": "219.35",
            "date": "2018-09-01T03:00:01+0200",
            "initialOutstandingPrincipal": "5000",
            "interest": "14.11",
            "principal": "205.23",
            "remainingOutstandingPrincipal": "3183.21"
        },
        {
            "borrowerPaymentAmount": "219.35",
            "date": "2018-10-01T03:00:01+0200",
            "initialOutstandingPrincipal": "5000",
            "interest": "13.26",
            "principal": "206.09",
            "remainingOutstandingPrincipal": "2977.12"
        },
        {
            "borrowerPaymentAmount": "219.35",
            "date": "2018-11-01T03:00:01Z",
            "initialOutstandingPrincipal": "5000",
            "interest": "12.4",
            "principal": "206.95",
            "remainingOutstandingPrincipal": "2770.17"
        },
        {
            "borrowerPaymentAmount": "219.35",
            "date": "2018-12-01T04:00:01Z",
            "initialOutstandingPrincipal": "5000",
            "interest": "11.54",
            "principal": "207.81",
            "remainingOutstandingPrincipal": "2562.35"
        },
        {
            "borrowerPaymentAmount": "219.35",
            "date": "2019-01-01T05:00:01Z",
            "initialOutstandingPrincipal": "5000",
            "interest": "10.67",
            "principal": "208.68",
            "remainingOutstandingPrincipal": "2353.67"
        },
        {
            "borrowerPaymentAmount": "219.35",
            "date": "2019-02-01T06:00:01Z",
            "initialOutstandingPrincipal": "5000",
            "interest": "9.8",
            "principal": "209.54",
            "remainingOutstandingPrincipal": "2144.12"
        },
        {
            "borrowerPaymentAmount": "219.35",
            "date": "2019-03-01T07:00:01Z",
            "initialOutstandingPrincipal": "5000",
            "interest": "8.93",
            "principal": "210.42",
            "remainingOutstandingPrincipal": "1933.7"
        },
        {
            "borrowerPaymentAmount": "219.35",
            "date": "2019-04-01T08:00:01+0200",
            "initialOutstandingPrincipal": "5000",
            "interest": "8.05",
            "principal": "211.29",
            "remainingOutstandingPrincipal": "1722.4"
        },
        {
            "borrowerPaymentAmount": "219.35",
            "date": "2019-05-01T08:00:01+0200",
            "initialOutstandingPrincipal": "5000",
            "interest": "7.17",
            "principal": "212.18",
            "remainingOutstandingPrincipal": "1510.22"
        },
        {
            "borrowerPaymentAmount": "219.35",
            "date": "2019-06-01T08:00:01+0200",
            "initialOutstandingPrincipal": "5000",
            "interest": "6.29",
            "principal": "213.06",
            "remainingOutstandingPrincipal": "1297.15"
        },
        {
            "borrowerPaymentAmount": "219.35",
            "date": "2019-07-01T08:00:01+0200",
            "initialOutstandingPrincipal": "5000",
            "interest": "5.4",
            "principal": "213.95",
            "remainingOutstandingPrincipal": "1083.2"
        },
        {
            "borrowerPaymentAmount": "219.35",
            "date": "2019-08-01T08:00:01+0200",
            "initialOutstandingPrincipal": "5000",
            "interest": "4.51",
            "principal": "214.84",
            "remainingOutstandingPrincipal": "868.36"
        },
        {
            "borrowerPaymentAmount": "219.35",
            "date": "2019-09-01T08:00:01+0200",
            "initialOutstandingPrincipal": "5000",
            "interest": "3.61",
            "principal": "215.73",
            "remainingOutstandingPrincipal": "652.62"
        },
        {
            "borrowerPaymentAmount": "219.35",
            "date": "2019-10-01T08:00:01+0200",
            "initialOutstandingPrincipal": "5000",
            "interest": "2.71",
            "principal": "216.63",
            "remainingOutstandingPrincipal": "435.98"
        },
        {
            "borrowerPaymentAmount": "219.35",
            "date": "2019-11-01T08:00:01Z",
            "initialOutstandingPrincipal": "5000",
            "interest": "1.81",
            "principal": "217.54",
            "remainingOutstandingPrincipal": "218.44"
        },
        {
            "borrowerPaymentAmount": "219.35",
            "date": "2019-12-01T09:00:01Z",
            "initialOutstandingPrincipal": "5000",
            "interest": "0.91",
            "principal": "218.44",
            "remainingOutstandingPrincipal": "0"
        }
    ]
}

Note: In the test document the response provided as 
{
	[
		{
            "borrowerPaymentAmount": "219.35",
            "date": "2019-12-01T09:00:01Z",
            "initialOutstandingPrincipal": "5000",
            "interest": "0.91",
            "principal": "218.44",
            "remainingOutstandingPrincipal": "0"
        }
	]

}
 But the above is not valid as it should be 

{
	"loanResponseList": [{
		"borrowerPaymentAmount": "219.35",
		"date": "2018-01-01T00:00:01Z",
		"initialOutstandingPrincipal": "5000",
		"interest": "20.83",
		"principal": "198.52",
		"remainingOutstandingPrincipal": "4801.47"
	}]
}
