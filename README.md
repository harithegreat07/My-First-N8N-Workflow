# My-First-N8N-Workflow
This is my first n8n workflow which I created just now during my quarterly holidays. It is quite simple and easy. Hoping to create more advanced and helpful agents in the upcoming days.

## What does this automation do?
1. This is an Automation which starts with a trigger node which is a form submission by our client.
2. The next node is a logical node (ie. Router) which catogerise the client based on the budget they selected (which is an option in the form)
3. The router catogerise the clients in one of the following basket, which are "High Budget", "Medium Budget" and "Low Budget"
4. In the next step, the Gmail node sends a message to the owner of this form (me) about the new lead we got.
5. The next one is also an Gmail node, which sends a Thank you message to the person who submitted the form (client).

I know that this Readme page lacks lots of nuances and important details about the workflow but since this is the first workflow I created, I will try to improve the details and clarity slowly but steadily.
