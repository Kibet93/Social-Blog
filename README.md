# Social-Blog
A Social Site Where users can post and comment on artlices.


#Recomendations

Preffered storage
	-Azure Blob storage
		-Reason Its higly scalable and can accomodate unstructured Data including Images, Videos..
		-Can hundle extreme situations like influx of users by allocating more resources.
Modeling User Statistics 
		-I would create a table e.g (Followers) that has many relationships 
		and so I can query this table using a single ID
		
Behaviour if activity grows to 200k per day
		- I would advice hosting the aplication in a cloud server 
		this would ensure we have enough resources at all times.
