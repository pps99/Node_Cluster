# Node_Cluster

This is a simple application to demonstrate how clustering works in Node.js using the cluster module and Express.

How it works
The application uses the cluster module to fork multiple worker processes, equal to the number of CPU cores available on the machine. Each worker process runs an Express server, allowing the application to handle more concurrent requests by utilizing multiple CPU cores.