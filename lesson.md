## Brief

### Preparation

Write about any preparations needed for the lesson, such as tools, installations, prior-knowledge, etcs.

### Lesson Overview

Write about how instructors can brief the students at the start of the lesson. It is good to guide students through what is going to be covered and the outcome. Setting expectations.

---

## Part 1 - Cloud Native Apps Concepts


The cloud-native application is the concept of creating apps that take advantage of distributed computing to exploit the resiliency, scale, flexibility, and elasticity the cloud delivery models offer. These applications are run and hosted in the cloud. It benefits businesses with independent services, portable containers, and is packaged as self-contained. It is designed mainly for the cloud.


### Key principles of cloud-native architecture
Have a look at some of the key principles of cloud-native architecture.

**Microservices**

Microservices are considered an architectural strategy capable of managing complex applications simply. They are highly capable of communicating with others which is possible with a language-agnostic API since it is an independent process. Each service is confined and focuses on completing the scheduled tasks on time.

Microservice architectures are well known for their modern application-building strategy that allows you to reuse and redesign specific areas based on your requirements. Enterprises can adopt microservices for easy deployment, scaling, and development and support technological diversity.

**Containerization**

Containers are now mainstream to developers and enterprises for building cloud-native applications. Linux namespaces are used to handle the space between network stacks, processes, and file systems. Containers are highly secured partitions that perform best by following the namespace method. Each container runs one or more multiple Linux processes and is supported by Linux Kernel on the host.

It works like virtual machines (VMs) do and is highly flexible for running operations smoothly. VMs are only installed with the help of a full operating system, whereas containers support apps using the packaging software. Developers and enterprises efficiently manage their applications with a packaging approach. Containers have less weight than VMs and require less maintenance and fewer resources to process the cloud-native apps.

Most enterprises prefer containers for faster accessibility, higher portability, and easy deployment.

**CI/CD**

Continuous integration (CI) assists in automating the integration of new code in a repository so that multiple contributors can have access to working on the same project simultaneously. CI tools are capable enough to run automated tests and verify that new bugs are not present in the code. It also prohibits overwriting other developers’ work and automatically creates new builds once the verification process is completed.

In addition, it uses these methodologies in cloud-native software development. Cloud-native CI tools and processes allow a team’s DevOps experts to work together on a similar codebase and update the software frequently without compromising the quality. Continuous delivery (CD) helps deploy new code builds for production and testing processes. Besides all that, the software release cycle is streamlined.

The CD methodology for cloud-native development benefits the cloud-based infrastructure by providing microservices. Multiple teams can work simultaneously on different modules since each microservice is developed, tested, and deployed independently. It has wide adoption with developers and enterprises for managing rapid and agile delivery of complex cloud-native apps.

**DevOps**

The cloud-native approach is DevOps‘ best practice to automate the process between operations and software development teams. It is bringing innovation to the global market at a rapid pace and helping enterprises to transform along with DevOps to align the processes and technologies for boosting business efficiency and productivity.

The collaboration of DevOps with the CI/CD paradigm has benefitted developers in iterating software to improve deployment time and reduce errors. From an enterprise perspective, a cloud-native approach with DevOps for software development helps maximize agility via continuous deployment and allows apps to scale up without needing further changes.


### 3 Benefits of cloud-native applications

What makes cloud-native development so valuable? The following three qualities are what have savvy companies paying attention:

1. Adaptability

Cloud-native applications can change with the needs of the business without creating dependencies that lock customers into a particular version of the software.

For example, if a company wants to make an application available on mobile devices, it can build the mobile front end and use APIs to access data on the server without modifying any code on the back end. This loose coupling makes it possible to make changes to either application without breaking it.

2. Scalability

Cloud-native applications use software-defined infrastructure to reduce or eliminate hardware dependency. This approach adds commodity servers for horizontal scalability rather than requiring the addition of more expensive processors, storage, and memory to existing servers. Horizontal scalability is what makes massive cloud services like Amazon and Facebook possible.

3. Portability

Using containers, developers can write applications that run on everything from a smartphone to a mainframe without changing the code. With the growing popularity of “edge computing,” a distributed processing architecture that pushes automated decisions to the far reaches of the network, it’s ideal to have the ability to deploy applications wherever they’re needed.


### 4 examples of cloud-native applications

1. Software Containers

Software containers are portable, integrated operating environments encompassing an application and all the software components needed to run it.

Containers have become a wildly popular alternative to complex virtual machines because they’re:
- small, typically measured in megabytes or less
- quick to deploy
- reusable and portable

Once you write an application in a container, you can move it to any platform that supports containers (which is most of them), and it will run without a hitch. Your application isn’t bound to a single cloud platform — it can run on any device with enough resources to support it, from a laptop to a supercomputer.

2. Microservices

Microservices are loosely coupled software services that can be strung together to create an application. This saves developers from having to reinvent the wheel and makes applications flexible and extendable. Applications composed of microservices are pieced together like Lego blocks with minimal custom coding, facilitating faster and more reliable development. New services can be swapped in or added without extensive integration testing.

3. Software-defined Infrastructure

Replacing switches, dials, and plugs with software almost entirely virtualizes hardware functionality. This makes it easy to scale capacity up and down, reallocate resources, and start and stop services automatically through software. Cloud-native applications assume that the underlying infrastructure is fluid and adaptable to their needs.

4. Application Program Interfaces (APIs)

APIs are software connectors that expose functionality that other software can use. They make it easy to extend or customize applications without touching the underlying code, which is a good practice to avoid in general. APIs also enable developers to tap into rich functionality in other applications.

A good example of an API-enabled application is Google Maps. With Google Maps, a developer of a real estate application can integrate mapping functionality from Google into its program by requesting geographic information using APIs. Without needing to build map functionality from scratch or install an application on their server, imagine how much time the developer can save.

---

## Part 2 - Common Cloud Native Apps Knowledge

### API

![image](https://user-images.githubusercontent.com/106639884/207229762-73cd8f2b-a10b-4266-9be5-a28d3af10efb.png)


### Logging

A microservices-based application might have several services running and communicating amongst themselves. Things get complicated when one or more services fail, and you need to know which one failed and why. It’s also essential that you’re able to comprehend the whole request flow — which services were invoked, how many times, and in what order.

To answer these questions, you should have meaningful logs available and a unique Id to correlate requests. You should have a proper way to track errors that might span several microservices. Moreover, the complexities of monitoring and logging grow exponentially when the business logic of your applications spans across several microservices.

| There will be a chapter specifically to cover about logging.

### Caching

**Lets spend 5-10 mins to read an article about caching here: https://www.linkedin.com/pulse/caching-microservice-highly-effective-way-maximize-performance-rao**


One of the example of in-memory data structure store / caching is Redis.

**Redis**

Redis is an open source, in-memory, key-value data store most commonly used as a primary database, cache, message broker, and queue. Redis delivers sub-millisecond response times, enabling fast and powerful real-time applications in industries such as gaming, fintech, ad-tech, social media, healthcare, and IoT.

Redis is the most-loved database by developers for five years running. Developers love Redis because of its ease of use, performance, and scalability. There is a Redis client available for use in every popular modern programming language. This, coupled with the performance benefits, makes Redis the most popular choice for caching, session management, gaming, fraud detection, leaderboards, real-time analytics, geospatial indexing, ride-sharing, social media, and streaming applications.

**Learner install redis locally**

---

## Part 3 - Installation - Node, NPM, NVM, Docker

Install these on your local machine:
- https://nodejs.org/en/download/
- https://docs.npmjs.com/downloading-and-installing-node-js-and-npm
- https://github.com/nvm-sh/nvm


### Your first node application

```npm init```

Instructor explain about the project structure including `package.json` and `node_modules`.

Add this to your project `index.js`

```
const http = require(‘http’);
const hostname = ‘localhost’;
const port = 3000;
const server = http.createServer((req, res) => {
 console.log(req.headers);
 res.statusCode = 200;
 res.end(‘<html><body><h1>Hello, World!</h1></body></html>’);
})
server.listen(port, hostname);
```

Run the project:

```node index.js```

## Part 4 - Installation - Docker

Install these on your local machine:
- https://docs.docker.com/get-docker/

**Learners need to complete the NPM, Node and Docker locally, so that on the next module, there is no issue because we will focus to code and no more installation process**
