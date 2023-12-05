# dotnet-interview-questions-answers
#difference between dotnet framework vs dotnet core<br/>
what is middleware ?  how request handle in middleware ? how to register? when to use<br/>
Middleware operate on the level of ASP.NET Core and can act on every single request that comes in to the application.


when to use middleware ?<br/>
if you don't require the context of MVC (let's say you're concerned about flow and execution, like responding to headers some pre-routing mechanism, etc.) then use middlewares.
But if you require the context of MVC and you want to operate against actions then use filters.<br/>

References<br/>https://stackoverflow.com/questions/42582758/asp-net-core-middleware-vs-filters <br/>
what is difference between app.run vs app.use<br/>
security of application<br/>
what method and tools used for security like jwt?<br/>
oops concept<br/>
what is Dependency injection ? type of lifespan<br/>
what is garbage collecter ? when it execute<br/>
filters in dotnet core <br/>

<br/>
angular 
how to pass data from parent to child or child to parent? <br/>
event emitter <br/>
difference between subject behaviour vs subject<br/>
intercepted<br/>
observable<br/>
how to consume webapi in angular<br/>
route guard<br/>

#sql
transaction
stored procedure vs function
join types and detail
cluster index vs non cluster index
scope of CTE
foreign key 
