# belly-button-challenge

This assignment creates an interactive page that uses data from a dataset of bacteria/microbes found in subjects' belly buttons.
OTUs (operational taxonomic units), test subject ID, demographics, and other graphs will be displayed for each test subject selected in the dropdown menu.

From the samples.json page that contains information on each test subject, each individual's demographic data is displayed along with their OTUs in a bubble chart and the top 10 OTUs in a bar chart.
A JS gauge was utilized to visualize the test subject's washing frequency.
Initially, colors for each bubble would have been manually entered, but using the otu_ids to generate a color automatically, thereby avoiding any of the bubbles defaulting to a black color in the event that the otu_ids outnumber the manually entered colors.
The dropdown menu that displays the test subject's ID number can be interacted with and updates the charts if the test subject's ID was changed.