# Patient-Database-Management-System

## Business Case Study: Peaceful Haven

A residential care home company has decided to set up a scheme to actively engage visitors in the care of their residents, in order to boost support to their elderly patients and make best use of their care staff whose numbers have been gradually declining because of Covid related issues. The basic premise is that visiting relatives can help with staff shortages by doing some of the work normally allocated to staff, eg serving meals and helping with leisure activities. This arrangement seems to have the backing of the residents and their families who appreciate that the care home is struggling to cope with the ever-increasing staff shortages.

All residents are now permitted one visitor who is the designated ‘primary visiting carer’ for that resident and can visit at any time, along with up to three other named visitors, whose visits are restricted to specific days of the week of their choosing. Basic details need to be recorded for each visitor, including to what level they have been vaccinated against Covid. The care home is insistent that for security reasons visitors can only visit on the days they have specified, and as a check, a list of the day’s ‘permitted visitors’ is kept in reception along with details of the person they are visiting.

Any registered visitor may volunteer to help with running leisure activities. This is being encouraged in order to expand the range of activities on offer and to cut down on external paid assistants who are employed to run them. The care home manager is appealing to the altruistic nature of relatives, but also thinks that she could incentivise them to help by allocating some kind of ‘bonus’ or small reward to the most ‘helpful’ visitor or to their related resident.

Activities are varied and range from card games to karate for the over 80’s. Residents are encouraged to try as many different things as they can to keep themselves mentally and physically active and to pursue each activity for at least a month. At the end of the month, they are asked to indicate whether they liked or disliked the activities, and this information is recorded so that the care home can offer something new if the resident was not happy with his/her choice.

A check needs to be kept on the expenses incurred in running these activities as most involve some kind of outgoings in addition to any hired help. The care home has worked out the average cost of each activity on a ‘per head/per month’ basis and needs to monitor the number of residents taking up each activity, to stay within its ‘entertainment’ budget.

The care home director has asked you to think about designing a database to help with tracking all this information. This is an extract below from an interview with her, where she provides her initial thoughts:

“We currently have 20 homes, but initially I’d really like to try this scheme out at our ‘Peaceful Haven’ home which is the largest. It could be a game changer, who knows? I’ve spoken to many of the visitors, and they’ve said they would like to help out - and to keep dementia at bay, our residents need to be kept busy. Some relatives have expressed interesting in running activities that we don’t currently offer, so I think we would be able to expand our current range and provide something for everyone. Ideally, I’d like to make one person responsible for a particular activity – a kind of ‘activity leader’, but he or she wouldn’t be required to attend every session that is run for that activity, just coordinate it in a general way. We need to know which resident is signed up for which monthly activity, and we also need to maintain a schedule of the dates that these activities are being run, and which visitors can help out at each session. There may be occasions where we get no volunteers and we might have to ring others to come in, ie those who have said they are interested in helping out with that activity, or we may just cancel the session if nobody can do it. We’ve decided that all residents who have signed up for an activity will attend all the scheduled sessions for at least a month before deciding whether or not they want to change to something else. In the past we’ve found that residents who stick at something actually grow to like it.

I feel that we could do more with the data that we collect, for example by working out some kind of ‘compatibility score’ between all residents (essentially the number of activities which a pair of residents both like). Those residents with the highest compatibility scores could then be ‘paired up’ so that they could keep themselves amused and enjoy each other’s company, thereby demanding less time from the care home staff.

Anyhow, I hope you can find some decent database developer who can put this all together and provide us with some useful reports that can help our organisation run more efficiently. Obviously, it would be useful to see which are the most popular activities over time and how many sessions we have managed to staff with volunteers, who is an ‘award winning ‘volunteer etc. It will probably make it easier to check that we haven’t overspent in any area, and we could have a look at the individual history of a specific resident. I guess it would be easier to pick out visitor patterns and so on. I haven’t really thought much more about what a database system might generate, but I hope your developer can help me come up with some other useful and innovative ideas. I’ve been told that we should be doing more with our data to get a competitive edge and to be more efficient in these tough times. Hopefully the database will help with this.”

## ASSUMPTIONS/BUSINESS RULES:
Here you need to state any rules or assumptions that affect the ER diagram design.

1. All residents are permitted one visitor who is the designated ‘primary visiting carer’ for that
resident. They can visit the resident at any time.
2. All residents are also permitted up to three other named visitors, whose visits are restricted to
specific days of the week of their choosing.
3. The visiting time is in the afternoon, from 3pm to 5pm.
4. The age limit for all visitors is between 18 years and 60 years.
5. Any registered visitor may volunteer to help with running leisure activities.
6. Any volunteer can be made responsible for a particular leisure activity, like an activity leader.
7. The activity leader isn’t required to attend every session that is run for a specific leisure
activity. They only need to coordinate it in a general way.
8. All residents who have signed up for an activity will attend all the scheduled sessions for at
least a month before deciding whether or not they want to change to something else.
9. The care home manager has hired some extra volunteers/helpers to help run the leisure
activity sessions when there are no volunteers available.
10. These extra helpers are people who have said they are interested in helping out with a leisure
activity.
11. A volunteer can help with running leisure activities and serve meals.
12. A volunteer can serve a meal to a resident on specific meal timings.



-- Note: This is an academic project associated with BSc (Honours) Computer Science of UWL. --
