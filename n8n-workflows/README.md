## WorkFlow 1
It's first node manual trigger is executed when workflow is executed and it moves to next node and there is an HTTP response node basically and api handler it takes and api link and take method which in this case was get and the api was one from github and it returned an output table containing many APIs.
## WorkFlow 2
So we first made a webhook node which it triggered when the link of this webhhot is hit after that we used a set node to set some values in this case in form of strings, so we can either let auto decide mapping or can treat values as json and respond to webhook is I guess used to ive output of that data that webhook got from, So when webhook is triggered the webhook gets data from set and the respond node return the output of webhook node is json format.
## WorkFLow 3
There is manual trigger node that is triggered on workflow execution and the second is code node that contain the code and execute and return the output of that code
