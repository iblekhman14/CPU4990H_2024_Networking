README is still a WIP


Plan of action:
I plan to spread the project timeline across the full 15 weeks of the semester, most likely into three sections. The first and longest section will analyze high and low-density areas and calculate various factors. I will then manually collect data to verify initial theories and expectations. After that, I will analyze the data and run simulation models to predict whether my proposed changes would help reduce bandwidth congestion. Finally, I will organize all my data and results, draw conclusions, and create the poster. I aim to complete everything except the poster by December 1st of the fall semester, to leave myself ample time for making the poster and wrapping up all other work.

As a note 8/29/2024 around 1-3pm the school had a sitewide partial outage over wifi.

To summarize:
Weeks 1-2: Acquire any necessary hardware or software and form initial hypotheses.
Weeks 3-8: Gather data and complete projections.
Weeks 7-10: Analyze data. Most likely python scripts to scrape mean median and all that.
Weeks 9-12: Conclude, and propose an improved model/suggestions.
Weeks 13-15: Conclude the project, and make the poster.

General Hypothesis: Speeds slow down due to high congestion. Downloads are vulnerable to the whims of an upload test.
Too many students using access points or are there too many students on the internet in general?
Could be a single problem or a combination of multiple problems such as the access point being overloaded, the router overloaded, are we lacking bandwidth for the school?

Campus Network Hardware:
Cpp village uses some variation of the Aruba campus 303/305 models.
Library uses some ..

Tools Used:

Testing methodologies:
Methods that might need to be done to put strain on a network and isolate issues...
- Downloading a large file from a known high-speed server on one device and running a ping and speed test in parallel on another device to measure changes. Similarly, testing this theory with an upload test.

- Running a speed test between two devices locally. Device 1 -> access point -> Device 2. Possibly Device1 -> access point -> Router -> access point -> Device 2.

- Run a multitude of ping tests.
  One such idea is maybe testing using a wired device compared to a wireless to see if it's a wireless access point problem or if the routers a level above are causing it to fail.

- Speak to IT to ask what they might consider to be an issue. Ask about architecture.

Potential Solutions:

- 
