# nx_microservices_example
 
This is an example of an nx workspace that can be used for the development of related microservices and other software products. 
It has some NestJS-based microservices in the `microservices` folder. 


NX was designed for, and works best with Typescript-based applications, but generally can work with languages outside of JS. 
Javascript-based backend applications generally need to be linted, tested and then bundled before being used in production. 

NX Ensures 
- A single workspace for microservices where they can share testing, linting and bundling configurations. 
- We can create and develop shared JS libraries in the same workspace, and include them in any applications we want. 
- We can create CI/CD pipelines for automatically moving approved code into staging, testing or development environments
- We can create build configurations for creating docker containers comprised of any combination of services we please
- We can use generators for scaffolding popular projects, or create our own generators to scaffold projects to a certain standard. 
