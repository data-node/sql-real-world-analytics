# SQL Real World Analytics

A repository that collects challenges that I face when solving problems with SQL. It's a personal notes keeping. Feel free to share your opinion.

> [!TIP]
> It doesn't really matter which database provider you use to solve problems. I like this quote by "Thomas Sowell"     
> There are no solutions, there are only trade-offs. […] But you try to get the best trade-off you can get, and that’s all you can hope for.

#### To-Do
- [ ] How to create a website to manage this? This is not a priority right now.
- [ ] How to organize the content? 

#### Scratchpad
- Add the drafts problem
- Add the top voice problem
- To organize the content I think each problem can have it's own folder and an accompanying Readme file to walk through. I think the necessary files to begin cooking would be schema file, seed data file, problem statement and solution walk through. To make it simpler in the future I think we can associate each problem with a unique id and have a docker instance spin up for the database of my choice. Have a simple UI to choose a problem and have the backend take care of creating a fresh database, seeding the data and you can use a database client to solve a problem. This is literally leetcode style SQL but a local setup 😂 Maybe, I can build my own LC 🫢 Hmmmm now I am curious how is this solution designed? I am not a web dev guy but I think from the front-end you submit the SQL code to a queue and then from there a Lambda or Cloudflare worker picks it up passes it to a database (Kubernetes cluster), collects the result and stores the result for a user in S3 or DynamoDB and for that job id if the solution or error is ready in DynamoDB then we show the user that result set. 
