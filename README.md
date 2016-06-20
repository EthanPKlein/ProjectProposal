# React Project Proposal

When Amber came over to visit us on the client site last week, it was noted that we haven't had an after-hours social event in a while.  We last had a happy hours near the client site, but not everyone is interested in going to be bar before driving home.

My proposal is to create an app where employees can suggest and vote on alternate venues.

Users can suggest:
	- Name of location (ex Bob's Bowling Alley)
	- Type of activity (iex sports)
	- Address of venues
	- URL of venue's website (if available)
	- Date of activity, including hours
	
Users are given three votes to distribute amongst the proposals.  The first vote has a weight of 3 for first choice.  Second vote has a weight of 2, and third vote has a weight of one.

An administrator is able to remove or edit suggestions.  Additionally, they can reject it if the criteria is not acceptable.

Web components required:
- Component to view a list of suggested venues, ordered by current popularity
- Component for user to enter in the required fields for a suggestions (and admin to edit fields)
- Component for users to assign their preferences to each venue
- Coponent for admin to delete or reject suggestions