# Backend systems

- Backend is the logical and data access layer of a software.
- In an overview of backend it can be divided in 3 layer. As the following :
![base](https://user-images.githubusercontent.com/25270515/208840549-efc04775-6881-4ecb-b5a8-e52f9b118da7.png)

- API layer 
- Business Core layer 
- Database layer



## API layer
Api layers works as the interface between the clients and the core backend components. All of the user's interactions, on website or mobile device or any other components is exposed by the API layer.
The communication is bi-directional.

## Business core 

The business core layer contains the code logic of the application. The expected behaviour of an application in any use-case is defined in business layer.

For example in spotify we ask for a new song or a puppy video that we remember, all of these logic are written in this layer.


## Database layer

The database layer contains the actual data.
The data can be of many types.
- structured data -> SQL table data or number and string type of data 
- unstructured data -> multimedia data like, photos or videos or songs. Also known as BLOB data.



## So, how to make a backend ?

This can be taken in the following two ways

1. Build it from scratch 
    In this way all the components and their working with each other is developed by the developers. 

    Pros
    - The backend is curated for a target audience, which makes them better for the specific need which can be speed or security or any other aspect.
    - No dependency issue on 3rd party, and have complete control over what is being built.
    - Use cases : Banks

    Cons
    - Requires more developers and it's a comparatively lengthy process.
    - Not easy to build, and few of the components building from scratch is a convoluted process.

2. Frameworks 
    Frameworks provides a skeleton for the backend, in which we can plug in the components according to our needs. Also framework provides the fundamental components inside it, like the API layer.

    Pros
    - Faster to build compared from scratch.
    - Easier to use, since made robust and not for a specific target audience.

    Cons
    - At times few frameworks can be heavy, since they are made robust.
    - Dependency issues: if the framework holds a bug, it can affect the backend system.


## Few of the languages of backend 

- Legacy 
    - Php, Perl 
- Existing structures 
    - Java, C#
- Newer generation 
    - Node.js, Golang, Rust 

- Rapid prototyping 
    - Python -> Easier to learn and very handy frameworks